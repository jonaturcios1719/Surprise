<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sorpresa de San Valentín</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #ffe6e6;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff99cc;
            padding: 20px;
            color: white;
        }
        header img {
            width: 200px;
            height: auto;
            margin-top: 10px;
        }
        h1 {
            font-size: 2.5em;
            margin-top: 20px;
        }
        .container {
            padding: 30px;
        }
        .input-container {
            margin: 20px 0;
        }
        input[type="text"] {
            padding: 10px;
            font-size: 1.2em;
            width: 300px;
            margin-top: 10px;
        }
        button {
            background-color: #ff66b2;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 1.2em;
            cursor: pointer;
            margin-top: 10px;
        }
        button:hover {
            background-color: #ff3385;
        }
        footer {
            margin-top: 30px;
            font-size: 0.9em;
            color: #555;
        }
    </style>
</head>
<body>

<header>
    <img src="https://img.freepik.com/vector-gratis/pareja-osos-koala-plana-san-valentin_23-2148815087.jpg">
    <h1> Hola Querida Mochito ❤️❤️❤️</h1>
</header>

<div class="container">
    <p>¿Would You Be My Valentine🐨❤️?</p>
    <div class="input-container">
        <input type="text" id="respuesta" placeholder="Escribe aquí 'Sí' o 'No'">
    </div>
    <button onclick="mostrarRespuesta()">Enviar</button>
    <p id="mensajeRespuesta" style="font-size: 1.5em; color: #ff66b2; margin-top: 20px;"></p>
</div>

<footer>
    <p>Hecho con amor para ti ❤️</p>
</footer>

<script>
    function mostrarRespuesta() {
        const respuesta = document.getElementById('respuesta').value.toLowerCase();
        const mensaje = document.getElementById('mensajeRespuesta');
        
        if (respuesta === 'sí' || respuesta === 'si') {
            mensaje.innerText = 'AAAAAA TE AMO MOCHIIIII ❤️';
        } else if (respuesta === 'no') {
            mensaje.innerText = 'Ya no me ama? 😢';
        } else {
            mensaje.innerText = 'Escriba "Sí" o "No" mochiiiii jeje';
        }
    }
</script>

</body>
</html>
