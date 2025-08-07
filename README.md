# html.html
html
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مفاهیم HTML و CSS</title>
    <!-- Tailwind CSS CDN for easy styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts for 'Inter' -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://github.com/godofwarfinalsaga-1140/css10.css/blob/c230e98b5526049aa496046bd50491d0d9c93ccf/Css.css">

</head>
<body class="text-gray-800">

    <!-- Header Section -->
    <header class="bg-indigo-700 text-white p-4 shadow-lg sticky top-0 z-50">
        <div class="container mx-auto flex justify-center items-center">
            <h1 class="text-3xl font-bold rounded-lg p-2 bg-indigo-600">مفاهیم HTML و CSS</h1>
        </div>
    </header>

    <!-- Main Content Section -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold text-center mb-12 section-heading mx-auto">مفاهیم کلیدی HTML و CSS</h2>
            <p class="text-xl text-center max-w-3xl mx-auto mb-12 leading-relaxed">
                در این صفحه می‌توانید خلاصه‌ای از مهم‌ترین مفاهیم HTML و CSS را که برای ساخت صفحات وب ضروری هستند، مشاهده کنید.
            </p>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

                <!-- Concept Card: DOCTYPE -->
                <div class="concept-card">
                    <div class="concept-name">&lt;!DOCTYPE html&gt;</div>
                    <p class="concept-description">
                        این اعلامیه به مرورگر می‌گوید که سند یک صفحه <strong>HTML5</strong> است.
                    </p>
                </div>

                <!-- Concept Card: html -->
                <div class="concept-card">
                    <div class="concept-name">&lt;html&gt;</div>
                    <p class="concept-description">
                        <strong>عنصر ریشه</strong> سند HTML است که تمام محتوای صفحه را در بر می‌گیرد.
                    </p>
                </div>

                <!-- Concept Card: html lang dir -->
                <div class="concept-card">
                    <div class="concept-name">&lt;html lang="fa" dir="rtl"&gt;</div>
                    <p class="concept-description">
                        ویژگی <code>lang="fa"</code> زبان صفحه را <strong>فارسی</strong> و <code>dir="rtl"</code> جهت نوشتار را <strong>راست به چپ</strong> تنظیم می‌کند.
                    </p>
                </div>

                <!-- Concept Card: head -->
                <div class="concept-card">
                    <div class="concept-name">&lt;head&gt;</div>
                    <p class="concept-description">
                        این تگ شامل <strong>فراداده (Metadata)</strong> صفحه است که مستقیماً در مرورگر نمایش داده نمی‌شود، مانند عنوان صفحه و لینک به فایل‌های CSS.
                    </p>
                </div>

                <!-- Concept Card: title -->
                <div class="concept-card">
                    <div class="concept-name">&lt;title&gt;</div>
                    <p class="concept-description">
                        عنوان صفحه را تعیین می‌کند که در نوار عنوان یا تب مرورگر نمایش داده می‌شود.
                    </p>
                </div>

                <!-- Concept Card: meta charset -->
                <div class="concept-card">
                    <div class="concept-name">&lt;meta charset="UTF-8"&gt;</div>
                    <p class="concept-description">
                        مجموعه کاراکتری <strong>UTF-8</strong> را برای نمایش صحیح متن‌ها (شامل فارسی) به مرورگر اعلام می‌کند.
                    </p>
                </div>

                <!-- Concept Card: meta viewport -->
                <div class="concept-card">
                    <div class="concept-name">&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</div>
                    <p class="concept-description">
                        برای <strong>طراحی واکنش‌گرا (Responsive Design)</strong> ضروری است و نحوه نمایش صفحه را در دستگاه‌های مختلف تنظیم می‌کند.
                    </p>
                </div>

                <!-- Concept Card: body -->
                <div class="concept-card">
                    <div class="concept-name">&lt;body&gt;</div>
                    <p class="concept-description">
                        <strong>بخش اصلی و قابل مشاهده</strong> صفحه وب است که تمام محتوای بصری و تعاملی کاربر در آن قرار می‌گیرد.
                    </p>
                </div>

                <!-- Concept Card: h1-h6 -->
                <div class="concept-card">
                    <div class="concept-name">&lt;h1&gt; تا &lt;h6&gt;</div>
                    <p class="concept-description">
                        برای تعریف <strong>تیترها و عناوین</strong> با سطوح اهمیت مختلف (از <code>&lt;h1&gt;</code> مهم‌ترین تا <code>&lt;h6&gt;</code> کم‌اهمیت‌ترین) استفاده می‌شوند.
                    </p>
                </div>

                <!-- Concept Card: p -->
                <div class="concept-card">
                    <div class="concept-name">&lt;p&gt;</div>
                    <p class="concept-description">
                        برای تعریف یک <strong>پاراگراف متن</strong> در HTML استفاده می‌شود.
                    </p>
                </div>

                <!-- Concept Card: a (Anchor Tag) -->
                <div class="concept-card">
                    <div class="concept-name">&lt;a&gt; (Anchor Tag)</div>
                    <p class="concept-description">
                        این تگ برای ایجاد <strong>لینک (Hyperlink)</strong> استفاده می‌شود. ویژگی <code>href</code> در این تگ، آدرس مقصد لینک را مشخص می‌کند.
                    </p>
                </div>

                <!-- Concept Card: img (Image Tag) -->
                <div class="concept-card">
                    <div class="concept-name">&lt;img&gt; (Image Tag)</div>
                    <p class="concept-description">
                        برای <strong>نمایش تصاویر</strong> در صفحه وب استفاده می‌شود. ویژگی <code>src</code> آدرس فایل تصویر و <code>alt</code> متن جایگزین را مشخص می‌کند.
                    </p>
                </div>

                <!-- Concept Card: div -->
                <div class="concept-card">
                    <div class="concept-name">&lt;div&gt;</div>
                    <p class="concept-description">
                        یک <strong>تگ کانتینر عمومی بلوکی</strong> است که برای گروه‌بندی عناصر HTML برای استایل‌دهی یا دستکاری استفاده می‌شود.
                    </p>
                </div>

                <!-- Concept Card: span -->
                <div class="concept-card">
                    <div class="concept-name">&lt;span&gt;</div>
                    <p class="concept-description">
                        یک <strong>تگ کانتینر عمومی درون‌خطی</strong> است که برای گروه‌بندی بخش‌های کوچک‌تر متن یا عناصر درون‌خطی برای استایل‌دهی استفاده می‌شود.
                    </p>
                </div>

                <!-- Concept Card: id attribute -->
                <div class="concept-card">
                    <div class="concept-name">id (ویژگی)</div>
                    <p class="concept-description">
                        یک <strong>شناسه یکتا</strong> برای یک عنصر HTML در کل سند است که برای هدف قرار دادن عناصر خاص با CSS یا جاوااسکریپت کاربرد دارد.
                    </p>
                </div>

                <!-- Concept Card: class attribute -->
                <div class="concept-card">
                    <div class="concept-name">class (ویژگی)</div>
                    <p class="concept-description">
                        یک یا چند <strong>نام کلاس</strong> را برای یک عنصر HTML مشخص می‌کند. برای اعمال استایل‌های CSS مشترک یا دستکاری گروهی عناصر استفاده می‌شود.
                    </p>
                </div>

                <!-- Concept Card: HTML Comments -->
                <div class="concept-card">
                    <div class="concept-name">&lt;!-- ... --&gt;</div>
                    <p class="concept-description">
                        برای افزودن <strong>نظرات و توضیحات</strong> در کد HTML استفاده می‌شود که در مرورگر نمایش داده نمی‌شوند و به خوانایی کد کمک می‌کنند.
                    </p>
                </div>

                <!-- Concept Card: ol (Ordered List) -->
                <div class="concept-card">
                    <div class="concept-name">&lt;ol&gt; (Ordered List)</div>
                    <p class="concept-description">
                        برای ایجاد <strong>لیست‌های مرتب</strong> استفاده می‌شود که آیتم‌های آن با اعداد، حروف یا رومی مشخص می‌شوند. هر آیتم باید داخل تگ <code>&lt;li&gt;</code> قرار بگیرد.
                    </p>
                </div>

                <!-- Concept Card: main -->
                <div class="concept-card">
                    <div class="concept-name">&lt;main&gt;</div>
                    <p class="concept-description">
                        یک <strong>تگ معنایی</strong> است که <strong>محتوای اصلی و منحصر به فرد</strong> صفحه را در بر می‌گیرد و نباید در سایر صفحات تکرار شود.
                    </p>
                </div>

                <!-- Concept Card: article -->
                <div class="concept-card">
                    <div class="concept-name">&lt;article&gt;</div>
                    <p class="concept-description">
                        یک <strong>تگ معنایی</strong> است که یک <strong>محتوای مستقل و خودکفا</strong> (مانند یک پست وبلاگ یا خبر) را نشان می‌دهد.
                    </p>
                </div>

                <!-- Concept Card: aside -->
                <div class="concept-card">
                    <div class="concept-name">&lt;aside&gt;</div>
                    <p class="concept-description">
                        یک <strong>تگ معنایی</strong> است که محتوایی را نشان می‌دهد که **مرتبط با محتوای اصلی صفحه است اما از نظر معنایی کمی جداگانه** (مانند نوار کناری یا نقل‌قول).
                    </p>
                </div>

                <!-- Concept Card: { (Curly Brace) -->
                <div class="concept-card">
                    <div class="concept-name">{ (کلید آکولاد باز)</div>
                    <p class="concept-description">
                        در <strong>CSS</strong>، نشان‌دهنده <strong>شروع یک بلوک قانون (Rule Block)</strong> یا **مجموعه قواعد (Rule Set)** است. تمام استایل‌های مربوط به یک سلکتور در داخل این آکولادها قرار می‌گیرند.
                    </p>
                </div>

                <!-- Concept Card: background-color -->
                <div class="concept-card">
                    <div class="concept-name">background-color (در CSS)</div>
                    <p class="concept-description">
                        ویژگی CSS برای <strong>تعیین رنگ پس‌زمینه</strong> یک عنصر است. می‌توانید از نام رنگ‌ها، کدهای هگزادسیمال (مانند <code>#FF0000</code>) یا مقادیر RGB استفاده کنید.
                    </p>
                </div>

                <!-- Concept Card: width -->
                <div class="concept-card">
                    <div class="concept-name">width (در CSS)</div>
                    <p class="concept-description">
                        ویژگی CSS برای <strong>تعیین عرض</strong> یک عنصر است. مقادیر می‌توانند بر حسب پیکسل (<code>px</code>)، درصد (<code>%</code>)، یا واحدهای دیگر باشند.
                    </p>
                </div>

                <!-- Concept Card: height -->
                <div class="concept-card">
                    <div class="concept-name">height (در CSS)</div>
                    <p class="concept-description">
                        ویژگی CSS برای <strong>تعیین ارتفاع</strong> یک عنصر است. مقادیر می‌توانند بر حسب پیکسل (<code>px</code>)، درصد (<code>%</code>)، یا واحدهای دیگر باشند.
                    </p>
                </div>

                <!-- Concept Card: style (HTML Attribute) -->
                <div class="concept-card">
                    <div class="concept-name">style (ویژگی HTML)</div>
                    <p class="concept-description">
                        یک **ویژگی HTML** برای اعمال **استایل‌های CSS درون‌خطی (Inline Styles)** به یک عنصر خاص. این روش برای استایل‌های موقت یا بسیار خاص استفاده می‌شود.
                        <br>مثال: <code>&lt;p style="color: blue; font-size: 16px;"&gt;متن آبی&lt;/p&gt;</code>
                    </p>
                </div>

                <!-- Concept Card: color (CSS Property) -->
                <div class="concept-card">
                    <div class="concept-name">color (در CSS)</div>
                    <p class="concept-description">
                        ویژگی CSS برای <strong>تعیین رنگ متن</strong> یک عنصر است.
                        <br>مثال: <code>p { color: red; }</code>
                    </p>
                </div>

                <!-- Concept Card: stylesheet (in rel="...") -->
                <div class="concept-card">
                    <div class="concept-name">"stylesheet" (در rel="...")</div>
                    <p class="concept-description">
                        مقدار رایج برای ویژگی <code>rel</code> در تگ <code>&lt;link&gt;</code> است که نشان می‌دهد منبع خارجی یک **فایل CSS** حاوی استایل‌ها برای صفحه است.
                        <br>مثال: <code>&lt;link rel="stylesheet" href="style.css"&gt;</code>
                    </p>
                </div>

            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-gray-800 text-white py-8 text-center rounded-t-3xl shadow-inner mt-16">
        <div class="container mx-auto px-6">
            <p class="mb-4 text-lg">&copy; 2025 مفاهیم HTML و CSS. تمامی حقوق محفوظ است.</p>
        </div>
    </footer>

</body>
</html>
