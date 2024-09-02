<!DOCTYPE html>
<html>
<head>
    <title>El Fútbol</title>
    <style>
        body {
            background-image: url('fondo9.jpg');
            background-size: cover;
            font-family: Tahoma, sans-serif;
        }
        h1, h2 {
            font-family: 'Kristen ITC', cursive;
        }
        .highlight {
            color: green;
        }
        .section-title {
            color: green;
            font-size: 24px;
            font-weight: bold;
        }
        .content {
            color: purple;
            font-size: 18px;
        }
        .player-img {
            width: 150px;
            height: 150px;
        }
        marquee {
            font-size: 24px;
            color: green;
        }
    </style>
    <script type="text/javascript">
        function greetUser() {
            var nombre = prompt("Ingrese su nombre", "");
            if (nombre) {
                document.getElementById('greeting').innerText = "Hola " + nombre;
            }
        }
    </script>
</head>
<body onload="greetUser()">
    <center>
        <marquee behavior="scroll"><h1>La Historia del Fútbol</h1></marquee>
        
        <div class="content">
            <p>La historia del fútbol se considera a partir de 1869, año de fundación de la Asociación Inglesa de Fútbol, aunque en sus orígenes, 
            al igual que los demás códigos de fútbol, se remontan varios siglos en el pasado, particularmente en las islas británicas durante la Edad Media. 
            Si bien existían puntos en común entre diferentes juegos de pelota que se desarrollaron desde los años del siglo III a. C., los primeros códigos británicos 
            que dieron origen al balompié se caracterizaban por su poca organización y violencia extrema. No obstante, también existían otros códigos menos violentos 
            y mejor organizados. Quizás uno de los más conocidos fue el calcio florentino, deporte de equipo muy popular en Italia que tuvo incidencia en los códigos 
            de algunas escuelas británicas. La formación definitiva del fútbol tuvo su momento culminante durante el siglo XIX.</p>
        </div>
        
        <div class="section-title">Características del fútbol</div>
        <div class="content">
            <ul>
                <li><strong>Número de Jugadores:</strong> Cada equipo tiene once jugadores en el campo, incluyendo al portero.</li>
                <li><strong>Duración del Partido:</strong> Un partido de fútbol se juega en dos tiempos de 45 minutos cada uno, con un intervalo de 15 minutos entre ambos tiempos.</li>
                <li><strong>Objetivo del Juego:</strong> El objetivo principal es marcar más goles que el equipo contrario. Un gol se consigue cuando el balón cruza completamente la línea de la portería.</li>
            </ul>
        </div>
        
        <div class="section-title">Reglas Básicas</div>
        <div class="content">
            <ul>
                <li>No se permite el uso de las manos o los brazos por parte de los jugadores, excepto por el portero dentro de su área.</li>
                <li>El fuera de juego (offside) se penaliza si un jugador está más cerca de la línea de meta contraria que el balón y el penúltimo adversario en el momento en que se le pasa el balón.</li>
                <li>Las faltas y conductas antideportivas pueden resultar en tiros libres, penales o tarjetas amarillas y rojas.</li>
            </ul>
        </div>

        <div class="section-title">Jugadores Históricos</div>
        <div class="content">
            <div>
                <strong>Pelé:</strong> Considerado uno de los mejores futbolistas de todos los tiempos, el brasileño Pelé ganó tres Copas del Mundo (1958, 1962, 1970) y es conocido por su habilidad, técnica y capacidad de marcar goles.
                <br>
                <img src="pele.jpeg" alt="Pelé" class="player-img">
            </div>
            <div>
                <strong>Diego Maradona:</strong> La leyenda argentina es famosa por su habilidad técnica y su famoso "Gol del Siglo" en el Mundial de 1986. Maradona llevó a Argentina a ganar ese torneo y es recordado por su magia con el balón.
                <br>
                <img src="maradona.jpg" alt="Diego Maradona" class="player-img">
            </div>
            <div>
                <strong>Johan Cruyff:</strong> Cruyff fue un innovador del juego y un embajador del "fútbol total". El neerlandés tuvo una carrera influyente tanto como jugador como entrenador, y su legado sigue vivo en el estilo de juego del FC Barcelona.
                <br>
                <img src="cruy.jpg" alt="Johan Cruyff" class="player-img">
            </div>
            <div>
                <strong>Zinedine Zidane:</strong> El francés fue un maestro del centro del campo y destacó en el Mundial de 1998, donde marcó dos goles en la final. Su elegancia y visión de juego le hicieron famoso en clubes como la Juventus y el Real Madrid.
                <br>
                <img src="zidan.jpg" alt="Zinedine Zidane" class="player-img">
            </div>
            <div>
                <strong>Cristiano Ronaldo:</strong> Conocido por su increíble capacidad física y habilidades ofensivas, Cristiano Ronaldo ha ganado múltiples Balones de Oro y ha establecido récords en la Liga de Campeones y en competiciones nacionales.
                <br>
                <img src="ronaldo.jpg" alt="Cristiano Ronaldo" class="player-img">
            </div>
        </div>

        <div class="section-title">Torneos Internacionales de Clubes</div>
        <div class="content">
            <div>
                <strong>Liga de Campeones de la UEFA:</strong> Es el torneo de clubes más prestigioso en Europa, organizado por la UEFA. Los mejores equipos de las ligas europeas compiten para ganar el título. <br>
                Próximo Evento: En curso, con la final prevista para mayo de 2025.
            </div>
            <div>
                <strong>Europa League:</strong> Es la segunda competición de clubes más importante en Europa, organizada por la UEFA. Los equipos que no califican para la Liga de Campeones pueden participar en esta competición. <br>
                Próximo Evento: En curso, con la final prevista para mayo de 2025.
            </div>
            <div>
                <strong>Liga de Conferencias de la UEFA:</strong> Es la tercera competición de clubes más importante en Europa, organizada por la UEFA. Se estableció para proporcionar oportunidades a clubes que no clasifican para las competiciones principales. <br>
                Próximo Evento: En curso, con la final prevista para mayo de 2025.
            </div>
            <div>
                <strong>Copa Libertadores:</strong> Es el torneo de clubes más prestigioso en América del Sur, organizado por la CONMEBOL. Los equipos compiten para ganar el título sudamericano. <br>
                Próximo Evento: En curso, con la final prevista para noviembre de 2024.
            </div>
            <div>
                <strong>Copa Sudamericana:</strong> Es el segundo torneo de clubes más importante en América del Sur, también organizado por la CONMEBOL. Se celebra cada año. <br>
                Próximo Evento: En curso, con la final prevista para noviembre de 2024.
            </div>
            <div>
                <strong>Mundial de Clubes de la FIFA:</strong> Es un torneo internacional de clubes en el que participan los campeones de cada una de las confederaciones continentales, así como el campeón de la liga anfitriona. <br>
                Próximo Evento: En curso, con el torneo de 2024 programado para diciembre en Arabia Saudita.
            </div>
        </div>
    </center>
</body>
</html>

