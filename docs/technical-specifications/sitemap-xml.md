# Sitemap XML
There are specific XML sitemaps for :

- **Agencies** : accessible from ../agences.xml
- **Products** : accessible from ../articles.xml
- **Categories** : accessible from ../category.xml
- **Drupal content** : accessible from ../content.xml
- <del>**Category + Brand pages** : accessible from ../category-brands.xml</del>

Sitemaps are generated on :

- Agencies : DSL side (/impulse-agency-query/api/v1/agencies/sitemap)
- Products : DSL side (impulse-article-query/api/v1/articles/sitemap) 
- Categories : DSL side (/impulse-menu-query/api/v1/menu/sitemap)
- Drupal content : generated on Drupal side. It regroups all the Drupal content (nodes), as well as “static” pages such as Conseils listings, registration, login, forms…. (all pages which are not Agencies / Products / Categories, except my Account section)
- <del>Category + Brand pages : generated on Drupal side. It regroups all nodes from Category + Brand CT. See [related section](https://docs.google.com/document/d/1ZMDciVlRPyAaNvmR3_gHF8ZypcmgCjxe1BOHaeRr2qk/edit#heading=h.z7ataqr1gh3h) for details.</del> 

**!!** Regarding ESDB content, it should be added to sitemap ONLY if ***$settings['sg\_common.esdb\_features']*** is enabled. If enabled, next content must be added to **Drupal content** sitemap : 

- ESDB Home Page
- ESDB Styles & Solutions detail page
- ESDB Style nodes
- ESDB Solution nodes
- ESDB Conseil Landing page
- ESDB Conseil nodes

All those sitemaps must be available via a sitemap index (./sitemap\_index.xml). This index must be referenced in robots.txt. 

Each sitemap XML must be available (https) with ZIP format (content-encoding : gzip / content-type : application.xml). Extension to use is .gz

Gzip generation : 

- Agencies : on Drupal side, using response from service
- Products : on Service side (service response allows to download the Gzip)
- Categories : on Drupal side, using response from service
- Drupal content : on Drupal side

For Articles, 1st step is to retrieve file(s) name(s) using ***/articles/sitemaps***, then retrieve GZIP(s) by passing file(s) name(s) to the dedicated service (***/articles/sitemap/{filename}/download***) : 

**Step 1 :** 

<http://ingress.ibm.ppr.docker4sg.saint-gobain.net:12090/impulse-article-query/api/v1/articles/sitemaps?websiteId=cedeo>

```
[
 {
   "name": "articles_sitemap_2018_09_20_13_06_25_cedeo_8393529855933241036.zip",
   "lastModified": "2018-09-20T13:06:25.735+0000"
 }
]
```

**Step 2 :** 

<http://ingress.ibm.ppr.docker4sg.saint-gobain.net:12090/impulse-article-query/api/v1/articles/sitemap/articles_sitemap_2018_09_20_13_06_25_cedeo_8393529855933241036.zip/download?websiteId=cedeo>
