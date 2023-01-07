## Règles d'ajout de fichier ressources 
- Vous devez être un acteur de la création ou de la gestion de la ressource pour l'ajouter au répertoire GitHub.
- Le nom de la ressource doit respecter la convention de nommage imposée par Vesperae Studio : [Convention de nommage des fichiers](convention_naming.md)

- Les fichiers de ressources connus comme ayant plusieurs auteurs mais insérés sans fichier licence seront documentés par nos soins avec un ajout de fichier annexe avec l'extension ".product".
Veuillez vous référer à l'exemple [Shyran.png.product](Shyran.png.product). Rien ne vous en empêche de le faire vous même lors de votre ajout.
- Les fichiers de ressources que vous ajoutez peuvent être renommées par le propriétaire du répertoire GitHub. Si cela venait à arriver, nous allons préserver votre nom d'origine en le balisant dans le champs "name" à votre place.
- Les fichiers de ressources sans fichier associé avec le format ".licence", auront pour mentions dans le fichier LICENCE.TXT généré :
```
L'AUTEUR AUTORISE L'ORGANISATION À BUT NON LUCRATIF "VESPERAE STUDIO",
LOCALISÉE EN FRANCE, D'UTILISER CETTE RESSOURCE, À TITRE GRATUIT,
EXPRIMÉE PAR UNE ADHÉSION AU PROJET CONTRIBUTIF SUR GITHUB ET CE DE MANIÈRE PERMANENTE,
TANT QUE LES ENGAGEMENTS DE L'ADHÉSION SONT RESPECTÉS PAR L'ASSOCIATION
```
```
CETTE PRODUCTION ARTISTIQUE EST SOUMISE AU DROIT D'AUTEUR ET L'AUTEUR DE CELLE-CI AUTORISE
EXPRESSÉMENT L'ASSOCIATION VESPERAE STUDIO À L'UTILISER DANS SES PROJETS DANS LES MÊMES
CONDITIONS, PERMISSIONS ET AUTORISATIONS DEFINIT DANS LA LICENCE CREATIVE COMMONS CC0.
```
Tandis que les autres, auront pour mentions dans le fichier LICENCE.TXT généré :
```
L'AUTEUR AUTORISE L'ORGANISATION À BUT NON LUCRATIF "VESPERAE STUDIO",
LOCALISÉE EN FRANCE, D'UTILISER CETTE RESSOURCE, À TITRE GRATUIT,
EXPRIMÉE PAR UNE ADHÉSION AU PROJET CONTRIBUTIF SUR GITHUB ET CE DE MANIÈRE PERMANENTE,
TANT QUE LES ENGAGEMENTS DE L'ADHÉSION SONT RESPECTÉS PAR L'ASSOCIATION
```
```
VOTRE LICENCE PERSONNALISEE
```

## Règles d'ajout de fichier ".licence" :
- Le fichier ".licence" doit avoir un contenu de type texte encodé en UTF-8.
- Les phrases renseignées ne doivent pas excéder 80/85 caractères de longueur afin de rendre lisible facilement et aisément les contenus sur l'ensemble des supports.
- Le fichier pour être accepté, doit comporter le même nom que la ressource avec la concaténation de l'extension ".licence"
- Des méta-informations peuvent y être apportées grâce à du balisage XML, elles sont toutes facultatives. Veuillez vous référer à l'exemple [Delicious.png.licence](Delicious.png.licence).
- Tout ce qui n'est pas balisé, sera déposé tel quel dans la section licence pour le fichier concerné. Veuillez-vous référer à l'exemple [Sathisien.png.licence](Sathisien.png.licence).
- Les contenus des balises de licence qui ne comportent aucune notion d'autorisations / conditions / limites, ne seront pas acceptés et seront redirigés vers la création d'un fichier ".product".

## Contenu de votre licence personnalisé
- Votre contribution à ce répertoire GitHub suppose que vous souhaiter aider un projet collaboratif, nous vous demanderons alors de rédiger vos contenus de licence de manière à ce que par défaut que l'on cite ce que permet la licence de "[Creative Commons CC0](https://choosealicense.com/licenses/cc0-1.0/)" puis puis vous y apporter vos exclusions, limitations, conditions.
- Le contenu de la licence doit être réaliste vis à vis de son projet d'insertion dans nos projets (on ne peut pas accepter une licence qui autorise l'utilisation de la skin sur le jeu Slayers Online et non sur le site Slayers Online)

## Règles d'ajout de fichier ".product" :
- Le fichier ".product" doit avoir un contenu de type texte encodé en UTF-8.
- Les phrases renseignés ne doivent pas exceder 80/85 caractères de longueur afin de rendre lisible facilement et aisément les contenus sur tous les supports.
- Le fichier pour être accepté doit comporter le même nom que la ressource avec la concaténation de l'extension ".product"
- Des méta informations peuvent y être apportées grâce à du balisage XML, elles sont toutes facultatives. Veuillez vous référer à l'exemple [Shyran.png.product](Shyran.png.product).
- Tout ce qui n'est pas balisé, sera ignoré à la génération du fichier LICENCE.txt.

## Informations sur le balisage :
- ```<Name></Name>``` Définit le nom de la ressource. Ils figureront dans les fichiers [CREDIT.txt](CREDIT.txt) et [LICENCE.txt](LICENCE.txt).
- ```<Website></Website>``` Définit le lien vers le site de la ressource. Il sera visible dans le fichier [LICENCE.txt](LICENCE.txt).
- ```<Description></Description>``` Définit une description de la ressource. Il sera peut être utilisé ultérieurement sur le site.
- ```<Authors></Authors>``` Définit les auteurs de la contribution, vous pouvez utiliser les pseudos ou les noms réels, ils figureront dans les fichiers [CREDIT.txt](CREDIT.txt) et [LICENCE.txt](LICENCE.txt). Le séparateur pour séparer chaque auteur est le caractère ",".
- ```<CreationDate></CreationDate>``` Définit la date de la création de la ressource. Il sera visible dans le fichier [LICENCE.txt](LICENCE.txt).
- ```<ConclusionDate></ConclusionDate>``` Définit la date de la fin de la création de la ressource. Il sera visible dans le fichier [LICENCE.txt](LICENCE.txt).
- ```<Email></Email>``` Définit un email de contact pour la ressource. Il sera visible dans le fichier [LICENCE.txt](LICENCE.txt).
- ```<Licence></Licence>``` Définit le texte de la licence en langue française ou anglaise. Il sera visible dans le fichier [LICENCE.txt](LICENCE.txt).
- ```<LicenceName></LicenceName>``` Définit le nom de la licence en langue française ou anglaise. Il sera visible dans le fichier [LICENCE.txt](LICENCE.txt).
- ```<LicenceWebsite></LicenceWebsite>``` Définit le lien vers le site de la licence en langue française ou anglaise. Il sera visible dans le fichier [LICENCE.txt](LICENCE.txt).
