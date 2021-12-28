# Discord-QR-Scam
תופס אסימון תמונה של Discord

### על אודות
סקריפט Python שיוצר אוטומטית קוד QR הונאה של Nitro ותופס את אסימון הדיסקורד בעת סריקה. כלי זה מדגים כיצד אנשים יכולים לרמות אחרים
לסרוק את קוד ההתחברות של Discord שלהם, ולקבל גישה לחשבון שלהם. שימוש למטרות חינוכיות בלבד.

![img1](https://i.ibb.co/BL2Q0jz/Screenshot-527.png)

## הפגנה
![qr-code](https://user-images.githubusercontent.com/75003671/117522092-fd79ff80-afe3-11eb-938c-23dd68d5927c.gif)

## מידע
הורד את הגרסה העדכנית ביותר של [chromedriver](https://chromedriver.chromium.org/downloads), והחלף את chromedriver.exe הישן בחדש. אם אתה מקבל שגיאות כלשהן, גלול למטה כדי לפתור בעיות כדי ללמוד עוד.

## שימוש
1. אם לא התקנת את Python, הורד את Python 3.7.6
וודא שאתה לוחץ על האפשרות 'הוסף לנתיב' במהלך
ההתקנה.

2. התקן את המודולים הנדרשים > ```pip install -r requirements.txt``` או לחץ פעמיים על `pip_install_requirements.bat`

3. הקלד ```python QR_Generator.py``` ב-cmd כדי להפעיל או לחץ פעמיים על `run_script.bat`

4. המתן ליצירת 'discord_gift.png'. שלח את התמונה לקורבן וגרם לו לסרוק אותה.

5. קוד QR נמשך כ-2 דקות בלבד. ודא שאתה שולח אחד חדש לקורבן והוא מוכן לסריקה.

6. כאשר קוד ה-QR ייסרק, תיכנס אוטומטית לחשבון שלהם והתסריט יתפוס את אסימון הדיסקורד.

## פתרון בעיות
ודא שקובץ chromedriver.exe שלך ??זהה לגרסה הנוכחית של דפדפן האינטרנט Chrome. כדי לבדוק את גרסת Chrome הנוכחית שלך,
הדבק `chrome://settings/help` ב-Google Chrome.

אם Chrome קורס,

1. ודא שקובץ chromedriver.exe שלך ??זהה לגרסה של דפדפן האינטרנט Chrome שלך
2. הורד את הגרסה העדכנית ביותר של chromedriver.exe כאן: https://chromedriver.chromium.org/downloads
3. לאחר מכן החלף את הקובץ chromedriver.exe בתיקייה.
