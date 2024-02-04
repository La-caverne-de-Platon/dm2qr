# dm2qr

## QR Code
- [ ] générer un QR code par devoir
- [ ] redirection vers un lien (id unique attention au bruteforce) pour accéder au corrigé

## QCM
- [ ] nom prénom
- [ ] qr code
- [ ] grille où le candidat coche les cases de ses réponses dans un tableau (y : réponse choisie | x : n° question)
  - [ ] - [ ] [💡] faire en sorte que la grille puisse former un symbole à scanner avec le telephone pour corriger tout seul
- [ ] 1. question \nA....B....
- [ ] mélanger les questions

## CORRIGÉ
- [ ] lire et pause audio corrigé
- [ ] liste de commpétences évaluées, avec étoiles type [check-list](https://lacavernedeplaton.fr/eval/index.php)
- [ ] encadré avec appreciation globale
  - [ ] possibilité de préselectioner des appreciations
- [ ] [💡] vidéo de l'écran du correcteur si devoir numérique
  - [ ] interface correcteur

## DB
- [ ] devoir
  - [ ] qr code
  - [ ] corrigé_wav
  - [ ] corrigé_appreciation
  - [ ] compétences_dm
  - [ ] note
- [ ] compétences_dm
  - [ ] compétence
  - [ ] note
- [ ]  qr code
  - [ ] url
- [ ] qcm
  - [ ] qr code
  - [ ] question
  - [ ] reponse
  - [ ] choix
