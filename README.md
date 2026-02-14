<!DOCTYPE html>
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
  grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
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

.contact-box img {
  width: 50px;
}

.contact-box a {
  display: block;
  margin-top: 8px;
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

<!-- Curso 3 -->
<div class="course">
<h3>Design Gráfico</h3>
<p>Aprenda Photoshop, Illustrator, edição de imagens e criação de artes digitais.</p>
<p class="price">MZN 2000</p>
<a class="btn" href="mailto:clementesoca00@gmail.com">Matricular por Gmail</a>
<a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank">Facebook</a>
<a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank">Instagram</a>
<a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Olá,%20quero%20me%20matricular%20no%20curso%20de%20Design%20Gráfico" target="_blank">WhatsApp</a>
</div>

<!-- Curso 4 -->
<div class="course">
<h3>Marketing Digital</h3>
<p>Aprenda estratégias de marketing online, redes sociais, anúncios e SEO.</p>
<p class="price">MZN 1800</p>
<a class="btn" href="mailto:clementesoca00@gmail.com">Matricular por Gmail</a>
<a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank">Facebook</a>
<a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank">Instagram</a>
<a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Olá,%20quero%20me%20matricular%20no%20curso%20de%20Marketing%20Digital" target="_blank">WhatsApp</a>
</div>

<!-- Curso 5 -->
<div class="course">
<h3>Redes de Computadores</h3>
<p>Aprenda configuração de redes, roteadores, switches e segurança de rede.</p>
<p class="price">MZN 2200</p>
<a class="btn" href="mailto:clementesoca00@gmail.com">Matricular por Gmail</a>
<a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank">Facebook</a>
<a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank">Instagram</a>
<a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Olá,%20quero%20me%20matricular%20no%20curso%20de%20Redes%20de%20Computadores" target="_blank">WhatsApp</a>
</div>

<!-- Curso 6 -->
<div class="course">
<h3>Programação Web</h3>
<p>HTML, CSS, JavaScript, criação de sites responsivos e interativos.</p>
<p class="price">MZN 2000</p>
<a class="btn" href="mailto:clementesoca00@gmail.com">Matricular por Gmail</a>
<a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank">Facebook</a>
<a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank">Instagram</a>
<a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Olá,%20quero%20me%20matricular%20no%20curso%20de%20Programação%20Web" target="_blank">WhatsApp</a>
</div>

<!-- Curso 7 -->
<div class="course">
<h3>Excel Avançado</h3>
<p>Funções avançadas, tabelas dinâmicas e automação de planilhas.</p>
<p class="price">MZN 1800</p>
<a class="btn" href="mailto:clementesoca00@gmail.com">Matricular por Gmail</a>
<a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank">Facebook</a>
<a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank">Instagram</a>
<a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Olá,%20quero%20me%20matricular%20no%20curso%20de%20Excel%20Avançado" target="_blank">WhatsApp</a>
</div>

<!-- Curso 8 -->
<div class="course">
<h3>Python para Iniciantes</h3>
<p>Aprenda lógica de programação, estruturas de dados e scripts simples em Python.</p>
<p class="price">MZN 2000</p>
<a class="btn" href="mailto:clementesoca00@gmail.com">Matricular por Gmail</a>
<a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank">Facebook</a>
<a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank">Instagram</a>
<a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Olá,%20quero%20me%20matricular%20no%20curso%20de%20Python%20para%20Iniciantes" target="_blank">WhatsApp</a>
</div>

<!-- Curso 9 -->
<div class="course">
<h3>Java Avançado</h3>
<p>Programação orientada a objetos, APIs e desenvolvimento de aplicações complexas.</p>
<p class="price">MZN 2500</p>
<a class="btn" href="mailto:clementesoca00@gmail.com">Matricular por Gmail</a>
<a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank">Facebook</a>
<a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank">Instagram</a>
<a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Olá,%20quero%20me%20matricular%20no%20curso%20de%20Java%20Avançado" target="_blank">WhatsApp</a>
</div>

<!-- Curso 10 -->
<div class="course">
<h3>Segurança Cibernética</h3>
<p>Aprenda proteção de dados, antivírus, firewalls e técnicas de segurança online.</p>
<p class="price">MZN 2300</p>
<a class="btn" href="mailto:clementesoca00@gmail.com">Matricular por Gmail</a>
<a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank">Facebook</a>
<a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank">Instagram</a>
<a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Olá,%20quero%20me%20matricular%20no%20curso%20de%20Segurança%20Cibernética" target="_blank">WhatsApp</a>
</div>

</div>

<div id="about">
<h2>Sobre Nós</h2>
<p>Oferecemos cursos práticos e acessíveis para desenvolver suas habilidades e melhorar sua carreira.</p>
</div>

<div id="contact" class="benefits">
<h2>Contactos</h2>
<div class="contact-container">

<div class="contact-box">
<a href="mailto:clementesoca00@gmail.com">
<img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" alt="Email">
</a>
</div>

<div class="contact-box">
<a href="https://wa.me/258833786021" target="_blank">
<img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp">
</a>
</div>

<div class="contact-box">
<a href="https://www.facebook.com/messages/t/socaclemente" target="_blank">
<img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook">
</a>
</div>

<div class="contact-box">
<a href="https://instagram.com/socaclemente" target="_blank">
<img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram">
</a>
</div>

</div>
</div>

</div>

<footer>
© 2026 Clemente Cursos Online | Ensino simples e acessível
</footer>

<a href="https://wa.me/258833786021?text=Olá,%20quero%20saber%20mais%20sobre%20os%20cursos" 
class="whatsapp-float" target="_blank">
<img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp">
</a>

</body>
</html>
