## Règles d'ajout de fichier ressources : ".png", ".ogg", ".midi", ".wav", etc. :
- Vous devez être l'auteur de la ressource pour l'ajouter au repository.
- Le nom de la ressource doit respecter la convention de nommage imposée par Vesperae Studio :
```
Contraintes technique :
- Pas de caractère spéciaux de type apostrophe ou symbole (ex: ', ", €, etc. )
- Pas d'espace entre les mots, on les remplace par un underscore “_” (→ hall_arene)
- Pas de fautes d'orthographe dans le nom
- Ne pas utiliser d'articles ou mots de liaison (par exemple: le, la, du, de, en, pour, donc, sur, etc.)
- Un minimum de cohérence et de personnalisation en lien avec le contenu du fichier (→ chipset_admin_interieur_maison)
- Aucune majuscule sur vos noms de fichiers.
- Pas de caractère avec accent (é, è, ê, ë, à, …)
Exception : Les noms de skin et les noms de son n'ont pas ces obligations mais c'est une préférence.

Contraintes d'organisation :
- chipset de boss : boss_drake.png 
- chipset de monstre : monstre_lapin.png
- chipset contenant un ou des pnj : pnj_herodontos.png
- chipset de type effet : effet_brouillard.png
- chipset d'animation : anim_bulle_eau.png
- chipset de background : fond_coucher_soleil.png
- chipset de magie : magie_boule_feu.png
- chipset d'emote : emote_noel_1250.png
- chipset objets de décors : objet_cadeaux.png
- chipset de skin portable : NomLibreAuCreateur.png (soumis aux règles de SkinSO)
- chipset de type interface : interface_menu.png
- chipset de carte : chipset_foret_01.png, chipset_foret_sombre.png, chipset_grotte_vesperae.png, chipset_desert_solipha.png
- musique de jeu : musique_combat_01.midi, musique_combat_sombre.midi, musique_grotte_vesperae.midi, musique_desert_solipha.midi
- son du jeu : son_epee_01.wav, son_cloche_enervante.wav, son_grotte_vesperae.wav, son_desert_solipha.wav
- chipset de carte mixte (chipset + présence d'anim, pnj, etc.) : chipset_sarosa.png, chipset_chateau_roland.png
(c'est comme un chipset normal mais il faut préciser le lieu dans le cas d'un chipset mixte car très localisé)
- chipset de carte en pixel art : chipset_sarosa.png, chipset_chateau_roland.png. (c'est comme un chipset normal mais il faut préciser le lieu dans le cas d'un chipset très localisé)

```
- Les fichiers de ressources connus comme ayant plusieurs auteurs mais insérés sans fichier licence seront documentés par nos soins avec un ajout de fichier annexe avec l'extension ".product".
Veuillez vous référer à l'exemple [Shyran.png.product](Shyran.png.product). Rien ne vous en empêche de le faire vous même lors de votre ajout.

## Règles d'ajout de fichier ".licence" :
- Le fichier ".licence" doit avoir un contenu de type texte encodé en UTF-8.
- Le fichier pour être accepter doit comporter le même nom que la ressource avec la concaténation de l'extension ".licence"
- Des méta informations peuvent y être apporter grâce à du balisage XML. Veuillez vous référer à l'exemple [Delicious.png.licence](Delicious.png.licence).
- Tout ce qui n'est pas balisé, sera déposé tel quel dans la section licence pour le fichier concerné. Veuillez vous référer à l'exemple [Sathisien.png.licence](Sathisien.png.licence).
- Le contenu de la licence doit être réaliste vis à vis de son projet d'insertion dans nos projets (on ne peut pas accepter une licence qui autorise l'utilisation de la skin sur le jeu Slayers Online et non sur le site Slayers Online)

## Règles d'ajout de fichier ".product" :
- Le fichier ".product" doit avoir un contenu de type texte encodé en UTF-8.
- Le fichier pour être accepter doit comporter le même nom que la ressource avec la concaténation de l'extension ".product"
- Des méta informations peuvent y être apporter grâce à du balisage XML. Veuillez vous référer à l'exemple [Shyran.png.product](Shyran.png.product).
- Tout ce qui n'est pas balisé, sera ignoré.

## Informations sur le balisage :
- <Name></Name> Définit le nom de la ressource. Ils figureront dans les fichiers [CREDIT.txt](CREDIT.txt) et [LICENCE.txt](LICENCE.txt).
- <Author></Author> Définit les auteurs de la contribution, vous pouvez utiliser les pseudos ou les noms réels, ils figureront dans les fichiers [CREDIT.txt](CREDIT.txt) et [LICENCE.txt](LICENCE.txt). Le séparateur pour séparer chaque auteur est le caractère ",".
- <Description></Description> Définit une description de la ressource. Il sera visible dans le fichier [LICENCE.txt](LICENCE.txt).
- <CreationDate></CreationDate> Définit la date de la création de la ressource. Il sera visible dans le fichier [LICENCE.txt](LICENCE.txt).
- <Email></Email> Définit un email de contact pour la ressource. Il sera visible dans le fichier [LICENCE.txt](LICENCE.txt).
- <Licence></Licence> Définit le texte de la licence en langue française ou anglaise. Il sera visible dans le fichier [LICENCE.txt](LICENCE.txt).
