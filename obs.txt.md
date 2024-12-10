https://alejandra-olazagasti-portfolio.netlify.app/

https://jsfdz.com/ 

https://github.com/emmabostian/developer-portfolios?tab=readme-ov-file


https://freefrontend.com/css-carousels/

 https://codepen.io/studiojvla/pen/qVbQqW

 https://www.free-css.com/assets/files/free-css-templates/preview/page200/habitat/pages/carousels.php


 https://codepen.io/ariona/pen/KMRoge

 https://codepen.io/fixcl/pen/KwpKvb

 https://codepen.io/rezaminaee/pen/qeqvaP

 https://jvcodes.com/infinite-autoplay-slider-html-css/

 https://webdesignerwall.com/wdw-snippet/infinite-autoplay-carousel

 https://www.codewithfaraz.com/content/446/create-infinite-carousel-using-html-and-css

 https://gist.github.com/lordbird12/7d061b0159c5112ed976a0353f29bb48


 https://www.w3schools.com/howto/howto_js_copy_clipboard.asp


 <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Modal con Temporizador</title>
    <style>
        .modal {
            display: none;
            position: fixed;
            z-index: 1;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0,0,0,0.5);
        }

        .modal-contenido {
            background-color: #fefefe;
            margin: 15% auto;
            padding: 20px;
            border: 1px solid #888;
            width: 80%;
            max-width: 500px;
            text-align: center;
            position: relative;
        }

        .close {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
            cursor: pointer;
        }

        .close:hover {
            color: black;
        }
    </style>
</head>
<body>
    <div id="miModal" class="modal">
        <div class="modal-contenido">
            <span class="close">&times;</span>
            <h2>¡Hola! Este es un modal temporal</h2>
            <p>Me mostraré y ocultaré automáticamente</p>
        </div>
    </div>

    <script>
        const modal = document.getElementById('miModal');
        const closeBtn = document.querySelector('.close');
        let modalTimer;
        let autoShowTimer;

        function mostrarModal() {
            modal.style.display = 'block';

            // Cerrar después de 5 segundos
            modalTimer = setTimeout(() => {
                ocultarModal();
            }, 5000);
        }

        function ocultarModal() {
            modal.style.display = 'none';
            clearTimeout(modalTimer);
        }

        // Cerrar al hacer clic fuera del modal
        window.addEventListener('click', (event) => {
            if (event.target === modal) {
                ocultarModal();
            }
        });

        // Cerrar con el botón de cerrar
        closeBtn.addEventListener('click', ocultarModal);

        // Mostrar modal cada 15 segundos
        function iniciarCicloModal() {
            autoShowTimer = setInterval(mostrarModal, 15000);
        }

        // Iniciar el ciclo de mostrar modal
        iniciarCicloModal();
    </script>
</body>
</html>








 1 animacion cambiar iconos habilidades coloridos los mas posibles (todos 30 ) buscar animacion prueba error
 2 logo nombre + dibujo (opcional) bing
 3  Incluir nombre, profesión y especialidad (falta prof especialidad)
    Bienvenidos soy favian Medina web developer + links(ok) falta grafico icono
    ej https://chaitanya31612.github.io/
 4 Acerca de Mí (About Me):
    Ofrezco soluciones completas y efectivas en desarrollo web full stack, con tecnologías como React.js, Vue.js, HTML5, CSS3, JavaScript y PHP. Tengo experiencia en diseño, desarrollo y administración de bases de datos relacionales, utilizando tanto software libre como propietario. Mis habilidades incluyen la creación de consultas SQL avanzadas para análisis y generación de informes, así como la implementación de estrategias de respaldo y recuperación de datos. Asimismo tengo experiencia y conocimiento en  el consumo de APIs REST.
Además, cuento con amplia experiencia en gestión de proyectos y colaboración técnica en entornos Linux, Windows y herramientas ofimáticas, integrando sistemas de control de versiones para garantizar procesos de desarrollo organizados. Mi enfoque está orientado a contribuir al crecimiento y éxito de empresas pequeñas y medianas, tanto del sector público como privado.

 5 Listar máximo 10 habilidades 3 tecnologicas, 3 herramientas y 3 bd 2 so No personales
 6 portafolio I apartado crud (EASIUI:prod->vue/angular/react/ user) II sist booking, cursoteka, echelon, III weater, rm, pokdex, brecelee => elegir 3 destacados CARUSEL TODOS
 7 Agregar botones flotantes que motiven al usuario a contactar en cualquier momento. (Contacto Hablemos sobre tu próximo proyecto ¿Listo para dar el siguiente paso? Ponte en contacto conmigo para discutir cómo puedo ayudarte a lograr tus metas. Estoy ansioso por conocer tus ideas y trabajar juntos para convertirlas en realidad)
Have any project in mind **Let's make it a reality! Tell me your idea and what platform you want it on and I'll take care of the rest. lets go...

 8 copiar email
 9 referencias o testimonios compañeros
10 aps 2012-2017 (OK) +english
11 form fuentes/font misma que la principal inherit (ok)

prioridad
10, 11, 4, 3, 2, 5, 6,  8, 9, 1, 7
 

