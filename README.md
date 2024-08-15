<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-image: url('https://example.com/futbol-background.jpg'); /* Cambia esto por una imagen de fondo relacionada con el fútbol */
            background-size: cover;
            color: #fff;
            text-align: center;
            padding: 50px;
            margin: 0;
        }
        h1 {
            color: #FFD700;
            font-size: 48px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .premio {
            background-color: rgba(0, 0, 0, 0.7);
            border: 2px solid #FFD700;
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s;
        }
        .premio:hover {
            transform: scale(1.05);
        }
        .cantidad {
            font-size: 32px;
            font-weight: bold;
            color: #FF4500;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
        }
        .icono {
            font-size: 50px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <h1>Predio Legue Cup</h1>
    <div class="premio">
        <div class="icono">🏆</div>
        <h2>1er Puesto</h2>
        <p class="cantidad">$19.000.000</p>
    </div>
    <div class="premio">
        <div class="icono">🥈</div>
        <h2>2do Puesto</h2>
        <p class="cantidad">$16.000.000</p>
    </div>
    <div class="premio">
        <div class="icono">🥉</div>
        <h2>3er Puesto</h2>
        <p class="cantidad">$10.000.000</p>
    </div>
    <div class="premio">
        <div class="icono">⚽</div>
        <h2>Máximo Goleador</h2>
        <p class="cantidad">$7.000.000</p>
    </div>
    <div class="premio">
        <div class="icono">🛡️</div>
        <h2>Valla Menos Vencida</h2>
        <p class="cantidad">$5.000.000</p>
    </div>
    <div class="premio">
        <div class="icono">🅰️</div>
        <h2>Máximo Asistidor</h2>
        <p class="cantidad">$5.000.000</p>
    </div>
</body>
</html>
