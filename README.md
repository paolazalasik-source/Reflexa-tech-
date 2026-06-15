# Reflexa-tech-
REFLEXA TECH é um espelho inteligente com Inteligência Artificial que exibe previsão do tempo, agenda, lembretes e notícias em tempo real. Com comandos de voz e interface moderna, oferece praticidade, conectividade e inovação para tornar a rotina mais eficiente e tecnológica.
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>REFLEXA TECH</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Segoe UI', sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#050816;
    color:white;
}

header{
    position:fixed;
    top:0;
    width:100%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 8%;
    background:rgba(5,8,22,.95);
    backdrop-filter:blur(10px);
    z-index:1000;
}

.logo{
    font-size:30px;
    font-weight:bold;
    color:#00c3ff;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:25px;
    transition:.3s;
}

nav a:hover{
    color:#00c3ff;
}

.hero{
    min-height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:120px 10%;
    background:linear-gradient(rgba(5,8,22,.8), rgba(5,8,22,.9)),
    url('https://images.unsplash.com/photo-1516321318423-f06f85e504b3?w=1600');
    background-size:cover;
    background-position:center;
}

.hero-content{
    max-width:800px;
}

.hero h1{
    font-size:65px;
    margin-bottom:20px;
}

.hero span{
    color:#00c3ff;
}

.hero p{
    font-size:20px;
    color:#d8d8d8;
    margin-bottom:30px;
    line-height:1.7;
}

.btn{
    display:inline-block;
    padding:15px 35px;
    background:#00c3ff;
    color:white;
    text-decoration:none;
    border-radius:40px;
    font-weight:bold;
    transition:.3s;
}

.btn:hover{
    transform:translateY(-3px);
    box-shadow:0 0 20px #00c3ff;
}

section{
    padding:100px 8%;
}

.titulo{
    text-align:center;
    font-size:45px;
    margin-bottom:50px;
}

.sobre{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:40px;
    align-items:center;
}

.sobre img{
    width:100%;
    border-radius:20px;
}

.sobre p{
    line-height:1.9;
    color:#d5d5d5;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#10192e;
    padding:30px;
    border-radius:20px;
    transition:.3s;
}

.card:hover{
    transform:translateY(-10px);
}

.card h3{
    margin-bottom:15px;
    color:#00c3ff;
}

.galeria{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:20px;
}

.galeria img{
    width:100%;
    height:250px;
    object-fit:cover;
    border-radius:20px;
}

.contato{
    text-align:center;
}

.contato p{
    margin:15px 0;
    font-size:18px;
}

footer{
    background:#02040b;
    text-align:center;
    padding:25px;
    color:#aaa;
}

@media(max-width:900px){

.sobre{
    grid-template-columns:1fr;
}

.hero h1{
    font-size:45px;
}

header{
    flex-direction:column;
    gap:15px;
}
}
</style>
</head>

<body>

<header>
    <div class="logo">REFLEXA TECH</div>

    <nav>
        <a href="#inicio">Início</a>
        <a href="#sobre">Sobre</a>
        <a href="#beneficios">Benefícios</a>
        <a href="#galeria">Galeria</a>
        <a href="#contato">Contato</a>
    </nav>
</header>

<section class="hero" id="inicio">
    <div class="hero-content">
        <h1>Espelho Inteligente com <span>Inteligência Artificial</span></h1>

        <p>
            Tecnologia, praticidade e inovação em um único produto.
            Receba informações em tempo real, utilize comandos de voz
            e tenha uma experiência totalmente personalizada.
        </p>

        <a href="#sobre" class="btn">Conhecer Projeto</a>
    </div>
</section>

<section id="sobre">
    <h2 class="titulo">Sobre o Projeto</h2>

    <div class="sobre">

        <img src="https://images.unsplash.com/photo-1556740749-887f6717d7e4?w=1000">

        <div>
            <p>
                O REFLEXA TECH é um espelho inteligente equipado com
                Inteligência Artificial capaz de exibir informações úteis
                enquanto o usuário realiza suas atividades diárias.
            </p>

            <br>

            <p>
                O sistema apresenta clima, agenda, lembretes,
                notícias e recursos personalizados através de uma
                interface moderna e intuitiva.
            </p>
        </div>

    </div>
</section>

<section id="beneficios">
    <h2 class="titulo">Benefícios</h2>

    <div class="cards">

        <div class="card">
            <h3>🤖 IA Integrada</h3>
            <p>Assistente inteligente para facilitar a rotina.</p>
        </div>

        <div class="card">
            <h3>📅 Agenda Digital</h3>
            <p>Visualização de compromissos em tempo real.</p>
        </div>

        <div class="card">
            <h3>🌦 Previsão do Tempo</h3>
            <p>Informações climáticas atualizadas.</p>
        </div>

        <div class="card">
            <h3>🎤 Comando por Voz</h3>
            <p>Controle funções sem tocar na tela.</p>
        </div>

        <div class="card">
            <h3>🔒 Segurança</h3>
            <p>Reconhecimento facial personalizado.</p>
        </div>

        <div class="card">
            <h3>📱 Conectividade</h3>
            <p>Integração com smartphones e dispositivos.</p>
        </div>

    </div>
</section>

<section id="galeria">
    <h2 class="titulo">Galeria</h2>

    <div class="galeria">

        <img src="https://images.unsplash.com/photo-1497366754035-f200968a6e72?w=800">

        <img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?w=800">

        <img src="https://images.unsplash.com/photo-1556740749-887f6717d7e4?w=800">

    </div>
</section>

<section class="contato" id="contato">
    <h2 class="titulo">Contato</h2>

    <p>📧 contato@reflexatech.com</p>
    <p>📱 47 93549-7623</p>

    <br>

    <a href="#" class="btn">Solicitar Demonstração</a>
</section>

<footer>
    © 2026 REFLEXA TECH - Todos os direitos reservados.
</footer>

</body>
</html>