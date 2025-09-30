# Masterarbeit: Sexismus-Erkennung mit Large Language Models
Masterarbeit im Fach Linguistik zu dem Thema Sexismus-Erkennung mit Large Language Models - Kombination von Transformern mit symbolischen Ansätzen
## Allgemeine Informationen
***
Diese Arbeit befasst sich mit der automatisierten Klassiﬁzierung sexistischer
und misogyner Sprache anhand von Kommentaren eines Online Forums.
Hierfür werden die Leistungen von logistischen Regressions-Modellen
mit denen des Transformer-Modells DistilBERT Base German Cased un-
ter Einﬂuss verschiedener Fine-Tuning Strategien verglichen. Der Fokus liegt auf dem Ansatz, eine von verschiedenen KI Modellen generierte Liste an Worten und Phrasen, die häuﬁg im Kontext sexistischer und misogyner Aussagen
vorkommen, als zusätzliche Information zur Klassiﬁzierung hinzuzuziehen.
Das Ziel ist es, durch die Kombination aus Transformer-Modellen und symbolischen
Methoden automatisierte Prozesse zur Erkennung frauenfeindlicher Sprache zu verbessern.


## Technologien
***
Eine Liste der im Rahmen des Projekts verwendeten Technologien:
* [tweepy](https://www.tweepy.org/): Version 3.2.4 
* [spacy](https://spacy.io/): Version 3.2.4
* [nltk](https://www.nltk.org/): Version 3.4.5
* [scikit_learn](https://scikit-learn.org/): Version 1.1.2
* [numpy](https://numpy.org/): Version 1.18.2
* [pandas](https://pandas.pydata.org/): Version 1.5.0
* [matplotlib](https://matplotlib.org/): Version 3.6.1
* [seaborn](https://seaborn.pydata.org/): Version 0.12.0


## hohe Rechenleistung erforderlich

Einige Aspekte dieses Notebooks benötigen eine hohe Rechenleistung, beispielsweise das Training der Transformer-Modelle. Für eine reibungslose Ausführung empfiehlt es sich daher, eine GPU zu nutzen, da sie die Ausführung des Codes erheblich beschleunigt, sowie den Arbeitsspeicher (RAM) zu erhöhen, um Speicherengpässe bei großen Datensätzen zu vermeiden.

In Google Colab lässt sich unter 

        Bearbeiten → Notebook-Einstellungen → Hardwarebeschleuniger

eine GPU aktivieren und bei Bedarf der RAM erweitern.
