# 🎈 بازی تولد: بادکنک‌های پیتزا پارتی

یک بازی مرورگری تک‌فایل (HTML). نیازی به نصب یا بیلد ندارد.

## فایل‌ها
- `index.html`: خود بازی (عکس هم داخل همین فایل جاسازی شده)
- `.nojekyll`: برای اینکه GitHub Pages فایل‌ها را بدون تغییر نمایش بدهد

## آپلود روی GitHub Pages (برای گرفتن لینک)
1. در github.com یک Repository جدید بساز (مثلا با اسم `birthday-game`).
2. دکمه‌ی **Add file ← Upload files** را بزن و فایل‌های همین پوشه (`index.html` و `.nojekyll`، نه خود زیپ) را بکش داخلش و **Commit changes** را بزن.
3. برو به **Settings ← Pages**.
4. در بخش **Build and deployment**، گزینه‌ی Source را روی **Deploy from a branch** بگذار، Branch را `main` و پوشه را `/ (root)` انتخاب کن و **Save** را بزن.
5. بعد از ۱ تا ۲ دقیقه لینک بازی بالای همان صفحه ظاهر می‌شود، به این شکل:
   `https://USERNAME.github.io/birthday-game/`

## شخصی‌سازی
داخل `index.html` بالای بخش script این دو خط را پیدا کن:
- `FRIEND_NAME`: اسم تولدگرفته
- `BIRTHDAY_TEXT`: متن تبریک زیر عکس

همچنین `NUM_BALLS` (تعداد توپ‌ها) و `MAX_LIVES` (تعداد جون‌ها) برای تنظیم سختی بازی.
