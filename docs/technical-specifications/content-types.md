# **Content Types**
## **Marque (brand)**
This content type is used on Bands landing and product detailed pages. Rule for url 
### Settings

| Published                   | No                                       |
| --------------------------- | ---------------------------------------- |
| Promoted                    | No                                       |
| Expected URL alias          | /les-marques/\[node:title\]              |
| Breadcrumbs                 | \[site:name\] > Marques > \[node:title\] |
| Meta-title                  | Configurable from back-office            |
| Meta-description            | Configurable from back-office            |
| Translate Interface Context | Marques                                  |

### Fields

|Name                 |Label (fr)        |Machine name                  |Type                          |Description/Options                                                                                                                                                                                                                 |Help Text (fr)                                                                                                                                                 |
|---------------------|------------------|------------------------------|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Principal            |                  |                              |                              |                                                                                                                                                                                                                                    |                                                                                                                                                               |
|Title*               |Titre             |As provided                   |                              |                                                                                                                                                                                                                                    |                                                                                                                                                               |
|Brand id*            |ID de la Marque   |field_brand_id                |Text field                    |                                                                                                                                                                                                                                    |Renseignez l’ID de la Marque. Il est utilisé pour faire le lien entre la fiche Produit et sa Marque, afin d’afficher le logo de la Marque sur la fiche Produit.|
|Top Brand            |Top Marque        |field_brand_top               |Checkbox                      |                                                                                                                                                                                                                                    |Cochez la checkbox si la Marque est une Top Marque (utilisé en tant que filtre sur la page Liste Marques).                                                     |
|Promoted             |Promotion         |field_brand_promo             |Checkbox                      |                                                                                                                                                                                                                                    |Cochez la checkbox si la Marque a des produits en promotion (utilisé en tant que filtre sur la page Liste Marques).                                            |
|Categories           |Catégorie(s)      |field_brand_category          |Remote (category)             |Multiple                                                                                                                                                                                                                            |Sélectionnez la ou les catégories de la Marque (utilisée(s) en tant que filtre(s) sur la page Liste Marques).                                                  |
|Logo*                |Logo              |field_brand_logo              |Image                         |                                                                                                                                                                                                                                    |Renseignez le logo de la Marque.                                                                                                                               |
|Short description*   |Description courte|field_brand_description_short |Plain text                    |                                                                                                                                                                                                                                    |Renseignez la description courte, affichée en haut de page.                                                                                                    |
|Seo                  |Description longue|field_brand_seo               |Text area (decorated text)    |                                                                                                                                                                                                                                    |Si renseignée, la description longue sera affiché en bas de page.                                                                                              |
|Link                 |Lien              |field_brand_link              |Link                          |With option “Open in a new tab”.                                                                                                                                                                                                    |Renseignez le label et l’URL du site de la Marque.                                                                                                             |
|Highlighted products |Mises en avant    |field_brand_product           |Remote (product)              |                                                                                                                                                                                                                                    |Définissez les produits mis en avant.                                                                                                                          |
|Content              |Encart Marketing 1|                              |                              |                                                                                                                                                                                                                                    |                                                                                                                                                               |
|Marketing block 1    |Encart Marketing 1|field_brand_mb1               |Paragraph (category_marketing)|Multi-value                                                                                                                                                                                                                         |Si renseigné, cet encart Marketing sera affiché au dessus de la liste des produits.                                                                            |
|Content              |Encart Marketing 2|                              |                              |                                                                                                                                                                                                                                    |                                                                                                                                                               |
|Marketing block 2    |Encart Marketing 2|field_brand_mb2               |Paragraph (category_marketing)|Multi-value                                                                                                                                                                                                                         |Si renseigné, cet encart Marketing sera affiché en dessous de la liste des produits.                                                                           |
|Similar Brands       |Marques similaires|                              |                              |                                                                                                                                                                                                                                    |                                                                                                                                                               |
|Brands               |Marques           |field_brand_similar           |Reference (brand)             |Multiple                                                                                                                                                                                                                            |Sélectionnez les Marques à afficher dans le bloc.                                                                                                              |
|Premium version      |Version premium   |                              |                              |                                                                                                                                                                                                                                    |                                                                                                                                                               |
|Hide Top block       |Cacher le bloc    |field_brand_hide_top_block    |Boolean                       |                                                                                                                                                                                                                                    |Cochez cette case si vous souhaitez cacher le bloc affiché en haut de la page marque standard.                                                                 |
|Version premium lines|Eléments premium  |field_brand_version_prem_lines|Paragraph                     |Multiple &#124; Reference:</br> Paragraph</br> (premium_brand_page_banner)</br> Paragraph</br> (premium_brand_page_wysiwyg)</br> Paragraph</br> (premium_brand_page_slider)</br> Paragraph</br> (univers_block)</br> Paragraph</br> (premium_promoted_products)</br> Paragraph</br> (full_html_block)|Choisissez les éléments à ajouter à la version premium de la page.                                                                                             |

## **Simple page (page)**
This content type is used to build simple pages like about us with WYSIWYG.

French label : Page simple
### Settings

| Published        | No                            |
| ---------------- | ----------------------------- |
| Promoted         | No                            |
| Meta-title       | Configurable from back-office |
| Meta-description | Configurable from back-office |

### Fields

| Name               | Label (fr)             | Machine name                 | Type                      | Description/Options | Help Text (fr)                                                                                                                       |
| ------------------ | ---------------------- | ---------------------------- | ------------------------- | ------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Principal          |                        |                              |                           |                     |                                                                                                                                      |
| Title\*            | Titre                  | As provided                  |                           |                     |                                                                                                                                      |
| Content\*          | Contenu                | field\_page\_content         | Text area (Filtered HTML) |                     | Renseignez le contenu de la page.                                                                                                    |
| Free HTML          | Contenu HTML libre     | field\_page\_freehtml        | Text area | Plain text    |                     | Utilisez ce champ pour ajouter votre propre code HTML.                                                                               |
| Visibilité         | Visibilité             | field\_role\_access          | Roles Access              |                     | Multiple                                                                                                                             |
| Search             | Recherche              |                              | Tab                       |                     |                                                                                                                                      |
| Search Description | Description recherche  | field\_csearch\_descr        | Textarea|Plain Text       |                     | Renseignez la description affichée sur la page de Résultats de recherche.                                                            |
| Publish            | Publication            |                              | Tab                       |                     |                                                                                                                                      |
| Publish Date       | Date de publication    | field\_publish\_date         | Date                      |                     | Renseignez la date à laquelle le contenu sera automatiquement publié.                                                                |
| Publish time       | Heure de publication   | field\_publish\_date\_time   | Time                      |                     | Renseignez l’heure à partir de laquelle le contenu sera automatiquement publié. Par défaut le champ heure est vide et égale à 00h00. |
| Unpublish Date     | Date de dépublication  | field\_unpublish\_date       | Date                      |                     | Renseignez la date à laquelle le contenu sera automatiquement dépublié.                                                              |
| Unpublish time     | Heure de dépublication | field\_unpublish\_date\_time | Time                      |                     | Renseignez l’heure à partir de laquelle le contenu sera automatiquement dépubliqué.                                                  |

## **Intermediation (intermediation)**
This content type is used to build intermediation pages.

French label : Page Intermediation
### Settings

| Published | No |
| --------- | -- |
| Promoted  | No |

### Fields

|Name                    |Label (fr)                  |Machine name                    |Type                           |Description/Options            |Help Text (fr)                                                                                                |
|------------------------|----------------------------|--------------------------------|-------------------------------|-------------------------------|--------------------------------------------------------------------------------------------------------------|
|Principal               |Principal                   |                                |                               |                               |                                                                                                              |
|Title*                  |Titre                       |As provided                     |                               |                               |                                                                                                              |
|Subtitle                |Sous titre                  |field_intermediation_subtitle   |Text field                     |                               |                                                                                                              |
|Tile Image*             |Image tuile                 |field_intermediation_image      |Image                          |                               |Image affichée lorsque la page est appelée sur une autre page de contenu ou la landing intermédiation         |
|Background image*       |Image Header                |field_intermediation_image_bg   |Image                          |                               |Image affichée dans le Header de la page                                                                      |
|Partner text            |Texte paternaire            |field_intermediation_partner    |Text field                     |                               |Texte affiché au dessus du logo partenaire dans le header                                                     |
|Partner logo            |Log partenaire              |field_intermediation_image_partn|Image                          |                               |Logo affiché dans le Header                                                                                   |
|Hide in dropdown list   |Masquer sur la tuile parente|field_intermediation_dropdown   |Single on/off checkbox         |                               |Si la checkbox est activée, la page courante ne sera pas affichée dans la liste déroulante de la page parente.|
|Intermediation reference|Tuiles référencées          |                                |                               |Tab                            |                                                                                                              |
|Intermediation          |Ajouter une tuiles          |field_intermediation_reference  |Reference (node:intermediation)|Widget &#124; Autocomplete, Multiple|Saisissez le titre d’un contenu à ajouter sur la page.                                                        |
|Parameters              |Paramètres                  |                                |                               |                               |Paramètres à transmettre au formulaire partenaire                                                             |
|Fid1                    |Fid1                        |field_intermediation_par_fid1   |Text field                     |                               |                                                                                                              |
|Fid2                    |Fid2                        |field_intermediation_par_fid2   |Text field                     |                               |                                                                                                              |
|Fid3                    |Fid3                        |field_intermediation_par_fid3   |Text field                     |                               |                                                                                                              |
|Fid4                    |Fid4                        |field_intermediation_par_fid4   |Text field                     |                               |                                                                                                              |
|SEO                     |SEO                         |                                |                               |                               |                                                                                                              |
|Title                   |Titre                       |field_intermediation_seo_title  |Text field                     |                               |                                                                                                              |
|Introduction            |Chapô                       |field_intermediation_seo_intro  |Text area (decorated text)     |                               |                                                                                                              |
|Content                 |Contenu                     |field_intermediation_seo_content|Text area (Filtered HTML)      |                               |                                                                                                              |
|Search                  |Recherche                   |                                |Tab                            |                               |                                                                                                              |
|Search Description      |Description recherche       |field_csearch_descr             |Textarea&#124;Plain Text            |                               |Renseignez la description affichée sur la page de Résultats de recherche.                                     |

## **Category page (category)**
This content type is used to build category landing pages.

French label : Landing Categorie
### Settings

| Published | No |
| --------- | -- |
| Promoted  | No |

### Fields

|Name             |Label (fr)   |Machine name              |Type                      |Description/Options                                                                                                                                                                                                                            |Help Text (fr)                                                                                                    |
|-----------------|-------------|--------------------------|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
|Principal        |Principal    |                          |                          |                                                                                                                                                                                                                                               |                                                                                                                  |
|Title*           |Titre        |As provided               |                          |                                                                                                                                                                                                                                               |Renseignez le titre de la catégorie.                                                                              |
|Description      |Description  |field_category_description|Text area (decorated text)|                                                                                                                                                                                                                                               |Renseignez la description de la catégorie.                                                                        |
|Icon             |             |field_category_icon       |File                      |Allowed file extensions: svg File directory: svg_custom                                                                                                                                                                                        |                                                                                                                  |
|Category*        |Catégorie    |field_category_reference  |Remote (category)         |Widget &#124; Autocomplete                                                                                                                                                                                                                          |Sélectionnez la catégorie courante de la page.                                                                    |
|<del>Background image*</del>|<del>Image de fond</del>|<del>field_category_background</del> |<del>Image</del>                     |                                                                                                                                                                                                                                               |<del>Configurez l’image de fond. Formats autorisés : .jpg, .jpeg, .png. Taille recommandée : 1480 x 528 pixels.</del>        |
|<del>Color</del>            |<del>Couleur</del>      |<del>field_category_color</del>      |<del>Colorpicker</del>               |                                                                                                                                                                                                                                               |<del>Définissez la couleur de la catégorie (optionnel). Si configurée, elle sera reprise à divers endroits de la page.</del> |
|Lines            |Lignes       |                          |                          |                                                                                                                                                                                                                                               |                                                                                                                  |
|Lines            |Lignes       |field_category_lines      |Paragraph                 |Multiple &#124; Reference:</br> Paragraph (category_reference)</br> Paragraph (category_products_grid)</br> Paragraph (homepage_brands_list)</br> Paragraph (category_marketing)</br> Paragraph (category_children_tree)</br> Paragraph (category_seo)</br> Paragraph (category_slider)|                                                                                                                  |

## **Edito Landing page (edito)**
This content type is used to build Edito Category pages.

French label : Landing Edito
### Settings

| Published | No |
| --------- | -- |
| Promoted  | No |

### Fields

|Name             |Label (fr)   |Machine name           |Type                      |Description/Options                                                                                                                                                     |Help Text (fr)                                                                                               |
|-----------------|-------------|-----------------------|--------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
|Principal        |Principal    |                       |                          |                                                                                                                                                                        |                                                                                                             |
|Title*           |Titre        |As provided            |                          |                                                                                                                                                                        |Renseignez le titre de la page.                                                                              |
|Description*     |Description  |field_edito_description|Text area (decorated text)|                                                                                                                                                                        |Renseignez la description de la page.                                                                        |
|Background image*|Image de fond|field_edito_background |Image                     |                                                                                                                                                                        |Configurez l’image de fond. Formats autorisés : .jpg, .jpeg, .png. Taille recommandée : 1480 x 528 pixels.   |
|Color            |Couleur      |field_edito_color      |Colorpicker               |                                                                                                                                                                        |Définissez la couleur de la page (optionnel). Si configurée, elle sera reprise à divers endroits de la page. |
|Lines            |Lignes       |                       |                          |                                                                                                                                                                        |                                                                                                             |
|Lines            |Lignes       |field_edito_lines      |Paragraph                 |Multiple &#124; Reference:</br> Paragraph (edito_grid)</br> Paragraph (category_products_grid)</br> Paragraph (homepage_brands_list)</br> Paragraph (category_marketing)</br> Paragraph (category_seo)|                                                                                                             |

## **Conseils (advice)**
This content type is used on Advice landing page and detailed pages 
### Settings

| Published                   | No                       |
| --------------------------- | ------------------------ |
| Promoted                    | No                       |
| Workflow                    |                          |
| Expected URL alias          | /conseils/\[node-title\] |
| Breadcrumbs                 |                          |
| Meta-title                  |                          |
| Meta-description            |                          |
| Translate Interface Context |                          |

### Fields

|Name                 |Label (fr)             |Machine name            |Type                         |Description/Options                                           |Help Text (fr)                                                                                                    |
|---------------------|-----------------------|------------------------|-----------------------------|--------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
|Principal            |Principal              |                        |                             |                                                              |                                                                                                                  |
|Title*               |Titre                  |As provided             |                             |                                                              |                                                                                                                  |
|Image                |Image principale       |field_advice_image      |Image                        |                                                              |Ajoutez l’image principale de l’article. Taille recommandée : 1400x738 pixels.                                    |
|Thumbnail            |Vignette               |field_advice_thumbnail  |Image                        |                                                              |Ajoutez la vignette de l’article, affiché sur la page d’accueil Conseils. Taille recommandée : 948x569 pixels.    |
|Short Description    |Description Listings   |field_advice_short_descr|Text area (Description)      |                                                              |Renseignez la description de l’article qui sera affichée sur la page d’accueil Conseils (au niveau des listings). |
|Description*         |Description            |field_advice_description|Text area (decorated text)   |                                                              |Renseignez la description courte de l’article, affichée sur la page détail.                                       |
|Body*                |Corps                  |field_advice_content    |Text area Filtered HTML)     |                                                              |Renseignez le corps de l’article.                                                                                 |
|Tags                 |Tags                   |field_advice_tags       |Reference (term:tag)         |Widget &#124; Autocomplete Multiple                                |Assignez un ou plusieurs tags à l’article.                                                                        |
|Category*            |                       |field_advice_category   |Reference (term:category)    |Widget &#124; Autocomplete Single item                             |Assignez une catégorie à l’article.                                                                               |
|Theme*               |Thème                  |field_advice_theme      |Reference (term:advice_theme)|Widget &#124; Autocomplete Single item                             |Assignez un thème à l’article.                                                                                    |
|Marketing Block Image|Image du bloc marketing|field_advice_mb_image   |Image                        |Regular image, alt field enabled, formats: png, gif, jpg, jpeg|Ajoutez l’image du bloc marketing.                                                                                |
|Link Marketing Block |Lien du bloc marketing |field_advice_mb_link    |Link                         |No title, only ref to external link, open in new tab          |Renseignez le lien du bloc marketing.                                                                             |
|Name                 |Nom (tracking)         |field_advice_mb_name    |Text                         |NOT output on front-end                                       |Renseignez la valeur de ce champ, qui sera utilisée à des fins de tracking.                                       |
|Is sponsor           |Article sponsorisé     |field_advice_sponsor    |Boolean                      |                                                              |Choisissez si l’article est un article sponsorisé.                                                                |
|Downloads            |Téléchargements        |                        |                             |                                                              |                                                                                                                  |
|Document             |Document               |field_advice_document   |Paragraph (advice_document)  |Multiple                                                      |Ajoutez un document à télécharger à l’article.                                                                    |

## **Page Conseil ESDB (advice\_esdb)**
This content type is used on Advice landing page and detailed pages 
### Settings

| Published                   | No                                     |
| --------------------------- | -------------------------------------- |
| Promoted                    | No                                     |
| Workflow                    |                                        |
| Expected URL alias          | /inspirations-tendances/\[node-title\] |
| Breadcrumbs                 |                                        |
| Meta-title                  |                                        |
| Meta-description            |                                        |
| Translate Interface Context |                                        |

### Fields

|Name                 |Label (fr)             |Machine name                 |Type                              |Description/Options                                           |Help Text (fr)                                                                                                    |
|---------------------|-----------------------|-----------------------------|----------------------------------|--------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
|Principal            |Principal              |                             |                                  |                                                              |                                                                                                                  |
|Title*               |Titre                  |As provided                  |                                  |                                                              |                                                                                                                  |
|Image                |Image principale       |field_advice_esdb_image      |Image                             |                                                              |Ajoutez l’image principale de l’article. Taille recommandée : 1400x738 pixels.                                    |
|Thumbnail            |Vignette               |field_advice_esdb_thumbnail  |Image                             |                                                              |Ajoutez la vignette de l’article, affiché sur la page d’accueil Conseils. Taille recommandée : 948x569 pixels.    |
|Short Description    |Description Listings   |field_advice_esdb_short_descr|Text area (Description)           |                                                              |Renseignez la description de l’article qui sera affichée sur la page d’accueil Conseils (au niveau des listings). |
|Description*         |Description            |field_advice_esdb_description|Text area (decorated text)        |                                                              |Renseignez la description courte de l’article, affichée sur la page détail.                                       |
|Body*                |Corps                  |field_advice_esdb_content    |Text area Filtered HTML)          |                                                              |Renseignez le corps de l’article.                                                                                 |
|Tags                 |Tags                   |field_advice_esdb_tags       |Reference (term:tag)              |Widget &#124; Autocomplete Multiple                                |Assignez un ou plusieurs tags à l’article.                                                                        |
|Category*            |                       |field_advice_esdb_category   |Reference (term:category)         |Widget &#124; Autocomplete Single item                             |Assignez une catégorie à l’article.                                                                               |
|Theme*               |Thème                  |field_advice_esdb_theme      |Reference (term:advice_theme_esdb)|Widget &#124; Autocomplete Single item                             |Assignez un thème à l’article.                                                                                    |
|Marketing Block Image|Image du bloc marketing|field_advice_esdb_mb_image   |Image                             |Regular image, alt field enabled, formats: png, gif, jpg, jpeg|Ajoutez l’image du bloc marketing.                                                                                |
|Link Marketing Block |Lien du bloc marketing |field_advice_esdb_mb_link    |Link                              |No title, only ref to external link, open in new tab          |Renseignez le lien du bloc marketing.                                                                             |
|Name                 |Nom (tracking)         |field_advice_esdb_mb_name    |Text                              |NOT output on front-end                                       |Renseignez la valeur de ce champ, qui sera utilisée à des fins de tracking.                                       |
|Is sponsor           |Article sponsorisé     |field_advice_esdb_sponsor    |Boolean                           |                                                              |Choisissez si l’article est un article sponsorisé.                                                                |
|Downloads            |Téléchargements        |                             |                                  |                                                              |                                                                                                                  |
|Document             |Document               |field_advice_esdb_document   |Paragraph (advice_document)       |Multiple                                                      |Ajoutez un document à télécharger à l’article.                                                                    |


## **ABCdaire Detail page (abcdaire)**
This content type is used on ABCdaire landing page and detailed pages 

Translation : Page detail ABCdaire
### Settings

| Published                   | No                                                               |
| --------------------------- | ---------------------------------------------------------------- |
| Promoted                    | No                                                               |
| Workflow                    |                                                                  |
| Expected URL alias          | /abcdaire/\[node:title\]                                         |
| Breadcrumbs                 | \[site:name\] > Abécédaire du bâtiment en vidéo > \[node:title\] |
| Meta-title                  | Configurable by contributor                                      |
| Meta-description            | Configurable by contributor                                      |
| Translate Interface Context | ABCdaire video pages                                             |

### Fields

| Name                     | Label (fr)             | Machine name                       | Type                       | Description/Options                                            | Help Text (fr)                                                                                                               |
| ------------------------ | ---------------------- | ---------------------------------- | -------------------------- | -------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Principal                | Principal              |                                    |                            |                                                                |                                                                                                                              |
| Associated video title\* | Titre                  |                                    |                            |                                                                | Renseignez le titre de la page. La page sera positionnée sur la Landing ABCdaire en fonction de la 1ère lettre de son titre. |
| Video\*                  | Vidéo                  | field\_abcdaire\_video             | Video (embed)              |                                                                | Renseignez le lien YouTube de la vidéo.                                                                                      |
| Description\*            | Description            | field\_abcdaire\_description       | Text area (decorated text) |                                                                | Renseignez la description de la page.                                                                                        |
| Related video            | Vidéos associées       | field\_abcdaire\_related\_abcdaire | Reference (node:abcdaire)  |                                                                | Définissez les pages ABCDaire associées à la page.                                                                           |
| Infos Landing Abcdaire   | Infos Landing Abcdaire |                                    |                            |                                                                |                                                                                                                              |
| Image\*                  | Vignette               | field\_abcdaire\_image             | Image                      | Regular image, alt field enabled, formats: png, gif, jpg, jpeg | Ajoutez la vignette de la page, affichée sur la Landing ABCdaire ainsi que dans la section “Vidéos associées”.               |
| Description              | Description courte     | field\_abcdaire\_lp\_description   | Text area (description)    |                                                                | Renseignez la description de la page, affichée sur la Landing ABCdaire.                                                      |

## **Catalog Detail page (catalog)**
This content type is used on catalog detailed pages 

Translation : Page Catalogue détail 
### Settings

| Published                   | No                                          |
| --------------------------- | ------------------------------------------- |
| Promoted                    | No                                          |
| Workflow                    |                                             |
| Expected URL alias          | catalogues/\[node:title\]                   |
| Breadcrumbs                 | \[site:name\] > Catalogues > \[node:title\] |
| Meta-title                  | Configurable by contributor                 |
| Meta-description            | Configurable by contributor                 |
| Translate Interface Context | Pages Catalogue                             |

### Fields

|Name             |Label (fr)                 |Machine name               |Type                   |Description/Options                                                                                                                                                                                                                                                                         |Help Text (fr)                                                                         |
|-----------------|---------------------------|---------------------------|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
|Principal        |Principal                  |                           |                       |                                                                                                                                                                                                                                                                                            |                                                                                       |
|Title            |Titre                      |As provided                |                       |                                                                                                                                                                                                                                                                                            |                                                                                       |
|Image            |Visuel                     |field_catalog_image        |Image                  |Regular image, alt field enabled, formats: png, gif, jpg, jpeg                                                                                                                                                                                                                              |Renseignez le visuel de la page Catalogue, affiché dans le Header de la page.          |
|Introduction text|Texte d’introduction       |field_catalog_introduction |Text area (description)|Decorated text                                                                                                                                                                                                                                                                              |Renseignez le texte d’introduction affiché dans le Header de la page.                  |
|Document link    |Lien du catalogue          |field_catalog_link_document|Link                   |With option “Open in a new tab”                                                                                                                                                                                                                                                             |Renseignez le lien du catalogue.                                                       |
|Catalog link     |Téléchargement du catalogue|field_catalog_link_file    |File                   |Formats: zip                                                                                                                                                                                                                                                                                |Ajoutez le catalogue au format ZIP, afin que les Utilisateurs puissent le télécharger. |
|Landing page     |Infos Landing Catalogues   |                           |                       |                                                                                                                                                                                                                                                                                            |                                                                                       |
|List view title  |Titre court                |field_catalog_lp_title     |Text field             |                                                                                                                                                                                                                                                                                            |Renseignez le titre de la page Catalogue qui sera affiché sur la Landing Catalogues.   |
|List view image  |Visuel Landing             |field_catalog_lp_image     |Image                  |Regular image, alt field enabled, formats: png, gif, jpg, jpeg                                                                                                                                                                                                                              |Renseignez le visuel de la page Catalogue qui sera affiché sur la Landing Catalogues.  |
|Lines            |Lignes                     |                           |                       |                                                                                                                                                                                                                                                                                            |                                                                                       |
|Lines            |Lignes                     |field_catalog_lines        |Paragraph              |Multiple &#124; Reference:</br> Paragraph (catalog_per_area)</br> Paragraph (catalog_text_image)</br> Paragraph (catalog_text_columns)</br> Paragraph (catalog_video)</br> Paragraph (catalog_links)</br> Paragraph (catalog_dowload)</br> Paragraph (catalog_scheduler)</br> Paragraph (catalog_gmap)</br> Paragraph (homepage_products_list)|                                                                                       |

## **Service Detail page (service)**
This content type is used on Service detailed pages 

Translation : Page Service
### Settings

| Published                   | No                             |
| --------------------------- | ------------------------------ |
| Promoted                    | No                             |
| Workflow                    |                                |
| Expected URL alias          | /\[node:title\]                |
| Breadcrumbs                 | \[site:name\] > \[node:title\] |
| Meta-title                  | Configurable by contributor    |
| Meta-description            | Configurable by contributor    |
| Translate Interface Context | Pages Service                  |

### Fields

|Name        |Label (fr) |Machine name     |Type                                                                                                                           |Description/Options                               |Help Text (fr)                                                                              |
|------------|-----------|-----------------|-------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------|--------------------------------------------------------------------------------------------|
|Principal   |Principal  |                 |Tab                                                                                                                            |                                                  |                                                                                            |
|Title*      |Titre      |As provided      |                                                                                                                               |                                                  |                                                                                            |
|Description*|Description|field_srv_descr  |Text area (description)                                                                                                        |                                                  |                                                                                            |
|Logo        |Logo       |field_srv_logo   |Image                                                                                                                          |                                                  |Ajoutez le logo du service (optionnel). Formats : png, jpg, jpeg                            |
|Back link   |Lien Retour|field_srv_back   |Link                                                                                                                           |If not filled, then do not display it on front-end|Renseignez le lien de la page parente. Si non renseigné, le lien ne s’affiche pas en front. |
|Visibility  |Visibilité |field_role_access|                                                                                                                               |                                                  |                                                                                            |
|Lines       |Lignes     |                 |Tab                                                                                                                            |                                                  |                                                                                            |
|Line        |Ligne      |field_srv_line   |Paragraph (service_line_pr,</br> service_line_bnf,</br> service_line_rich_off,</br> service_line_st_off,</br> service_line_sm_off,</br> service_line_km)|Multiple                                          |                                                                                            |

## **Conseils Detail page (conseils)**
This content type is used on Conseils detailed pages 

Translation : Page Conseil expert
### Settings

| Published                   | No                                                           |
| --------------------------- | ------------------------------------------------------------ |
| Promoted                    | No                                                           |
| Workflow                    |                                                              |
| Expected URL alias          | conseils-d-experts/\[Page-theme\]/\[node:title\]             |
| Breadcrumbs                 | \[site:name\]/Conseils d’experts/\[Page-tag\]/\[node:title\] |
| Meta-title                  | Configurable by contributor                                  |
| Meta-description            | Configurable by contributor                                  |
| Translate Interface Context | Pages Conseils experts                                       |

### Fields

|Name                       |Label (fr)                                    |Machine name               |Type                            |Description/Options                                                                                                                                                                                                              |Help Text (fr)                                                                                                                                                                          |
|---------------------------|----------------------------------------------|---------------------------|--------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Principal                  |Principal                                     |                           |Tab                             |                                                                                                                                                                                                                                 |                                                                                                                                                                                        |
|Title*                     |Titre                                         |As provided                |                                |                                                                                                                                                                                                                                 |                                                                                                                                                                                        |
|Theme                      |Thème                                         |field_conseils_themes      |Reference (term:conseils_themes)|Widget &#124; Autocomplete Multiple, use Conseils Themes vocab                                                                                                                                                                        |Assignez un ou plusieurs thèmes à la page Conseil.                                                                                                                                      |
|Introduction text          |Texte d’introduction                          |field_conseils_text        |Text area (description)         |                                                                                                                                                                                                                                 |Renseignez le texte d’introduction.                                                                                                                                                     |
|Conseil Image              |Bannière                                      |field_conseils_image       |Image                           |Regular image, alt field enabled, formats: png, gif, jpg, jpeg                                                                                                                                                                   |Ajoutez la bannière de la page Conseil.                                                                                                                                                 |
|Marketing Block Image      |Image du bloc marketing                       |field_conseils_mb_image    |Image                           |Regular image, alt field enabled, formats: png, gif, jpg, jpeg                                                                                                                                                                   |Renseignez l’image à afficher dans le bloc marketing.                                                                                                                                   |
|Link Marketing Block       |Lien du bloc marketing                        |field_conseils_mb_link     |Link                            |No title, only ref to external link, open in new tab                                                                                                                                                                             |Renseignez le lien du bloc marketing.                                                                                                                                                   |
|Landing page               |Landing Conseils                              |                           |                                |                                                                                                                                                                                                                                 |                                                                                                                                                                                        |
|List view title            |Titre Liste                                   |field_conseils_lp_title    |Text field                      |                                                                                                                                                                                                                                 |Renseignez le titre de la page Conseil, affichée sur la Landing Conseils.                                                                                                               |
|List view image            |Visuel Liste                                  |field_conseils_lp_image    |Image                           |Regular image, alt field enabled, formats: png, gif, jpg, jpeg                                                                                                                                                                   |Ajoutez le visuel de la page Conseil, affiché sur la Landing Conseils.                                                                                                                  |
|List view description      |Description Liste                             |field_conseils_lp_text     |Text area (description)         |                                                                                                                                                                                                                                 |Renseignez la description de la page Conseil, affichée sur la Landing Conseils.                                                                                                         |
|Position                   |                                              |field_conseils_lp_position |                                |                                                                                                                                                                                                                                 |                                                                                                                                                                                        |
|Update on landing page     |                                              |field_conseils_lp_update   |                                |                                                                                                                                                                                                                                 |                                                                                                                                                                                        |
|Push update on landing page|Pousser la mise à jour sur la Landing Conseils|field_conseils_push_landing|Boolean                         |                                                                                                                                                                                                                                 |Si cette case est cochée, la date de la publication de ce node sera actualisée avec l'heure courante . En conséquence, le node apparaîtra d'en haut de la liste sur la Landing Conseils.|
|Lines                      |Lignes                                        |                           |Tab                             |                                                                                                                                                                                                                                 |                                                                                                                                                                                        |
|Line                       |Lignes                                        |field_conseils_lines       |Paragraph                       |Multiple &#124; Reference:</br> Paragraph (conseils_text_image)</br> Paragraph (conseils_text_cta)</br> Paragraph (conseils_text_presentation)</br> Paragraph (catalog_scheduler)</br> Paragraph (service_line_free_html)</br> Paragraph (conseils_related_conseils)|                                                                                                                                                                                        |
|SEO                        |Bloc SEO                                      |                           |                                |                                                                                                                                                                                                                                 |                                                                                                                                                                                        |
|Title                      |Titre                                         |field_conseils_seo_title   |Text field                      |                                                                                                                                                                                                                                 |                                                                                                                                                                                        |
|Content                    |Contenu                                       |field_conseils_seo_content |Text area (decorated text)      |                                                                                                                                                                                                                                 |                                                                                                                                                                                        |
|Hidden                     |Hidden                                        |                           |                                |                                                                                                                                                                                                                                 |                                                                                                                                                                                        |
|Published                  |                                              |field_conseils_published   |Integer                         |                                                                                                                                                                                                                                 |                                                                                                                                                                                        |

## **Web to Showroom (w2s\_detail)**
This content type is used on Web to Showroom detailed pages 

Translation : Détail Web to Showroom
### Settings

| Published                   | No                             |
| --------------------------- | ------------------------------ |
| Promoted                    | No                             |
| Workflow                    |                                |
| Expected URL alias          | /\[node:title\]                |
| Breadcrumbs                 | \[site:name\] > \[node:title\] |
| Meta-title                  | Configurable by contributor    |
| Meta-description            | Configurable by contributor    |
| Translate Interface Context | W2S                            |

### Fields

|Name                     |Label (fr)                         |Machine name              |Type                              |Description/Options |Help Text (fr)                                                                      |
|-------------------------|-----------------------------------|--------------------------|----------------------------------|--------------------|------------------------------------------------------------------------------------|
|Page header              |Général                            |                          |Tab                               |                    |                                                                                    |
|Room Type*               |Pièce                              |field_w2s_room_type       |Reference (taxonomy:w2s_room_type)|                    |Sélectionnez la Pièce à associer à la page.                                         |
|Style*                   |Style                              |field_w2s_style           |Reference (taxonomy:w2s_style)    |                    |Sélectionnez le Style à associer à la page.                                         |
|Description              |Description                        |field_w2s_head_description|Textarea (description)            |                    |Renseignez la description de la page.                                               |
|Immersive Carousel       |Carousel immersif                  |                          |Tab                               |                    |                                                                                    |
|Immersive carousel       |Carousel immersif                  |field_w2s_im_slider       |Reference (eck:w2s_im_slider)     |                    |Associez le carousel immersif créé au préalable.                                    |
|Highlighted Products Grid|Grille de produits                 |                          |                                  |                    |                                                                                    |
|Description              |Description                        |field_w2s_hlprods_descr   |Textarea (description)            |                    |Renseignez la description du bloc.                                                  |
|Highlighted Products     |Produit(s) mis à avant             |field_w2s_hlprods         |Paragraph (w2s_hl_prods)          |Multiple            |Renseignez les couples image / produit à afficher.                                  |
|Highlighted Product      |Mise en avant produit              |                          |                                  |                    |                                                                                    |
|Highlighted Product      |Produit mis en avant               |field_w2s_hlprod          |Paragraph (w2s_hl_product)        |                    |                                                                                    |
|Appointment block        |Prise de rendez-vous               |                          |                                  |                    |                                                                                    |
|Appointment block        |Affichage bloc Prise de Rendez-vous|field_w2s_ab              |Checkbox                          |Unchecked by default|Si coché, alors le bloc Prise de Rendez-vous est affiché sur la page.               |
|Coverings & Aspects      |Revêtement(s) et Aspect(s)         |                          |                                  |                    |                                                                                    |
|Coverings & Aspects      |Revêtement(s) et Aspect(s)         |field_w2s_ca              |Paragraph (w2s_ca)                |Multiple            |                                                                                    |
|Expert Advice Block      |Conseils d’Expert                  |                          |                                  |                    |                                                                                    |
|Description              |Description                        |field_w2s_ea_descr        |Textarea (decorated text)         |                    |Renseignez la description du bloc.                                                  |
|Items                    |Eléments                           |field_w2s_ea_item         |Reference (node:conseils)         |Multiple (3 max)    |Associez les pages Conseils d’Expert au bloc.                                       |
|Services Block           |Services                           |                          |                                  |                    |                                                                                    |
|Description              |Description                        |field_w2s_sb_descr        |Textarea (decorated text)         |                    |Renseignez la description du bloc.                                                  |
|Items                    |Eléments                           |field_w2s_sb_item         |Paragraph(w2s_sb)                 |Multiple (2 max)    |Renseignez les éléments Services (jusqu’à 2 maximum).                               |
|SEO Block                |Bloc SEO                           |                          |                                  |                    |                                                                                    |
|Title                    |Titre                              |field_w2s_seo_title       |Text field                        |Optional            |Renseignez le titre du bloc SEO (optionnel).                                        |
|Description              |Description                        |field_w2s_seo_descr       |Textarea (decorated text)         |                    |                                                                                    |
|WYSIWYG 1                |Bloc WYSIWYG - haut de page        |field_w2s_seo_wysiwyg_1   |Text area (Filtered HTML)         |                    |Renseignez le bloc WYSIWYG affiché au dessus du titre de la page.                   |
|WYSIWYG 2                |Bloc WYSIWYG - milieu de page      |field_w2s_seo_wysiwyg_2   |Text area (Filtered HTML)         |                    |Renseignez le bloc WYSIWYG affiché en dessous du bouton “Voir le mur d’inspiration”.|


## **Inspirational wall page (w2s\_insp\_wall)**
This content type is used on Inspirational wall pages 

Translation : Mur Inspirationnel W2S
### Settings

| Published                   | No                             |
| --------------------------- | ------------------------------ |
| Promoted                    | No                             |
| Workflow                    |                                |
| Expected URL alias          | /\[node:title\]                |
| Breadcrumbs                 | \[site:name\] > \[node:title\] |
| Meta-title                  | Configurable by contributor    |
| Meta-description            | Configurable by contributor    |
| Translate Interface Context | Reclamations                   |

### Fields

| General            |                               |                               | Tab                             |                  |                                                                                            |
| ------------------ | ----------------------------- | ----------------------------- | ------------------------------- | ---------------- | ------------------------------------------------------------------------------------------ |
| Description\*      | Description                   | field\_w2sin\_descr           | Textarea (decorated text)       |                  | Renseignez la description de la page.                                                      |
| Immersive carousel | Carousel immersif             | field\_w2sin\_im\_slider      | Reference (eck:w2s\_im\_slider) |                  | Renseignez le carousel immersif créé au préalable.                                         |
| W2S detail page\*  | Page détail Web to Showroom   | field\_w2sin\_w2s\_detail     | Reference (node:w2s)            |                  | Renseignez la page détail Web to Showroom liée à la page Mur Inspirationnel (obligatoire). |
| Author             | Auteur                        |                               | Tab                             |                  |                                                                                            |
| Title              | Nom                           | field\_w2sin\_auth\_title     | Text                            |                  | Renseignez le nom de l’auteur.                                                             |
| Subtitle           | Fonction                      | field\_w2sin\_auth\_subtitle  | Text                            |                  | Renseignez la fonction de l’auteur.                                                        |
| Image              | Image                         | field\_w2sin\_auth\_img       | Image                           |                  | Renseignez l’image de l’auteur.                                                            |
| Testimony          | Témoignage                    | field\_w2sin\_auth\_descr     | Textarea (decorated text)       |                  | Renseignez le témoignage.                                                                  |
| Tones              | Tonalités                     |                               |                                 |                  |                                                                                            |
| Tones              | Tonalité                      | field\_w2sin\_tones           | Colorpicker                     | Multiple (6 max) | Renseignez jusqu’à 6 tonalités à l’aide du colorpicker.                                    |
| Text section       | Zone de texte                 |                               |                                 |                  |                                                                                            |
| Title              | Titre                         | field\_w2sin\_txt\_title      | Text                            |                  | Renseignez le titre de la zone de texte (par exemple : “Matières et finitions”.            |
| Description        | Contenu                       | field\_w2sin\_txt\_descr      | Textarea (decorated text)       |                  | Renseignez le contenu de la zone de texte.                                                 |
| SEO Block          | Bloc SEO                      |                               |                                 |                  |                                                                                            |
| Title              | Titre                         | field\_w2sin\_seo\_title      | Text field                      | Optional         | Renseignez le titre du bloc SEO (optionnel).                                               |
| Description        | Contenu                       | field\_w2sin\_seo\_descr      | Textarea (decorated text)       |                  | Renseignez le contenu du bloc SEO.                                                         |
| WYSIWYG 1          | Bloc WYSIWYG - haut de page   | field\_w2sin\_seo\_wysiwyg\_1 | Text area (Filtered HTML)       |                  | Renseignez le bloc WYSIWYG affiché au dessus du titre de la page.                          |
| WYSIWYG 2          | Bloc WYSIWYG - milieu de page | field\_w2sin\_seo\_wysiwyg\_2 | Text area (Filtered HTML)       |                  | Renseignez le bloc WYSIWYG affiché au dessus du bloc de Prise de Rendez-vous.              |

## **Quiz result page (w2s\_quiz\_result)**
This content type is used on quiz result pages

Translation : Page Résultat Quiz W2S
### Settings

| Published                   | No                             |
| --------------------------- | ------------------------------ |
| Promoted                    | No                             |
| Workflow                    |                                |
| Expected URL alias          | /\[node:title\]                |
| Breadcrumbs                 | \[site:name\] > \[node:title\] |
| Meta-title                  | Configurable by contributor    |
| Meta-description            | Configurable by contributor    |
| Translate Interface Context | W2S                            |

### Fields

| Name        | Label (fr)       | Machine name                       | Type                                                                                                                                      | Description/Options | Help Text (fr)                                          |
| ----------- | ---------------- | ---------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ------------------------------------------------------- |
| General     | Général          |                                    | Tab                                                                                                                                       |                     |                                                         |
| Title\*     | Titre            | As provided                        |                                                                                                                                           |                     |                                                         |
| Description | Description      | field\_w2s\_qr\_description        | Textarea (decorated text)                                                                                                                 |                     | Renseignez la description de la page.                   |
| Image\*     | Image(s)         | field\_w2s\_qr\_image              | Image                                                                                                                                     | Multiple (2 max)    | Renseignez jusqu’à 2 images.                            |
| Style\*     | Style            | field\_w2s\_qr\_style              | Reference (taxonomy:[w2s\_style](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.2ovzkin)) |                     | Sélectionnez le Style à associer à la page de résultat. |
| Tones       | Caractéristiques |                                    |                                                                                                                                           |                     |                                                         |
| Title       | Titre            | field\_w2s\_qr\_tones\_title       | Text                                                                                                                                      |                     | Renseignez le titre du bloc de texte.                   |
| Description | Contenu          | field\_w2s\_qr\_tones\_description | Textarea (decorated text)                                                                                                                 |                     | Renseignez le contenu du bloc de texte.                 |
| Tones       | Tonalités        | field\_w2s\_qr\_tones              | Colorpicker                                                                                                                               | Multiple (6 max)    | Renseignez jusqu’à 6 tonalités à l’aide du colorpicker. |

## **Claims form (claims\_form)**
This content type is used on Claims form detailed pages 

Translation : Page formulaire
### Settings

| Published                   | No                             |
| --------------------------- | ------------------------------ |
| Promoted                    | No                             |
| Workflow                    |                                |
| Expected URL alias          | /\[node:title\]                |
| Breadcrumbs                 | \[site:name\] > \[node:title\] |
| Meta-title                  | Configurable by contributor    |
| Meta-description            | Configurable by contributor    |
| Translate Interface Context | Reclamations                   |

### Fields

|Name                |Label (fr)                                                                  |Machine name           |Type                    |Description/Options|Help Text (fr)                                                                                                                                                                                             |
|--------------------|----------------------------------------------------------------------------|-----------------------|------------------------|-------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|General             |Général                                                                     |                       |Tab                     |                   |                                                                                                                                                                                                           |
|Title*              |Titre                                                                       |As provided            |                        |                   |                                                                                                                                                                                                           |
|Description         |Description                                                                 |field_cf_description   |Textarea (Filtered HTML)|                   |Renseignez la description affichée au dessus du formulaire (optionnel).                                                                                                                                    |
|Footer              |Bas de page                                                                 |field_cf_footer        |Textarea (Filtered HTML)|                   |Renseignez la description affichée en dessous du formulaire (optionnel).                                                                                                                                   |
|Emails*             |Adresse(s) email                                                            |field_cf_emails        |Text field              |                   |Renseignez les adresses email auxquelles une copie de la soumission du formulaire sera envoyée. Si plusieurs adresses sont nécessaires, séparez-les avec une virgule (email1@email.com, email2@email.com). |
|Send email to agency|Envoyer un email d'information à l'agence sélectionnée lors de la soumission|field_cf_send_to_agency|Boolean                 |                   |Si sélectionné, un email d'information contenant les informations saisies par l'utilisateur sera envoyé à l'agence sélectionnée lors de la soumission.                                                     |

## **Page Service Point P (service\_detail)**
This content type is used on Service detailed pages 

Translation : Services Point P

### Settings

| Published                   | No                                                               |
| --------------------------- | ---------------------------------------------------------------- |
| Promoted                    | No                                                               |
| Workflow                    |                                                                  |
| Expected URL alias          | /\[node:title\]                                                  |
| Breadcrumbs                 | \[site:name\] > \[service\_landing:node:title\] > \[node:title\] |
| Meta-title                  | Configurable by contributor                                      |
| Meta-description            | Configurable by contributor                                      |
| Translate Interface Context | Pages Service                                                    |

### Fields

|Name        |Label (fr)  |Machine name         |Type                            |Description/Options                                                                                                                           |Help Text (fr)                                                      |
|------------|------------|---------------------|--------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|
|General     |Général     |                     |Tab                             |                                                                                                                                              |                                                                    |
|Title*      |Titre       |As provided          |                                |                                                                                                                                              |                                                                    |
|Description |Description |field_sdp_description|Textarea (decorated text)       |                                                                                                                                              |Renseignez la description de la page.                               |
|Landing page|Page Landing|field_sdp_landing    |Reference (node:service_landing)|Reference to service landing content type                                                                                                     |Assignez la page Service à une Landing Service préalablement créée. |
|Lines       |Lignes      |                     |Tab                             |                                                                                                                                              |                                                                    |
|Line        |Lignes      |field_sdp_line       |Paragraph                       |Multiple &#124; Reference:</br> Paragraph</br> (service_line_bnf)</br> (service_line_media)</br> (service_line_wysiwyg) (service_line_free_html)</br> (service_line_at_form)|                                                                    |

## **Page Landing Service Point P (service\_landing)**
This content type is used on Service landing pages 

Translation : Page Landing Service Point P  

### Settings

| Published                   | No                             |
| --------------------------- | ------------------------------ |
| Promoted                    | No                             |
| Workflow                    |                                |
| Expected URL alias          | /\[node:title\]                |
| Breadcrumbs                 | \[site:name\] > \[node:title\] |
| Meta-title                  | Configurable by contributor    |
| Meta-description            | Configurable by contributor    |
| Translate Interface Context | Pages Service                  |

### Fields

|Name                          |Label (fr)                          |Machine name                  |Type                               |Description/Options                                                                   |Help Text (fr)                                                                                                                      |
|------------------------------|------------------------------------|------------------------------|-----------------------------------|--------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|
|General                       |Général                             |                              |Tab                                |                                                                                      |                                                                                                                                    |
|Title*                        |Titre                               |As provided                   |                                   |                                                                                      |Renseignez le titre utilisé pour la génération de l’alias URL / du fil d’Ariane                                                     |
|Additional title              |Titre de la page                    |field_slp_title               |Text field                         |                                                                                      |Renseignez le titre de la page.                                                                                                     |
|Description                   |Description                         |field_slp_description         |Textarea (decorated text)          |                                                                                      |Renseignez la description de la page.                                                                                               |
|Desktop background            |Bannière desktop                    |field_slp_bg_desktop          |Image                              |                                                                                      |Ajoutez la bannière desktop. Taille recommandée : 1480x307 pixels.                                                                  |
|Mobile background             |Bannière mobile                     |field_slp_bg_mobile           |Image                              |                                                                                      |Ajoutez la bannière mobile.                                                                                                         |
|Logo                          |Logo Génération Artisans            |field_slp_logo                |Image                              |                                                                                      |Ajoutez le logo Génération Artisans affiché sur la bannière (optionnel).                                                            |
|Generation Artisans visibility|Afficher la date Génération Artisans|field_slp_gav                 |Single on/off checkbox             |                                                                                      |Cochez la checkbox pour afficher la date d’inscription à Génération Artisans (applicable uniquement pour les utilisateurs membres). |
|Quick access bar              |Barre accès rapides                 |                              |Tab                                |                                                                                      |                                                                                                                                    |
|Quick access bar items        |Eléments barre accès rapide         |field_slp_qab_items           |Paragraph                          |Multiple &#124; Reference:</br> Paragraph</br> (service_landing_qab_block)                           |Ajoutez des éléments à la barre d’accès rapides.                                                                                    |
|Service Blocks Defaults       |Informations blocs Services         |                              |Tab                                |                                                                                      |                                                                                                                                    |
|GA Text                       |Description Génération Artisans     |field_slp_sbd_ga_text         |Textarea (decorated text)          |                                                                                      |Renseignez la description affichée sur le bloc Génération Artisans, pour les Utilisateurs abonnés.                                  |
|GA Link title                 |Label lien Génération Artisans      |field_slp_sbd_ga_link_title   |Textfield                          |                                                                                      |Renseignez le label du lien affiché sur le bloc Génération Artisans, pour les Utilisateurs abonnés.                                 |
|SOLU+ Text                    |Description SOLU+                   |field_slp_sbd_solup_text      |Textarea (decorated text)          |                                                                                      |Renseignez la description affichée sur le bloc SOLU+, pour les Utilisateurs abonnés.                                                |
|SOLU+ Link title              |Label lien SOLU+                    |field_slp_sbd_solup_link_title|Textfield                          |                                                                                      |Renseignez le label du lien affiché sur le bloc SOLU+, pour les Utilisateurs abonnés.                                               |
|Caprenov+ Text                |Description Caprenov+               |field_slp_sbd_cap_text        |Textarea (decorated text)          |                                                                                      |Renseignez la description affichée sur le bloc Caprenov+, pour les Utilisateurs abonnés.                                            |
|Caprenov+ Link title          |Label lien Caprenov+                |field_slp_sbd_cap_link_title  |Textfield                          |                                                                                      |Renseignez le label du lien affiché sur le bloc Caprenov+, pour les Utilisateurs abonnés.                                           |
|Lines                         |Lignes                              |                              |Tab                                |                                                                                      |                                                                                                                                    |
|Numbers                       |Afficher les chiffres               |field_slp_numbers_show        |Bool &#124; Single on/off checkbox      |                                                                                      |                                                                                                                                    |
|Line                          |Lignes                              |field_slp_line                |Paragraph                          |Multiple &#124; Reference:</br> Paragraph</br> (service_landing_lines_block)</br> (service_line_free_html)|                                                                                                                                    |
|SEO                           |SEO                                 |                              |                                   |                                                                                      |                                                                                                                                    |
|Title                         |Titre                               |field_slp_seo_title           |Text field                         |                                                                                      |Renseignez le titre du bloc SEO.                                                                                                    |
|Content                       |Description                         |field_slp_seo_description     |Text area (advanced decorated text)|                                                                                      |                                                                                                                                    |
|Content                       |Contenu                             |field_slp_seo_content         |Text area (advanced decorated text)|                                                                                      |Renseignez le contenu du bloc SEO.                                                                                                  |

## **Mini-catalog (mini\_catalog)**
This content type is used on mini\_catalog detailed pages 

Translation : Mini catalogue
### Settings

| Published                   | No                          |
| --------------------------- | --------------------------- |
| Promoted                    | No                          |
| Workflow                    |                             |
| Expected URL alias          | /\[node:title\]             |
| Breadcrumbs                 | No breadcrumbs on this page |
| Meta-title                  | Configurable by contributor |
| Meta-description            | Configurable by contributor |
| Translate Interface Context | Mini catalogue              |

### Fields

|Name                |Label (fr)                 |Machine name                 |Type                     |Description/Options                                                                                  |Help Text (fr)                                                                                                                                                          |
|--------------------|---------------------------|-----------------------------|-------------------------|-----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|General             |Général                    |                             |Tab                      |                                                                                                     |                                                                                                                                                                        |
|Title*              |Titre                      |As provided                  |                         |                                                                                                     |                                                                                                                                                                        |
|Banner*             |Bannière                   |field_minic_banner           |Image                    |                                                                                                     |Ajoutez la bannière de la page.                                                                                                                                         |
|Description         |Description                |field_minic_description      |Textarea (decorated text)|                                                                                                     |Renseignez la description de la page.                                                                                                                                   |
|Color               |Couleur                    |field_minic_color            |Colorpicker              |                                                                                                     |.                                                                                                                                                                       |
|Back link           |Lien Retour                |field_minic_back             |Link                     |If not filled, then do not display it on front-end                                                   |Renseignez le lien de la page parente. Si non renseigné, le lien ne s’affiche pas en front.                                                                             |
|Visibilité          |Visibilité                 |field_role_access            |Roles Access             |                                                                                                     |Définissez la visibilité par profil de la section Mini catalogue. Si aucun profil sélectionné, la section ne sera pas accessible depuis le front du site.               |
|Pagination line     |Pagination line            |                             |Tab                      |                                                                                                     |                                                                                                                                                                        |
|Title               |Titre                      |field_minic_pagination_title |Text                     |                                                                                                     |Renseignez le titre du bloc (optionnel).                                                                                                                                |
|File                |Fichier                    |field_minic_pagination_file  |File                     |                                                                                                     |Importez le fichier contenant les produits à ajouter.  Format recommandé : TXT. Une référence produit par ligne.  La pagination sera affichée sur la grille de produits.|
|Amount of pagination|Nombre de produits par page|field_minic_pagination_amount|Number &#124; integer         |                                                                                                     |Définissez le nombre de produits affiché par page.                                                                                                                      |
|Lines               |Lignes                     |                             |Tab                      |                                                                                                     |                                                                                                                                                                        |
|Line                |Lignes                     |C &#124;&#124;                         |Paragraph                |Multiple &#124; Reference:</br> Paragraph:</br> (service_line_wysiwyg)</br> (category_products_grid) (products_grid_file)|                                                                                                                                                                        |
|Publish             |Publication                |                             |Tab                      |                                                                                                     |                                                                                                                                                                        |
|Publish Date        |Date de publication        |field_publish_date           |Date                     |                                                                                                     |Renseignez la date à laquelle le contenu sera automatiquement publié.                                                                                                   |
|Publish time        |Heure de publication       |field_publish_time           |                         |                                                                                                     |Renseignez l’heure à partir de laquelle le contenu sera automatiquement publié. Par défaut le champ heure est vide et égale à 00h00.                                    |
|Unpublish Date      |Date de dépublication      |field_unpublish_date         |Date                     |                                                                                                     |Renseignez la date à laquelle le contenu sera automatiquement dépublié.                                                                                                 |
|Unpublish time      |Heure de publication       |field_unpublish_time         |                         |                                                                                                     |Renseignez l’heure à partir de laquelle le contenu sera automatiquement dépubliqué.                                                                                     |

## **Mini-catalog Advanced (mini\_catalog\_advanced)**
This content type is used on mini\_catalog\_advanced detailed pages 

Translation : Page Mini Catalogue avancé
### Settings

| Published                   | No                          |
| --------------------------- | --------------------------- |
| Promoted                    | No                          |
| Workflow                    |                             |
| Expected URL alias          | /\[node:title\]             |
| Breadcrumbs                 | No breadcrumbs on this page |
| Meta-title                  | Configurable by contributor |
| Meta-description            | Configurable by contributor |
| Translate Interface Context | Mini catalogue avance       |

### Fields

| Name                 | Label (fr)                   | Machine name                    | Type                                                                                                                                           | Description/Options                                | Help Text (fr)                                                                                                                                                |
| -------------------- | ---------------------------- | ------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| General              | Général                      |                                 | Tab                                                                                                                                            |                                                    |                                                                                                                                                               |
| Title\*              | Titre                        | As provided                     |                                                                                                                                                |                                                    |                                                                                                                                                               |
| Hide title           |                              | filed\_mca\_hide\_title         |                                                                                                                                                |                                                    |                                                                                                                                                               |
| Banner               | Bannière                     | field\_mca\_banner              | Image                                                                                                                                          |                                                    | Ajoutez la bannière de la page, affichée sous les filtres mis en avant.                                                                                       |
| Banner title         |                              | field\_mca\_banner\_title       | Text                                                                                                                                           |                                                    |                                                                                                                                                               |
| Banner description   |                              | field\_mca\_banner\_description | Textarea (decorated text)                                                                                                                      |                                                    |                                                                                                                                                               |
| Opacity              | Opacité de la bannière       | field\_mca\_opacity             | Bool | Single on/off checkbox                                                                                                                  |                                                    | Cochez cette case pour afficher le layer d’opacité sur la bannière.                                                                                           |
| Sidebar Banner       | Bannière Marketing           | field\_mca\_banner\_sidebar     | Image                                                                                                                                          |                                                    | Si ajoutée, la bannière Marketing est affichée sous les filtres, dans la colonne de gauche.                                                                   |
| Description          | Description                  | field\_mca\_description         | Textarea (decorated text)                                                                                                                      |                                                    | Ajoutez la description de la page.                                                                                                                            |
| Top text             | Bloc WYSIWYG principal       | field\_mca\_seo\_top            | Textarea (Filtered HTML)                                                                                                                       |                                                    | Si renseigné, le contenu s’affiche entre la bannière principale et la liste des produits.                                                                     |
| Free HTML 1          | Bloc HTML libre haut de page | field\_mca\_free\_html\_1       | Paragraph ([service\_line\_free\_html](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.wy8ajl)) |                                                    | Si renseigné, ce bloc s’affiche au dessus de la liste des produits.                                                                                           |
| File\*               | Fichier CSV                  | field\_mca\_file                | File                                                                                                                                           | Private, \*.csv                                    | Ajoutez le fichier CSV contenant les produits et leurs filtres. Nombre maximum de produits recommandé : 500.                                                  |
| Back link            | Lien Retour                  | field\_mca\_back                | Link                                                                                                                                           | If not filled, then do not display it on front-end | Renseignez le lien de la page parente. Si non renseigné, le lien ne s’affiche pas en front.                                                                   |
| Visibilité           | Visibilité                   | field\_role\_access             | Roles Access                                                                                                                                   | <br><br>                                           | Définissez la visibilité par profil de la page Mini catalogue avancé. Si aucun profil sélectionné, la section ne sera pas accessible depuis le front du site. |
| Early birds          | Early Birds                  |                                 |                                                                                                                                                | Fieldset                                           |                                                                                                                                                               |
| Widget ID            | Widget ID                    | field\_mca\_eb\_widget\_id      | Text                                                                                                                                           |                                                    | Renseignez le widget ID Early Birds.                                                                                                                          |
| Category ID          | Catégorie                    | field\_mca\_eb\_category\_id    | Remote (category)                                                                                                                              | Widget | Autocomplete                              | Renseignez une catégorie (optionnel).                                                                                                                         |
| Free HTML 2          | Bloc HTML libre bas de page  | field\_mca\_free\_html\_2       | Paragraph ([service\_line\_free\_html](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.wy8ajl)) |                                                    | Si renseigné, ce bloc s’affiche en dessous de la liste des produits.                                                                                          |
| Highlighted filter   | Filtres mis en avant         |                                 | Tab                                                                                                                                            |                                                    |                                                                                                                                                               |
| Subtitle             | Sous-titre                   | field\_mca\_hf\_subtitle        | Text                                                                                                                                           |                                                    | Renseignez le sous-titre affiché au dessus des filtres mis en avant.                                                                                          |
| Filter property name | Nom du filtre                | field\_mca\_hf\_prop\_name      | Text                                                                                                                                           |                                                    | Renseignez le nom du filtre mis en avant, tel que renseigné dans le fichier CSV.                                                                              |
| Filter options       | Options du filtre            | field\_mca\_hf\_options         | Paragraph                                                                                                                                      | Multiple (mca\_hf\_option)                         | Renseignez les options (valeurs) du filtre, telles que renseignées dans le fichier CSV.                                                                       |
| Publish              | Publication                  |                                 | Tab                                                                                                                                            |                                                    |                                                                                                                                                               |
| Publish Date         | Date de publication          | field\_publish\_date            | Date                                                                                                                                           |                                                    | Renseignez la date à laquelle le contenu sera automatiquement publié.                                                                                         |
| Publish time         | Heure de publication         | field\_publish\_time            |                                                                                                                                                |                                                    | Renseignez l’heure à partir de laquelle le contenu sera automatiquement publié. Par défaut le champ heure est vide et égale à 00h00.                          |
| Unpublish Date       | Date de dépublication        | field\_unpublish\_date          | Date                                                                                                                                           |                                                    | Renseignez la date à laquelle le contenu sera automatiquement dépublié.                                                                                       |
| Unpublish time       | Heure de publication         | field\_unpublish\_time          |                                                                                                                                                |                                                    | Renseignez l’heure à partir de laquelle le contenu sera automatiquement dépubliqué.                                                                           |
| SEO                  |                              |                                 | Tab                                                                                                                                            |                                                    |                                                                                                                                                               |
| Sidebar text         | Bloc SEO - gauche            | field\_mca\_seo\_sidebar        | Textarea (advanced decorated text)                                                                                                             |                                                    | Si renseigné, ce bloc s’affiche sous les filtres / la bannière Marketing.                                                                                     |
| Bottom text          | Bloc SEO - bas de page       | field\_mca\_seo\_bottom         | Textarea (advanced decorated text)                                                                                                             |                                                    | Si renseigné, ce bloc s'affiche sous la liste des produits.                                                                                                   |

## **SEO Detail page (seo)**
This content type is used on SEO detail pages

Translation : Page SEO
### Settings

| Published                   | No                             |
| --------------------------- | ------------------------------ |
| Promoted                    | No                             |
| Workflow                    |                                |
| Expected URL alias          | /\[node:title\]                |
| Breadcrumbs                 | \[site:name\] > \[node:title\] |
| Meta-title                  | Configurable by contributor    |
| Meta-description            | Configurable by contributor    |
| Translate Interface Context | Page SEO                       |

### Fields

|Name          |Label (fr)            |Machine name             |Type                              |Description/Options                                                                                                                                        |Help Text (fr)                                                                                                                      |
|--------------|----------------------|-------------------------|----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|
|General       |Général               |                         |Tab                               |                                                                                                                                                           |                                                                                                                                    |
|Title*        |Titre                 |As provided              |                                  |                                                                                                                                                           |                                                                                                                                    |
|Description   |Description           |field_seo_description    |Textarea (decorated text)         |                                                                                                                                                           |Renseignez la description de la page.                                                                                               |
|Visibilité    |Visibilité            |field_role_access        |Roles Access                      |                                                                                                                                                           |                                                                                                                                    |
|Lines         |Lignes                |                         |Tab                               |                                                                                                                                                           |                                                                                                                                    |
|Line          |Lignes                |field_seo_line           |Paragraph                         |Multiple &#124; Reference:</br> Paragraph:</br> (service_line_media)</br> (service_line_wysiwyg)</br> (service_line_free_html)</br> (homepage_products_list)</br> (catalog_scheduler, ca_line)|                                                                                                                                    |
|SEO           |SEO                   |                         |                                  |                                                                                                                                                           |                                                                                                                                    |
|Title         |Titre                 |field_seo_seo_title      |Text field                        |Optional                                                                                                                                                   |Renseignez le titre du bloc SEO (optionnel).                                                                                        |
|Description   |Description           |field_seo_seo_description|Textarea (advanced decorated text)|                                                                                                                                                           |                                                                                                                                    |
|Publish       |                      |                         |                                  |                                                                                                                                                           |                                                                                                                                    |
|Publish Date  |Date de publication   |field_publish_date       |Date                              |                                                                                                                                                           |Renseignez la date à laquelle le contenu sera automatiquement publié.                                                               |
|Publish time  |Heure de publication  |field_publish_time       |                                  |                                                                                                                                                           |Renseignez l’heure à partir de laquelle le contenu sera automatiquement publié. Par défaut le champ heure est vide et égale à 00h00.|
|Unpublish Date|Date de dépublication |field_unpublish_date     |Date                              |                                                                                                                                                           |Renseignez la date à laquelle le contenu sera automatiquement dépublié.                                                             |
|Unpublish time|Heure de dépublication|field_unpublish_time     |                                  |                                                                                                                                                           |Renseignez l’heure à partir de laquelle le contenu sera automatiquement dépubliqué.                                                 |

## **Agency / Showroom (agency\_showroom)**
This content type is used for contribution Agency and Showroom details on Drupal side.

French name : Agence / Showroom
### Settings

| Published                   | No |
| --------------------------- | -- |
| Promoted                    | No |
| Expected URL alias          |    |
| Breadcrumbs                 |    |
| Meta-title                  |    |
| Meta-description            |    |
| Translate Interface Context |    |

### Fields

| Name                 | Label (fr)                | Machine name                     | Type                                                                                                                                           | Description/Options | Help Text (fr)                                                                                               |
| -------------------- | ------------------------- | -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ------------------------------------------------------------------------------------------------------------ |
| Principal            |                           |                                  |                                                                                                                                                |                     |                                                                                                              |
| Title\*              | Titre                     | As provided                      |                                                                                                                                                |                     |                                                                                                              |
| Agency title         | Titre page agence H1      | field\_as\_agency\_title         | Text                                                                                                                                           |                     | Renseignez le titre de la page agence à afficher. Cela ne changera pas l’URL.                                |
| Showroom title       | Titre page showroom H1    | field\_as\_showroom\_title       | Text                                                                                                                                           |                     | Renseignez le titre de la page showroom à afficher. Cela ne changera pas l’URL.                              |
| Agency id\*          | Agency ID                 | field\_as\_agency\_id            | Text field                                                                                                                                     |                     | Renseignez l’ID de l’agence / du showroom.                                                                   |
| Agency image         | Visuel Agence             | field\_as\_agency\_image         | Image                                                                                                                                          |                     | Renseignez le visuel de l’agence. Si non renseigné, le visuel par défaut s’affichera.                        |
| Showroom images      | Visuels Showroom          | field\_as\_showroom\_images      | Image                                                                                                                                          | Multiple            | Renseignez les visuels du showroom. Si non renseigné, le visuel par défaut s’affichera.                      |
| Agency description   | Description de l’agence   | field\_as\_description\_agency   | Textarea (Filtered HTML)                                                                                                                       |                     | Renseignez la description de l’agence.                                                                       |
| Free HTML agency     | Bloc HTML libre Agence    | field\_as\_free\_html\_agency    | Paragraph ([service\_line\_free\_html](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.wy8ajl)) |                     |                                                                                                              |
| Simple Text          | Bloc WYSIWYG Agence       | field\_as\_simple\_text          | Textarea (Filtered HTML)                                                                                                                       |                     |                                                                                                              |
| Free HTML showroom   | Bloc HTML libre Showroom  | field\_as\_free\_html\_shoowroom | Paragraph ([service\_line\_free\_html](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.wy8ajl)) |                     |                                                                                                              |
| Showroom text slot 1 | Bloc WYSIWYG Showroom 1   | field\_as\_showroom\_text1       | Textarea (Filtered HTML)                                                                                                                       |                     |                                                                                                              |
| Showroom text slot 2 | Bloc WYSIWYG Showroom 2   | field\_as\_showroom\_text2       | Textarea (Filtered HTML)                                                                                                                       |                     |                                                                                                              |
| Showroom text slot 3 | Bloc WYSIWYG Showroom 3   | field\_as\_showroom\_text3       | Textarea (Filtered HTML)                                                                                                                       |                     |                                                                                                              |
| WYSIWYG title        | Bloc WYSIWYG haut de page | field\_as\_wysiwyg\_title        | Textarea (Filtered HTML)                                                                                                                       |                     | Si renseigné, ce bloc s’affiche entre le titre et la description de la page (pour les Showrooms uniquement). |

## **FAQ Category (faq\_category)**
This content type is used on FAQ Category pages 

Translation : Catégorie FAQ

### Settings

| Published                   | No                                    |
| --------------------------- | ------------------------------------- |
| Promoted                    | No                                    |
| Workflow                    |                                       |
| Expected URL alias          | ../foire-aux-questions-\[node:title\] |
| Breadcrumbs                 | \[site:name\] > FAQ \[node:title\]    |
| Meta-title                  | Configurable by contributor           |
| Meta-description            | Configurable by contributor           |
| Translate Interface Context | Page FAQ                              |

### Fields

|Name              |Label (fr)           |Machine name        |Type                         |Description/Options                                    |Help Text (fr)                                                           |
|------------------|---------------------|--------------------|-----------------------------|-------------------------------------------------------|-------------------------------------------------------------------------|
|General           |Général              |                    |Tab                          |                                                       |                                                                         |
|Title*            |Titre                |As provided         |                             |                                                       |Renseignez le titre de la catégorie FAQ.                                 |
|Icon*             |Icône                |field_faq_c_icon    |File                         |Allowed file extensions: svg File directory: svg_custom|Renseignez l’icône de la catégorie FAQ.                                  |
|Questions         |Questions            |                    |Tab                          |                                                       |                                                                         |
|Questions         |Questions            |field_faq_c_question|Reference (node:faq_question)|Multivalue                                             |Liez les Questions préalablement créées à la catégorie FAQ.              |
|Search            |Recherche            |                    |Tab                          |                                                       |                                                                         |
|Search Description|Description recherche|field_csearch_descr |Textarea&#124;Plain Text          |                                                       |Renseignez la description affichée sur la page de Résultats de recherche.|

## **FAQ Question (faq\_question)**
This content type is used on FAQ question pages 

Translation : Question FAQ

### Settings

| Published                   | No       |
| --------------------------- | -------- |
| Promoted                    | No       |
| Workflow                    |          |
| Expected URL alias          | No       |
| Breadcrumbs                 | No       |
| Meta-title                  | No       |
| Meta-description            | No       |
| Translate Interface Context | Page FAQ |

### Fields

| Name    | Label (fr) | Machine name          | Type          | Description/Options | Help Text (fr)                       |
| ------- | ---------- | --------------------- | ------------- | ------------------- | ------------------------------------ |
| General | Général    |                       | Tab           |                     |                                      |
| Title\* | Titre      | As provided           |               |                     | Renseignez le titre de la Question.  |
| Answer  | Réponse    | field\_faq\_q\_answer | Filtered HTML |                     | Renseignez la réponse à la Question. |

## **Page formulaire Drupal (drupal\_form\_page)**
This content type is used for Webform pages 

Translation : Page formulaire Drupal

### Setting

| Published                   | No                             |
| --------------------------- | ------------------------------ |
| Promoted                    | No                             |
| Workflow                    |                                |
| Expected URL alias          | ../\[node:title\]              |
| Breadcrumbs                 | \[site:name\] > \[node:title\] |
| Meta-title                  | Configurable by contributor    |
| Meta-description            | Configurable by contributor    |
| Translate Interface Context | Formulaire Drupal              |

### Fields

|Name           |Label (fr)|Machine name     |Type                                          |Description/Options|Help Text (fr)                                              |
|---------------|----------|-----------------|----------------------------------------------|-------------------|------------------------------------------------------------|
|General        |Général   |                 |Tab                                           |                   |                                                            |
|Title*         |Titre     |As provided      |                                              |                   |                                                            |
|Visibilité     |Visibilité|field_role_access|Roles Access                                  |                   |Définissez la visibilité du Page.                           |
|Paragraph lines|Lignes    |field_wf_lines   |Paragraph (line_wysiwyg &#124; webform_line_form ) |                   |Ajoutez les différentes lignes qui vont composer votre page.|


## **Category Brand (category\_brand)**
This content type is used for Category + Brand pages.

Translation : Page Catégorie + Marque

### Settings

| Published                   | No                                                                                                                        |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Promoted                    | No                                                                                                                        |
| Workflow                    |                                                                                                                           |
| Expected URL alias          | ../c/\[category:name\]/\[category:id\]/\[brand:name\]                                                                     |
| Breadcrumbs                 | \[site:name\] > \[category level 1\] > \[category level 2\] > \[current category\] > … > \[Category:name\] \[Brand:name\] |
| Meta-title                  | Configurable from back-office                                                                                             |
| Meta-description            | Configurable from back-office                                                                                             |
| Translate Interface Context | Liste Categorie + Marque                                                                                                  |

### Fields

|Name            |Label (fr)             |Machine name           |Type                              |Description/Options  |Help Text (fr)                                                                                                                                                                                                 |
|----------------|-----------------------|-----------------------|----------------------------------|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|General         |Général                |                       |Tab                               |                     |                                                                                                                                                                                                               |
|Title*          |Titre                  |As provided            |                                  |                     |                                                                                                                                                                                                               |
|Category*       |Catégorie              |field_cb_category      |Remote (category)                 |Widget &#124; Autocomplete|Définissez la catégorie de la page.                                                                                                                                                                            |
|Brand*          |Marque                 |field_cb_brand         |Reference (node:brand)            |                     |Définissez la marque de la page.                                                                                                                                                                               |
|Brand slug*     |Filtre Marque          |field_cb_brand_slug    |Text field                        |                     |Renseignez le filtre Marque tel qu’utilisé dans le moteur de recherche. Exemple : “atlantic electrique”. Ce champ “technique” est utilisé pour pouvoir filtrer sur la marque depuis la page Catégorie + Marque.|
|Description     |Description            |field_cb_description   |Textarea (decorated text)         |                     |Renseignez la description de la page.                                                                                                                                                                          |
|Side SEO title  |Titre SEO - Gauche     |field_cb_seo1_title    |Text field                        |                     |Renseignez le titre du bloc SEO - Gauche.                                                                                                                                                                      |
|Side SEO text   |Texte SEO - Gauche     |field_cb_seo1          |Textarea (Advanced decorated text)|                     |Renseignez le contenu SEO affiché à gauche de la page, sous les filtres (optionnel).                                                                                                                           |
|Bottom SEO title|Titre SEO - bas de page|field_cb_seo2_title    |Text field                        |                     |Renseignez le titre du bloc SEO - bas de page.                                                                                                                                                                 |
|Bottom SEO text |Texte SEO - bas de page|field_cb_seo2          |Textarea (Advanced decorated text)|                     |Renseignez le contenu SEO affiché en bas de page (optionnel).                                                                                                                                                  |
|Early Birds     |Early Birds            |                       |Tab                               |                     |                                                                                                                                                                                                               |
|Widget ID       |Widget ID              |field_cb_eb_widget_id  |Text                              |                     |Renseignez le widget ID Early Birds.                                                                                                                                                                           |
|Type            |Variantes d’affichage  |field_cb_eb_type       |Select                            |Type 1 Type 2        |Sélectionnez la variante d’affichage Early Birds. Type 1 : affichage “Liste” Type 2 : affichage “Carousel”                                                                                                     |
|Title           |Titre                  |field_cb_eb_title      |Text                              |                     |Le titre du bloc est affiché uniquement si le Type 2 est sélectionné                                                                                                                                           |
|Title color     |Couleur du titre       |field_cb_eb_title_color|Colorpicker                       |                     |Définissez la couleur du titre, affiché uniquement si le Type 2 est sélectionné                                                                                                                                |
|Background color|Couleur de fond        |field_cb_eb_bg_color   |Colorpicker                       |                     |Définissez la couleur de fond, affichée uniquement si le Type 2 est sélectionné                                                                                                                                |

## **ESDB - Page Style (esdb\_style)**
This content type is used for ESDB style pages.

Translation : Page Style ESDB

### Settings

| Published                   | No                                                                             |
| --------------------------- | ------------------------------------------------------------------------------ |
| Promoted                    | No                                                                             |
| Expected URL alias          | envie-de-salle-de-bain/styles-et-solutions/\[node:title\]                      |
| Breadcrumbs                 | \[site:name\] > Envie de Salle de Bain > Styles et Solutions >  \[node:title\] |
| Meta-title                  | Configurable from back-office                                                  |
| Meta-description            | Configurable from back-office                                                  |
| Translate Interface Context | ESDB                                                                           |

### Field

|Name                         |Label (fr)                              |Machine name                 |Type                                        |Description/Options         |Help Text (fr)                                                              |
|-----------------------------|----------------------------------------|-----------------------------|--------------------------------------------|----------------------------|----------------------------------------------------------------------------|
|General                      |Général                                 |                             |Tab                                         |                            |                                                                            |
|Title*                       |Titre                                   |As provided                  |                                            |                            |                                                                            |
|Description                  |Description                             |field_e_s_description        |Textarea (Advanced decorated text)          |                            |Renseignez la description de la page.                                       |
|Immersive carousel           |Carousel Immersif                       |                             |Tab                                         |                            |                                                                            |
|Immersive carousel           |Carousel Immersif                       |field_e_s_im_carousel        |Paragraph (esdb_im_slider)                  |                            |Ajoutez un carousel immersif à la page.                                     |
|List page                    |Page Liste                              |                             |Tab                                         |                            |                                                                            |
|Thumbnail*                   |Vignette                                |field_e_s_thumbnail          |Image                                       |                            |Renseignez la vignette affichée sur la page Liste et la page d’accueil ESDB.|
|Style presentation           |Présentation du Style                   |                             |Tab                                         |                            |                                                                            |
|Testimony: author            |Auteur                                  |field_e_s_sp_tauthor         |Reference (term:advice_author_esdb)         |                            |Sélectionnez l’auteur du témoignage (optionnel).                            |
|Testimony: content           |Témoignage                              |field_e_s_sp_descr           |Textarea (decorated text)                   |                            |Renseignez le témoignage associé à la slide (optionnel).                    |
|Images grid                  |Image(s)                                |field_e_s_sp_images          |Image                                       |Multiple                    |Renseignez les images de présentation du Style.                             |
|Colors tones items           |Palette de couleur                      |field_e_s_sp_tones           |Texte (brut)                                |Colorpicker/Multiple (6 max)|Définissez la palette de couleurs du Style.                                 |
|Style Inspirations (carousel)|Origines du Style                       |                             |Tab                                         |                            |                                                                            |
|Style Inspirations (carousel)|Carousel Origines                       |field_e_s_insiparion_carousel|Paragraph (esdb_carousel_inspirations_style)|                            |Configurez le carousel des Origines du Style.                               |
|Style Highlights (carousel)  |Objets emblématiques                    |                             |Tab                                         |                            |                                                                            |
|Style Highlights (carousel)  |Carousel Objets emblématiques           |field_e_s_highlights_carousel|Paragraph (esdb_style_highlights_carousel)  |                            |Configurez le carousel des Objets emblématiques.                            |
|Appointment                  |Prise de rendez-vous                    |                             |Tab                                         |                            |                                                                            |
|Show appointment block       |Afficher le bloc de prise de rendez-vous|field_e_s_im_appointment     |Boolean                                     |                            |Cochez la checkbox pour afficher le bloc de Prise de rendez-vous.           |
|Related products carousel    |Produits liés                           |                             |Tab                                         |                            |                                                                            |
|Related products carousel    |Carousel Produits liés                  |field_e_s_related_products   |Paragraph(esdb_related_products_carousel)   |Unlimited                   |Configurez le carousel des Produits liés.                                   |
|Conseils related content     |Conseils                                |                             |Tab                                         |                            |                                                                            |
|Conseils related content     |Conseils                                |field_e_s_crc                |Paragraph(esdb_advice_line)                 |                            |Ajoutez des Conseils liés.                                                  |

## **ESDB - Page Solution (esdb\_solution)**
This content type is used for ESDB solution pages.

Translation : Page Solution ESDB

### Settings

| Published                   | No                                                                                               |
| --------------------------- | ------------------------------------------------------------------------------------------------ |
| Promoted                    | No                                                                                               |
| Workflow                    |                                                                                                  |
| Expected URL alias          | /p/sanitaire/\[node:title\]                                                                      |
| Breadcrumbs                 | \[site:name\] > \[category:level1\] > \[category:level2\] > \[category:level3\] > \[node:title\] |
| Meta-title                  | Configurable by contributor                                                                      |
| Meta-description            | Configurable by contributor                                                                      |
| Translate Interface Context | Ensembles ESDB                                                                                   |

### Field

| Name                     | Label (fr)             | Machine name            | Type                                     | Description/Options           | Help Text (fr)                                                                                                                                            |
| ------------------------ | ---------------------- | ----------------------- | ---------------------------------------- | ----------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| General                  | Général                |                         | Tab                                      |                               |                                                                                                                                                           |
| Title\*                  | Titre                  | As provided             |                                          |                               |                                                                                                                                                           |
| Category\*               | Catégorie              | field\_epe\_category    | Remote (category)                        |                               | Assignez une catégorie à l’Ensemble (utilisé pour la génération du fil d’Ariane).                                                                         |
| Description              | Description            | field\_epe\_description | Text area (Advanced decorated text)      |                               | Renseignez la description de l’Ensemble.                                                                                                                  |
| Images\*                 | Images                 | field\_epe\_images      | Image                                    |                               | Ajoutez les images de l’Ensemble.                                                                                                                         |
| Show promo label         | En promotion           | field\_epe\_promo       | Boolean                                  | Bool | Single on/off checkbox | Cochez cette case si l’Ensemble est en promotion. Un label Promo apparait en front.                                                                       |
| Search page              | Résultats de recherche |                         | Tab                                      |                               |                                                                                                                                                           |
| Thumbnail\*              | Vignette               | field\_epe\_thumbnail   | Image                                    |                               | Renseignez la vignette affichée sur la page de résultats de recherche.                                                                                    |
| Search description       | Description recherche  | field\_epe\_short\_desc | Text area (plain text)                   |                               | Renseignez la description affichée sur la page de résultats de recherche.                                                                                 |
| Products                 | Produits               |                         | Tab                                      |                               |                                                                                                                                                           |
| Products\*               | Produits               | field\_epe\_products    | Remote (product)                         |                               | Associez les produits à l’Ensemble.                                                                                                                       |
| Ensembles                | Ensembles alternatifs  |                         | Tab                                      |                               |                                                                                                                                                           |
| Related ensembles        | Ensembles alternatifs  | field\_epe\_ensembles   | Reference (node:esdb\_product\_ensemble) |                               | Renseignez les Ensembles alternatifs. L’Ensemble actual sera également automatiquement ajouté en tant qu’Ensemble alternatif sur les contenus renseignés. |
| Conseils related content | Conseils               |                         | Tab                                      |                               |                                                                                                                                                           |
| Conseils related content | Conseils               | field\_epe\_crc         | Paragraph(esdb\_advice\_line)            |                               | Ajoutez des Conseils liés.                                                                                                                                |

## **Editorial Page (editorial\_page)**
This content type is used by brands to create flexible content page with the new Template Engine Builder.

Translation : Page éditoriale

### Settings

| Published                   | No                             |
| --------------------------- | ------------------------------ |
| Promoted                    | No                             |
| Workflow                    |                                |
| Expected URL alias          | /\[node:title\]                |
| Breadcrumbs                 | \[site:name\] > \[node:title\] |
| Meta-title                  | Configurable by contributor    |
| Meta-description            | Configurable by contributor    |
| Translate Interface Context | Editorial Page                 |

### Field

|Name                   |Label (fr)             |Machine name                  |Type                             |Description/Options                                                                                                                          |Help Text (fr)                                                                      |
|-----------------------|-----------------------|------------------------------|---------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|
|General                |Général                |                              |Fieldset                         |Contains general fields for the editorial page. Mark as required.                                                                            |                                                                                    |
|Title*                 |Titre                  |As provided                   |                                 |                                                                                                                                             |                                                                                    |
|Editorial Title        |Titre Editorial        |field_editorial_title         |Text (Plain)                     |This title will be displayed on the page if it exists. It will replace the technical content title.                                          |Titre affiché dans la page.                                                         |
|Title Display          |Affichage du Titre     |field_title_display           |List (Text)                      |The way the title is displayed on the editorial page. Optional (could be None)</br>  0&#124;Above Header</br> 1&#124;In Header</br> 2&#124;Below Header                    |Choisissez l’endroit où le titre sera affiché.                                      |
|Title Alignment*       |Alignement du titre    |field_title_alignment         |List (Text)                      |Title Alignment.</br> 0&#124;Gauche</br> 1&#124;Droite</br> 2&#124;Centré                                                                                                  |Choisissez l’alignement du titre.                                                   |
|Title Color            |Couleur du titre       |field_title_color             |Colorpicker                      |                                                                                                                                             |Choisissez la couleur de la police.                                                 |
|Header                 |Entête                 |                              |Details Inside Fieldset “Général”|Contains fields to configure a header on the editorial page.</br> Default state closed. Mark as required.                                         |                                                                                    |
|Image Header           |Image entête           |field_image_header            |Image                            |Image contributed for the header.                                                                                                            |Ajoutez l’image de la page à afficher en desktop.                                   |
|Image Header Mobile    |Image entête mobile    |field_image_header_mobile     |Image                            |Image contributed for the header on mobile devices. (Separated field)                                                                        |Ajoutez l’image de la page à afficher en mobile.                                    |
|Navigation             |Navigation             |                              |Details Inside Fieldset “Général”|Contains fields to configure navigation and visibility on the editorial page. Default state closed. Mark as required.                        |                                                                                    |
|Parent Page            |Page parente           |field_parent_page             |Reference (node:editorial_page)  |The Parent Page system will allow you to enhance the navigation between your editorial pages. It includes automatic breadcrumb, menus, etc...|Renseignez la page parente.                                                         |
|Visibility             |Visibilité             |field_role_access             |Roles Access                     |                                                                                                                                             |                                                                                    |
|Block Navigation       |Bloc Navigation        |field_edito_block_navigation  |Reference Paragraph              |You can choose a block navigation OR a block anchor to contribute here for your editorial page. You cannot add more than one block.          |                                                                                    |
|Footer                 |Bas de Page            |                              |Details Inside Fieldset “Footer” |Contains fields to configure footer on the editorial page. Default state closed. Mark as required.                                           |                                                                                    |
|Reinsurrance items     |Éléments de réassurance|field_edito_reinsurrance_items|Checkbox                         |Check this if you want to add the reinsurrance items system block in your editorial page footer                                              |Cochez cette case si vous voulez ajouter les éléments de réassurance en bas de page.|
|CTA items              |Éléments de CTA        |field_edito_cta_items         |Checkbox                         |Check this if you want to add the CTA items system block in your editorial page footer                                                       |Cochez cette case si vous voulez ajouter les éléments de CTA en bas de page.        |
|Sticky                 |Bloc Sticky            |                              |Details Inside Fieldset “Sticky” |Contains fields to configure optionnal sticky block on the editorial page. Default state closed.                                             |                                                                                    |
|Sticky Block           |Bloc Sticky            |field_editorial_sticky_block  |Reference Paragraph              |You can choose a block sticky to contribute here for your editorial page. You cannot add more than one block.                                |Ajoutez un bloc sticky. Seulement un bloc peut être ajouté par page.                |
|End Of General Fieldset|                       |                              |                                 |                                                                                                                                             |                                                                                    |
|Sections               |Sections               |field_sections                |Paragraph(section)               |Paragraph field to add sections to your editorial page. Inline Entity Form : Complex                                                         |Ajoutez les sections de la page.                                                    |
|Metatags               |Métatags               |field_editorial_metatags      |Meta tags                        |Metatags field for SEO.                                                                                                                      |                                                                                    |
