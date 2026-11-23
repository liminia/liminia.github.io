<div align="center">
  <style>
    .project-card {
      width: 260px;
      padding: 20px;
      border-radius: 12px;
      background: #f6f8fa;
      border: 1px solid #d0d7de;
      text-decoration: none !important;
      color: inherit !important;
      display: inline-block;
      vertical-align: top;
      margin: 10px;
      transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
    }
    .project-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 8px 16px rgba(0,0,0,0.1);
      border-color: #0969da;
    }
    .project-card h3 {
      margin-top: 0;
      color: #0969da;
      font-size: 18px;
    }
    .project-card p {
      font-size: 14px;
      color: #57606a;
      line-height: 1.5;
      margin-bottom: 15px;
    }
    .project-card .link-text {
      font-size: 13px;
      color: #0969da;
      font-weight: 600;
    }
    /* پشتیبانی از حالت تاریک (Dark Mode) گیتهاب */
    @media (prefers-color-scheme: dark) {
      .project-card {
        background: #161b22;
        border-color: #30363d;
      }
      .project-card p {
        color: #8b949e;
      }
      .project-card:hover {
        box-shadow: 0 8px 16px rgba(0,0,0,0.4);
        border-color: #58a6ff;
      }
      .project-card h3, .project-card .link-text {
        color: #58a6ff;
      }
    }
  </style>

  <h1>سلام! 👋 من لیمینیا هستم</h1>
  <p style="color: #57606a; max-width: 600px; margin: 0 auto 30px auto; font-size: 16px;">توسعه‌دهنده وب و خالق ابزارهای کاربردی، سبک و سریع</p>
  
  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 16px; max-width: 900px; margin: 0 auto;">
    
    <!-- پروژه اول -->
    <a href="https://liminia.github.io/Summary/" class="project-card" target="_blank">
      <h3>📝 خلاصه‌ساز متن</h3>
      <p>ابزاری برای فشرده‌سازی و تولید خلاصه ساختاریافته از متن‌ها به صورت آنی.</p>
      <span class="link-text">مشاهده پروژه ←</span>
    </a>

    <!-- پروژه دوم -->
    <a href="https://liminia.github.io/icon/" class="project-card" target="_blank">
      <h3>🎨 کتابخانه آیکون</h3>
      <p>دسترسی سریع به بیش از ۸۹۰۰ آیکون دسته‌بندی‌شده با خروجی SVG و PNG.</p>
      <span class="link-text">مشاهده پروژه ←</span>
    </a>

    <!-- پروژه سوم -->
    <a href="https://liminia.github.io/edit/" class="project-card" target="_blank">
      <h3>🖼️ ویرایشگر تصویر</h3>
      <p>ویرایشگر تصویر سبک و سریع که پردازش را به‌طور کامل روی دستگاه کاربر انجام می‌دهد.</p>
      <span class="link-text">مشاهده پروژه ←</span>
    </a>

  </div>
</div>
