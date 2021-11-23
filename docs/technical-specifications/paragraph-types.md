# **Paragraph Types**
## **Main Categories Color (main\_categories\_color)**
This paragraph is used to manage main categories color.

French label : Couleur Univers produits
### Fields

|Name     |Label (fr)|Machine name       |Type             |Description/Options                                     |Help Text (fr)                                              |
|---------|----------|-------------------|-----------------|--------------------------------------------------------|------------------------------------------------------------|
|Category*|Univers   |field_main_category|Remote (category)|First level categories from service Widget &#124; Select list|Choisissez un univers (catégorie de niveau 1) dans la liste.|
|Color    |Couleur   |field_mcc_color    |Colorpicker      |                                                        |Choisissez la couleur à associer à l’univers sélectionné.   |


## **MCA Highlighted filter option (mca\_hf\_option)**
This paragraph is used to manage advanced mini catalog highlighted filters.

French label : Mini Catalogue Avancé : options filtres mis en avant
### Fields

| Name    | Label (fr) | Machine name                  | Type | Description/Options | Help Text (fr)                                                                                                                                                          |
| ------- | ---------- | ----------------------------- | ---- | ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Title\* | Titre      | field\_mca\_hf\_option\_title |      |                     | Ajoutez le titre de la valeur du filtre, qui sera affiché en front. Vous pouvez utiliser la même valeur que dans le champ “Valeur”, ou bien en indiquer une différente. |
| Image\* | Image      | field\_mca\_hf\_option\_image |      |                     | Ajoutez l’image correspondant à la valeur du filtre mis en avant.                                                                                                       |
| Value\* | Valeur     | field\_mca\_hf\_option\_value |      |                     | Ajoutez la valeur du filtre mis en avant tel que contribué dans le fichier CSV.                                                                                         |

## **DEMAT presentation (demat\_presentation)**
This paragraph is used to manage demat presentation.

French label : 
### Fields

| Name    | Label (fr) | Machine name       | Type     | Description/Options | Help Text (fr) |
| ------- | ---------- | ------------------ | -------- | ------------------- | -------------- |
| Image   |            | field\_dp\_image   | Image    |                     |                |
| WYSIWYG |            | field\_dp\_wysiwyg | Textarea |                     |                |


## **DEMAT step (demat\_step)**
This paragraph is used to manage demat steps.

French label : 
### Fields


| Name       | Label (fr) | Machine name        | Type     | Description/Options | Help Text (fr) |
| ---------- | ---------- | ------------------- | -------- | ------------------- | -------------- |
| Step text  |            | field\_dstep\_text  | Textarea |                     |                |
| Step title |            | field\_dstep\_title | Text     |                     |                |


## **DEMAT option (demate\_option)**
This paragraph is used to manage main categories.

French label : 
### Fields

| Name         | Label (fr) | Machine name             | Type  | Description/Options | Help Text (fr) |
| ------------ | ---------- | ------------------------ | ----- | ------------------- | -------------- |
| Option image |            | field\_do\_option\_image | Image |                     |                |
| Option title |            | field\_do\_option\_title | Text  |                     |                |

## **Main Categories (main\_categories)**
This paragraph is used to manage main categories.

French label : Encart Marketing Univers Produits
### Fields

|Name           |Label (fr)      |Machine name            |Type                       |Description/Options                                     |Help Text (fr)                                              |
|---------------|----------------|------------------------|---------------------------|--------------------------------------------------------|------------------------------------------------------------|
|Category*      |Univers         |field_main_category     |Remote (category)          |First level categories from service Widget &#124; Select list|Choisissez un univers (catégorie de niveau 1) dans la liste.|
|Marketing Block|Encart Marketing|field_mc_marketing_block|Paragraph (marketing_block)|single                                                  |                                                            |
|Visibilité     |Visibilité      |field_par_role_access   |Roles Access               |                                                        |                                                            |


## **Webform line form (webform\_line\_form)**
This paragraph is used for form lines in Webform CT.

French label : Ligne Formulaire
### Fields

| Name | Label (fr) | Machine name     | Type                | Description/Options | Help Text (fr)                                    |
| ---- | ---------- | ---------------- | ------------------- | ------------------- | ------------------------------------------------- |
| Form | Formulaire | field\_wlf\_form | Reference (webform) |                     | Sélectionnez le formulaire à ajouter sur la page. |

## **Ligne Wysiwyg (line\_wysiwyg)**
Wysiwyg line to be used in different CTs.

French label : Ligne WYSIWYG

### Fields

| Name          | Label (fr)  | Machine name    | Type                      | Description/Options | Help Text (fr)                 |
| ------------- | ----------- | --------------- | ------------------------- | ------------------- | ------------------------------ |
| Content       | Contenu     |                 | Details                   |                     |                                |
| Description\* | Description | field\_lw\_text | Textarea (decorated text) |                     | Renseignez le contenu du bloc. |

## **Products Carousels area (pca\_content)**
This paragraph is used to place products block on Products Carousels area.

French label : Carousel Produits
### Fields

|Name                  |Label (fr)        |Machine name     |Type               |Description/Options                                                 |Help Text (fr)                                                                                                                                       |
|----------------------|------------------|-----------------|-------------------|--------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
|Title                 |Titre             |field_pca_title  |Text               |                                                                    |                                                                                                                                                     |
|Early Birds widget ID |Widget Early Birds|field_pca_eb_id  |Text               |                                                                    |Renseignez l’ID Early Birds si ce carousel doit remonter des produits Early Birds, sinon utilisez le champ Type de produits.                         |
|Related product`s type|Type de produits  |field_pca_rp_type|Select (Multivalue)|COMPLEMENTARY&#124; COMPLEMENTARY SIMILAR&#124; SIMILAR ASSOCIATED&#124; ASSOCIATED|Sélectionnez le type de produits à afficher. Si le champ Widget Early Birds est renseigné, alors il prend la priorité sur le champ Type de produits. |

## **Marketing Block (marketing\_block)**
This paragraph is used to manage Marketing Block.

French label : Encart Marketing
### Fields

|Name       |Label (fr)    |Machine name      |Type    |Description/Options            |Help Text (fr)                                                                        |
|-----------|--------------|------------------|--------|-------------------------------|--------------------------------------------------------------------------------------|
|Link       |Lien          |field_mb_link     |Link    |With option “Open in a new tab”|Définissez le lien de redirection de l’encart Marketing (optionnel)                   |
|Image*     |Image         |field_mb_image    |Image   |                               |Uploadez l’encart à associer à l’univers sélectionné. Largeur recommandée : 204 pixels|
|Name       |Nom (tracking)|field_mb_name     |Text    |NOT output on front-end        |Renseignez la valeur de ce champ, qui sera utilisée à des fins de tracking.           |
|Description|Description   |field_mb_des      |Textarea|                               |Renseignez la description du bloc marketing.                                          |
|Subtitle   |Sous-titre    |field_mb_sub_title|Text    |                               |Renseignez le sous-titre du bloc marketing.                                           |
|Title      |Titre         |field_mb_title    |Text    |                               |Renseignez le titre du bloc marketing.                                                |


## **Menu Marketing Block (menu\_marketing\_block)**
This paragraph is used to manage Menu Marketing Block.

French label : Encart Marketing menu Contenu
### Fields

| Name            | Label (fr)       | Machine name                 | Type                         | Description/Options                      | Help Text (fr)                                          |
| --------------- | ---------------- | ---------------------------- | ---------------------------- | ---------------------------------------- | ------------------------------------------------------- |
| Menu Item\*     | Elément de menu  | field\_mmb\_menu\_item       | Text field                   | First level menu<br>Widget | Select list | Choisissez un élément de menu (niveau 1) dans la liste. |
| Marketing Block | Encart Marketing | field\_mmb\_marketing\_block | Paragraph (marketing\_block) | single                                   |                                                         |

## **CTA items (**pf\_cta\_items**)**
This paragraph is used to manage CTA items block.

French label : Elément CTA
### Fields

| Name        | Label (fr)  | Machine name             | Type       | Description/Options             | Help Text (fr)                             |
| ----------- | ----------- | ------------------------ | ---------- | ------------------------------- | ------------------------------------------ |
| Icon        | Icône       | field\_pfci\_icon        | Image      |                                 | Définissez l’icône de l’élément CTA        |
| Title       | Titre       | field\_fpci\_title       | Text field |                                 | Définissez le titre de l’élément CTA       |
| Description | Description | field\_fpci\_description | Text area  |                                 | Définissez la description de l’élément CTA |
| Link        | Lien        | field\_pfci\_link        | Link       | with “Open in new tab” checkbox | Définissez le lien de l’élément CTA        |

## **Social media icon (social\_media\_icon)**
This paragraph is used to manage social media icons.

French label : Icône Réseau social
### Fields

|Name|Label (fr)|Machine name |Type                     |Description/Options            |Help Text (fr)                                                  |
|----|----------|-------------|-------------------------|-------------------------------|----------------------------------------------------------------|
|Icon|Icône     |field_si_icon|List (text) &#124; Select list|Predefined list of social icons|Sélectionnez l’icône du réseau social                           |
|Link|Lien      |field_si_link|Link &#124; Link              |URL, “open in new tab” checkbox|Définissez le lien de redirection vers la page du réseau social |


## **Reinsurance item (reinsurance\_item)**
This paragraph is used to manage Reinsurance items.

French label : Élément de Réassurance
### Fields

|Name       |Label (fr) |Machine name        |Type                            |Description/Options |Help Text (fr)                                    |
|-----------|-----------|--------------------|--------------------------------|--------------------|--------------------------------------------------|
|Icon       |Icône      |field_ri_icon       |Reference &#124; Image               |                    |Définissez l’icône de l’élément Réassurance       |
|Title      |Titre      |field_ri_title      |Text &#124; Text field               |                    |Définissez le titre de l’élément Réassurance      |
|Description|Description|field_ri_description|Text &#124; Text area (multiple rows)|Format : Description|Définissez la description de l’élément Réassurance|


## **Login Reinsurance Item (login\_reinsurance\_item)**
This paragraph is used to manage Reinsurance items on Login page.

French label : Élément de réassurance Inscription
### Fields

|Name |Label (fr)|Machine name   |Type              |Description/Options|Help Text (fr)                              |
|-----|----------|---------------|------------------|-------------------|--------------------------------------------|
|Icon |Icône     |field_lri_icon |Reference &#124; Image |                   |Définissez l’icône de l’élément Réassurance |
|Title|Titre     |field_lri_title|Text &#124; Text field |                   |Définissez le titre de l’élément Réassurance|


## **Agency Landing box (agency\_landing\_box)**
This paragraph is used to manage content boxes on Agency landing page.

French label : Bloc de réassurance Agence
### Fields

|Name            |Label (fr)   |Machine name         |Type                                   |Description/Options       |Help Text (fr)                                                                            |
|----------------|-------------|---------------------|---------------------------------------|--------------------------|------------------------------------------------------------------------------------------|
|Title           |Titre        |field_alb_title      |Text &#124; Text field                      |                          |Le titre est optionnel.                                                                   |
|Background image|Image de fond|field_alb_bg_image   |Reference &#124; Image                      |                          |Définissez l’image de fond du bloc de réassurance. Taille recommandée : 948 x 517 pixels. |
|Description     |Description  |field_alb_description|Text &#124; Text area (Format : Description)|                          |Ajoutez la description courte du bloc de réassurance.                                     |
|URL             |             |field_alb_url        |Link &#124; Link                            |URL only + open in new tab|                                                                                          |


## **Agency Marker Icon (agency\_marker\_icon)**
This paragraph is used to manage marker icons on google map on Agency landing page.

French label : Icône Marqueur carte 
### Fields

|Name|Label (fr)|Machine name  |Type                     |Description/Options                                                                                    |Help Text (fr)                                                       |
|----|----------|--------------|-------------------------|-------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
|Type|Type      |field_ami_type|List (text) &#124; Select list|Agency, Agency Highlighted Showroom,  Showroom Highlighted Agency+Showroom, Agency+Showroom Highlighted|Sélectionnez un élément dans ce champ, afin de lui associer un icône.|
|Icon|Icône     |field_ami_icon|File                     |svg                                                                                                    |Définissez l’icône associé au type sélectionné.                      |


## **Agency service Icon (agency\_service\_icon)**
This paragraph is used to manage service icon on agency page.

French label : Icône Service Agence
### Fields

|Name      |Label (fr)|Machine name      |Type                   |Description/Options                                    |Help Text (fr)                                                                                                                                                                                                         |
|----------|----------|------------------|-----------------------|-------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Title*    |Service   |field_asi_id      |Remote (agency service)|Widget &#124; Select list                                   |Sélectionnez un Service dans la liste.                                                                                                                                                                                 |
|Icon      |Icône SVG |field_asi_icon    |File                   |Allowed file extensions: svg File directory: svg_custom|Définissez l’icône SVG à associer au Service sélectionné. L’icône sera affiché sur la page Agence détail proposant ce Service. Si l’icône PNG est également renseigné, alors ce dernier s’affichera à la place du SVG. |
|Icon (png)|Icône PNG |field_asi_icon_png|File                   |Allowed file extensions: png                           |Définissez l’icône PNG à associer au Service sélectionné. L’icône sera affiché sur la page Agence détail proposant ce Service.                                                                                         |


## **Checkout Delivery Note (checkout\_delivery\_note)**
This paragraph is used to manage checkout notes on delivery step.

French label : Réassurance Livraison
### Fields

|Name |Label (fr)|Machine name  |Type                      |Description/Options            |Help Text (fr)                      |
|-----|----------|--------------|--------------------------|-------------------------------|------------------------------------|
|Text*|Texte     |field_cdn_text|Text area (decorated text)|                               |Définissez la phrase de réassurance.|
|Icon*|Icône     |field_cdn_icon|File                      |type: svg directory: svg_custom|Définissez l’icône de réassurance.  |


## **Homepage Products Grid (homepage\_products\_grid)**
This paragraph is used to manage homepage products grid.

French label : Grille de produits Page d’accueil 
### Fields

|Name            |Label (fr)            |Machine name                 |Type             |Description/Options  |Help Text (fr)                                                                                                                      |
|----------------|----------------------|-----------------------------|-----------------|---------------------|------------------------------------------------------------------------------------------------------------------------------------|
|Content         |Contenu               |                             |Details          |                     |                                                                                                                                    |
|Subtitle*       |Surtitre              |field_hppg_subtitle          |Text field       |                     |                                                                                                                                    |
|Title*          |Titre                 |field_hppg_title             |Text field       |                     |                                                                                                                                    |
|Background color|Couleur de fond       |field_hppg_bg_color          |Colorpicker      |                     |Définissez la couleur de fond du bloc (à utiliser si vous ne souhaitez pas avoir d’image de fond).                                  |
|Background image|Image de fond         |field_hppg_bg_image          |Image            |                     |Définissez l’image de fond affichée en haut à gauche du bloc (à utiliser si vous ne souhaitez pas avoir de couleur de fond).        |
|Color*          |Couleur               |field_hppg_color             |Colorpicker      |                     |Définissez la couleur du trait affiché en haut à gauche du bloc.                                                                    |
|Products*       |Produits              |field_hppg_products          |Remote (product) |Multiple             |Sélectionnez les produits affichés dans le bloc.                                                                                    |
|Early birds     |Early Birds           |                             |                 |Fieldset             |                                                                                                                                    |
|Widget ID       |Widget ID             |field_hppg_eb_widget_id      |Text             |                     |Renseignez le widget ID Early Birds.                                                                                                |
|Category ID     |Catégorie             |field_hppg_eb_category_id    |Remote (category)|Widget &#124; Autocomplete|Renseignez une Catégorie (optionnel).                                                                                               |
|Publish         |Publication           |                             |                 |Fieldset             |                                                                                                                                    |
|Publish Date    |Date de publication   |field_hpp_publish_date       |Date             |                     |Renseignez la date à laquelle le contenu sera automatiquement publié.                                                               |
|Publish time    |Heure de publication  |field_hpp_publish_date_time  |Time             |                     |Renseignez l’heure à partir de laquelle le contenu sera automatiquement publié. Par défaut le champ heure est vide et égale à 00h00.|
|Unpublish Date  |Date de dépublication |field_hpp_unpublish_date     |Date             |                     |Renseignez la date à laquelle le contenu sera automatiquement dépublié.                                                             |
|Unpublish time  |Heure de dépublication|field_hpp_unpublish_date_time|Time             |                     |Renseignez l’heure à partir de laquelle le contenu sera automatiquement dépubliqué.                                                 |
|Visibilité      |Visibilité            |field_par_role_access        |Roles Access     |                     |                                                                                                                                    |


## **Homepage Products List (homepage\_products\_list)**
This paragraph is used to manage homepage products list.

French label : Carrousel de produits Page d’accueil
### Fields

|Name          |Label (fr)            |Machine name                 |Type            |Description/Options|Help Text (fr)                                                                                                                      |
|--------------|----------------------|-----------------------------|----------------|-------------------|------------------------------------------------------------------------------------------------------------------------------------|
|Content       |Contenu               |                             |Details         |                   |                                                                                                                                    |
|Title*        |Titre                 |field_hppl_title             |Text field      |                   |                                                                                                                                    |
|Products*     |Produits              |field_hppl_products          |Remote (product)|Multiple           |Sélectionnez les produits affichés dans le bloc.                                                                                    |
|Early birds   |Early Birds           |                             |                |Fieldset           |                                                                                                                                    |
|Widget ID     |Widget ID             |field_hppl_eb_widget_id      |Text            |                   |Renseignez le widget ID Early Birds.                                                                                                |
|Publish       |Publication           |                             |                |Fieldset           |                                                                                                                                    |
|Publish Date  |Date de publication   |field_hpp_publish_date       |Date            |                   |Renseignez la date à laquelle le contenu sera automatiquement publié.                                                               |
|Publish time  |Heure de publication  |field_hpp_publish_date_time  |                |                   |Renseignez l’heure à partir de laquelle le contenu sera automatiquement publié. Par défaut le champ heure est vide et égale à 00h00.|
|Unpublish Date|Date de dépublication |field_hpp_unpublish_date     |Date            |                   |Renseignez la date à laquelle le contenu sera automatiquement dépublié.                                                             |
|Unpublish time|Heure de dépublication|field_hpp_unpublish_date_time|                |                   |Renseignez l’heure à partir de laquelle le contenu sera automatiquement dépubliqué.                                                 |


## **Homepage Brands List (homepage\_brands\_list)**
This paragraph is used to manage homepage brands list.

French label : Liste de Marques Page d’accueil
### Fields

|Name   |Label (fr)|Machine name     |Type             |Description/Options|Help Text (fr)                                    |
|-------|----------|-----------------|-----------------|-------------------|--------------------------------------------------|
|Content|Contenu   |                 |Details          |                   |                                                  |
|Title* |Titre     |field_hpbl_title |Text field       |                   |                                                  |
|Brands*|Marques   |field_hpbl_brands|Reference (brand)|Multiple           |Sélectionnez les Marques à afficher dans le bloc. |


## <del>**Homepage Instagram Feed (homepage\_instagram\_feed)**</del>

## **Homepage Categories List (homepage\_categories\_list)**
This paragraph is used to manage homepage categories list.

French label : Liste Univers Page d’accueil
### Fields

|Name       |Label (fr)|Machine name         |Type                          |Description/Options|Help Text (fr)              |
|-----------|----------|---------------------|------------------------------|-------------------|----------------------------|
|Content    |Contenu   |                     |Details                       |                   |                            |
|Title*     |Titre     |field_hpcl_title     |Text field                    |                   |Définissez le titre du bloc.|
|Categories*|Univers   |field_hpcl_categories|Paragraphs (homepage_category)|Multiple           |                            |


## **Homepage Category (homepage\_category)**
This paragraph is used to manage homepage category item in list.

French label : Univers 

### Fields

|Name     |Label (fr)|Machine name       |Type             |Description/Options                                    |Help Text (fr)                             |
|---------|----------|-------------------|-----------------|-------------------------------------------------------|-------------------------------------------|
|Content  |Contenu   |                   |Details          |                                                       |                                           |
|Category*|Univers   |field_hpcl_cat_item|Remote (category)|                                                       |Sélectionnez un Univers parmi la liste.    |
|Icon*    |Icône     |field_hpcl_cat_icon|File             |Allowed file extensions: svg File directory: svg_custom|Associez un icône à l’Univers sélectionné. |


## **Homepage Slide (homepage\_widget\_slide)**
This paragraph is used to insert slides in ECK entity type Homepage Widget : Slider content.

French label : Bannière de carrousel Page d’accueil

### Fields

|Name               |Label (fr)            |Machine name              |Type    |Description/Options                                           |Help Text (fr)                                                                  |
|-------------------|----------------------|--------------------------|--------|--------------------------------------------------------------|--------------------------------------------------------------------------------|
|Content            |Contenu               |                          |Details |                                                              |                                                                                |
|Image              |Bannière              |field_hpws_image          |Image   |Regular image, alt field enabled, formats: png, gif, jpg, jpeg|Formats autorisés : png, gif, jpg, jpeg Dimensions recommandées : 1155 x 506 px.|
|Mobile Image       |Bannière mobile       |field_hpws_image_mob      |Image   |Regular image, alt field enabled, formats: png, gif, jpg, jpeg|Formats autorisés : png, gif, jpg, jpeg Dimensions recommandées : 1008 x 807 px.|
|Url                |Lien                  |field_hpws_url            |Url     |Url field with checkbox ‘open in new tab’                     |Optionnel.                                                                      |
|Name               |Nom (tracking)        |field_hpws_name           |Text    |NOT output on front-end                                       |Renseignez la valeur de ce champ, qui sera utilisée à des fins de tracking.     |
|Display for VI Club|Afficher pour les CLUB|field_hpws_display_vi_club|Checkbox|Used to mark specific VI Club slides.                         |Cochez cette case pour afficher la slide pour les CLUB.                         |
|Publish Date       |Date de publication   |field_hpp_publish_date    |Date    |                                                              |Renseignez la date à laquelle le contenu sera automatiquement publié.           |
|Publish time       |Heure de publication  |field_hpp_publish_time    |        |                                                              |Renseignez l’heure à partir de laquelle le contenu sera automatiquement publié  |
|Unpublish Date     |Date de dépublication |field_hpp_unpublish_date  |Date    |                                                              |Renseignez la date à laquelle le contenu sera automatiquement dépublié.         |
|Unpublish time     |Heure de publication  |field_hpp_unpublish_time  |        |                                                              |Renseignez l’heure à partir de laquelle le contenu sera automatiquement publié  |


## **Homepage Marketing Block (homepage\_widget\_marketing)**
This paragraph is used to insert marketing blocks in ECK entity type Homepage Widget : Marketing.

French label : Bannière Marketing Page d’accueil 

### Fields

|Name   |Label (fr)    |Machine name    |Type   |Description/Options                                           |Help Text (fr)                                                              |
|-------|--------------|----------------|-------|--------------------------------------------------------------|----------------------------------------------------------------------------|
|Content|Contenu       |                |Details|                                                              |                                                                            |
|Image* |Image         |field_hpwm_image|Image  |Regular image, alt field enabled, formats: png, gif, jpg, jpeg|Formats autorisés : png, gif, jpg, jpeg                                     |
|Url    |Lien          |field_hpwm_url  |Url    |Url field with checkbox ‘open in new tab’                     |                                                                            |
|Name   |Nom (tracking)|field_hpwm_name |Text   |NOT output on front-end                                       |Renseignez la valeur de ce champ, qui sera utilisée à des fins de tracking. |


## **Homepage Slider (homepage\_slider)**
This paragraph is used to insert blocks in slider on Homepage.

French label : Carrousel principal page d’accueil

### Fields

| Name                  | Label (fr)       | Machine name                         | Type                                 | Description/Options | Help Text (fr)                                                                                                                                                                                                                                                                  |
| --------------------- | ---------------- | ------------------------------------ | ------------------------------------ | ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Content Blocks        | Blocs de contenu |                                      |                                      | Tab                 |                                                                                                                                                                                                                                                                                 |
| Default blocks\*      | Blocs par défaut | field\_hpsl\_content\_blocks         | Paragraph (homepage\_content\_block) | Multiple (2 items ) | Ces blocs ne sont visibles que pour les visiteurs anonymes (VA, VAR) si pas de blocs dédiés configurés pour ces rôles. Un module d’ajout rapide de produits au panier est affiché pour les utilisateurs connectés (si pas de blocs dédiés configurés pour les rôles connectés). |
| Role-dependent blocks | Blocs dédiés     | field\_hpsl\_role\_dependent\_blocks | Paragraph (homepage\_slider\_block)  | Multiple            | Définissez les blocs dédiés par rôle (optionnel).                                                                                                                                                                                                                               |

## **Homepage Content Block (homepage\_content\_block)**
This paragraph is used to manage homepage default content blocks for anonymous.

French label : Bloc de contenu défaut Carrousel principal 

### Fields

|Name             |Label (fr)   |Machine name    |Type                   |Description/Options                                     |Help Text (fr)|
|-----------------|-------------|----------------|-----------------------|--------------------------------------------------------|--------------|
|Content          |Contenu      |                |Details                |                                                        |              |
|Title            |Titre        |field_hpcb_title|Text                   |                                                        |              |
|Background Image*|Image de fond|field_hpcb_image|Image                  |                                                        |              |
|Link             |Lien         |field_hbcb_link |Link                   |Open in new tab checkbox => Ouvrir dans un nouvel onglet|              |
|Description      |Description  |field_hpcb_descr|Text area (Description)|                                                        |              |


## **Homepage Marketing (homepage\_marketing)**
This paragraph is used to manage homepage marketing block.

French label :  Ligne Marketing

### Fields

| Name    | Label (fr) | Machine name      | Type                                       | Description/Options | Help Text (fr)                                                                                                                               |
| ------- | ---------- | ----------------- | ------------------------------------------ | ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Content | Contenu    |                   | Details                                    |                     |                                                                                                                                              |
| Block   | Blocs      | field\_hpm\_block | Reference (eck:homepage\_widget:marketing) | Multiple            | Sélectionnez les différents blocs marketing associés à la Ligne. Le bloc correspondant au profil et à l’agence de l’utilisateur s’affichera. |

## **Homepage Slider role-dependent block (homepage\_slider\_block)**
This paragraph is used to insert role-dependent blocks in slider on Homepage.

French label : Blocs dédiés Carousel page d’accueil

### Fields

| Name       | Label (fr) | Machine name               | Type                                                                                            | Description/Options | Help Text (fr)                                                                                                    |
| ---------- | ---------- | -------------------------- | ----------------------------------------------------------------------------------------------- | ------------------- | ----------------------------------------------------------------------------------------------------------------- |
| Blocks\*   | Blocs      | field\_hpsl\_b\_item       | Paragraph (homepage\_slider\_block\_ct, homepage\_slider\_block\_s,homepage\_slider\_block\_ct) | Multiple            | Sélectionnez les blocs à afficher à droite du carousel principal, puis sélectionnez la visibilité correspondante. |
| Visibility | Visibilité | field\_hpsl\_b\_visibility | Roles Access                                                                                    |                     | Sélectionnez la visibilité des blocs.                                                                             |

## **Homepage Slider block cart (homepage\_slider\_block\_ca)**
This paragraph is used to insert cart block in slider on Homepage. It has no fields, just points the place where to render the block.

French label : Bloc ajout rapide au panier
## **Homepage Slider block services (homepage\_slider\_block\_s)**
This paragraph is used to insert services block in slider on Homepage.

French label : Bloc Service Page d’accueil

### Fields

|Name      |Label (fr)   |Machine name           |Type  |Description/Options                      |Help Text (fr)                                                                           |
|----------|-------------|-----------------------|------|-----------------------------------------|-----------------------------------------------------------------------------------------|
|Logo*     |Logo         |field_hpsl_bs_logo     |Image |PNG                                      |Ajoutez le logo du service (Solu+, Génération Artisans)                                  |
|Title*    |Titre        |field_hpsl_bs_title    |Text  |                                         |Renseignez le titre du bloc affiché sous le logo.                                        |
|Link*     |Lien         |field_hpsl_bs_link     |Link  |Url field with checkbox ‘open in new tab’|Renseignez le lien de redirection, appliqué pour les utilisateurs non abonnés au service.|
|Link text*|Texte du lien|field_hpsl_bs_link_text|Text  |                                         |                                                                                         |
|Service   |Service      |field_hpsl_bs_service  |Select|ga&#124;Génération Artisans solu&#124;SOLU+        |Choisissez le service dans la liste déroulante.                                          |

## **Homepage Slider block content (homepage\_slider\_block\_c)**
This paragraph is used to insert content block in slider on Homepage.

French label : Bloc contenu Page d’accueil

### Fields

|Name           |Label (fr)       |Machine name         |Type       |Description/Options                                           |Help Text (fr)                                                                                                       |
|---------------|-----------------|---------------------|-----------|--------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|
|Image          |Visuel           |field_hpsl_bc_image  |Image      |Regular image, alt field enabled, formats: png, gif, jpg, jpeg|Renseignez le visuel du bloc.                                                                                        |
|Color          |Couleur de fond  |field_hpsl_bc_color  |Colorpicker|                                                              |Renseignez la couleur de fond du bloc. Si le visuel est également contribué, alors ce dernier s’affiche sur le front.|
|Url            |Lien             |field_hpsl_bc_link   |Url        |Url field with checkbox ‘open in new tab’                     |Renseignez le lien de redirection, ainsi que son label.                                                              |
|Upper title    |Surtitre         |field_hpsl_bc_uptitle|Text       |                                                              |Renseignez le surtitre (optionnel).                                                                                  |
|Title          |Titre            |field_hpsl_bc_title  |Text       |                                                              |Renseignez le titre du bloc.                                                                                         |
|Overlay opacity|Opacité du filtre|field_hpsl_bc_opacity|Number     |Float (0.0 - 1.0)                                             |Renseignez le degré d’opacité du filtre appliqué sur le bloc.                                                        |
|Name           |Nom (tracking)   |field_hpsl_bc_name   |Text       |NOT output on front-end                                       |Renseignez la valeur de ce champ, qui sera utilisée à des fins de tracking.                                          |


## **Ligne Wysiwyg No JS (SEO)**
This paragraph is used to add Product names + Product URLs, for SEO purposes.

### Fields

| Name          | Label (fr)    | Machine name                     | Type                                 | Description/Options | Help Text (fr)                                                                                                                                        |
| ------------- | ------------- | -------------------------------- | ------------------------------------ | ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| Content       | Contenu       |                                  | Details                              |                     |                                                                                                                                                       |
| No JS Content | Contenu no JS | field\_homepage\_no\_js\_content | Text field (advanced decorated text) |                     | Ajoutez les noms des produits et leurs URLs. Ce bloc est à destination des moteurs de recherche, il n’est affiché que si le Javascript est désactivé. |

## **Pages metatag (pages\_metatag)**
This paragraph is used to manage metatag for pages.

French label : Metatags des Pages
### Fields

|Name     |Label (fr)|Machine name    |Type             |Description/Options       |Help Text (fr)|
|---------|----------|----------------|-----------------|--------------------------|--------------|
|Content  |Contenu   |                |Details          |                          |              |
|Url*     |URL       |field_pm_url    |Text &#124; Text field|Widget &#124; Select pages list|              |
|Metatags*|Metatags  |field_pm_metatag|Metatags         |                          |              |


## **Testimonial (testimonial)**
This paragraph is used to manage testimonials.

French label : Temoignage
### Fields

|Name    |Label (fr)|Machine name             |Type                      |Description/Options|Help Text (fr)                  |
|--------|----------|-------------------------|--------------------------|-------------------|--------------------------------|
|Content |Contenu   |                         |Details                   |                   |                                |
|Image*  |Image     |field_testimonial_image  |Image                     |                   |                                |
|Text*   |Texte     |field_testimonial_text   |Text area (decorated text)|                   |                                |
|Name*   |Auteur    |field_testimonial_name   |Text field                |                   |Nom de l’auteur du témoignage   |
|Address*|Adresse   |field_testimonial_address|Text field                |                   |Code postal et ville de l’auteur|


## **Categories reference list (categories\_reference\_list)**
This paragraph is used to manage category reference for category landing page.

French label : Liste de Univers Categorie
### Fields

|Name     |Label (fr)|Machine name       |Type                          |Description/Options|Help Text (fr)          |
|---------|----------|-------------------|------------------------------|-------------------|------------------------|
|Content  |Contenu   |                   |Details                       |                   |                        |
|Category*|Catégorie |field_crl_reference|Paragraph (category_reference)|Multiple           |Renseignez la catégorie.|


## **Category reference (category\_reference)**
This paragraph is used to manage category reference for categories reference list.

French label : Univers Categorie
### Fields

|Name     |Label (fr)|Machine name      |Type             |Description/Options  |Help Text (fr)                          |
|---------|----------|------------------|-----------------|---------------------|----------------------------------------|
|Image*   |Image     |field_cr_image    |Image            |                     |Définissez la vignette de la catégorie. |
|Category*|Catégorie |field_cr_reference|Remote (category)|Widget &#124; Autocomplete|Renseignez la catégorie.                |


## **Line Search bar (line\_search\_bar)**
This paragraph is used to insert search line.

French label : Configurez la barre de recherche
### Fields

| Name    | Label (fr) | Machine name      | Type    | Description/Options | Help Text (fr)                               |
| ------- | ---------- | ----------------- | ------- | ------------------- | -------------------------------------------- |
| Content | Contenu    |                   | Details |                     |                                              |
| Title   | Titre      | field\_lsb\_title | Text    |                     | Renseignez le titre de la barre de recherche |

## **Line Early birds (line\_early\_birds)**
This paragraph is used to insert the Early Birds line.

French label : Configurez le widget EB de la page de recherche
### Fields

| Name      | Label (fr) | Machine name               | Type    | Description/Options | Help Text (fr)                       |
| --------- | ---------- | -------------------------- | ------- | ------------------- | ------------------------------------ |
| Content   | Contenu    |                            | Details |                     |                                      |
| Title     | Titre      | field\_leb\_title          | Text    |                     | Renseignez le titre du widget EB     |
| Widget ID | Widget ID  | field\_leb\_eb\_widget\_id | Text    |                     | Renseignez le widget ID Early Birds. |

## **Category Products Grid (category\_products\_grid)**
This paragraph is used to manage products grid on category landing page.

French label : Grille de produits Landing Catégorie
### Fields

| Name        | Label (fr)  | Machine name                 | Type              | Description/Options   | Help Text (fr)                                                                                              |
| ----------- | ----------- | ---------------------------- | ----------------- | --------------------- | ----------------------------------------------------------------------------------------------------------- |
| Content     | Contenu     |                              | Details           |                       |                                                                                                             |
| Title       | Titre       | field\_cpg\_title            | Text field        |                       | Renseignez le titre du bloc. Si laissé vide, alors le titre par défaut “Nos meilleures ventes” s’affichera. |
| Products    | Produits    | field\_cpg\_products         | Remote (product)  | Multiple, not limited | Sélectionnez les produits affichés dans le bloc.                                                            |
| Early birds | Early Birds |                              |                   | Fieldset              |                                                                                                             |
| Widget ID   | Widget ID   | field\_cpg\_eb\_widget\_id   | Text              |                       | Renseignez le widget ID Early Birds.                                                                        |
| Category ID | Catégorie   | field\_cpg\_eb\_category\_id | Remote (category) | Widget | Autocomplete | Renseignez une catégorie (optionnel).                                                                       |

## **Category marketing block (category\_marketing)**
This paragraph is used to insert marketing block line on category landing page.
French label : Encart Marketing

### Fields

|Name           |Label (fr)          |Machine name                   |Type                       |Description/Options                                                                                                             |Help Text (fr)                                                                                    |
|---------------|--------------------|-------------------------------|---------------------------|--------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
|Content        |Contenu             |                               |Details                    |                                                                                                                                |                                                                                                  |
|Type*          |Variante d’affichage|field_category_marketing_type  |Text                       |Widget &#124; Select list Options :</br> 100</br> 50 / 50</br> 66 / 33</br> 33 / 66</br> 33 / 33 / 33</br> 50 / 25 / 25</br> 25 / 50 / 25</br> 25 / 25 / 50</br> 25 / 25 / 25 / 25|Sélectionnez la variante d’affichage.                                                             |
|Marketing Block|Bannière Marketing  |field_category_marketing       |Paragraph (marketing_block)|Multiple                                                                                                                        |Ajoutez une ou plusieurs bannières marketing en fonction de la variante d’affichage sélectionnée. |
|Visibilité     |Visibilité          |field_category_marketing_access|Roles Access               |                                                                                                                                |Définissez la visibilité de l’encart Marketing.                                                   |


## **Category slider(category\_slider)**
This paragraph is used to insert category slider block line on category landing page. 

French label : 

### Fields

| Name        | Label (fr) | Machine name        | Type                                                                                                                                      | Description/Options | Help Text (fr)                                |
| ----------- | ---------- | ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | --------------------------------------------- |
| Title       | Titre      | field\_cs\_title    | Text                                                                                                                                      |                     | Renseignez le titre du carrousel.             |
| Slide\*     | Slide      | field\_cs\_slide    | Paragraoh([category\_slide](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.sa1ri56s9y11)) |                     | Ajoutez une ou plusieurs slides au carrousel. |
| Role access | Visibilité | field\_role\_access | Roles Access                                                                                                                              |                     | Définissez la visibilité du carrousel.        |

## **Category slide(category\_slide)**
This paragraph is used to insert category slide on slider block line on category landing page. 

French label : 

### Fields

| Name           | Label (fr)            | Machine name                | Type                                 | Description/Options | Help Text (fr)                                             |
| -------------- | --------------------- | --------------------------- | ------------------------------------ | ------------------- | ---------------------------------------------------------- |
| Image\*        | Image                 | field\_cs\_image            | Image                                |                     | Choisissez l’image à afficher dans la slide.               |
| Link\*         | Lien                  | field\_cs\_link             | Link (with option Open in a new tab) |                     | Renseignez le lien à afficher dans la slide.               |
| Tag            | Texte                 | field\_cs\_tag\_text        | Text                                 |                     |                                                            |
| Tag text color | Couleur du texte      | field\_cs\_tag\_text\_color | Colorpicker                          |                     | Renseignez le texte du tag qui sera affiché dans la slide. |
| Tag color      | Couleur du background | field\_cs\_tag\_bg\_color   | Colorpicker                          |                     | Choisissez la couleur de fond du tag.                      |

## **Category children tree (category\_children\_tree)**
This paragraph is used to insert category children tree block line on category landing page. It has no fields, just points the place where to render the block.
French label : Arborescence Categorie

### Fields

| Name | Label (fr) | Machine name | Type | Description/Options | Help Text (fr) |
| ---- | ---------- | ------------ | ---- | ------------------- | -------------- |
|      |            |              |      |                     |                |

## **Category SEO (category\_seo)**
This paragraph is used to insert SEO block line on category landing page.
French label : Bloc SEO - Landing Categorie

### Fields

| Name    | Label (fr)  | Machine name               | Type                               | Description/Options | Help Text (fr)             |
| ------- | ----------- | -------------------------- | ---------------------------------- | ------------------- | -------------------------- |
| Content | Contenu     |                            | Details                            |                     |                            |
| SEO     | Contenu SEO | field\_category\_seo\_text | Textarea (advanced decorated text) |                     | Renseignez le contenu SEO. |

## **Dropdown main menu item (esdb\_main\_menu\_item)**
This paragraph is used to insert items to 2nd level of main menu.
French label : Elément menu niveau 2

### Fields

| Name    | Label (fr) | Machine name       | Type                                 | Description/Options | Help Text (fr)                                          |
| ------- | ---------- | ------------------ | ------------------------------------ | ------------------- | ------------------------------------------------------- |
| Content | Contenu    |                    | Details                              |                     |                                                         |
| Image\* | Image      | field\_emmi\_image | Image                                |                     | Ajoutez l’image de l’élément de menu.                   |
| Link\*  | Lien       | field\_emmi\_link  | Link (with option Open in a new tab) |                     | Ajoutez le label et l’URL du lien de l’élément de menu. |

## **Mega menu item (mega\_menu\_item)**
This paragraph is used to insert items to 2nd level of main menu.
French label : Menu principal avancé

### Fields

|Name            |Label (fr)                           |Machine name        |Type                           |Description/Options                  |Help Text (fr)                                                                                             |
|----------------|-------------------------------------|--------------------|-------------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------|
|Content         |Contenu                              |                    |Details                        |                                     |                                                                                                           |
|Menu item       |Elément de menu niveau 1             |field_mmi_item      |Text field                     |First level menu Widget &#124; Select list|Sélectionnez l’élément de menu niveau 1 préalablement créé via l’administration du menu principal du site. |
|Menu items      |Eléments de menu niveau 2            |field_mmi_items     |Paragraph (esdb_main_menu_item)|                                     |Définissez les éléments de niveau 2 (enfants de l’élément de menu niveau 1).                               |
|Background color|Couleur de fond                      |field_mmi_color     |Colorpicker                    |                                     |Définissez la couleur de fond du menu.                                                                     |
|Text color      |Couleur des éléments de menu niveau 2|field_mmi_text_color|Colorpicker                    |                                     |Définissez la couleur des éléments de menu niveau 2.                                                       |


## **Edito grid block (edito\_grid)**
This paragraph is used to insert Edito grid block line.
French label : Bloc Grille 

### Fields

| Name    | Label (fr) | Machine name     | Type                                                                                                                                   | Description/Options             | Help Text (fr)                                                                       |
| ------- | ---------- | ---------------- | -------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------- | ------------------------------------------------------------------------------------ |
| Content | Contenu    |                  | Details                                                                                                                                |                                 |                                                                                      |
| Title\* | Titre      | field\_eg\_title | Text field                                                                                                                             |                                 |                                                                                      |
| CTA     | CTA        | field\_eg\_cta   | Link                                                                                                                                   | With option “Open in a new tab” | Renseignez le titre et le label du CTA affiché en haut à droite du bloc (optionnel). |
| Item    | Elément    | field\_eg\_item  | Paragraph ([edito\_grid\_item](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.nwp17c)) | Multiple                        | Ajoutez des éléments au bloc.                                                        |

## **Edito grid item (edito\_grid\_item)**
This paragraph is used to insert Edito grid item.

French label : Elément bloc grille
### Fields

| Name    | Label (fr) | Machine name      | Type  | Description/Options             | Help Text (fr)                               |
| ------- | ---------- | ----------------- | ----- | ------------------------------- | -------------------------------------------- |
| Image\* | Image      | field\_egi\_image | Image |                                 | Ajoutez l’image de l’élément.                |
| Links\* | Lien       | field\_egi\_link  | Link  | With option “Open in a new tab” | Ajouter le lien de redirection de l’élément. |

## **Surface option (surface\_option)**
This paragraph is used to create Surface select list on Style & Solution list page.

French label : Intervalle Surface ESDB
### Fields

| Name  | Label (fr)  | Machine name           | Type    | Description/Options | Help Text (fr)                                                      |
| ----- | ----------- | ---------------------- | ------- | ------------------- | ------------------------------------------------------------------- |
| Title | Titre       | field\_so\_title       | text    |                     | Le titre est affiché en front, dans la drop-down du filtre Surface. |
| From  | A partir de | field\_so\_range\_from | decimal |                     | Définissez la valeur de début de l’intervalle.                      |
| To    | Jusqu’à     | field\_so\_range\_to   | decimal |                     | Définissez la valeur de fin de l’intervalle.                        |

## **Advice document (advice\_document)**
This paragraph is used to insert document in Advice detail page.
French label : Document Conseils

### Fields

| Name      | Label (fr) | Machine name         | Type       | Description/Options                                                          | Help Text (fr)                                                                                |
| --------- | ---------- | -------------------- | ---------- | ---------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| Title\*   | Titre      | field\_ad\_title     | Text field |                                                                              |                                                                                               |
| Thumbnail | Vignette   | field\_ad\_thumbnail | Image      |                                                                              | Ajoutez une vignette au document. Taille recommandée : 474x673 pixels.                        |
| File      | Document   | field\_ad\_file      | File       | Authorized extensions : png, jpg, jpeg, doc, docx, ppt, pptx, xls, xlsx, pdf | Ajoutez le document. Formats autorisés : png, jpg, jpeg, doc, docx, ppt, pptx, xls, xlsx, pdf |

## **Catalog per area (catalog\_per\_area)**
This paragraph is used to insert ‘Catalog Per Area’ block in Catalog detail page.
French label : Catalogues par région 

### Fields

| Name    | Label (fr)                  | Machine name       | Type                             | Description/Options   | Help Text (fr)                                                                              |
| ------- | --------------------------- | ------------------ | -------------------------------- | --------------------- | ------------------------------------------------------------------------------------------- |
| Title\* | Titre                       | field\_cpa\_title  | Text field                       |                       | Renseignez le titre du bloc “Catalogues par régions”.                                       |
| Blocks  | Blocs Catalogues par région | field\_cpa\_blocks | Paragraph (catalog\_cpa\_blocks) | Multiple, 5 items max | Ajoutez des blocs “Catalogues par région”, et renseignez les liens pour chaque bloc ajouté. |

## **Catalog per area blocks (catalog\_cpa\_blocks)**
This paragraph is used to insert ‘Catalog Per Area info’ block in Catalog detail page.
French label : Catalogues par région - colonnes

### Fields

| Name       | Label (fr)  | Machine name       | Type                       | Description/Options                                   | Help Text (fr)                                            |
| ---------- | ----------- | ------------------ | -------------------------- | ----------------------------------------------------- | --------------------------------------------------------- |
| Title\*    | Titre       | field\_cpab\_title | Text field                 |                                                       |                                                           |
| Short text | Description | field\_cpab\_text  | Text area (decorated text) | Decorated text                                        | Renseignez la description du bloc “Catalogues par région” |
| Links      | Liens       | field\_cpab\_links | Link                       | Multiple (unlimited), with option “Open in a new tab” | Ajoutez les liens (titre + URL) de chaque catalogue.      |

## **Catalog text image (catalog\_text\_image)**
This paragraph is used to insert ‘Text Image’ block in Catalog detail page.
French label : Catalogue - zone texte et image

### Fields

|Name                         |Label (fr)         |Machine name        |Type                      |Description/Options                                                         |Help Text (fr)                                                                  |
|-----------------------------|-------------------|--------------------|--------------------------|----------------------------------------------------------------------------|--------------------------------------------------------------------------------|
|Title*                       |Titre              |field_cti_title     |Text field                |                                                                            |                                                                                |
|The title is hide on the page|Masquer le titre   |field_cti_title_hide|Text field                |Hide                                                                        |Si activé, le titre ne sera pas affiché en front sur la page.                   |
|Text                         |Texte              |field_cti_text      |Text area (decorated text)|                                                                            |Renseignez le texte du bloc.                                                    |
|Image*                       |Visuel             |field_cti_image     |Image                     |                                                                            |Renseignez le visuel du bloc.                                                   |
|Position                     |Position de l’image|field_cti_position  |List (text) &#124; Select list |Variants of image position (left/right), two required values (radio buttons)|Sélectionnez la position de l’image (droite / gauche).                          |
|CTA                          |CTA                |field_cti_cta       |Link                      |With option open in new tab Do not display if not filled                    |Définissez le lien et le label du CTA. Le CTA ne sera affiché que si renseigné. |


## **Catalog text columns (catalog\_text\_columns)**
This paragraph is used to insert ‘Text 2 columns’ block in Catalog detail page.
French label : Catalogue - zone texte sans image 

### Fields

| Name    | Label (fr) | Machine name      | Type                       | Description/Options   | Help Text (fr)                                                                                                                                                                    |
| ------- | ---------- | ----------------- | -------------------------- | --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Title\* | Titre      | field\_ctc\_title | Text field                 |                       |                                                                                                                                                                                   |
| Text    | Texte      | field\_ctc\_text  | Text area (decorated text) | Multiple, 2 items max | Renseignez le(s texte(s) du bloc. Si vous renseignez 2 textes, chacun sera affiché sur 50% de la largeur. Si un seul texte est renseigné, il sera affiché sur 100% de la largeur. |

## **Catalog video (catalog\_video)**
This paragraph is used to insert ‘Video’ block in Catalog detail page.
French label : Catalogue - zone vidéo 

### Fields

| Name    | Label (fr)  | Machine name     | Type                       | Description/Options | Help Text (fr)                          |
| ------- | ----------- | ---------------- | -------------------------- | ------------------- | --------------------------------------- |
| Title\* | Titre       | field\_cv\_title | Text field                 |                     |                                         |
| Video\* | Vidéo       | field\_cv\_video | Video (embed)              |                     | Renseignez le lien YouTube de la vidéo. |
| Text    | Description | field\_cv\_text  | Text area (decorated text) |                     | Renseignez la description de la vidéo.  |

## **Catalog links (catalog\_links)**
This paragraph is used to insert ‘Redirect list’ block in Catalog detail page.
French label : Catalogues par région - liste déroulante

### Fields

| Name            | Label (fr)           | Machine name        | Type       | Description/Options                                   | Help Text (fr)                                                                         |
| --------------- | -------------------- | ------------------- | ---------- | ----------------------------------------------------- | -------------------------------------------------------------------------------------- |
| Title\*         | Titre                | field\_cl\_title    | Text field |                                                       |                                                                                        |
| Catalog cover\* | Visuel               | field\_ct\_image    | Image      |                                                       | Renseignez le visuel du catalogue affiché dans le bloc.                                |
| Subtitle        | Sous-titre           | field\_cl\_subtitle | Text field |                                                       | Renseignez le sous-titre du bloc (exemple : “Choisissez le catalogue de votre région”) |
| Catalog list    | Liste des catalogues | field\_cl\_links    | Link       | Multiple (unlimited), with option “Open in a new tab” | Renseignez les liens (label + URL) de chacun des catalogues.                           |

## **Quick access links (quick\_access\_links)**
This paragraph is used to insert ‘Quick access links” to quick access dashboard.
French label : Items de Mon Espace personnel

### Fields

| Name       | Label (fr) | Machine name             | Type         | Description/Options               | Help Text (fr) |
| ---------- | ---------- | ------------------------ | ------------ | --------------------------------- | -------------- |
| Link       | Lien       | field\_qal\_link         | Link         | (with option “Open in a new tab”) |                |
| Visibility |            | field\_par\_role\_access | Roles Access |                                   |                |

## **Quick access promo link (quick\_access\_promo\_lilnk)**
This paragraph is used to insert ‘Quick access promo link’ to quick access dashboard.
French label : Bloc de promotion du dashboard d’accès rapide à l’EMC

### Fields

| Name                 | Label (fr) | Machine name             | Type         | Description/Options               | Help Text (fr)                                                                |
| -------------------- | ---------- | ------------------------ | ------------ | --------------------------------- | ----------------------------------------------------------------------------- |
| Title\*              |            | field\_qapl\_title       | Text field   |                                   | Renseignez le titre du bloc.                                                  |
| Image\*              |            | field\_qapl\_image       | Image        |                                   | Renseignez l’image du bloc.                                                   |
| Description          |            | field\_qapl\_description | Text field   |                                   | Renseignez la description du bloc.                                            |
| Tag                  |            | field\_qapl\_tag         | Text field   |                                   | Renseignez le label du tag.                                                   |
| Tag background color |            | field\_qapl\_tag\_bg     | Colorpicker  |                                   | Choisissez la couleur de fond du tag.                                         |
| Link                 |            | field\_qapl\_link        | Link         | (with option “Open in a new tab”) | Renseignez l’URL vers lequel l’utilisateur sera redirigé au clic sur le bloc. |
| Visibility           |            | field\_par\_role\_access | Roles Access |                                   |                                                                               |

## **Catalog download (catalog\_download)**
This paragraph is used to insert ‘Redirect list’ block in Catalog detail page.
French label : Catalogue - téléchargement
In this block links for the download and redirect we will get from parent node ‘Catalog detail page’.

### Fields

|Name          |Label (fr)          |Machine name         |Type      |Description/Options                        |Help Text (fr)                                                                                                                                                                                    |
|--------------|--------------------|---------------------|----------|-------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Title*        |Titre               |field_cd_title       |Text field|                                           |                                                                                                                                                                                                  |
|Catalog cover*|Visuel              |field_cd_image       |Image     |                                           |Renseignez le visuel du catalogue affiché dans le bloc.                                                                                                                                           |
|Subtitle      |Sous-titre          |field_cd_subtitle    |Text field|                                           |Renseignez le sous-titre du bloc.                                                                                                                                                                 |
|View CTA      |Bouton “Voir”       |field_cd_view_cta    |Text field|Default value if not filled : “Voir”       |Renseignez le label du bouton “Visualisation”. Notez que le lien est automatiquement récupéré depuis la zone Header de la page Catalogue (si configuré)</br> - autrement le bouton ne s’affichera pas. |
|Download CTA  |Bouton “Télécharger”|field_cd_download_cta|Text field|Default value if not filled : “Télécharger”|Renseignez le label du bouton “Téléchargement”. Notez que le lien est automatiquement récupéré depuis la zone Header de la page Catalogue (si configuré)</br> - autrement le bouton ne s’affichera pas.|

## **Catalog appointment scheduler (catalog\_scheduler)**
This paragraph is used to insert ‘Appointment scheduler’ block in Catalog detail page.
French label : Prise de rendez-vous 
Fields list are empty. All data stored in ‘Content site settings’ config page.

### Fields

| Name | Label (fr) | Machine name | Type | Description/Options | Help Text (fr) |
| ---- | ---------- | ------------ | ---- | ------------------- | -------------- |
|      |            |              |      |                     |                |

## **Catalog gmap (catalog\_gmap)**
This paragraph is used to insert ‘Gmap’ block in Catalog detail page.
French label : Carte interactive

### Fields

| Name | Label (fr) | Machine name | Type | Description/Options | Help Text (fr) |
| ---- | ---------- | ------------ | ---- | ------------------- | -------------- |
|      |            |              |      |                     |                |

## **ESDB Toolbox item (esdb\_toolbox\_pdp\_item)**
This paragraph is used to.
French label : Elément Boîte à Outils ESDB

### Fields

| Name             | Label (fr)    | Machine name                | Type     | Description/Options         | Help Text (fr)                                                                 |
| ---------------- | ------------- | --------------------------- | -------- | --------------------------- | ------------------------------------------------------------------------------ |
| Icon/Image       | Icône / Image | field\_esdb\_pdp\_tb\_icon  | Image    |                             | Renseignez l’icône ou l’image de l’élément.                                    |
| Item description | Description   | field\_esdb\_pdp\_tb\_descr | Textarea |                             | Renseignez la description de l’élément (affichée si 1 seul élément configuré). |
| Item title       | Titre         | field\_esdb\_pdp\_tb\_title | Text     |                             | Renseignez le titre de l’élément.                                              |
| Link label       | Lien          | field\_esdb\_pdp\_tb\_link  | Link     | WIth option Open in new Tab | Renseignez le label et l’URL du lien de l’élément.                             |

## **ESDB Toolbox PDP (esdb\_toolbox\_pdp)**
This paragraph is used to.
French label : Boîte à Outils Produits ESDB 

### Fields

| Name  | Label (fr) | Machine name                | Type                           | Description/Options | Help Text (fr)             |
| ----- | ---------- | --------------------------- | ------------------------------ | ------------------- | -------------------------- |
| Items | Eléments   | field\_esdb\_tb\_pdp\_items | Paragraph (esdb\_toolbox\_pdp) |                     | Ajoutez un nouvel élément. |

## **Presentation Line (service\_line\_pr)**
This paragraph is used to insert Line on Service detail page.
French label : Service - ligne de présentation 

### Fields

|Name              |Label (fr)          |Machine name         |Type                     |Description/Options                                  |Help Text (fr)                                                                                                           |
|------------------|--------------------|---------------------|-------------------------|-----------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|
|Content           |Contenu             |                     |Details                  |                                                     |                                                                                                                         |
|Background color* |Couleur de fond     |field_sl_pr_bgcolor  |Colorpicker              |                                                     |Définissez la couleur de fond affichée sous le texte.                                                                    |
|Text color*       |Couleur du texte    |field_sl_pr_txtcolor |Colorpicker              |                                                     |Définissez la couleur du texte.                                                                                          |
|Description text* |Texte               |field_sl_pr_descr    |Textarea (decorated text)|                                                     |Renseignez le texte du bloc.                                                                                             |
|Media             |                    |                     |Details                  |                                                     |                                                                                                                         |
|Image             |Visuel              |field_sl_pr_image    |Image                    |                                                     |Renseignez le visuel du bloc. Si une vidéo est également renseignée, alors la vidéo sera affichée à la place de l’image. |
|Video             |                    |                     |Fieldset                 |                                                     |                                                                                                                         |
|Thumbnail         |Vignette de la vidéo|field_sl_pr_thumbnail|Image                    |                                                     |Ajoutez la vignette de la vidéo.                                                                                         |
|Video             |Vidéo               |field_sl_pr_video    |Video (embed)            |                                                     |Renseignez l’URL YouTube de la vidéo.                                                                                    |
|Ratio*            |Variante d’affichage|fiedl_sl_pr_ratio    |Select                   |⅓ texte - ⅔ media</br> ⅔ texte - ⅓ media</br> ½ texte - ½ media|Choisissez la variante d’affichage parmi les options proposées.                                                          |

## **Benefits Line (service\_line\_bnf)**
This paragraph is used to insert Line on Service detail page.
French label : Service - Ligne de bénéfices

### Fields

| Name      | Label (fr) | Machine name          | Type                                 | Description/Options       | Help Text (fr)                                                               |
| --------- | ---------- | --------------------- | ------------------------------------ | ------------------------- | ---------------------------------------------------------------------------- |
| Content   | Contenu    |                       | Details                              |                           |                                                                              |
| Title\*   | Titre      | field\_sl\_bnf\_title | Text                                 | Optional                  |                                                                              |
| Benefit\* | Bénéfice   | field\_sl\_bnf\_item  | Paragraph (service\_line\_bnf\_item) | Multiple (1 - 4 items)    | Ajoutez jusqu’à 4 items Bénéfice.                                            |
| CTA       | CTA        | field\_sl\_bnf\_cta   | Link                                 | \+ open in new tab option | Renseignez le label et le lien du bouton affiché en bas du bloc (optionnel). |

## **Benefits Line Benefit (service\_line\_bnf\_item)**
This paragraph is used to insert benefit in Service Benefits Line paragraph.
French label : Item Bénéfice	

### Fields

| Name          | Label (fr)  | Machine name                | Type                      | Description/Options | Help Text (fr)                                                                |
| ------------- | ----------- | --------------------------- | ------------------------- | ------------------- | ----------------------------------------------------------------------------- |
| Content       | Contenu     |                             | Details                   |                     |                                                                               |
| Icon\*        | Icône       | field\_sl\_bnf\_item\_icon  | Image                     | PNG                 | Renseignez l’icône du Bénéfice (format PNG avec fond transparent privilégié). |
| Description\* | Description | field\_sl\_bnf\_item\_descr | Textarea (decorated text) |                     | Ajoutez la description du Bénéfice.                                           |

## **Rich Offers Line (service\_line\_rich\_off)**
This paragraph is used to insert Line on Service detail page.
French label : Service - Offre riche				

### Fields

| Name        | Label (fr)  | Machine name                | Type                              | Description/Options       | Help Text (fr)                                                               |
| ----------- | ----------- | --------------------------- | --------------------------------- | ------------------------- | ---------------------------------------------------------------------------- |
| Content     | Contenu     |                             | Details                           |                           |                                                                              |
| Title\*     | Titre       | field\_sl\_rich\_off\_title | Text                              |                           |                                                                              |
| CTA         | Bouton      | field\_sl\_rich\_off\_cta   | Link                              | \+ open in new tab option | Renseignez le label et le lien du bouton affiché en bas du bloc (optionnel). |
| Description | Description | field\_sl\_rich\_off\_descr | Textarea (decorated text)         |                           | Renseignez la description affichée en bas du bloc (optionnel).               |
| Items       | Contenu     |                             | Details                           |                           |                                                                              |
| Items\*     | Offres      | field\_sl\_rich\_off\_item  | Paragraph (rich\_off\_line\_item) | Multiple (1 - 4 items)    | Renseignez jusqu’à 4 offres.                                                 |


## **Rich Offers Line Item (rich\_off\_line\_item)**
This paragraph is used to insert Line on Rich Offers Line on Service detail page.
French label : Item Offre riche

### Fields

|Name        |Label (fr)  |Machine name     |Type                              |Description/Options         |Help Text (fr)                                                                                   |
|------------|------------|-----------------|----------------------------------|----------------------------|-------------------------------------------------------------------------------------------------|
|Content     |Contenu     |                 |Details                           |                            |                                                                                                 |
|Title*      |Titre       |field_roli_title |Text                              |                            |                                                                                                 |
|Price*      |Prix 1      |field_roli_price |Text                              |                            |Renseignez le prix, la devise et le label de la taxe (par exemple : 290 € HT).                   |
|Title 2*    |Sous-titre 1|field_roli_title2|Text                              |                            |Renseignez le sous-titre (par exemple : “Ambassadeurs”)                                          |
|Price 2*    |Prix 2      |field_roli_price2|Text                              |                            |Renseignez le prix, la devise et le label de la taxe (par exemple : 189 € HT).                   |
|Description*|Sous-titre 2|field_roli_descr |Text                              |                            |Renseignez le sous-titre (par exemple : “101€ d’économie”)                                       |
|Link        |Lien        |field_roli_link  |Link                              |URL + open in new tab option|Renseignez le lien de l’offre (optionnel).                                                       |
|Content     |Contenu     |                 |Details                           |                            |                                                                                                 |
|Advantages* |Avantages   |field_roli_adv   |Paragraph (rich_off_line_item_adv)|Multiple                    |Renseignez les avantages de l’offre (nombre illimité), composés d’un icône et d’une description. |


## **Rich Offers Line Item Advantage (rich\_off\_line\_item\_adv)**
This paragraph is used to insert Advantage item in list of Line on Rich Offers Line on Service detail page.
French label : Item avantage Offre riche		

### Fields

| Name          | Label (fr)  | Machine name        | Type    | Description/Options | Help Text (fr)                              |
| ------------- | ----------- | ------------------- | ------- | ------------------- | ------------------------------------------- |
| Content       | Contenu     |                     | Details |                     |                                             |
| Icon\*        | Icône       | field\_rolia\_icon  | Image   | PNG                 | Ajoutez l’icône de l’avantage (format PNG). |
| Description\* | Description | field\_rolia\_descr | Text    |                     | Renseignez la description de l’avantage.    |

## **Standard Offers Line (service\_line\_st\_off)**
This paragraph is used to insert Line on Service detail page.
French label : Service - Offre standard

### Fields

| Name        | Label (fr)  | Machine name              | Type                            | Description/Options    | Help Text (fr)                                                               |
| ----------- | ----------- | ------------------------- | ------------------------------- | ---------------------- | ---------------------------------------------------------------------------- |
| Content     | Contenu     |                           | Details                         |                        |                                                                              |
| Title\*     | Titre       | field\_sl\_st\_off\_title | Text                            |                        |                                                                              |
| CTA         | Bouton      | field\_sl\_st\_off\_cta   | Link                            |                        | Renseignez le label et le lien du bouton affiché en bas du bloc (optionnel). |
| Description | Description | field\_sl\_st\_off\_descr | Textarea (decorated text)       |                        | Renseignez la description affichée en bas du bloc (optionnel).               |
| Content     | Contenu     |                           | Details                         |                        |                                                                              |
| Item\*      | Item        | field\_sl\_st\_off\_item  | Paragraph (st\_off\_line\_item) | Multiple (1 - 4 items) | Renseignez de 2 à 4 items Offre Standard.                                    |

## **Standard Offers Line Item (st\_off\_line\_item)**
This paragraph is used to insert Line item on Standard Offers Line on Service detail page.
French label : Item Offre standard

### Fields

| Name              | Label (fr)               | Machine name              | Type        | Description/Options          | Help Text (fr)                                                                                                  |
| ----------------- | ------------------------ | ------------------------- | ----------- | ---------------------------- | --------------------------------------------------------------------------------------------------------------- |
| Content           | Contenu                  |                           | Details     |                              |                                                                                                                 |
| Icon              | Icône                    | field\_soli\_icon         | Image       | PNG                          | Ajoutez l’icône de l’offre (format PNG).                                                                        |
| Top Text          | Texte haut               | field\_soli\_top\_text    | Text        |                              | Renseignez le texte affiché en haut de l’offre. Si l’icône est également configurée, alors l’icône s’affichera. |
| Title\*           | Titre                    | field\_soli\_title        | Text        |                              | Renseignez le titre (par exemple : Offre pro)                                                                   |
| Price Top Text    | Texte au dessus du prix  | field\_soli\_price\_text1 | Text        |                              | Renseignez le texte affiché au dessus du prix (par exemple : “à partir de”). Optionnel                          |
| Price\*           | Prix                     | field\_soli\_price        | Text        |                              | Renseignez le prix, la devise et le label de la taxe (par exemple : 290 € HT).                                  |
| Price Bottom Text | Texte en dessous du prix | field\_soli\_price\_text2 | Text        |                              | Renseignez le texte affiché en dessous du prix (par exemple : “par mois”). Optionnel                            |
| Bottom Text       | Text bas                 | field\_soli\_btext        | Text        |                              | Renseignez le texte affiché en bas de l’offre (optionnel).                                                      |
| Background color  | Couleur de fond          | field\_soli\_bgcolor      | Colorpicker |                              | Renseignez la couleur de fond de l’offre.                                                                       |
| Text Color        | Couleur du texte         | field\_soli\_txtcolor     | Colorpicker |                              | Renseignez la couleur du texte de l’offre.                                                                      |
| Link              | Lien                     | field\_soli\_link         | Link        | URL + open in new tab option | Renseignez le lien de l’offre (optionnel).                                                                      |

## **Simple Offers Line (service\_line\_sm\_off)**
This paragraph is used to insert Line on Service detail page.
French label : Service - Offre simple

### Fields

| Name        | Label (fr)  | Machine name              | Type                            | Description/Options       | Help Text (fr)                                                               |
| ----------- | ----------- | ------------------------- | ------------------------------- | ------------------------- | ---------------------------------------------------------------------------- |
| Content     | Contenu     |                           | Details                         |                           |                                                                              |
| Title\*     | Titre       | field\_sl\_sm\_off\_title | Text                            |                           |                                                                              |
| CTA         | Bouton      | field\_sl\_sm\_off\_cta   | Link                            | \+ open in new tab option | Renseignez le label et le lien du bouton affiché en bas du bloc (optionnel). |
| Description | Description | field\_sl\_sm\_off\_descr | Textarea (decorated text)       |                           | Renseignez la description affichée en bas du bloc (optionnel).               |
| Content     | Contenu     |                           | Details                         |                           |                                                                              |
| Items\*     | Item        | field\_sl\_sm\_off\_item  | Paragraph (sm\_off\_line\_item) | Multiple (1 - 4 items)    | Renseignez de 1 à 4 items Offre simple.                                      |

## **Simple Offers Line Item (sm\_off\_line\_item)**
This paragraph is used to insert Line item on Simple Offers Line on Service detail page.
French label : Item Offre simple

### Fields

| Name    | Label (fr) | Machine name            | Type                                  | Description/Options          | Help Text (fr)                                                 |
| ------- | ---------- | ----------------------- | ------------------------------------- | ---------------------------- | -------------------------------------------------------------- |
| Content | Contenu    |                         | Details                               |                              |                                                                |
| Icon    | Logo       | field\_smli\_icon       | Image                                 | PNG                          |   Ajoutez le logo de l’offre (format PNG).                     |
| Title\* | Titre      | field\_smli\_title      | Text                                  |                              |                                                                |
| Link    | Lien       | field\_smli\_link       | Link                                  | URL + open in new tab option | Renseignez le lien de l’offre (optionnel).                     |
| Content | Contenu    |                         | Details                               |                              |                                                                |
| Text\*  | Paragraphe | field\_smli\_text\_item | Paragraph (sm\_off\_line\_item\_text) | Multiple                     | Ajoutez un ou plusieurs paragraphes de description de l’offre. |

## **Simple Offers Line Item Text (sm\_off\_line\_item\_text)**
This paragraph is used to insert Text in Line item on Simple Offers Line on Service detail page.
French label : Item paragraphe Offre simple					

### Fields

| Name        | Label (fr)    | Machine name        | Type    | Description/Options | Help Text (fr)                                                                        |
| ----------- | ------------- | ------------------- | ------- | ------------------- | ------------------------------------------------------------------------------------- |
| Content     | Contenu       |                     | Details |                     |                                                                                       |
| Text        | Description 1 | field\_smlit\_text  | Text    |                     | Renseignez la description 1 de l’offre.                                               |
| Description | Description 2 | field\_smlit\_descr | Text    |                     | Renseignez la description 2 de l’offre (affichée en plus petit que la description 1). |

## **W2S Sticky Bar (w2s\_sticky\_bar)**
This paragraph is used to insert Sticky Bars on W2S Pages.
French label : Barre sticky Web to Showroom

### Fields

|Name      |Label (fr)  |Machine name    |Type   |Description/Options                                                                                                         |Help Text (fr)                                                                                     |
|----------|------------|----------------|-------|----------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
|Content   |Contenu     |                |Details|                                                                                                                            |                                                                                                   |
|Page type*|Type de page|field_w2ssb_type|List   |Options :</br> Page Landing&#124;landing</br> Page détail&#124;detail</br> Mur inspirationnel&#124;inspiration</br> Quiz&#124;quiz_form</br> Résultat du Quiz&#124;quiz_result|Sélectionnez les pages de la section Web to Showroom sur lesquelles la barre sticky sera affichée. |
|CTA*      |CTA         |field_w2ssb_cta |Url    |+ Open in new tab                                                                                                           |Renseignez le lien du CTA.                                                                         |

## **W2S Quiz Detail (w2s\_quiz\_detail)**
This paragraph is used to insert Quiz Blocks on W2S Detail Page.
French label : Quiz Web to Showroom - page détail

### Fields

|Name             |Label (fr)            |Machine name                |Type                  |Description/Options|Help Text (fr)                                                                      |
|-----------------|----------------------|----------------------------|----------------------|-------------------|------------------------------------------------------------------------------------|
|Content          |Contenu               |                            |Details               |                   |                                                                                    |
|Title*           |Titre                 |field_w2sdquiz_title        |Textarea (description)|                   |                                                                                    |
|Background Image*|Image de fond         |field_w2sdquiz_img          |Image                 |                   |Renseignez l’image de fond du bloc Quiz affiché sur les pages détail.               |
|Link*            |Lien                  |field_w2sdquiz_link         |Link                  |+ Open in new tab  |Renseignez l’URL et le titre du lien.                                               |
|Quiz block show  |Affichage du bloc Quiz|field_w2slquiz_detail_status|Single on/off checkbox|                   |Cochez la checkbox pour afficher le bloc Quiz sur les pages Web to Showroom détail. |


## **W2S Quiz Landing (w2s\_quiz\_landing)**
This paragraph is used to insert Quiz Blocks on W2S Landing Page.
French label : Quiz Web to Showroom - page Landing

### Fields

|Name             |Label (fr)            |Machine name                 |Type                  |Description/Options|Help Text (fr)                                                                                           |
|-----------------|----------------------|-----------------------------|----------------------|-------------------|---------------------------------------------------------------------------------------------------------|
|Content          |Contenu               |                             |Details               |                   |                                                                                                         |
|Title*           |Titre                 |field_w2slquiz_title         |Text                  |                   |                                                                                                         |
|Subtitle*        |Sous-titre            |field_w2slquiz_stitle        |Text                  |                   |Renseignez le sous-titre affiché sur l’image.                                                            |
|Background Image*|Image de fond         |field_w2slquiz_img           |Image                 |                   |Renseignez l’image de fond du bloc Quiz affiché sur la page Landing. Taille recommandée : 460x74 pixels. |
|Link*            |Lien                  |field_w2slquiz_link          |Link                  |+ Open in new tab  |Renseignez l’URL et le titre du lien.                                                                    |
|Quiz block show  |Affichage du bloc Quiz|field_w2slquiz_landing_status|Single on/off checkbox|                   |Cochez la checkbox pour afficher le bloc Quiz sur la page d’accueil Web to Showroom.                     |


## **W2S Highlighted Product Item (w2s\_hl\_prods\_item)**
This paragraph is used to insert Highlighted Product item in Highlighted Products Block on W2S Detail Page (Products Grid).
French label : Elément Grille de produits W2S

### Fields

| Name      | Label (fr) | Machine name          | Type             | Description/Options | Help Text (fr)                 |
| --------- | ---------- | --------------------- | ---------------- | ------------------- | ------------------------------ |
| Item      | Elément    |                       | Details          |                     |                                |
| Image\*   | Image      | field\_w2shlpri\_img  | Image            |                     | Renseignez l’image à afficher. |
| Product\* | Produit    | field\_w2shlpri\_prod | Remote (product) |                     | Renseignez le produit.         |


## **W2S Highlighted Products (w2s\_hl\_prods)**
This paragraph is used to insert Highlighted Products Blocks on W2S Detail Page (Products Grid).
French label : Grille de produits W2S

### Fields

|Name   |Label (fr)|Machine name       |Type                         |Description/Options|Help Text (fr)                                                                                                                                                                                                  |
|-------|----------|-------------------|-----------------------------|-------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Content|Contenu   |                   |Details                      |                   |                                                                                                                                                                                                                |
|Item*  |Elément   |field_w2shlprs_item|Paragraph (w2s_hl_prods_item)|Multiple (3 max)   |Si vous ajoutez 3 éléments, alors les 2 premiers seront affichés sur la colonne de gauche, le 3ème sur la colonne de droite.  Si vous ajoutez 2 éléments, alors ils seront positionnés l’un à côté de l’autre.  |


## **W2S Highlighted Product CTA (w2s\_hl\_product\_cta)**
This paragraph is used to insert CTA lines in Highlighted Product Block on W2S Detail Page.
French label : Bloc catégorie Web to Showroom

### Fields

| Name               | Label (fr)    | Machine name              | Type    | Description/Options | Help Text (fr)                        |
| ------------------ | ------------- | ------------------------- | ------- | ------------------- | ------------------------------------- |
| Content            | Contenu       |                           | Details |                     |                                       |
| Background Image\* | Image de fond | field\_w2shlpr\_cta\_img  | Image   |                     | Renseignez l’image de fond.           |
| Link\*             | Lien          | field\_w2shlpr\_cta\_link | Link    | \+ Open in new tab  | Renseignez l’URL et le titre du lien. |

## **W2S Highlighted Product (w2s\_hl\_product)**
This paragraph is used to insert Highlighted Product in Highlighted Product Block on W2S Detail Page.
French label : Mise en avant produit W2S

### Fields

| Name          | Label (fr)  | Machine name          | Type                              | Description/Options | Help Text (fr)                                               |
| ------------- | ----------- | --------------------- | --------------------------------- | ------------------- | ------------------------------------------------------------ |
| Content       | Contenu     |                       | Details                           |                     |                                                              |
| Title\*       | Titre       | field\_w2shlpr\_title | Title                             |                     |                                                              |
| Product\*     | Produit     | field\_w2shlpr\_prod  | Remote (product)                  |                     | Renseignez le produit.                                       |
| Image\*       | Image       | field\_w2shlpr\_img   | Image                             |                     | Ajoutez l’image de la mise en avant.                         |
| Description\* | Description | field\_w2shlpr\_descr | Textarea (decorated text)         |                     |                                                              |
| CTA           | CTA         | field\_w2shlpr\_cta   | Paragraph (w2s\_hl\_product\_cta) | Multiple            | Renseignez les blocs de la section “VOir tous nos produits”. |

## **Coverings & Aspects (ca\_line)**
This paragraph is used to insert Coverings & Aspects line.
French label : Bloc Surfaces et Revêtements

### Fields

| Name                | Label (fr)                 | Machine name        | Type                 | Description/Options | Help Text (fr) |
| ------------------- | -------------------------- | ------------------- | -------------------- | ------------------- | -------------- |
| Content             | Contenu                    |                     | Details              |                     |                |
| Coverings & Aspects | Revêtement(s) et Aspect(s) | field\_ca\_line\_ca | Paragraph (w2s\_ca) | Multiple            |                |

## **W2S Coverings & Aspects (w2s\_ca)**
This paragraph is used to insert Coverings & Aspects Block on W2S Detail Page.
French label : Bloc Revêtement Web to Showroom

### Fields

| Name             | Label (fr)         | Machine name           | Type                               | Description/Options | Help Text (fr)                                                                      |
| ---------------- | ------------------ | ---------------------- | ---------------------------------- | ------------------- | ----------------------------------------------------------------------------------- |
| Content          | Contenu            |                        | Details                            |                     |                                                                                     |
| Covering\*       | Revêtement         | field\_w2sca\_covering | Reference (taxonomy:w2s\_covering) | Drop-down list      | Sélectionnez un revêtement dans la liste.                                           |
| Aspect/Product\* | Aspects / Produits | field\_w2sca\_ap       | Paragraph (w2s\_ap)                | Multiple            | Définissez le(s) aspect(s) associés au Revêtement (optionnel) et les produits liés. |


## **W2S Coverings & Aspects (w2s\_ap)**
This paragraph is used to insert Coverings & Aspects Block on W2S Detail Page.
French label : Bloc Aspects / Produits Web to Showroom

### Fields

| Name      | Label (fr) | Machine name          | Type                             | Description/Options | Help Text (fr)                                   |
| --------- | ---------- | --------------------- | -------------------------------- | ------------------- | ------------------------------------------------ |
| Content   | Contenu    |                       | Details                          |                     |                                                  |
| Aspect    | Aspect     | field\_w2sap\_aspect  | Reference (taxonomy:w2s\_aspect) | Drop-down list      | Sélectionnez un aspect dans la list (optionnel). |
| Product\* | Produit(s) | field\_w2sap\_product | Remote(product)                  | Multiple            | Sélectionnez un ou plusieurs produits.           |

## **W2S Services block (w2s\_sb)**
This paragraph is used to insert Services block on W2S Detail Page.
French label : Bloc Service W2S

### Fields

| Name          | Label (fr)          | Machine name         | Type                      | Description/Options | Help Text (fr)                                  |
| ------------- | ------------------- | -------------------- | ------------------------- | ------------------- | ----------------------------------------------- |
| Content       | Contenu             |                      | Details                   |                     |                                                 |
| Title\*       | Titre               | field\_w2ssrb\_title | Text                      |                     |                                                 |
| Description\* | Description         | field\_w2ssrb\_descr | Textarea (decorated text) |                     | Renseignez la description.                      |
| Image\*       | Image               | field\_w2ssrb\_img   | Image                     |                     | Renseignez l’image.                             |
| Know more     | Lien en savoir plus | field\_w2ssrb\_link  | Url                       | \+ Open in new tab  | Configurez le lien En savoir plus de l’élément. |
| CTA           | CTA                 | field\_w2ssrb\_cta   | Link                      | \+ Open in new tab  | Configurez le CTA de l’élément.                 |

## **W2S Immersive carousel slide (w2s\_im\_slide)**
This paragraph is used to insert Immersive carousel on W2S Detail Page and Inspirational wall page.
French label : Slide Carousel immersif

### Fields

| Name           | Label (fr)               | Machine name            | Type                               | Description/Options | Help Text (fr)                                                                                      |
| -------------- | ------------------------ | ----------------------- | ---------------------------------- | ------------------- | --------------------------------------------------------------------------------------------------- |
| Content        | Contenu                  |                         | Details                            |                     |                                                                                                     |
| Image\*        | Image                    | field\_w2imsl\_img      | Image                              |                     | Ajoutez l’image de la slide. Taille recommandée : 1480 x 740 pixels.                                |
| Mobile Image\* | Image mobile             | field\_w2imsl\_mob\_img | Image                              |                     | Ajoutez l’image de la slide utilisée sur la version mobile. Taille recommandée  : 600 x 500 pixels. |
| Marker         | Marqueurs                | field\_w2imsl\_marker   | Paragraph (w2s\_im\_slide\_marker) | Multiple            | Configurez les marqueurs Produit à afficher sur la slide.                                           |
| Square Image   | Image Mur Inspirationnel | field\_w2imsl\_sq\_img  | Image                              |                     | Ajoutez l’image affichée sur le Mur Inspirationnel.<br>Taille recommandée : 458 x 458 pixels.       |

## **W2S Immersive carousel slide product (w2s\_im\_slide\_marker)**
This paragraph is used to insert markers on Immersive carousel paragraph.
French label : Marqueur Produit Carousel immersif

### Fields

|Name                |Label (fr)                       |Machine name         |Type            |Description/Options                  |Help Text (fr)                                                                                                                                    |
|--------------------|---------------------------------|---------------------|----------------|-------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
|Content             |Contenu                          |                     |Details         |                                     |                                                                                                                                                  |
|Product*            |Produit                          |field_w2imslm_product|Remote (product)|                                     |Définissez le produit.                                                                                                                            |
|Unit*               |Mode de configuration du Marqueur|field_w2imslm_unit   |Select          |pixels&#124;Pixels percentage&#124;Pourcentages|Sélectionnez le mode de définition du Marqueur. Si vous choisissez l'option Pourcentages, alors les valeurs doivent être comprises entre 0 et 100.|
|Vertical position*  |Position verticale               |field_w2imslm_posy   |Integer         |                                     |Définissez la position verticale du Marqueur (en pixels).                                                                                         |
|Horizontal position*|Position horizontale             |field_w2imslm_posx   |Integer         |                                     |Définissez la position horizontale du Marqueur (en pixels).                                                                                       |


## **ESDB Immersive carousel slider (esdb\_im\_slider)**
This paragraph is used to insert Immersive carousel on ESDB Detail Page.
French label : Slider Carousel immersif

### Fields

| Name               | Label (fr)         | Machine name  | Type                                                                                                                                    | Description/Options | Help Text (fr) |
| ------------------ | ------------------ | ------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | -------------- |
| Content            | Contenu            |               | Details                                                                                                                                 |                     |                |
| Immersive carousel | Immersive carousel | field\_e\_imc | ECK entity ([esdb\_im\_slider](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.1eadkte)) |                     |                |

## **ESDB Immersive carousel slider line (esdb\_im\_slider\_line)**
This paragraph is used to insert Immersive carousel on ESDB Homepage.
French label : Slider Carousel immersif ligne

### Fields

| Name               | Label (fr)         | Machine name   | Type                                                                                                                                    | Description/Options | Help Text (fr) |
| ------------------ | ------------------ | -------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | -------------- |
| Content            | Contenu            |                | Details                                                                                                                                 |                     |                |
| Immersive carousel | Immersive carousel | field\_el\_imc | ECK entity ([esdb\_im\_slider](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.1eadkte)) |                     |                |

## **ESDB Immersive carousel slide (esdb\_im\_slide)**
This paragraph is used to insert Immersive carousel on ESDB Detail Page.
French label : Slide Carousel immersif

### Fields

|Name                   |Label (fr)             |Machine name          |Type                                |Description/Options|Help Text (fr)                                                                                     |
|-----------------------|-----------------------|----------------------|------------------------------------|-------------------|---------------------------------------------------------------------------------------------------|
|Content                |Contenu                |                      |Details                             |                   |                                                                                                   |
|Image*                 |Image                  |field_e_imsl_img      |Image                               |                   |Ajoutez l’image de la slide. Taille recommandée : 1480 x 740 pixels.                               |
|Slide description      |Description de la slide|field_e_imsl_descr    |Text                                |                   |Renseignez la description de la slide (optionnel, affiché en bas à droite de la slide si renseigné)|
|Slide description: link|Lien de la slide       |field_e_imsl_descr_l  |Link (with option Open in a new tab)|                   |Renseignez le lien de la slide (optionnel, affiché en bas à droite de la slide si renseigné)       |
|Mobile Image*          |Image mobile           |field_e_imsl_mob_img  |Image                               |                   |Ajoutez l’image de la slide utilisée sur la version mobile. Taille recommandée : 600 x 500 pixels. |
|Marker                 |Marqueurs              |field_e_imsl_marker   |Paragraph (esdb_im_slide_marker)    |Multiple           |Configurez les marqueurs Produit à afficher sur la slide.                                          |
|Testimony: author      |Auteur                 |field_e_imsl_t_author |Reference (term:advice_author_esdb) |                   |Sélectionnez l’auteur du témoignage (optionnel).                                                   |
|Testimony: content     |Témoignage             |field_e_imsl_t_content|Textarea (decorated text)           |                   |Renseignez le témoignage associé à la slide (optionnel).                                           |


## **ESDB Immersive carousel slide product (esdb\_im\_slide\_marker)**
This paragraph is used to insert markers on ESDB Immersive carousel paragraph.
French label : Marqueur Produit Carousel immersif

### Fields

|Name                |Label (fr)                       |Machine name         |Type            |Description/Options                  |Help Text (fr)                                                                                                                                    |
|--------------------|---------------------------------|---------------------|----------------|-------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
|Content             |Contenu                          |                     |Details         |                                     |                                                                                                                                                  |
|Product*            |Produit                          |field_e_imslm_product|Remote (product)|                                     |Définissez le produit.                                                                                                                            |
|Unit*               |Mode de configuration du Marqueur|field_e_imslm_unit   |Select          |pixels&#124;Pixels percentage&#124;Pourcentages|Sélectionnez le mode de définition du Marqueur. Si vous choisissez l'option Pourcentages, alors les valeurs doivent être comprises entre 0 et 100.|
|Vertical position*  |Position verticale               |field_e_imslm_posy   |Integer         |                                     |Définissez la position verticale du Marqueur (en pixels).                                                                                         |
|Horizontal position*|Position horizontale             |field_e_imslm_posx   |Integer         |                                     |Définissez la position horizontale du Marqueur (en pixels).                                                                                       |


## **ESDB presentation style (esdb\_presentation\_style)**
This paragraph is used to insert Présentation Style ESDB.
French label : Présentation Style ESDB

### Fields

| Name      | Label (fr) | Machine name            | Type        | Description/Options     | Help Text (fr) |
| --------- | ---------- | ----------------------- | ----------- | ----------------------- | -------------- |
| Content   | Contenu    |                         | Details     |                         |                |
| Image     |            | field\_e\_ps\_image     | Image       | Multiple                |                |
| Name      |            | field\_e\_ps\_name      | Text        |                         |                |
| Function  |            | field\_e\_ps\_function  | Text        |                         |                |
| Thumbnail |            | field\_e\_ps\_thimbnail | Image       |                         |                |
| Testimony |            | field\_e\_ps\_testimony | Textarea    | Advanced decorated text |                |
| Tonality  |            | field\_e\_ps\_tonality  | Colorpicker | Multiple                |                |

## **ESDB Style highlights Carousel (esdb\_style\_highlights\_carousel)**
This paragraph is used to insert Style Highlights Carousel.
French label : Carousel Objets emblématiques 

### Fields

| Name          | Label (fr)    | Machine name         | Type                                                                                                                                                      | Description/Options | Help Text (fr)                  |
| ------------- | ------------- | -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ------------------------------- |
| Content       | Contenu       |                      | Details                                                                                                                                                   |                     |                                 |
| Block title\* | Titre du bloc | field\_e\_sh\_title  | Text                                                                                                                                                      |                     |                                 |
| Slide         | Slides        | field\_e\_sh\_slider | Paragraph ([esdb\_slide\_highlights\_style](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.ho1c2lfzp5dz)) | Multiple            | Ajoutez des slides au carousel. |


## **ESDB carousel Inspirations Style (esdb\_carousel\_inspirations\_style)**
This paragraph is used to insert Carousel Inspirations Style.
French label : Carousel Inspirations Style

### Fields

| Name              | Label (fr)          | Machine name               | Type                                                                                                                                                  | Description/Options | Help Text (fr)                     |
| ----------------- | ------------------- | -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ---------------------------------- |
| Content           | Contenu             |                            | Details                                                                                                                                               |                     |                                    |
| Block title       | Titre du bloc       | field\_e\_cis\_title       | Text                                                                                                                                                  |                     |                                    |
| Block description | Description du bloc | field\_e\_cis\_description | Textarea (Decorated text)                                                                                                                             |                     | Renseignez la description du bloc. |
| Slide             | Slides              | field\_e\_cis\_slide       | Paragraph ([esdb\_slide\_inspirations\_style](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.rtofi4)) | Multiple            | Ajoutez les slides au carousel.    |


## **ESDB Slide Inspirations Style (esdb\_slide\_inspirations\_style)**
This paragraph is used to insert Slide Inspirations Style.
French label : Slide Carousel Style

### Fields

|Name        |Label (fr) |Machine name           |Type    |Description/Options|Help Text (fr)                        |
|------------|-----------|-----------------------|--------|-------------------|--------------------------------------|
|Content     |Contenu    |                       |Details |                   |                                      |
|Title       |TItre      |field_e_sis_title      |Text    |                   |                                      |
|Description |Description|field_e_sis_description|Textarea|Decorated text     |Renseignez la description de la slide.|
|Image       |Image      |field_e_sis_image      |Image   |                   |Ajoutez l’image de la slide.          |


## **ESDB Slide highlights Style (esdb\_slide\_highlights\_style)**
This paragraph is used to insert Slide highlights Style.
French label : 

### Fields

|Name        |Label (fr) |Machine name           |Type                                |Description/Options|Help Text (fr)                        |
|------------|-----------|-----------------------|------------------------------------|-------------------|--------------------------------------|
|Content     |Contenu    |                       |Details                             |                   |                                      |
|Title       |TItre      |field_e_shs_title      |Text                                |                   |                                      |
|Description |Description|field_e_shs_description|Textarea                            |Decorated text     |Renseignez la description de la slide.|
|Link        |Lien       |field_e_shs_link       |Link (with option open in a new tab)|                   |                                      |
|Image       |Image      |field_e_shs_image      |Image                               |                   |Ajoutez l’image de la slide.          |


## **Conseils text image (conseils\_text\_image)**
This paragraph is used to insert Line on Conseils detail page.
French label : Conseils d’expert - Contenu

### Fields

|Name           |Label (fr)         |Machine name              |Type                     |Description/Options                                          |Help Text (fr)                                                       |
|---------------|-------------------|--------------------------|-------------------------|-------------------------------------------------------------|---------------------------------------------------------------------|
|Content        |Contenu            |                          |Details                  |                                                             |                                                                     |
|Title*         |Titre              |field_cl_ti_title         |Text                     |                                                             |                                                                     |
|Title position*|Position du titre  |field_cl_ti_title_position|List (text) &#124; Select list|Variants of title position (above/inline), radio buttons     |Définissez la position du titre (au dessus du bloc ou dans le bloc). |
|Description*   |Description        |field_cl_ti_text          |Textarea (filtered HTML) |                                                             |Renseignez la description du bloc.                                   |
|Image          |Visuel             |field_cl_ti_image         |Image                    |                                                             |Renseignez le visuel du bloc (optionnel).                            |
|Legend         |Légende            |field_cl_ti_image_legend  |Textarea (description)   |                                                             |Renseignez la légende du visuel (optionnel).                         |
|Image position*|Position de l’image|field_cl_ti_image_position|List (text) &#124; Select list|Variants of image position (left/right/bottom), radio buttons|Définissez la position de l’image (gauche / droite / bas).           |
|CTA            |Bouton             |field_cl_ti_cta           |Link                     |Title + URL + open in new tab option                         |Configurez le bouton (optionnel).                                    |


## **Conseils text button (conseils\_text\_cta)**
This paragraph is used to insert Line on Conseils detail page.
French label : Conseils d’expert - CTA

### Fields

| Name          | Label (fr)  | Machine name         | Type                      | Description/Options                  | Help Text (fr)                      |
| ------------- | ----------- | -------------------- | ------------------------- | ------------------------------------ | ----------------------------------- |
| Content       | Contenu     |                      | Details                   |                                      |                                     |
| Title\*       | Titre       | field\_cl\_tc\_title | Text                      |                                      |                                     |
| Description\* | Description | field\_cl\_tc\_text  | Textarea (decorated text) |                                      | Renseignez le contenu du bloc.      |
| CTA           | Bouton      | field\_cl\_tc\_cta   | Link                      | Title + URL + open in new tab option | Configurez le bouton (lien, label). |

## **Conseils presentation (conseils\_text\_presentation)**
This paragraph is used to insert Line on Conseils detail page.
French label : Conseils d’expert - Mise en avant Article

### Fields

| Name          | Label (fr)  | Machine name            | Type                      | Description/Options                  | Help Text (fr)                                   |
| ------------- | ----------- | ----------------------- | ------------------------- | ------------------------------------ | ------------------------------------------------ |
| Content       | Contenu     |                         | Details                   |                                      |                                                  |
| Title\*       | Titre       | field\_cl\_ctp\_title   | Text                      |                                      |                                                  |
| Description\* | Description | field\_cl\_ctp\_text    | Textarea (decorated text) |                                      | Renseignez le contenu du bloc.                   |
| CTA           | Bouton      | field\_cl\_ctp\_cta     | Link                      | Title + URL + open in new tab option | Configurez le bouton (lien, label).              |
| Product       | Produit     | field\_cl\_ctp\_product | Remote (product)          |                                      | Définissez le produit mis en avant dans le bloc. |

## **Conseils related (conseils\_related\_conseils)**
This paragraph is used to insert Line on Conseils detail page.
French label : Conseils d’expert - contenus liés

### Fields

| Name     | Label (fr)  | Machine name             | Type                         | Description/Options | Help Text (fr)                                  |
| -------- | ----------- | ------------------------ | ---------------------------- | ------------------- | ----------------------------------------------- |
| Content  | Contenu     |                          | Details                      |                     |                                                 |
| Title\*  | Titre       | field\_cl\_crc\_title    | Text                         |                     | Définissez le titre du bloc.                    |
| Conseils | Contenu lié | field\_cl\_crc\_conseils | Remote (conseils) (services) | 3 items maximum     | Ajoutez jusqu’à 3 Conseils d’expert / Services. |

## **Quiz question answers (w2s\_qqa)**
This paragraph is used to insert answers on question in quiz page.
French label : Réponses Quiz 

### Fields

| Name     | Label (fr) | Machine name            | Type                                                                                                                                      | Description/Options | Help Text (fr)                                                                   |
| -------- | ---------- | ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | -------------------------------------------------------------------------------- |
| Title\*  | Titre      | field\_w2s\_qqa\_title  | Text                                                                                                                                      |                     |                                                                                  |
| Image\*  | Image      | field\_w2s\_qqa\_image  | Image                                                                                                                                     |                     | Renseignez l’image illustrant la réponse. Taille recommandée : 946 x 378 pixels. |
| Weight\* | Poids      | field\_w2s\_qqa\_weight | Number | integer                                                                                                                          |                     | Renseignez le poids de la réponse, utilisé pour la mécanique de calcul.          |
| Style\*  | Style      | field\_w2s\_qqa\_style  | Reference (taxonomy:[w2s\_style](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.2ovzkin)) |                     | Associez un Style à la réponse.                                                  |


## **ESDB Quiz question answers (esdb\_qqa)**
This paragraph is used to insert answers in the questions on the quiz page.
French label : Réponses Quiz ESDB

### Fields

| Name     | Label (fr) | Machine name             | Type                                                                                                                                  | Description/Options | Help Text (fr)                                                                   |
| -------- | ---------- | ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | -------------------------------------------------------------------------------- |
| Title\*  | Titre      | field\_esdb\_qqa\_title  | Text                                                                                                                                  |                     |                                                                                  |
| Image\*  | Image      | field\_esdb\_qqa\_image  | Image                                                                                                                                 |                     | Renseignez l’image illustrant la réponse. Taille recommandée : 946 x 378 pixels. |
| Weight\* | Poids      | field\_esdb\_qqa\_weight | Number | integer                                                                                                                      |                     | Renseignez le poids de la réponse, utilisé pour la mécanique de calcul.          |
| Style\*  | Style      | field\_esdb\_qqa\_style  | Reference (node:[ESDB Style](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.1maplo9)) |                     | Associez un Style à la réponse.                                                  |

## **Media Block (service\_line\_media)**
Media block for service detail page.

French label : Bloc Media

### Fields

|Name         |Label (fr)       |Machine name              |Type                     |Description/Options                                                                                                   |Help Text (fr)                                                                                                                                        |
|-------------|-----------------|--------------------------|-------------------------|----------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
|Content      |Contenu          |                          |Details                  |                                                                                                                      |                                                                                                                                                      |
|Description  |Description      |field_sp_mb_description   |Textarea - decorated text|                                                                                                                      |Renseignez la description du bloc.                                                                                                                    |
|Position*    |Position du média|field_sp_mb_media_position|List (text) &#124; Select list|Variants of media position (left/right), two required values (radio buttons) By default: left                         |Renseignez la position du média (gauche / droite).                                                                                                    |
|Video*       |Vidéo            |field_sp_mb_video         |Video (embed)            |                                                                                                                      |Renseignez le lien de la vidéo YouTube (optionnel).                                                                                                   |
|Image Before*|Image “Avant”    |field_sp_mb_image_before  |Image                    |If only this field is filled (and “Image after” is left as empty), then display “Image before” as it is (no JS module)|Renseignez l’image “Avant” pour le module “Avant / Après”. Si l’image “Après” n’est pas renseignée, alors l’image “Avant” sera affichée telle quelle. |
|Image After  |Image “Après”    |field_sp_mb_image_after   |Image                    |                                                                                                                      |Renseignez l’image “Après” pour le module “Avant / Après”. Optionnel.                                                                                 |
|CTA          |Bouton           |field_sp_mb_cta           |Paragraph                |Multiple &#124; Reference: Paragraph   (service_line_media_cta)                                                            |Ajoutez un ou plusieurs CTA, et définissez la visibilité pour chaque.                                                                                 |


## **Media Block CTA item (service\_line\_media\_cta)**
CTA item for media block.

French label : CTA bloc Media

### Fields

| Name          | Label (fr)                       | Machine name                     | Type                      | Description/Options                  | Help Text (fr)                                                       |
| ------------- | -------------------------------- | -------------------------------- | ------------------------- | ------------------------------------ | -------------------------------------------------------------------- |
| Content       | Contenu                          |                                  | Details                   |                                      |                                                                      |
| Description1  | Description au dessus du bouton  | field\_sp\_mb\_cta\_text1        | Textarea (decorated text) |                                      | Renseignez la description affichée au dessus du bouton (optionnel).  |
| CTA           | Bouton                           | field\_sp\_mb\_cta\_cta          | Link                      | Title + URL + open in new tab option |                                                                      |
| Description 2 | Description en dessous du bouton | field\_sp\_mb\_cta\_text2        | Textarea (decorated text) |                                      | Renseignez la description affichée en dessous du bouton (optionnel). |
| Visibilité    | Visibilité                       | field\_sp\_mb\_cta\_role\_access | Roles Access              |                                      | Définissez la visibilité du CTA et de ses descriptions associées.    |


## **Wysiwyg Block (service\_line\_wysiwyg)**
Wysiwyg block for service detail page.

French label : Bloc WYSIWYG

### Fields

| Name          | Label (fr)  | Machine name         | Type                      | Description/Options | Help Text (fr)                 |
| ------------- | ----------- | -------------------- | ------------------------- | ------------------- | ------------------------------ |
| Content       | Contenu     |                      | Details                   |                     |                                |
| Title\*       | Titre       | field\_sp\_wb\_title | Text                      |                     |                                |
| Description\* | Description | &@                   | Textarea (decorated text) |                     | Renseignez le contenu du bloc. |


## **Free html Block (service\_line\_free\_html)**
Free html block for service detail page.

French label : Block HTML libre

### Fields

| Name      | Label (fr)         | Machine name         | Type                   | Description/Options | Help Text (fr)                              |
| --------- | ------------------ | -------------------- | ---------------------- | ------------------- | ------------------------------------------- |
| Content   | Contenu            |                      | Details                |                     |                                             |
| Title\*   | Titre              | field\_sp\_fh\_title | Text                   |                     |                                             |
| Free HTML | Contenu HTML libre | field\_sp\_fh\_text  | Text area | Plain text |                     | Ajoutez votre code HTML / JS dans ce champ. |

## **AT form Block (service\_line\_at\_form)**
Aides aux travaux form block for service detail page.
French label : Bloc Aide aux Travaux

### Fields

| Name  | Label (fr) | Machine name       | Type | Description/Options | Help Text (fr) |
| ----- | ---------- | ------------------ | ---- | ------------------- | -------------- |
| Title | Titre      | field\_slaf\_title | Text |                     |                |

## **Service Landing QAB Block (service\_landing\_qab\_block)**
Service landing block for quick access bar

French label : Barre accès rapide Landing Services 

### Fields

|Name                 |Label (fr)|Machine name      |Type        |Description/Options                                       |Help Text (fr)                                        |
|---------------------|----------|------------------|------------|----------------------------------------------------------|------------------------------------------------------|
|Content              |Contenu   |                  |Details     |                                                          |                                                      |
|Available for        |Visibilité|field_slqab_access|Roles Access|                                                          |Définissez la visibilité de la barre d’accès rapide.  |
|Quick access bar item|Elements  |field_slqab_item  |Paragraph   |Multiple &#124; Reference: Paragraph (service_landing_qab_item)|Définissez les éléments de la barre.                  |


## **Service Landing QAB item (service\_landing\_qab\_item)**
Service landing item for quick access bar

French label : Elément accès rapide Landing Services

### Fields

| Name    | Label (fr) | Machine name          | Type                      | Description/Options                  | Help Text (fr)                    |
| ------- | ---------- | --------------------- | ------------------------- | ------------------------------------ | --------------------------------- |
| Content | Contenu    |                       | Details                   |                                      |                                   |
| Service |            | field\_slqab\_service | List (text) | Select list | service\_solup|SOLUP, service\_ga|GA |                                   |
| Title\* | Titre      | field\_slqab\_title   | Text                      |                                      | Renseignez le titre de l’élément. |
| Icon\*  | Icone      | field\_slqab\_icon    | File                      | svg                                  | Ajoutez l’icône de l’élément.     |
| Link\*  | Lien       | field\_slqab\_link    | Link                      | URL                                  | Renseignez le lien de l’élément.  |


## **Service Landing Lines Block (service\_landing\_lines\_block)**
Service landing block for service landing page.

French label : Ligne Landing Services

### Fields

|Name           |Label (fr)|Machine name          |Type                  |Description/Options                                                                        |Help Text (fr)|
|---------------|----------|----------------------|----------------------|-------------------------------------------------------------------------------------------|--------------|
|Content        |Contenu   |                      |Details               |                                                                                           |              |
|Line           |Lignes    |field_sllb_line       |Paragraph             |Multiple &#124; Reference:</br> Paragraph</br> (service_landing_lines_line1)</br> (service_landing_lines_line2)|              |
|Title*         |Titre     |field_sllb_title      |Text                  |                                                                                           |              |
|Additional info|          |field_sllb_description|Text area &#124; Plain</br> text|                                                                                           |              |

## **Service Landing Lines Line 1 (service\_landing\_lines\_line1)**
Service landing line for service landing page.

French label : Ligne Landing Type 1

### Fields

|Name   |Label (fr)|Machine name   |Type      |Description/Options                                                                       |Help Text (fr)|
|-------|----------|---------------|----------|------------------------------------------------------------------------------------------|--------------|
|Content|Contenu   |               |Details   |                                                                                          |              |
|Items* |Items     |field_sll_line1|Paragraph |Multiple &#124; Reference:</br> Paragraph</br> (service_landing_lines_type1)</br> (service_landing_lines_masb)|              |


## **Service Landing Lines Line 2 (service\_landing\_lines\_line2)**
Service landing line for service landing page.

French label : Ligne Landing Type 2

### Fields

|Name   |Label (fr)|Machine name   |Type      |Description/Options                                          |Help Text (fr)|
|-------|----------|---------------|----------|-------------------------------------------------------------|--------------|
|Content|Contenu   |               |Details   |                                                             |              |
|Items* |Items     |field_sll_line2|Paragraph |Multiple &#124; Reference:</br> Paragraph</br> (service_landing_lines_type2)|              |


## **Service landing lines type 1 (service\_landing\_lines\_type1)**
Service landing block type 1 for service landing page.

French label : Ligne Service 1

### Fields

|Name   |Label (fr)|Machine name   |Type      |Description/Options                                          |Help Text (fr)|
|-------|----------|---------------|----------|-------------------------------------------------------------|--------------|
|Content|Contenu   |               |Details   |                                                             |              |
|Nouveauté|Nouveauté |field_sllt_1_new|Bool &#124; Single on/off checkbox|                                                             |              |
|Title* |Titre     |field_sllt_1_title|Text      |                                                             |              |
|Image  |          |field_sllt_1_image|Image     |                                                             |              |
|Description|          |field_sllt_1_text|Textarea (decorated text)|                                                             |              |
|Link   |          |field_sllt_1_link|Link &#124; Link|With option “Open in a new tab”                              |              |
|Service|          |field_sllt_1_service|Textfield &#124; Select list|service_solup&#124;Solu+,</br> service_ga&#124;Generation</br> Artisans</br> service_caprenov&#124;Caprenov+|              |

## **My account service block (service\_landing\_lines\_masb)**
Service landing block for my account redirect for service landing page.

French label : Mon compte bloc spécial

### Fields

| Name         | Label (fr)  | Machine name             | Type                          | Description/Options | Help Text (fr) |
| ------------ | ----------- | ------------------------ | ----------------------------- | ------------------- | -------------- |
| Content      | Contenu     |                          | Details                       |                     |                |
| Nouveauté    | Nouveauté   | field\_sllt\_masb\_new   | Bool | Single on/off checkbox |                     |                |
| Title\*      | Titre       | field\_sllt\_masb\_title | Text                          |                     |                |
| Image        | Image       | field\_sllt\_masb\_image | Image                         |                     |                |
| Description  | Description | field\_sllt\_masb\_text  | Textarea (decorated text)     |                     |                |
| Link title\* | Lien titre  | field\_sllt\_masb\_lt    | Text                          |                     |                |


## **Service landing lines type 2 (service\_landing\_lines\_type2)**
Service landing block type 2 for service landing page.

French label : Ligne Service 2

### Fields

|Name       |Label (fr)|Machine name      |Type                     |Description/Options            |Help Text (fr)|
|-----------|----------|------------------|-------------------------|-------------------------------|--------------|
|Content    |Contenu   |                  |Details                  |                               |              |
|Title*     |Titre     |field_sllt_2_title|Text                     |                               |              |
|Description|          |field_sllt_2_text |Textarea (decorated text)|                               |              |
|<del>Link</del>       |          |<del>field_sllt_2_link</del> |<del>Link &#124; Link</del>              |<del>With option “Open in a new tab”</del>|              |


## **Custom service subscription (custom\_service\_subscription)**
Service registration block for service registration page.

French label : 

### Fields

| Name                             | Label (fr)                                 | Machine name                       | Type         | Description/Options | Help Text (fr)                                                                          |
| -------------------------------- | ------------------------------------------ | ---------------------------------- | ------------ | ------------------- | --------------------------------------------------------------------------------------- |
| Content                          | Contenu                                    |                                    | Details      |                     |                                                                                         |
| Title\*                          | Titre                                      | field\_pcss\_title                 | Text         |                     | Renseignez le titre de la page.                                                         |
| Alias                            | Alias                                      | field\_pcss\_alias                 | Text         |                     | Renseignez l’alias de la page.                                                          |
| Service code                     | Code du service                            | field\_pcss\_service\_code         | Text         |                     | Renseignez le code du service concerné.                                                 |
| Visibility block                 | Visibilité                                 | field\_par\_role\_access           | Roles Access |                     | Définissez la visibilité de la page d’adhésion au service.                              |
| Service success redirection page | Page de redirection en cas de succès       | field\_pcss\_redirection           | Link         |                     | En cas d'adhésion réussite, renseignez le lien vers lequel l’utilisateur sera redirigé. |
| Successful information message   | Message d’information en cas de succès     | field\_pcss\_success\_message      | Textarea     |                     | En cas d'adhésion réussite, renseignez le message d’information à afficher.             |
| Unsuccessful information message | Message d’information en cas de non succès | field\_pcss\_unsuccessful\_message | Textarea     |                     | En cas d'adhésion non réussite, renseignez le message d’information à afficher.         |

## **Catalog category (catalog\_category)**
This custom entity type is used to handle catalog categories on category LP.

French label : 

### Fields

|Name  |Label (fr)|Machine name  |Type      |Description/Options                                                      |Help Text (fr)|
|------|----------|--------------|----------|-------------------------------------------------------------------------|--------------|
|Title*|Titre     |field_cc_title|Text      |Multivalue, 2 items max                                                  |              |
|Image*|Image     |field_cc_image|Image     |                                                                         |              |
|Items |Contenus  |field_cc_items|Paragraph |Multiple &#124; Reference: Paragraph (catalog_content_item, catalog_text_item)|              |


## **Catalog content item (catalog\_content\_item)**
This custom entity type is used to handle catalog content items on category LP.

French label : 

### Fields

| Name      | Label (fr) | Machine name        | Type                           | Description/Options | Help Text (fr) |
| --------- | ---------- | ------------------- | ------------------------------ | ------------------- | -------------- |
| Catalog\* | Catalogue  | field\_cci\_catalog | Reference (node|mini\_catalog) |                     |                |

## **Catalog text item (catalog\_text\_item)**
This custom entity type is used to handle catalog text items on category LP.

French label : 

### Fields

| Name   | Label (fr) | Machine name    | Type | Description/Options        | Help Text (fr) |
| ------ | ---------- | --------------- | ---- | -------------------------- | -------------- |
| Text\* | Texte      | field\_ti\_text | Text | Text area (decorated text) |                |

## **Information Bar Messages (ibm\_item)**
Information bar messages for content site settings config page.

French label : Messages d’information

### Fields

| Name                     | Label (fr)      | Machine name         | Type                       | Description/Options                       | Help Text (fr)                                                            |
| ------------------------ | --------------- | -------------------- | -------------------------- | ----------------------------------------- | ------------------------------------------------------------------------- |
| Content                  | Contenu         |                      | Details                    |                                           |                                                                           |
| Text                     | Message         | field\_ibm\_text     | Text area (decorated text) |                                           | Renseignez le message de la barre d’information, affichée sous le Header. |
| Visibilité               | Visibilité      | field\_ibm\_access   | Roles Access               |                                           |                                                                           |
| Navigateur IE uniquement | Show only on IE | field\_ibm\_ie\_only | Boolean                    |                                           |                                                                           |
| Page type                | Type de page    |                      | Details                    |                                           |                                                                           |
| Page type                | Type de page    | field\_ibm\_page     | Checkboxes                 | Options :<br>All pages (list, checkboxes) |                                                                           |

## **My Account Quick Access Bar (as\_qab)**
Manage quick access bars on My Account page.

French label : 

### Fields

| Name       | Label (fr) | Machine name           | Type                      | Description/Options | Help Text (fr)                                                            |
| ---------- | ---------- | ---------------------- | ------------------------- | ------------------- | ------------------------------------------------------------------------- |
| Content    | Contenu    |                        | Details                   |                     |                                                                           |
| Visibilité | Visibilité | field\_as\_qab\_access | Roles Access              |                     | Définissez la visibilité de la barre d’accès rapide.                      |
| Item       | Item       | field\_as\_qab\_item   | Paragraph (as\_qab\_item) | Multiple            | Sélectionner les items à afficher dans la bar d’accès rapide (5 maximum). |

## **My Account Quick Access Bar Item (as\_qab\_item)**
Quick Access Bar items on My Account Page

French label :

### Fields

|Name   |Label (fr)|Machine name         |Type                   |Description/Options                                                           |Help Text (fr)                                 |
|-------|----------|---------------------|-----------------------|------------------------------------------------------------------------------|-----------------------------------------------|
|Content|Contenu   |                     |Details                |                                                                              |                                               |
|Icon   |Icône     |field_as_qabi_icon   |File                   |svg                                                                           |Ajoutez l’icône de l’accès rapide (format SVG).|
|Title  |Titre     |field_as_qabi_title  |Text                   |                                                                              |Renseignez le titre de l’accès rapide          |
|Link   |Lien      |field_as_qabi_link   |Url                    |+ Open in new tab                                                             |Renseignez le lien de l’accès rapide           |
|Service|Service   |field_as_qabi_service|Textfield &#124; Select list|service_solup&#124;Solu+,</br> service_ga&#124;Generation</br> Artisans</br> service_caprenov&#124;Caprenov+|                                               |

## **My Account Home Description (as\_hpd)**
My Account Description items on My Account Home Page

French label : Page d’accueil mon compte

### Fields

| Name        | Label (fr)                      | Machine name           | Type                                | Description/Options | Help Text (fr)                                               |
| ----------- | ------------------------------- | ---------------------- | ----------------------------------- | ------------------- | ------------------------------------------------------------ |
| Content     | Contenu                         |                        | Details                             |                     |                                                              |
| Visibilité  | Visibilité                      | field\_as\_hpd\_access | Roles Access                        |                     | Définissez la visibilité de la page d’accueil Mon Compte.    |
| Description | Présentation Accueil Mon Compte | field\_as\_hpd\_descr  | Textarea (Simplified Filtered HTML) |                     | Renseignez le bloc affiché sur la page d‘accueil Mon Compte. |

## **Wishlist icon item (hw\_icon\_item)**
Wishlist icons for header.

French label : Liste de souhaits Icône

### Fields

|Name         |Label (fr)|Machine name    |Type        |Description/Options|Help Text (fr)               |
|-------------|----------|----------------|------------|-------------------|-----------------------------|
|Content      |Contenu   |                |Details     |                   |                             |
|Icon         |Icône     |field_hwi_icon  |File        |svg                |Ajouter l'icône (format SVG).|
|Available for|Visibilité|field_hwi_access|Roles Access|                   |                             |


## **Content Search Image (csearch\_img)**
Default image for CT to be configured .

French label : 

### Fields

|Name   |Label (fr)     |Machine name   |Type   |Description/Options                                                                                                                                                                                    |Help Text (fr)                                                                                                    |
|-------|---------------|---------------|-------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
|Content|Contenu        |               |Details|                                                                                                                                                                                                       |                                                                                                                  |
|CT     |Type de contenu|field_csimg_ct |Select |service_detail&#124;Service detail</br> Point P</br> conseils&#124;Conseil d’Expert</br> mini_catalog&#124;Mini-catalogue</br> catalog&#124;Catalogue détail</br> faq_category&#124;FAQ Category</br> w2s_detail&#124;W2S detail page</br> page&#124;Simple page</br> seo&#124;SEO page|Sélectionnez le type de contenu auquel associer l’image par défaut affichée sur la page de Résultats de recherche.|
|Image  |Image          |field_csimg_img|Image  |                                                                                                                                                                                                       |Renseignez l’image à afficher sur la page de Résultats de recherche. Ratio conseillé : 157x95 pixels.             |

## **Edito content on Product detail item (pe\_item)**
This paragraph is used to insert item for Edito content on Product detail page.

French label : Elément contenu Edito page Produit

### Fields

| Name    | Label (fr) | Machine name      | Type       | Description/Options             | Help Text (fr)                                              |
| ------- | ---------- | ----------------- | ---------- | ------------------------------- | ----------------------------------------------------------- |
| Content | Contenu    |                   | Details    |                                 |                                                             |
| Image\* | Image      | field\_pei\_image | Image      |                                 | Renseignez l’image du contenu.                              |
| Label   | Label      | field\_pei\_label | Text field |                                 | Renseignez le label affiché au dessus du titre (optionnel). |
| Title\* | Titre      | field\_pei\_title | Text field |                                 | Renseignez le titre du contenu.                             |
| Link\*  | Lien       | field\_pei\_link  | Link       | With option “Open in a new tab” | Renseignez le lien du contenu.                              |

## **Fichier Grille de produits (products\_grid\_file)**
This paragraph is used to insert line on Mini Catalog.

French label : Grille de produits - Import 

### Fields

|Name   |Label (fr)|Machine name   |Type   |Description/Options|Help Text (fr)                                                                                                   |
|-------|----------|---------------|-------|-------------------|-----------------------------------------------------------------------------------------------------------------|
|Content|Contenu   |               |Details|                   |                                                                                                                 |
|Fichier|Fichier   |field_pgf_file |File   |                   |Importez le fichier contenant les produits à ajouter.</br>  Format recommandé : TXT.</br> Une référence produit par ligne. |
|Titre  |Titre     |field_pgf_title|Text   |txt                |Renseignez le titre du bloc (optionnel).                                                                         |

## **ESDB Atouts Solution (esdb\_solution\_benefit\_line)**
This paragraph is used to insert line on CT “ESDB - Page Solution”.

French label : ESDB Atouts Solution 

### Fields

| Name    | Label (fr) | Machine name       | Type                                      | Description/Options | Help Text (fr) |
| ------- | ---------- | ------------------ | ----------------------------------------- | ------------------- | -------------- |
| Content | Contenu    |                    | Details                                   |                     |                |
| Items   | Items      | field\_esbl\_items | Paragraph (esdb\_solution\_benefit\_item) | 3 item              |                |

## **ESDB Atouts Solution Item (esdb\_solution\_benefit\_item)**
This paragraph is used to insert line items in PB “ESDB Atouts Solution”.

French label : ESDB Atouts Solution Item

### Fields

| Name          | Label (fr)    | Machine name         | Type                   | Description/Options | Help Text (fr) |
| ------------- | ------------- | -------------------- | ---------------------- | ------------------- | -------------- |
| Content       | Contenu       |                      | Details                |                     |                |
| Title         | Titre         | field\_esbli\_title  | Text                   |                     |                |
| Icon          | Icon          | field\_esbli\_icon   | ?                      | ?                   | ?              |
| Bullet points | Bullet points | field\_esbli\_points | Textarea (description) |                     |                |

## **Pictogram links (pictogram\_links)**
This paragraph is used to insert Pictogram links on PDP.

French label : 

### Fields

| Name             | Label (fr)          | Machine name    | Type    | Description/Options | Help Text (fr)                    |
| ---------------- | ------------------- | --------------- | ------- | ------------------- | --------------------------------- |
| Content          | Contenu             |                 | Details |                     |                                   |
| Pictogram code\* | Code du pictogramme | field\_pl\_code | Text    |                     | Renseignez le code du pictogramme |
| Pictogram Link\* | Lien du pictogramme | field\_pl\_link | Link    |                     | Renseignez le lien du pictogramme |

## **Marketing block (pdp\_marketing\_block)**
This paragraph is used to insert Marketing blocks on PDP.

French label : Bloc Marketing

### Fields

|Name          |Label (fr)           |Machine name            |Type           |Description/Options              |Help Text (fr)                                                                |
|--------------|---------------------|------------------------|---------------|---------------------------------|------------------------------------------------------------------------------|
|Content       |Contenu              |                        |Details        |                                 |                                                                              |
|Title         |Titre                |field_pdpm_title        |Text field     |                                 |Renseignez le titre du bloc. Il sera utilisé seulement en BO.                 |
|Image*        |Image                |field_pdpm_image        |Image          |                                 |Téléchargez l’image du bloc.                                                  |
|Url           |URL                  |field_pdpm_url          |Link           |(with option “Open in a new tab”)|Renseignez l’URL vers lequel l’utilisateur sera dirigé.                       |
|Category list |Catégories           |field_pdpm_cat          |Remote (agency)|Widget &#124; Autocomplete, Multiple  |Choisissez les catégories de produits concernées par la campagne marketing.   |
|Product list  |Produits             |field_pdpm_prod         |File (csv)     |                                 |Choisissez les produits concernés par la campagne marketing.                  |
|Visibility    |Visibilité           |field_par_role_access   |Roles Access   |                                 |Définissez la visibilité par profil du bloc.                                  |
|Publish Date  |Date de publication  |field_hpp_publish_date  |Date           |                                 |Renseignez la date à laquelle le contenu sera automatiquement publié.         |
|Publish time  |Heure de publication |field_hpp_publish_time  |               |                                 |Renseignez l’heure à partir de laquelle le contenu sera automatiquement publié|
|Unpublish Date|Date de dépublication|field_hpp_unpublish_date|Date           |                                 |Renseignez la date à laquelle le contenu sera automatiquement dépublié.       |
|Unpublish time|Heure de publication |field_hpp_unpublish_time|               |                                 |Renseignez l’heure à partir de laquelle le contenu sera automatiquement publié|


## **ESDB Conseils Line (esdb\_advice\_line)**
This paragraph is used to insert line on CT “ESDB - Page Solution”.

French label : ESDB Conseils

### Fields

| Name     | Label (fr) | Machine name        | Type                         | Description/Options | Help Text (fr) |
| -------- | ---------- | ------------------- | ---------------------------- | ------------------- | -------------- |
| Content  | Contenu    |                     | Details                      |                     |                |
| Conseils | Conseils   | field\_eadl\_advice | Reference(node:advice\_esdb) | Multiple            |                |

## **ESDB Pushes (esdb\_pushes)**
This paragraph is used to insert ESDB Pushes on Homepage.

French label : Push ESDB

### Fields

|Name         |Label (fr)         |Machine name              |Type            |Description/Options            |Help Text (fr)                                                                   |
|-------------|-------------------|--------------------------|----------------|-------------------------------|---------------------------------------------------------------------------------|
|Content      |Contenu            |                          |Details         |                               |                                                                                 |
|Block title* |Titre du bloc      |field_epushes_block_title |Text            |                               |Renseignez le titre du bloc.                                                     |
|Title        |Titre du push      |field_epushes_title       |Text            |                               |Renseignez le titre de la bannière push.                                         |
|Description  |Description du push|field_epushes_description |Text            |                               |Renseignez la description de la bannière push.                                   |
|Link         |Lien               |field_epushes_link        |Link            |With option “Open in a new tab”|Renseignez le lien de la bannière push.                                          |
|Image*       |Image - Desktop    |field_epushes_image       |Image           |                               |Ajoutez l’image (desktop) de la bannière push.                                   |
|Image mobile*|Image - Mobile     |field_epushes_image_mobile|Image           |                               |Ajoutez l’image (mobile) de la bannière push.                                    |
|Type*        |Type de push       |field_epushes_type        |Select          |type_1&#124;Banner type_2&#124;Promo push|Sélectionnez le type de représentation visuelle du push parmi les 2 disponibles. |
|Products*    |Products           |field_epushes_products    |Remote (product)|Multiple                       |Renseignez les produits à afficher dans le carousel.                             |


## **Pushes PLP (esdb\_pushes\_plp)**
This paragraph is used to insert Pushes on PLP.

French label : Push Page Liste

### Fields

|Name            |Label (fr)         |Machine name                |Type             |Description/Options                                               |Help Text (fr)                                                                                            |
|----------------|-------------------|----------------------------|-----------------|------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
|Content         |Contenu            |                            |Details          |                                                                  |                                                                                                          |
|Title           |Titre du push      |field_epush_plp_title       |Text             |                                                                  |Renseignez le titre de la bannière push.                                                                  |
|Position*       |Position           |field_epush_plp_position    |Number &#124; Integer |Min: 1 Max: 24                                                    |Définissez la position du push (entre 1 et 24). Le push sera affiché dans la liste à la position définie. |
|Category        |Catégorie          |field_epush_plp_category    |Remote (category)|Widget &#124; Autocomplete                                             |Sélectionnez la catégorie où afficher le Push.                                                            |
|Special pages   |Pages Promotions   |field_epush_plp_spages      |Select           |web_promotions&#124; Web promo promotions_agence&#124; Agency promo         |Sélectionnez les pages Promotions sur lesquelles le Push sera affiché.                                    |
|Description     |Description du push|field_epush_plp_description |Text             |                                                                  |Renseignez la description de la bannière push.                                                            |
|Link            |Lien               |field_epush_plp_link        |Link             |With option “Open in a new tab” Title optional                    |Renseignez le lien de la bannière push.                                                                   |
|Image*          |Image - Desktop    |field_epush_plp_image       |Image            |                                                                  |Ajoutez l’image (desktop) de la bannière push.                                                            |
|Image mobile*   |Image - Mobile     |field_epush_plp_image_mobile|Image            |                                                                  |Ajoutez l’image (mobile) de la bannière push.                                                             |
|Type*           |Type de push       |field_epush_plp_type        |Select           |type_1&#124;Product-box 1 type_2&#124;Product-box 2 type_3&#124;Horizontal banner|Sélectionnez le type de Push.                                                                             |
|Disable overlay |Dégradé de couleur |field_epush_plp_overlay     |Boolean          |                                                                  |Cochez cette case pour désactiver le dégradé de couleur appliqué sur l’image de la bannière push          |
|Background color|Couleur de fond    |field_epush_plp_background  |Colorpicker      |                                                                  |Choisissez la couleur du fond de la bannière push.                                                        |
|Visibilité      |Visibilité         |field_par_role_access       |Roles Access     |                                                                  |                                                                                                          |


## **ESDB Related products Carousel (esdb\_related\_products\_carousel)**
This paragraph is used to insert Related products Carousel.

French label : Carousel Produits ESDB

### Fields

|Name    |Label (fr)|Machine name      |Type            |Description/Options|Help Text (fr)                                       |
|--------|----------|------------------|----------------|-------------------|-----------------------------------------------------|
|Content |Contenu   |                  |Details         |                   |                                                     |
|Title   |Titre     |field_prc_title   |Text            |                   |                                                     |
|Image   |Image     |field_rpc_image   |Image           |                   |Renseignez l’image affichée à gauche du carousel.    |
|Products|Products  |field_rpc_products|Remote (product)|Multiple           |Renseignez les produits à afficher dans le carousel. |


## **ESDB Products Carousel (esdb\_products\_carousel\_line)**
This paragraph is used to insert line on CT “ESDB - Page Solution”.

French label : ESDB Products Carousel

### Fields

|Name    |Label (fr)|Machine name       |Type            |Description/Options|Help Text (fr)|
|--------|----------|-------------------|----------------|-------------------|--------------|
|Content |Contenu   |                   |Details         |                   |              |
|Title   |Titre     |field_epcl_title   |Text            |                   |              |
|Products|Products  |field_epcl_products|Remote (product)|Multiple           |              |


## **ESDB Styles & Solutions (esdb\_styles\_solutions)**
This paragraph is used to insert ESDB Styles & Solutions block.

French label : Bloc Styles & Solutions ESDB

### Fields

|Name          |Label (fr) |Machine name               |Type                          |Description/Options              |Help Text (fr)                                                           |
|--------------|-----------|---------------------------|------------------------------|---------------------------------|-------------------------------------------------------------------------|
|Content       |Contenu    |                           |Details                       |                                 |                                                                         |
|Title         |Titre      |field_esdb_sas_title       |Textfield                     |                                 |Renseignez le titre du bloc.                                             |
|Description   |Description|field_esdb_sas_description |Textarea (Plain text)         |                                 |Renseignez la description du bloc.                                       |
|Link          |Lien       |field_esdb_sas_link        |Link                          |With option “Open in a new tab”. |Renseignez le label et l’URL du lien affiché sous la description du bloc.|
|Items Style   |Styles     |field_esdb_sas_style_ref   |Reference (node:esdb_style)   |Multiple                         |Ajoutez les Styles préalablement créés.                                  |
|Items Solution|Solutions  |field_esdb_sas_solution_ref|Reference (node:esdb_solution)|Multiple                         |Ajoutez les Solutions préalablement créées.                              |


## **ESDB Tools (esdb\_tools)**
This paragraph is used to insert ESDB Tools block.

French label : Bloc Outils ESDB

### Fields

|Name   |Label (fr)|Machine name          |Type     |Description/Options                               |Help Text (fr)                                                 |
|-------|----------|----------------------|---------|--------------------------------------------------|---------------------------------------------------------------|
|Content|Contenu   |                      |Details  |                                                  |                                                               |
|Title  |Titre     |field_esdb_tools_title|Textfield|                                                  |Renseignez le titre du bloc.                                   |
|Items  |Eléments  |field_esdb_tools_items|Paragraph|Multiple &#124; Reference: Paragraph: (esdb_tools_item)|Ajoutez les différents éléments “Outils” affichés dans le bloc.|


## **ESDB Tools item (esdb\_tools\_item)**
This paragraph is used to insert ESDB Tools item.

French label : Element Outil ESDB

### Fields

| Name        | Label (fr)  | Machine name                 | Type                  | Description/Options              | Help Text (fr)                           |
| ----------- | ----------- | ---------------------------- | --------------------- | -------------------------------- | ---------------------------------------- |
| Content     | Contenu     |                              | Details               |                                  |                                          |
| Title       | Titre       | field\_esdb\_ti\_title       | Textfield             |                                  | Renseignez le titre de l’Outil.          |
| Description | Description | field\_esdb\_ti\_description | Textarea (Plain text) |                                  | Renseignez la description de l’Outil.    |
| Link        | Lien        | field\_esdb\_ti\_link        | Link                  | With option “Open in a new tab”. | Renseignez le label et l’URL de l’Outil. |
| Image       | Image       | field\_esdb\_ti\_image       | Image                 |                                  | Renseignez l’image de l’Outil.           |

## **Checkout Sidebar Information Block (checkout\_sidebar\_information)**
Information block for checkout sidebar.

French label : Bloc d’information du récapitulatif du checkout

### Fields

| Name          | Label (fr)  | Machine name            | Type                      | Description/Options | Help Text (fr) |
| ------------- | ----------- | ----------------------- | ------------------------- | ------------------- | -------------- |
| Content       | Contenu     |                         | Details                   |                     |                |
| Title         |             | field\_csi\_title       |                           |                     |                |
| Description\* | Description | field\_csi\_description | Textarea (decorated text) |                     |                |
| Profile       | Utilisateur | field\_csi\_profile     | Roles Access              |                     |                |

## **Checkout Wysiwyg Block (checkout\_wysiwyg)**
Wysiwyg block for checkout page.

French label : Blocs wysiwyg du checkout

### Fields

|Name            |Label (fr)          |Machine name            |Type                     |Description/Options                                                                         |Help Text (fr)                                                                    |
|----------------|--------------------|------------------------|-------------------------|--------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
|Description*    |Description         |field_cw_description    |Textarea (decorated text)|                                                                                            |Renseignez le contenu du bloc.                                                    |
|Stock source*   |Stock source ID     |field_cw_stock_source   |Textfield                |                                                                                            |Renseignez les stock sources ID pour lesquels il faut afficher le bloc wysiwyg.   |
|Delivery option*|Méthode de livraison|field_cw_delivery_option|Textfield                |                                                                                            |Renseignez la méthode de livraison pour laquelle il faut afficher le bloc wysiwyg.|
|Cart Type       |Type de panier      |field_cw_cart_type      |List (Text)              |Default is “All”.</br> DEFAULT&#124;Classic</br> Order QUOTE&#124;Quote</br> Transformation</br> CHECKOUT_REQUEST&#124;LA</br> Order|Choisissez le type de panier sur lequel le block wysiwyg sera affiché.            |
|Profile         |Utilisateur         |field_cw_profile        |Roles Access             |                                                                                            |Choisissez les utilisateurs pour lesquels il faut afficher le bloc wysiwyg.       |

## **Delivery service icon (delivery\_service\_icon)**
Delivery services icons for the checkout page.

French label : Icônes des services de livraison du checkout

### Fields

|Name         |Label (fr)                   |Machine name          |Type     |Description/Options|Help Text (fr)                                        |
|-------------|-----------------------------|----------------------|---------|-------------------|------------------------------------------------------|
|Service ID*  |ID du service de livraison   |field_dsi_service_id  |Textfield|                   |Renseignez l’ID du service de livraison du checkout   |
|Service icon*|Icône du service de livraison|field_dsi_service_icon|File     |svg                |Choisissez l’icône du service de livraison du checkout|


## **Conseils tabs (conseils\_tabs)**
This paragraph is used to add Conseils tabs
French label : Tabs

### Fields

| Name    | Label (fr) | Machine name                 | Type       | Description/Options | Help Text (fr)                                        |
| ------- | ---------- | ---------------------------- | ---------- | ------------------- | ----------------------------------------------------- |
| Title\* | Title      | field\_conseils\_tabs\_title | Text field |                     |                                                       |
| Link\*  | Link       | field\_conseils\_tabs\_link  | List       | Drop-down list      |                                                       |
| Image\* | Image      | field\_conseils\_tabs\_image | Image      |                     | Renseignez l’image à afficher dans l’onglet concerné. |

## **Advice marketing (advice\_marketing)**
This paragraph is used to add advice marketing block
French label : Bloc marketing

### Fields

| Name    | Label (fr)     | Machine name                    | Type  | Description/Options          | Help Text (fr)                                                              |
| ------- | -------------- | ------------------------------- | ----- | ---------------------------- | --------------------------------------------------------------------------- |
| Image\* | Image          | field\_advice\_marketing\_image | Image |                              | Renseignez l’image à afficher dans le bloc marketing de la page Conseils.   |
| Link\*  | Lien           | field\_advice\_marketing\_link  | Link  | URL + open in new tab option | Renseignez le lien du bloc marketing de la page Conseils.                   |
| Name    | Nom (tracking) | field\_advice\_marketing\_name  | Text  | NOT output on front-end      | Renseignez la valeur de ce champ, qui sera utilisée à des fins de tracking. |

## **Advice video (advice\_video)**
This paragraph is used to add advice video block
French label : Bloc vidéo

### Fields

| Name    | Label (fr) | Machine name                | Type  | Description/Options          | Help Text (fr)                                                        |
| ------- | ---------- | --------------------------- | ----- | ---------------------------- | --------------------------------------------------------------------- |
| Image\* | Image      | field\_advice\_video\_image | Image |                              | Renseignez l’image à afficher dans le bloc vidéo de la page Conseils. |
| Link\*  | Lien       | field\_advice\_video\_link  | Link  | URL + open in new tab option | Renseignez le lien de la vidéo de la page Conseils.                   |

## **Section (section)**
This paragraph is used to add sections to editorial pages.
French label : Section

### Fields

|Name              |Label (fr)           |Machine name        |Type                      |Description/Options                                                                                                                                                                                                                                          |Help Text (fr)                                                                     |
|------------------|---------------------|--------------------|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
|Title             |Titre                |field_section_title |Text (Plain)              |Define a title for your section. Optionnal.                                                                                                                                                                                                                  |Renseignez le titre de la section.                                                 |
|Title Localisation|Localisation du Titre|field_tplb_title_loc|List (Text)               |Define the title localisation in the bloc.</br> Default is “Top Left”.</br> 0&#124;Top Left</br> 1&#124;Top Centered</br> 2&#124;Top Right                                                                                                                                                      |Choisissez l’endroit où le titre doit être affiché.                                |
|Blocs             |Blocs                |field_section_blocs |Reference to Custom Blocks|Inline Entity Form - Complex</br>  Form mode: Default</br> Overriden labels are used:</br> Bloc and Blocs</br> New Blocs can be added.</br> Existing Blocs can not be referenced.</br>  Check all custom blocks type that you want to add to the template engine system on editorial pages.|Ajoutez des blocs dans la section.                                                 |
|Layout            |Mise en page         |field_section_layout|Paragraph (layout)        |Inline Entity Form - Simple Reference to Layout</br> Paragraph                                                                                                                                                                                                    |                                                                                   |
|Anchor            |Ancre                |field_section_anchor|Text (Plain)              |Define an anchor for your section. It will be useful for the “block anchor” display.                                                                                                                                                                         |Renseignez le titre de l’ancre si nécessaire. Il sera affiché dans le bloc “ancre”.|

## **Layout (layout)**
This paragraph is used to configure layout in editorial pages (on Sections and Custom Blocks).
French label : Mise en page

### Fields

|Name                 |Label (fr)               |Machine name                 |Type       |Description/Options                                                                                           |Help Text (fr)                                                                                                                                                      |
|---------------------|-------------------------|-----------------------------|-----------|--------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Layout Management    |Mise en Page             |                             |Details    |Contains fields to define layout for devices.</br> Default state closed</br> Mark as required                           |Choisissez la mise en page à appliquer à la section/bloc.                                                                                                           |
|Layout Width*        |Mise en page Desktop     |field_layout_desktop         |List (Text)|Define the width for Desktop and Tablet devices.</br> For Mobile is 100 by default.</br> 25&#124;25</br> 33&#124;33</br> 50&#124;50</br> 75&#124;75</br> 100&#124;100|Choisissez la taille de la section ou du bloc pour desktop et tablette. Pour le mobile, un affichage responsive sera réalisé et prendra toute la largeur de la page.|
|Full Width Centered  |Centré sur toute la ligne|field_full_width_centered    |Checkbox   |Check this if you want the block/section to be centered and takeall the line width.                           |Cochez la case si vous voulez un affichage centré sur toute la ligne de la section ou du bloc.                                                                      |
|Color Management     |Gestion des couleurs     |                             |Details    |Contains fields to define color options.</br> Default state closed</br> Mark as required                                |Choisissez les options de couleur à appliquer à la section/bloc.                                                                                                    |
|Title Color          |Couleur du Titre         |field_layout_text_color      |Colorpicker|Define color for the block/section title. It can be usefull if you define a background color (to contrast).   |Choisissez la couleur du titre.                                                                                                                                     |
|Background Color     |Couleur de fond          |field_layout_background_color|Colorpicker|Define background color for the block/section.                                                                |Choisissez la couleur de fond du background.                                                                                                                        |
|Decoration Management|Gestion des décorations  |                             |Details    |Contains fields to define decoration for your section or bloc..</br> Default state closed</br> Mark as required         |Choisissez les options supplémentaires de décoration à appliquer à la section/bloc.                                                                                 |
|Border Color         |Couleur de la bordure    |field_layout_background_color|Colorpicker|Define color for the border of the section or the bloc. Optional.                                             |Choisissez la couleur de la bordure.                                                                                                                                |
|Shadow Box Effect    |Effet d’ombre de bordure |field_shadow_box_effect      |Checkbox   |Check this if you want the block/section to have a shadow box effect. Override border color if exist.         |Cochez cette case si vous souhaitez ajouter un effet d’ombre, cela annulera la couleur de la bordure s’il y en a une.                                               |

## **Editorial Download File (editorial\_download\_file)**
This paragraph is used to add a document download object at the download block.
French label : Document éditorial à télécharger

### Fields

|Name              |Label (fr)           |Machine name      |Type        |Description/Options                                           |Help Text (fr)                                                                                                    |
|------------------|---------------------|------------------|------------|--------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
|File Title        |Titre du fichier     |field_edf_title   |Text (Plain)|Define a file title if you want to override the real filename.|Renseignez le titre du fichier qui sera affiché si vous souhaitez qu’il soit différent de celui du nom du fichier.|
|Presentation Image|Image de présentation|field_edf_img_pres|Image       |Define an image for visual presentation of the block.         |Renseignez l’image qui sera affichée dans le bloc.                                                                |
|File*             |Fichier              |field_edf_file    |File        |The file to download.                                         |Téléchargez le fichier à télécharger.                                                                             |


## **Editorial Slide (editorial\_slide)**
This paragraph is used to add a slide in the carousel block.
French label : Slide éditoriale

### Fields

|Name             |Label (fr)             |Machine name     |Type            |Description/Options                                                                                                                                                                             |Help Text (fr)                                                                                                                                                          |
|-----------------|-----------------------|-----------------|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Slide Title      |Titre de la slide      |field_es_title   |Text (Plain)    |Define a title to display in your slide.                                                                                                                                                        |Renseignez le titre de la slide.                                                                                                                                        |
|Slide Description|Description de la slide|field_es_des     |Textarea        |Define a description for your slide.                                                                                                                                                            |Renseignez la description de la slide.                                                                                                                                  |
|Slide Image*     |Image de la slide      |field_es_img     |Image           |Define an image for your slide                                                                                                                                                                  |Renseignez l’image à afficher dans la slide.                                                                                                                            |
|Slide CTA        |CTA de la slide        |field_es_cta     |Link with Target|Define the link of your CTA.</br> Text for the link is required (will be used inside the button).</br> Target : Open in a new window                                                                      |Renseignez le CTA à afficher dans la slide.                                                                                                                             |
|Image display*   |Affichage de l’image   |field_es_img_pos |List (Text)     |Define how the slide image will be displayed. Default is 100 - All Width</br>  100&#124;All Width</br> 50L&#124;Width 50 Align Left</br> 50R&#124;Width 50 Align Right                                                        |Choisissez le format et l’affichage de l’image dans la slide. Par défaut, elle est affichée à 100%.                                                                     |
|Text display*    |Affichage du texte     |field_es_text_pos|List (Text)     |Define how the text will be displayed. Default is 50R. This text part includes Title, Description and CTA in the bottom.</br>  50R&#124;Width 50 Align Right</br> 50L&#124;Width 50 Align Left</br> 50C&#124;Width 50 Centered|Choisissez le format et l’affichage du texte dans la slide. Cela concerne, le titre, la description et le lien. Par défaut, ils sont affichés à 50% et alignés à droite.|

## **Editorial Service (editorial\_service)**
This paragraph is used to add a service field group in the service block.
French label : Service éditorial

### Fields

|Name               |Label (fr)            |Machine name   |Type            |Description/Options                                                                                                        |Help Text (fr)                                                                                                   |
|-------------------|----------------------|---------------|----------------|---------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|
|Service Title*     |Titre du service      |field_esr_title|Text (Plain)    |Define a title to display in your service.                                                                                 |Renseignez le titre du service.                                                                                  |
|Service Description|Description du service|field_esr_des  |Textarea        |Define a description for your service.                                                                                     |Renseignez la description du service.                                                                            |
|Service Image      |Image du service      |field_esr_img  |Image           |Define an image for your service                                                                                           |Téléchargez l’image associée au service.                                                                         |
|Service CTA        |CTA du service        |field_esr_cta  |Link with Target|Define the link of your CTA. Text for the link is required (will be used inside the button). Target : Open in a new window |Renseignez le lien à afficher et définissez s’il doit s'ouvrir dans la même fenêtre ou dans une nouvelle fenêtre.|


## **Editorial Icon (editorial\_icon)**
This paragraph is used to add an icon field group in the icons block.
French label : Icone éditoriale

### Fields

|Name            |Label (fr)            |Machine name             |Type            |Description/Options                                                                                      |Help Text (fr)                                                                                                   |
|----------------|----------------------|-------------------------|----------------|---------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|
|icon Title      |Titre de l’icône      |field_ei_title           |Text (Plain)    |Define a title to display in your icon.                                                                  |Renseignez le titre associé à l’icône.                                                                           |
|Icon Description|Description de l’icône|field_ei_des             |Textarea        |Define a description for your icon.                                                                      |Renseignez la description associée à l’icône.                                                                    |
|Icon Image*     |Image de l’icône      |field_ei_img             |Image           |Define an image for your icon                                                                            |Télécharger l’icône.                                                                                             |
|Icon CTA        |CTA de l’icône        |field_ei_cta             |Link with Target|Define the link of your CTA. This link is on the image if it exists. Target : Open in a new window or not|Renseignez le lien à afficher et définissez s’il doit s'ouvrir dans la même fenêtre ou dans une nouvelle fenêtre.|
|Icon Alignment  |Alignement de l’icône |field_tplb_icon_alignment|List (Text)     |Define the alignment. Default is “Aligned Left”.</br> 0&#124;Aligned Left</br> 1&#124;Below the Title                        |Choisissez l’endroit où l’icône doit être affichée.                                                              |

## **Editorial Tile (editorial\_tile)**
This paragraph is used to add a tile field group in the tiles block.
French label : Tuile éditoriale

### Fields

|Name          |Label (fr)        |Machine name      |Type            |Description/Options                                                                                                            |Help Text (fr)                                                                                                   |
|--------------|------------------|------------------|----------------|-------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|
|Tile Title*   |Titre de la tuile |field_et_title    |Text (Plain)    |Define a title to display in your tile.                                                                                        |Renseignez le titre de la tuile.                                                                                 |
|Tile Image*   |Image de la tuile |field_et_img      |Image           |Define an image for your tile.                                                                                                 |Téléchargez l’image à afficher                                                                                   |
|Tile Link     |Lien de la tuile  |field_et_link     |Link with Target|Define the link of your tile. This link is on the entire tile if it exists. Target : Open in a new window or not               |Renseignez le lien à afficher et définissez s’il doit s'ouvrir dans la même fenêtre ou dans une nouvelle fenêtre.|
|Title display*|Affichage du titre|field_et_title_pos|List (Text)     |Define where the title will be displayed. Default is BL (Bottom Left).</br>  BL&#124;Bottom Left</br> BR&#124;Bottom Right</br> TL&#124;Top Left</br> TR&#124;Top Right|Choisissez l’emplacement du titre. Par défaut, il est affiché en bas du bloc aligné à gauche.                    |

## **Premium brand page banner (premium\_brand\_page\_banner)**
This paragraph is used to add a banner on premium brand page.
French label : Bannière premium

### Fields

| Name          | Label (fr)    | Machine name                       | Type  | Description/Options | Help Text (fr)                                                |
| ------------- | ------------- | ---------------------------------- | ----- | ------------------- | ------------------------------------------------------------- |
| Desktop image | Image desktop | field\_pbp\_banner\_desktop\_image | Image |                     | Téléchargez l’image qui sera affichée pour le format desktop. |
| Mobile image  | Image mobile  | field\_pbp\_banner\_mobile\_image  | Image |                     | Téléchargez l’image qui sera affichée pour le format mobile.  |

## **Premium brand page wysiwyg (premium\_brand\_page\_wysiwyg)**
This paragraph is used to add a wysiwyg block on premium brand page.
French label : Bloc wysiwyg premium

### Fields

| Name            | Label (fr) | Machine name                 | Type                     | Description/Options | Help Text (fr)                         |
| --------------- | ---------- | ---------------------------- | ------------------------ | ------------------- | -------------------------------------- |
| WYSIWYG content | WYSIWYG    | field\_pbp\_wysiwyg\_content | Textarea (Filtered HTML) |                     | Renseignez le contenu du bloc wysiwyg. |

## **Full HTML block (full\_html\_block)**
This paragraph is used to add a wysiwyg block on premium brand page.
French label : Full HTML block premium

### Fields

| Name    | Label (fr) | Machine name        | Type                 | Description/Options | Help Text (fr)                                                                    |
| ------- | ---------- | ------------------- | -------------------- | ------------------- | --------------------------------------------------------------------------------- |
| Content | Contenu    | field\_fhb\_content | Textarea (Full HTML) |                     | Renseignez le contenu du bloc Full HTML. Les scripts ne peuvent pas être ajoutés. |

## **Premium brand page slider (premium\_brand\_page\_slider)**
This paragraph is used to add a slider block on premium brand page.
French label : Carrousel premium

### Fields

| Name   | Label (fr) | Machine name       | Type                                                                                                                                    | Description/Options | Help Text (fr)                |
| ------ | ---------- | ------------------ | --------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ----------------------------- |
| Slider | Carrousel  | field\_pbp\_slider | Paragraph ([image\_slide](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.dm7371q30x78)) |                     | Ajoutez un carrousel premium. |

## **Image slide (image\_slide)**
This paragraph is used to add a slide in a slider on premium brand page.
French label : Slides du carrousel premium

### Fields

| Name  | Label (fr) | Machine name     | Type  | Description/Options | Help Text (fr)                                                     |
| ----- | ---------- | ---------------- | ----- | ------------------- | ------------------------------------------------------------------ |
| Image | Image      | field\_is\_image | Image |                     | Téléchargez l’image souhaitée qui sera affichée dans le carrousel. |

## **Univers block (univers\_block)**
This paragraph is used to add a univers block on premium brand page.
French label : Bloc univers premium

### Fields

| Name         | Label (fr)    | Machine name             | Type                                                                                                                                            | Description/Options | Help Text (fr)                                                    |
| ------------ | ------------- | ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ----------------------------------------------------------------- |
| Logo         | Logo          | field\_ub\_logo          | Image                                                                                                                                           |                     | Téléchargez le logo qui sera affiché en dessous du titre du bloc. |
| Title        | Titre         | field\_ub\_title         | textfield                                                                                                                                       |                     | Renseignez le titre du bloc.                                      |
| Univers line | Ligne univers | field\_ub\_univers\_line | Paragraph ([univers\_block\_line](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.aptie7elz6wy)) |                     | Ajoutez une ligne d’items univers.                                |

## **Univers block line (univers\_block\_line)**
This paragraph is used to add a univers line on premium brand page.
French label : Ligne d’items univers

### Fields

| Name           | Label (fr)           | Machine name                | Type                                                                                                                                            | Description/Options | Help Text (fr)                                 |
| -------------- | -------------------- | --------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ---------------------------------------------- |
| Image location | Placement de l’image | field\_ubl\_image\_location | Liste (texte)                                                                                                                                   |                     | Choisissez l’endroit où l’image sera affichée. |
| Univers items  | Items univers        | field\_ubl\_univers\_item   | Paragraph ([univers\_push\_block](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.mnl7mgofrtog)) |                     | Ajoutez les items univers.                     |

## **Univers push block (univers\_push\_block)**
This paragraph is used to add a univers push block univers line on premium brand page.
French label : Item univers

### Fields

| Name             | Label (fr)    | Machine name                 | Type      | Description/Options | Help Text (fr)                                                                        |
| ---------------- | ------------- | ---------------------------- | --------- | ------------------- | ------------------------------------------------------------------------------------- |
| Desktop image    | Image desktop | field\_upb\_image\_desktop   | Image     |                     | Téléchargez l’image qui sera affichée pour le format desktop.                         |
| Mobile image     | Image mobile  | field\_upb\_image\_mobile    | Image     |                     | Téléchargez l’image qui sera affichée pour le format mobile.                          |
| Item description | Description   | field\_upb\_item\_descriptio | Textarea  |                     | Renseignez la description de l’univers.                                               |
| Item title       | Titre         | field\_upb\_item\_title      | Textfield |                     | Renseignez le titre de l’univers.                                                     |
| Link             | Lien          | field\_upb\_link             | Link      |                     | Renseignez le lien vers lequel l’utilisateur sera renvoyé s’il clique dans l’univers. |

## **Premium promoted products (premium\_promoted\_products)**
This paragraph is used to add a promoted products block on premium brand page.
French label : Produits mis en valeur premium

### Fields

| Name              | Label (fr)             | Machine name                   | Type             | Description/Options | Help Text (fr)                                          |
| ----------------- | ---------------------- | ------------------------------ | ---------------- | ------------------- | ------------------------------------------------------- |
| Title             | Titre                  | field\_ppp\_title              | Textfield        |                     | Renseignez le titre du bloc.                            |
| Description       | Description            | field\_ppp\_description        | Textarea         |                     | Renseignez la description du bloc.                      |
| Background color  | Couleur de background  | field\_ppp\_background\_color  | Colorpicker      |                     | Choisissez la couleur de fond du bloc.                  |
| CTA               | Button                 | field\_ppp\_cta                | Link             |                     | Renseignez le label et le lien du button.               |
| Promoted products | Produits mis en valeur | field\_ppp\_promoted\_products | Remote (product) |                     | Choisissez les produits à mettre en valeur (3 maximum). |


## **Custom optional icon (custom\_optional\_icons)**
This paragraph is used to add optional icons on the header.
French label : 

### Fields

| Name       | Label (fr) | Machine name             | Type            | Description/Options | Help Text (fr)                                            |
| ---------- | ---------- | ------------------------ | --------------- | ------------------- | --------------------------------------------------------- |
| Icon       | Icône      | field\_coi\_icon         | File            | SVG                 | Téléchargez l’icône qui sera affichée dans le top header. |
| Link       | Lien       | field\_coi\_link         | URL with Target |                     | Renseignez l’URL de l’icône.                              |
| Visibility | Visibilité | field\_par\_role\_access | Roles Access    |                     | Choisissez quels utilisateurs pourront voir l’icône.      |

## **Burger Menu Item Level 3 (burger\_menu\_item\_level\_3)**
Paragraph used to affiliate images blocks to burger menu level 3 items.
French label : Burger menu item level 3

### Fields

| Name                    | Label (fr)               | Machine name            | Type                                                                                                                                              | Description/Options | Help Text (fr)                                                          |
| ----------------------- | ------------------------ | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ----------------------------------------------------------------------- |
| Menu Element Level 3 \* | Elément de menu niveau 3 | field\_bmi\_item        | Text | Menu Main level 3                                                                                                                          |                     | Choisissez l'élément du menu du niveau 3.                               |
| Background color        | Couleur de fond          | field\_bmi\_color       | Color Picker                                                                                                                                      |                     | Choisissez la couleur du fond à appliquer à l’item du menu du niveau 3. |
| Menu element color      | Couleur de la police     | field\_bmi\_text\_color | Color Picker                                                                                                                                      |                     | Choisissez la couleur de la police de l’item du menu du niveau 3.       |
| Image Blocks\*          | Bloc liste d’images      | field\_bmi\_items       | Paragraph ([esdb\_main\_menu\_item](https://docs.google.com/document/d/1gA63rLhAp7rmo6ArQ8OwplOak8aASDg3WxSfOUrZKH4/edit#heading=h.6mh6mnv9ogq1)) |                     | Ajoutez un bloc avec une liste d’images pour le menu burger.            |

## **Burger Menu See All Links (burger\_menu\_see\_all\_links)**
Paragraph used to affiliate "see all" links to burger menu level 2 items.
French label : Burger menu lien “voir tout”

### Fields

| Name                 | Label (fr)               | Machine name     | Type                     | Description/Options | Help Text (fr)                                              |
| -------------------- | ------------------------ | ---------------- | ------------------------ | ------------------- | ----------------------------------------------------------- |
| Menu Element Level 2 | Elément de menu niveau 2 | field\_bmi\_item | Text | Menu Main level 2 |                     | Choisissez l'élément du menu du niveau 2.                   |
| See All Link         | Lien “voir tout”         | field\_bmi\_link | Link + Title             |                     | Renseignez le lien vers lequel l’utilisateur sera redirigé. |

