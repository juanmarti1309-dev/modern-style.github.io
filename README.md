<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contacto | Gorras Colombia</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #f5f5f5;
            color: #222;
        }

        .contacto {
            max-width: 1100px;
            margin: 60px auto;
            padding: 20px;
        }

        .titulo {
            text-align: center;
            margin-bottom: 40px;
        }

        .titulo h1 {
            font-size: 42px;
            margin-bottom: 10px;
        }

        .titulo p {
            color: #666;
            font-size: 17px;
        }

        .contenedor {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
        }

        .info,
        .formulario {
            background: white;
            padding: 35px;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
        }

        .info h2,
        .formulario h2 {
            margin-bottom: 20px;
        }

        .info p {
            color: #666;
            line-height: 1.6;
            margin-bottom: 25px;
        }

        .dato {
            margin-bottom: 20px;
        }

        .dato strong {
            display: block;
            margin-bottom: 5px;
        }

        .dato a {
            color: #222;
            text-decoration: none;
        }

        .dato a:hover {
            color: #008f5a;
        }

        label {
            display: block;
            margin-bottom: 7px;
            font-weight: bold;
        }

        input,
        textarea {
            width: 100%;
            padding: 13px;
            margin-bottom: 18px;
            border: 1px solid #ddd;
            border-radius: 8px;
            outline: none;
            font-size: 15px;
        }

        input:focus,
        textarea:focus {
            border-color: #008f5a;
        }

        textarea {
            height: 130px;
            resize: vertical;
        }

        button {
            width: 100%;
            padding: 14px;
            border: none;
            border-radius: 8px;
            background: #111;
            color: white;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background: #008f5a;
        }

        .redes {
            display: flex;
            gap: 10px;
            margin-top: 10px;
        }

        .redes a {
            text-decoration: none;
            background: #111;
            color: white;
            padding: 10px 15px;
            border-radius: 7px;
            transition: 0.3s;
        }

        .redes a:hover {
            background: #008f5a;
        }

        @media (max-width: 768px) {
            .contenedor {
                grid-template-columns: 1fr;
            }

            .titulo h1 {
                font-size: 32px;
            }

            .contacto {
                margin: 30px auto;
            }
        }
    </style>
</head>

<body>

    <section class="contacto">

        <div class="titulo">
            <h1>Contáctanos</h1>
            <p>
                ¿Tienes preguntas sobre nuestras gorras?
                Estamos aquí para ayudarte.
            </p>
        </div>

        <div class="contenedor">

            <!-- Información de contacto -->
            <div class="info">

                <h2>Hablemos</h2>

                <p>
                    Somos una empresa colombiana especializada en gorras.
                    Escríbenos para conocer nuestros diseños, precios,
                    disponibilidad y opciones de compra.
                </p>

                <div class="dato">
                    <strong>📱 WhatsApp</strong>
                    <a href="https://wa.me/573001234567" target="_blank">
                        +57 300 123 4567
                    </a>
                </div>

                <div class="dato">
                    <strong>✉️ Correo electrónico</strong>
                    <a href="mailto:contacto@tugorras.com">
                        contacto@tugorras.com
                    </a>
                </div>

                <div class="dato">
                    <strong>🕐 Horario de atención</strong>
                    <span>Lunes a sábado · 8:00 AM - 6:00 PM</span>
                </div>

                <div class="dato">
                    <strong>🌐 Síguenos</strong>

                    <div class="redes">
                        <a href="#" target="_blank">Instagram</a>
                        <a href="#" target="_blank">Facebook</a>
                        <a href="#" target="_blank">TikTok</a>
                    </div>
                </div>

            </div>


            <!-- Formulario -->
            <div class="formulario">

                <h2>Envíanos un mensaje</h2>

                <form action="#" method="POST">

                    <label for="nombre">Nombre</label>
                    <input
                        type="text"
                        id="nombre"
                        name="nombre"
                        placeholder="Escribe tu nombre"
                        required
                    >

                    <label for="email">Correo electrónico</label>
                    <input
                        type="email"
                        id="email"
                        name="email"
                        placeholder="correo@ejemplo.com"
                        required
                    >

                    <label for="telefono">Teléfono</label>
                    <input
                        type="tel"
                        id="telefono"
                        name="telefono"
                        placeholder="+57 300 000 0000"
                    >

                    <label for="mensaje">Mensaje</label>
                    <textarea
                        id="mensaje"
                        name="mensaje"
                        placeholder="Cuéntanos qué tipo de gorra estás buscando..."
                        required
                    ></textarea>

                    <button type="submit">
                        Enviar mensaje
                    </button>

                </form>

            </div>

        </div>

    </section>

</body>
</html>
