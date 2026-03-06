# FuruAme - 降る雨

**FuruAme** (降る雨) is Japanese for "falling rain":

- **降る** (*furu*) — to fall, used for precipitation (rain, snow, hail)
- **雨** (*ame*) — rain

The name reflects the visual: JLPT vocabulary words fall across the screen like rain.

---

Inspired by an iPad app named *Japanese* that would scroll kanji across the screen like a screensaver — tapping any kanji would open its dictionary entry inside the app. This is a desktop recreation of that experience, built with Python and Tkinter.

JLPT vocabulary words scroll across the screen in a depth-layered rain effect. Clicking any word opens its [Jisho.org](https://jisho.org) dictionary entry in your browser.

## Requirements

- Python 3.13+
- No external dependencies (uses stdlib only)

## Usage

```bash
python furuame.py
```

## Controls

| Key | Level | Description |
|-----|-------|-------------|
| `5` | JLPT N5 | Beginner. ~800 words, basic kanji such as 日, 本, 人 |
| `4` | JLPT N4 | Elementary. ~1,500 words, everyday vocabulary and kanji |
| `3` | JLPT N3 | Intermediate. ~3,750 words, broader kanji and grammar |
| `2` | JLPT N2 | Upper intermediate. ~6,000 words, newspaper-level kanji |
| `1` | JLPT N1 | Advanced. ~10,000 words, complex and literary kanji such as 憂, 鬱 |

Click any word to open its Jisho.org dictionary entry.

## JLPT Levels

The Japanese Language Proficiency Test (JLPT) has five levels, N5 through N1. N5 is the entry level, covering basic vocabulary and kanji used in everyday situations. Each level builds on the last, with N1 representing full professional and literary proficiency. The kanji at N1 include rare and complex characters not commonly seen outside of formal writing.

## Word Lists

Word lists are plain text files with one word per line:

```
JLPT-N5.txt
JLPT-N4.txt
JLPT-N3.txt
JLPT-N2.txt
JLPT-N1.txt
```

Any plain text file with one word or kanji per line is compatible.

## License

MIT — see [LICENSE](LICENSE)
