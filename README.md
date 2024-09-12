<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Programa de Diamantes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #4CAF50; /* Fondo verde */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .container {
            background-color: #ffffff;
            border: 2px solid #007BFF; /* Borde azul */
            border-radius: 10px;
            padding: 0;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 300px;
            position: relative;
        }

        .header {
            background-color: #808080; /* Color gris */
            padding: 10px;
            text-align: center;
            border-top-left-radius: 10px;
            border-top-right-radius: 10px;
        }

        h1 {
            margin: 0;
            font-size: 24px;
            color: #FFFFFF; /* Texto blanco */
            display: inline-block; /* Permite que la imagen esté al lado */
        }

        .diamond-image {
            width: 40px; /* Tamaño de la imagen ajustado */
            height: auto;
            vertical-align: middle; /* Alineación vertical con el texto */
            margin-left: 5px; /* Espacio entre el texto y la imagen */
        }

        .diamond-row {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin: 10px 0;
            padding: 10px;
            border: 2px solid #FF0000; /* Borde rojo */
            border-radius: 5px;
        }

        .diamond-image-large {
            width: 30px; /* Ajusta el tamaño de la imagen según sea necesario */
            height: auto;
            margin-right: 10px; /* Espacio entre la imagen y el número */
        }

        .diamond {
            font-size: 20px;
            font-weight: bold; /* Negrita para el número */
        }

        .toggle {
            display: flex;
            align-items: center;
        }

        .toggle input {
            margin-left: 10px;
        }

        /* Estilo para el botón toggle */
        .toggle input[type="checkbox"] {
            appearance: none;
            width: 50px;
            height: 25px;
            background: #ccc;
            border-radius: 15px;
            position: relative;
            outline: none;
            cursor: pointer;
        }

        .toggle input[type="checkbox"]:checked {
            background: #4CAF50;
        }

        .toggle input[type="checkbox"]:checked::before {
            left: 25px;
        }

        .toggle input[type="checkbox"]::before {
            content: "";
            position: absolute;
            width: 20px;
            height: 20px;
            background: white;
            border-radius: 50%;
            transition: 0.3s;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="header">
            <h1>ROPARDIFIRE</h1>
            <img src="https://i.pinimg.com/736x/2c/ab/df/2cabdf3c2e5108fdedd935262d759386.jpg" alt="Imagen" class="diamond-image">
        </div>
        <div class="diamond-row">
            <img src="https://i.pinimg.com/736x/05/28/7d/05287da0c5dac32078f996c1a07fadda.jpg" alt="Diamante" class="diamond-image-large">
            <span class="diamond">10,000</span>
            <div class="toggle">
                <input type="checkbox" id="toggle1">
                <label for="toggle1">OFF</label>
            </div>
        </div>
        <div class="diamond-row">
            <img src="https://i.pinimg.com/736x/05/28/7d/05287da0c5dac32078f996c1a07fadda.jpg" alt="Diamante" class="diamond-image-large">
            <span class="diamond">50,000</span>
            <div class="toggle">
                <input type="checkbox" id="toggle2">
                <label for="toggle2">OFF</label>
            </div>
        </div>
        <div class="diamond-row">
            <img src="https://i.pinimg.com/736x/05/28/7d/05287da0c5dac32078f996c1a07fadda.jpg" alt="Diamante" class="diamond-image-large">
            <span class="diamond">100,000</span>
            <div class="toggle">
                <input type="checkbox" id="toggle3">
                <label for="toggle3">OFF</label>
            </div>
        </div>
        <div class="diamond-row">
            <img src="https://i.pinimg.com/736x/05/28/7d/05287da0c5dac32078f996c1a07fadda.jpg" alt="Diamante" class="diamond-image-large">
            <span class="diamond">250,000</span>
            <div class="toggle">
                <input type="checkbox" id="toggle4">
                <label for="toggle4">OFF</label>
            </div>
        </div>
        <div class="diamond-row">
            <img src="https://i.pinimg.com/736x/05/28/7d/05287da0c5dac32078f996c1a07fadda.jpg" alt="Diamante" class="diamond-image-large">
            <span class="diamond">500,000</span>
            <div class="toggle">
                <input type="checkbox" id="toggle5">
                <label for="toggle5">OFF</label>
            </div>
        </div>
    </div>

    <script>
        // Tu script aquí
    </script>
</body>
</html>
