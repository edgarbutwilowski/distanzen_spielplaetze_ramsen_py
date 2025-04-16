# Analyse der Spielplatz-Gehdistanzen in Ramsen (Schweiz)

## Lokale Ausführung

Um dieses Jupyter Notebook **lokal** auszuführen, kann eine **Virtuelle Umgebung** in Python verwendet werden.

Hierzu muss die **Viruelle Umgebung** mit den folgenden Befehlen zunächst **angelegt** werden:

Windows:

```bash
python -m venv .venv\
```

Linux:

```bash
python3 -m venv .venv/
```

Anschliessend kann die **Virtuelle Umgebung** mit den folgenden Befehlen **aktiviert** werden:

Windows:

```cmd
.venv\Scripts\activate
```

Linux:

```bash
source .venv/bin/activate
```

Danach werden die **Python-Pakete** in der **Virtuellen Umgebung** installiert:

```bash
pip install requirements.txt
```

Achtung, die Pakete werden auch durch das AUsführen des Notebook installiert (siehe folgendes Kapitel).

## Ausführung in Google Colab

Dieses Jupyter Notebook kann auch in **Google Colab** ausgeführt werden, was einen besonders einfachen Einstieg ermöglicht. Das Notebook kann in Google Colab einfach durch den Aufruf des folgenden Links geöffnet werden:

https://colab.research.google.com/github/edgarbutwilowski/distanzen_spielplaetze_ramsen_py/blob/main/distanzen_spielplaetze_ramsen.ipynb

Da das Notebook diverse externe Python-Pakete verwendet, müssen diese in der Colab-Umgebung installiert werden. Eine Installation über `requirements.txt` funktioniert in Colab jedoch nicht. Daher enthält die erste Zelle des Notebooks direkt Installationsanweisungen für die Python-Pakete. Dadurch werden während des Ausführung des Notebooks gleich zu Beginn die Pakete installiert.
