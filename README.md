# Julio-Valdivia-Pagina-WEB
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Julio Valdivia - Página Web</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 30px;
        }

        /* Columna izquierda - Perfil */
        .left-column {
            background: linear-gradient(135deg, #2c3e50, #3498db);
            color: white;
            padding: 40px 30px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .profile {
            text-align: center;
            margin-bottom: 30px;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid white;
            margin: 0 auto 20px;
            background-color: #ecf0f1;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 48px;
        }

        .profile h1 {
            font-size: 28px;
            margin-bottom: 10px;
        }

        .profile p {
            font-size: 18px;
            opacity: 0.9;
        }

        .contact-info {
            margin-top: 30px;
        }

        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
            padding: 10px;
            background: rgba(255,255,255,0.1);
            border-radius: 8px;
        }

        .contact-item i {
            margin-right: 10px;
            font-size: 18px;
        }

        /* Columna derecha - Contenido */
        .right-column {
            background: white;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        .section {
            margin-bottom: 40px;
        }

        .section-title {
            font-size: 24px;
            color: #2c3e50;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 3px solid #3498db;
        }

        .skill {
            margin-bottom: 15px;
        }

        .skill-tag {
            display: inline-block;
            background: #3498db;
            color: white;
            padding: 8px 15px;
            margin: 5px;
            border-radius: 20px;
            font-size: 14px;
            transition: transform 0.3s ease;
        }

        .skill-tag:hover {
            transform: translateY(-2px);
            background: #2980b9;
        }

        .info-item {
            margin-bottom: 20px;
            padding: 15px;
            background: #f8f9fa;
            border-radius: 8px;
            border-left: 4px solid #3498db;
        }

        .info-label {
            font-weight: bold;
            color: #2c3e50;
            font-size: 18px;
        }

        .info-content {
            color: #7f8c8d;
            margin: 5px 0;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .container {
                grid-template-columns: 1fr;
                gap: 20px;
            }
            
            .left-column, .right-column {
                padding: 25px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Columna Izquierda - Perfil -->
        <div class="left-column">
            <div class="profile">
                <div class="profile-img">
                    👨‍💼
                </div>
                <h1>JULIO VALDIVIA</h1>
                <p>Administrador de Empresas</p>
            </div>

            <div class="section">
                <h3 class="section-title">Contacto</h3>
                <div class="contact-info">
                    <div class="contact-item">
                        <i>📧</i>
                        <span>julio@email.com</span>
                    </div>
                    <div class="contact-item">
                        <i>📱</i>
                        <span>+51 999 999 999</span>
                    </div>
                    <div class="contact-item">
                        <i>📍</i>
                        <span>Arequipa, Perú</span>
                    </div>
                    <div class="contact-item">
                        <i>🔗</i>
                        <span>linkedin.com/in/juliovaldivia</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- Columna Derecha - Contenido -->
        <div class="right-column">
            <!-- Sección Habilidades -->
            <div class="section">
                <h3 class="section-title">Habilidades</h3>
                <div class="skill">
                    <span class="skill-tag">Ventas y Negociación</span>
                    <span class="skill-tag">Análisis de Datos</span>
                    <span class="skill-tag">Gestión Comercial</span>
                    <span class="skill-tag">Atención al Cliente</span>
                    <span class="skill-tag">Trabajo en Equipo</span>
                    <span class="skill-tag">Planificación Estratégica</span>
                    <span class="skill-tag">Microsoft Office</span>
                    <span class="skill-tag">CRM</span>
                </div>
            </div>

            <!-- Sección Educación -->
            <div class="section">
                <h3 class="section-title">Educación</h3>
                <div class="info-item">
                    <div class="info-label">Universidad Católica San Pablo</div>
                    <div class="info-content">2020 - Presente</div>
                    <p>Pregrado en Administración</p>
                </div>
                <div class="info-item">
                    <div class="info-label">Instituto Superior Tecnológico</div>
                    <div class="info-content">2017 - 2019</div>
                    <p>Técnico en Administración de Empresas</p>
                </div>
            </div>

            <!-- Sección Experiencia (agregué esta sección como ejemplo) -->
            <div class="section">
                <h3 class="section-title">Experiencia Profesional</h3>
                <div class="info-item">
                    <div class="info-label">Empresa ABC</div>
                    <div class="info-content">2022 - Presente</div>
                    <p>Asistente de Gerencia Comercial</p>
                </div>
                <div class="info-item">
                    <div class="info-label">Compañía XYZ</div>
                    <div class="info-content">2020 - 2022</div>
                    <p>Ejecutivo de Ventas</p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
