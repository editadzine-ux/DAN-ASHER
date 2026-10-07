# Dr. Dan Asher — Landing Page (The Tacit Dimension)

עמוד נחיתה באנגלית לד"ר דן אשר: קורסים וייעוץ בניהול ידע ושימור ידע מומחים.
התוכן והמבנה לקוחים מהעמוד המקורי, עם עיצוב חדש, מודל הבצל המונפש והעין מהלוגו.

## מבנה התיקייה

| נתיב | מה זה |
|---|---|
| `index.html` | **העמוד המלא, עצמאי.** HTML + CSS + JavaScript בקובץ אחד, בלי ספריות. פותחים בדפדפן וזה עובד. |
| `assets/` | התמונות: פורטרט, KMWorld 2026, MIKE 2026, והעין מהלוגו (`dan-eye.png`). |
| `design/Main.dc.html` | קובץ המקור של העיצוב מהקנבס של Claude (פורמט Design Component). |
| `design/canvas.json` | אינדקס הקנבס. |
| `ELEMENTOR.md` | איך מעבירים את העמוד לאלמנטור דרך Novamira. |

## מה יש בעמוד (לפי סדר המקור)

1. הדר: לוגו (העין + Dr. Dan Asher / THE TACIT DIMENSION), ניווט, פס התקדמות קריאה
2. הירו: "Expertise goes deeper.", עין מונפשת שעוקבת אחרי העכבר, **מודל הבצל** (בחירת שכבה, Separate, Play, ניגון אוטומטי פעם אחת)
3. היכרות עם דן ופס אמינות
4. When an expert moves on: מסע הידע, Expert knowledge retention, Typical outputs
5. Courses & workshops: ניווט תוכניות דביק ו־6 קורסים נפתחים
6. Our approach: Focus / Extract / Structure / Embed ומחקר מודל הבצל
7. About Dan, מחקר, KMGN, MIKE, KMWorld
8. Assessment & advisory: 4 שירותים
9. Your priorities: טאבים לפי תפקיד
10. FAQ, צור קשר (נושא המייל מתעדכן לפי הקישור שנלחץ), פוטר ומדיניות פרטיות

## הרצה מקומית

פותחים את `index.html` בדפדפן. הפונטים נטענים מ־Google Fonts: Big Shoulders Display, Geist, Instrument Serif, Space Grotesk ו־IBM Plex Mono.

## הגדרות מהירות (בתוך `index.html`)

- **צבע הדגש:** `--amber` על `.da` (ברירת מחדל `#ffb547`)
- **ביטול אנימציות:** להוסיף את המחלקה `still` לצד `da`. משתמשים עם `prefers-reduced-motion` מקבלים את זה אוטומטית.
- **ביטול הניגון האוטומטי של הבצל:** למחוק את הבלוק `auto-play once` בסקריפט.
