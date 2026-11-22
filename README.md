# سیستم مدیریت کتابخانه | Library Management System (Student Project)

## فارسی

پروژهٔ دانشجویی آماده: یک سیستم مدیریت کتابخانه کامل در **یک فایل HTML** — بدون نیاز به نصب، بدون سرور و بدون پایگاه‌داده. فقط فایل را در مرورگر باز کنید.

> **نسخهٔ نمایشی (دمو):** فایلی که در این ریپو می‌بینید نسخهٔ دموی برنامه است — می‌توانید کتاب اضافه کنید و یک امانت آزمایشی ثبت کنید تا ببینید به کارتان می‌آید یا نه؛ دانلود CSV در دمو غیرفعال است. نسخهٔ کامل (بدون محدودیت، بدون بنر دمو) فقط بعد از پرداخت ارسال می‌شود.

### امکانات نسخهٔ کامل

- **مدیریت کتاب‌ها:** افزودن، ویرایش و جستجوی کتاب با عنوان، نویسنده، دسته و تعداد نسخه؛ تعداد نسخه‌های در دسترس همیشه مشخص است و کتابی که امانت فعال دارد حذف نمی‌شود
- **مدیریت اعضا:** افزودن عضو با کد عضویت خودکار، شماره تماس و تعداد امانت‌های فعال هر عضو
- **امانت دادن و پس گرفتن:** ثبت امانت با انتخاب عضو و کتاب و تاریخ سررسید (پیش‌فرض ۱۴ روز)، دکمهٔ بازگشت و تمدید ۷ روزه؛ کنترل موجودی نمی‌گذارد کتابی را که نسخه‌ای در دسترس ندارد امانت دهید
- **سررسید گذشته:** فهرست خودکار کتاب‌هایی که سررسیدشان گذشته و پس داده نشده‌اند، با تعداد روزهای تأخیر
- **داشبورد:** تعداد عنوان‌ها و نسخه‌ها، تعداد اعضا، امانت‌های فعال و سررسید گذشته در یک نگاه
- **گزارش‌ها:** پُرامانت‌ترین کتاب‌ها با نمودار میله‌ای و جمع امانت‌ها
- **خروجی CSV:** دانلود گزارش امانت‌ها برای اکسل
- **ذخیره‌سازی:** همهٔ داده‌ها در `localStorage` مرورگر ذخیره می‌شود؛ دکمهٔ «برگرداندن داده‌های نمونه» داده‌ها را ریست می‌کند

### داده‌های نمونه

۸ کتاب، ۴ عضو و ۳ امانت نمونه داخل برنامه هست (یکی سررسید گذشته، یکی فعال و یکی پس داده شده) تا بلافاصله بتوانید آن را امتحان و ارائه کنید. همهٔ نام‌ها فرضی‌اند.

### چطور اجرا کنم؟

1. فایل `index.html` را دانلود کنید
2. با دابل‌کلیک در مرورگر بازش کنید — همین. نیازی به نصب XAMPP یا سرور نیست

### برای ارائهٔ دانشجویی

ساختار کد ساده و خواناست: داده‌ها در `SEED_BOOKS` و `SEED_MEMBERS` و `SEED_LOANS`، توابع `render*` برای نمایش هر بخش، و `localStorage` برای ذخیره‌سازی. برای گزارش پروژه می‌توانید این بخش‌ها را توضیح دهید: مدیریت کتاب و اعضا، چرخهٔ امانت و بازگشت، محاسبهٔ سررسید و تأخیر، و گزارش‌گیری.

### قیمت و خرید

**۵ دلار** — نسخهٔ کامل را از فروشگاه بخرید:

https://digi-market-shop.netlify.app/

1. مبلغ دقیق را با **USDC در شبکهٔ سولانا** به این کیف پول بفرستید: `HqxvhpdWdBvjk1JvCwLdrp3fW47Zt1A8Eg1atDwZ3oQQ`
2. امضای تراکنش و کد محصول (`library-system`) را به **mehdivakili0@gmail.com** ایمیل کنید
3. پرداخت روی بلاک‌چین بررسی می‌شود و نسخهٔ کامل معمولاً تا یک ساعت بعد، خودکار با ایمیل می‌رسد

---

## English

A ready-made student project: a complete library management system in **a single HTML file** — no installation, no server, no database. Just open the file in a browser.

> **Demo version:** the file in this repo is the demo of the app — you can add books and record one trial loan to see if it fits your needs; CSV download is disabled in the demo. The full version (unlimited, no demo banner) is sent only after payment.

### Full version features

- **Book management:** add, edit and search books by title, author, category and copy count; available copies are always shown, and a book with an active loan cannot be deleted
- **Member management:** add members with an automatic membership code, phone number and a count of each member's active loans
- **Lend & return:** record a loan by picking a member and a book with a due date (14 days by default), return button and a 7-day extension; stock control prevents lending a book with no available copies
- **Overdue list:** automatic list of loans past their due date and not yet returned, with days late
- **Dashboard:** titles, copies, members, active loans and overdue count at a glance
- **Reports:** most-borrowed books as a bar chart, plus loan totals
- **CSV export:** download the loans report for Excel
- **Storage:** all data is saved in the browser's `localStorage`; a reset button restores the sample data

### Sample data

8 books, 4 members and 3 sample loans are included (one overdue, one active, one returned) so you can try and present it right away. All names are fictional.

### How to run

1. Download `index.html`
2. Double-click to open it in a browser — that's it. No XAMPP or server needed.

### For a student presentation

The code is simple and readable: data in `SEED_BOOKS`, `SEED_MEMBERS` and `SEED_LOANS`, `render*` functions for each section, and `localStorage` for persistence. For your project report you can explain: book and member management, the lend/return cycle, due-date and late-day calculation, and reporting.

### Price & purchase

**$5** — buy the full version from the store:

https://digi-market-shop.netlify.app/

1. Pay the exact price in **USDC on Solana** to: `HqxvhpdWdBvjk1JvCwLdrp3fW47Zt1A8Eg1atDwZ3oQQ`
2. Email the transaction signature and product code (`library-system`) to **mehdivakili0@gmail.com**
3. The payment is verified on-chain and the full version is emailed to you automatically, usually within an hour

## License

MIT — see [LICENSE](LICENSE).
