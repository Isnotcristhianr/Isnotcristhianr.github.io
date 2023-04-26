<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--========== UNICONS ==========-->
    <link rel="stylesheet" href="https://unicons.iconscout.com/release/v4.0.8/css/line.css">
    <!--========== BOXICONS ==========-->
    <link href='https://unpkg.com/boxicons@2.1.1/css/boxicons.min.css' rel='stylesheet'>
    <!--========== SWIPER CSS ==========-->
    <link rel="stylesheet" href="assets/css/swiper-bundle.min.css">
    <!--========== MAIN CSS ==========-->
    <link rel="stylesheet" href="assets/css/styles.css">
    <!--META-->
    <meta name="description"
        content="CodeByme es una plataforma de cursos online para aprender a programar desde cero.">
    <title>ItsnotCristhian Portafolio</title>
    <link rel="shortcut icon" href="assets/imgs/log isncr.png" type="image/x-icon">
    <!--===========Animacion Scroll================-->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

</head>

<body>
    <!--========== SIDEBAR ==========-->
    <div class="nav__toggle" id="nav-toggle">
        <i class="uil uil-bars"></i>
    </div>
    <aside class="sidebar" id="sidebar">
        <nav class="nav">
            <div class="nav__logo">
                <a href="index.html" class="nav__logo-text">C
                </a>
            </div>

            <div class="nav__menu">
                <div class="menu">
                    <ul class="nav__list">
                        <li class="nav__item">
                            <a href="#home" class="nav__link active-link">Home</a>
                        </li>
                        <li class="nav__item">
                            <a href="#about" class="nav__link">Sobre mi</a>
                        </li>
                        <li class="nav__item">
                            <a href="#services" class="nav__link">Servicios</a>
                        </li>
                        <li class="nav__item">
                            <a href="#work" class="nav__link">Proyectos</a>
                        </li>
                        <li class="nav__item">
                            <a href="#skills" class="nav__link">Habilidades</a>
                        </li>
                        <li class="nav__item">
                            <a href="#contact" class="nav__link">Contáctame</a>
                        </li>
                    </ul>
                </div>
            </div>

            <div class="btn__share">
                <a href="#" onclick="copied()" class="uil uil-share-alt social__share"></a>
            </div>

            <div class="nav__close" id="nav-close">
                <i class="uil uil-times"></i>
            </div>
        </nav>
    </aside>

    <!--========== MAIN ==========-->
    <main class="main">
        <!--===== Home =====-->
        <section class="home" id="home">
            <div class="home__container container grid">
                <div class="home__social">
                    <span class="home__social-follow">Sígueme</span>
                    <div class="home__social-links">
                        <a href="https://www.facebook.com/IsnotCristhianr/" target="_blank" class="home__social-link">
                            <i class="uil uil-facebook-f"></i>
                        </a>
                        <a href="https://www.instagram.com/itsnotcristhianr/" target="_blank" class="home__social-link">
                            <i class="uil uil-instagram"></i>
                        </a>
                        <a href="https://twitter.com/Cristhi69039818" target="_blank" class="home__social-link">
                            <i class="uil uil-twitter"></i>
                        </a>
                        <!-- Youtube -->
                        <a href="https://www.youtube.com/channel/UCcG_of4TIXa1l7bNbegRgEQ" target="_blank"
                            class="home__social-link">
                            <i class="uil uil-youtube"></i>
                        </a>
                    </div>
                </div>

                <img src="assets/imgs/mebg.png" alt="" class="home__img">

                <div class="home__data">
                    <h1 class="home__title">Hola, Soy <span class="typed" style="color: #475364;">Cristhian</span></h1>
                    <h3 class="home__subtitle">Estudiante de Ingenieria en Tecnologias de la Informacion y Comunicacion
                    </h3>
                    <p class="home__description">
                        Dominio en conocimientos de TIC's capaz de utilizar metodos, tecnicas y herramientas de alto
                        invel
                        para el desarrollo de software, con capacidad de analisis y resolucion de problemas.
                    </p>
                    <a href="resourses/Profile (1).pdf" download="Profile (1).pdf" class="button"><i
                            class="uil uil-user button__icon"></i>
                        Mas sobre mi
                    </a>
                </div>

                <div class="my__info">
                    <div class="info__item">
                        <a href="https://www.instagram.com/itsnotcristhianr/" target="_blank">
                            <i class="uil uil-instagram info__icon"></i>
                        </a>
                        <div>
                            <h3 class="info__title">Instagram</h3>
                            <span class="info__subtitle">@isnotcristhianr</span>
                        </div>

                    </div>

                    <div class="info__item">
                        <a href="https://api.whatsapp.com/send?phone=+593996221950&text=Hola, Estoy interesado en trabajar contigo!"
                            target="_blank">
                            <i class="uil uil-whatsapp info__icon"></i>
                        </a>

                        <div>
                            <h3 class="info__title">Whatsapp</h3>
                            <span class="info__subtitle">+593 996221950</span>
                        </div>
                    </div>

                    <div class="info__item">
                        <a href="mailto:isnotcristhianr@gmail.com" target="_blank">
                            <i class="uil uil-envelope-edit info__icon"></i>
                        </a>

                        <div>
                            <h3 class="info__title">Email</h3>
                            <span class="info__subtitle">isnotcristhianr@gmail.com</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!--===== About =====-->
        <section class="about section" id="about">
            <h2 data-heading="Presentación" class="section__title">Sobre mi</h2>

            <div class="about__container container grid">
                <img src="assets/imgs/about-img.png" alt="" class="about__img">

                <div class="about__data">
                    <h3 class="about__heading">
                        Hola, soy Cristhian Recalde y vivo en Ibarra-Ecuador
                    </h3>
                    <p class="about__description">
                        Tengo una pasión por la programación, trato de encontrar la mejor solución y no me gusta
                        rendirme. Me gusta dar valor en donde me encuentre y a la vez puedan contar conmigo, por ello he
                        creado algunos proyectos interesantes que se pueden vislumbrar en este portafolio.
                        Del mismo modo me gusta trabajar en solitario o en grupo, siempre que haya pasión por el
                        trabajo o proyecto cuentan con mi voluntad a cumplirlo de la mejor manera.</p>
                    <div class="about__info grid">
                        <div class="about__box">
                            <i class="uil uil-award about__icon"></i>
                            <h3 class="about__title">Experiencia</h3>
                            <span class="about__subtitle">4 + Years</span>
                        </div>

                        <div class="about__box">
                            <i class="uil uil-suitcase-alt about__icon"></i>
                            <h3 class="about__title">Completados</h3>
                            <span class="about__subtitle">32 + Proyectos</span>
                        </div>

                        <div class="about__box">
                            <i class="uil uil-headphones-alt about__icon"></i>
                            <h3 class="about__title">Disponibilidad</h3>
                            <span class="about__subtitle">Online 24/7</span>
                        </div>
                    </div>
                    <a href="#contact" class="button"><i class="uil uil-navigator button__icon"></i>
                        Contactame
                    </a>
                </div>
            </div>
        </section>

        <!--===== Qualification =====-->
        <section class="qualification section">
            <h2 data-heading="Camino del Programador" class="section__title">Trayectoria</h2>

            <div class="qualification__container container grid">
                <div class="experience">
                    <h3 class="qualification__title">
                        <i class="uil uil-suitcase"></i> Experiencia
                    </h3>

                    <div class="timeline">

                        <div class="timeline__item">
                            <div class="circle__dot"></div>
                            <h3 class="timeline__title">Agroindustrias Equatorial</h3>
                            <p class="timeline__text">Community Manager</p>
                            <span class="timeline__date"><i class="uil uil-calendar-alt"></i>
                                2018 - 2021
                            </span>
                        </div>

                        <div class="timeline__item">
                            <div class="circle__dot"></div>
                            <h3 class="timeline__title">Hood Code (Online)</h3>
                            <p class="timeline__text">Junior Dev Javascript-Python</p>
                            <span class="timeline__date"><i class="uil uil-calendar-alt"></i>
                                2021 - 2022
                            </span>
                        </div>

                        <div class="timeline__item">
                            <div class="circle__dot"></div>
                            <h3 class="timeline__title">Google Developer Group (Online)</h3>
                            <p class="timeline__text">Google IO Assistant</p>
                            <span class="timeline__date"><i class="uil uil-calendar-alt"></i>
                                2021 - Presente
                            </span>
                        </div>

                        <div class="timeline__item">
                            <div class="circle__dot"></div>
                            <h3 class="timeline__title">Vreech (Online - Presencial)</h3>
                            <p class="timeline__text">Junior Programer / Community Manager</p>
                            <span class="timeline__date"><i class="uil uil-calendar-alt"></i>
                                2020 - 2021
                            </span>
                        </div>
                    </div>
                </div>

                <div class="education">
                    <h3 class="qualification__title">
                        <i class="uil uil-graduation-cap"></i> Formación
                    </h3>

                    <div class="timeline">
                        <div class="timeline__item">
                            <div class="circle__dot"></div>
                            <h3 class="timeline__title">Pontifia Universidad Catolica del Ecuador (Sede Ibarra)</h3>
                            <p class="timeline__text">Ingenieria en TIC's (Tecnologias de la Informacion y
                                Comunicacion)
                            </p>
                            <span class="timeline__date"><i class="uil uil-calendar-alt"></i>
                                2020 - 2024
                            </span>
                        </div>

                        <div class="timeline__item">
                            <div class="circle__dot"></div>
                            <h3 class="timeline__title">Google Courses</h3>
                            <p class="timeline__text">Html5, Css, Desarrollo de aplicaciones </p>
                            <span class="timeline__date"><i class="uil uil-calendar-alt"></i>
                                2017 - Presente
                            </span>
                        </div>

                        <div class="timeline__item">
                            <div class="circle__dot"></div>
                            <h3 class="timeline__title">FreeCodeCamp (Online)</h3>
                            <p class="timeline__text">Web Site / UX Designer</p>
                            <span class="timeline__date"><i class="uil uil-calendar-alt"></i>
                                2019 - Presente
                            </span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!--===== Skills =====-->
        <section class="services section" id="services">
            <h2 data-heading="Servicios" class="section__title">¿Qué Puedo Hacer?</h2>

            <div class="services__container container grid">
                <div class="services__content">
                    <div>
                        <i class="uil uil-web-grid services__icon"></i>
                        <h3 class="services__title">Diseño <br> Web</h3>
                    </div>

                    <span class="services__button">
                        Ver más <i class="uil uil-arrow-right services__button-icon"></i>
                    </span>

                    <div class="services__modal">
                        <div class="services__modal-content">
                            <i class="uil uil-times services__modal-close"></i>

                            <h3 class="services__modal-title">Desarrollo Web</h3>
                            <p class="services__modal-description">

                            </p>

                            <ul class="services__modal-services grid">
                                <li class="services__modal-service">
                                    <i class="uil uil-check-circle services__modal-icon"></i>
                                    <p class="services__modal-info">Desarrollo de Interfaces de Usuario</p>
                                </li>
                                <li class="services__modal-service">
                                    <i class="uil uil-check-circle services__modal-icon"></i>
                                    <p class="services__modal-info">Maquetado y estruturado en diseño Web</p>
                                </li>
                                <li class="services__modal-service">
                                    <i class="uil uil-check-circle services__modal-icon"></i>
                                    <p class="services__modal-info">Uso y creación de elementos interactivos </p>
                                </li>
                                <li class="services__modal-service">
                                    <i class="uil uil-check-circle services__modal-icon"></i>
                                    <p class="services__modal-info">Posicionamiento del sitio web en linea</p>
                                </li>
                                <li class="services__modal-service">
                                    <i class="uil uil-check-circle services__modal-icon"></i>
                                    <p class="services__modal-info">Diseño multiplataformas adaptable
                                    </p>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>

                <div class="services__content">
                    <div>
                        <i class="uil uil-arrow services__icon"></i>
                        <h3 class="services__title">Diseño <br> UI/UX</h3>
                    </div>

                    <span class="services__button">
                        Ver más <i class="uil uil-arrow-right services__button-icon"></i>
                    </span>

                    <div class="services__modal">
                        <div class="services__modal-content">
                            <i class="uil uil-times services__modal-close"></i>

                            <h3 class="services__modal-title">Diseño UI/UX</h3>
                            <p class="services__modal-description">

                            </p>

                            <ul class="services__modal-services grid">
                                <li class="services__modal-service">
                                    <i class="uil uil-check-circle services__modal-icon"></i>
                                    <p class="services__modal-info">Desarrollo de Interfaces de Usuario</p>
                                </li>
                                <li class="services__modal-service">
                                    <i class="uil uil-check-circle services__modal-icon"></i>
                                    <p class="services__modal-info">Maquetado del producto en Adobe XD o Figma</p>
                                </li>
                                <li class="services__modal-service">
                                    <i class="uil uil-check-circle services__modal-icon"></i>
                                    <p class="services__modal-info">Creacion de marca digital</p>
                                </li>
                                <li class="services__modal-service">
                                    <i class="uil uil-check-circle services__modal-icon"></i>
                                    <p class="services__modal-info">Maquetado del diseño web</p>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>

                <div class="services__content">
                    <div>
                        <i class="uil uil-edit services__icon"></i>
                        <h3 class="services__title">Community <br> Manager</h3>
                    </div>

                    <span class="services__button">
                        Ver más <i class="uil uil-arrow-right services__button-icon"></i>
                    </span>

                    <div class="services__modal">
                        <div class="services__modal-content">
                            <i class="uil uil-times services__modal-close"></i>

                            <h3 class="services__modal-title">Community Manager</h3>
                            <p class="services__modal-description">

                            </p>

                            <ul class="services__modal-services grid">
                                <li class="services__modal-service">
                                    <i class="uil uil-check-circle services__modal-icon"></i>
                                    <p class="services__modal-info">Planificación y creación de contenido</p>
                                </li>
                                <li class="services__modal-service">
                                    <i class="uil uil-check-circle services__modal-icon"></i>
                                    <p class="services__modal-info">Perfiles dinamicos en línea</p>
                                </li>
                                <li class="services__modal-service">
                                    <i class="uil uil-check-circle services__modal-icon"></i>
                                    <p class="services__modal-info">Manejo de arbol de links para redes sociales</p>
                                </li>
                                <li class="services__modal-service">
                                    <i class="uil uil-check-circle services__modal-icon"></i>
                                    <p class="services__modal-info">Desarrollo de herramientas digitales</p>
                                </li>
                                <li class="services__modal-service">
                                    <i class="uil uil-check-circle services__modal-icon"></i>
                                    <p class="services__modal-info">Automatización de planificacion de contenido</p>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!--===== Work =====-->
        <section class="work section" id="work">
            <h2 data-heading="Portafolio de Proyectos" class="section__title">Proyectos</h2>

            <div class="work__filters">
                <span class="work__item active-work" data-filter="all">Todos</span>
                <span class="work__item" data-filter=".web">Web</span>
                <span class="work__item" data-filter=".app">App</span>
                <span class="work__item" data-filter=".design">Diseño UI-IX</span>
            </div>

            <div class="work__container container grid">
                <div class="work__card mix web">
                    <img src="assets/imgs/proyectos/presentacion portafolio.png" alt="" class="work__img">
                    <h3 class="work__title">Portafolio Web</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Diseño de Portafolio-Personal</h3>
                        <p class="details__description">Inspirado en la simplicidad y minimalismo para mostrar mis
                            proyectos realizados</p>
                        <ul class="details__info">
                            <li>Creado: <span>10 Mayo 2022</span></li>
                            <li>Tecnologias: <span>Html - Css - Javascript</span></li>
                            <li>Rol: <span>Dev Frontend</span></li>
                            <li>Vista: <span><a href="index.html">demo</a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix app">
                    <img src="assets/imgs/proyectos/webCandidatos.png" alt="" class="work__img">
                    <h3 class="work__title">Candidatos Alcaldias-PrefecturasImbabura 2023</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Candidatos Alcaldias-PrefecturasImbabura 2023</h3>
                        <p class="details__description"> Sistema de ahorro contable para el control de ingresos y
                            egresos de una empresa
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>13 Febrero 2023</span></li>
                            <li>Tecnologias: <span>Html - Css - JavaScript - PHP</span></li>
                            <li>Rol: <span>Dev Frontend</span></li>
                            <li>Vista: <span><a href="resourses/webCandidatos.zip">demo </a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix app">
                    <img src="assets/imgs/proyectos/supermerk2.png" alt="" class="work__img">
                    <h3 class="work__title">App Control Almacen</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Aplicacion de Escritorio para un almacén</h3>
                        <p class="details__description">Diseñado para ser rapido y efectivo en torno al almacenaje y
                            distribucion de
                            produtos para su futura venta.
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>22 Octubre 2020</span></li>
                            <li>Tecnologias: <span>Java</span></li>
                            <li>Rol: <span>Dev Junior</span></li>
                            <li>Visita: <span><a href="resourses/SupermercadoDemo.rar">demo</a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix web">
                    <img src="assets/imgs/proyectos/presentacion vinos.png" alt="" class="work__img">
                    <h3 class="work__title">Vinos Equatorial</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Vinos Equatoria</h3>
                        <a class="details__description">Diseño web Informativo para una empresa de vinos
                            </p>
                            <ul class="details__info">
                                <li>Creado: <span>10 marzo 2020</span></li>
                                <li>Tecnologias: <span>Html - Css - JavaScript - Wordpress</span></li>
                                <li>Rol: <span>Dev Frontend</span></li>
                                <li>Vista: <span><a href="https://agroindustriasequatorial.com">demo</a></span></li>
                            </ul>
                        </a>
                    </div>
                </div>

                <div class="work__card mix design">
                    <img src="assets/imgs/proyectos/presentacion perfil.png" alt="" class="work__img">
                    <h3 class="work__title">Tarjeta Presentacion</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Tarjeta Presentacion</h3>
                        <p class="details__description"> Tarjeta de presentacion digital con arbol de links
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>19 febrero 2098</span></li>
                            <li>Tecnologias: <span>Html - Css Javascript</span></li>
                            <li>Rol: <span>UX-UI Designer</span></li>
                            <li>Visita: <span><a href="https://beacons.ai/itsnotcristhianr">demo</a></span>
                            </li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix app">
                    <img src="assets/imgs/proyectos/presentacion app firebase.png" alt="" class="work__img">
                    <h3 class="work__title">Aplicacion Android CRUD</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Aplicacion Android CRUD</h3>
                        <p class="details__description"> Aplicacion de Android/Ios que usa una api y permite hacer CRUD
                            de
                            productos y usuarios con firebase
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>10 Enero 2023</span></li>
                            <li>Tecnologias: <span>Flutter - Firebase</span></li>
                            <li>Rol: <span>Developer / UX-UI Designer</span></li>
                            <li>Vista: <span><a href="resourses/appFirebase2.zip">demo</a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix design">
                    <img src="assets/imgs/proyectos/presntacion filtro astigma.gif" alt="" class="work__img">
                    <h3 class="work__title">Filtro Astigma</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Filtro Astigma</h3>
                        <p class="details__description">Filtro para Instagram y facebook con retoques de luz.
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>19 febrero 2018</span></li>
                            <li>Tecnologias: <span>Meta-Spark</span></li>
                            <li>Rol: <span>UX-UI Designer</span></li>
                            <li>Visita: <span><a href="https://www.instagram.com/ar/587230052172601/">demo</a></span>
                            </li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix app">
                    <img src="assets/imgs/proyectos/proyecto planificador.png" alt="" class="work__img">
                    <h3 class="work__title">Planificador Round-Robbin</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Planificador de Procesos y Tareas</h3>
                        <p class="details__description">Sistema Operativo de control de Tareas <br>
                            (Simulador de tareas ejecutandose en Escritorio)</p>
                        <ul class="details__info">
                            <li>Creado: <span>4 Junio 2021</span></li>
                            <li>Tecnologias: <span>Java </span></li>
                            <li>Rol: <span>Developer</span></li>
                            <li>Vista: <span><a href="resourses/RoundRobinDemo.rar">demo</a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix web">
                    <img src="assets/imgs/proyectos/proyecto walki dogs.png" alt="" class="work__img">
                    <h3 class="work__title">Web WalkiDogs</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Landing Page WalkiDogs</h3>
                        <p class="details__description">Diseño y Maquetado de la Web basado en los requerimientos
                            del cliente en base a una pagina informativa.
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>12 febrero 2021</span></li>
                            <li>Tecnologias: <span>Html - Css</span></li>
                            <li>Rol: <span>Dev Frontend</span></li>
                            <li>Vista: <span><a href="https://outdoorsy-photos.000webhostapp.com/apps/WalkyDogs/principal.html">demo</a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix app">
                    <img src="assets/imgs/proyectos/presentacion app chumapp.png" alt="" class="work__img">
                    <h3 class="work__title">Chumapp</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">ChumApp (Android)</h3>
                        <p class="details__description">Aplicacion desarrollada para Android con el fin de ayudar a las
                            personas a encontrar
                            y comprar bebidas alcholicas
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>19 enero 2023</span></li>
                            <li>Tecnologias: <span>Xamarin </span></li>
                            <li>Rol: <span>Developer</span></li>
                            <li>Vista: <span><a href="resourses/APPCOMPRAS_demo.apk">demo </a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix web">
                    <img src="assets/imgs/proyectos/presentacion spicy.png" alt="" class="work__img">
                    <h3 class="work__title">Web Spicy</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">WEb Spicy</h3>
                        <p class="details__description">Prototipo de maqueta web para implementar en paginas Tipo
                            informativas o que requieran mostrar contenido tipo blog
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>2 abril 2019</span></li>
                            <li>Tecnologias: <span>Html Css Javascript</span></li>
                            <li>Rol: <span>Dev Frontend</span></li>
                            <li>Vista: <span><a href="https://outdoorsy-photos.000webhostapp.com/apps/spicy/index.html">demo</a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix web">
                    <img src="assets/imgs/proyectos/proyecto wep1p.png" alt="" class="work__img">
                    <h3 class="work__title">Web Informativa Design</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Diseño de web Informativa</h3>
                        <p class="details__description">Prototipo de maqueta web para implementar en paginas Tipo
                            informativas o que requieran mostrar contenido tipo blog
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>23 abril 2019</span></li>
                            <li>Tecnologias: <span>Html Css Javascript</span></li>
                            <li>Rol: <span>Dev Frontend</span></li>
                            <li>Vista: <span><a href="https://outdoorsy-photos.000webhostapp.com/apps/1.0P/index.html">demo</a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix design">
                    <img src="assets/imgs/proyectos/presntacion filtro glitch.gif" alt="" class="work__img">
                    <h3 class="work__title">Filtro Glitch</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Filtro Glitch</h3>
                        <p class="details__description">Filtro de imagen con efecto glitch para aplicar en imagenes
                            o videos para facebook e Instagram
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>29 febrero 2018</span></li>
                            <li>Tecnologias: <span>Meta-Spark</span></li>
                            <li>Rol: <span>UX-UI Designer</span></li>
                            <li>Visita: <span><a href="https://www.instagram.com/ar/365607665600007/">demo</a></span>
                            </li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix app">
                    <img src="assets/imgs/proyectos/proyecto web ahorcado.png" alt="" class="work__img">
                    <h3 class="work__title">Juego El ahorcado </h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">El ahorcado Web</h3>
                        <p class="details__description">Clasico Juego "El ahorcado" optimizado para navegadores webs
                        </p>
                        <ul class="details__info">
                            <li>Created: <span>29 agosto 2019</span></li>
                            <li>Tecnologias: <span>Html - Css - Javascript</span></li>
                            <li>Rol: <span>Dev Junior</span></li>
                            <li>Visita: <span><a href="https://isnotcristhianr.github.io/AhorcadosGame.github.io/">demo</a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix web">
                    <img src="assets/imgs/proyectos/presentacion formulario.png" alt="" class="work__img">
                    <h3 class="work__title">Formulario de Inscripcion</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Formulario de Inscripcion</h3>
                        <p class="details__description"> Formulario de inscripcion para colegios con validaciones
                            de campos y envio de datos a base de datos
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>7 Abril 2023</span></li>
                            <li>Tecnologias: <span>Html - Css - JavaScript - PHP </span></li>
                            <li>Rol: <span>Developer</span></li>
                            <li>Vista: <span><a
                                        href="https://outdoorsy-photos.000webhostapp.com/apps/creatibots/vista/formularioColegio.php">demo
                                    </a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix web">
                    <img src="assets/imgs/proyectos/presentacion login2.png" alt="" class="work__img">
                    <h3 class="work__title">Inicio de Sesion</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Inicio de Sesion</h3>
                        <p class="details__description">Diseño de un inicio de sesion con validacion de datos
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>27 Noviembre 2022</span></li>
                            <li>Tecnologias: <span>Html - Css - JavaScript </span></li>
                            <li>Rol: <span>Dev Frontend</span></li>
                            <li>Vista: <span><a
                                        href="https://bdcrudestudiantes.000webhostapp.com/apps/sesiones/pagAlumnos/vista/login.php">demo
                                    </a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix web">
                    <img src="assets/imgs/proyectos/presentacion indeximgs.png" alt="" class="work__img">
                    <h3 class="work__title">Repositorio Imagenes Online</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Repositorio Imagenes Online</h3>
                        <p class="details__description">Diseñada para optimizar carga de imagenes en paginas web, se
                            puede
                            descargarla y usarla en cualquier proyecto
                        </p>
                        <ul class="details__info">
                            <li>Creado - <span>28 Noviembre 2022</span></li>
                            <li>Tecnologias - <span>Javascript</span></li>
                            <li>Rol - <span>Developer</span></li>
                            <li>Visita - <span><a
                                        href="https://bdcrudestudiantes.000webhostapp.com/imgs/">demo</a></span></li>
                        </ul>
                    </div>
                </div>

                <!--   <div class="work__card mix app">
                    <img src="assets/imgs/proyectos/app calc.png" alt="" class="work__img">
                    <h3 class="work__title">App Calculadora Niñ@s</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">App Calculadora Niñ@s</h3>
                        <p class="details__description">Aplicacion web educativa <br>
                            (permite visualizar en cadenas de 5 multiplicaciones hasta el infinito para repasar las
                            tablas de multiplicar).</p>
                        <ul class="details__info">
                            <li>Creado: <span>4 Junio 2021</span></li>
                            <li>Tecnologias: <span>Html - Css </span></li>
                            <li>Rol: <span>Dev Junior</span></li>
                            <li>Vista: <span><a href="#">demo</a></span></li>
                        </ul>
                    </div>
                </div> -->

                <div class="work__card mix web">
                    <img src="assets/imgs/proyectos/proyecto info curso.png" alt="" class="work__img">
                    <h3 class="work__title">Web Infotmativa Cursos</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Web Infotmativa Cursos</h3>
                        <p class="details__description">Diseñada a partir de una maqueta simple enfocada <br> en la
                            optimizacion de la Informacion
                            presentada.
                        </p>
                        <ul class="details__info">
                            <li>Creado - <span>05 septiembre 2022</span></li>
                            <li>Tecnologias - <span>Html - Css</span></li>
                            <li>Rol - <span>Dev Frontend</span></li>
                            <li>Visita - <span><a href="https://outdoorsy-photos.000webhostapp.com/apps/EjerciciosHtml/1/index.html">www.domain.com</a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix app">
                    <img src="assets/imgs/proyectos/presentacion sac enci.png" alt="" class="work__img">
                    <h3 class="work__title">Sistema de Ahorro Contable</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">istema de Ahorro Contable</h3>
                        <p class="details__description"> Sistema de ahorro contable para el control de ingresos y
                            egresos de una empresa
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>13 Febrero 2023</span></li>
                            <li>Tecnologias: <span>Html - Css - JavaScript - Mysql - .Net - C# </span></li>
                            <li>Rol: <span>Developer</span></li>
                            <li>Vista: <span><a href="resourses/ProyectoCoworking_SAC.rar">demo </a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix web">
                    <img src="assets/imgs/proyectos/plantilla curriculum web.png" alt="" class="work__img">
                    <h3 class="work__title">Web Curriculum Basica</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Web Curriculum Basica</h3>
                        <p class="details__description">Web sencilla para mostrar un perfil laboral. <br>
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>05 septiembre 2022</span></li>
                            <li>Tecnologias: <span>Html - Css</span></li>
                            <li>Rol: <span>Dev Frontend</span></li>
                            <li>Visita: <span><a href="https://outdoorsy-photos.000webhostapp.com/apps/trabajoenclaseSemana3_RecaldeCristhian/index.html">demo</a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix app">
                    <img src="assets/imgs/proyectos/app matriz.png" alt="" class="work__img">
                    <h3 class="work__title">App Matriz Transpuesta</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">App Matriz Transpuesta</h3>
                        <p class="details__description">Aplicacion de escritorio que resuelve matrices y las
                            transpone
                        <ul class="details__info">
                            <li>Creado: <span>14 enero 2021</span></li>
                            <li>Tecnologias: <span>Java </span></li>
                            <li>Rol: <span>Dev Junior</span></li>
                            <li>Vista: <span><a href="resourses/EjecutableMatrices.rar">demo</a></span></li>
                        </ul>
                    </div>
                </div>


                <div class="work__card mix web">
                    <img src="assets/imgs/proyectos/web informativa.png" alt="" class="work__img">
                    <h3 class="work__title">Web Informativa Valores Empresariales</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Web Infotmativa Valores Empresariales</h3>
                        <p class="details__description">Inspirado en la recursividad y enfocada a dar una mayor
                            accesibilidad <br> al acceso
                            de la representacion de los valores Empresariales.
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>10 septiembre 2022</span></li>
                            <li>Tecnologias: <span>Html - Css</span></li>
                            <li>Rol: <span>Dev Frontend</span></li>
                            <li>Visita: <span><a href="https://outdoorsy-photos.000webhostapp.com/apps/EjerciciosHtml/2/index.html">demo</a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix design">
                    <img src="assets/imgs/proyectos/presntacion filtro indie.gif" alt="" class="work__img">
                    <h3 class="work__title">Filtro Indie</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Filtro Indie</h3>
                        <p class="details__description">Filtro de imagen inspirado en el estilo Indie para facebook e
                            instagram
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>29 febrero 2018</span></li>
                            <li>Tecnologias: <span>Meta-Spark</span></li>
                            <li>Rol: <span>UX-UI Designer</span></li>
                            <li>Visita: <span><a href="https://www.instagram.com/ar/164923048603691/">demo</a></span>
                            </li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix web">
                    <img src="assets/imgs/proyectos/proyecto tienda ropa.png" alt="" class="work__img">
                    <h3 class="work__title">Web Tienda Ropa</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Web Tienda Ropa</h3>
                        <p class="details__description">Web interactiva para una tienda de ropa <br>
                            permite visualizar el catalogo disponible de ropa de manera intuitiva y versátil.
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>04 Octubre 2022</span></li>
                            <li>Tecnologias: <span>Html - Css</span></li>
                            <li>Rol: <span>Dev Frontend</span></li>
                            <li>Visita: <span><a href="https://outdoorsy-photos.000webhostapp.com/apps/ActividadSemana3_RecaldeCristhian/index.html">demo</a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix app">
                    <img src="assets/imgs/proyectos/presentacion crud.png" alt="" class="work__img">
                    <h3 class="work__title">Directorio Estudiantes</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Directorio de Estudiantes</h3>
                        <p class="details__description">Sistema CRUD para ingreso de estudiantes y sus datos a un
                            sistema de registro y control
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>25 Noviembre 2022</span></li>
                            <li>Tecnologias: <span>Html - Css - JavaScript - PHP - Codelgniter </span></li>
                            <li>Rol: <span>Developer</span></li>
                            <li>Vista: <span><a
                                        href="https://bdcrudestudiantes.000webhostapp.com/apps/pgA2/pagAlumnos/vista/index.php">demo
                                    </a></span></li>
                        </ul>
                    </div>
                </div>

                <!-- <div class="work__card mix design">
                    <img src="assets/imgs/proyectos/proyecto wep visual.png" alt="" class="work__img">
                    <h3 class="work__title">Web Presentacion Usuario</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Web Presentacion Usuario</h3>
                        <p class="details__description">Inspirada en las olas de mar, diseñada para mostrar las
                            capacidades <br>
                            del desarrollador y una muestra del arte que se puede crear con codigo
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>19 febrero 2018</span></li>
                            <li>Tecnologias: <span>Html - Css</span></li>
                            <li>Rol: <span>Dev Frontend</span></li>
                            <li>Visita: <span><a href="#">demo</a></span></li>
                        </ul>
                    </div>
                </div>
 -->
                <div class="work__card mix app">
                    <img src="assets/imgs/proyectos/presentacion apipokemon.png" alt="" class="work__img">
                    <h3 class="work__title">Buscador Pokemon</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Consumo de la Api de Pokemon</h3>
                        <p class="details__description">Uso de la Api de Pokemon para mostrar los datos de los pokemones
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>20 enero 2023</span></li>
                            <li>Tecnologias: <span>Html - Css - JavaScript</span></li>
                            <li>Rol: <span>Dev Frontend</span></li>
                            <li>Vista: <span><a
                                        href="https://bdcrudestudiantes.000webhostapp.com/apps/consumoWebServices2_RecaldeCristhian/index.html">demo
                                    </a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix web">
                    <img src="assets/imgs/proyectos/proyecto royal vitas.png" alt="" class="work__img">
                    <h3 class="work__title">Web Hotel Royal Vitas</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Web Hotel Royal Vitas</h3>
                        <p class="details__description">Estilo simple basado en ser minimalista y del agrado del
                            usuario
                            <br> como del huesped
                            que visualice la web
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>21 septiembre 2022</span></li>
                            <li>Tecnologias: <span>Html - Css </span></li>
                            <li>Rol: <span>Dev Frontend</span></li>
                            <li>Visita: <span><a href="https://outdoorsy-photos.000webhostapp.com/apps/EjerciciosHtml/3/index.html">demo</a></span></li>
                        </ul>
                    </div>
                </div>

                <div class="work__card mix design">
                    <img src="assets/imgs/proyectos/presntacion filtro vintage.gif" alt="" class="work__img">
                    <h3 class="work__title">Filtro Vintage</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Filtro Vintage</h3>
                        <p class="details__description">Filtro de imagen inspirado en el estilo vintage para facebook e
                            instagram
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>29 febrero 2018</span></li>
                            <li>Tecnologias: <span>Meta-Spark</span></li>
                            <li>Rol: <span>UX-UI Designer</span></li>
                            <li>Visita: <span><a href="https://www.instagram.com/ar/466877215086875/">demo</a></span>
                            </li>
                        </ul>
                    </div>
                </div>


                <div class="work__card mix design">
                    <img src="assets/imgs/proyectos/proyecto app zapatillas.png" alt="" class="work__img">
                    <h3 class="work__title">Diseño App Nike</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">App UI para una tienda de zapatos</h3>
                        <p class="details__description">Diseño de maquetado moderno para aplicaciones moviles listas
                            para entrar <br>
                            a produccion de codificacion
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>9 diciembre 2020</span></li>
                            <li>Tecnologias: <span>Adobe XD - Figma</span></li>
                            <li>Rol: <span>UX-UI Designer</span></li>
                            <li>Vista: <span><a href="resourses/Apps Zapatillas 1.xd">demo </a></span></li>
                        </ul>
                    </div>
                </div>

<!--                 <div class="work__card mix desing">
                    <img src="assets/imgs/proyectos/presentacion logins.png" alt="" class="work__img">
                    <h3 class="work__title">Inicio de Sesion</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Inicio de Sesion</h3>
                        <p class="details__description">Diseño de un inicio de sesion con un estilo moderno y
                            minimalista
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>15 diciembre 2022</span></li>
                            <li>Tecnologias: <span>Html - Css - JavaScript - PHP</span></li>
                            <li>Rol: <span>Dev Frontend</span></li>
                            <li>Vista: <span><a href="#">demo </a></span></li>
                        </ul>
                    </div>
                </div> -->

                <div class="work__card mix app">
                    <img src="assets/imgs/proyectos/presentacion api.png" alt="" class="work__img">
                    <h3 class="work__title">Api Full Rest</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Api Rest de un consultorio medico</h3>
                        <p class="details__description">Api que, contiene dni, altura, peso, imc, etc; permite acciones
                            de CRUD
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>12 enero 2023</span></li>
                            <li>Tecnologias: <span>PHP</span></li>
                            <li>Rol: <span>Dev backend</span></li>
                            <li>Vista: <span><a href="https://outdoorsy-photos.000webhostapp.com/apps/01pagAlumnos/servicios/api.php">demo</a></span></li>
                        </ul>
                    </div>
                </div>



                <div class="work__card mix app">
                    <img src="assets/imgs/proyectos/presentacion app flutter.png" alt="" class="work__img">
                    <h3 class="work__title">Calculadora IMC</h3>
                    <span class="work__button">Demo
                        <i class="uil uil-arrow-right work__button-icon"></i>
                    </span>
                    <div class="portfolio__item-details">
                        <h3 class="details__title">Calculadora IMC</h3>
                        <p class="details__description"> Aplicacion movil que calcula el indice de masa corporal
                        </p>
                        <ul class="details__info">
                            <li>Creado: <span>5 Enero 2023</span></li>
                            <li>Tecnologias: <span>flutter </span></li>
                            <li>Rol: <span>Developer</span></li>
                            <li>Vista: <span><a href="resourses/app-release.apk">demo </a></span></li>
                        </ul>
                    </div>
                </div>



            </div>
        </section>

        <!-- Portfolio Popup -->
        <div class="portfolio__popup">
            <div class="portfolio__popup-inner">
                <div class="portfolio__popup-content grid">
                    <span class="portfolio__popup-close"><i class="uil uil-times"></i></span>
                    <div class="pp__thumbnail">
                        <img src="assets/imgs/proyectos/app matriz.png" alt="" class="portfolio__popup-img">
                    </div>
                    <div class="portfolio__popup-info">
                        <div class="portfolio__popup-subtitle">Tipo - <span>Design</span></div>
                        <div class="portfolio__popup-body">
                            <h3 class="details__title">App para Tecnologia y Servicios</h3>
                            <p class="details__description">Lorem ipsum, dolor sit amet consectetur adipisicing
                                elit.
                                Earum impedit voluptatibus minima.</p>
                            <ul class="details__info">
                                <li>Created - <span>4 dec 2020</span></li>
                                <li>Technologies - <span>html css</span></li>
                                <li>Role - <span>frontend</span></li>
                                <li>View - <span><a href="#">www.domain.com</a></span></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!--===== Services =====-->
        <section class="skills section" id="skills">
            <h2 data-heading="Habilidades" class="section__title">Experiencia</h2>

            <div class="skills__container container grid">
                <div class="skills__tabs">
                    <div class="skills__header skills__active" data-target="#frontend">
                        <i class="uil uil-brackets-curly skills__icon"></i>

                        <div>
                            <h1 class="skills__title">Desarrollador Frontend</h1>
                            <span class="skills__subtitle">+5 años</span>
                        </div>

                        <i class="uil uil-angle-down skills__arrow"></i>
                    </div>

                    <div class="skills__header" data-target="#design">
                        <i class="uil uil-swatchbook skills__icon"></i>

                        <div>
                            <h1 class="skills__title">Diseño UI / UX</h1>
                            <span class="skills__subtitle">+3 años</span>
                        </div>

                        <i class="uil uil-angle-down skills__arrow"></i>
                    </div>

                    <div class="skills__header" data-target="#prog">
                        <i class="uil uil-arrow services__icon"></i>

                        <div>
                            <h1 class="skills__title">Lenguajes de Programacion</h1>
                            <span class="skills__subtitle">+7 años</span>
                        </div>

                        <i class="uil uil-angle-down skills__arrow"></i>
                    </div>

                    <div class="skills__header" data-target="#frame">
                        <i class="uil uil-analytics services__icon"></i>

                        <div>
                            <h1 class="skills__title"> Frameworks</h1>
                            <span class="skills__subtitle">+2 años</span>
                        </div>

                        <i class="uil uil-angle-down skills__arrow"></i>
                    </div>

                    <div class="skills__header" data-target="#backend">
                        <i class="uil uil-database skills__icon"></i>

                        <div>
                            <h1 class="skills__title">Base de Datos</h1>
                            <span class="skills__subtitle">+3 años</span>
                        </div>

                        <i class="uil uil-angle-down skills__arrow"></i>
                    </div>

                    <div class="skills__header" data-target="#grafics">
                        <i class="uil uil-server-network skills__icon"></i>

                        <div>
                            <h1 class="skills__title">Motores Graficos</h1>
                            <span class="skills__subtitle">+1 año</span>
                        </div>

                        <i class="uil uil-angle-down skills__arrow"></i>
                    </div>
                </div>

                <div class="skills__content">
                    <div class="skills__group skills__active" data-content id="frontend">
                        <div class="skills__list grid">
                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">HTML</h3>
                                    <span class="skills__number">90%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 90%;"></span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">CSS</h3>
                                    <span class="skills__number">70%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 70%;"></span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">Plug-ins JavaScript</h3>
                                    <span class="skills__number">80%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 80%;"></span>
                                </div>
                            </div>

                        </div>
                    </div>

                    <div class="skills__group" data-content id="design">
                        <div class="skills__list grid">
                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">Figma/Ilustrator</h3>
                                    <span class="skills__number">60%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 60%;"></span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">Sketch</h3>
                                    <span class="skills__number">80%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 80%;"></span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">MetaSparkHub</h3>
                                    <span class="skills__number">60%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 60%;"></span>
                                </div>
                            </div>
                                    

                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">Photoshop</h3>
                                    <span class="skills__number">40%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 30%;"></span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">Premier Pro</h3>
                                    <span class="skills__number">50%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 40%;"></span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="skills__group" data-content id="prog">
                        <div class="skills__list grid">
                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">PHP</h3>
                                    <span class="skills__number">50%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 50%;"></span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">Python</h3>
                                    <span class="skills__number">60%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 60%;"></span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">Java</h3>
                                    <span class="skills__number">85%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 85%;"></span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">C</h3>
                                    <span class="skills__number">60%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 60%;"></span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">C#</h3>
                                    <span class="skills__number">40%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 40%;"></span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">Dart</h3>
                                    <span class="skills__number">50%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 50%;"></span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">Javascript</h3>
                                    <span class="skills__number">70%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 70%;"></span>
                                </div>
                            </div>
                        </div>
                    </div>


                    <div class="skills__group" data-content id="backend">
                        <div class="skills__list grid">
                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">MySql</h3>
                                    <span class="skills__number">70%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 70%;"></span>
                                </div>
                            </div>

                            <div class="skills__list grid">
                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">Postgresql</h3>
                                        <span class="skills__number">50%</span>
                                    </div>

                                    <div class="skills__bar">
                                        <span class="skills__percentage" style="width: 50%;"></span>
                                    </div>
                                </div>
                            </div>

                            <div class="skills__list grid">
                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">Oracle</h3>
                                        <span class="skills__number">50%</span>
                                    </div>

                                    <div class="skills__bar">
                                        <span class="skills__percentage" style="width: 50%;"></span>
                                    </div>
                                </div>
                            </div>

                            <div class="skills__list grid">
                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">Firebase</h3>
                                        <span class="skills__number">70%</span>
                                    </div>

                                    <div class="skills__bar">
                                        <span class="skills__percentage" style="width: 70%;"></span>
                                    </div>
                                </div>
                            </div>

                        </div>
                    </div>

                    <div class="skills__group" data-content id="frame">
                        <div class="skills__list grid">
                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">Codelgniter</h3>
                                    <span class="skills__number">60%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 60%;"></span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">Flutter</h3>
                                    <span class="skills__number">50%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 50%;"></span>
                                </div>
                            </div>



                        </div>
                    </div>

                    <div class="skills__group" data-content id="grafics">
                        <div class="skills__list grid">
                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">Unity 3D</h3>
                                    <span class="skills__number">25%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 25%;"></span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">Unreal Engine 4</h3>
                                    <span class="skills__number">10%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 10%;"></span>
                                </div>
                            </div>

                            <div class="skills__data">
                                <div class="skills__titles">
                                    <h3 class="skills__name">Unreal Engine 5</h3>
                                    <span class="skills__number">8%</span>
                                </div>

                                <div class="skills__bar">
                                    <span class="skills__percentage" style="width: 8%;"></span>
                                </div>
                            </div>

                        </div>
                    </div>
        </section>

        <!--===== Testimonials =====-->
        <!--Proximamente
        <div data-aos="fade-up-left">
            <section class="testimonials section">
                <h2 data-heading="Comentarios" class="section__title">Testimonios</h2>

                <div class="testimonials__container container swiper">
                    <div class="swiper-wrapper">
                        <div class="testimonial__card swiper-slide">
                            <div class="testimonial__quote">
                                <i class='bx bxs-quote-alt-left'></i>
                            </div>
                            <p class="testimonial__description">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                Exercitationem quaerat ducimus ea.</p>
                            <h3 class="testimonial__date">March 27. 2020</h3>
                            <div class="testimonial__profile">
                                <img src="assets/img/client1.jpg" alt="" class="testimonial__profile-img">

                                <div class="testimonial__profile-data">
                                    <span class="testimonial__profile-name">Lee Doe</span>
                                    <span class="testimonial__profile-detail">Director of a company</span>
                                </div>
                                <div class="testimonial__quote">
                                    <i class='bx bxs-quote-alt-left'></i>
                                </div>
                            </div>
                        </div>

                        <div class="testimonial__card swiper-slide">
                            <div class="testimonial__quote">
                                <i class='bx bxs-quote-alt-left'></i>
                            </div>
                            <p class="testimonial__description">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                Exercitationem quaerat ducimus ea.</p>
                            <h3 class="testimonial__date">March 27. 2020</h3>
                            <div class="testimonial__profile">
                                <img src="assets/img/client2.jpg" alt="" class="testimonial__profile-img">

                                <div class="testimonial__profile-data">
                                    <span class="testimonial__profile-name">Lee Doe</span>
                                    <span class="testimonial__profile-detail">Director of a company</span>
                                </div>
                            </div>
                        </div>

                        <div class="testimonial__card swiper-slide">
                            <div class="testimonial__quote">
                                <i class='bx bxs-quote-alt-left'></i>
                            </div>
                            <p class="testimonial__description">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                Exercitationem quaerat ducimus ea.</p>
                            <h3 class="testimonial__date">March 27. 2020</h3>
                            <div class="testimonial__profile">
                                <img src="assets/img/client3.jpg" alt="" class="testimonial__profile-img">

                                <div class="testimonial__profile-data">
                                    <span class="testimonial__profile-name">Lee Doe</span>
                                    <span class="testimonial__profile-detail">Director of a company</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="swiper-pagination"></div>
                </div>
            </section>
        </div>
        -->


        <!--===== Contact =====-->
        <section class="contact section" id="contact">
            <h2 data-heading="Directorio" class="section__title">Contáctame</h2>

            <div class="contact__container container grid">
                <div class="contact__content">
                    <div class="contact__info">
                        <div class="contact__card">
                            <i class="uil uil-envelope-edit contact__card-icon"></i>
                            <h3 class="contact__card-title">Email</h3>
                            <span class="contact__card-data">isnotcristhianr@gmail.com</span>
                            <a href="mailto:isnotcristhianr@gmail.com" target="_blank" class="contact__button">
                                Contáctame<i class="uil uil-arrow-right contact__button-icon"></i>
                            </a>
                        </div>

                        <div class="contact__card">
                            <i class="uil uil-whatsapp contact__card-icon"></i>
                            <h3 class="contact__card-title">Whatsapp</h3>
                            <span class="contact__card-data">(+593) 996221950</span>
                            <a href="https://api.whatsapp.com/send?phone=+593996221950&text=Hola, Estoy interesado en trabajar contigo!"
                                target="_blank" class="contact__button">
                                Escríbeme <i class="uil uil-arrow-right contact__button-icon"></i>
                            </a>
                        </div>

                        <div class="contact__card">
                            <i class="uil uil-linkedin contact__card-icon"></i>
                            <h3 class="contact__card-title">linkedin</h3>
                            <span class="contact__card-data">@isnotcristhianr</span>
                            <a href="https://www.linkedin.com/in/cristhian-recalde-a84679171/" class="contact__button">
                                Ver Perfil <i class="uil uil-arrow-right contact__button-icon"></i>
                            </a>
                        </div>
                    </div>
                </div>

                <div class="contact__content">
                    <form action="https://formspree.io/f/mgebzbgk" method="POST" class="contact__form">
                        <div class="input__container">
                            <input aria-label="Search" type="text" class="input" name="nameUser" required>
                            <label for="">Nombre de Usuario</label>
                            <span>Nombre de Usuario</span>
                        </div>
                        <div class="input__container">
                            <input aria-label="Search" type="email" class="input" name="userEmail" required>
                            <label for="">Email</label>
                            <span>Email</span>
                        </div>
                        <div class="input__container">
                            <input aria-label="Search" type="tel" class="input" name="userTelf" required>
                            <label for="">Teléfono</label>
                            <span>Teléfono</span>
                        </div>
                        <div class="input__container textarea">
                            <textarea aria-label="Search" name="userText" id="" class="input"></textarea>
                            <label for="">Mensaje</label>
                            <span>Mensaje</span>
                        </div>
                        <button type="submit" class="button" name="userEnvio"><i
                                class="uil uil-navigator button__icon"></i>
                            Enviar
                        </button>
                    </form>
                </div>
            </div>
        </section>

        <!--===== Otros =====-->
        <section class="otros section" id="otros">
            <h2 data-heading="Social" class="section__title">Otros</h2>

            <div class="spotify">
                <h3 data-heading="Spotify" class="section__title"></h3>
                <iframe style="border-radius:12px"
                    src="https://open.spotify.com/embed/playlist/34JdRTqEJGlZNWLoQeZiuL?utm_source=generator&theme=0"
                    width="60%" height="370" frameBorder="0"  allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture">
                </iframe>
            </div>


        </section>

        <!--========== FOOTER ==========-->
        <footer class="footer">
            <div class="footer__bg">
                <div class="footer__container container grid">
                    <div>
                        <h1 class="footer__title">isnotcristhianr</h1>
                        <span class="footer__subtitle">Desarrollo de Software - Community Manager</span>
                    </div>

                    <ul class="footer__links">
                        <li>
                            <a href="#services" class="footer__link">Servicios</a>
                        </li>
                        <li>
                            <a href="#work" class="footer__link">Proyectos</a>
                        </li>
                        <li>
                            <a href="#contact" class="footer__link">Contáctame</a>
                        </li>
                        <li>
                            <a href="#otros" class="footer__link">Otros</a>
                        </li>
                    </ul>

                    <div class="footer__socials">
                        <a href="https://www.facebook.com/IsnotCristhianr/" target="_blank" class="footer__social">
                            <i class="uil uil-facebook-f"></i>
                        </a>
                        <a href="https://www.instagram.com/itsnotcristhianr/" target="_blank" class="footer__social">
                            <i class="uil uil-instagram"></i>
                        </a>
                        <a href="https://twitter.com/Cristhi69039818" target="_blank" class="footer__social">
                            <i class="uil uil-twitter"></i>
                        </a>
                    </div>

                </div>

                <p class="footer__copy">&#169; isnotcristhianr. All right reserved 2023</p>
            </div>

        </footer>
    </main>

    <!--========== SCROLL UP ==========-->
    <a aria-label="Search" href="#" class="scrollup" id="scroll-up">
        <i class="bx bx-up-arrow-alt scrollup__icon"></i>
    </a>
    <!--========== SCROLLREVEAL ==========-->
    <script src="https://unpkg.com/scrollreveal"></script>

    <!--========== TYPESCRIPT ==========-->
    <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.11"></script>

    <!--========== MIXITUP FILTER ==========-->
    <script src="assets/js/js/mixitup.min.js"></script>

    <!--========== SWIPER JS ==========-->
    <script src="assets/js/js/swiper-bundle.min.js"></script>

    <!--========== ALERTS JS ==========-->
    <script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>

    <!--========== NFTS JS ==========-->
    <script src="https://unpkg.com/embeddable-nfts/dist/nft-card.min.js"></script>

    <!--========Scroll Animation Js====================-->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>

    <!--========== MAIN JS ==========-->
    <script src="assets/js/js/main.js"></script>

    <!--JS general-->
    <script>
        AOS.init();
    </script>
</body>

</html>
