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
  background-image: url('https://images.pexels.com/photos/3184427/pexels-photo-3184427.jpeg');
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
  text-align: center;
}
.course img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 10px;
}
.course p { font-size: 14px; color: #374151; }
.price { font-size: 18px; color: #16a34a; font-weight: bold; margin-bottom: 10px; }

.btn {
  display: inline-block;
  margin: 5px 5px 0 0;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  text-align: center;
  line-height: 40px;
  transition: 0.3s;
}
.btn img { width: 20px; }

.btn-facebook { background: #1877f2; }
.btn-instagram { background: #e1306c; }
.btn-whatsapp { background: #25d366; }
.btn:hover { opacity: 0.8; }

#about {
  background: #fff;
  padding: 30px;
  border-radius: 10px;
  margin-top: 40px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
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
}
.contact-box img { width: 50px; }
.contact-box a { display: block; margin-top: 8px; text-decoration: none; color:#1e40af; font-weight:bold; }

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

<!-- CURSO 1 -->
<div class="course">
  <img src="https://images.pexels.com/photos/3184427/pexels-photo-3184427.jpeg" alt="Informática Básica">
  <h3>Informática Básica</h3>
  <p>Computador, internet, Word e Excel do zero.</p>
  <p class="price">MZN 1000</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Informática%20Básica" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 2 -->
<div class="course">
  <img src="https://images.pexels.com/photos/414519/pexels-photo-414519.jpeg" alt="Informática Avançada">
  <h3>Informática Avançada</h3>
  <p>Softwares, redes e soluções avançadas.</p>
  <p class="price">MZN 1500</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Informática%20Avançada" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 3 -->
<div class="course">
  <img src="https://images.pexels.com/photos/1181675/pexels-photo-1181675.jpeg" alt="Design Gráfico">
  <h3>Design Gráfico</h3>
  <p>Photoshop, Illustrator e criação de artes visuais.</p>
  <p class="price">MZN 2000</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Design%20Gráfico" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 4 -->
<div class="course">
  <img src="https://images.pexels.com/photos/3184298/pexels-photo-3184298.jpeg" alt="Marketing Digital">
  <h3>Marketing Digital</h3>
  <p>Estratégias online, redes sociais e anúncios.</p>
  <p class="price">MZN 1800</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Marketing%20Digital" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 5 -->
<div class="course">
  <img src="https://images.pexels.com/photos/1181622/pexels-photo-1181622.jpeg" alt="Fotografia Digital">
  <h3>Fotografia Digital</h3>
  <p>Aperfeiçoe suas fotos com técnicas profissionais.</p>
  <p class="price">MZN 1700</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Fotografia%20Digital" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 6 -->
<div class="course">
  <img src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg" alt="Programação Web">
  <h3>Programação Web</h3>
  <p>HTML, CSS, JavaScript e frameworks modernos.</p>
  <p class="price">MZN 2200</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Programação%20Web" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 7 -->
<div class="course">
  <img src="https://images.pexels.com/photos/3861972/pexels-photo-3861972.jpeg" alt="Excel Avançado">
  <h3>Excel Avançado</h3>
  <p>Fórmulas, gráficos e dashboards profissionais.</p>
  <p class="price">MZN 1300</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Excel%20Avançado" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 8 -->
<div class="course">
  <img src="https://images.pexels.com/photos/3861975/pexels-photo-3861975.jpeg" alt="Programação Python">
  <h3>Programação Python</h3>
  <p>Aprenda Python do básico ao avançado.</p>
  <p class="price">MZN 2100</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Programação%20Python" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>
<!-- CURSO 9 -->
<div class="course">
  <img src="https://images.pexels.com/photos/3184631/pexels-photo-3184631.jpeg" alt="Redes de Computadores">
  <h3>Redes de Computadores</h3>
  <p>Configuração de redes, segurança e protocolos.</p>
  <p class="price">MZN 1900</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Redes%20de%20Computadores" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 10 -->
<div class="course">
  <img src="https://images.pexels.com/photos/3861966/pexels-photo-3861966.jpeg" alt="JavaScript Avançado">
  <h3>JavaScript Avançado</h3>
  <p>Manipulação de DOM, eventos e APIs.</p>
  <p class="price">MZN 2300</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20JavaScript%20Avançado" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 11 -->
<div class="course">
  <img src="https://images.pexels.com/photos/1181263/pexels-photo-1181263.jpeg" alt="Banco de Dados SQL">
  <h3>Banco de Dados SQL</h3>
  <p>Criação e gestão de bancos de dados relacionais.</p>
  <p class="price">MZN 2000</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Banco%20de%20Dados%20SQL" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 12 -->
<div class="course">
  <img src="https://images.pexels.com/photos/3861977/pexels-photo-3861977.jpeg" alt="Python para Data Science">
  <h3>Python para Data Science</h3>
  <p>Análise de dados e machine learning com Python.</p>
  <p class="price">MZN 2500</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Python%20para%20Data%20Science" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 13 -->
<div class="course">
  <img src="https://images.pexels.com/photos/1181273/pexels-photo-1181273.jpeg" alt="Inteligência Artificial">
  <h3>Inteligência Artificial</h3>
  <p>Conceitos de IA e implementação de modelos inteligentes.</p>
  <p class="price">MZN 3000</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Inteligência%20Artificial" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 14 -->
<div class="course">
  <img src="https://images.pexels.com/photos/1181269/pexels-photo-1181269.jpeg" alt="Machine Learning">
  <h3>Machine Learning</h3>
  <p>Criação de modelos preditivos e análise de dados.</p>
  <p class="price">MZN 3200</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Machine%20Learning" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>
<!-- CURSO 15 -->
<div class="course">
  <img src="https://images.pexels.com/photos/1181244/pexels-photo-1181244.jpeg" alt="Desenvolvimento Mobile">
  <h3>Desenvolvimento Mobile</h3>
  <p>Crie apps para Android e iOS do básico ao avançado.</p>
  <p class="price">MZN 2800</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Desenvolvimento%20Mobile" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 16 -->
<div class="course">
  <img src="https://images.pexels.com/photos/1181353/pexels-photo-1181353.jpeg" alt="Segurança da Informação">
  <h3>Segurança da Informação</h3>
  <p>Proteja dados, sistemas e redes corporativas.</p>
  <p class="price">MZN 2600</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Segurança%20da%20Informação" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 17 -->
<div class="course">
  <img src="https://images.pexels.com/photos/3184642/pexels-photo-3184642.jpeg" alt="Animação 3D">
  <h3>Animação 3D</h3>
  <p>Modelagem, rigging e animação em softwares 3D.</p>
  <p class="price">MZN 3000</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Animação%203D" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 18 -->
<div class="course">
  <img src="https://images.pexels.com/photos/3184291/pexels-photo-3184291.jpeg" alt="Edição de Vídeo">
  <h3>Edição de Vídeo</h3>
  <p>Adobe Premiere, After Effects e técnicas de produção.</p>
  <p class="price">MZN 2400</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Edição%20de%20Vídeo" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 19 -->
<div class="course">
  <img src="https://images.pexels.com/photos/3184639/pexels-photo-3184639.jpeg" alt="Marketing de Conteúdo">
  <h3>Marketing de Conteúdo</h3>
  <p>Criação de conteúdo estratégico para redes e blogs.</p>
  <p class="price">MZN 2100</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Marketing%20de%20Conteúdo" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>

<!-- CURSO 20 -->
<div class="course">
  <img src="https://images.pexels.com/photos/3184301/pexels-photo-3184301.jpeg" alt="Design UX/UI">
  <h3>Design UX/UI</h3>
  <p>Experiência do usuário, prototipagem e interfaces.</p>
  <p class="price">MZN 2700</p>
  <a class="btn btn-email" href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Gmail"></a>
  <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
  <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
  <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Quero%20me%20matricular%20no%20curso%20de%20Design%20UX/UI" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>
</div> <!-- Fim da seção de cursos -->

<!-- SOBRE NÓS -->
<div id="about">
<h2>Sobre Nós</h2>
<p>Na Clemente Cursos Online oferecemos cursos completos e práticos para todas as áreas de tecnologia, design e marketing. Nosso objetivo é capacitar você para o mercado de trabalho com habilidades atuais e aplicáveis.</p>
</div>

<!-- CONTACTOS -->
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
<a href="https://wa.me/258833786021" target="_blank">+258 83 378 6021</a>
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

<!-- RODAPÉ -->
<footer>
© 2026 Clemente Cursos Online | Ensino simples e acessível
</footer>

<!-- BOTÃO FLUTUANTE WHATSAPP -->
<a href="https://wa.me/258833786021?text=Olá,%20quero%20saber%20mais%20sobre%20os%20cursos" 
class="whatsapp-float" target="_blank">
<img src="https://cdn-icons-png.flaticon.com/512/733/733585.png">
</a>

