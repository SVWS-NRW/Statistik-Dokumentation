# Markdown - Übersicht

Eine Übersicht der wichtigsten Markdown-Syntax-Elemente für die tägliche Arbeit.

---

## 1. Überschriften
Überschriften werden mit Rauten (`#`) erzeugt. Je mehr Rauten, desto kleiner die Überschrift. Nach den Rauten muss ein Leerzeichen folgen.

```markdown
# Überschrift 1 (Haupttitel)
## Überschrift 2 (Sektion)
### Überschrift 3 (Untersektion)
#### Überschrift 4
```

---

## 2. Textformatierung
Für Formatierungen werden Sternchen (`*`) oder Unterstriche (`_`) direkt um den Text herum platziert.

```markdown
**Dieser Text ist fett**
_Dieser Text ist kursiv_ (oder: *kursiv*)
***Dieser Text ist fett und kursiv***
~~Dieser Text ist durchgestrichen~~
```

---

## 3. Aufzählungen & Listen
Listen helfen dabei, Inhalte strukturiert darzustellen. Nach dem Symbol muss ein Leerzeichen stehen.

### Unsortierte Liste (Bullet Points)
```markdown
- Erster Punkt
- Zweiter Punkt
  - Unterpunkt (mit zwei Leerzeichen eingerückt)
```

oder 
+ Punkt 1

### Sortierte Liste (Nummeriert)
```markdown
1. Erster Schritt
2. Zweiter Schritt
3. Dritter Schritt
```

---

## 4. Verlinkungen (Links)
Der sichtbare Text steht in eckigen Klammern `[]`, die Ziel-URL folgt direkt danach in runden Klammern `()`.

```markdown
[Besuche die offizielle GitHub-Seite](https://github.com)
```

---

## 5. Bilder einfügen
Funktioniert genau wie ein Link, benötigt aber ein führendes Ausrufezeichen (`!`). In den eckigen Klammern steht der Alternativtext für Screenreader oder falls das Bild nicht lädt.

```markdown
![Logo von Markdown](https://markdown-here.com/img/icon256.png)
```

---

## 🛠️ Bonus: Praktische Zusatz-Elemente

### Zitate (Blockquotes)
Nützlich, um Texte hervorzuheben oder zu zitieren. Wird mit einem Größer-als-Zeichen (`>`) erzeugt.

```markdown
> "Der beste Weg, die Zukunft vorherzusagen, ist, sie zu erschaffen." - Peter Drucker
```

### Tabellen
Spalten werden durch vertikale Striche (`|`) getrennt. Die zweite Zeile definiert die Ausrichtung mit Bindestrichen (`-`).

```markdown
| Rolle | Beschreibung |
| :--- | :--- |
| **Write** | Darf Inhalte bearbeiten und einreichen. |
| **Maintain** | Verwaltet und prüft das gesamte Projekt. |
```
