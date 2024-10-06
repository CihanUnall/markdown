
# Markdown Cheatsheet

## Überschriften

Für Überschriften benutze `#`:

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

Ergebnis:

# H1  
## H2  
### H3  
#### H4  
##### H5  
###### H6

---

## Textformatierung

- **Fett**: `**Text**` oder `__Text__`
- *Kursiv*: `*Text*` oder `_Text_`
- ***Fett und Kursiv***: `***Text***` oder `___Text___`
- ~~Durchgestrichen~~: `~~Text~~`

Beispiele:

```markdown
**Fett**
*Kursiv*
***Fett und Kursiv***
~~Durchgestrichen~~
```

---

## Listen

### Ungeordnete Liste

Benutze `*`, `-`, oder `+`:

```markdown
* Ein Element
* Ein weiteres Element
  * Verschachteltes Element
```

Ergebnis:

- Ein Element
- Ein weiteres Element
  - Verschachteltes Element

### Geordnete Liste

Benutze Zahlen gefolgt von einem Punkt:

```markdown
1. Erstes Element
2. Zweites Element
3. Drittes Element
```

Ergebnis:

1. Erstes Element
2. Zweites Element
3. Drittes Element

---

## Links und Bilder

### Links

```markdown
[Link-Text](https://example.com)
```

Ergebnis:  
[Link-Text](https://example.com)

### Bilder

```markdown
![Alt-Text](https://example.com/bild.png)
```

Ergebnis:  
![Alt-Text](https://example.com/bild.png)

---

## Zitate

Zitate werden mit `>` eingeleitet:

```markdown
> Dies ist ein Zitat.
> Mehrzeiliges Zitat.
```

Ergebnis:

> Dies ist ein Zitat.  
> Mehrzeiliges Zitat.

---

## Code

### Inline-Code

Benutze Backticks für Inline-Code:

```markdown
`print("Hallo Welt")`
```

Ergebnis:  
`print("Hallo Welt")`

### Code-Blöcke

Verwende drei Backticks (```):

```markdown
```python
def hallo():
    print("Hallo Welt")
```
```

Ergebnis:

```python
def hallo():
    print("Hallo Welt")
```

---

## Tabellen

Tabellen können so erstellt werden:

```markdown
| Überschrift 1 | Überschrift 2 |
| ------------- | ------------- |
| Zelle 1       | Zelle 2       |
| Zelle 3       | Zelle 4       |
```

Ergebnis:

| Überschrift 1 | Überschrift 2 |
| ------------- | ------------- |
| Zelle 1       | Zelle 2       |
| Zelle 3       | Zelle 4       |

---

## Horizontale Linie

Erzeuge eine horizontale Linie mit `---`, `***` oder `___`:

```markdown
---
```

Ergebnis:

---

---

## Checklisten

Für Checklisten nutze `[ ]` für nicht ausgewählt und `[x]` für ausgewählt:

```markdown
- [ ] Nicht erledigt
- [x] Erledigt
```

Ergebnis:

- [ ] Nicht erledigt
- [x] Erledigt

---

## Links in Fußnoten

```markdown
Das ist ein Beispieltext mit einer Fußnote [^1].

[^1]: Das ist die Fußnote.
```

Ergebnis:

Das ist ein Beispieltext mit einer Fußnote [^1].

[^1]: Das ist die Fußnote.
```

---

## Erweiterte Funktionen (optional)

### HTML-Einbettung

Du kannst HTML direkt in Markdown verwenden:

```markdown
<div style="color: red;">Das ist ein roter Text.</div>
```

Ergebnis:  
<div style="color: red;">Das ist ein roter Text.</div>

---
