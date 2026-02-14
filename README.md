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
  text-align: center;
}

.course:hover { transform: translateY(-5px); }

.course img {
  width: 100%;
  max-height: 150px;
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

.btn img { width: 20px; vertical-align: middle; }

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

.contact-box img { width: 50px; }

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

<!-- Gerando 20 cursos com imagens únicas -->
<script>
const cursos = [
  {nome:"Informática Básica", desc:"Aprenda computador, internet, Word e Excel do zero.", preco:"MZN 1000", img:"https://images.unsplash.com/photo-1581090700227-90c9ff5cce16?auto=format&fit=crop&w=800&q=80"},
  {nome:"Informática Avançada", desc:"Aprofunde conhecimentos em softwares e redes.", preco:"MZN 1500", img:"https://images.unsplash.com/photo-1581093457681-c2b34a64b0c1?auto=format&fit=crop&w=800&q=80"},
  {nome:"Design Gráfico", desc:"Aprenda Photoshop, Illustrator e técnicas de design profissional.", preco:"MZN 2000", img:"https://images.unsplash.com/photo-1590608897129-79f8f80b0917?auto=format&fit=crop&w=800&q=80"},
  {nome:"Marketing Digital", desc:"Domine estratégias de redes sociais e anúncios online.", preco:"MZN 1800", img:"https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=800&q=80"},
  {nome:"Fotografia", desc:"Aprenda fotografia profissional e edição de imagens.", preco:"MZN 1700", img:"https://images.unsplash.com/photo-1519681393784-d120267933ba?auto=format&fit=crop&w=800&q=80"},
  {nome:"Programação Web", desc:"Crie websites usando HTML, CSS e JavaScript.", preco:"MZN 2200", img:"https://images.unsplash.com/photo-1557804506-669a67965ba0?auto=format&fit=crop&w=800&q=80"},
  {nome:"Python para Iniciantes", desc:"Aprenda Python do zero e crie seus próprios programas.", preco:"MZN 2000", img:"https://images.unsplash.com/photo-1581090700223-0f993f8407c2?auto=format&fit=crop&w=800&q=80"},
  {nome:"Excel Avançado", desc:"Domine fórmulas, gráficos e tabelas dinâmicas.", preco:"MZN 1500", img:"https://images.unsplash.com/photo-1581090700225-13f35a5dc8e6?auto=format&fit=crop&w=800&q=80"},
  {nome:"Gestão de Projetos", desc:"Aprenda a gerenciar projetos com ferramentas profissionais.", preco:"MZN 2500", img:"https://images.unsplash.com/photo-1581090700221-08b3f7b50aa8?auto=format&fit=crop&w=800&q=80"},
  {nome:"Redes de Computadores", desc:"Entenda redes, servidores e protocolos.", preco:"MZN 2100", img:"https://images.unsplash.com/photo-1581090700220-0e6c4a5a4b30?auto=format&fit=crop&w=800&q=80"},
  {nome:"Inglês Básico", desc:"Aprenda o inglês do zero de forma prática.", preco:"MZN 1200", img:"https://images.unsplash.com/photo-1581090700218-0f9b2a5a5b01?auto=format&fit=crop&w=800&q=80"},
  {nome:"Inglês Avançado", desc:"Aprimore o inglês para negócios e viagens.", preco:"MZN 1800", img:"https://images.unsplash.com/photo-1581090700217-1f9b2a5a5b02?auto=format&fit=crop&w=800&q=80"},
  {nome:"Programação Java", desc:"Aprenda Java do básico ao avançado.", preco:"MZN 2300", img:"https://images.unsplash.com/photo-1581090700216-2f9b2a5a5b03?auto=format&fit=crop&w=800&q=80"},
  {nome:"Desenvolvimento Mobile", desc:"Crie apps para Android e iOS.", preco:"MZN 2500", img:"https://images.unsplash.com/photo-1581090700215-3f9b2a5a5b04?auto=format&fit=crop&w=800&q=80"},
  {nome:"SEO e Marketing", desc:"Aprenda técnicas de SEO e marketing de conteúdo.", preco:"MZN 2000", img:"https://images.unsplash.com/photo-1581090700214-4f9b2a5a5b05?auto=format&fit=crop&w=800&q=80"},
  {nome:"Edição de Vídeo", desc:"Domine Premiere, After Effects e edição criativa.", preco:"MZN 2200", img:"https://images.unsplash.com/photo-1581090700213-5f9b2a5a5b06?auto=format&fit=crop&w=800&q=80"},
  {nome:"Autocad", desc:"Aprenda desenho técnico e projetos arquitetônicos.", preco:"MZN 2400", img:"https://images.unsplash.com/photo-1581090700212-6f9b2a5a5b07?auto=format&fit=crop&w=800&q=80"},
  {nome:"WordPress", desc:"Crie sites profissionais sem precisar programar.", preco:"MZN 1800", img:"https://images.unsplash.com/photo-1581090700211-7f9b2a5a5b08?auto=format&fit=crop&w=800&q=80"},
  {nome:"Redação e Comunicação", desc:"Aprenda técnicas de escrita e comunicação eficaz.", preco:"MZN 1500", img:"https://images.unsplash.com/photo-1581090700210-8f9b2a5a5b09?auto=format&fit=crop&w=800&q=80"},
  {nome:"Finanças Pessoais", desc:"Organize suas finanças e aprenda a investir.", preco:"MZN 2000", img:"https://images.unsplash.com/photo-1581090700209-9f9b2a5a5b10?auto=format&fit=crop&w=800&q=80"}
];

const container = document.querySelector('.courses');
cursos.forEach(c => {
  container.innerHTML += `
  <div class="course">
    <img src="${c.img}" alt="${c.nome}">
    <h3>${c.nome}</h3>
    <p>${c.desc}</p>
    <p class="price">${c.preco}</p>
    <a class="btn" href="mailto:clementesoca00@gmail.com" title="Gmail"><img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" alt="Gmail"></a>
    <a class="btn btn-facebook" href="https://www.facebook.com/messages/t/socaclemente" target="_blank" title="Facebook"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
    <a class="btn btn-instagram" href="https://instagram.com/socaclemente" target="_blank" title="Instagram"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
    <a class="btn btn-whatsapp" href="https://wa.me/258833786021?text=Olá,%20quero%20me%20matricular%20no%20curso%20de%20${encodeURIComponent(c.nome)}" target="_blank" title="WhatsApp"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
  </div>`;
});
</script>

</div>

<div id="about">
<h2>Sobre Nós</h2>
<p>Oferecemos cursos práticos e acessíveis para desenvolver suas habilidades e melhorar sua carreira.</p>
</div>

<div id="contact" class="benefits">
<h2>Contactos</h2>
<div class="contact-container">
<div class="contact-box">
<a href="mailto:clementesoca00@gmail.com"><img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" alt="Email"></a>
</div>
<div class="contact-box">
<a href="https://wa.me/258833786021" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp"></a>
</div>
<div class="contact-box">
<a href="https://www.facebook.com/messages/t/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
</div>
<div class="contact-box">
<a href="https://instagram.com/socaclemente" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram"></a>
</div>
</div>
</div>

<footer>
© 2026 Clemente Cursos Online | Ensino simples e acessível
</footer>

<a href="https://wa.me/258833786021?text=Olá,%20quero%20saber%20mais%20sobre%20os%20cursos" class="whatsapp-float" target="_blank">
<img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp">
</a>

</body>
</html>
