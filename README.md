# Laboratoire 9

- Groupe 23
- Nicola Baker, 300360908
- Maxime Malouf, 300238380

## Les étapes nécessaires pour installer et exécuter le projet

Cloner le projet dans le terminal : git clone https://github.com/NicolaBaker/SEG3502Lab9.git 
Ouvrir un terminal PowerShell à la racine du projet SEG3502Lab9.
Démarrer l’application avec la commande : .\gradlew.bat bootRun
Ouvrir un deuxième terminal et tester sans identifiants : curl.exe -i http://localhost:8080/calculator/add/5/3   
Tester avec user1 : curl.exe -i -u user1:pass1 http://localhost:8080/calculator/add/5/3
Tester avec user2 : curl.exe -i -u user2:pass2 http://localhost:8080/calculator/add/5/3 
...
Pour arrêter le serveur, faire Ctrl + C dans le terminal où l’application fonctionne.

