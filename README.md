# web-001


<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imagen de Fondo</title>
    <style>
        body {
            background-image: url('fondo n1.jpg'); /* Imagen de fondo */
            background-size: cover; /* Ajusta la imagen para cubrir toda la pantalla */
            background-position: center; /* Centra la imagen */
            background-repeat: no-repeat; /* Evita que la imagen se repita */
            margin: 0;
            font-family: Arial, sans-serif;
            color: white; /* Color del texto */
        }
        h1, p {
            text-align: center; /* Centrar el texto */
        }
    </style>
</head>
<body>
    <h1>¡Hola Mundo!</h1>
    <p></p>
</body>
</html>









<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imágenes con Hipervínculo</title>
    <style>
        .image-link {
            display: inline-block; /* Hace que el enlace se comporte como un bloque */
            margin: 10px; /* Espacio entre imágenes */
        }
        .image-link img {
            max-width: 100%; /* Ajusta el tamaño de la imagen al contenedor */
            height: auto; /* Mantiene la proporción de la imagen */
            border-radius: 10px; /* Bordes redondeados */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Añade sombra a la imagen */
            transition: transform 0.2s; /* Efecto de transición */
        }
        .image-link img:hover {
            transform: scale(1.05); /* Escala la imagen al pasar el ratón */
        }
    </style>
</head>
<body>
    <a href="" class="image-link">
        <img src="fondo 001.gif" alt="Descripción de la imagen 1">
  
  
</body>
</html>


