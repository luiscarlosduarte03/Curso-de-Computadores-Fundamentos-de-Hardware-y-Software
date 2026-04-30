# Curso-de-Computadores-Fundamentos-de-Hardware-y-Software
Proyecto de curso de computadores desarrollado en HTML por Luis Carlos Duarte.
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Curso de Computadores - Luis Carlos Duarte</title>

<style>
    body {
        font-family: 'Segoe UI', sans-serif;
        margin: 0;
        background: linear-gradient(120deg, #1e3c72, #2a5298);
    }

    header {
        background: rgba(0,0,0,0.7);
        color: white;
        text-align: center;
        padding: 25px;
    }

    nav {
        background: #111;
        text-align: center;
        padding: 10px;
    }

    nav a {
        color: #00d4ff;
        margin: 15px;
        text-decoration: none;
        font-weight: bold;
    }

    section {
        background: white;
        margin: 20px;
        padding: 20px;
        border-radius: 10px;
    }

    .card {
        background: #f1f1f1;
        padding: 15px;
        margin-top: 15px;
        border-left: 5px solid #2a5298;
        border-radius: 8px;
    }

    img {
        width: 250px;   
        height: auto;
        border-radius: 10px;
        display: block;
        margin-top: 10px;
    }

    button {
        background: #2a5298;
        color: white;
        border: none;
        padding: 10px 15px;
        border-radius: 5px;
        cursor: pointer;
    }

    footer {
        text-align: center;
        color: white;
        padding: 15px;
    }
</style>
</head>

<body>

<header>
    <h1>Curso de Computadores</h1>
    <p>Creado por Luis Carlos Duarte</p>
</header>

<nav>
    <a href="#">Inicio</a>
    <a href="#">Temas</a>
    <a href="#">Contacto</a>
</nav>

<section>
    <h2>📘 Introducción</h2>
    <p>Este proyecto explica los conceptos básicos de los computadores: hardware, software e internet.</p>
</section>

<section class="card">
    <h2>💻 Hardware</h2><img width="275" height="183" alt="hardware" src="https://github.com/user-attachments/assets/4c31e21c-16c1-4e1c-ae87-765adfb0fbee" />
    <p>El hardware son las partes físicas del computador como la CPU, teclado, mouse, memoria RAM y disco duro.</p>
</section>

<section class="card">
    <h2>🧠 Software</h2>
    <img src="software.jpg"><img width="275" height="183" alt="software" src="https://github.com/user-attachments/assets/6e300fec-5b0e-4c1c-bd97-8fb00ea2ab82" />
    <p>El software son los programas que permiten el funcionamiento del computador, como Windows, Chrome o Word.</p>
</section>

<section class="card">
    <h2>🌐 Internet</h2>
    <p>Internet permite la comunicación entre millones de computadores en todo el mundo.</p>
</section>

<section class="card">
    <h2>⚙️ Componentes principales</h2>
    <ul>
        <li>CPU (Procesador)</li>
        <li>Memoria RAM</li>
        <li>Disco duro</li>
        <li>Tarjeta madre</li>
    </ul>
</section>

<section>
    <h2>📞 Contacto</h2>

    <div class="card">
        <p><strong>Nombre:</strong> Luis Carlos Duarte</p>
        <p><strong>Teléfono:</strong> <a href="tel:3142032426">3142032426</a></p>
        <p><strong>Email:</strong> luis.duarte02@uptc.edu.co</p>
    </div>

    <br>
    <button onclick="mensaje()">Haz clic aquí</button>
</section>

<footer>
    <p>© 2026 Luis Carlos Duarte</p>
</footer>

<script>
function mensaje() {
    alert("¡Bienvenido a mi proyecto 😎!");
}
</script>

</body>
</html>
