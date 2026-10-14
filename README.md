# My-portfolio-
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>أميرة محمد | مطوّرة واجهات</title>
  <meta name="description" content="الموقع الشخصي لأميرة محمد: السيرة الذاتية والمهارات وأعمال برمجية.">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.rtl.min.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Reem+Kufi:wght@600;700&family=Tajawal:wght@400;500;700&display=swap" rel="stylesheet">
  <link href="css/style.css" rel="stylesheet">
</head>
<body data-bs-spy="scroll" data-bs-target="#mainNav" data-bs-root-margin="-30% 0px -60% 0px" tabindex="0">

<!-- شريط التنقل -->
<nav id="mainNav" class="navbar navbar-expand-md sticky-top site-nav">
  <div class="container">
    <a class="navbar-brand" href="#top">أميرة محمد</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menu" aria-controls="menu" aria-expanded="false" aria-label="فتح القائمة">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="menu">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#about">نبذة</a></li>
        <li class="nav-item"><a class="nav-link" href="#skills">المهارات</a></li>
        <li class="nav-item"><a class="nav-link" href="#projects">الأعمال</a></li>
        <li class="nav-item"><a class="nav-link" href="#resume">السيرة</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">تواصل</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- المقدمة -->
<header id="top" class="hero">
  <div class="container">
    <div class="row align-items-center g-5">
      <div class="col-lg-7">
        <p class="hero-kicker">طالبة تطوير ويب · متاحة للتدريب</p>
        <h1 class="hero-title">أبني واجهات <br>واضحة وسريعة <br>وسهلة الاستخدام.</h1>
        <p class="hero-text">أنا أميرة محمد، أدرس نظم المعلومات وأتخصص في تطوير الواجهات الأمامية، وأحب تحويل الأفكار إلى صفحات منظمة تعمل بسلاسة على الكمبيوتر والهاتف.</p>
        <div class="d-flex flex-wrap gap-2">
          <a href="#projects" class="btn btn-accent btn-lg">شاهد أعمالي</a>
          <a href="#contact" class="btn btn-outline-ink btn-lg">تواصل معي</a>
        </div>
      </div>
      <div class="col-lg-5 text-center">
        <!-- استبدل الدائرة بصورتك: <img src="img/me.jpg" class="avatar" alt="صورة أميرة محمد"> -->
        <div class="avatar" role="img" aria-label="صورة شخصية">أ</div>
      </div>
    </div>
  </div>
</header>

<main>
  <!-- نبذة -->
  <section id="about" class="section">
    <div class="container">
      <h2 class="section-title">نبذة عني</h2>
      <div class="row g-4">
        <div class="col-lg-7">
          <p class="lead-text">طالبة في معهد الدلتا العالي للنظم والمعلومات، بدأت رحلتي مع البرمجة بتعلم HTML وCSS، وأطبّق ما أتعلمه في مشاريع صغيرة.</p>
          <p>أهتم بكتابة كود نظيف ومرتب، وبتصميم صفحات تتكيّف مع كل أحجام الشاشات. أبحث الآن عن فرصة تدريب لأطوّر خبرتي العملية.</p>
        </div>
        <div class="col-lg-5">
          <ul class="info-list">
            <li><span>الموقع</span> مصر</li>
            <li><span>الدراسة</span> نظم ومعلومات</li>
            <li><span>اللغات</span> العربية، الإنجليزية</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- المهارات -->
  <section id="skills" class="section section-tint">
    <div class="container">
      <h2 class="section-title">المهارات</h2>
      <div class="row g-4">
        <div class="col-md-6">
          <h3 class="h5 mb-3">تقنية</h3>
          <div class="skill"><div class="skill-head"><span>HTML5</span><span>90%</span></div>
            <div class="progress" role="progressbar" aria-label="HTML5" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100"><div class="progress-bar" style="width:90%"></div></div></div>
          <div class="skill"><div class="skill-head"><span>CSS3</span><span>85%</span></div>
            <div class="progress" role="progressbar" aria-label="CSS3" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100"><div class="progress-bar" style="width:85%"></div></div></div>
          <div class="skill"><div class="skill-head"><span>Bootstrap</span><span>80%</span></div>
            <div class="progress" role="progressbar" aria-label="Bootstrap" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100"><div class="progress-bar" style="width:80%"></div></div></div>
          <div class="skill"><div class="skill-head"><span>Git و GitHub</span><span>70%</span></div>
            <div class="progress" role="progressbar" aria-label="Git و GitHub" aria-valuenow="70" aria-valuemin="0" aria-valuemax="100"><div class="progress-bar" style="width:70%"></div></div></div>
        </div>
        <div class="col-md-6">
          <h3 class="h5 mb-3">شخصية</h3>
          <div class="d-flex flex-wrap gap-2">
            <span class="chip">العمل الجماعي</span>
            <span class="chip">حل المشكلات</span>
            <span class="chip">إدارة الوقت</span>
            <span class="chip">التعلّم الذاتي</span>
            <span class="chip">الاهتمام بالتفاصيل</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- الأعمال -->
  <section id="projects" class="section">
    <div class="container">
      <h2 class="section-title">سابقة الأعمال</h2>
      <div class="row g-4">
        <div class="col-md-6 col-lg-4">
          <article class="project">
            <div class="project-thumb t1">صفحة هبوط</div>
            <div class="project-body">
              <h3 class="h5">موقع مقهى</h3>
              <p>صفحة هبوط متجاوبة لمقهى محلي، تعرض القائمة والموقع وساعات العمل.</p>
              <p class="tags"><span>HTML</span><span>CSS</span><span>Bootstrap</span></p>
            </div>
          </article>
        </div>
        <div class="col-md-6 col-lg-4">
          <article class="project">
            <div class="project-thumb t2">قائمة مهام</div>
            <div class="project-body">
              <h3 class="h5">تطبيق قائمة المهام</h3>
              <p>تطبيق بسيط لإضافة المهام وإنجازها، بتصميم نظيف يعمل على الهاتف.</p>
              <p class="tags"><span>HTML</span><span>CSS</span><span>JavaScript</span></p>
            </div>
          </article>
        </div>
        <div class="col-md-6 col-lg-4">
          <article class="project">
            <div class="project-thumb t3">معرض صور</div>
            <div class="project-body">
              <h3 class="h5">معرض صور متجاوب</h3>
              <p>شبكة صور تتغير أعمدتها حسب حجم الشاشة باستخدام نظام الشبكة في Bootstrap.</p>
              <p class="tags"><span>HTML</span><span>Bootstrap</span></p>
            </div>
          </article>
        </div>
      </div>
    </div>
  </section>

  <!-- السيرة -->
  <section id="resume" class="section section-tint">
    <div class="container">
      <h2 class="section-title">التعليم والخبرة</h2>
      <ol class="timeline">
        <li><span class="when">2022 – 2027</span><h3 class="h5">معهد الدلتا العالي للنظم والمعلومات</h3><p>دراسة نظم المعلومات والبرمجة.</p></li>
        <li><span class="when">2025</span><h3 class="h5">دورة تطوير الواجهات الأمامية</h3><p>HTML وCSS وBootstrap، مع مشروع تطبيقي.</p></li>
        <li><span class="when">2025</span><h3 class="h5">مشروع تطوعي</h3><p>بناء موقع تعريفي لمبادرة طلابية.</p></li>
      </ol>
    </div>
  </section>

  <!-- التواصل -->
  <section id="contact" class="section">
    <div class="container">
      <h2 class="section-title">تواصل معي</h2>
      <div class="row g-4">
        <div class="col-lg-5">
          <p>يسعدني التواصل بخصوص التدريب أو أي فرصة تعاون.</p>
          <ul class="info-list">
            <li><span>البريد</span> <a href="mailto:amiramohammed767@gmail.com">amiramohammed767@gmail.com</a></li>
            <li><span>LinkedIn</span> <a href="https://www.linkedin.com/in/amira-mohammed-500328288" target="_blank" rel="noopener">linkedin.com/in/amira-mohammed-500328288</a></li>
          </ul>
        </div>
        <div class="col-lg-7">
          <form action="mailto:amiramohammed767@gmail.com" method="post" enctype="text/plain" class="contact-form">
            <div class="mb-3"><label for="name" class="form-label">الاسم</label><input type="text" class="form-control" id="name" name="name" required></div>
            <div class="mb-3"><label for="email" class="form-label">البريد الإلكتروني</label><input type="email" class="form-control" id="email" name="email" required></div>
            <div class="mb-3"><label for="msg" class="form-label">الرسالة</label><textarea class="form-control" id="msg" name="message" rows="4" required></textarea></div>
            <button type="submit" class="btn btn-accent">أرسل الرسالة</button>
          </form>
        </div>
      </div>
    </div>
  </section>
</main>

<footer class="site-footer">
  <div class="container">© 2026 أميرة محمد المتولي محمد. جميع الحقوق محفوظة.</div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
based 
