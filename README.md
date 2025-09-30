# Masterarbeit: Sexismus-Erkennung mit Large Language Models
Masterarbeit im Fach Linguistik zu dem Thema Sexismus-Erkennung mit Large Language Models - Kombination von Transformern mit symbolischen Ansätzen
## Allgemeine Informationen
***
Diese Arbeit befasst sich mit der automatisierten Klassiﬁzierung sexistischer
und misogyner Sprache anhand von Kommentaren eines Online Forums.
Hierfür werden die Leistungen von logistischen Regressions-Modellen
mit denen des Transformer-Modells _DistilBERT Base German Cased_ unter Einﬂuss verschiedener _Fine-Tuning_ Strategien verglichen. 
Der Fokus liegt auf dem Ansatz, eine von verschiedenen KI Modellen generierte Liste an Worten und Phrasen, die häuﬁg im Kontext sexistischer und misogyner Aussagen
vorkommen, als zusätzliche Information zur Klassiﬁzierung hinzuzuziehen.
Das Ziel ist es, durch die Kombination aus Transformer-Modellen und symbolischen Methoden automatisierte Prozesse zur Erkennung sexistischer und misogyner Sprache zu verbessern.

## Hinweis zur Nutzung

Das Notebook "Masterarbeit_MariJebe.ipynb" enthält interaktive Widgets und kann nicht korrekt auf GitHub angezeigt werden.  
Bitte lade die Datei herunter und öffne sie in [Google Colab](https://colab.research.google.com/), damit der Code korrekt angezeigt wird und ausgeführt werden kann. 
Die Dateien _"requirements.txt", wordlist_chatgpt.txt", "wordlist_gemini.txt"_ und _"wordlist_grok.txt"_ sollten für einen reibungslosen Durchlauf des Codes ebenfalls heruntergeladen und in das Colab Dokument eingefügt werden.

## Technologien
***
Eine Liste der im Rahmen des Projekts verwendeten Technologien:

* [spacy](https://spacy.io/)
* [nltk](https://www.nltk.org/)
* [scikit_learn](https://scikit-learn.org/)
* [numpy](https://numpy.org/)
* [pandas](https://pandas.pydata.org/)
* [matplotlib](https://matplotlib.org/)
* [seaborn](https://seaborn.pydata.org/)
* [torch](https://pytorch.org/)
* [tensorflow](https://www.tensorflow.org/)
* [datasets](https://huggingface.co/docs/datasets/index)
* [transformers](https://huggingface.co/docs/transformers/de/index)
* [tqdm](https://tqdm.github.io/)
* [optuna](https://optuna.org/)


## hohe Rechenleistung erforderlich

Einige Aspekte dieses Notebooks benötigen eine hohe Rechenleistung, beispielsweise das Training der Transformer-Modelle. Für eine reibungslose Ausführung empfiehlt es sich daher, eine GPU zu nutzen, da sie die Ausführung des Codes erheblich beschleunigt, sowie den Arbeitsspeicher (RAM) zu erhöhen, um Speicherengpässe bei großen Datensätzen zu vermeiden.

In Google Colab lässt sich unter 

        Bearbeiten → Notebook-Einstellungen → Hardwarebeschleuniger

eine GPU aktivieren und bei Bedarf der RAM erweitern.
