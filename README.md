<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>朱序 · Original Handmade Bracelets | 新中式原创珠宝手链</title>
    <meta name="description" content="ZhuXu 朱序｜独立原创新中式手工珠宝手链，孤品串珠，东方美学，海外可配送，每一件都是手工创作。">
    <style>
        *{margin:0;padding:0;box-sizing:border-box;font-family:"Noto Serif SC",serif;}
        body{background-color:#F7F3EB;color:#222;line-height:1.6;}
        /* 导航栏 */
        header{background-color:#9E2B25;position:sticky;top:0;z-index:999;}
        .nav-wrap{max-width:1400px;margin:0 auto;display:flex;justify-content:space-between;align-items:center;padding:1rem 2rem;}
        .logo{font-size:1.8rem;color:#F7F3EB;font-weight:bold;letter-spacing:0.2em;}
        nav a{color:#F7F3EB;text-decoration:none;margin:0 1rem;font-size:1rem;transition:opacity 0.3s;}
        nav a:hover{opacity:0.7;color:#C8A86E;}
        .hamburger{display:none;color:#fff;font-size:2rem;}

        /* 首屏Banner */
        .hero{height:90vh;background:linear-gradient(rgba(158,43,37,0.8),rgba(158,43,37,0.8)),url('https://images.unsplash.com/photo-1573408301185-9146fe634ad0?ixlib=rb-4.0.3&auto=format&fit=crop&w=1800&q=80');background-size:cover;background-position:center;display:flex;align-items:center;justify-content:center;text-align:center;color:#F7F3EB;}
        .hero-content h1{font-size:3.2rem;letter-spacing:0.3em;margin-bottom:1rem;}
        .hero-content p{font-size:1.2rem;max-width:700px;margin:0 auto 2rem;opacity:0.9;}
        .btn{display:inline-block;padding:1rem 2.4rem;border:1px solid #F7F3EB;color:#F7F3EB;text-decoration:none;transition:all 0.4s;}
        .btn:hover{background:#F7F3EB;color:#9E2B25;border-color:#C8A86E;}
        .btn-gold{border-color:#C8A86E;color:#C8A86E;margin-left:1rem;}
        .btn-gold:hover{background:#C8A86E;color:#222;}

        /* 通用容器 */
        .container{max-width:1400px;margin:0 auto;padding:6rem 2rem;}
        .section-title{text-align:center;margin-bottom:4rem;}
        .section-title h2{font-size:2.2rem;color:#9E2B25;letter-spacing:0.15em;margin-bottom:0.8rem;}
        .section-title .line{width:80px;height:2px;background:#C8A86E;margin:0 auto;}

        /* 产品区 */
        .product-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:2.5rem;}
        .product-card{background:#fff;border:1px solid #e8e2d8;overflow:hidden;transition:transform 0.3s;}
        .product-card:hover{transform:translateY(-8px);box-shadow:0 12px 30px rgba(158,43,37,0.15);}
        .product-img{height:320px;background:#eee;overflow:hidden;}
        .product-img img{width:100%;height:100%;object-fit:cover;}
        .product-info{padding:1.5rem;text-align:center;}
        .product-info h3{color:#222;margin-bottom:0.5rem;font-size:1.1rem;}
        .product-info p{color:#666;font-size:0.9rem;margin-bottom:0.8rem;}
        .price{font-size:1.2rem;color:#9E2B25;font-weight:bold;}

        /* 品牌故事 */
        .about-wrap{display:grid;grid-template-columns:1fr 1fr;gap:4rem;align-items:center;}
        .about-text h2{color:#9E2B25;font-size:2rem;margin-bottom:1.5rem;letter-spacing:0.1em;}
        .about-text p{margin-bottom:1rem;color:#444;font-size:1rem;}
        .about-img{height:500px;overflow:hidden;}
        .about-img img{width:100%;height:100%;object-fit:cover;}

        /* 服务优势 */
        .feature-wrap{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:2rem;margin-top:2rem;}
        .feature-item{text-align:center;padding:2rem;border:1px solid #e8e2d8;background:#fff;}
        .feature-item h3{color:#9E2B25;margin-bottom:0.8rem;}

        /* 联系咨询 */
        .contact{background:#9E2B25;color:#F7F3EB;text-align:center;padding:5rem 2rem;}
        .contact h2{font-size:2rem;margin-bottom:1rem;}
        .contact p{max-width:700px;margin:0 auto 2rem;opacity:0.9;}

        /* 页脚 */
        footer{background:#222;color:#aaa;text-align:center;padding:3rem 2rem;}
        footer p{margin-top:1rem;font-size:0.9rem;}

        /* 移动端适配 */
        @media (max-width:768px){
            nav{display:none;}
            .hamburger{display:block;}
            .hero-content h1{font-size:2rem;}
            .about-wrap{grid-template-columns:1fr;}
            .btn{display:block;margin:1rem auto;width:fit-content;}
        }
    </style>
</head>
<body>
<!-- 导航 -->
<header>
    <div class="nav-wrap">
        <div class="logo">朱序 ZHUXU</div>
        <nav>
            <a href="#home">Home</a>
            <a href="#products">Collections</a>
            <a href="#about">Our Story</a>
            <a href="#service">Service</a>
            <a href="#contact">Contact</a>
        </nav>
        <div class="hamburger">☰</div>
    </div>
</header>

<!-- 首屏 -->
<section class="hero" id="home">
    <div class="hero-content">
        <h1>朱序 · 原创新中式珠宝手链</h1>
        <p>Handcrafted Original Chinese Style Bracelets | Every piece is handmade, limited & unique. Ship worldwide.</p>
        <a href="#products" class="btn">View Collections</a>
        <a href="#contact" class="btn btn-gold">Custom Order</a>
    </div>
</section>

<!-- 产品展示 -->
<section class="container" id="products">
    <div class="section-title">
        <h2>Bracelet Collections</h2>
        <div class="line"></div>
    </div>
    <div class="product-grid">
        <!-- 产品1 -->
        <div class="product-card">
            <div class="product-img">
                <img src="https://images.unsplash.com/photo-1611591437281-460bfbe1220a?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Red Agate New Chinese Bracelet">
            </div>
            <div class="product-info">
                <h3>Cinnabar Cloud · Red Agate Bracelet</h3>
                <p>Original Design | Hand Knotted</p>
                <div class="price">$48.00 USD</div>
            </div>
        </div>
        <!-- 产品2 -->
        <div class="product-card">
            <div class="product-img">
                <img src="https://images.unsplash.com/photo-1599643478518-a784e5dc4c8f?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Jade Beaded Bracelet">
            </div>
            <div class="product-info">
                <h3>Spring Mist · Jade Beaded Bracelet</h3>
                <p>One of a Kind | Handmade</p>
                <div class="price">$62.00 USD</div>
            </div>
        </div>
        <!-- 产品3 -->
        <div class="product-card">
            <div class="product-img">
                <img src="https://images.unsplash.com/photo-1602173574767-37ac01994b2a?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Lucky Knot Bracelet">
            </div>
            <div class="product-info">
                <h3>Auspicious Knot · Stack Bracelet Set</h3>
                <p>Gift Ready | Hand Woven</p>
                <div class="price">$55.00 USD</div>
            </div>
        </div>
        <!-- 产品4 -->
        <div class="product-card">
            <div class="product-img">
                <img src="https://images.unsplash.com/photo-1617038220319-276d3cfab638?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Natural Stone Bracelet">
            </div>
            <div class="product-info">
                <h3>Mountain Echo · Natural Stone Bracelet</h3>
                <p>Limited Edition</p>
                <div class="price">$78.00 USD</div>
            </div>
        </div>
    </div>
</section>

<!-- 品牌故事 -->
<section class="container" id="about">
    <div class="about-wrap">
        <div class="about-text">
            <h2>Our Story</h2>
            <p>ZhuXu is an independent handmade jewelry studio. All bracelets are original designs inspired by traditional Chinese aesthetics.</p>
            <p>Every bead is carefully selected, every knot tied by hand. No mass production. Most pieces are limited or one-of-a-kind. We combine cinnabar red, jade, natural stones and traditional Chinese knot craft.</p>
            <p>We ship worldwide, provide gift wrapping & custom engraving service for global customers.</p>
            <a href="#contact" class="btn" style="margin-top:1rem;background:#9E2B25">Learn More</a>
        </div>
        <div class="about-img">
            <img src="https://images.unsplash.com/photo-1605100804763-247f67b3557e?ixlib=rb-4.0.3&auto=format&fit=crop&w=900&q=80" alt="Hand making bracelet">
        </div>
    </div>
</section>

<!-- 服务优势 -->
<section class="container" id="service">
    <div class="section-title">
        <h2>Why Choose Us</h2>
        <div class="line"></div>
    </div>
    <div class="feature-wrap">
        <div class="feature-item">
            <h3>Original Design</h3>
            <p>All works are independently designed. No copied patterns.</p>
        </div>
        <div class="feature-item">
            <h3>Handmade Craft</h3>
            <p>Hand stringing & hand knotting, every detail carefully finished.</p>
        </div>
        <div class="feature-item">
            <h3>Worldwide Shipping</h3>
            <p>Trackable international shipping to US, UK, EU, Australia etc.</p>
        </div>
        <div class="feature-item">
            <h3>Gift Service</h3>
            <p>Free gift packaging & custom handwritten English greeting card.</p>
        </div>
    </div>
</section>

<!-- 联系下单 -->
<section class="contact" id="contact">
    <h2>Make Your Order & Custom Inquiry</h2>
    <p>DM us for custom bracelet, bulk wholesale, or product details. We reply within 24 hours.</p>
    <a href="#" class="btn">Email Us</a>
    <a href="#" class="btn btn-gold">Instagram / TikTok</a>
</section>

<!-- 页脚 -->
<footer>
    <div class="logo">朱序 ZHUXU</div>
    <p>©2026 ZhuXu Handmade Jewelry | All Original Design. All Rights Reserved.</p>
    <p>Handmade New Chinese Style Bracelets | Worldwide Shipping</p>
</footer>
</body>
</html>
