# alejandrosystem.github.io
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú Interactivo de Departamentos</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #f4f7f6;
            color: #333;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        header {
            text-align: center;
            margin-bottom: 30px;
        }
        header h1 {
            color: #2c3e50;
            font-size: 24px;
            margin-bottom: 10px;
        }
        header p {
            color: #7f8c8d;
            font-size: 14px;
        }
        .container {
            width: 100%;
            max-width: 600px;
            background: #fff;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            padding: 15px;
        }
        .menu-list {
            list-style: none;
        }
        .menu-item {
            border-bottom: 1px solid #edf2f7;
            padding: 15px 10px;
            display: flex;
            flex-direction: column;
            gap: 12px;
        }
        .menu-item:last-child {
            border-bottom: none;
        }
        .dept-title {
            font-size: 16px;
            font-weight: 600;
            color: #2d3748;
        }
        .btn-group {
            display: flex;
            gap: 10px;
            width: 100%;
        }
        .btn {
            flex: 1;
            padding: 10px;
            border: none;
            border-radius: 8px;
            font-size: 14px;
            font-weight: 600;
            text-align: center;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            cursor: pointer;
            transition: background 0.2s, transform 0.1s;
        }
        .btn:active {
            transform: scale(0.98);
        }
        .btn-call {
            background-color: #3182ce;
            color: white;
        }
        .btn-call:hover {
            background-color: #2b6cb0;
        }
        .btn-wa {
            background-color: #38a169;
            color: white;
        }
        .btn-wa:hover {
            background-color: #2f855a;
        }
        .footer {
            margin-top: 30px;
            text-align: center;
            font-size: 12px;
            color: #a0aec0;
        }
        @media (min-width: 480px) {
            .menu-item {
                flex-direction: row;
                align-items: center;
                justify-content: space-between;
            }
            .btn-group {
                width: auto;
                min-width: 240px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Menú de Contacto</h1>
        <p>Seleccione un departamento para comunicarse</p>
    </header>

    <div class="container">
        <ul class="menu-list">
            <!-- REPETIR ESTE BLOQUE CAMBIANDO EL NÚMERO Y LOS TELÉFONOS -->
            <!-- NOTA: Reemplazar +5491112345678 con el número real (con código de país sin el signo + para WhatsApp) -->
            
            <!-- Departamento 1 -->
            <li class="menu-item">
                <span class="dept-title">Departamento 1</span>
                <div class="btn-group">
                    <a href="tel:+5491112345678" class="btn btn-call">📞 Llamar</a>
                    <a href="https://wa.me/5491112345678" target="_blank" class="btn btn-wa">💬 WhatsApp</a>
                </div>
            </li>

            <!-- Departamento 2 -->
            <li class="menu-item">
                <span class="dept-title">Departamento 2</span>
                <div class="btn-group">
                    <a href="tel:+5491133346212" class="btn btn-call">📞 Llamar</a>
                    <a href="https://wa.me/5491133346212" target="_blank" class="btn btn-wa">💬 WhatsApp</a>
                </div>
            </li>

            <!-- Departamento 3 -->
            <li class="menu-item">
                <span class="dept-title">Departamento 3</span>
                <div class="btn-group">
                    <a href="tel:+5491133346212" class="btn btn-call">📞 Llamar</a>
                    <a href="https://wa.me/5491133346212" target="_blank" class="btn btn-wa">💬 WhatsApp</a>
                </div>
            </li>

            <!-- Departamento 4 -->
            <li class="menu-item">
                <span class="dept-title">Departamento 4</span>
                <div class="btn-group">
                    <a href="tel:+5491112345678" class="btn btn-call">📞 Llamar</a>
                    <a href="https://wa.me/5491112345678" target="_blank" class="btn btn-wa">💬 WhatsApp</a>
                </div>
            </li>

            <!-- Departamento 5 -->
            <li class="menu-item">
                <span class="dept-title">Departamento 5</span>
                <div class="btn-group">
                    <a href="tel:+5491112345678" class="btn btn-call">📞 Llamar</a>
                    <a href="https://wa.me/5491112345678" target="_blank" class="btn btn-wa">💬 WhatsApp</a>
                </div>
            </li>

            <!-- Departamento 6 -->
            <li class="menu-item">
                <span class="dept-title">Departamento 6</span>
                <div class="btn-group">
                    <a href="tel:+5491112345678" class="btn btn-call">📞 Llamar</a>
                    <a href="https://wa.me/5491112345678" target="_blank" class="btn btn-wa">💬 WhatsApp</a>
                </div>
            </li>

            <!-- Departamento 7 -->
            <li class="menu-item">
                <span class="dept-title">Departamento 7</span>
                <div class="btn-group">
                    <a href="tel:+5491112345678" class="btn btn-call">📞 Llamar</a>
                    <a href="https://wa.me/5491112345678" target="_blank" class="btn btn-wa">💬 WhatsApp</a>
                </div>
            </li>

            <!-- Departamento 8 -->
            <li class="menu-item">
                <span class="dept-title">Departamento 8</span>
                <div class="btn-group">
                    <a href="tel:+5491112345678" class="btn btn-call">📞 Llamar</a>
                    <a href="https://wa.me/5491112345678" target="_blank" class="btn btn-wa">💬 WhatsApp</a>
                </div>
            </li>

            <!-- Departamento 9 -->
            <li class="menu-item">
                <span class="dept-title">Departamento 9</span>
                <div class="btn-group">
                    <a href="tel:+5491112345678" class="btn btn-call">📞 Llamar</a>
                    <a href="https://wa.me/5491112345678" target="_blank" class="btn btn-wa">💬 WhatsApp</a>
                </div>
            </li>

            <!-- Departamento 10 -->
            <li class="menu-item">
                <span class="dept-title">Departamento 10</span>
                <div class="btn-group">
                    <a href="tel:+5491112345678" class="btn btn-call">📞 Llamar</a>
                    <a href="https://wa.me/5491112345678" target="_blank" class="btn btn-wa">💬 WhatsApp</a>
                </div>
            </li>

            <!-- Departamento 11 -->
            <li class="menu-item">
                <span class="dept-title">Departamento 11</span>
                <div class="btn-group">
                    <a href="tel:+5491112345678" class="btn btn-call">📞 Llamar</a>
                    <a href="https://wa.me/5491112345678" target="_blank" class="btn btn-wa">💬 WhatsApp</a>
                </div>
            </li>

            <!-- Departamento 12 -->
            <li class="menu-item">
                <span class="dept-title">Departamento 12</span>
                <div class="btn-group">
                    <a href="tel:+5491112345678" class="btn btn-call">📞 Llamar</a>
                    <a href="https://wa.me/5491112345678" target="_blank" class="btn btn-wa">💬 WhatsApp</a>
                </div>
            </li>
        </ul>
    </div>

    <div class="footer">
        <p>&copy; 2026 Menú de Contacto Comercial</p>
    </div>

</body>
</html>
