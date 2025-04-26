# cv-website
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>السيرة الذاتية</title>
  <link rel="stylesheet" href="css/style.css">

  <style>
    body {
      font-family: 'Tahoma', sans-serif;
      direction: rtl;
      background-color: #f9f9f9;
      padding: 20px;
    }

    h1 {
      color: #004466;
    }

    .cv-section {
      background-color: #ffffff;
      border: 1px solid #ddd;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 5px;
    }

    .cv-section h3 {
      margin-top: 0;
      color: #006699;
    }

    .download-btn {
      background-color: #004466;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .download-btn:hover {
      background-color: #006699;
    }
  </style>
</head>

<body>

  <h1>السيرة الذاتية</h1>

  <div class="cv-section">
    <h3>الهدف المهني</h3>
    <p>أسعى للعمل في بيئة تقنية تتيح لي تطوير مهاراتي في تطوير الويب والمساهمة في مشاريع حقيقية وفعالة.</p>
  </div>

  <div class="cv-section">
    <h3>الخبرات</h3>
    <ul>
      <li>تدريب صيفي في شركة XYZ – تطوير صفحات ويب تفاعلية</li>
      <li>مشروع تخرّج: تصميم موقع خدمات طلابية باستخدام HTML/CSS/JS</li>
    </ul>
  </div>

  <div class="cv-section">
    <h3>المهارات التقنية</h3>
    <ul>
      <li>إتقان HTML5, CSS3, JavaScript</li>
      <li>تصميم متجاوب (Responsive Design)</li>
      <li>استخدام Git وGitHub</li>
    </ul>
  </div>

  <div class="cv-section">
    <h3>تحميل السيرة الذاتية PDF</h3>
    <a href="assets/resume.pdf" download>
      <button class="download-btn">تحميل السيرة الذاتية</button>
    </a>
  </div>

  <a class="back-home" href="index.html">العودة للرئيسية</a>

</body>
</html>
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>مشاريعي</title>
  <link rel="stylesheet" href="css/style.css">

  <style>
    body {
      font-family: 'Cairo', sans-serif;
      direction: rtl;
      background-color: #f5f5f5;
      padding: 20px;
    }

    h1 {
      color: #004466;
      text-align: center;
      margin-bottom: 30px;
    }

    .projects-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .project-card {
      background-color: white;
      border: 1px solid #ccc;
      border-radius: 10px;
      width: 300px;
      padding: 15px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .project-card h3 {
      margin-top: 0;
      color: #006699;
    }

    .project-card p {
      font-size: 14px;
      color: #333;
    }

    .project-card button {
      margin-top: 10px;
      background-color: #004466;
      color: white;
      padding: 8px 12px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .project-card button:hover {
      background-color: #006699;
    }
  </style>
</head>

<body>

  <h1>مشاريعي</h1>

  <div class="projects-container">

    <!-- مشروع 1 -->
    <div class="project-card">
      <h3>موقع خدمات طلابية</h3>
      <p>موقع إلكتروني يقدم خدمات تعليمية مثل الجدول الدراسي، رفع المهام، وغيرها.</p>
      <button onclick="window.open('https://github.com/username/project1', '_blank')">عرض على GitHub</button>
    </div>

    <!-- مشروع 2 -->
    <div class="project-card">
      <h3>نظام تسجيل طلاب</h3>
      <p>نظام بسيط لتسجيل الطلاب باستخدام واجهة HTML/CSS مع تخزين البيانات.</p>
      <button onclick="window.open('https://github.com/username/project2', '_blank')">عرض على GitHub</button>
    </div>

    <!-- مشروع 3 -->
    <div class="project-card">
      <h3>حساب الآلة</h3>
      <p>تطبيق آلة حاسبة باستخدام JavaScript وتفاعل المستخدم مع الواجهة مباشرة.</p>
      <button onclick="window.open('https://github.com/username/project3', '_blank')">عرض على GitHub</button>
    </div>

  </div>

  <a class="back-home" href="index.html">العودة للرئيسية</a>

</body>
</html>
