# Mi-hoja-de-vida
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hoja de Vida - Yeraldin Largo Diaz</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Segoe UI", Arial, sans-serif;
        }

        body {
            background: #f8e9f1;
            color: #3d2631;
            line-height: 1.6;
        }

        .cv {
            max-width: 1000px;
            margin: 40px auto;
            background: white;
            display: grid;
            grid-template-columns: 32% 68%;
            box-shadow: 0 10px 30px rgba(130, 60, 90, 0.18);
            border-radius: 18px;
            overflow: hidden;
        }

        /* PANEL IZQUIERDO */
        .sidebar {
            background: linear-gradient(180deg, #d94f91, #b83270);
            color: white;
            padding: 40px 30px;
        }

        .foto {
            width: 125px;
            height: 125px;
            border-radius: 50%;
            background: #f8c6dc;
            margin: 0 auto 25px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #a52d65;
            font-size: 45px;
            font-weight: bold;
            border: 5px solid rgba(255,255,255,0.7);
        }

        .sidebar h1 {
            text-align: center;
            font-size: 28px;
            letter-spacing: 1px;
            margin-bottom: 8px;
        }

        .cargo {
            text-align: center;
            font-size: 15px;
            opacity: 0.95;
            margin-bottom: 35px;
        }

        .sidebar h2 {
            font-size: 17px;
            border-bottom: 1px solid rgba(255,255,255,0.5);
            padding-bottom: 8px;
            margin: 25px 0 15px;
        }

        .contacto p {
            font-size: 14px;
            margin: 10px 0;
        }

        .habilidades {
            list-style: none;
        }

        .habilidades li {
            margin: 10px 0;
            font-size: 14px;
        }

        .habilidades li::before {
            content: "●";
            margin-right: 9px;
            color: #ffd6e7;
        }

        /* CONTENIDO */
        .contenido {
            padding: 45px;
        }

        .seccion {
            margin-bottom: 32px;
        }

        .seccion h2 {
            color: #c13978;
            font-size: 22px;
            border-bottom: 2px solid #efb2cd;
            padding-bottom: 7px;
            margin-bottom: 18px;
        }

        .perfil {
            font-size: 15px;
            color: #5b414c;
        }

        .item {
            margin-bottom: 20px;
            padding-left: 18px;
            border-left: 3px solid #d94f91;
        }

        .item h3 {
            color: #9f2c62;
            font-size: 17px;
            margin-bottom: 3px;
        }

        .item .fecha {
            color: #c65b88;
            font-size: 13px;
            font-weight: bold;
        }

        .item p {
            font-size: 14px;
            color: #5b414c;
        }

        .etiquetas {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .etiqueta {
            background: #f9d9e7;
            color: #9f2c62;
            padding: 8px 14px;
            border-radius: 20px;
            font-size: 13px;
            font-weight: 600;
        }

        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 12px;
            color: #98717f;
        }

        /* RESPONSIVE */
        @media (max-width: 750px) {
            .cv {
                grid-template-columns: 1fr;
                margin: 15px;
            }

            .sidebar {
                padding: 30px 25px;
            }

            .contenido {
                padding: 30px 25px;
            }
        }
    </style>
</head>

<body>

    <div class="cv">

        <!-- PANEL LATERAL -->
        <aside class="sidebar">

            <div class="foto">YL</div>

            <h1>YERALDIN<br>LARGO DIAZ</h1>

            <p class="cargo">
                Candidata a Personería<br>
                <strong>2026</strong>
            </p>

            <h2>CONTACTO</h2>

            <div class="contacto">
                <p>✉️ yeraldinlargo@gmail.com</p>
                <p>📍 Vrd. El Carmelo<br>Guática, Risaralda</p>
            </div>

            <h2>HABILIDADES</h2>

            <ul class="habilidades">
                <li>Empatía y escucha activa</li>
                <li>Trabajo en equipo</li>
                <li>Comunicación asertiva</li>
                <li>Responsabilidad</li>
                <li>Compromiso</li>
                <li>Iniciativa</li>
            </ul>

        </aside>


        <!-- CONTENIDO PRINCIPAL -->
        <main class="contenido">

            <section class="seccion">
                <h2>Perfil</h2>

                <p class="perfil">
                    Estudiante comprometida, responsable y con iniciativa,
                    interesada en fortalecer el liderazgo estudiantil y
                    contribuir positivamente a la comunidad educativa.
                    Me caracterizo por la empatía, la comunicación asertiva,
                    el trabajo en equipo y el compromiso con cada
                    responsabilidad que asumo.
                </p>
            </section>


            <section class="seccion">
                <h2>Educación</h2>

                <div class="item">
                    <h3>Escuela El Carmelo</h3>
                    <p class="fecha">Básica primaria</p>
                    <p>
                        Preescolar a quinto de primaria. Graduada con
                        honores académicos.
                    </p>
                </div>

                <div class="item">
                    <h3>IE Instituto Guática</h3>
                    <p class="fecha">Básica secundaria y media</p>
                </div>
            </section>


            <section class="seccion">
                <h2>Cursos y formación</h2>

                <div class="etiquetas">
                    <span class="etiqueta">Técnico Ambiental en curso</span>
                    <span class="etiqueta">Mujeres TIC</span>
                    <span class="etiqueta">Primeros Auxilios</span>
                </div>
            </section>


            <section class="seccion">
                <h2>Experiencia y participación</h2>

                <div class="item">
                    <h3>Representante estudiantil en primaria</h3>
                    <p>
                        Fui representante de los estudiantes durante toda
                        mi primaria, fortaleciendo mi liderazgo,
                        responsabilidad y capacidad de comunicación.
                    </p>
                </div>

                <div class="item">
                    <h3>Programa Ondas</h3>
                    <p>
                        Participación en proyectos académicos,
                        fortaleciendo el pensamiento crítico, las
                        habilidades investigativas y el trabajo colaborativo.
                    </p>
                </div>

                <div class="item">
                    <h3>Danzas municipales</h3>
                    <p>
                        Experiencia que permitió fortalecer la disciplina,
                        el compromiso y la seguridad al presentarme
                        en público.
                    </p>
                </div>

                <div class="item">
                    <h3>Campamentos juveniles</h3>
                    <p>
                        Participación en actividades que fortalecieron
                        mis habilidades sociales y mi capacidad de
                        adaptación a diferentes entornos.
                    </p>
                </div>
            </section>


            <section class="seccion">
                <h2>Objetivo</h2>

                <p class="perfil">
                    Representar a los estudiantes con responsabilidad,
                    escuchar sus necesidades y promover iniciativas que
                    aporten al bienestar, la participación y el crecimiento
                    de la comunidad educativa.
                </p>
            </section>

            <footer>
                Hoja de Vida · Yeraldin Largo Diaz · Personería Estudiantil 2026
            </footer>

        </main>

    </div>

</body>
</html>
