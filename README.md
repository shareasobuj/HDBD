HDBD

<html lang="bn">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Human Development — HDBD (hdbd.com)</title>
  <meta name="description" content="Human Development — তথ্য, প্রোগ্রাম, গবেষণা ও অংশগ্রহণ।" />
  <style>
    /* ========== Reset & base ========== */
    :root{
      --primary:#0b6b6f; /* teal */
      --accent:#ffb703; /* warm */
      --muted:#6b7280;
      --bg:#f7fafc;
      --card:#ffffff;
      --maxw:1100px;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Noto Sans", "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;background:var(--bg);color:#0f172a}
    a{color:inherit;text-decoration:none}
    img{max-width:100%;display:block}
    .container{max-width:var(--maxw);margin:0 auto;padding:1rem}

    /* ========== Header ========== */
    header{background:linear-gradient(90deg,var(--primary),#064e52);color:white}
    .topbar{display:flex;align-items:center;justify-content:space-between;padding:0.75rem 1rem}
    .brand{display:flex;gap:.75rem;align-items:center}
    .logo{width:48px;height:48px;border-radius:8px;background:linear-gradient(135deg,#fff4,rgba(255,255,255,0.08));display:flex;align-items:center;justify-content:center;font-weight:700}
    .brand h1{font-size:1.05rem;margin:0}
    nav{display:flex;gap:1rem;align-items:center}
    .nav-links{display:flex;gap:.5rem}
    .btn{background:var(--accent);color:#042029;padding:.5rem .8rem;border-radius:8px;font-weight:600}

    /* mobile menu */
    .menu-toggle{display:none;background:transparent;border:0;color:white;font-size:1.05rem}

    /* ========== Hero ========== */
    .hero{padding:2.25rem 0}
    .hero-grid{display:grid;grid-template-columns:1fr 380px;gap:1.25rem;align-items:center}
    .hero-card{background:linear-gradient(180deg, rgba(255,255,255,.04), rgba(255,255,255,.02));padding:1.5rem;border-radius:12px;box-shadow:0 6px 18px rgba(6,8,15,0.08)}
    .kpi{display:flex;gap:1rem}
    .kpi .item{flex:1;background:var(--card);padding:.75rem;border-radius:10px;text-align:center}

    /* ========== Sections ========== */
    section{padding:2rem 0}
    h2.section-title{margin:0 0 1rem 0;font-size:1.25rem}
    .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:1rem}
    .card{background:var(--card);padding:1rem;border-radius:10px;box-shadow:0 6px 18px rgba(11,16,20,0.04)}

    /* news list */
    .news-list{display:flex;flex-direction:column;gap:.75rem}
    .news-item{display:flex;gap:.75rem;align-items:center}
    .news-thumb{width:96px;height:64px;border-radius:8px;background:linear-gradient(135deg,var(--primary),#0d807f);flex-shrink:0}

    /* footer */
    footer{padding:1.5rem 0;color:var(--muted);font-size:.95rem}

    /* responsiveness */
    @media (max-width:900px){
      .hero-grid{grid-template-columns:1fr}
      .grid-3{grid-template-columns:repeat(2,1fr)}
      nav{display:none}
      .menu-toggle{display:block}
    }
    @media (max-width:560px){
      .grid-3{grid-template-columns:1fr}
      .brand h1{font-size:.95rem}
      .hero{padding:1rem 0}
    }

    /* small utilities */
    .muted{color:var(--muted)}
    .center{text-align:center}
    .pill{display:inline-block;padding:.25rem .5rem;border-radius:999px;background:rgba(255,255,255,0.06);font-weight:600}
    .search{display:flex;gap:.5rem;align-items:center;background:var(--card);padding:.5rem;border-radius:10px}
    input[type="search"]{border:0;outline:0;font-size:0.95rem}

    /* programs accordion */
    .accordion .head{display:flex;justify-content:space-between;cursor:pointer;padding:.6rem;border-radius:8px}
    .accordion .content{padding:.6rem 0;display:none}
    .accordion .open .content{display:block}
  </style>
</head>
<body>
  <header>
    <div class="topbar container">
      <div class="brand">
        <div class="logo" aria-hidden>
          <svg width="28" height="28" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect width="24" height="24" rx="5" fill="white" opacity="0.06"/>
            <path d="M6 12h12M8 8h8M8 16h6" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </div>
        <div>
          <h1>Human Development <small class="muted">(HDBD)</small></h1>
          <div class="muted" style="font-size:.85rem">hdbd.com — মান উন্নয়ন তথ্য ও প্রোগ্রাম</div>
        </div>
      </div>

      <nav aria-label="প্রধান নেভিগেশন">
        <div class="nav-links">
          <a href="#about" class="muted">About</a>
          <a href="#programs" class="muted">Programs</a>
          <a href="#news" class="muted">News</a>
          <a href="#resources" class="muted">Resources</a>
          <a href="#contact" class="muted">Contact</a>
        </div>
        <a class="btn" href="#get-involved">Get Involved</a>
      </nav>

      <button class="menu-toggle" id="menuToggle" aria-expanded="false">☰</button>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container hero-grid">
        <div class="hero-card">
          <h2 style="margin-top:0">মানব উন্নয়ন: তথ্য, প্রোগ্রাম, অংশগ্রহণ</h2>
          <p class="muted">HDBD (Human Development Bangladesh) দেশের বিভিন্ন সামাজিক, অর্থনৈতিক ও স্বাস্থ্যসংশ্লিষ্ট সূচক উন্নয়নে কাজ করে। এখানে প্রোগ্রাম, গবেষণা, খবর এবং অংশগ্রহণের সুযোগ পাবেন।</p>

          <div style="margin-top:1rem" class="kpi">
            <div class="item">
              <div style="font-size:1.15rem;font-weight:700">120+</div>
              <div class="muted" style="font-size:.85rem">প্রকল্প</div>
            </div>
            <div class="item">
              <div style="font-size:1.15rem;font-weight:700">450k</div>
              <div class="muted" style="font-size:.85rem">লাভভোগী</div>
            </div>
            <div class="item">
              <div style="font-size:1.15rem;font-weight:700">25</div>
              <div class="muted" style="font-size:.85rem">জেলা কভারেজ</div>
            </div>
          </div>

          <div style="display:flex;gap:.5rem;margin-top:1rem">
            <a class="btn" href="#programs">Our Programs</a>
            <a class="muted" href="#news" style="align-self:center;padding:.5rem .6rem">Latest News</a>
          </div>
        </div>

        <aside class="hero-card">
          <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:.75rem">
            <strong>Quick Links</strong>
            <span class="pill">Citizen Portal</span>
          </div>
          <div style="display:flex;flex-direction:column;gap:.5rem">
            <a class="card" href="#">Program Dashboard</a>
            <a class="card" href="#">Data & Research</a>
            <a class="card" href="#">Volunteer</a>
            <a class="card" href="#">Donate</a>
          </div>
        </aside>
      </div>
    </section>

    <section id="about" class="container">
      <h2 class="section-title">আমাদের সম্পর্কে</h2>
      <div class="card">
        <p class="muted">Human Development (HDBD) প্রতিষ্ঠিত হয়েছে মানুষের জীবনমান উন্নত করার লক্ষ্যে—শিক্ষা, স্বাস্থ্য, সামাজিক নিরাপত্তা ও আর্থিক সক্ষমতা বৃদ্ধির মাধ্যমে। আমরা গভীর গবেষণা করে নীতিমালা প্রণয়ন, প্রোগ্রাম বাস্তবায়ন ও কমিউনিটি অংশগ্রহণ নিশ্চিত করি।</p>
      </div>
    </section>

    <section id="programs" class="container">
      <h2 class="section-title">প্রোগ্রামসমূহ</h2>
      <div class="grid-3">
        <div class="card">
          <h3>শিক্ষা ও দক্ষতা উন্নয়ন</h3>
          <p class="muted">স্কিল ট্রেনিং, কম্পিউটার শিক্ষা এবং মধ্যবিত্ত কাজের সুযোগ তৈরিতে উদ্যোগ।</p>
        </div>
        <div class="card">
          <h3>স্বাস্থ্য ও নিউট্রিশন</h3>
          <p class="muted">প্রাথমিক স্বাস্থ্য সেবা, মাতৃদুগ্ধ বৃদ্ধি, টিকাদান ক্যাম্পেইন ও পুষ্টি সম্পর্কিত কর্মসূচি।</p>
        </div>
        <div class="card">
          <h3>সামাজিক নিরাপত্তা</h3>
          <p class="muted">দারিদ্র্য লঘুকরণ, ক্ষুদ্র ঋণ ও সমবায় দলের মাধ্যমে অর্থনৈতিক স্থিতিশীলতা।</p>
        </div>
      </div>

      <div style="margin-top:1rem" class="card">
        <h3 style="margin-top:0">প্রোগ্রাম বিবরণ (একটি অ্যাকর্ডিয়ন উদাহরণ)</h3>
        <div class="accordion">
          <div class="item">
            <div class="head" data-idx="1">
              <strong>শিক্ষা প্রকল্প: কমিউনিটি কম্পিউটার ল্যাব</strong>
              <span class="muted">+</span>
            </div>
            <div class="content">কমিউনিটি পর্যায়ে কম্পিউটার ল্যাব প্রতিষ্ঠা করে কিশোর-কিশোরী ও বয়স্কদের ডিজিটাল দক্ষতা বাড়ানো হবে।</div>
          </div>
          <div class="item">
            <div class="head" data-idx="2">
              <strong>স্বাস্থ্য ক্যাম্প: মাতৃত্ব ও শিশু পরিচর্যা</strong>
              <span class="muted">+</span>
            </div>
            <div class="content">রেমোট এলাকার জন্য স্বাস্থ্য ক্যাম্প এবং পুষ্টি সেবা।</div>
          </div>
        </div>
      </div>
    </section>

    <section id="news" class="container">
      <h2 class="section-title">সর্বশেষ সংবাদ</h2>
      <div class="card news-list">
        <a class="news-item" href="#">
          <div class="news-thumb"></div>
          <div>
            <div style="font-weight:700">নতুন প্রশিক্ষণ: ডিজিটাল সাক্ষরতা বাড়ানো</div>
            <div class="muted" style="font-size:.95rem">অক্টোবর ১, ২০২৫ — সম্প্রতি আমাদের ৩টি জেলার ট্রেইনিং চালু হয়েছে।</div>
          </div>
        </a>
        <a class="news-item" href="#">
          <div class="news-thumb"></div>
          <div>
            <div style="font-weight:700">স্বাস্থ্য ক্যাম্প সফল</div>
            <div class="muted" style="font-size:.95rem">সেপ্টেম্বর ১৫, ২০২৫ — ৪,৫০০ লোককে প্রাথমিক সেবা প্রদান করা হয়েছে।</div>
          </div>
        </a>
      </div>
    </section>

    <section id="resources" class="container">
      <h2 class="section-title">রিসোর্স & ডাউনলোড</h2>
      <div class="grid-3">
        <div class="card">
          <h4>রিসার্চ পেপার</h4>
          <p class="muted">মানব উন্নয়ন সূচক (HDI) সম্পর্কিত সাম্প্রতিক বিশ্লেষণ।</p>
        </div>
        <div class="card">
          <h4>প্রকল্প রিপোর্ট</h4>
          <p class="muted">প্রতিবছর প্রকল্প বাস্তবায়ন রিপোর্ট ডাউনলোড করুন।</p>
        </div>
        <div class="card">
          <h4>ডেটাসেট</h4>
          <p class="muted">যোগ্যতা যাচাইয়ের জন্য খোলা ডেটা (CSV/JSON)।</p>
        </div>
      </div>
    </section>

    <section id="get-involved" class="container">
      <h2 class="section-title">যোগাযোগ ও অংশগ্রহণ</h2>
      <div class="card" style="display:flex;gap:1rem;flex-wrap:wrap;align-items:center">
        <div style="flex:1;min-width:220px">
          <h3 style="margin-top:0">কিভাবে সাহায্য করবেন</h3>
          <ul>
            <li>স্বেচ্ছাসেবক হিসেবে নিবন্ধন</li>
            <li>অর্থ সাহায্য/ডোনেশন</li>
            <li>কমিউনিটি কর্মশালায় অংশগ্রহণ</li>
          </ul>
        </div>
        <form id="contactForm" style="flex:1;min-width:240px">
          <label class="muted">নাম<br><input required name="name" placeholder="আপনার নাম" style="width:100%;padding:.5rem;border-radius:8px;border:1px solid #e6eef0;margin-top:.25rem"></label>
          <label class="muted">ইমেইল<br><input required type="email" name="email" placeholder="you@example.com" style="width:100%;padding:.5rem;border-radius:8px;border:1px solid #e6eef0;margin-top:.25rem"></label>
          <label class="muted">বার্তা<br><textarea required name="message" placeholder="আপনার বার্তা" style="width:100%;padding:.5rem;border-radius:8px;border:1px solid #e6eef0;margin-top:.25rem"></textarea></label>
          <div style="margin-top:.5rem"><button class="btn" type="submit">পাঠান</button></div>
        </form>
      </div>
    </section>
  </main>

  <footer>
    <div class="container" style="display:flex;justify-content:space-between;flex-wrap:wrap;gap:1rem">
      <div>
        <strong>Human Development (HDBD)</strong>
        <div class="muted">© <span id="year"></span> hdbd.com — সকল অধিকার সংরক্ষিত।</div>
      </div>
      <div class="muted">Address: Pabna, Dhaka,BD — Email: shareasobuj9829@gmail.com</div>
    </div>
  </footer>

  <script>
    // small helper scripts: mobile menu, accordion, contact form (demo)
    (function(){
      const toggle = document.getElementById('menuToggle');
      toggle.addEventListener('click', ()=>{
        const nav = document.querySelector('nav');
        const expanded = toggle.getAttribute('aria-expanded') === 'true';
        toggle.setAttribute('aria-expanded', String(!expanded));
        if(nav.style.display === 'flex'){nav.style.display='none'} else {nav.style.display='flex'}
      });

      // accordion
      document.querySelectorAll('.accordion .head').forEach(h=>{
        h.addEventListener('click', ()=>{
          const item = h.parentElement;
          item.classList.toggle('open');
          const plus = h.querySelector('.muted') || h.querySelector('span.muted');
        });
      });

      // contact form (demo only)
      const form = document.getElementById('contactForm');
      form.addEventListener('submit', (e)=>{
        e.preventDefault();
        const data = new FormData(form);
        // demo: simple client-side acknowledgement
        alert('ধন্যবাদ '+ (data.get('name') || '') +'. আপনার বার্তা প্রেরিত হয়েছে (ডেমো)।');
        form.reset();
      });

      document.getElementById('year').textContent = new Date().getFullYear();
    })();
  </script>

