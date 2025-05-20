<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Spirit of Watercolor</title>
<style>
  body {
    margin: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #40e0d0; /* تركواز */
    scroll-behavior: smooth;
    color: #333;
  }
  header {
    background: linear-gradient(45deg, #40e0d0, #ffeb3b, #f06292);
    padding: 1rem 0;
    text-align: center;
    color: white;
    position: sticky;
    top: 0;
    z-index: 10;
  }
  header h1 {
    margin: 0;
    font-size: 2.5rem;
    animation: fadeInDown 1.5s ease-out;
  }
  nav {
    margin-top: 0.5rem;
  }
  nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
    transition: color 0.3s;
  }
  nav a:hover {
    color: #444;
  }
  section {
    padding: 3rem 1rem;
    max-width: 1000px;
    margin: auto;
    animation: fadeInUp 1s ease-in-out;
    background-color: rgba(255,255,255,0.85);
    border-radius: 15px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.15);
  }
  .gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
  }
  .gallery img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 12px;
    box-shadow: 0 6px 18px rgba(0,0,0,0.2);
    transition: transform 0.4s ease, box-shadow 0.4s ease;
  }
  .gallery img:hover {
    transform: scale(1.05);
    box-shadow: 0 10px 30px rgba(0,0,0,0.3);
  }
  footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    font-size: 0.9rem;
  }
  h2 {
    color: #f06292;
    text-align: center;
    margin-bottom: 1.5rem;
  }
  p {
    color: #555;
    line-height: 1.6;
    text-align: center;
  }
  @keyframes fadeInDown {
    0% { opacity: 0; transform: translateY(-30px); }
    100% { opacity: 1; transform: translateY(0); }
  }
  @keyframes fadeInUp {
    0% { opacity: 0; transform: translateY(30px); }
    100% { opacity: 1; transform: translateY(0); }
  }
</style>
</head>
<body>

<header>
  <h1>Spirit of Watercolor</h1>
  <nav>
    <a href="#home">الرئيسية</a>
    <a href="#gallery">المعرض</a>
    <a href="#articles">المقالات</a>
    <a href="#contact">اتصل بنا</a>
  </nav>
</header>

<section id="home">
  <h2>الرئيسية</h2>
  <p>مرحباً بك في موقع Spirit of Watercolor، حيث نعرض لك جمال الألوان المائية والتصميم الإبداعي الذي ينبض بالحياة والهدوء.</p>
</section>

<section id="gallery">
  <h2>المعرض</h2>
  <div class="gallery">
    <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=800&q=80" alt="لوحة 1" />
    <img src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97?auto=format&fit=crop&w=800&q=80" alt="لوحة 2" />
    <img src="https://images.unsplash.com/photo-1500534623283-312aade485b7?auto=format&fit=crop&w=800&q=80" alt="لوحة 3" />
    <img src="https://images.unsplash.com/photo-1472214103451-9374bd1c798e?auto=format&fit=crop&w=800&q=80" alt="لوحة 4" />
    <img src="https://images.unsplash.com/photo-1470770841072-f978cf4d019e?auto=format&fit=crop&w=800&q=80" alt="لوحة 5" />
    <img src="https://images.unsplash.com/photo-1494526585095-c41746248156?auto=format&fit=crop&w=800&q=80" alt="لوحة 6" />
  </div>
</section>

<section id="articles">
  <h2>المقالات</h2>
  <p>اكتشف مقالات ملهمة حول تقنيات الرسم بالألوان المائية، ونصائح للفنانين المبتدئين والمحترفين.</p>
</section>

<section id="contact">
  <h2>اتصل بنا</h2>
  <p>للتواصل معنا أو حجز ورشة عمل، الرجاء إرسال بريد إلكتروني إلى: <br><strong>contact@spiritofwatercolor.com</strong></p>
</section>

<footer>
  &copy; 2025 Spirit of Watercolor. جميع الحقوق محفوظة.
</footer>

</body>
</html>
