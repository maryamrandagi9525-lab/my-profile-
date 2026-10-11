<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nova</title>
    <link rel="stylesheet"  q1` href="style.css">
</head>
<body>
    <header>
        <div class="container header-inner">
            <h1 class="logo">NOVA.</h1>
            <nav>
                <ul>
                    <a href="#welcome">Home</a></li>
                    <a href="#me">About</a>
                    <a href="#Services">Services</a>
                    <a href="#Projects">Projects</a>
                    <a href="#contact">Contact</a>
                </ul>
            </nav>
        </div>
    </header>
    <main>
        <section id="welcome" class="welcome">
            <div class="container welcome-grid">
                <div class="welcome-text">
                    <h2>We Create <span><br>Digital Experience.<span></h2>
                    <p> NOVA Studio helps businesses and organizations build modern, beautiful and <br> user-friendly digital experiences</p>
                    <div class="cta">
                        <a href="#" class="btn primary">Our Services</a>
                        <a href="#" target="_blank" class="btn secondary">View projects</a>
                    </div>
                </div>
                <div class="welcome-image">
                <img src="images/aimjay.jpg" alt="profile-picture">
                </div>
            </div>
        </section>
        <section id="me" class="me-about">
            <div class="container me-grid">
                <div class="me-image">
                    <img src="images/aimjay.jpg" alt="Creative beach sunset with flowers representing digital ideas">
                </div>
                <div class="me">
                    <h4 class="small-title">ABOUT NOVA →</h4>
                    <h2 class="we">Ideas become digital<br>experiences.</h2>
                    <p class="desc">We are a creative digital studio focused on building websites and digital products that are simple, useful and visually engaging.</p>
                    <p class="desc">From the first idea to the final product, we combine creativity, design and technology to solve real problems.</p>
                    <a href="#contact" class="work-link">Work With Us →</a>
                </div>
            </div>
        </section>
        <section id="Services" class="services">
  <div class="container">
    <span class="top">WHAT WE DO</span>
    <h2>Our Services</h2>
    <p class="sub">We create digital solutions designed around real people and real needs.</p>

    <div class="grid">
      <div class="card">
        <small>01</small>
        <h3>Web Design</h3>
        <p>Clean and modern website designs that communicate your brand clearly.</p>
      </div>
      <div class="card">
        <small>02</small>
        <h3>Web Development</h3>
        <p>Fast, responsive and functional websites built for the modern web.</p>
      </div>
      <div class="card">
        <small>03</small>
        <h3>UI/UX Design</h3>
        <p>Simple user experiences that make digital products easy to use.</p>
      </div>
      <div class="card">
        <small>04</small>
        <h3>Digital Solutions</h3>
        <p>Technology solutions designed to help businesses work better.</p>
      </div>
    </div>
  </div>
</section>
        <section id="Projects" class="featured-work">
    <div class="container">
        <h4 class="small-title">OUR WORK</h4>
        <h2 class="section-heading">Featured Projects</h2>
        
        <div class="work-grid">
            <div class="work-card">
                <img src="images/aimjay.jpg" alt="E-commerce MarketPlace online shopping project">
                <div class="work-info">
                    <h5>E-COMMERCE</h5>
                    <h3>MarketPlace</h3>
                    <p>A modern online shopping experience designed for growing businesses</p>
                    <a href="#" class="view-link">View Project →</a>
                </div>
            </div>

            <div class="work-card">
                <img src="images/aimjay.jpg" alt="Hospitality Urban Table restaurant digital experience project">
                <div class="work-info">
                    <h5>HOSPITALITY</h5>
                    <h3>Urban Table</h3>
                    <p>A stylish digital experience for a modern restaurant.</p>
                    <a href="#" class="view-link">View Project →</a>
                </div>
            </div>

            <div class="work-card">
                <img src="images/aimjay.jpg" alt="Education LearnSpace online learning platform project">
                <div class="work-info">
                    <h5>EDUCATION</h5>
                    <h3>LearnSpace</h3>
                    <p>An engaging platform designed to make online learning easier.</p>
                    <a href="#" class="view-link">View Project →</a>
                </div>
            </div>
        </div>
    </div>
</section>
<section class="purpose-section">
    <div class="container">
        <span class="small-blue">WHY NOVA</span>
        <h2 class="purpose-heading">Built With Purpose.</h2>
        
        <div class="purpose-grid">
            <div class="purpose-item">
                <h4>01. Creative</h4>
                <p>We approach every project with fresh ideas and thoughtful design.</p>
            </div>
            <div class="purpose-item">
                <h4>02. Simple</h4>
                <p>We believe great digital products should be easy to understand and use.</p>
            </div>
            <div class="purpose-item">
                <h4>03. Responsive</h4>
                <p>Our websites are designed to work across phones, tablets and computers.</p>
            </div>
        </div>
    </div>
</section>
    <section class="contact-section" id="contact">
    <div class="container">
        <div class="contact-left">
            <span class="small-blue">GET IN TOUCH</span>
            <h2>Have an idea? Let's build it.</h2>
            <p>We'd love to hear about your next project.</p>
        </div>
        <div class="contact-right">
            <p>hello@novastudio.com</p>
            <p>+234 800 000 0000</p>
            <p class="light">Lagos, Nigeria</p>
        </div>
    </div>
</section>
</main>
<footer class="footer">
    <div class="container">
        <div class="footer-left">
            <h3>NOVA.</h3>
            <p>Creative Digital Studio</p>
        </div>
        <div class="footer-right">
            <p>©️ 2026 NOVA Studio. All rights reserved.</p>
        </div>
    </div>
</footer>
</body>
</html>
*{ 
    margin: 0; 
    padding: 0; 
    box-sizing: border-box; 
}
body { font-family: 'Segoe UI', sans-serif;
    line-height: 1.6; 
    color: #1e293b;
    background: #f8fafc; 
}
.container { 
    max-width: 1100px; 
    margin: 0 auto; 
    padding: 0 20px; 
}

header { 
    background: #fdfdfd; 
    color: rgb(29, 4, 4); 
    padding: 18px 0; 
    border-bottom: 4px solid #fefeff; 
    position: sticky; 
    top: 0; 
}
.header-inner { 
    display: flex; 
    justify-content: space-between; 
    align-items: center; 
}
nav ul { 
    display: flex; 
    list-style: none; 
    gap: 22px; 
}
nav a { 
    color: #011227; 
    text-decoration: none; 
    font-weight: 500; 
}
nav a:hover { 
    color: #60a5fa; 
}
.welcome { 
    padding: 70px 0; 
    background: linear-gradient(135deg, #ffffff 0%, #e0e7ff 100%); 
}
.welcome-grid { 
    display: flex; 
    align-items: center; 
    gap: 40px; 
}
.welcome-text { 
    flex: 1; 
}
.welcome-text h2 { 
    font-size: 2.8rem; 
    margin-bottom: 16px; 
}
.welcome-text h2 span { 
    color: #2563eb; 
}
.welcome-image { 
    flex: 0 0 100px; 
}
.welcome-image img { 
    width: 400px;
    height: 450px;
    object-fit: cover; 
    border-radius: 16px;  
    box-shadow: 0 10px 25px rgba(0,0,0,0.1);
}
.cta { 
    display: flex; 
    gap: 12px;
    margin-top: 10px; 
}
.btn { 
    padding: 10px 20px; 
    border-radius: 8px; 
    text-decoration: none; 
    font-weight: 600; 
    border: 2px solid transparent; 
}
.btn.primary { 
    background: #091630; 
    color: white; 
}
.btn.secondary { 
    background: white; 
    color: #091630; 
    border-color: #091630; 
}

.me-about {
  padding: 80px 0;
  background: #ffffff;
}
.me-grid {
  display: flex;
  align-items: center;
  gap: 70px;
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 20px;
}
.me-image { 
    flex: 1; 
}
.me-image img {
  width: 400px;
  height: 450px;
  object-fit: cover;
  border-radius: 16px;
}
.me-text { flex: 1; }
.small-title {
  font-size: 0.75rem;
  letter-spacing: 3px;
  color: #5a7ab5;
  font-weight: 700;
  margin-bottom: 18px;
}

.me-text h2 {
  font-size: 2.6rem;
  line-height: 1.2;
  color: #2f3d5a;
  font-weight: 700;
  margin-bottom: 20px;
}
.me-text .desc {
  color: #7a8aa6;
  font-size: 0.95rem;
  line-height: 1.7;
  margin-bottom: 14px;
}
.work-link {
  display: inline-block;
  margin-top: 8px;
  color: #5a7ab5;
  font-weight: 600;
  text-decoration: none;
}

  .me-image img { 
    height: 300px; 
}

.services{
  padding:80px 20px;
  background:#f8fafd;
  font-family: sans-serif;
}
.container{
  max-width:1100px;
  margin:auto;
}
.top{
  color:#6b8cc3;
  font-size:11px;
  letter-spacing:3px;
  font-weight:700;
}
.services h2{
  font-size:32px;
  color:#1e2a44;
  margin:10px 0;
}
.sub{
  color:#7a8ca8;
  font-size:14px;
  margin-bottom:40px;
}
.grid{
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:20px;
}
.card{
  background:#fff;
  padding:25px;
  border-radius:12px;
  box-shadow:0 4px 20px rgba(0,0,0,0.05);
}
.card small{
  color:#6b8cc3;
  font-weight:700;
  font-size:11px;
}
.card h3{
  font-size:16px;
  color:#1e2a44;
  margin:20px 0 10px;
}
.card p{
  font-size:13px;
  color:#8a9bb5;
  line-height:1.6;
}

.tag { 
    display: inline-block; 
    background: #eff6ff; 
    color: #1d4ed8; 
    padding: 4px 10px; 
    border-radius: 20px; 
    font-size: 0.85rem; 
    border: 1px solid #dbeafe; 
}

.featured-work {
    padding: 80px 0;
    background: #fdfdfd;
}
.small-title {
    font-size: 0.75rem;
    letter-spacing: 3px;
    color: #5a7ab5;
    font-weight: 700;
    margin-bottom: 12px;
}
.section-heading {
    font-size: 2.2rem;
    color: #1a253c;
    font-weight: 700;
    margin-bottom: 40px;
}
.work-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 30px;
}
.work-card {
    background: transparent;
    border-radius: 12;
    box-shadow: 12px;
    
}
.work-card img {
    width: 100%;
    height: 220px;
    object-fit: cover;
    border-radius: 12px;
    display: block;
    margin-bottom: 16px;
}
.work-info h5 {
    font-size: 0.65rem;
    letter-spacing: 2px;
    color: #8a9ab8;
    font-weight: 700;
    margin-bottom: 8px;
}
.work-info h3 {
    font-size: 1.15rem;
    color: #1a253c;
    font-weight: 700;
    margin-bottom: 8px;
}
.work-info p {
    font-size: 0.85rem;
    color: #7a8aa6;
    line-height: 1.6;
    margin-bottom: 12px;
}
.view-link {
    font-size: 0.85rem;
    color: #5a7ab5;
    font-weight: 600;
    text-decoration: none;
}
.view-link:hover {
    color: #1a253c;
}


.purpose-section {
    background: #151b2b;
    background: linear-gradient(180deg, #1a233a 0%, #151b2b 100%);
    padding: 90px 20px;
    color: white;
    font-family: sans-serif;
}
.purpose-section .container {
    max-width: 1100px;
    margin: auto;
}
.small-blue {
    color: #6b8cc3;
    font-size: 11px;
    letter-spacing: 3px;
    font-weight: 700;
    text-transform: uppercase;
}
.purpose-heading {
    font-size: 38px;
    font-weight: 700;
    margin: 15px 0 50px 0;
    color: #ffffff;
}
.purpose-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 50px;
}
.purpose-item h4 {
    font-size: 16px;
    font-weight: 700;
    margin-bottom: 12px;
    color: #ffffff;
}
.purpose-item p {
    font-size: 13.5px;
    color: #8a9bb5;
    line-height: 1.7;
}


.contact-section {
    background: #f8fbfd;
    padding: 80px 20px;
    font-family: sans-serif;
}
.contact-section .container {
    max-width: 1100px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
}
.small-blue {
    color: #6b8cc3;
    font-size: 11px;
    letter-spacing: 3px;
    font-weight: 700;
    text-transform: uppercase;
}
.contact-left h2 {
    font-size: 32px;
    color: #1e2a44;
    margin: 15px 0 15px;
    font-weight: 700;
}
.contact-left p {
    color: #8a9bb5;
    font-size: 14px;
}
.contact-right {
    text-align: right;
}
.contact-right p {
    font-size: 14px;
    color: #1e2a44;
    font-weight: 600;
    margin-bottom: 12px;
}
.contact-right p.light {
    color: #8a9bb5;
    font-weight: 400;
}

.footer {
    background: #121a2b;
    padding: 35px 20px;
    color: white;
}
.footer .container {
    max-width: 1100px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.footer-left h3 {
    font-size: 18px;
    font-weight: 800;
    letter-spacing: 1px;
}
.footer-left p {
    font-size: 12px;
    color: #8a9bb5;
    margin-top: 4px;
}
.footer-right p {
    font-size: 11px;
    color: #6b7d9a;
}

@media (max-width: 800px) {
.welcome-grid { 
    flex-direction: column-reverse; 
    text-align: center; 
}
.welcome-image { 
    width: 100px; 
}
.cta { 
    justify-content: center; 
}
.header-inner { 
    flex-direction: column; gap: 12px; 
}
.cards { 
    flex-direction: column; 
}
.contact-section .container,
.footer .container {
    flex-direction: column;
    gap: 25px;
}
.contact-right {
    text-align: left;
}
    .purpose-grid {
    gap: 30px;
}
.purpose-heading {
    font-size: 28px;
}

.work-grid {
    grid-template-columns: 1fr;
}
me-grid { 
    flex-direction: column; 
    gap: 30px;

}
}
