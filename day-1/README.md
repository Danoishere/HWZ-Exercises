# Übungen: AI-Plattformen & Tools - Tag 1

Die folgenden zwei kurzen Aufgaben sollen Sie weiter vertraut machen mit verschiedenen Aspekten von Data Cleanup und Preparation.

Für Teil 1 können sie den Spreadsheet Editor ihrer Wahl verwenden (MS Excel, Apple Numbers, Google Sheets, etc.)

> Als Alternative zu Excel und Co. können Sie auch Visual Studio Code verwenden (https://code.visualstudio.com/download). Um CSV-Dateien darzustellen wird empfohlen die "Data Wrangler" Extension zu installieren: https://marketplace.visualstudio.com/items?itemName=ms-toolsai.datawrangler. Gerne helfe ich Ihnen weiter falls Sie diese Option versuchen wollen.

## Teil 1 - Struktur des Dataset

1. Laden Sie die Datei ```Life_Expectancy_Data.csv``` herunter.
Klicken Sie dazu auf die Datei und wähle das Download Symbol *Download Raw Data*
2. Öffnen Sie die Datei in einem Editor deiner Wahl und beantworten Sie die folgenden Fragen unter

> https://forms.gle/G3QgGUzJzu324oam6

3. Fahren Sie mit Teil 2 weiter. Am Ende der Übung besprechen wir zusammen, was Sie herausgefunden haben.


## Teil 2 - Image Classifier

Ziel dieser Übung ist das Trainieren eines einfachen Image Classifiers.
Folgen Sie dazu den folgenden Schritten:

1. Laden sie die ZIP-Datei ```danos_plant_dataset.zip``` herunter.
2. Bei der Datei handelt es sich um einen kleinen Datensatz mit Pflanzen (und einigen Nicht-Pflanzen) mit N = 25.
3. Sortieren sie die Bilder nach "Enthält Pflanze" oder "Enthält keine Pflanze" in zwei verschiedene Ordner.
4. Beantworten Sie die folgenden Fragen:

> https://forms.gle/KJXVxcFWK25EiRgL9

5. Erstellen Sie ein neues *Image Project* auf https://teachablemachine.withgoogle.com/train
6. Laden Sie die annotierten Bilder hoch in die zwei Klassen.
7. Trainieren Sie ein Modell. Sie sollten nun Bilder klassifizieren können.
8. Können Sie den Classifier austricksen (via Webacam oder Fileupload)? Welche Fehler finden sie?
9. Wie könnten Sie diese Fehlerfälle in Ihre Annotations-Pipline behandeln? Machen Sie sich Notizen.



