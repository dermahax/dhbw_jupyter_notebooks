# DHBW Jupyter Notebooks

Programmieraufgaben zu den Vorlesungen, direkt im Browser ausführbar,
ohne Installation und ohne Registrierung (JupyterLite). Python läuft per Pyodide im Browser,
JavaScript in einem Web Worker des Browsers. Wo es beide Sprachen gibt, wählen Sie eine.

**Start:** https://dermahax.github.io/dhbw_jupyter_notebooks/

| Vorlesung | Aufgabe | Python | JavaScript |
|---|---|---|---|
| Theoretische Informatik 1 | P1 Geburtstage | [Notebook](https://dermahax.github.io/dhbw_jupyter_notebooks/lab/index.html?path=Theoretische_Informatik_1/P1_Geburtstage_Python.ipynb) | [Notebook](https://dermahax.github.io/dhbw_jupyter_notebooks/lab/index.html?path=Theoretische_Informatik_1/P1_Geburtstage_JavaScript.ipynb) |
| Fortgeschrittene Algorithmen | 05 Dijkstra und A\* | [Notebook](https://dermahax.github.io/dhbw_jupyter_notebooks/lab/index.html?path=Fortgeschrittene_Algorithmen/05_Dijkstra_AStar.ipynb) | – |

Interaktive Übungsseiten (kein Notebook, laufen auch auf dem Handy):

| Vorlesung | Übung | Link |
|---|---|---|
| Fortgeschrittene Algorithmen | 10 Spielbäume: Alpha-Beta-Pruning | [Übung](https://dermahax.github.io/dhbw_jupyter_notebooks/files/Fortgeschrittene_Algorithmen/10_Spielbaeume/alphabeta-uebung.html) |

Hinweis: Änderungen werden nur im eigenen Browser gespeichert. Wer seine
Lösung behalten will, lädt das Notebook über *File → Download* herunter.

## Aufbau

- `content/` – die Notebooks (so erscheinen sie auch in JupyterLite)
  - HTML-Seiten in `content/` liegen nach dem Build unter `…/files/<Pfad>` und sind direkt aufrufbar
- `.github/workflows/deploy.yml` – baut bei jedem Push nach `main` die Seite
