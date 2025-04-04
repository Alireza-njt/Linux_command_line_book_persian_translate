می‌خواهم برایت داستانی بگویم. نه، نه داستان سال ۱۹۹۱ که لینوس توروالدز اولین نسخه از هسته لینوکس را نوشت. آن داستان را می‌توانی در بسیاری از کتاب‌های لینوکس بخوانی. نه، حتی نمی‌خواهم درباره این بگویم که چگونه چند سال پیش از آن، ریچارد استالمن پروژه گنو (GNU) را برای خلق یک سیستم‌عامل آزاد شبه‌یونیکس آغاز کرد. آن هم داستان مهمی است، اما بیشتر کتاب‌های لینوکس آن را هم روایت کرده‌اند.<br> <br>
نه، می‌خواهم داستانی متفاوت بگویم: داستان پس گرفتن کنترل رایانه‌ات توسط خودت. <br> <br>
وقتی در اواخر دهه ۱۹۷۰ به عنوان یک دانشجو شروع به کار با رایانه‌ها کردم، انقلابی در جریان بود. اختراع ریزپردازنده‌ها این امکان را برای مردم عادی مثل من و تو فراهم کرد که صاحب واقعی یک رایانه باشیم. امروز برای بسیاری تصور دنیایی که در آن فقط شرکت‌های بزرگ و دولت‌ها کنترل تمام رایانه‌ها را در دست داشتند، دشوار است. بگذار اینطور بگویم: در آن زمان کار چندانی از دستت برنمی‌آمد! <br> <br>
اما امروز دنیا بسیار متفاوت است. رایانه‌ها همه‌جا هستند؛ از ساعت‌های مچی کوچک گرفته تا مراکز داده عظیم و هر چیزی بین این دو. علاوه بر رایانه‌های همه‌جا حاضر، شبکه‌ای فراگیر نیز آن‌ها را به هم متصل کرده است. این فناوری عصر جدیدی شگفت‌انگیز از توانمندسازی شخصی و آزادی خلاقانه را خلق کرده، اما در دو دهه اخیر اتفاق دیگری نیز در حال رخ دادن بوده است: چند شرکت غول‌آسا در حال تحمیل کنترل خود بر اکثر رایانه‌های جهان هستند و تصمیم می‌گیرند تو چه کاری می‌توانی با رایانه‌ات انجام دهی و چه کاری نمی‌توانی.<br> <br>
خوشبختانه، مردم سراسر جهان در حال مقابله هستند. آن‌ها با نوشتن نرم‌افزارهای خود در حال جنگ برای حفظ کنترل رایانه‌هایشان هستند. آن‌ها در حال ساختن لینوکس هستند. <br> <br>
بسیاری از مردم از «آزادی» در ارتباط با لینوکس سخن می‌گویند، اما فکر نمی‌کنم اکثر آن‌ها واقعاً بدانند این آزادی به چه معناست. آزادی یعنی قدرت تصمیم‌گیری درباره آنچه رایانه‌ات انجام می‌دهد، و تنها راه داشتن این آزادی این است که بدانی رایانه‌ات چه می‌کند. آزادی یعنی رایانه‌ای بدون راز، رایانه‌ای که هر چیزی در آن قابل کشف است اگر به اندازه کافی کنجکاو باشی. <br> <br>
# چرا از خط فرمان (Command Line) استفاده می کنیم ؟ 
آیا تا به حال در فیلم‌ها توجه کرده‌اید که وقتی "سوپر هکر" - همان کسی که می‌تواند در کمتر از ۳۰ ثانیه به ابررایانه نظامی فوق امنیتی نفوذ کند - پشت کامپیوتر می‌نشیند، هرگز از ماوس استفاده نمی‌کند؟ این به آن دلیل است که فیلمسازان دریافته‌اند ما به عنوان انسان به طور غریزی می‌دانیم که تنها راه واقعی انجام هر کاری روی کامپیوتر، تایپ کردن روی صفحه کلید است! <br> <br>
امروزه اکثر کاربران کامپیوتر فقط با رابط کاربری گرافیکی (GUI) آشنا هستند و توسط فروشندگان و کارشناسان به آنها آموزش داده شده که رابط خط فرمان (CLI) یک چیز ترسناک و متعلق به گذشته است. این موضوع تأسف‌بار است، زیرا یک رابط خط فرمان خوب، روشی شگفت‌انگیز برای ارتباط با کامپیوتر است - درست همانطور که نوشتار برای ارتباط بین انسان‌هاست. گفته می‌شود که "رابط‌های کاربری گرافیکی کارهای ساده را آسان می‌کنند، در حالی که رابط‌های خط فرمان کارهای دشوار را ممکن می‌سازند" - و این گفته تا امروز هم کاملاً صحیح است. <br> <br>
از آنجا که لینوکس بر اساس خانواده سیستم‌عامل‌های یونیکس طراحی شده، همان میراث غنی ابزارهای خط فرمان یونیکس را به اشتراک می‌گذارد. یونیکس در اوایل دهه ۱۹۸۰ (اگرچه اولین بار یک دهه قبل توسعه یافته بود) به شهرت رسید - یعنی قبل از پذیرش گسترده رابط کاربری گرافیکی - و در نتیجه به جای آن، یک رابط خط فرمان گسترده توسعه داد. در واقع، یکی از مهم‌ترین دلایلی که کاربران اولیه لینوکس آن را به جای ویندوز ان‌تی انتخاب می‌کردند، همین رابط خط فرمان قدرتمند بود که "کارهای دشوار را ممکن می‌ساخت".<br> <br>
# این کتاب درباره چیست ؟
این کتاب یک مرور گسترده از "زندگی" در خط فرمان لینوکس ارائه می‌دهد. برخلاف برخی کتاب‌ها که فقط روی یک برنامه خاص مانند bash (پوسته سیستم) تمرکز می‌کنند، این کتاب سعی <br> <br> دارد هنر کار با رابط خط فرمان را به معنای وسیع‌تری آموزش دهد. چگونه کار می‌کند؟ چه کارهایی می‌تواند انجام دهد؟ بهترین روش استفاده از آن چیست؟
این کتاب درباره مدیریت سیستم لینوکس نیست. هرچند هر بحث جدی درباره خط فرمان ناگزیر به موضوعات مدیریت سیستم می‌رسد، اما این کتاب فقط به چند مورد از مسائل مدیریتی اشاره می‌کند. با این حال، با ارائه پایه‌ای محکم در استفاده از خط فرمان - که ابزاری ضروری برای هر کار جدی مدیریت سیستم است - خواننده را برای مطالعه بیشتر آماده می‌کند. <br> <br>
این کتاب کاملاً بر لینوکس متمرکز است. بسیاری از کتاب‌های دیگر سعی می‌کنند با پوشش پلتفرم‌های دیگری مانند یونیکس عمومی و مک‌اواس، مخاطبان بیشتری جذب کنند. آنها با این کار محتوای خود را "رقیق" می‌کنند و فقط به موضوعات عمومی می‌پردازند. اما این کتاب فقط توزیع‌های معاصر لینوکس را پوشش می‌دهد. اگرچه ۹۵ درصد مطالب آن برای کاربران سایر سیستم‌های شبه‌یونیکس مفید است، اما هدف اصلی آن کاربران مدرن خط فرمان لینوکس هستند. <br> <br>
# این کتاب مناسب چه کسانی است؟ 
این کتاب برای کاربران تازه‌وارد لینوکس طراحی شده که از سایر پلتفرم‌ها (مانند ویندوز) به این سیستم‌عامل مهاجرت کرده‌اند. احتمالاً شما یک کاربر حرفه‌ای (Power User) در یکی از نسخه‌های ویندوز هستید. شاید رئیستان از شما خواسته یک سرور لینوکس را مدیریت کنید، یا وارد دنیای هیجان‌انگیز رایانه‌های تک‌برد (SBC) مانند رزبری پای شده‌اید. ممکن است فقط یک کاربر دسکتاپ باشید که از مشکلات امنیتی سیستم‌های قبلی خسته شده‌اید و می‌خواهید لینوکس را امتحان کنید. همه این‌ها دلایل خوبی هستند و شما در اینجا خوشآمدید.<br> <br>
هشدار مهم: مسیر یادگیری سریع وجود ندارد!
آموزش خط فرمان لینوکس چالش‌برانگیز است و به تلاش واقعی نیاز دارد. مشکل سختی آن نیست، بلکه وسعتش است. یک سیستم لینوکس معمولی هزاران برنامه دارد که می‌توانید از طریق خط فرمان از آن‌ها استفاده کنید. پس به خودتان هشدار دهید: یادگیری خط فرمان یک تلاش غیرجدی نیست!<br> <br>
از طرف دیگر، تسلط بر خط فرمان لینوکس بسیار پاداش‌دهنده است. اگر فکر می‌کنید الآن یک «کاربر حرفه‌ای» هستید، صبر کنید تا ببینید قدرت واقعی چیست! برخلاف بسیاری از مهارت‌های کامپیوتری دیگر، دانش خط فرمان ماندگار است. مهارت‌هایی که امروز یاد می‌گیرید، حتی ۱۰ سال بعد هم کاربردی خواهند بود. خط فرمان آزمون زمان را پس داده است.
<br> <br>
نیازی به تجربه برنامه‌نویسی نیست
فرض شده که شما هیچ تجربه برنامه‌نویسی ندارید، اما نگران نباشید! ما شما را در این مسیر هم راهنمایی خواهیم کرد.

# محتوای این کتاب چیست؟

این مطالب با ترتیب و چینشی دقیق و حساب شده ارائه شده‌اند، دقیقاً مانند یک مربی خصوصی که کنار شما نشسته و قدم به قدم راهنمایی‌تان می‌کند. در حالی که بسیاری از نویسندگان این موضوعات را به شیوه‌ای «سیستماتیک» و با پوشش جامع و ترتیبی هر مبحث ارائه می‌دهند - که اگرچه از دیدگاه نویسنده منطقی به نظر می‌رسد - اما می‌تواند برای کاربران تازه‌کار بسیار گیج‌کننده باشد.<br> <br>

یکی دیگر از اهداف این کتاب، آشنا کردن شما با شیوه تفکر یونیکس است که با نحوه تفکر در ویندوز متفاوت است. در طول این مسیر، گاهی به بررسی موضوعات جانبی خواهیم پرداخت تا به شما کمک کنیم درک کنید که چرا برخی امور به شیوه فعلی خود کار می‌کنند و چگونه به این شکل درآمده‌اند. لینوکس صرفاً یک نرم‌افزار نیست؛ بلکه بخش کوچکی از فرهنگ گسترده‌تر یونیکس محسوب می‌شود که دارای زبان و تاریخچه خاص خود است. ممکن است گاهی هم یک یا دو بحث جانبی پرحرارت را به میان بیاورم!<br> <br>

### ساختار کتاب

این کتاب به چهار بخش اصلی تقسیم شده است که هر کدام جنبه‌ای متفاوت از تجربه کار با خط فرمان را پوشش می‌دهند:<br> <br>

<strong>بخش اول: "آموزش پوسته" </strong> <br>
مبانی زبان خط فرمان<br>
ساختار دستورات<br>
پیمایش در سیستم فایل<br>
ویرایش خط فرمان<br>
یافتن راهنما و مستندات دستورات<br>

<strong>بخش دوم: "پیکربندی و محیط"</strong> <br>
ویرایش فایل‌های پیکربندی که کنترل عملکرد کامپیوتر از طریق خط فرمان را ممکن می‌سازند<br>

<strong>بخش سوم: "کارهای متداول و ابزارهای ضروری"</strong> <br>
بسیاری از کارهای معمولی که معمولاً از خط فرمان انجام می‌شوند<br>
برنامه‌های "کلاسیک" خط فرمان در سیستم‌عامل‌های شبه یونیکس مانند لینوکس که برای انجام عملیات قدرتمند روی داده‌ها استفاده می‌شوند<br>

<strong>بخش چهارم: "نوشتن اسکریپت‌های پوسته"</strong> <br>
مقدمه‌ای بر برنامه‌نویسی پوسته<br>
تکنیکی ساده اما کاربردی برای خودکارسازی بسیاری از کارهای رایج کامپیوتری<br>
آشنایی با مفاهیمی که در بسیاری از زبان‌های برنامه‌نویسی دیگر نیز کاربرد دارند<br>

# نحوه مطالعه این کتاب
از ابتدای کتاب شروع کنید و تا انتها به ترتیب پیش بروید. این کتاب به صورت یک مرجع نوشته نشده است، بلکه بیشتر شبیه یک داستان با ساختار مشخصِ آغاز، میانه و پایان است. <br>

### پیش‌نیازها
برای استفاده از این کتاب، تنها چیزی که نیاز دارید یک سیستم لینوکس قابل اجراست. شما می‌توانید این نیاز را به یکی از دو روش زیر برطرف کنید: <br>

##### نصب لینوکس روی یک کامپیوتر (ترجیحاً نه چندان جدید)

انتخاب توزیع خاصی اهمیت چندانی ندارد، اگرچه اکثر کاربران امروزی با اوبونتو، فدورا یا OpenSUSE شروع می‌کنند. در صورت تردید، ابتدا اوبونتو را امتحان کنید.

نصب یک توزیع مدرن لینوکس بسته به سخت‌افزار شما می‌تواند به طرز مسخره‌آسانی ساده یا به طور غیرمنتظره‌ای دشوار باشد.

پیشنهاد می‌کنم از یک کامپیوتر رومیزی چند ساله با حداقل ۲ گیگابایت RAM و ۶ گیگابایت فضای خالی هارددیسک استفاده کنید.

در صورت امکان از لپ‌تاپ‌ها و شبکه‌های بی‌سیم اجتناب کنید، زیرا معمولاً راه‌اندازی آنها مشکل‌تر است.

##### استفاده از "لایو سی‌دی" یا فلش‌درایو USB

یکی از ویژگی‌های جالب بسیاری از توزیع‌های لینوکس، امکان اجرای مستقیم آنها از طریق CD-ROM یا فلش‌درایو USB بدون نیاز به نصب است.

فقط وارد تنظیمات BIOS شوید و سیستم را برای بوت از CD-ROM یا USB تنظیم کنید.

این روش برای تست سازگاری سیستم با لینوکس قبل از نصب اصلی عالی است.

نقطه ضعف آن سرعت پایین‌تر نسبت به نصب روی هارددیسک است.

هر دو توزیع اوبونتو و فدورا (و برخی دیگر) نسخه‌های لایو دارند.

نکته مهم:
صرف نظر از روش نصب، برای انجام تمرینات این کتاب به دسترسی سطح سوپرکاربر (مدیر سیستم) نیاز خواهید داشت. <br>

شیوه مطالعه:
پس از نصب موفق سیستم، همگام با مطالعه کتاب روی کامپیوتر خود تمرین کنید. اکثر مطالب این کتاب "عملی" هستند، بنابراین پشت سیستم بنشینید و شروع به تایپ کردن کنید!<br>



__________________________________________________________________________________________________________________________________________________________________

# چرا از عبارت "گنو/لینوکس" استفاده نمی‌کنم؟

در برخی محافل، مرسوم است که به سیستم عامل لینوکس "گنو/لینوکس" گفته شود. اما مشکل اینجاست که هیچ نام کاملاً صحیحی برای این سیستم عامل وجود ندارد، چرا که محصول کار مشترک هزاران توسعه‌دهنده در یک پروژه گسترده و توزیع‌شده است. از نظر فنی، لینوکس فقط نام هسته سیستم عامل است. هسته اگرچه بسیار حیاتی است و باعث کارکرد سیستم عامل می‌شود، اما به تنهایی یک سیستم عامل کامل محسوب نمی‌شود. <br> <br>

ریچارد استالمن، فیلسوف و نابغه‌ای که جنبش نرم‌افزار آزاد را پایه‌گذاری کرد، اصرار دارد که برای قدردانی از مشارکت‌های پروژه گنو، باید از نام "گنو/لینوکس" استفاده شود. هرچند سهم پروژه گنو بسیار ارزشمند است، اما استفاده از این نام به سایر مشارکت‌کنندگان بی‌عدالتی می‌کند. به نظر من حتی "لینوکس/گنو" از نظر فنی دقیق‌تر است، چرا که ابتدا هسته لینوکس بارگذاری می‌شود و بقیه اجزا بر اساس آن کار می‌کنند. <br> <br>

در کاربرد عمومی، لینوکس به هسته و تمام نرم‌افزارهای آزادی اشاره دارد که در یک توزیع معمولی لینوکس وجود دارند - یعنی کل اکوسیستم لینوکس، نه فقط اجزای گنو. از آنجا که بازار سیستم‌عامل‌ها معمولاً نام‌های تک‌کلمه‌ای (مانند ویندوز یا مک‌اواس) را ترجیح می‌دهد، من هم از همین شیوه رایج پیروی کرده‌ام. البته اگر شما ترجیح می‌دهید از "گنو/لینوکس" استفاده کنید، می‌توانید هنگام مطالعه این کتاب این عبارت را در ذهن خود جایگزین کنید. <br> <br>

___________________________________________________________________________________________________________________________________________________________________

# تازه‌های ویرایش دوم 

در حالی که ساختار و محتوای اصلی کتاب بدون تغییر باقی مانده است، این ویرایش از خط فرمان لینوکس حاوی اصلاحات، شفاف‌سازی‌ها و به‌روزرسانی‌های متعددی است که بسیاری از آن‌ها بر اساس بازخوردهای خوانندگان صورت گرفته‌اند. علاوه بر این، دو بهبود ویژه در این ویرایش به چشم می‌خورد: <br> <br>

اول، کتاب اکنون بر اساس نسخه 4.x از باش (Bash) به‌روزرسانی شده است که در زمان نگارش نسخه اول به طور گسترده استفاده نمی‌شد. این نسخه چهارم از باش، چندین ویژگی جدید و کاربردی را معرفی کرده که در این ویرایش پوشش داده شده‌اند. <br> <br>

دوم، بخش چهارم کتاب با عنوان «اسکریپت‌نویسی پوسته» بازنگری شده تا نمونه‌های بهتری از شیوه‌های صحیح اسکریپت‌نویسی ارائه دهد. اسکریپت‌های این بخش برای افزایش استحکام و قابلیت اطمینان بازنویسی شده‌اند و البته چند باگ هم اصلاح شده‌اند 😉. <br> <br>

# به بازخورد شما نیاز داریم! 

این کتاب نیز مانند بسیاری از پروژه‌های نرم‌افزاری متن‌باز، یک پروژه در حال تکامل است. اگر اشکال فنی یا خطایی مشاهده کردید، می‌توانید از طریق آدرس bshotts@users.sourceforge.net با من تماس بگیرید. لطفاً نسخه دقیق کتابی که مطالعه می‌کنید را ذکر کنید. پیشنهادات و اصلاحات شما ممکن است در نسخه‌های آینده کتاب اعمال شوند. <br> <br>

