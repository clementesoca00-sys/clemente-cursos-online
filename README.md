<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />

<style>
body { margin: 0; font-family: Arial, sans-serif; background: #f3f4f6; }

header {
  background: #1e40af;
  color: #fff;
  padding: 40px;
  text-align: center;
  background-image: url('https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1350&q=80');
  background-size: cover;
  background-position: center;
}

header h1, header p {
  background: rgba(0,0,0,0.6);
  display: inline-block;
  padding: 10px 20px;
  border-radius: 10px;
}

nav {
  background: #1e3a8a;
  padding: 12px;
  text-align: center;
}

nav a {
  color: #fff;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover { text-decoration: underline; }

.container { padding: 30px; }

h2 { text-align: center; margin-bottom: 20px; }

.courses {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.course {
  background: #fff;
  border-radius: 12px;
  padding: 20px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  transition: 0.3s;
}

.course:hover { transform: translateY(-5px); }

.course img { width: 100%; border-radius: 10px; margin-bottom: 10px; }

.course p { font-size: 14px; color: #374151; }

.price { font-size: 18px; color: #16a34a; font-weight: bold; }

.btn {
  display: inline-block;
  margin: 5px 5px 0 0;
  padding: 8px;
  background: #22c55e;
  color: #fff;
  text-decoration: none;
  border-radius: 6px;
  font-weight: bold;
  text-align: center;
  transition: 0.3s;
}

.btn img { width: 20px; vertical-align: middle; }

.btn:hover { opacity: 0.8; }

.btn-facebook { background: #1877f2; }
.btn-instagram { background: #e1306c; }
.btn-whatsapp { background: #25d366; }

#about {
  background: #fff;
  padding: 30px;
  border-radius: 10px;
  margin-top: 40px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.benefits {
  background: #fff;
  margin-top: 40px;
  padding: 30px;
  border-radius: 10px;
}

.contact-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.contact-box {
  background: #f9fafb;
  padding: 20px;
  border-radius: 12px;
  text-align: center;
  box-shadow: 0 4px 10px rgba(0,0,0,0.08);
  transition: 0.3s;
}

.contact-box:hover { transform: translateY(-5px); }

.contact-box img { width: 40px; margin-bottom: 10px; }

.contact-box a {
  text-decoration: none;
  font-weight: bold;
  color: #1e40af;
}

footer {
  background: #1e40af;
  color: #fff;
  text-align: center;
  padding: 20px;
  margin-top: 40px;
}

/* Botão flutuante */
.whatsapp-float {
  position: fixed;
  width: 60px;
  height: 60px;
  bottom: 20px;
  right: 20px;
  background-color: #25d366;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 2px 2px 10px rgba(0,0,0,0.3);
  z-index: 100;
}
.whatsapp-float img { width: 35px; }
</style>
</head>

<body>

<header>
  <h1>Clemente Cursos Online</h1>
  <p>Aprenda novas habilidades e mude seu futuro</p>
</header>

<nav>
  <a href="#">Início</a>
  <a href="#courses">Cursos</a>
  <a href="#about">Sobre</a>
  <a href="#contact">Contactos</a>
</nav>

<div class="container">

<h2 id="courses">Cursos Disponíveis</h2>

<div class="courses">

<!-- CURSOS 1 a 20 -->
<!-- Copie os cursos completos dos blocos anteriores aqui -->
<!-- Para economizar espaço, aqui colocamos apenas um exemplo. No seu HTML final, cole todos os 20 cursos que eu te passei nos passos anteriores -->

<!-- CURSO 1 -->
<div class="course">
<img src="https://images.pexels.com/photos/3861964/pexels-photo-3861964.jpeg" alt="Informática Básica">
<h3>Informática Básica</h3>
<p>Aprenda computador, internet, Word e Excel do zero.</p>
<p class="price">MZN 1000</p>
<a class="btn" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" alt=""></a>
<a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt=""></a>
<a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt=""></a>
<a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Informática%20Básica" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt=""></a>
</div>

<!-- Insira aqui os cursos 2 a 20 seguindo o mesmo padrão -->

</div> <!-- /courses -->

<div id="about">
<h2>Sobre Nós</h2>
<p>O Clemente Cursos Online oferece cursos de alta qualidade para todos os níveis, com foco em prática e aprendizado real. Nossa missão é capacitar pessoas através do ensino acessível e de ferramentas modernas, permitindo que você desenvolva habilidades para sua carreira ou negócio.</p>
</div>

<div id="contact" class="benefits">
<h2>Contactos</h2>
<div class="contact-container">

<div class="contact-box">
<img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" alt="Email">
<a href="mailto:clementesoca00@gmail.com">clementesoca00@gmail.com</a>
</div>

<div class="contact-box">
<img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp">
<a href="https://wa.me/258833786021" target="_blank">Falar no WhatsApp</a>
</div>

<div class="contact-box">
<img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook">
<a href="https://www.facebook.com/messages/t/socaclemente" target="_blank">socaclemente</a>
</div>

<div class="contact-box">
<img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram">
<a href="https://instagram.com/socaclemente" target="_blank">@socaclemente</a>
</div>

</div>
</div>

</div> <!-- /container -->

<footer>
© 2026 Clemente Cursos Online | Ensino simples e acessível
</footer>

<a href="https://wa.me/258833786021?text=Olá,%20quero%20saber%20mais%20sobre%20os%20cursos" 
class="whatsapp-float" target="_blank">
<img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp">
</a>

</body>
</html>
