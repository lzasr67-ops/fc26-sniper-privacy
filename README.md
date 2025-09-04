<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سياسة الخصوصية - Fc26 Sniper Extension</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.8;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(135deg, #22c55e, #16a34a);
            color: white;
            padding: 40px;
            text-align: center;
        }
        
        .header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 0 2px 4px rgba(0,0,0,0.3);
        }
        
        .header p {
            font-size: 1.2em;
            opacity: 0.9;
        }
        
        .content {
            padding: 40px;
            direction: rtl;
        }
        
        .section {
            margin-bottom: 35px;
            padding: 25px;
            background: #f8f9fa;
            border-radius: 10px;
            border-left: 5px solid #22c55e;
        }
        
        .section h2 {
            color: #22c55e;
            margin-bottom: 15px;
            font-size: 1.4em;
            border-bottom: 2px solid #e9ecef;
            padding-bottom: 10px;
        }
        
        .section p {
            margin-bottom: 15px;
            font-size: 1.1em;
        }
        
        .section ul {
            margin-left: 20px;
            margin-top: 10px;
        }
        
        .section li {
            margin-bottom: 8px;
            font-size: 1.1em;
        }
        
        .contact-info {
            background: linear-gradient(135deg, #22c55e, #16a34a);
            color: white;
            padding: 25px;
            border-radius: 10px;
            text-align: center;
            margin-top: 30px;
        }
        
        .contact-info h3 {
            margin-bottom: 20px;
            font-size: 1.3em;
        }
        
        .contact-links {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }
        
        .contact-link {
            background: rgba(255,255,255,0.2);
            padding: 15px 25px;
            border-radius: 25px;
            text-decoration: none;
            color: white;
            font-weight: bold;
            transition: all 0.3s ease;
        }
        
        .contact-link:hover {
            background: rgba(255,255,255,0.3);
            transform: translateY(-2px);
        }
        
        .footer {
            background: #343a40;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 0.9em;
        }
        
        @media (max-width: 768px) {
            .header h1 {
                font-size: 2em;
            }
            
            .content {
                padding: 20px;
            }
            
            .contact-links {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🔒 سياسة الخصوصية</h1>
            <p>إضافة Fc26 Sniper - Chrome Extension</p>
        </div>
        
        <div class="content">
            <div class="section">
                <h2>📋 معلومات عامة</h2>
                <p>مرحباً بك في سياسة الخصوصية لإضافة Fc26 Sniper. نحن نلتزم بحماية خصوصيتك وبياناتك الشخصية.</p>
                <p>هذه السياسة تصف كيفية عمل الإضافة وما إذا كانت تجمع أو تستخدم أي بيانات شخصية.</p>
            </div>

            <div class="section">
                <h2>📊 البيانات التي نجمعها وكيف نستخدمها</h2>
                <p><strong>لا تجمع الإضافة بيانات شخصية حساسة (مثل الاسم الحقيقي، البريد الإلكتروني، عنوان IP، الموقع الجغرافي، أو سجل التصفح العام).</strong></p>
                <p>تخزّن الإضافة محلياً داخل متصفحك إعداداتك فقط عبر <strong>Chrome Storage</strong> (مثل: اللغة، الفواصل الزمنية للبحث، أسعار البدء والشراء، عدد مرات إعادة الضبط، خيار المزاد/الشراء الفوري، مفاتيح التشغيل/الإيقاف، ومعرّف الدردشة الذي تُدخله اختيارياً للتنبيهات).</p>
                <p>تُستخدم هذه الإعدادات لتشغيل ميزة الأتمتة على صفحة FIFA Ultimate Team فقط، ولا تُستخدم لأي غرض إعلاني أو تحليلي.</p>
            </div>

            <div class="section">
                <h2>🔌 الأذونات ولماذا نحتاجها</h2>
                <ul>
                    <li><strong>activeTab</strong>: لتمكين الإضافة من التفاعل مع علامة التبويب النشطة عندما تكون على موقع <code>ea.com</code> فقط، لتفعيل/إيقاف الأتمتة. لا نقرأ محتوى الصفحات خارج نطاق الاستخدام الوظيفي، ولا نُرسله خارج جهازك.</li>
                    <li><strong>storage</strong>: لحفظ إعداداتك محلياً في المتصفح.</li>
                    <li><strong>host permissions</strong> على <code>https://www.ea.com/*</code>: لتنفيذ الأتمتة محلياً على صفحة الويب المستهدفة فقط.</li>
                </ul>
            </div>

            <div class="section">
                <h2>🎯 كيفية عمل الإضافة</h2>
                <p>تعمل الإضافة محلياً على جهازك من خلال:</p>
                <ul>
                    <li>قراءة عناصر الصفحة الخاصة بـ FIFA Ultimate Team بهدف الأتمتة (مثل ملء الحقول/النقر)، دون حفظ أو إرسال محتوى الصفحة خارج جهازك.</li>
                    <li>استخدام الإعدادات التي حفظتها لتحديد سلوك الأتمتة.</li>
                    <li>إرسال تنبيه اختياري إذا فعّلت ميزة التنبيهات.</li>
                </ul>
            </div>

            <div class="section">
                <h2>🤝 مشاركة البيانات مع أطراف ثالثة</h2>
                <ul>
                    <li><strong>Telegram/WhatsApp (اختياري)</strong>: إذا أدخلت معرّف الدردشة لتلقي تنبيهات، قد تُرسل الإضافة رسالة نصية تحتوي على إشعار بالصفقة (دون بيانات شخصية) إلى قناة التنبيه التي اخترتها. يمكنك إيقاف ذلك في أي وقت بحذف المعرّف من الإعدادات.</li>
                    <li><strong>التحقق من الترخيص</strong>: قد تتواصل الإضافة مع موقع <code>eafcsniper.com</code> للتحقق من حالة الترخيص باستخدام رمز مصادقة. لا تُرسل الإضافة بيانات شخصية ضمن هذا الطلب.</li>
                    <li><strong>قائمة الحسابات</strong>: قد تقوم الواجهة بتحميل قائمة حسابات مُصرّح بها من مصدر عام على GitHub لأغراض التحقق المحلي. لا تُرسل بيانات اعتمادك إلينا؛ يتم التحقق محلياً على جهازك.</li>
                </ul>
            </div>

            <div class="section">
                <h2>🔒 الأمان والاحتفاظ بالبيانات</h2>
                <ul>
                    <li>تُخزَّن الإعدادات محلياً في متصفحك ويمكنك حذفها من خلال مسح بيانات المتصفح أو إزالة الإضافة.</li>
                    <li>لا نحتفظ بأي نسخ من بياناتك على خوادمنا.</li>
                    <li>يقتصر إرسال الشبكة على التحقق من الترخيص والرسائل الاختيارية للتنبيه كما هو موضح أعلاه.</li>
                </ul>
            </div>

            <div class="section">
                <h2>📱 الإشعارات والتحكم</h2>
                <ul>
                    <li>يمكنك تشغيل/إيقاف الأتمتة أو التنبيهات في أي وقت من واجهة الإضافة.</li>
                    <li>يمكنك حذف أي معرّفات للتنبيه قمت بإدخالها (مثل معرّف الدردشة) لإيقاف الإرسال الخارجي.</li>
                    <li>يمكنك إزالة الإضافة أو مسح بيانات المتصفح لحذف جميع الإعدادات المخزّنة محلياً.</li>
                </ul>
            </div>

            <div class="section">
                <h2>🌐 ملفات تعريف الارتباط (Cookies)</h2>
                <p>الإضافة لا تستخدم ملفات تعريف الارتباط ولا تضع أي تتبع على المواقع التي تزورها.</p>
            </div>

            <div class="section">
                <h2>📅 تحديثات السياسة</h2>
                <p>قد نقوم بتحديث هذه السياسة من وقت لآخر لتحسين حماية خصوصيتك.</p>
                <p>سيتم إشعارك بأي تغييرات جوهرية من خلال تحديث الإضافة.</p>
            </div>

            <div class="contact-info">
                <h3>📞 التواصل معنا</h3>
                <p>لأي استفسارات حول هذه السياسة أو الإضافة، يمكنك التواصل معنا عبر:</p>
                <div class="contact-links">
                    <a href="https://wa.me/0544664548" class="contact-link">📱 الواتساب: 0544664548</a>
                    <a href="https://instagram.com/fc.sniper1" class="contact-link">📸 الإنستغرام: fc.sniper1</a>
                    <a href="https://tiktok.com/@fc.sniper1" class="contact-link">🎵 التيك توك: fc.sniper1</a>
                </div>
            </div>
        </div>
        
        <div class="footer">
            <p>© 2024 Fc26 Sniper Extension. جميع الحقوق محفوظة.</p>
            <p>آخر تحديث: سبتمبر 2025</p>
        </div>
    </div>
</body>
</html>
