# LaboData pour Prestashop

Module https://www.labodata.fr permettant d'importer des fiches produits dans Prestashop version 1.6 et 1.7


## FAQ

### Comment obtenir ma clé API ?

* Vous devez vous inscrire sur le site : https://www.labodata.fr
* Puis dans la zone **Mon compte**, consulter la section **Mon compte et API**


### Comment installer le module LaboData depuis GitHub ?

* Télécharger le master : https://github.com/161io/labodata-prestashop
* Extraire le fichier zip dans le dossier `modules`
* Veiller à ce que le dossier du module soit bien nommé `labodata`
* Enfin, vous devez configurer vos accès dans l'onglet **Configuration** du module


### Comment désinstaller "totalement" le module LaboData ?

1. Supprimer le module dans Prestashop
2. Supprimer les tables : `PREFIX_category_labodata` et `PREFIX_manufacturer_labodata`
