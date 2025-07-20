# Aufgaben zu dem Code Uebung2.py

## Allgemeine Hinweise

- Bearbeiten Sie die Aufgaben stets **in Ihrer Gruppe**.
- Arbeiten Sie zu **zweit** (1–3 Personen, idealerweise 2).
- Wenn mehrere Teams innerhalb einer Gruppe existieren, dann:
  - Kopieren Sie die Dateien entsprechend.
  - Benennen Sie diese um, z. B.: `Uebung2-TeamA.py`, `Antworten-TeamB.md`, etc.

---

## Aufgabenstellung

1. Welche Funktionen erfüllt der vorliegende Code?

2. Welche Aspekte des Codes sind aus Sicht der Softwarequalität positiv bzw. negativ zu bewerten?

3. Verbessern Sie den Code gezielt.  
   Jeder Veränderungsschritt soll in einem eigenen **Commit mit einer passenden Commit-Message** dokumentiert werden, z. B.:
   - `Kommentare hinzugefügt`
   - `Methodennamen verbessert`
   - `Fehlende Rückgabewerte ergänzt`

   **Falls mehrere Teams in der Gruppe arbeiten:**
   - Führen Sie gegenseitig ein kurzes **Code Review (5 Minuten)** durch.
   - Tauschen Sie sich danach in **5 Minuten über die Änderungen** aus (z. B. „Wer hat was und warum geändert?“).

4. *(Optional)* Führen Sie eine automatisierte Code-Qualitätsanalyse mit *Pylint* durch und dokumentieren Sie die wichtigsten Ergebnisse.  
   - Ziel: Bewertung und Verbesserung der Codequalität.
   - Liste der möglichen Pylint-Codes zur Interpretation der Ergebnisse:  
     👉 [Pylint Message Codes – offizielle Doku](https://pylint.readthedocs.io/en/stable/user_guide/messages/)

---

## Anleitung zu Aufgabe 4 (Optional – Pylint)

1. Öffnen Sie das Terminal in Ihrem Codespace und geben Sie ein:  
   `pip install pylint`

2. Navigieren Sie zum richtigen Ordner mit der Python-Datei:  
   `cd "Aufgaben/Uebungsblatt2"`

3. Führen Sie Pylint aus:  
   `python -m pylint Uebung2.py`

🛠️ **Hinweis zur Umsetzung von Aufgabe 4:**  
Nach jedem Testschritt sowie nach jeder einzelnen Implementierungsänderung soll ein **separater Commit** gemacht werden.  
Die Commit-Messages sollten den jeweiligen Schritt möglichst präzise beschreiben (z. B. `Test für Funktion xyz hinzugefügt`, `Fehlerbehandlung ergänzt`, ...).

---

**Pylint zeigt Ihnen:**

- **Score**: Bewertung von 0–10 (10 = perfekt)
- **Kategorien**:
  - C = Convention
  - R = Refactor
  - W = Warning
  - E = Error
  - F = Fatal
- **Zeilennummern** der betroffenen Stellen

**Notieren Sie (optional):**

- Den Pylint-Score: ___ / 10
- Die 3 häufigsten Problemtypen
