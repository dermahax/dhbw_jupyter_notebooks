# DHBW Jupyter Notebooks

Programmieraufgaben zu den Vorlesungen, direkt im Browser ausführbar,
ohne Installation und ohne Registrierung (JupyterLite). Jede Aufgabe gibt es
in Python (läuft per Pyodide im Browser) und in JavaScript (läuft in einem
Web Worker des Browsers), Sie wählen eine Sprache.

**Start:** https://dermahax.github.io/dhbw_jupyter_notebooks/

| Vorlesung | Aufgabe | Python | JavaScript |
|---|---|---|---|
| Theoretische Informatik 1 | P1 Geburtstage | [Notebook](https://dermahax.github.io/dhbw_jupyter_notebooks/lab/index.html?path=Theoretische_Informatik_1/P1_Geburtstage_Python.ipynb) | [Notebook](https://dermahax.github.io/dhbw_jupyter_notebooks/lab/index.html?path=Theoretische_Informatik_1/P1_Geburtstage_JavaScript.ipynb) |

Hinweis: Änderungen werden nur im eigenen Browser gespeichert. Wer seine
Lösung behalten will, lädt das Notebook über *File → Download* herunter.

## Aufbau

- `content/` – die Notebooks (so erscheinen sie auch in JupyterLite)
- `.github/workflows/deploy.yml` – baut bei jedem Push nach `main` die Seite
