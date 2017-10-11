# Liens
  
 Markdown supporte deux types de liens: "incorporé" et "référence".
  
 Dans les deux styles, le lien de texte est délimité par  des crochet [].
  
 Pour créer un "inline", fixe des parenthèses immédiatement après le lien incorporé fermé par des crochets. A l'intérieur des parenthèses, mets le lien où tu veux renvoyé,  accompagné optionnellemnt d'un titre pour le lien, entouré de guillemets. Par example:
  ```markdown
  
 [je suis un lien incorporé](https://www.google.com)
 
 [je suis un lien incorporé avec titre](https://www.google.com "Google's Homepage")
  
 [je suis une référence du fichier de dépot](../blob/master/LICENSE)
  ```
  
 les liens de style reference utilise une seconde fois les crochets, A l'intérieur duquel tu place ton identifiant choisi pour identifier le lien :
  ```markdown
  Ceci est [un exemple][id] reference-style link.
  ```
  
 tu peux aussi utilisé un espace pour séparé les deux paires de crochet:
  ```markdown
 
 C'est [un exemple] [id] de lien de style de reference.
  ```
  
 Puis,n'importe ou dans le document, tu définis l'identifiant de ton lien, sur une seul ligne:
  ```markdown

 [id]: http://example.com/  "Le titre optionnel ici"
  ```
  
 **GitHub** et **GitBook** supportent l'Url automatique. ils vont autoriser les url standard,alors si tu veux relier une URL(au lieu de paramétrer le texte du lien) tu peux simplement entrer l'Url il sera alors transformé en lien vers cette url.
  
  
  ---
  
 Voici un quizz sur les liens markdown.
  
 coche les liens vakide:
   [x] `[a link](http://google.fr)`
   [ ] `(a link)[http://google.fr]`
  
 > le lien texte est délimité par [des crochets].
  
 Quel est l'information correcte à propos de ce lien: ```[a link](http://google.fr "google")```
 - [ ] le lien est https://google.fr
 - [x] le titre du lien est "google"
 - [ ] ca montrera le mot "google"
 - [x] cela montrera le mot "a link"
  
 > Les liens peuvent avoir trois parties: le texte, l'url et un titre.
  
  ---
  
