<h2>Affiche et gère un diaporama configurable</h2>
<h3>aide</h3>

Ativation du plugin
- aller dans le menu Paramètres > Plugins
- cocher le plugin MySlippry et dans le déroulant "Pour la sélection", sélectionner le menu "Activer"

Configuration du diaporama MySlippry
- Aller dans le menu Paramètres > Plugins, et cliquer sur le lien Configuration du plugin MySlippry

Pour ajouter des images au diaporama
- aller dans le gestionnaire des médias
- cocher les images à ajouter dans le diaporama
- dans le déroulant "Pour la sélection", sélectionner le menu MySlippry > Ajouter au diaporama

Activation et personnalisation des images du diaporama
- allez dans le menu MySlippry (dans le bandeau des menus de l'administration)
- renseigner les champs titre et description des images
- activer l'affichage en choisissant la valeur "Oui" dans la colonne "Active"
- cliquer sur le bouton "Modifier la liste des images" pour enregistrer les modifications

Affichage du diaporama sur la page d'accueil de son site
- éditer le fichier header.php de son theme
- ajouter la ligne suivante à l'endroit où vous souhaitez afficher le diaporama

<code style="color:#000;padding:0 10px 15px 10px;border:1px solid #dedede">&lt;?php eval($plxShow->callHook("MySlippry")) ?></code>

Affichage du diaporama dans une page statique
- éditer le contenu d'une page statique et allant dans la gestion des pages statiques: menu "Pages statiques" dans l'administration
- ajouter les lignes suivantes à l'endroit où vous souhaitez afficher le diaporama

<code style="color:#000;padding:0 10px 15px 10px;border:1px solid #dedede">&lt;?php eval($this->callHook("MySlippry")); ?></code>

<strong>Slippry</strong>: jQuery Image Slider Plugin.
<a href="http://slippry.com/">http://slippry.com/</a>
