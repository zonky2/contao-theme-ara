# contao-theme-ara

Das Ara Theme ist ein Shop-Theme für das Contao CMS, das auf der beliebten Erweiterung [MetaModels](https://now.metamodel.me)
basiert. Es ist dazu gedacht, die Erweiterung [MM Shop](https://github.com/birdsinthesun/mm_shop) näher kennenzulernen.

### Zugang zum Contao-Backend

- Benutzer: Ara
- Passwort: HelloContao

### Ganz einfach und schnell über die Konsole installieren

1. per ssh anmelden
2. zum http-Verzeichnis gehen
3. composer create-project birdsinthesun/contao-theme-ara:1.1.1 website-name
4. die Zeile 1 in der .env aktivieren und die Datenbank-Zugangsdaten eintragen
5. die Zeile 1 der .env in die env.local kopieren
6. zum website-verzeichnis wechseln
7. php bin/console contao:backup:restore
8. die composer.json im Root in einem Editor öffnen
9. die Requirements ergänzen mit dem erworbenen MetaModels Token
10. das Requirement "birdsinthesun/mm_shop":"1.1.7" ergänzen
11. composer install 
12. php vendor/bin/contao-console contao:migrate
13. im Backend einloggen
14. Einstellungen -> Administrator-Mail-Adresse hinzufügen
