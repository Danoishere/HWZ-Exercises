# Übungen: AI-Plattformen & Tools - Tag 2
## Ausgangslage

Ziel dieser Übung ist, dass Sie sich mit dem Pricing-Modell und den gängigsten Begriffen moderner Cloud-Anbieter vertraut machen. 

Sie arbeiten in einem Startup, welches eine Machine Learning Pipeline aufbauen will. Sie haben sich entschlossen, Microsoft Azure zu verwenden. Azure ermöglicht es, Computer zu mieten und innert weniger Sekunden zu verwenden.

Mit dem Engineering Team sind folgende Anforderungen definiert worden:

Server 1: 
- CPU server für Data Cleanup und Processing
- Betriebssystem: Ubuntu Linux
- Mindestens 4 Prozessorkerne
- Mindestens 4 GB Arbeitsspeicher

Server 2:
- GPU server für das Training neuronaler Netzwerke
- Betriebssystem: Ubuntu Linux
- Mindestens 8 Prozessorkerne
- Mindestens 64 GB Arbeitsspeicher
- GPU mit mindestens 48 GB GPU Memory

Beide Server sollten nahe zur oder in der Schweiz stationiert sein. Hilfe zu den Verschiedenen Server Typen (instance types) finden Sie unter [diesem Link](https://learn.microsoft.com/de-de/azure/virtual-machines/sizes/overview?tabs=breakdownseries%2Cgeneralsizelist%2Ccomputesizelist%2Cmemorysizelist%2Cstoragesizelist%2Cgpusizelist%2Cfpgasizelist%2Chpcsizelist).

## Auftrag

1. Gehen sie auf den Azure Pricing Calculator: https://azure.microsoft.com/en-us/pricing/calculator/
2. Ihr Ziel ist es nun, ein passendes Angebot zu finden, welches die definierten Anforderungen erfüllt.

Auf dem Cost Calculator finden Sie verschiedene Maschinen in der Sektion "Virtual Machines"-
Machen Sie für beide Server ein Screenshot mit dem günstigsten Angebot, welches Sie finden. Kopieren Sie den Screenshot ins folgende Google Forms hoch:

https://forms.gle/oaEurmoQC9Q9417z7

Geben Sie folgende Informationen an in Textform

- Die Instanz Typen, für welche Sie sich entschieden haben für die beiden Server
- Preis pro Monat

3. Ihr Team entwickelt sich weiter, und braucht noch mehr Rechenpower. Leider ist die aktuelle Generation von GPUs limitiert auf ca. 80 GB GPU Memory. Recherchieren Sie: Welche Möglichkeiten gibt es, diese Beschränkungen zu umgehen? Finden Sie eine passende Azure Instanz, dass Sie Modelle mit einer Grösse von mind. 100 GB trainieren könnnen.

Im obigen Google Forms Formular:

- Machen Sie einen Screenshot und fügen Sie auch diesen ein
- Beschreiben Sie Ihre Lösung, die Sie recherchiert haben
- Geben Sie auch hier den Preis pro Monat an.

Anschliessend besprechen wir die Aufgabe.


