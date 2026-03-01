<!DOCTYPE html>
<html lang="ro">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Kaizoku | Performance Lab</title>
<meta name="description" content="Kaizoku Performance Lab: Sisteme high-performance personalizate, instalare Windows/Linux, fine-tuning și testare benchmark.">

<!-- Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;600;700&display=swap" rel="stylesheet" />
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />

<style>
*{margin:0;padding:0;box-sizing:border-box;}
body{
  font-family:'Space Grotesk',sans-serif;
  background:#000; /* fundal negru pentru întreg corpul */
  color:#f5f5f7;
  line-height:1.6;
  overflow-x:hidden;
}

/* Cursor customizat */
@media(min-width:1024px){
  .cursor{
    width:12px;height:12px;border:1px solid #fff;border-radius:50%;
    position:fixed;pointer-events:none;z-index:9999;
    transition:transform .15s ease;
  }
}
.cursor{
  width:12px;height:12px;border:1px solid #fff;border-radius:50%;
  position:fixed;pointer-events:none;z-index:9999;
  transition:transform .15s ease;
}

/* Navigare */
nav{
  position:fixed;top:0;width:100%;
  padding:15px 5%;
  display:flex;justify-content:space-between;align-items:center;
  background:rgba(15,15,17,.8);
  backdrop-filter:blur(10px);
  z-index:1000;
}
nav .logo{
  font-weight:700;font-size:1.5rem;color:#fff;
}
nav .menu a{
  color:#fff;text-decoration:none;margin-left:25px;font-size:1rem;transition:.3s;
}
nav .menu a:hover{
  opacity:.7;
}

/* Header */
header{
  height:100vh;display:flex;flex-direction:column;justify-content:center;align-items:center;
  text-align:center;padding:0 5%;
  background:linear-gradient(rgba(15,15,17,.85),rgba(15,15,17,.85)),
    url('https://i.pinimg.com/1200x/95/09/7d/95097d719b393b33c47fe04e45ad09d1.jpg') center/cover no-repeat;
}
header h1{
  font-size:3rem;margin-bottom:15px;line-height:1.2;color:#fff;
}
header p{
  max-width:600px;color:#ccc;margin-bottom:25px;font-size:1.2rem;
}
.btn{
  padding:12px 25px;border-radius:30px;border:1px solid #fff;background:transparent;color:#fff;
  text-decoration:none;font-weight:600;font-size:1.1rem;transition:.3s;
}
.btn:hover{
  background:#fff;color:#000;opacity:.8;
}

/* Secțiuni */
section{
  padding:80px 5%;opacity:0;transform:translateY(50px);transition:1s;
}
section.reveal{
  opacity:1;transform:none;
}
.section-title{
  text-align:center;margin-bottom:40px;font-size:2rem;color:#fff;
}
.grid{
  display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:30px;
}
.card{
  background:#1a1a1d;padding:25px;border-radius:15px;transition:.3s;text-align:center;color:#fff;
}
.card:hover{
  transform:translateY(-6px);
}
.card h3{
  margin-bottom:15px;
}
.card ul{
  list-style:none;margin-top:10px; padding-left:0;
}
.card ul li{
  font-size:1rem;color:#ccc;margin-bottom:8px;
}
.highlight{
  background:#141417;padding:40px;border-radius:15px;text-align:center;font-size:1.1rem;color:#fff;
}
.portfolio img{
  width:100%;border-radius:12px;transition:.3s;
}

/* Formular */
#contact form{
  max-width:500px;margin:0 auto;display:flex;flex-direction:column;gap:15px;
}
#contact input,
#contact textarea{
  padding:12px;border-radius:10px;border:none;background:#222;color:#fff;font-size:1rem;
}
/* Stilizare select cu ton de gri închis */
#contact select{
  padding:12px;
  border-radius:30px;
  border:none;
  background:#222; /* fundal gri închis */
  color:#ccc; /* text gri deschis */
  font-weight:600;
  font-size:1.1rem;
  cursor:pointer;
  transition:.3s;
  appearance: none;
}
/* Opțiuni */
#contact select option{
  background:#222; /* fundal gri închis pentru opțiuni */
  color:#ccc; /* text gri deschis */
}
#contact button{
  padding:12px;border-radius:30px;border:none;background:#fff;color:#000;font-weight:600;cursor:pointer;transition:.3s;
}
#contact button:hover{
  background:#ddd;
}
</style>
</head>
<body>

<div class="cursor"></div>

<nav>
  <div class="logo">Kaizoku</div>
  <div class="menu">
    <a href="#process">Proces</a>
    <a href="#performance">Performanță</a>
    <a href="#filosofie">Filosofie</a>
    <a href="#mentenanta">Mentenanță</a>
    <a href="#instalari">Instalări Sisteme de Operare</a>
    <a href="#contact">Aplică</a>
  </div>
</nav>

<header>
  <h1>I Don’t Build PCs.<br>I Engineer Performance.</h1>
  <p>Sisteme optimizate la nivel de arhitectură hardware și software. Fără compromisuri. Fără dezechilibre.</p>
  <a href="#contact" class="btn">Start Your Build</a>
</header>

<section class="highlight">
  <p>✔ Consultanță gratuită &nbsp;&nbsp; ✔ Configurații echilibrate &nbsp;&nbsp; ✔ Garanție montaj &nbsp;&nbsp; ✔ Suport post-instalare</p>
</section>

<section id="process">
  <h2 class="section-title">Procesul Kaizoku</h2>
  <div class="grid">
    <div class="card">
      <h3>01 — Analiză</h3>
      <p>Înțeleg exact workflow-ul tău: gaming competitiv, editare 4K, AI sau development.</p>
    </div>
    <div class="card">
      <h3>02 — Arhitectură</h3>
      <p>Selectez componente echilibrate. Fără bottleneck. Fiecare decizie contează.</p>
    </div>
    <div class="card">
      <h3>03 — Fine Tuning</h3>
      <ul>
        <li>Instalare Windows 11 / Windows 10 / Ubuntu</li>
        <li>Dual Boot</li>
        <li>Drivere & optimizare latență</li>
        <li>Calibrare BIOS & software</li>
      </ul>
    </div>
    <div class="card">
      <h3>04 — Testare</h3>
      <p>Stress test și benchmark real. Rezultatul: performanță maximă cu stabilitate garantată.</p>
    </div>
  </div>
</section>

<section id="performance">
  <h2 class="section-title">Sisteme Construite</h2>
  <div class="grid portfolio">
    <div class="card">
      <h3>Ryzen 7 7800X3D + RTX 4070 Super</h3>
      <ul>
        <li>240 FPS CS2</li>
        <li>170 FPS Warzone</li>
        <li>Temperaturi optime</li>
        <li>Zero throttling</li>
      </ul>
      <img loading="lazy" src="https://www.createpcs.co.uk/wp-content/uploads/2025/09/amd-ryzen-9950x3d-rtx-5090-rog-astral-gaming-pc-30-1024x1024.jpg" style="width:100%; max-width:300px;" />
    </div>
  </div>
</section>

<section id="filosofie">
  <h2 class="section-title">Filosofie</h2>
  <p style="text-align:center;font-size:1.2rem;">Performanta este o disciplină. Nu o bifare. Fiecare sistem este calibrat ca un instrument de precizie.</p>
</section>

<section id="mentenanta">
  <h2 class="section-title">Mentenanță</h2>
  <div class="grid">
    <div class="card">
      <h3>Upgrade-uri, Diagnoze & Îngrijire pe Termen Lung</h3>
      <ul>
        <li>Actualizări hardware și software</li>
        <li>Diagnoză și remediere probleme</li>
        <li>Îngrijire și mentenanță preventivă</li>
      </ul>
    </div>
  </div>
</section>

<!-- Secțiune nouă pentru instalări sisteme de operare -->
<section id="instalari">
  <h2 class="section-title">Instalări Sisteme de Operare</h2>
  <p style="text-align:center;font-size:1.2rem;">Ofer instalare și configurare pentru cele mai populare sisteme de operare: Windows, Linux, macOS.</p>
  <div class="grid">
    <div class="card">
      <h3>Windows</h3>
      <p>Instalare și configurare Windows 10/11 pentru performanță și stabilitate.</p>
    </div>
    <div class="card">
      <h3>Linux</h3>
      <p>Distribuții precum Ubuntu, Fedora, Debian, configurate pentru nevoile tale.</p>
    </div>
    <div class="card">
      <h3>macOS</h3>
      <p>Configurare Hackintosh sau alte servicii legate de macOS.</p>
    </div>
  </div>
</section>

<!-- Secțiunea pentru aplicare -->
<section id="contact">
  <h2 class="section-title">Aplică pentru un Build</h2>
  <p style="text-align:center;margin-bottom:20px;">Răspund în maxim 1 oră. Completează formularul pentru consultanță personalizată.</p>
  <form action="https://formspree.io/f/xbdapado" method="POST">
    <input type="text" name="name" placeholder="Nume" required>
    <input type="email" name="_replyto" placeholder="Email" required>
    <input type="text" name="budget" placeholder="Buget estimativ" required>
    <!-- Select pentru Tip utilizare -->
    <select class="custom-button" name="usage" required>
      <option value="">Tip utilizare</option>
      <option value="gaming">Gaming</option>
      <option value="editare">Editare 3D</option>
      <option value="office">Office</option>
      <option value="programare">Programare/Development</option>
    </select>
    <!-- Select pentru Nivel dorit -->
    <select class="custom-button" name="level" required>
      <option value="">Nivel dorit</option>
      <option value="high">High Performance</option>
      <option value="extreme">Extreme Performance</option>
    </select>
    <textarea name="message" rows="5" placeholder="Detalii suplimentare" required></textarea>
    <button type="submit">Aplică</button>
  </form>
</section>

<footer style="text-align:center;padding:40px 10px;color:#777;background:#000;">
  © 2026 Kaizoku | Performance Lab
</footer>

<!-- Buton WhatsApp -->
<a href="https://wa.me/40746299115" class="whatsapp" title="Trimite mesaj WhatsApp" style="position:fixed;bottom:20px;right:20px;background:#000;border-radius:50%;padding:15px;z-index:999;">
  <i class="fab fa-whatsapp" style="color:#25D366;font-size:1.5rem;"></i>
</a>

<script>
const sections=document.querySelectorAll("section");
const observer=new IntersectionObserver(entries=>{
  entries.forEach(entry=>{if(entry.isIntersecting){entry.target.classList.add("reveal");}});
},{threshold:0.15});
sections.forEach(sec=>observer.observe(sec));

if(window.innerWidth>1024){
  const cursor=document.querySelector(".cursor");
  document.addEventListener("mousemove",(e)=>{
    cursor.style.top=e.clientY+"px";
    cursor.style.left=e.clientX+"px";
  });
}
</script>
</body>
</html>
