<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
    <style>
        body {
            font-family: sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #f0f0f0;
        }

        .container {
            background-color: #fff;
            padding: 30px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        h2 {
            margin-bottom: 20px;
            color: #000000;
        }

        input[type="text"],
        input[type="email"],
        input[type="tel"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #000000;
            border-radius: 3px;
            box-sizing: border-box;
        }

        button {
            background-color: #8b41b6;
            color: white;
            padding: 12px 20px;
            margin: 10px 0;
            border: none;
            border-radius: 3px;
            cursor: pointer;
            font-size: 16px;
            width: 100%;
        }

        button:hover {
            background-color: #8b41b6;
        }

        .footer {
            margin-top: 20px;
            font-size: 14px;
            color: #000000;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Formulario</h2>
        <input type="text" id="nombre" placeholder="Nombre">
        <input type="email" id="email" placeholder="Email">
        <input type="tel" id="telefono" placeholder="Telefono">
        <button type="submit">Enviar</button>
        <button type="reset">Reiniciar</button>
        <div class="footer">
            by: Karen Restrepo Valencis
        </div>
    </div>
</body>
</html>
