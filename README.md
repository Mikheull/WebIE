# WebDirectory

**WebDirectory** est un explorateur de fichiers/dossiers pour le web. Avec cet outil vous pourrez naviguez facilement entre vos dossiers, et créer autant de fichiers/dossiers que vous voulez directement depuis votre page web.
Vous pourrez également faire des actions sur les fichiers ( dupliquer, supprimer, télécharger )
**WebDirectory** a été conçu pour plaire au maximum de gens, de ce fait il est configurable vous pouvez choisir un thème d'explorateur (dark, light, modern ..) ou mettre un des votres, changer le pack d'icon et la traduction de l'outil.
Vous pouvez désormais configurer votre outil directement depuis la page
<br>

### Requirements :
* Php server


<br><hr>
### Installation :
Pour l'installation rien de plus simple, télécharger le fichier [index.php](https://raw.githubusercontent.com/Mikheull/WebDirectory/master/index.php) et glisser le simplement dans les dossiers ou vous voulez avoir le **WebDirectory** .
Voilà c'est tout, le script, par la suite, s'occupera de télécharger les fichiers dépendants tout seul.


### Configuration :
Une grande partie de l'outil est ouvert a la configuration pour vous permettre d'avoir votre version de **WebDirectory** parfaite.
*toutes les configurations se font en haut de la page index.php*

1) Thème :<br>
*Installez le thème qui vous plait, ou créer le votre*
```php
define('theme', 'dark');
```
- [x] dark
- [x] light
- [x] blue
- [x] red
- [x] green
- [x] orange
- [x] purple
- [x] yellow
<br>

2) Format de la date :<br>
*modifiez votre format*
```php
define('date_format', 'j-n-Y H:i:s');
```
*documentation du format ici -> http://php.net/manual/fr/function.date.php*
<br>

3) Pack d'icon :<br>
*personnalisez vos icons de fichiers*
```php
```
<br>

4) Traductions :<br>
*prenez votre langage favori*
```php
define('langage', 'FR');
```
- [x] FR
- [x] EN
- [x] ES
- [x] AL
<br>

5) Quelques réglagles :<br>
*Activer / Désactiver des options*<br>
Outil de création de fichier (true - false)
```php
define('file_creator', true);
```
Outil de création de dossier (true - false)
```php
define('file_creator', true);
```
<br><hr>

### TO-DO :
- [x] affichage des fichiers/dossiers
- [x] support des icons de fichiers
- [x] fonction de retour en arriere
- [x] création de dossier
- [x] création de fichier
- [x] ajouter les traductions
- [x] faire le menu d'aide
- [x] ajouter les raccourcis clavier
- [x] editer les réglages de configuration directement dans le WebDirectory
- [x] effectuer une mise a jour
- [x] ajouter des nouveaux thèmes
- [x] créer la possibilité d'ajouter un theme custom 
- [x] créer la possibilité d'ajouter un langage custom 
- [ ] trier les listes
- [ ] detecter les mise a jour et mettre un message en cookie
- [ ] détecter si localhost ou hebergement et faire une Auth unique si hebergement (ou local)
- [ ] securité sur la création de dossiers/fichiers
- [ ] ajouter un système de recherche (bouton, CTRL F)
- [ ] supprimer un élément
- [ ] archiver un élément (accessible dans une liste cachée en bas de page)
- [ ] renommer un élément
- [ ] dupliquer un élément
- [ ] télécharger un élément
- [ ] ajouter les packs d'icons
- [ ] ajouter plus de compatiblité d'icons de fichiers
- [ ] cloner un fichier / dossier dans un AUTRE dossier
- [ ] améliorer la vitesse d'affichage, afficher uniquement des divs vides au début, puis les remplir avec le chargement
- [ ] intégrer GoogleDrive, Dropbox et GitHub pour stocker les fichiers/dossiers
- [ ] ajouter des popups ( d'erreur, de succes, de confirmations )
- [ ] rendre compatible tout navigateur, tout OS
- [ ] rendre responsive l'outil
- [ ] créer le site de presentation de cet outil (page github)
