| **Schritt**                             | **Anweisung**                                                                                                                              |
| --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| 1                                       | Im Ordner der ein lokal repository werden soll folgenden Befehl eingeben: `git init`                                                       |
| 2                                       | Erstelle einen neuen und leeren remote repository auf GitHub                                                                               |
| 3                                       | Kopiere die SSH repository Adresse und verküfe den remote repsoitory mit dem lokalen: `git remote add origin <ssh link>`                   |
| 4                                       | Überprüfe ob der remote repository erfolgreich verknüpft wurde: `git remote -v` (eine "fetch" und "push" Adresse sollten angezeigt werden) |
| **Erfolgreiche Verknüpfung**            |                                                                                                                                            |
| **lokale Order/Datein synchronisieren** |                                                                                                                                            |
| 5                                       | Gebe `git add .` oder `git add <datei>`ein, um deine Änderungen zu stagen                                                                  |
| 6                                       | Gebe `git commit -m "<Nachricht>"`ein, um die Änderungen zu commiten                                                                       |
| 7                                       | Gebe `git push -u origin main` oder `git push`ein, um den neuen commit mit dem remote repository zu synchronisieren                        |
