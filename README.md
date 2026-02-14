<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Clemente Cursos Online</title>

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

.course p { font-size: 14px; color: #374151; }

.price { font-size: 18px; color: #16a34a; font-weight: bold; }

.btn {
  display: block;
  margin-top: 10px;
  padding: 10px;
  background: #22c55e;
  color: #fff;
  text-decoration: none;
  border-radius: 6px;
  font-weight: bold;
  text-align: center;
  transition: 0.3s;
}

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

<!-- Curso 1 -->
<div class="course">
<h3>Informática Básica</h3>
<p>Aprenda computador, internet, Word e Excel do zero.</p>
<p class="price">MZN 1000</p>
<a class="btn" href="mailto:clementesoca00@gmail.com">Matricular por Gmail</a>
<a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank">Facebook</a>
<a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank">Instagram</a>
<a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Olá,%20quero%20me%20matricular%20no%20curso%20de%20Informática%20Básica" target="_blank">WhatsApp</a>
</div>

<!-- Curso 2 -->
<div class="course">
<h3>Informática Avançada</h3>
<p>Aprofunde conhecimentos em softwares e redes.</p>
<p class="price">MZN 1500</p>
<a class="btn" href="mailto:clementesoca00@gmail.com">Matricular por Gmail</a>
<a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank">Facebook</a>
<a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank">Instagram</a>
<a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Olá,%20quero%20me%20matricular%20no%20curso%20de%20Informática%20Avançada" target="_blank">WhatsApp</a>
</div>

<!-- Se houver mais cursos, basta duplicar e atualizar o nome do curso no link WhatsApp -->

</div>

<div id="about">
<h2>Sobre Nós</h2>
<p>Oferecemos cursos práticos e acessíveis para desenvolver suas habilidades e melhorar sua carreira.</p>
</div>

<div id="contact" class="benefits">
<h2>Contactos</h2>
<div class="contact-container">

<div class="contact-box">
<img src="https://cdn-icons-png.flaticon.com/512/732/732200.png">
<p>Email</p>
<a href="mailto:clementesoca00@gmail.com">clementesoca00@gmail.com</a>
</div>

<div class="contact-box">
<img src="https://cdn-icons-png.flaticon.com/512/733/733585.png">
<p>WhatsApp</p>
<a href="https://wa.me/258833786021" target="_blank">Falar no WhatsApp</a>
</div>

<div class="contact-box">
<img src="https://cdn-icons-png.flaticon.com/512/733/733547.png">
<p>Facebook</p>
<a href="https://www.facebook.com/messages/t/socaclemente" target="_blank">socaclemente</a>
</div>

<div class="contact-box">
<img src="https://cdn-icons-png.flaticon.com/512/733/733558.png">
<p>Instagram</p>
<a href="https://instagram.com/socaclemente" target="_blank">@socaclemente</a>
</div>

</div>
</div>

</div>

<footer>
© 2026 Clemente Cursos Online | Ensino simples e acessível
</footer>

<a href="https://wa.me/258833786021?text=Olá,%20quero%20saber%20mais%20sobre%20os%20cursos" 
class="whatsapp-float" target="_blank">
<img src="https://cdn-icons-png.flaticon.com/512/733/733585.png">
</a>

</body>
</html>
