# **ECK Entity Types**
## **Sidebar Menu (sidebar\_menu)**
This custom entity type is used to handle site's sidebar menus.

French label : Menu latéral
### Settings

| Created | Yes |
| ------- | --- |
| Changed | Yes |
| Author  | Yes |
| Title   | Yes |

### Fields

| Name          | Label (fr)   | Machine name                 | Type         | Description/Options  | Help Text (fr)                                         |
| ------------- | ------------ | ---------------------------- | ------------ | -------------------- | ------------------------------------------------------ |
| Sidebar menu  | Menu latéral | sidebar                      | Bundle       |                      |                                                        |
| Menu          |              |                              |              | Tab                  |                                                        |
| Title\*       | Titre        | As provided                  |              |                      |                                                        |
| Available for | Visibilité   | field\_sidebar\_menu\_access | Roles Access |                      | Définissez la visibilité du menu.                      |
| Links\*       | Liens        | field\_sidebar\_menu\_links  | Link         | Multiple (unlimited) | Définissez les liens des pages présentes dans le menu. |

## **Homepage Widget : Slider (slider)**
This custom entity type is used to handle site's homepage slider widgets.

French label : Carrousel principal Page d’accueil
### Settings

| Created | Yes |
| ------- | --- |
| Changed | Yes |
| Author  | Yes |
| Title   | Yes |

### Fields

|Name          |Label (fr)           |Machine name            |Type                             |Description/Options            |Help Text (fr)                                                                                                                                                     |
|--------------|---------------------|------------------------|---------------------------------|-------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Slider        |                     |                        |                                 |                               |                                                                                                                                                                   |
|Visibilité    |Visibilité           |field_hpw_role_access   |Roles</br> Access                     |                               |Multiple                                                                                                                                                           |
|Agencies      |Agences              |field_hpw_agencies      |Remote (agency)                  |Widget &#124; Autocomplete, Multiple|Sélectionnez les agences pour lesquelles le slider est visible (optionnel). Si pas d’agences renseignées, alors le slider est disponible pour toutes les agences.  |
|Regions       |Régions              |field_hpw_regions       |Remote (region)                  |Widget &#124; Select List, Multiple |Sélectionnez les régions pour lesquelles le slider est visible (optionnel). Si pas de régions renseignées, alors le slider est disponible pour toutes les régions. |
|Slides*       |Bannières            |field_hpw_sl_slides     |Paragraph (homepage_widget_slide)|                               |Multiple                                                                                                                                                           |
|Publish       |Publication          |                        |                                 |                               |                                                                                                                                                                   |
|Publish Date  |Date de publication  |field_hpw_publish_date  |Date                             |                               |Renseignez la date à laquelle le contenu sera automatiquement publié.                                                                                              |
|Publish time  |Heure de publication |field_hpw_publish_time  |                                 |                               |Renseignez l’heure à partir de laquelle le contenu sera automatiquement publié                                                                                     |
|Unpublish Date|Date de dépublication|field_hpw_unpublish_date|Date                             |                               |Renseignez la date à laquelle le contenu sera automatiquement dépublié.                                                                                            |
|Unpublish time|Heure de publication |field_hpw_unpublish_time|                                 |                               |Renseignez l’heure à partir de laquelle le contenu sera automatiquement publié                                                                                     |

## **Homepage Widget : Marketing (marketing)**
This custom entity type is used to handle site's homepage marketing widgets.

French label : Bannières Marketing Page d’accueil 
### Settings

| Created | Yes |
| ------- | --- |
| Changed | Yes |
| Author  | Yes |
| Title   | Yes |

### Fields

|Name          |Label (fr)           |Machine name            |Type                                 |Description/Options                                                                                                                                                                                                                                                 |Help Text (fr)                                                                                                                                                                                                                       |
|--------------|---------------------|------------------------|-------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|              |                     |                        |                                     |                                                                                                                                                                                                                                                                    |                                                                                                                                                                                                                                     |
|Visibilité    |Visibilité           |field_hpw_role_access   |Roles Access                         |                                                                                                                                                                                                                                                                    |Multiple                                                                                                                                                                                                                             |
|Agencies      |Agences              |field_hpw_agencies      |Remote (agency)                      |Widget &#124; Autocomplete, Multiple                                                                                                                                                                                                                                     |Sélectionnez les agences pour lesquelles le bloc Marketing est visible (optionnel). Si pas d’agences renseignées, alors le bloc Marketing est disponible pour toutes les agences.                                                    |
|Regions       |Régions              |field_hpw_regions       |Remote (region)                      |Widget &#124; Select list, Multiple                                                                                                                                                                                                                                      |Sélectionnez les régions pour lesquelles le bloc Marketing est visible (optionnel). Si pas de régions renseignées, alors le bloc Marketing est disponible pour toutes les régions.                                                   |
|Type*         |Variante d’affichage |field_hpw_mb_type       |Text                                 |Widget &#124; Select list Options :</br> 100% , 50%, 33%, 25%, 66% x 33%, 33% x 66%</br>  ----------</br> 1 bannière pleine largeur</br> 2 bannières, 50% chaque</br> 3 bannières, 33% chaque</br> 4 bannières, 25% chaque</br> 2 bannières, la 1ère 66% - la 2ème 33%</br> 2 bannières, la 1ère 33%, la 2ème 66%|Sélectionnez la variante d’affichage des bannières dans la liste. Si vous sélectionnez une variante avec plusieurs bannières sur la même ligne, attention à bien ajouter des bannières ayant la même hauteur.                        |
|Blocks*       |Bannières            |field_hpw_mb_blocks     |Paragraph (homepage_widget_marketing)|Multiple                                                                                                                                                                                                                                                            |Ajoutez le nombre de bannières correspondant à la variante d’affichage sélectionnée. Si vous ajoutez plus de bannières que le nombre correspondant à la variante d’affichage, les bannières supplémentaires ne seront pas affichées. |
|Publish       |Publication          |                        |                                     |                                                                                                                                                                                                                                                                    |                                                                                                                                                                                                                                     |
|Publish Date  |Date de publication  |field_hpw_publish_date  |Date                                 |                                                                                                                                                                                                                                                                    |Renseignez la date à laquelle le contenu sera automatiquement publié.                                                                                                                                                                |
|Publish time  |Heure de publication |field_hpw_publish_time  |                                     |                                                                                                                                                                                                                                                                    |Renseignez l’heure à partir de laquelle le contenu sera automatiquement publié                                                                                                                                                       |
|Unpublish Date|Date de dépublication|field_hpw_unpublish_date|Date                                 |                                                                                                                                                                                                                                                                    |Renseignez la date à laquelle le contenu sera automatiquement dépublié.                                                                                                                                                              |
|Unpublish time|Heure de publication |field_hpw_unpublish_time|                                     |                                                                                                                                                                                                                                                                    |Renseignez l’heure à partir de laquelle le contenu sera automatiquement publié                                                                                                                                                       |

## **Immersive carousel (w2s\_im\_slider)**
This custom entity type is used to handle Immersive carousel on W2S Detail page and Images grid Inspirational wall page.

French label : Carousel immersif Web to Showroom 
### Settings

| Created | Yes  |
| ------- | ---- |
| Changed | Yes  |
| Author  | Yes+ |
| Title   | Yes  |

### Fields

| Name    | Label (fr) | Machine name      | Type                       | Description/Options | Help Text (fr)                           |
| ------- | ---------- | ----------------- | -------------------------- | ------------------- | ---------------------------------------- |
| Content |            |                   |                            |                     |                                          |
| Slide   | Slide      | field\_imc\_slide | Paragraph (w2s\_im\_slide) | Multiple            | Ajoutez des slides au Carousel immersif. |

## **ESDB Immersive carousel (esdb\_im\_slider)**
This custom entity type is used to handle Immersive carousel on ESDB Style Detail page.

French label : Immersive carousel ESDB
### Settings

| Created | Yes  |
| ------- | ---- |
| Changed | Yes  |
| Author  | Yes+ |
| Title   | Yes  |

### Fields

| Name    | Label (fr) | Machine name            | Type                                                                                                                                  | Description/Options | Help Text (fr)                           |
| ------- | ---------- | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ---------------------------------------- |
| Content |            |                         |                                                                                                                                       |                     |                                          |
| Slide   | Slide      | field\_esdb\_imc\_slide | Paragraph ([esdb\_im\_slide](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.2a997sx)) | Multiple            | Ajoutez des slides au Carousel immersif. |


## **Quiz question (w2s\_quiz\_question)**
This custom entity type is used to handle quiz question on W2S quiz page.

French label : Question Quiz W2S
### Settings

| Created | Yes |
| ------- | --- |
| Changed | Yes |
| Author  | Yes |
| Title   | Yes |

### Fields

| Name       | Label (fr) | Machine name             | Type                                                                                                                                                 | Description/Options | Help Text (fr)                                     |
| ---------- | ---------- | ------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | -------------------------------------------------- |
| Content    | Contenu    |                          |                                                                                                                                                      |                     |                                                    |
| Title\*    | Titre      | As provided              |                                                                                                                                                      |                     |                                                    |
| Category\* | Catégorie  | field\_w2s\_qq\_category | Reference (taxonomy:[w2s\_quiz\_categories](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.32b5gho)) |                     | Assignez une catégorie à la question.              |
| Answers    | Réponses   |                          |                                                                                                                                                      |                     |                                                    |
| Answers    | Réponses   | field\_w2s\_qq\_answers  | Paragraph ([w2s\_qqa](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.33ipx8d))                       | Multiple            | Renseignez les différentes réponses à la question. |

## **ESDB Quiz question (esdb\_quiz\_question)**
This custom entity type is used to handle quiz question on ESDB quiz page.

French label : Question Quiz ESDB
### Settings

| Created | Yes |
| ------- | --- |
| Changed | Yes |
| Author  | Yes |
| Title   | Yes |

### Fields

| Name    | Label (fr) | Machine name             | Type                                                                                                                                            | Description/Options | Help Text (fr)                                     |
| ------- | ---------- | ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | -------------------------------------------------- |
| Content | Contenu    |                          |                                                                                                                                                 |                     |                                                    |
| Title\* | Titre      | As provided              |                                                                                                                                                 |                     |                                                    |
| Answers | Réponses   |                          |                                                                                                                                                 |                     |                                                    |
| Answers | Réponses   | field\_esdb\_qq\_answers | Paragraph ([ESDB question answer](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.cwf0h0k7bubq)) | Multiple            | Renseignez les différentes réponses à la question. |

## **Categories SEO (categories\_seo)**
This custom entity type is used to handle categories SEO page.

French label : Catégorie Produits
### Settings

| Created | Yes |
| ------- | --- |
| Changed | Yes |
| Author  | Yes |
| Title   | Yes |


### Fields

|Name            |Label (fr)                    |Machine name               |Type             |Description/Options    |Help Text (fr)                                                                              |
|----------------|------------------------------|---------------------------|-----------------|-----------------------|--------------------------------------------------------------------------------------------|
|Content         |Contenu                       |                           |                 |                       |                                                                                            |
|Category*       |Catégorie                     |field_cseo_reference       |Remote (category)|Widget &#124; Autocomplete  |Renseignez la catégorie.                                                                    |
|Description     |Description                   |field_cseo_description     |Text area        |Decorated text         |Si renseignée, cette description s’affiche à la place de la description renvoyée par le PIM.|
|Meta title      |Meta-title                    |field_cseo_meta_title      |Text field       |                       |Si renseigné, le meta-title s’affiche à la place place du meta-title automatique.           |
|Meta description|Meta-description              |field_cseo_meta_description|Text area        |                       |Si renseignée, la meta-description s’affiche à la place de la meta-description automatique. |
|SEO text sidebar|Description SEO - gauche      |field_cseo_text_sidebar    |Text area        |Advanced decorated text|Si renseignée, cette description s’affiche sous les filtres à gauche.                       |
|SEO text footer |Description SEO - pied de page|field_cseo_text_footer     |Text area        |Advanced decorated text|Si renseignée, cette description s’affiche en bas de page.                                  |


## **Catégories produits filtrées (categories\_seo\_filtered)**
This custom entity type is used to override SEO meta tags on filtered PLP pages.

French label : Catégorie produits filtrées
### Settings

| Created | Yes |
| ------- | --- |
| Changed | Yes |
| Author  | Yes |
| Title   | Yes |


### Fields

|Name                |Label (fr)           |Machine name          |Type             |Description/Options              |Help Text (fr)                                                             |
|--------------------|---------------------|----------------------|-----------------|---------------------------------|---------------------------------------------------------------------------|
|Content             |Contenu              |                      |                 |                                 |                                                                           |
|Category*           |Catégorie            |field_cseof_reference |Remote (category)|Widget &#124; Autocomplete            |Renseignez la catégorie.                                                   |
|URL of filtered PLP*|Url de la PLP filtrée|field_cseof_url       |Text field       |Relative URL Example : /mapage/13|Renseignez l’URL relative de la page filtrée concernée                     |
|Meta title          |Meta-title           |field_cseof_meta_title|Text field       |                                 |Si renseigné, le meta-title s’affiche à la place du meta-title automatique.|
|Page title          |H1                   |field_cseof_page_title|Text field       |H1 page title                    |Si renseigné, le H1 s’affiche à la place du H1 automatique.                |


## **Edito content on Product detail (products\_edito)**
This custom entity type is used to handle Edito content on Product detail page.

French label : Contenus Edito page Produit
### Settings

| Created | Yes |
| ------- | --- |
| Changed | Yes |
| Author  | Yes |
| Title   | Yes |


|Name            |Label (fr)              |Machine name        |Type                  |Description/Options            |Help Text (fr)                                                                                                                                                                                |
|----------------|------------------------|--------------------|----------------------|-------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Content         |Contenu                 |                    |                      |                               |                                                                                                                                                                                              |
|Category ref*   |Catégorie               |field_pe_reference  |Remote (category)     |Widget &#124; Autocomplete          |Renseignez la catégorie. Les contenus seront affichés sur tous les produits liés à cette catégorie et à ses catégories enfant (sauf si contenu spécifique configuré pour un (des) enfant(s)). |
|Mise en avant   |Mise en avant           |                    |                      |                               |                                                                                                                                                                                              |
|Image           |Image                   |field_pe_image      |Image                 |                               |Renseignez l’image si vous souhaitez mettre un contenu en avant.                                                                                                                              |
|Label           |Label                   |field_pe_label      |Text field            |                               |Renseignez le label affiché au dessus de la description si vous souhaitez mettre un contenu en avant (optionnel).                                                                             |
|Label background|Couleur de fond du label|field_pe_label_color|Colorpicker           |                               |Renseignez la couleur de fond du label. Si pas de couleur sélectionnée, alors la couleur Marque 1 (définie dans Site Settings) s’appliquera.                                                  |
|Description     |Description             |field_pe_description|Text area &#124; Plain text|                               |Renseignez la description si vous souhaitez mettre un contenu en avant.                                                                                                                       |
|Link            |Lien                    |field_pe_link       |Link                  |With option “Open in a new tab”|Renseignez le lien si vous souhaitez mettre un contenu en avant.                                                                                                                              |
|Background color|Couleur de fond         |field_pe_color      |Colorpicker           |                               |Renseignez la couleur de fond si vous souhaitez mettre un contenu en avant. Si pas de couleur sélectionnée, alors la couleur Marque 1 (définie dans Site Settings) s’appliquera.              |
|Eléments        |Eléments                |                    |                      |                               |                                                                                                                                                                                              |
|Items           |Eléments                |field_pe_items      |Paragraph (pe_item)   |Multiple                       |Ajoutez des éléments de contenu.                                                                                                                                                              |

