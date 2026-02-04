# 🧠 סמינר מדעי המוח א'

סיכום מקיף לסמינר מדעי המוח א' | אוניברסיטת תל אביב | שנה א' סמסטר א'

---

## 📂 מבנה הפרויקט

| תיקייה/קובץ | תיאור |
|-------------|--------|
| `main.tex` | קובץ LaTeX ראשי ליצירת PDF |
| `chapters/` | פרקי הסיכום (LaTeX) |
| `docs/` | אתר התיעוד (MkDocs) – סיכומים במרקאון, תמונות, גלריה |
| `figures/` | תמונות לשימוש ב-PDF |

---

## 📄 בניית ה-PDF

דרושות התקנת [TeX Live](https://www.tug.org/texlive/) (או חבילת LaTeX דומה) ותמיכה ב-XeLaTeX לעברית.

```bash
xelatex main.tex
```

(לעיתים יש להריץ פעמיים כדי לעדכן תוכן עניינים.)

---

## 🌐 אתר התיעוד (MkDocs)

האתר מכיל את אותם סיכומים בפורמט מרקאון, עם ניווט, חיפוש ותמיכה בנוסחאות.

**הרצה מקומית:**

```bash
pip install -r requirements.txt
mkdocs serve
```

לאחר מכן לפתוח בדפדפן: [http://127.0.0.1:8000](http://127.0.0.1:8000)

**בנייה סטטית:**

```bash
mkdocs build
```

הקבצים ייווצרו בתיקייה `site/`.

---

## 🔗 קישורים

- **אתר מפורסם:** [https://orinlevi-neurocspsy.github.io/Seminar_Neuroscience/](https://orinlevi-neurocspsy.github.io/Seminar_Neuroscience/)
- **מאגר:** [GitHub – OrinLevi-NeuroCSpsy/Seminar_Neuroscience](https://github.com/OrinLevi-NeuroCSpsy/Seminar_Neuroscience)

---

## 📚 נושאים בפרויקט

- **פיזיולוגיה:** יונים וגרדיאנטים, נרנסט ו-GHK, פוטנציאל מנוחה ופעולה, הולכה באקסון
- **סינפסות:** רצפטורים, EPSP/IPSP, GABA
- **נוירואנטומיה:** מנחים, חתכי מוח, גזע המוח, צרבלום

---

*נוצר על ידי אורין לוי*
