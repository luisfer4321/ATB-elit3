# ATB-elit3
Primera versión de mi página"
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Perfil en Línea</title>
    <link rel="icon" href="https://www.tiktok.com/favicon.ico" type="image/x-icon">
    <style>
        /* Estilos generales */
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            margin: 0;
            padding: 20px;
            background-color: #f0f2f5; /* Un gris claro para el fondo */
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh; /* Asegura que ocupe toda la altura de la ventana */
            box-sizing: border-box; /* Incluye padding y borde en el tamaño total */
        }

        /* Contenedor principal de la tarjeta */
        .container {
            background-color: #ffffff; /* Fondo blanco para la tarjeta */
            border-radius: 12px; /* Esquinas más redondeadas */
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1); /* Sombra suave */
            padding: 30px;
            max-width: 450px; /* Ancho máximo para la tarjeta */
            width: 100%; /* Ocupa todo el ancho disponible dentro del max-width */
            box-sizing: border-box;
            animation: fadeIn 1s ease-out; /* Animación de aparición */
        }

        /* Animación para que la tarjeta aparezca suavemente */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Estilos para el encabezado */
        h1 {
            color: #000; /* Negro para el título */
            font-size: 2.2em; /* Tamaño de fuente más grande */
            margin-bottom: 15px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.05); /* Sombra de texto sutil */
        }

        /* Estilos para el párrafo de descripción */
        p {
            font-size: 1.1em;
            line-height: 1.6;
            margin-bottom: 25px;
            color: #555;
        }

        /* Estilos para el botón de TikTok */
        .tiktok-link {
            display: inline-flex; /* Permite alinear el icono y el texto */
            align-items: center; /* Centra verticalmente los elementos */
            justify-content: center; /* Centra horizontalmente los elementos */
            margin-top: 20px;
            padding: 14px 28px;
            background-color: #fe2c55; /* Rojo vibrante de TikTok */
            color: white;
            text-decoration: none; /* Quita el subrayado del enlace */
            border-radius: 8px; /* Esquinas redondeadas para el botón */
            font-weight: bold;
            font-size: 1.2em; /* Tamaño de fuente más grande para el botón */
            transition: background-color 0.3s ease, transform 0.2s ease; /* Transiciones suaves */
            box-shadow: 0 4px 8px rgba(254, 44, 85, 0.3); /* Sombra para el botón */
        }

        .tiktok-link:hover {
            background-color: #d11e47; /* Rojo más oscuro al pasar el ratón */
            transform: translateY(-3px); /* Efecto de "levantar" al pasar el ratón */
            box-shadow: 0 6px 12px rgba(254, 44, 85, 0.4); /* Sombra más pronunciada al pasar el ratón */
        }

        /* Estilos para el icono de TikTok dentro del botón */
        img.tiktok-logo {
            vertical-align: middle;
            margin-right: 10px; /* Espacio entre el icono y el texto */
            width: 30px; /* Tamaño del icono */
            height: 30px;
            filter: brightness(0) invert(1); /* Hace que el logo de TikTok sea blanco si es necesario */
        }

        /* Medias queries para responsividad en pantallas más pequeñas */
        @media (max-width: 600px) {
            .container {
                margin: 20px; /* Margen en pantallas pequeñas */
                padding: 25px;
            }
            h1 {
                font-size: 1.8em;
            }
            p {
                font-size: 1em;
            }
            .tiktok-link {
                font-size: 1.1em;
                padding: 12px 24px;
            }
            img.tiktok-logo {
                width: 26px;
                height: 26px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>¡Hola! Soy Atbelit 👋</h1>
        <p>¡Bienvenido a mi página personal! Aquí puedes encontrar el enlace directo a mi perfil de TikTok para que no te pierdas nada de mi contenido.</p>

        <a href="https://www.tiktok.com/@atbelit3?_t=ZS-8x33wBVTt6Q&_r=1" target="_blank" class="tiktok-link">
            <img src="https://www.tiktok.com/favicon.ico" alt="Logo de TikTok" class="tiktok-logo">
            ¡Sígueme en TikTok!
        </a>

        <p style="margin-top: 30px; font-size: 0.9em; color: #888;">¡Gracias por tu visita!</p>
    </div>
</body>
</html>
 
