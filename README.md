# dm2qr

## QR Code
- [x] générer un QR code par devoir
- [x] redirection vers un lien (id unique attention au bruteforce) pour accéder au corrigé

## QCM
- [x] nom prénom
- [x] qr code
- [x] grille où le candidat coche les cases de ses réponses dans un tableau (y : réponse choisie | x : n° question)
  - [ ] - [ ] [💡] faire en sorte que la grille puisse former un symbole à scanner avec le telephone pour corriger tout seul
- [x] 1. question \nA....B....
- [ ] mélanger les questions

## CORRIGÉ
- [x] lire et pause audio corrigé
- [x] liste de commpétences évaluées, avec étoiles type [check-list](https://lacavernedeplaton.fr/eval/index.php)
- [x] encadré avec appreciation globale
  - [x] possibilité de préselectioner des appreciations
- [ ] [💡] vidéo de l'écran du correcteur si devoir numérique
  - [ ] interface correcteur

## DB
- [x] devoir
  - [x] qr code
  - [x] corrigé_wav
  - [x] corrigé_appreciation
  - [x] compétences_dm
  - [x] note
- [x] compétences_dm
  - [x] compétence
  - [x] note
- [x]  qr code
  - [x] url
- [x] qcm
  - [x] qr code
  - [x] question
  - [x] reponse
  - [x] choix
