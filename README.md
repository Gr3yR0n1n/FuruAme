# JLPT Rain

Inspired by an iPad app named *Japanese* that would scroll kanji across the screen like a screensaver — tapping any kanji would open its dictionary entry inside the app. This is a desktop recreation of that experience, built with Python and Tkinter.

JLPT vocabulary words scroll across the screen in a depth-layered rain effect. Clicking any word opens its [Jisho.org](https://jisho.org) dictionary entry in your browser.

## Requirements

- Python 3.13+
- No external dependencies (uses stdlib only)

## Usage

```bash
python jlpt_rain.py
```

## Controls

| Key | Level |
|-----|-------|
| `1` | JLPT N5 (easiest) |
| `2` | JLPT N4 |
| `3` | JLPT N3 |
| `4` | JLPT N2 |
| `5` | JLPT N1 (hardest) |

Click any word to open its Jisho.org dictionary entry.

## Word Lists

Word lists are plain text files with one word per line:

```
JLPT-N5.txt
JLPT-N4.txt
JLPT-N3.txt
JLPT-N2.txt
JLPT-N1.txt  ← not included, see below
```

N1 is not included. A copy can be sourced from GitHub repos or sites like Jisho.org that provide JLPT vocabulary lists.
