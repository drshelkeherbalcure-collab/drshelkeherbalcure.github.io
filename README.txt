<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Dr Shelke Herbalcure — herbal beauty, hair care and wellness products. Manufacturing in Kalyan East, Maharashtra.">
  <title>Dr Shelke Herbalcure | Natural • Herbal • Pure</title>
  <style>
    :root{
      --green:#0d3b2a; --green2:#15563d; --gold:#c9a34a; --cream:#f7f1df;
      --text:#1d2a24; --muted:#66736d; --white:#fff; --line:#e6dfcd;
    }
    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{margin:0;font-family:Arial,Helvetica,sans-serif;color:var(--text);background:#fbfaf5}
    a{text-decoration:none;color:inherit}
    .topbar{background:var(--green);color:#fff;text-align:center;padding:9px 16px;font-size:13px;letter-spacing:.4px}
    header{position:sticky;top:0;z-index:20;background:rgba(255,255,255,.96);backdrop-filter:blur(10px);border-bottom:1px solid var(--line)}
    .nav{max-width:1180px;margin:auto;display:flex;align-items:center;justify-content:space-between;padding:14px 20px}
    .brand{display:flex;align-items:center;gap:10px;font-weight:800;color:var(--green);letter-spacing:.5px}
    .brand-mark{width:43px;height:43px;border:2px solid var(--gold);border-radius:50%;display:grid;place-items:center;font-size:20px;background:#f5eedb}
    .brand small{display:block;font-weight:500;color:#8a6b2a;font-size:10px;letter-spacing:2px;margin-top:2px}
    nav{display:flex;gap:24px;font-size:14px;font-weight:700;color:#294337}
    nav a:hover{color:#a37d26}
    .hero{max-width:1280px;margin:0 auto;padding:30px 20px 20px}
    .hero-card{position:relative;min-height:560px;border-radius:26px;overflow:hidden;background:var(--green);box-shadow:0 18px 50px rgba(0,0,0,.13)}
    .hero-card img{width:100%;height:100%;min-height:560px;object-fit:cover;display:block}
    .hero-overlay{position:absolute;inset:0;background:linear-gradient(90deg,rgba(6,31,22,.86) 0%,rgba(6,31,22,.55) 43%,rgba(6,31,22,.05) 75%)}
    .hero-copy{position:absolute;left:7%;top:50%;transform:translateY(-50%);max-width:510px;color:#fff}
    .eyebrow{color:#e6c765;letter-spacing:3px;text-transform:uppercase;font-size:13px;font-weight:800}
    h1{font-family:Georgia,serif;font-size:clamp(42px,6vw,76px);line-height:.98;margin:12px 0 16px}
    .hero-copy p{font-size:18px;line-height:1.65;color:#f3f0e5;max-width:470px}
    .btns{display:flex;gap:12px;flex-wrap:wrap;margin-top:24px}
    .btn{display:inline-block;padding:13px 20px;border-radius:999px;font-weight:800;font-size:14px}
    .btn-gold{background:var(--gold);color:#172b20}
    .btn-light{border:1px solid rgba(255,255,255,.7);color:#fff}
    section{max-width:1180px;margin:auto;padding:72px 20px}
    .section-head{text-align:center;margin-bottom:34px}
    .section-head span{color:#a27b27;font-size:12px;letter-spacing:2.5px;font-weight:800;text-transform:uppercase}
    .section-head h2{font-family:Georgia,serif;color:var(--green);font-size:40px;margin:8px 0}
    .section-head p{color:var(--muted);max-width:680px;margin:0 auto;line-height:1.6}
    .products{display:grid;grid-template-columns:repeat(5,1fr);gap:18px}
    .product{background:#fff;border:1px solid var(--line);border-radius:18px;overflow:hidden;box-shadow:0 7px 25px rgba(18,54,39,.06);display:flex;flex-direction:column}
    .product-img{height:230px;background:#f2f1e8;overflow:hidden}
    .product-img img{width:100%;height:100%;object-fit:cover}
    .product-body{padding:18px}
    .tag{display:inline-block;background:#eef5ee;color:var(--green2);border-radius:999px;padding:5px 9px;font-size:10px;font-weight:800;text-transform:uppercase;letter-spacing:.7px}
    .product h3{font-family:Georgia,serif;color:var(--green);font-size:21px;margin:12px 0 7px}
    .product p{color:var(--muted);font-size:13px;line-height:1.5;min-height:39px}
    .price{font-size:21px;font-weight:900;color:#9a7421;margin:10px 0 14px}
    .buy{display:block;text-align:center;background:var(--green);color:#fff;padding:11px;border-radius:10px;font-size:13px;font-weight:800}
    .about{background:linear-gradient(135deg,#eef4ec,#fffaf0);border-top:1px solid var(--line);border-bottom:1px solid var(--line)}
    .about-grid{max-width:1180px;margin:auto;padding:72px 20px;display:grid;grid-template-columns:1.05fr .95fr;gap:42px;align-items:center}
    .about-img{border-radius:22px;overflow:hidden;box-shadow:0 15px 40px rgba(0,0,0,.12)}
    .about-img img{display:block;width:100%;height:100%;object-fit:cover}
    .about-copy h2{font-family:Georgia,serif;color:var(--green);font-size:42px;margin:8px 0 15px}
    .about-copy p{line-height:1.75;color:var(--muted)}
    .pillars{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:25px}
    .pillar{background:#fff;border:1px solid var(--line);border-radius:14px;padding:16px}
    .pillar b{display:block;color:var(--green);margin-bottom:5px}
    .pillar span{font-size:12px;color:var(--muted)}
    .gallery{display:grid;grid-template-columns:1.4fr .8fr .8fr;grid-auto-rows:230px;gap:15px}
    .gallery img{width:100%;height:100%;object-fit:cover;border-radius:18px;border:1px solid var(--line)}
    .gallery img:first-child{grid-row:span 2}
    .contact{background:var(--green);color:#fff}
    .contact-inner{max-width:1000px;margin:auto;padding:68px 20px;text-align:center}
    .contact h2{font-family:Georgia,serif;font-size:42px;margin:8px 0 12px}
    .contact p{color:#dfeae2;line-height:1.6}
    .contact-cards{display:grid;grid-template-columns:repeat(3,1fr);gap:15px;margin-top:28px}
    .contact-card{background:rgba(255,255,255,.08);border:1px solid rgba(255,255,255,.16);border-radius:16px;padding:20px}
    .contact-card strong{display:block;color:#e8cb73;margin-bottom:7px}
    footer{background:#062419;color:#dce6df;text-align:center;padding:24px 20px;font-size:12px}
    .note{font-size:11px;color:#aab8b0;margin-top:12px}
    @media(max-width:980px){.products{grid-template-columns:repeat(2,1fr)}nav{gap:12px}.about-grid{grid-template-columns:1fr}.gallery{grid-template-columns:1fr 1fr}.gallery img:first-child{grid-row:auto;grid-column:span 2}}
    @media(max-width:620px){nav{display:none}.hero-card,.hero-card img{min-height:600px}.hero-copy{left:7%;right:7%}.products{grid-template-columns:1fr}.contact-cards{grid-template-columns:1fr}.gallery{grid-template-columns:1fr;grid-auto-rows:220px}.gallery img:first-child{grid-column:auto}.section-head h2,.about-copy h2,.contact h2{font-size:32px}}
  </style>
</head>
<body>
  <div class="topbar">Natural • Herbal • Pure &nbsp; | &nbsp; Manufacturing in Kalyan East, Maharashtra</div>
  <header>
    <div class="nav">
      <a class="brand" href="#home">
        <div class="brand-mark">🌿</div>
        <div>DR. SHELKE HERBALCURE<small>NATURAL • HERBAL • PURE</small></div>
      </a>
      <nav>
        <a href="#products">Products</a>
        <a href="#about">About</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main id="home">
    <div class="hero">
      <div class="hero-card">
        <img src="assets/hair-range.png" alt="Dr Shelke Herbalcure hair care range">
        <div class="hero-overlay"></div>
        <div class="hero-copy">
          <div class="eyebrow">Dr. Shelke Herbalcure</div>
          <h1>Nature’s Care.<br>Beautiful You.</h1>
          <p>Discover our herbal-inspired range of hair care, skin care and wellness products crafted for everyday self-care.</p>
          <div class="btns">
            <a class="btn btn-gold" href="#products">Explore Products</a>
            <a class="btn btn-light" href="tel:+918689958725">Call 8689958725</a>
          </div>
        </div>
      </div>
    </div>

    <section id="products">
      <div class="section-head">
        <span>Our Collection</span>
        <h2>Featured Products</h2>
        <p>Premium-looking herbal care products from the Dr. Shelke Herbalcure range.</p>
      </div>
      <div class="products">
        <article class="product">
          <div class="product-img"><img src="assets/hair-range.png" alt="He and She Hair Oil"></div>
          <div class="product-body"><span class="tag">Hair Care</span><h3>He and She Hair Oil</h3><p>Herbal beauty-care hair oil for routine hair care.</p><div class="price">₹499</div><a class="buy" href="https://wa.me/918689958725?text=Hello%20Dr%20Shelke%20Herbalcure%2C%20I%20want%20He%20and%20She%20Hair%20Oil.">Order on WhatsApp</a></div>
        </article>
        <article class="product">
          <div class="product-img"><img src="assets/soap-lineup.png" alt="Dr Shelke Herbal Soap"></div>
          <div class="product-body"><span class="tag">Skin Care</span><h3>Herbal Soap</h3><p>Herbal soap with a clean, nature-inspired care concept.</p><div class="price">₹70</div><a class="buy" href="https://wa.me/918689958725?text=Hello%20Dr%20Shelke%20Herbalcure%2C%20I%20want%20Herbal%20Soap.">Order on WhatsApp</a></div>
        </article>
        <article class="product">
          <div class="product-img"><img src="assets/multivitamin.png" alt="Dr Shelke Herbalcure Multivitamin Tablets"></div>
          <div class="product-body"><span class="tag">Wellness</span><h3>Multivitamin Tablets</h3><p>Daily wellness supplement presented in the Dr. Shelke range.</p><div class="price">₹290</div><a class="buy" href="https://wa.me/918689958725?text=Hello%20Dr%20Shelke%20Herbalcure%2C%20I%20want%20Multivitamin%20Tablets.">Order on WhatsApp</a></div>
        </article>
        <article class="product">
          <div class="product-img"><img src="assets/vitamin-e.png" alt="Dr Shelke Herbalcure Vitamin E Softgel Capsules"></div>
          <div class="product-body"><span class="tag">Wellness</span><h3>Vitamin E</h3><p>Vitamin E softgel capsules in a premium herbalcure presentation.</p><div class="price">₹175</div><a class="buy" href="https://wa.me/918689958725?text=Hello%20Dr%20Shelke%20Herbalcure%2C%20I%20want%20Vitamin%20E.">Order on WhatsApp</a></div>
        </article>
        <article class="product">
          <div class="product-img"><img src="assets/hair-range.png" alt="Dr Shelke Herbal Hair Colour"></div>
          <div class="product-body"><span class="tag">Hair Care</span><h3>Hair Colour</h3><p>Herbal hair-colour range designed for a rich, natural-looking finish.</p><div class="price">₹75</div><a class="buy" href="https://wa.me/918689958725?text=Hello%20Dr%20Shelke%20Herbalcure%2C%20I%20want%20Hair%20Colour.">Order on WhatsApp</a></div>
        </article>
      </div>
    </section>

    <div class="about" id="about">
      <div class="about-grid">
        <div class="about-img"><img src="assets/he-and-she.png" alt="Dr Shelke He and She herbal beauty care collection"></div>
        <div class="about-copy">
          <span class="eyebrow" style="color:#9b7627">About the brand</span>
          <h2>Herbal care for everyday beauty</h2>
          <p>Dr. Shelke Herbalcure brings together a nature-inspired product collection spanning hair care, skin care and wellness. The brand is presented with a premium herbal identity and is manufactured in Kalyan East, Maharashtra.</p>
          <div class="pillars">
            <div class="pillar"><b>Hair Care</b><span>Oil, shampoo, colour & serum range</span></div>
            <div class="pillar"><b>Skin Care</b><span>Herbal soap & beauty care</span></div>
            <div class="pillar"><b>Wellness</b><span>Multivitamin & Vitamin E range</span></div>
          </div>
        </div>
      </div>
    </div>

    <section id="gallery">
      <div class="section-head">
        <span>Brand Gallery</span>
        <h2>Explore the Range</h2>
        <p>Selected product visuals supplied for the Dr. Shelke Herbalcure website.</p>
      </div>
      <div class="gallery">
        <img src="assets/hair-range.png" alt="Dr Shelke Herbalcure hair care products">
        <img src="assets/soap-lineup.png" alt="Dr Shelke Herbalcure soap range">
        <img src="assets/vitamin-e.png" alt="Dr Shelke Herbalcure Vitamin E">
        <img src="assets/multivitamin.png" alt="Dr Shelke Herbalcure multivitamin">
        <img src="assets/herbal-soap.png" alt="Dr Shelke Herbalcure herbal soap">
      </div>
    </section>

    <div class="contact" id="contact">
      <div class="contact-inner">
        <div class="eyebrow">Get in touch</div>
        <h2>Dr. Shelke Herbalcure</h2>
        <p>For product enquiries and orders, contact us directly.</p>
        <div class="contact-cards">
          <a class="contact-card" href="tel:+918689958725"><strong>Phone</strong>8689958725</a>
          <a class="contact-card" href="mailto:drshelkeherbalcure@gmail.com"><strong>Email</strong>drshelkeherbalcure@gmail.com</a>
          <div class="contact-card"><strong>Manufacturing</strong>Kalyan East, Maharashtra</div>
        </div>
        <div class="note">Product prices shown are the prices supplied for this website. Product labels, regulatory declarations and final packaging should be verified before commercial publication.</div>
      </div>
    </div>
  </main>

  <footer>© 2026 Dr. Shelke Herbalcure • Natural • Herbal • Pure</footer>
</body>
</html>
