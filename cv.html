<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>منشئ السيرة الذاتية الاحترافي</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>
    <style>
        :root {
            --primary-color: #3498db;
            --secondary-color: #2c3e50;
            --accent-color: #e74c3c;
            --success-color: #27ae60;
            --warning-color: #f39c12;
            --text-color: #333;
            --light-bg: #f5f5f5;
            --white: #ffffff;
            --gray: #7f8c8d;
            --light-gray: #ecf0f1;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--light-bg);
            direction: rtl;
        }

        body[dir="ltr"] {
            direction: ltr;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* الشريط العلوي */
        nav {
            background: var(--secondary-color);
            color: var(--white);
            padding: 1rem 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        nav .logo h1 {
            color: var(--primary-color);
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 2rem;
        }

        .nav-links a {
            color: var(--white);
            text-decoration: none;
            transition: all 0.3s;
            padding: 5px 10px;
            border-radius: 3px;
        }

        .nav-links a:hover {
            background-color: var(--primary-color);
        }

        /* قسم الرئيسية */
        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: var(--white);
            padding: 100px 0;
            text-align: center;
        }

        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .cta-button {
            background: var(--accent-color);
            color: var(--white);
            border: none;
            padding: 15px 30px;
            font-size: 1.1rem;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s;
        }

        .cta-button:hover {
            background: #c0392b;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        /* قسم القوالب */
        .templates-section {
            padding: 50px 0;
            background-color: var(--white);
        }

        .templates-section h2 {
            text-align: center;
            margin-bottom: 30px;
            color: var(--secondary-color);
            font-size: 2rem;
        }

        .template-selector {
            display: flex;
            gap: 20px;
            margin-bottom: 30px;
            justify-content: center;
            flex-wrap: wrap;
        }

        .template-option {
            border: 2px solid #ddd;
            padding: 15px;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s;
            width: 200px;
            text-align: center;
        }

        .template-option:hover, .template-option.active {
            border-color: var(--primary-color);
            background-color: #f0f8ff;
            transform: translateY(-5px);
        }

        .template-preview {
            width: 100%;
            height: 250px;
            margin-bottom: 10px;
            border-radius: 3px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--white);
            font-weight: bold;
            font-size: 1.2rem;
        }

        .modern-preview {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
        }

        .professional-preview {
            background: linear-gradient(135deg, var(--secondary-color), #34495e);
        }

        .creative-preview {
            background: linear-gradient(135deg, var(--accent-color), #c0392b);
        }

        /* محرر السيرة */
        .cv-builder {
            padding: 50px 0;
            background-color: #f9f9f9;
        }

        .cv-builder h2 {
            text-align: center;
            margin-bottom: 30px;
            color: var(--secondary-color);
            font-size: 2rem;
        }

        .builder-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
            margin-top: 30px;
        }

        @media (max-width: 768px) {
            .builder-container {
                grid-template-columns: 1fr;
            }
            
            .nav-links {
                flex-direction: column;
                gap: 1rem;
                text-align: center;
            }
            
            .hero h2 {
                font-size: 2rem;
            }
            
            .template-selector {
                flex-direction: column;
                align-items: center;
            }
            
            .nav-container {
                flex-direction: column;
                gap: 1rem;
            }
            
            .form-actions {
                flex-direction: column;
            }
            
            .language-selector {
                position: relative;
                top: 0;
                left: 0;
                text-align: center;
                margin-bottom: 15px;
            }
        }

        .input-sidebar {
            background: var(--white);
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            height: fit-content;
        }

        .form-section {
            margin-bottom: 30px;
            padding-bottom: 20px;
            border-bottom: 1px solid #eee;
        }

        .form-section:last-child {
            border-bottom: none;
        }

        .form-section h3 {
            color: var(--secondary-color);
            margin-bottom: 15px;
            padding-bottom: 5px;
            border-bottom: 2px solid var(--primary-color);
            display: inline-block;
        }

        input, textarea, select {
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
            transition: border 0.3s;
        }

        input:focus, textarea:focus, select:focus {
            border-color: var(--primary-color);
            outline: none;
            box-shadow: 0 0 5px rgba(52, 152, 219, 0.3);
        }

        button {
            background: var(--primary-color);
            color: var(--white);
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
            font-size: 1rem;
        }

        button:hover {
            background: #2980b9;
        }

        .add-btn {
            background: var(--success-color);
            display: block;
            width: 100%;
            margin-top: 10px;
        }

        .add-btn:hover {
            background: #219a52;
        }

        .remove-btn {
            background: var(--accent-color);
            padding: 5px 10px;
            font-size: 0.9rem;
            margin-top: 5px;
        }

        .remove-btn:hover {
            background: #c0392b;
        }

        .experience-item, .education-item, .skill-item {
            background: #f9f9f9;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 15px;
            border-left: 3px solid var(--primary-color);
            position: relative;
        }

        /* معاينة السيرة */
        .preview-sidebar {
            position: sticky;
            top: 100px;
        }

        .cv-preview {
            background: var(--white);
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            min-height: 600px;
            font-family: 'Arial', sans-serif;
        }

        .cv-header {
            text-align: center;
            margin-bottom: 30px;
            border-bottom: 2px solid var(--primary-color);
            padding-bottom: 20px;
        }

        .cv-header h3 {
            font-size: 28px;
            color: var(--secondary-color);
            margin-bottom: 10px;
        }

        .cv-header p {
            color: var(--gray);
        }

        .cv-section {
            margin-bottom: 25px;
        }

        .cv-section h4 {
            color: var(--secondary-color);
            border-bottom: 1px solid #eee;
            padding-bottom: 5px;
            margin-bottom: 10px;
            font-size: 18px;
        }

        .experience-preview, .education-preview {
            margin-bottom: 15px;
        }

        .experience-preview h5, .education-preview h5 {
            color: var(--secondary-color);
            margin-bottom: 5px;
        }

        .experience-preview .company, .education-preview .institution {
            color: var(--primary-color);
            font-weight: bold;
        }

        .experience-preview .period, .education-preview .period {
            color: var(--gray);
            font-style: italic;
        }

        .skill-tag {
            background: var(--light-gray);
            padding: 5px 10px;
            border-radius: 15px;
            margin: 5px;
            display: inline-block;
            font-size: 0.9rem;
        }

        .download-btn {
            background: var(--success-color);
            width: 100%;
            margin-top: 20px;
            padding: 15px;
            font-size: 1.1rem;
        }

        .download-btn:hover {
            background: #219a52;
        }

        .update-btn {
            background: var(--warning-color);
            width: 100%;
            margin-top: 10px;
        }

        .update-btn:hover {
            background: #d68910;
        }

        /* قسم اتصل بنا */
        .contact-section {
            padding: 50px 0;
            background-color: var(--secondary-color);
            color: var(--white);
            text-align: center;
        }

        .contact-section h2 {
            margin-bottom: 20px;
        }

        .contact-info {
            max-width: 600px;
            margin: 0 auto;
        }

        .contact-info ul {
            list-style: none;
            margin-top: 15px;
        }

        .contact-info li {
            margin-bottom: 10px;
        }

        /* التنبيهات */
        .alert {
            padding: 15px;
            margin-bottom: 20px;
            border: 1px solid transparent;
            border-radius: 4px;
            text-align: center;
        }

        .alert-success {
            color: #155724;
            background-color: #d4edda;
            border-color: #c3e6cb;
            display: none;
        }

        .alert-info {
            color: #0c5460;
            background-color: #d1ecf1;
            border-color: #bee5eb;
            display: none;
        }

        footer {
            background: #34495e;
            color: var(--white);
            text-align: center;
            padding: 20px 0;
            margin-top: 50px;
        }

        .form-actions {
            display: flex;
            gap: 10px;
            margin-top: 20px;
            flex-wrap: wrap;
        }

        .save-btn {
            background: #9b59b6;
        }

        .save-btn:hover {
            background: #8e44ad;
        }

        .upload-btn {
            background: #16a085;
        }

        .upload-btn:hover {
            background: #138a72;
        }

        .import-btn {
            background: #d35400;
        }

        .import-btn:hover {
            background: #b84500;
        }

        .features {
            padding: 50px 0;
            background-color: var(--white);
        }

        .features h2 {
            text-align: center;
            margin-bottom: 40px;
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .feature-card {
            background: #f8f9fa;
            padding: 30px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .feature-card:hover {
            transform: translateY(-5px);
        }

        .feature-card h3 {
            color: var(--secondary-color);
            margin-bottom: 15px;
        }

        .language-selector {
            position: absolute;
            top: 20px;
            left: 20px;
            z-index: 1001;
        }

        .language-selector select {
            padding: 5px 10px;
            border-radius: 5px;
            border: 1px solid #ddd;
            background: var(--white);
        }
        
        /* تحسينات إضافية */
        .section-title {
            text-align: center;
            margin-bottom: 40px;
            color: var(--secondary-color);
            position: relative;
        }
        
        .section-title:after {
            content: '';
            display: block;
            width: 80px;
            height: 3px;
            background: var(--primary-color);
            margin: 10px auto 0;
        }
        
        .loading {
            display: none;
            text-align: center;
            padding: 20px;
        }
        
        .spinner {
            border: 4px solid #f3f3f3;
            border-top: 4px solid var(--primary-color);
            border-radius: 50%;
            width: 40px;
            height: 40px;
            animation: spin 2s linear infinite;
            margin: 0 auto;
        }
        
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        .file-upload-section {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
            border: 2px dashed var(--primary-color);
            text-align: center;
        }
        
        .file-upload-section h4 {
            margin-bottom: 15px;
            color: var(--secondary-color);
        }
        
        .file-input {
            display: none;
        }
        
        .file-label {
            display: inline-block;
            padding: 10px 20px;
            background: var(--primary-color);
            color: var(--white);
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }
        
        .file-label:hover {
            background: #2980b9;
        }
        
        .upload-info {
            margin-top: 10px;
            font-size: 0.9rem;
            color: var(--gray);
        }
        
        .analysis-result {
            margin-top: 20px;
            padding: 15px;
            background: #e8f4fc;
            border-radius: 5px;
            border-left: 4px solid var(--primary-color);
            display: none;
        }
        
        .missing-sections {
            margin-top: 10px;
        }
        
        .missing-item {
            display: flex;
            align-items: center;
            margin-bottom: 5px;
        }
        
        .missing-item i {
            margin-left: 5px;
            color: var(--accent-color);
        }
        
        .ai-suggestions {
            margin-top: 20px;
            padding: 15px;
            background: #fff3cd;
            border-radius: 5px;
            border-left: 4px solid var(--warning-color);
            display: none;
        }
        
        .suggestion-item {
            margin-bottom: 10px;
            padding: 10px;
            background: var(--white);
            border-radius: 5px;
        }
        
        .ai-button {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            border: none;
            padding: 8px 15px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 5px;
            font-size: 0.9rem;
        }
        
        .progress-bar {
            height: 5px;
            background: #eee;
            border-radius: 5px;
            margin-top: 10px;
            overflow: hidden;
        }
        
        .progress {
            height: 100%;
            background: var(--success-color);
            width: 0%;
            transition: width 0.5s;
        }
        
        .cv-completeness {
            text-align: center;
            margin-bottom: 15px;
            font-weight: bold;
        }
        
        /* أنماط للغة الإنجليزية */
        body[dir="ltr"] .section-title:after {
            margin: 10px auto 0;
        }
        
        body[dir="ltr"] .form-section h3 {
            padding-bottom: 5px;
            border-bottom: 2px solid var(--primary-color);
        }
        
        body[dir="ltr"] .experience-item, 
        body[dir="ltr"] .education-item, 
        body[dir="ltr"] .skill-item {
            border-left: none;
            border-right: 3px solid var(--primary-color);
        }
        
        body[dir="ltr"] .missing-item i {
            margin-left: 0;
            margin-right: 5px;
        }
    </style>
</head>
<body>
    <div class="language-selector">
        <select id="languageSelect">
            <option value="ar">العربية</option>
            <option value="en">English</option>
        </select>
    </div>

    <header>
        <nav>
            <div class="nav-container">
                <div class="logo">
                    <h1 id="logo-text">سيرتي</h1>
                </div>
                <ul class="nav-links">
                    <li><a href="#home" id="nav-home">الرئيسية</a></li>
                    <li><a href="#templates" id="nav-templates">القوالب</a></li>
                    <li><a href="#create" id="nav-create">إنشاء سيرة</a></li>
                    <li><a href="#contact" id="nav-contact">اتصل بنا</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <main>
        <!-- قسم الرئيسية -->
        <section id="home" class="hero">
            <div class="container">
                <h2 id="hero-title">أنشئ سيرتك الذاتية باحترافية في دقائق</h2>
                <p id="hero-subtitle">اختر من بين القوالب المصممة بخبرة واحصل على وظيفة أحلامك</p>
                <button class="cta-button" onclick="startCreating()" id="hero-button">ابدأ الآن مجانًا</button>
            </div>
        </section>

        <!-- قسم المميزات -->
        <section class="features">
            <div class="container">
                <h2 class="section-title" id="features-title">مميزات موقعنا</h2>
                <div class="features-grid">
                    <div class="feature-card">
                        <i class="fas fa-magic fa-3x" style="color: #3498db; margin-bottom: 15px;"></i>
                        <h3 id="feature1-title">سهل الاستخدام</h3>
                        <p id="feature1-desc">واجهة بسيطة تمكنك من إنشاء سيرة ذاتية احترافية في دقائق</p>
                    </div>
                    <div class="feature-card">
                        <i class="fas fa-palette fa-3x" style="color: #e74c3c; margin-bottom: 15px;"></i>
                        <h3 id="feature2-title">قوالب متعددة</h3>
                        <p id="feature2-desc">اختر من بين مجموعة متنوعة من القوالب المناسبة لمختلف المجالات</p>
                    </div>
                    <div class="feature-card">
                        <i class="fas fa-file-pdf fa-3x" style="color: #27ae60; margin-bottom: 15px;"></i>
                        <h3 id="feature3-title">تحميل فوري</h3>
                        <p id="feature3-desc">احصل على سيرتك الذاتية بصيغة PDF جاهزة للإرسال</p>
                    </div>
                    <div class="feature-card">
                        <i class="fas fa-upload fa-3x" style="color: #9b59b6; margin-bottom: 15px;"></i>
                        <h3 id="feature4-title">رفع وتعديل السير</h3>
                        <p id="feature4-desc">أرفع سيرتك الحالية لتعديلها وإكمال النواقص فيها</p>
                    </div>
                    <div class="feature-card">
                        <i class="fas fa-robot fa-3x" style="color: #16a085; margin-bottom: 15px;"></i>
                        <h3 id="feature5-title">مساعد ذكي</h3>
                        <p id="feature5-desc">احصل على اقتراحات ذكية لتحسين سيرتك الذاتية</p>
                    </div>
                    <div class="feature-card">
                        <i class="fas fa-chart-line fa-3x" style="color: #d35400; margin-bottom: 15px;"></i>
                        <h3 id="feature6-title">تتبع التقدم</h3>
                        <p id="feature6-desc">تتبع اكتمال سيرتك الذاتية واحصل على نصائح للتحسين</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- قسم القوالب -->
        <section id="templates" class="templates-section">
            <div class="container">
                <h2 class="section-title" id="templates-title">اختر قالب السيرة الذاتية</h2>
                <div class="template-selector">
                    <div class="template-option active" data-template="modern">
                        <div class="template-preview modern-preview" id="template-modern">قالب حديث</div>
                        <p id="template-modern-desc">قالب عصري</p>
                    </div>
                    <div class="template-option" data-template="professional">
                        <div class="template-preview professional-preview" id="template-professional">قالب احترافي</div>
                        <p id="template-professional-desc">قالب تقليدي</p>
                    </div>
                    <div class="template-option" data-template="creative">
                        <div class="template-preview creative-preview" id="template-creative">قالب إبداعي</div>
                        <p id="template-creative-desc">قالب مبدع</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- قسم إنشاء السيرة -->
        <section id="create" class="cv-builder">
            <div class="container">
                <h2 class="section-title" id="builder-title">محرر السيرة الذاتية</h2>
                
                <div class="alert alert-success" id="successAlert">
                    تم تحديث السيرة الذاتية بنجاح!
                </div>
                
                <div class="alert alert-info" id="uploadAlert">
                    تم رفع الملف بنجاح! جاري تحليل المحتوى...
                </div>
                
                <div class="cv-completeness">
                    <span id="completeness-text">اكتمال السيرة الذاتية:</span> <span id="completenessPercent">0%</span>
                </div>
                <div class="progress-bar">
                    <div class="progress" id="completenessProgress"></div>
                </div>
                
                <div class="loading" id="loadingIndicator">
                    <div class="spinner"></div>
                    <p id="loading-text">جاري تحميل السيرة الذاتية...</p>
                </div>
                
                <div class="file-upload-section">
                    <h4><i class="fas fa-upload"></i> <span id="upload-title">رفع سيرة ذاتية موجودة</span></h4>
                    <p id="upload-desc">يمكنك رفع سيرتك الذاتية الحالية (PDF أو صورة) لتعديلها وإكمال النواقص</p>
                    <input type="file" id="fileInput" class="file-input" accept=".pdf,.jpg,.jpeg,.png,.doc,.docx">
                    <label for="fileInput" class="file-label" id="file-label">اختر ملف السيرة الذاتية</label>
                    <div class="upload-info" id="upload-info">يدعم الموقع ملفات PDF، الصور، وملفات Word (DOC, DOCX)</div>
                    
                    <div id="analysisResult" class="analysis-result">
                        <h5 id="analysis-title">نتيجة تحليل السيرة الذاتية:</h5>
                        <div id="missingSections" class="missing-sections"></div>
                        <p id="analysis-desc">يمكنك الآن تعديل السيرة وإضافة الأقسام الناقصة باستخدام النموذج أدناه.</p>
                    </div>
                    
                    <div id="aiSuggestions" class="ai-suggestions">
                        <h5 id="ai-title">اقتراحات الذكاء الاصطناعي لتحسين سيرتك:</h5>
                        <div id="suggestionsList"></div>
                        <button class="ai-button" onclick="applyAISuggestions()" id="ai-button">تطبيق الاقتراحات</button>
                    </div>
                </div>
                
                <div class="builder-container">
                    <!-- جانب الإدخال -->
                    <div class="input-sidebar">
                        <form id="cvForm">
                            <div class="form-section">
                                <h3 id="personal-info-title">المعلومات الشخصية</h3>
                                <input type="text" id="name" placeholder="الاسم الكامل" required>
                                <input type="email" id="email" placeholder="البريد الإلكتروني">
                                <input type="tel" id="phone" placeholder="رقم الهاتف">
                                <input type="text" id="jobTitle" placeholder="المسمى الوظيفي المستهدف">
                                <input type="text" id="location" placeholder="المدينة/البلد">
                                <textarea id="summary" placeholder="ملخص احترافي" rows="3"></textarea>
                            </div>

                            <div class="form-section">
                                <h3 id="experience-title">الخبرة العملية</h3>
                                <div id="experiences">
                                    <div class="experience-item">
                                        <input type="text" class="exp-title" placeholder="المسمى الوظيفي">
                                        <input type="text" class="exp-company" placeholder="اسم الشركة">
                                        <input type="text" class="exp-period" placeholder="الفترة الزمنية (مثال: 2020 - 2023)">
                                        <textarea class="exp-description" placeholder="المسؤوليات والإنجازات" rows="3"></textarea>
                                        <button type="button" class="remove-btn" onclick="removeExperience(this)" id="remove-exp-btn">حذف الخبرة</button>
                                    </div>
                                </div>
                                <button type="button" class="add-btn" onclick="addExperience()" id="add-exp-btn">+ إضافة خبرة أخرى</button>
                            </div>

                            <div class="form-section">
                                <h3 id="education-title">التعليم</h3>
                                <div id="educations">
                                    <div class="education-item">
                                        <input type="text" class="edu-degree" placeholder="المؤهل الدراسي">
                                        <input type="text" class="edu-institution" placeholder="اسم المؤسسة التعليمية">
                                        <input type="text" class="edu-period" placeholder="سنة التخرج">
                                        <textarea class="edu-details" placeholder="التفاصيل الإضافية (اختياري)" rows="2"></textarea>
                                        <button type="button" class="remove-btn" onclick="removeEducation(this)" id="remove-edu-btn">حذف المؤهل</button>
                                    </div>
                                </div>
                                <button type="button" class="add-btn" onclick="addEducation()" id="add-edu-btn">+ إضافة مؤهل آخر</button>
                            </div>

                            <div class="form-section">
                                <h3 id="skills-title">المهارات</h3>
                                <div id="skills-container">
                                    <div class="skill-item">
                                        <input type="text" class="skill-input" placeholder="المهارة (مثال: HTML, CSS, JavaScript)">
                                        <select class="skill-level">
                                            <option value="">مستوى المهارة</option>
                                            <option value="مبتدئ">مبتدئ</option>
                                            <option value="متوسط">متوسط</option>
                                            <option value="متقدم">متقدم</option>
                                            <option value="خبير">خبير</option>
                                        </select>
                                        <button type="button" class="remove-btn" onclick="removeSkill(this)" id="remove-skill-btn">حذف</button>
                                    </div>
                                </div>
                                <button type="button" class="add-btn" onclick="addSkill()" id="add-skill-btn">+ إضافة مهارة</button>
                            </div>
                            
                            <div class="form-section">
                                <h3 id="additional-title">معلومات إضافية</h3>
                                <textarea id="languages" placeholder="اللغات التي تتقنها" rows="2"></textarea>
                                <textarea id="certifications" placeholder="الشهادات والدورات" rows="2"></textarea>
                                <textarea id="projects" placeholder="المشاريع الشخصية" rows="2"></textarea>
                            </div>

                            <div class="form-actions">
                                <button type="button" class="update-btn" onclick="updatePreview()" id="update-btn">تحديث المعاينة</button>
                                <button type="button" class="save-btn" onclick="saveCV()" id="save-btn">حفظ السيرة</button>
                                <button type="button" class="upload-btn" onclick="importCV()" id="import-btn">استيراد من ملف</button>
                                <button type="button" class="download-btn" onclick="generatePDF()" id="download-btn">تحميل PDF</button>
                                <button type="button" class="ai-button" onclick="getAISuggestions()" id="ai-suggest-btn">اقتراحات الذكاء الاصطناعي</button>
                            </div>
                        </form>
                    </div>

                    <!-- معاينة السيرة -->
                    <div class="preview-sidebar">
                        <div class="cv-preview" id="cvPreview">
                            <div class="cv-header">
                                <h3 id="previewName">اسمك الكامل</h3>
                                <p id="previewJobTitle">المسمى الوظيفي المستهدف</p>
                                <p id="previewContact">بريدك الإلكتروني | هاتفك</p>
                                <p id="previewLocation">مدينتك/بلدك</p>
                            </div>
                            
                            <div class="cv-section">
                                <h4 id="preview-summary-title">ملخص احترافي</h4>
                                <p id="previewSummary">ملخصك المهني سيظهر هنا</p>
                            </div>
                            
                            <div class="cv-section">
                                <h4 id="preview-exp-title">الخبرة العملية</h4>
                                <div id="previewExperience">
                                    <div class="experience-preview">
                                        <h5>المسمى الوظيفي</h5>
                                        <span class="company">اسم الشركة</span> | 
                                        <span class="period">الفترة الزمنية</span>
                                        <p>وصف المسؤوليات والإنجازات</p>
                                    </div>
                                </div>
                            </div>

                            <div class="cv-section">
                                <h4 id="preview-edu-title">التعليم</h4>
                                <div id="previewEducation">
                                    <div class="education-preview">
                                        <h5>المؤهل الدراسي</h5>
                                        <span class="institution">اسم المؤسسة التعليمية</span> | 
                                        <span class="period">سنة التخرج</span>
                                    </div>
                                </div>
                            </div>

                            <div class="cv-section">
                                <h4 id="preview-skills-title">المهارات</h4>
                                <div id="previewSkills">
                                    <span class="skill-tag">مهارة مثال</span>
                                </div>
                            </div>
                            
                            <div class="cv-section" id="previewAdditional" style="display: none;">
                                <h4 id="preview-add-title">معلومات إضافية</h4>
                                <div id="previewLanguages"></div>
                                <div id="previewCertifications"></div>
                                <div id="previewProjects"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- قسم اتصل بنا -->
        <section id="contact" class="contact-section">
            <div class="container">
                <h2 class="section-title" id="contact-title">اتصل بنا</h2>
                <div class="contact-info">
                    <p id="contact-desc">للاستفسارات والدعم الفني، يرجى التواصل معنا عبر:</p>
                    <ul>
                        <li><i class="fas fa-envelope"></i> <span id="contact-email">البريد الإلكتروني: support@cvmaker.com</span></li>
                        <li><i class="fas fa-phone"></i> <span id="contact-phone">الهاتف: 0123456789</span></li>
                        <li><i class="fas fa-map-marker-alt"></i> <span id="contact-address">العنوان: المدينة، الشارع، الدولة</span></li>
                    </ul>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p id="footer-text">© 2024 جميع الحقوق محفوظة - منشئ السيرة الذاتية</p>
        </div>
    </footer>

    <script>
        // ترجمة النصوص
        const translations = {
            ar: {
                // النصوص العربية
                "logo-text": "سيرتي",
                "nav-home": "الرئيسية",
                "nav-templates": "القوالب",
                "nav-create": "إنشاء سيرة",
                "nav-contact": "اتصل بنا",
                "hero-title": "أنشئ سيرتك الذاتية باحترافية في دقائق",
                "hero-subtitle": "اختر من بين القوالب المصممة بخبرة واحصل على وظيفة أحلامك",
                "hero-button": "ابدأ الآن مجانًا",
                "features-title": "مميزات موقعنا",
                "feature1-title": "سهل الاستخدام",
                "feature1-desc": "واجهة بسيطة تمكنك من إنشاء سيرة ذاتية احترافية في دقائق",
                "feature2-title": "قوالب متعددة",
                "feature2-desc": "اختر من بين مجموعة متنوعة من القوالب المناسبة لمختلف المجالات",
                "feature3-title": "تحميل فوري",
                "feature3-desc": "احصل على سيرتك الذاتية بصيغة PDF جاهزة للإرسال",
                "feature4-title": "رفع وتعديل السير",
                "feature4-desc": "أرفع سيرتك الحالية لتعديلها وإكمال النواقص فيها",
                "feature5-title": "مساعد ذكي",
                "feature5-desc": "احصل على اقتراحات ذكية لتحسين سيرتك الذاتية",
                "feature6-title": "تتبع التقدم",
                "feature6-desc": "تتبع اكتمال سيرتك الذاتية واحصل على نصائح للتحسين",
                "templates-title": "اختر قالب السيرة الذاتية",
                "template-modern": "قالب حديث",
                "template-modern-desc": "قالب عصري",
                "template-professional": "قالب احترافي",
                "template-professional-desc": "قالب تقليدي",
                "template-creative": "قالب إبداعي",
                "template-creative-desc": "قالب مبدع",
                "builder-title": "محرر السيرة الذاتية",
                "completeness-text": "اكتمال السيرة الذاتية:",
                "loading-text": "جاري تحميل السيرة الذاتية...",
                "upload-title": "رفع سيرة ذاتية موجودة",
                "upload-desc": "يمكنك رفع سيرتك الذاتية الحالية (PDF أو صورة) لتعديلها وإكمال النواقص",
                "file-label": "اختر ملف السيرة الذاتية",
                "upload-info": "يدعم الموقع ملفات PDF، الصور، وملفات Word (DOC, DOCX)",
                "analysis-title": "نتيجة تحليل السيرة الذاتية:",
                "analysis-desc": "يمكنك الآن تعديل السيرة وإضافة الأقسام الناقصة باستخدام النموذج أدناه.",
                "ai-title": "اقتراحات الذكاء الاصطناعي لتحسين سيرتك:",
                "ai-button": "تطبيق الاقتراحات",
                "personal-info-title": "المعلومات الشخصية",
                "experience-title": "الخبرة العملية",
                "education-title": "التعليم",
                "skills-title": "المهارات",
                "additional-title": "معلومات إضافية",
                "remove-exp-btn": "حذف الخبرة",
                "add-exp-btn": "+ إضافة خبرة أخرى",
                "remove-edu-btn": "حذف المؤهل",
                "add-edu-btn": "+ إضافة مؤهل آخر",
                "remove-skill-btn": "حذف",
                "add-skill-btn": "+ إضافة مهارة",
                "update-btn": "تحديث المعاينة",
                "save-btn": "حفظ السيرة",
                "import-btn": "استيراد من ملف",
                "download-btn": "تحميل PDF",
                "ai-suggest-btn": "اقتراحات الذكاء الاصطناعي",
                "preview-summary-title": "ملخص احترافي",
                "preview-exp-title": "الخبرة العملية",
                "preview-edu-title": "التعليم",
                "preview-skills-title": "المهارات",
                "preview-add-title": "معلومات إضافية",
                "contact-title": "اتصل بنا",
                "contact-desc": "للاستفسارات والدعم الفني، يرجى التواصل معنا عبر:",
                "contact-email": "البريد الإلكتروني: support@cvmaker.com",
                "contact-phone": "الهاتف: 0123456789",
                "contact-address": "العنوان: المدينة، الشارع، الدولة",
                "footer-text": "© 2024 جميع الحقوق محفوظة - منشئ السيرة الذاتية",
                "success-alert": "تم تحديث السيرة الذاتية بنجاح!",
                "upload-alert": "تم رفع الملف بنجاح! جاري تحليل المحتوى..."
            },
            en: {
                // النصوص الإنجليزية
                "logo-text": "MyCV",
                "nav-home": "Home",
                "nav-templates": "Templates",
                "nav-create": "Create CV",
                "nav-contact": "Contact Us",
                "hero-title": "Create Your Professional Resume in Minutes",
                "hero-subtitle": "Choose from expertly designed templates and land your dream job",
                "hero-button": "Start Now for Free",
                "features-title": "Our Features",
                "feature1-title": "Easy to Use",
                "feature1-desc": "Simple interface to create a professional resume in minutes",
                "feature2-title": "Multiple Templates",
                "feature2-desc": "Choose from a variety of templates suitable for different fields",
                "feature3-title": "Instant Download",
                "feature3-desc": "Get your resume in PDF format ready to send",
                "feature4-title": "Upload & Edit Resumes",
                "feature4-desc": "Upload your existing resume to edit and complete missing parts",
                "feature5-title": "Smart Assistant",
                "feature5-desc": "Get smart suggestions to improve your resume",
                "feature6-title": "Progress Tracking",
                "feature6-desc": "Track your resume completion and get improvement tips",
                "templates-title": "Choose Your Resume Template",
                "template-modern": "Modern Template",
                "template-modern-desc": "Modern Design",
                "template-professional": "Professional Template",
                "template-professional-desc": "Traditional Design",
                "template-creative": "Creative Template",
                "template-creative-desc": "Creative Design",
                "builder-title": "Resume Builder",
                "completeness-text": "Resume Completeness:",
                "loading-text": "Loading Resume...",
                "upload-title": "Upload Existing Resume",
                "upload-desc": "You can upload your current resume (PDF or image) to edit and complete missing parts",
                "file-label": "Choose Resume File",
                "upload-info": "Supports PDF, Images, and Word files (DOC, DOCX)",
                "analysis-title": "Resume Analysis Result:",
                "analysis-desc": "You can now edit the resume and add missing sections using the form below.",
                "ai-title": "AI Suggestions to Improve Your Resume:",
                "ai-button": "Apply Suggestions",
                "personal-info-title": "Personal Information",
                "experience-title": "Work Experience",
                "education-title": "Education",
                "skills-title": "Skills",
                "additional-title": "Additional Information",
                "remove-exp-btn": "Delete Experience",
                "add-exp-btn": "+ Add Another Experience",
                "remove-edu-btn": "Delete Education",
                "add-edu-btn": "+ Add Another Education",
                "remove-skill-btn": "Delete",
                "add-skill-btn": "+ Add Skill",
                "update-btn": "Update Preview",
                "save-btn": "Save Resume",
                "import-btn": "Import from File",
                "download-btn": "Download PDF",
                "ai-suggest-btn": "AI Suggestions",
                "preview-summary-title": "Professional Summary",
                "preview-exp-title": "Work Experience",
                "preview-edu-title": "Education",
                "preview-skills-title": "Skills",
                "preview-add-title": "Additional Information",
                "contact-title": "Contact Us",
                "contact-desc": "For inquiries and technical support, please contact us via:",
                "contact-email": "Email: support@cvmaker.com",
                "contact-phone": "Phone: 0123456789",
                "contact-address": "Address: City, Street, Country",
                "footer-text": "© 2024 All Rights Reserved - Resume Builder",
                "success-alert": "Resume updated successfully!",
                "upload-alert": "File uploaded successfully! Analyzing content..."
            }
        };

        // وظيفة تغيير اللغة
        function changeLanguage(lang) {
            // تحديث اتجاه الصفحة
            document.body.dir = lang === 'ar' ? 'rtl' : 'ltr';
            document.documentElement.lang = lang;
            
            // تحديث جميع النصوص
            Object.keys(translations[lang]).forEach(key => {
                const element = document.getElementById(key);
                if (element) {
                    element.textContent = translations[lang][key];
                }
            });
            
            // تحديث النصوص في الأماكن الأخرى
            document.querySelectorAll('input, textarea, select').forEach(element => {
                const placeholder = element.getAttribute('placeholder');
                if (placeholder) {
                    const translationKey = Object.keys(translations[lang]).find(key => 
                        translations['ar'][key] === placeholder || translations['en'][key] === placeholder
                    );
                    if (translationKey) {
                        element.setAttribute('placeholder', translations[lang][translationKey]);
                    }
                }
            });
            
            // تحديث رسائل التنبيه
            document.getElementById('successAlert').textContent = translations[lang]['success-alert'];
            document.getElementById('uploadAlert').textContent = translations[lang]['upload-alert'];
        }

        // دالة للبدء في إنشاء السيرة
        function startCreating() {
            document.getElementById('create').scrollIntoView({
                behavior: 'smooth'
            });
        }

        // تحديث المعاينة
        function updatePreview() {
            // إظهار مؤشر التحميل
            document.getElementById('loadingIndicator').style.display = 'block';
            
            // تأخير بسيط لمحاكاة التحميل
            setTimeout(() => {
                // المعلومات الشخصية
                const name = document.getElementById('name').value || 'اسمك الكامل';
                const jobTitle = document.getElementById('jobTitle').value || 'المسمى الوظيفي المستهدف';
                const email = document.getElementById('email').value || 'بريدك الإلكتروني';
                const phone = document.getElementById('phone').value || 'هاتفك';
                const location = document.getElementById('location').value || '';
                const summary = document.getElementById('summary').value || 'ملخصك المهني سيظهر هنا';
                
                document.getElementById('previewName').textContent = name;
                document.getElementById('previewJobTitle').textContent = jobTitle;
                document.getElementById('previewContact').textContent = `${email} | ${phone}`;
                if (location) {
                    document.getElementById('previewLocation').textContent = location;
                    document.getElementById('previewLocation').style.display = 'block';
                } else {
                    document.getElementById('previewLocation').style.display = 'none';
                }
                document.getElementById('previewSummary').textContent = summary;
                
                // الخبرات العملية
                const experiences = document.querySelectorAll('.experience-item');
                const previewExperience = document.getElementById('previewExperience');
                previewExperience.innerHTML = '';
                
                if (experiences.length === 0) {
                    previewExperience.innerHTML = '<p>لا توجد خبرات مضافة بعد</p>';
                } else {
                    experiences.forEach(exp => {
                        const title = exp.querySelector('.exp-title').value || 'المسمى الوظيفي';
                        const company = exp.querySelector('.exp-company').value || 'اسم الشركة';
                        const period = exp.querySelector('.exp-period').value || 'الفترة الزمنية';
                        const description = exp.querySelector('.exp-description').value || 'وصف المسؤوليات والإنجازات';
                        
                        const expHTML = `
                            <div class="experience-preview">
                                <h5>${title}</h5>
                                <span class="company">${company}</span> | 
                                <span class="period">${period}</span>
                                <p>${description.replace(/\n/g, '<br>')}</p>
                            </div>
                        `;
                        
                        previewExperience.innerHTML += expHTML;
                    });
                }
                
                // التعليم
                const educations = document.querySelectorAll('.education-item');
                const previewEducation = document.getElementById('previewEducation');
                previewEducation.innerHTML = '';
                
                if (educations.length === 0) {
                    previewEducation.innerHTML = '<p>لا توجد مؤهلات مضافة بعد</p>';
                } else {
                    educations.forEach(edu => {
                        const degree = edu.querySelector('.edu-degree').value || 'المؤهل الدراسي';
                        const institution = edu.querySelector('.edu-institution').value || 'اسم المؤسسة التعليمية';
                        const period = edu.querySelector('.edu-period').value || 'سنة التخرج';
                        const details = edu.querySelector('.edu-details').value || '';
                        
                        const eduHTML = `
                            <div class="education-preview">
                                <h5>${degree}</h5>
                                <span class="institution">${institution}</span> | 
                                <span class="period">${period}</span>
                                ${details ? `<p>${details.replace(/\n/g, '<br>')}</p>` : ''}
                            </div>
                        `;
                        
                        previewEducation.innerHTML += eduHTML;
                    });
                }
                
                // المهارات
                const skills = document.querySelectorAll('.skill-input');
                const previewSkills = document.getElementById('previewSkills');
                previewSkills.innerHTML = '';
                
                if (skills.length === 0) {
                    previewSkills.innerHTML = '<p>لا توجد مهارات مضافة بعد</p>';
                } else {
                    skills.forEach(skill => {
                        const skillValue = skill.value.trim();
                        const skillLevel = skill.parentElement.querySelector('.skill-level').value;
                        if (skillValue) {
                            const levelText = skillLevel ? ` (${skillLevel})` : '';
                            const skillHTML = `<span class="skill-tag">${skillValue}${levelText}</span>`;
                            previewSkills.innerHTML += skillHTML;
                        }
                    });
                }
                
                // المعلومات الإضافية
                const languages = document.getElementById('languages').value;
                const certifications = document.getElementById('certifications').value;
                const projects = document.getElementById('projects').value;
                
                const additionalSection = document.getElementById('previewAdditional');
                if (languages || certifications || projects) {
                    additionalSection.style.display = 'block';
                    
                    if (languages) {
                        document.getElementById('previewLanguages').innerHTML = `<strong>اللغات:</strong> ${languages}`;
                    }
                    if (certifications) {
                        document.getElementById('previewCertifications').innerHTML = `<strong>الشهادات والدورات:</strong> ${certifications}`;
                    }
                    if (projects) {
                        document.getElementById('previewProjects').innerHTML = `<strong>المشاريع الشخصية:</strong> ${projects}`;
                    }
                } else {
                    additionalSection.style.display = 'none';
                }
                
                // تحديث مؤشر الاكتمال
                updateCompleteness();
                
                // إخفاء مؤشر التحميل
                document.getElementById('loadingIndicator').style.display = 'none';
                
                // إظهار رسالة النجاح
                const alert = document.getElementById('successAlert');
                alert.style.display = 'block';
                setTimeout(() => {
                    alert.style.display = 'none';
                }, 3000);
            }, 500);
        }

        // تحديث مؤشر اكتمال السيرة الذاتية
        function updateCompleteness() {
            let completeness = 0;
            const totalPoints = 12; // إجمالي النقاط المحتملة
            
            // المعلومات الأساسية (3 نقاط)
            if (document.getElementById('name').value) completeness += 1;
            if (document.getElementById('email').value) completeness += 1;
            if (document.getElementById('jobTitle').value) completeness += 1;
            
            // الملخص (1 نقطة)
            if (document.getElementById('summary').value) completeness += 1;
            
            // الخبرات (2 نقطة - نقطة لكل خبرة، بحد أقصى 2)
            const experiences = document.querySelectorAll('.experience-item');
            completeness += Math.min(experiences.length, 2);
            
            // التعليم (1 نقطة)
            const educations = document.querySelectorAll('.education-item');
            if (educations.length > 0) completeness += 1;
            
            // المهارات (2 نقطة)
            const skills = document.querySelectorAll('.skill-input');
            completeness += Math.min(skills.length, 2);
            
            // المعلومات الإضافية (2 نقطة)
            if (document.getElementById('languages').value) completeness += 1;
            if (document.getElementById('certifications').value || document.getElementById('projects').value) completeness += 1;
            
            const percent = Math.round((completeness / totalPoints) * 100);
            document.getElementById('completenessPercent').textContent = percent + '%';
            document.getElementById('completenessProgress').style.width = percent + '%';
        }

        // إضافة خبرة عمل جديدة
        function addExperience() {
            const experiencesDiv = document.getElementById('experiences');
            const newExperience = document.createElement('div');
            newExperience.className = 'experience-item';
            newExperience.innerHTML = `
                <input type="text" class="exp-title" placeholder="المسمى الوظيفي">
                <input type="text" class="exp-company" placeholder="اسم الشركة">
                <input type="text" class="exp-period" placeholder="الفترة الزمنية (مثال: 2020 - 2023)">
                <textarea class="exp-description" placeholder="المسؤوليات والإنجازات" rows="3"></textarea>
                <button type="button" class="remove-btn" onclick="removeExperience(this)">حذف الخبرة</button>
            `;
            experiencesDiv.appendChild(newExperience);
        }

        // حذف خبرة
        function removeExperience(button) {
            button.parentElement.remove();
            updatePreview();
        }

        // إضافة تعليم جديد
        function addEducation() {
            const educationsDiv = document.getElementById('educations');
            const newEducation = document.createElement('div');
            newEducation.className = 'education-item';
            newEducation.innerHTML = `
                <input type="text" class="edu-degree" placeholder="المؤهل الدراسي">
                <input type="text" class="edu-institution" placeholder="اسم المؤسسة التعليمية">
                <input type="text" class="edu-period" placeholder="سنة التخرج">
                <textarea class="edu-details" placeholder="التفاصيل الإضافية (اختياري)" rows="2"></textarea>
                <button type="button" class="remove-btn" onclick="removeEducation(this)">حذف المؤهل</button>
            `;
            educationsDiv.appendChild(newEducation);
        }

        // حذف تعليم
        function removeEducation(button) {
            button.parentElement.remove();
            updatePreview();
        }

        // إضافة مهارة جديدة
        function addSkill() {
            const skillsContainer = document.getElementById('skills-container');
            const newSkill = document.createElement('div');
            newSkill.className = 'skill-item';
            newSkill.innerHTML = `
                <input type="text" class="skill-input" placeholder="المهارة (مثال: HTML, CSS, JavaScript)">
                <select class="skill-level">
                    <option value="">مستوى المهارة</option>
                    <option value="مبتدئ">مبتدئ</option>
                    <option value="متوسط">متوسط</option>
                    <option value="متقدم">متقدم</option>
                    <option value="خبير">خبير</option>
                </select>
                <button type="button" class="remove-btn" onclick="removeSkill(this)">حذف</button>
            `;
            skillsContainer.appendChild(newSkill);
        }

        // حذف مهارة
        function removeSkill(button) {
            button.parentElement.remove();
            updatePreview();
        }

        // حفظ السيرة الذاتية
        function saveCV() {
            const cvData = {
                personalInfo: {
                    name: document.getElementById('name').value,
                    email: document.getElementById('email').value,
                    phone: document.getElementById('phone').value,
                    jobTitle: document.getElementById('jobTitle').value,
                    location: document.getElementById('location').value,
                    summary: document.getElementById('summary').value
                },
                experiences: [],
                education: [],
                skills: [],
                additional: {
                    languages: document.getElementById('languages').value,
                    certifications: document.getElementById('certifications').value,
                    projects: document.getElementById('projects').value
                }
            };

            // جمع الخبرات
            document.querySelectorAll('.experience-item').forEach(item => {
                cvData.experiences.push({
                    title: item.querySelector('.exp-title').value,
                    company: item.querySelector('.exp-company').value,
                    period: item.querySelector('.exp-period').value,
                    description: item.querySelector('.exp-description').value
                });
            });

            // جمع التعليم
            document.querySelectorAll('.education-item').forEach(item => {
                cvData.education.push({
                    degree: item.querySelector('.edu-degree').value,
                    institution: item.querySelector('.edu-institution').value,
                    period: item.querySelector('.edu-period').value,
                    details: item.querySelector('.edu-details').value
                });
            });

            // جمع المهارات
            document.querySelectorAll('.skill-item').forEach(item => {
                const skillInput = item.querySelector('.skill-input');
                const skillLevel = item.querySelector('.skill-level').value;
                if (skillInput.value.trim()) {
                    cvData.skills.push({
                        name: skillInput.value.trim(),
                        level: skillLevel
                    });
                }
            });

            // حفظ في localStorage
            localStorage.setItem('cvData', JSON.stringify(cvData));
            
            // إنشاء ملف JSON للتحميل
            const dataStr = "data:text/json;charset=utf-8," + encodeURIComponent(JSON.stringify(cvData, null, 2));
            const downloadAnchorNode = document.createElement('a');
            downloadAnchorNode.setAttribute("href", dataStr);
            downloadAnchorNode.setAttribute("download", "سيرتي_الذاتية.json");
            document.body.appendChild(downloadAnchorNode);
            downloadAnchorNode.click();
            downloadAnchorNode.remove();
            
            alert('تم حفظ السيرة الذاتية بنجاح! وتم تحميل ملف JSON.');
        }

        // استيراد سيرة ذاتية من ملف JSON
        function importCV() {
            const fileInput = document.createElement('input');
            fileInput.type = 'file';
            fileInput.accept = '.json';
            fileInput.onchange = e => {
                const file = e.target.files[0];
                const reader = new FileReader();
                reader.onload = function(event) {
                    try {
                        const cvData = JSON.parse(event.target.result);
                        loadCVData(cvData);
                        alert('تم استيراد السيرة الذاتية بنجاح!');
                    } catch (error) {
                        alert('خطأ في تحميل الملف. يرجى التأكد من صحة تنسيق الملف.');
                    }
                };
                reader.readAsText(file);
            };
            fileInput.click();
        }

        // تحميل بيانات السيرة الذاتية
        function loadCVData(cvData) {
            // تعبئة البيانات الشخصية
            document.getElementById('name').value = cvData.personalInfo.name || '';
            document.getElementById('email').value = cvData.personalInfo.email || '';
            document.getElementById('phone').value = cvData.personalInfo.phone || '';
            document.getElementById('jobTitle').value = cvData.personalInfo.jobTitle || '';
            document.getElementById('location').value = cvData.personalInfo.location || '';
            document.getElementById('summary').value = cvData.personalInfo.summary || '';
            
            // تعبئة الخبرات
            const experiencesDiv = document.getElementById('experiences');
            experiencesDiv.innerHTML = '';
            cvData.experiences.forEach(exp => {
                const newExperience = document.createElement('div');
                newExperience.className = 'experience-item';
                newExperience.innerHTML = `
                    <input type="text" class="exp-title" placeholder="المسمى الوظيفي" value="${exp.title || ''}">
                    <input type="text" class="exp-company" placeholder="اسم الشركة" value="${exp.company || ''}">
                    <input type="text" class="exp-period" placeholder="الفترة الزمنية" value="${exp.period || ''}">
                    <textarea class="exp-description" placeholder="المسؤوليات والإنجازات" rows="3">${exp.description || ''}</textarea>
                    <button type="button" class="remove-btn" onclick="removeExperience(this)">حذف الخبرة</button>
                `;
                experiencesDiv.appendChild(newExperience);
            });
            
            // تعبئة التعليم
            const educationsDiv = document.getElementById('educations');
            educationsDiv.innerHTML = '';
            cvData.education.forEach(edu => {
                const newEducation = document.createElement('div');
                newEducation.className = 'education-item';
                newEducation.innerHTML = `
                    <input type="text" class="edu-degree" placeholder="المؤهل الدراسي" value="${edu.degree || ''}">
                    <input type="text" class="edu-institution" placeholder="اسم المؤسسة التعليمية" value="${edu.institution || ''}">
                    <input type="text" class="edu-period" placeholder="سنة التخرج" value="${edu.period || ''}">
                    <textarea class="edu-details" placeholder="التفاصيل الإضافية" rows="2">${edu.details || ''}</textarea>
                    <button type="button" class="remove-btn" onclick="removeEducation(this)">حذف المؤهل</button>
                `;
                educationsDiv.appendChild(newEducation);
            });
            
            // تعبئة المهارات
            const skillsContainer = document.getElementById('skills-container');
            skillsContainer.innerHTML = '';
            cvData.skills.forEach(skill => {
                const newSkill = document.createElement('div');
                newSkill.className = 'skill-item';
                newSkill.innerHTML = `
                    <input type="text" class="skill-input" placeholder="المهارة" value="${skill.name || ''}">
                    <select class="skill-level">
                        <option value="">مستوى المهارة</option>
                        <option value="مبتدئ" ${skill.level === 'مبتدئ' ? 'selected' : ''}>مبتدئ</option>
                        <option value="متوسط" ${skill.level === 'متوسط' ? 'selected' : ''}>متوسط</option>
                        <option value="متقدم" ${skill.level === 'متقدم' ? 'selected' : ''}>متقدم</option>
                        <option value="خبير" ${skill.level === 'خبير' ? 'selected' : ''}>خبير</option>
                    </select>
                    <button type="button" class="remove-btn" onclick="removeSkill(this)">حذف</button>
                `;
                skillsContainer.appendChild(newSkill);
            });
            
            // تعبئة المعلومات الإضافية
            document.getElementById('languages').value = cvData.additional.languages || '';
            document.getElementById('certifications').value = cvData.additional.certifications || '';
            document.getElementById('projects').value = cvData.additional.projects || '';
            
            // تحديث المعاينة
            updatePreview();
        }

        // تحليل ملف السيرة الذاتية المرفوع (محاكاة)
        function analyzeUploadedCV(file) {
            document.getElementById('uploadAlert').style.display = 'block';
            document.getElementById('analysisResult').style.display = 'none';
            document.getElementById('aiSuggestions').style.display = 'none';
            
            setTimeout(() => {
                // محاكاة لنتيجة التحليل
                const missingSections = [
                    'المعلومات الشخصية غير مكتملة',
                    'لا توجد مهارات تقنية محددة',
                    'يفتقر إلى ملخص احترافي',
                    'يمكن إضافة المزيد من التفاصيل في الخبرات العملية'
                ];
                
                const missingSectionsDiv = document.getElementById('missingSections');
                missingSectionsDiv.innerHTML = '';
                
                missingSections.forEach(section => {
                    const missingItem = document.createElement('div');
                    missingItem.className = 'missing-item';
                    missingItem.innerHTML = `<i class="fas fa-exclamation-circle"></i> ${section}`;
                    missingSectionsDiv.appendChild(missingItem);
                });
                
                document.getElementById('analysisResult').style.display = 'block';
                
                // محاكاة لتحميل بعض البيانات من الملف
                document.getElementById('name').value = 'محمد أحمد';
                document.getElementById('jobTitle').value = 'مطور ويب';
                
                // إخفاء رسالة التحميل بعد التحليل
                setTimeout(() => {
                    document.getElementById('uploadAlert').style.display = 'none';
                    updatePreview();
                }, 2000);
                
            }, 2000);
        }

        // الحصول على اقتراحات الذكاء الاصطناعي
        function getAISuggestions() {
            document.getElementById('aiSuggestions').style.display = 'block';
            const suggestionsList = document.getElementById('suggestionsList');
            suggestionsList.innerHTML = '';
            
            // اقتراحات محاكاة
            const suggestions = [
                'يمكنك إضافة ملخص احترافي يوضح خبراتك وأهدافك المهنية',
                'حاول إضافة المزيد من التفاصيل حول إنجازاتك في الخبرات العملية',
                'أضف مستويات لمهاراتك لتوضيح درجة إتقانك لها',
                'فكر في إضافة معلومات عن المشاريع الشخصية التي قمت بها'
            ];
            
            suggestions.forEach(suggestion => {
                const suggestionItem = document.createElement('div');
                suggestionItem.className = 'suggestion-item';
                suggestionItem.textContent = suggestion;
                suggestionsList.appendChild(suggestionItem);
            });
        }

        // تطبيق اقتراحات الذكاء الاصطناعي
        function applyAISuggestions() {
            // تطبيق اقتراحات محاكاة
            if (!document.getElementById('summary').value) {
                document.getElementById('summary').value = 'مطور ويب متخصص في إنشاء تطبيقات ويب تفاعلية باستخدام أحدث التقنيات. أسعى للانضمام إلى فريق عمل ديناميكي حيث يمكنني المساهمة بمهاراتي وتطوير خبراتي المهنية.';
            }
            
            // إضافة مهارة إذا لم تكن موجودة
            const skills = document.querySelectorAll('.skill-input');
            let hasWebSkills = false;
            skills.forEach(skill => {
                if (skill.value.toLowerCase().includes('html') || skill.value.toLowerCase().includes('css') || skill.value.toLowerCase().includes('javascript')) {
                    hasWebSkills = true;
                }
            });
            
            if (!hasWebSkills) {
                addSkill();
                const newSkill = document.querySelector('#skills-container .skill-item:last-child .skill-input');
                newSkill.value = 'HTML, CSS, JavaScript';
                const newSkillLevel = document.querySelector('#skills-container .skill-item:last-child .skill-level');
                newSkillLevel.value = 'متقدم';
            }
            
            updatePreview();
            alert('تم تطبيق الاقتراحات بنجاح!');
            document.getElementById('aiSuggestions').style.display = 'none';
        }

        // تحميل PDF باستخدام jsPDF
        function generatePDF() {
            const { jsPDF } = window.jspdf;
            const doc = new jsPDF();
            
            // إظهار رسالة تحميل
            alert("جاري تحضير السيرة الذاتية للتحميل...");
            
            // استخدام html2canvas لالتقاط المحتوى
            const element = document.getElementById('cvPreview');
            
            html2canvas(element, {
                scale: 2, // زيادة الدقة
                useCORS: true,
                logging: false
            }).then(canvas => {
                const imgData = canvas.toDataURL('image/png');
                const imgWidth = doc.internal.pageSize.getWidth();
                const pageHeight = doc.internal.pageSize.getHeight();
                const imgHeight = canvas.height * imgWidth / canvas.width;
                let heightLeft = imgHeight;
                let position = 0;
                
                // إضافة الصورة الأولى
                doc.addImage(imgData, 'PNG', 0, position, imgWidth, imgHeight);
                heightLeft -= pageHeight;
                
                // إضافة صفحات إضافية إذا لزم الأمر
                while (heightLeft >= 0) {
                    position = heightLeft - imgHeight;
                    doc.addPage();
                    doc.addImage(imgData, 'PNG', 0, position, imgWidth, imgHeight);
                    heightLeft -= pageHeight;
                }
                
                // حفظ الملف
                doc.save('سيرتي_الذاتية.pdf');
            }).catch(error => {
                console.error('Error generating PDF:', error);
                alert('حدث خطأ أثناء إنشاء ملف PDF. يرجى المحاولة مرة أخرى.');
            });
        }

        // اختيار القالب
        document.querySelectorAll('.template-option').forEach(option => {
            option.addEventListener('click', function() {
                document.querySelectorAll('.template-option').forEach(opt => {
                    opt.classList.remove('active');
                });
                this.classList.add('active');
                
                // تغيير تنسيق المعاينة حسب القالب المختار
                const template = this.getAttribute('data-template');
                const preview = document.getElementById('cvPreview');
                
                // إزالة جميع كلاسات القوالب
                preview.classList.remove('modern-template', 'professional-template', 'creative-template');
                
                // إضافة كلاس القالب المختار
                preview.classList.add(template + '-template');
                
                // تغيير الألوان حسب القالب
                if (template === 'modern') {
                    preview.style.borderLeft = '5px solid #3498db';
                } else if (template === 'professional') {
                    preview.style.borderLeft = '5px solid #2c3e50';
                } else if (template === 'creative') {
                    preview.style.borderLeft = '5px solid #e74c3c';
                }
            });
        });

        // التمرير السلس للروابط
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth'
                    });
                }
            });
        });

        // تحميل البيانات المحفوظة عند بدء التحميل
        document.addEventListener('DOMContentLoaded', function() {
            const savedCV = localStorage.getItem('cvData');
            if (savedCV) {
                const cvData = JSON.parse(savedCV);
                loadCVData(cvData);
            }
            
            // إعداد رفع الملف
            document.getElementById('fileInput').addEventListener('change', function(e) {
                const file = e.target.files[0];
                if (file) {
                    analyzeUploadedCV(file);
                }
            });
            
            // تحديث الاكتمال عند التحميل
            updateCompleteness();
            
            // إعداد اختيار اللغة
            document.getElementById('languageSelect').addEventListener('change', function() {
                const lang = this.value;
                changeLanguage(lang);
            });
            
            // تعيين اللغة الافتراضية
            changeLanguage('ar');
        });
    </script>
</body>
</html>
