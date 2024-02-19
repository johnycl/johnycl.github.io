---

title: "Gallery"
layaut: post
---
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galería de Perros</title>
    <style>
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            grid-gap: 10px;
            justify-items: center;
        }
        .gallery img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <h1>Galería de Perros</h1>
    <div class="gallery">
        <img src="https://media.istockphoto.com/id/513133900/es/foto/oro-retriever-sentado-en-frente-de-un-fondo-blanco.jpg?s=612x612&w=0&k=20&c=0lRWImB8Y4p6X6YGt06c6q8I3AqBgKD-OGQxjLCI5EY=" alt="Perro 1">
        <img src="https://img.freepik.com/foto-gratis/aislado-feliz-sonriente-perro-fondo-blanco-retrato-4_1562-693.jpg?size=626&ext=jpg " alt="Perro 2">
        <img src="https://img.freepik.com/foto-gratis/perro-gracioso-beagle-feliz-caminando-jugando-parque_176420-6453.jpg?size=626&ext=jpg&ga=GA1.1.1270795388.1708374543&semt=sph" alt="Perro 3">
    </div>
</body>
</html>