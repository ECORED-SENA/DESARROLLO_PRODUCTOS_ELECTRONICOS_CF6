<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Planificación del ensamble de tarjetas electrónicas
    
    .row.mb-5
      .col-12.col-md-6.mb-3.mb-md-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/tema1/t1-1.png', alt='Texto que describa la imagen')
      .col-12.col-md-6(data-aos="fade-left")
        .cajon.bgr.p-5.mb-3
          p.mb-0 La planificación es una fase importante de cualquier proceso. En el ensamble de tarjetas, esto influye mayormente en el resultado de la producción general de cualquier equipo electrónico. Una mala planificación traerá muchas consecuencias, desde errores de ensamble hasta pérdidas económicas para una empresa.
        .row
          .col-12.col-md-2.mb-3.mb-md-0.d-flex.align-items-center.justify-content-center
            figured
              img.img90(src='@/assets/curso/tema1/t1-2.svg', alt='Texto que describa la imagen')
          .col-12.col-md-10
            p.mb-0 La planificación requiere que se tenga un conocimiento amplio de la naturaleza de la tarjeta a ensamblar, es necesario contar con los planos y la documentación completa del proyecto, tal como se observa en la figura.
    
    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 2
      span Planificación del ensamble
    
    .row.mb-5.justify-content-center(data-aos="zoom-in")
      .col-12.col-md-10
        figure
          img(src='@/assets/curso/tema1/t1-3.svg', alt='Texto que describa la imagen')
    
    separador

    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Equipos de ensamblaje electrónico
    
    .row.mb-5
      .col-12.col-md-6.mb-3.mb-md-0(data-aos="fade-right")
        .cajon.bgr_2.p-5.mb-3
          p.mb-0 Los equipos usados para el ensamblaje electrónico son muy variados, dependiendo de si el proceso es manual o automatizado, pero todos cumplen el mismo propósito: posicionar y fijar con soldadura los componentes electrónicos a la PCB <em>(Printed Circuit Board)</em>.
        p Los equipos más destacados son los siguientes:
      .col-12.col-md-6(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema1/t1-4.png', alt='Texto que describa la imagen')

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 3
      span Equipos destacados
    
    .row.mb-5.justify-content-center(data-aos="zoom-in")
      .col-12.col-md-10
        figure
          img(src='@/assets/curso/tema1/t1-5.svg', alt='Texto que describa la imagen')
    
    p.mb-5 A continuación, se explica cada uno de ellos: 

    .bgr_3.p-2.mb-5(data-aos="fade-down-right")
      h4.mb-0 a. Estación de soldadura
    
    .row.mb-5
      .col-12.col-md-4.mb-3.mb-md-0(data-aos="fade-up")
        .cajon.bgr.p-4
          .row
            .col-12.col-md-3.mb-3.mb-md-0
              figure.d-flex.justify-content-center.mb-3.mb-md-0
                img.img90(src='@/assets/curso/tema1/t1-6.svg', alt='Texto que describa la imagen')
            .col-12.col-md-9
              p.mb-0 La estación de soldadura es un equipo que reemplazó, con el paso de los años, el uso del típico cautín. Es un equipo encargado básicamente de regular a través de la potencia que entrega al elemento calefactor la temperatura en la punta del mango que es el elemento que tiene contacto final con el estaño y el elemento a soldar.
      .col-12.col-md-4.mb-3.mb-md-0(data-aos="fade-down")
        figure
          img(src='@/assets/curso/tema1/t1-7.png', alt='Texto que describa la imagen')
      .col-12.col-md-4(data-aos="fade-up")
        p.mb-0 Esta se caracteriza por ser una caja metálica que cuenta con controles manuales digitales o analógicos para dominar la temperatura de cada mango por separado. Generalmente, cuenta con algún tipo de elemento de visualización, como <em>display</em> o pantalla, que permite observar de forma precisa la temperatura presente en cada mango, y en algunos casos, si hay algún tipo de fallo, también cuenta con puertos conectores donde se ancla el cable que lleva la alimentación al elemento calefactor; en la mayoría de casos, cada mango es también la entrada de señal de algún sensor que detecta la temperatura en la punta del mismo. 
    
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/t1-8.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 En algunas estaciones se cuenta con una función adicional, que consiste en brindar un flujo de aire caliente para soldar (mangos de aire caliente) o desoldar componentes, y en las estaciones más especializadas se cuenta con una función de succión, donde se tiene un mango especial hueco, el cual tiene también un calefactor, que ayuda, mediante una bomba ubicada en la estación, a absorber la soldadura fundida (mango extractor). Esta función es usada para desoldar componentes de hueco pasante <em>(thru-hole)</em>.
    
    p.mb-5 En la siguiente imagen, se pueden observar varios tipos de estaciones de soldadura electrónica.

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 4
      span Tipos de estaciones de soldadura electrónica
    .bg_grad-02
      .row.mb-5.justify-content-center
        .col-12.col-md-10
          .row.mb-5.p-5.bg_grad-01.justify-content-center(data-aos="zoom-in")
            .col-12.col-md-6.mb-3.mb-md-0
              figure
                img(src='@/assets/curso/tema1/t1-9.png', alt='Texto que describa la imagen')
            .col-12.col-md-6.mb-3
              figure
                img(src='@/assets/curso/tema1/t1-10.png', alt='Texto que describa la imagen')
            Audio.color-acento-contenido.mx-3.pst(
              :audio="require('@/assets/componentes/audios/1.wav')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
    
    p.mb-5 Las estaciones de soldadura electrónica que más mantenimiento requieren por parte del ensamblador, el técnico/tecnólogo u operador son las que cuentan con mango extractor, ya que estas cuentan con un filtro que evita que los trozos de soldadura extraídos paren dentro de la bomba que genera la succión.

    .cajon.bgr_2.p-3.mb-5(data-aos="flip-down")
      .row.justify-content-center
        .col-12.col-md-1.mb-3.mb-md-0
          figure.d-flex.justify-content-center
            img.img90(src='@/assets/curso/tema1/t1-11.svg', alt='Texto que describa la imagen')
        .col-12.col-md-10.d-flex.align-items-center
          p.mb-0 Es necesario que cada vez que el mango pierde poder de succión, se extraiga este filtro, se desocupe y se limpie, para evitar su avería.

    .bgr_3.p-2.mb-5(data-aos="fade-down-right")
      h4.mb-0 b. Hornos de reflujo
    
    .row.mb-5
      .col-12.col-md-4.mb-3.mb-md-0(data-aos="fade-down")
        span A nivel industrial, se hace necesario que la producción y el ensamble de las tarjetas sea un proceso más ágil. El ensamble manual es engorroso y toma tiempo, además de requerir de una gran experticia por parte del ensamblador, por esto son muy útiles equipos como el horno de reflujo. 
        span.colr.text-bold Es una máquina de convección, que posee un control sofisticado de temperatura que permite crear el llamado “perfil”, el cual es la curva de temperatura durante el proceso de reflujo de la soldadura.
        .cajon.bgr_2.p-4.mt-4
          p El reflujo es el proceso mediante el cual la soldadura en pasta se derrite mientras se sueldan así los componentes. 
      .col-12.col-md-4.mb-3.mb-md-0(data-aos="fade-up")
        figure
          img(src='@/assets/curso/tema1/t1-12.png', alt='Texto que describa la imagen')
      .col-12.col-md-4(data-aos="fade-down")
        .bgr_4.p-3.h-100
          p.mb-0 El perfil depende de varios factores asociados: el tamaño del horno, el tipo de la soldadura, el tipo de fundente y, por supuesto, las características del horno como tal. Generalmente, los fabricantes de estos hornos ya tienen caracterizados estos perfiles, los cuales son los recomendados, pero en el proceso se pueden ir ajustando de acuerdo con las necesidades de la parametrización que se hace con el control mismo del horno.
          p.mb-0 Los perfiles son muy similares y tienen como objeto hacer un control preciso de la temperatura, para asegurar una correcta soldadura protegiendo así la integridad de los componentes. La siguiente imagen presenta una estructura básica de un perfil.
 
    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 5
      span Perfil de temperatura
    .bg_grad-03
      .row.mb-5.justify-content-center.mb-5
        .col-12.col-md-8
          figure
            img(src='@/assets/curso/tema1/t1-13.svg', alt='Texto que describa la imagen')
    
    .row.mb-5
      .col-12.col-md-8.mb-3.mb-md-0
        p Existen hornos de reflujo prácticamente de todos los tipos, pero en general todos funcionan igual y su perfil es parecido al mostrado en la figura anterior. Los hornos de tipo industrial cuentan con una banda que mueve las tarjetas por diferentes zonas de calentamiento, de forma que aseguran la ejecución del perfil y permiten procesar una gran cantidad de tarjetas al mismo tiempo, generando un proceso continuo y en serie.
        .titulo-sexto.color-acento-contenido.mb-3(data-aos="fade-down-right")
          h5 Figura 6
          span Hornos de reflujo
        #carouselExampleIndicators.carousel.slide.pst_1(data-bs-ride='carousel')
          .carousel-indicators
            button.active(type='button' data-bs-target='#carouselExampleIndicators' data-bs-slide-to='0' aria-current='true' aria-label='Slide 1')
            button(type='button' data-bs-target='#carouselExampleIndicators' data-bs-slide-to='1' aria-label='Slide 2')
          .carousel-inner
            .carousel-item.active
              figure
                img(src='@/assets/curso/tema1/t1-15.png', alt='Texto que describa la imagen')
                figcaption Nota. Tomada de Das (2021).
            .carousel-item
              figure
                img(src='@/assets/curso/tema1/t1-16.png', alt='Texto que describa la imagen')
                figcaption Nota. Tomada de Qtsolder (2021).
          button.carousel-control-prev(type='button' data-bs-target='#carouselExampleIndicators' data-bs-slide='prev')
            span.carousel-control-prev-icon(aria-hidden='true')
            span.visually-hidden Previous
          button.carousel-control-next(type='button' data-bs-target='#carouselExampleIndicators' data-bs-slide='next')
            span.carousel-control-next-icon(aria-hidden='true')
            span.visually-hidden Next
      .col-12.col-md-4
        figure
          img(src='@/assets/curso/tema1/t1-14.png', alt='Texto que describa la imagen')
    
    .bgr_3.p-2.mb-5(data-aos="fade-down-right")
      h4.mb-0 c. Equipos de soldadura por ola
    
    .row.mb-5
      .col-12.col-md-4.mb-3.mb-md-0(data-aos="zoom-in")
        .cajon.bgr_2.p-4.h-100
          p La soldadura por ola es usada exclusivamente para los componentes del tipo hueco pasante <em>(thru-hole)</em>. Básicamente, el equipo contiene un recipiente con un calefactor que derrite una cantidad considerable de estaño y lo mantiene en su estado líquido. Dentro de este, hay un equipo de bombeo, que genera literalmente una pequeña ola; también cuenta con un sistema de spray que pulveriza fundente sobre las tarjetas previo a la soldadura.
      .col-12.col-md-4.mb-3.mb-md-0(data-aos="zoom-down")
        figure
          img(src='@/assets/curso/tema1/t1-17.png', alt='Texto que describa la imagen')
      .col-12.col-md-4(data-aos="zoom-in")
        .bgr_4.p-4.h-100
          p También, dentro del equipo, hay un sistema de rieles que mueven constantemente los lotes de tarjetas, las cuales ya tienen previamente insertados y acomodados los componentes. Las tarjetas pasan por la sección donde se les aplica el fundente y, luego, por la ola de estaño, la cual suelda instantáneamente los componentes de una manera muy eficiente; la gravedad se encarga de retirar el exceso de temperatura.
    
    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 7
      span Estructura del equipo de soldadura por ola
    .row.mb-5.justify-content-center.mb-5
      .col-12.col-md-10
        figure
          img(src='@/assets/curso/tema1/t1-18.svg', alt='Texto que describa la imagen')
  

    .bgr_5.p-3.mb-5
      .row  
        .col-12.col-md-1.mb-3.mb-md-0
          figure.d-flex.justify-content-center
            img.img90(src='@/assets/curso/tema1/t1-19.svg', alt='Texto que describa la imagen')
        .col-12.col-md-11
          p.mb-0 En los últimos años, se desarrolló un avance en este tipo de equipos y es la ola selectiva, la cual conserva el mismo principio pero, en vez de ser una ola que baña toda la tarjeta, es un sistema que puede movilizar un pequeño tanque con una ola muy pequeña que va soldando pin por pin. Esto es útil cuando las tarjetas tienen una tecnología combinada entre hueco pasante <em>(thru-hole)</em> y superficie (SMD).
    
    .bgr_3.p-2.mb-5(data-aos="fade-down-right")
      h4.mb-0 d. Máquinas de posicionamiento automático de componentes 
    
    p.mb-5 Las máquinas automatizadas, mejor conocidas como <em>Pick and Place</em>, son máquinas que, mediante el uso de uno de los archivos generados en el diseño de la tarjeta, están en capacidad de posicionar de manera automática los componentes en la tarjeta. 

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 8
      span Típica máquina <em>Pick and Place</em> en funcionamiento

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/t1-20.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        h4 Típica máquina <em>Pick and Place</em> en funcionamiento
        br
        br
        p Estos equipos son usados, esencialmente, cuando hay en su mayoría componentes de superficie que por su tamaño se hace más complejo su posicionamiento.
    
    p.mb-5 La siguiente figura presenta el proceso que realiza este tipo de equipo

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 9
      span Proceso de una máquina de posicionamiento automático
    .row.mb-5.justify-content-center.mb-5(data-aos="flip-left")
      .col-12.col-md-8
        figure
          img(src='@/assets/curso/tema1/t1-21.png', alt='Texto que describa la imagen')
  
    separador

    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Técnicas y sistemas de microscopía óptica y ampliación de imágenes
    
    .row.mb-5
      .col-12.col-md-6.mb-3.mb-md-0(data-aos="fade-right")
        .cajon.bgr_2.p-5.mb-3
          p.mb-0 Antes de realizar el ensamble, es necesario inspeccionar el PCB, en busca de posibles fallas de fabricación o defectos que pueden llegar a afectar su correcto funcionamiento, para ello existen diferentes equipos. Una vez  ensamblada, es necesario realizar nuevamente una revisión minuciosa de la misma.
        .row
          .col-12.col-md-2.d-flex.align-items-center.mb-3.mb-md-0
            figure.d-flex.justify-content-center
              img.img90(src='@/assets/curso/tema1/t1-22.svg', alt='Texto que describa la imagen')
          .col-12.col-md-10 
            span.colr.text-bold Normas internacionales que rigen este tipo de procesos, 
            | como la IPC 610E, 
            span.colr.text-bold especifican los aspectos a tener en cuenta para elegir un equipo de aumento visual adecuado para cada tarea, 
            | tal como se presenta en las siguientes tablas, adaptadas de la IPC-A-610E-2010.
      .col-12.col-md-6(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema1/t1-23.png', alt='Texto que describa la imagen')
    
    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Tabla 1.
      span Normatividad en la ampliación de imágenes
    .row.mb-5.justify-content-center(data-aos="flip-right")
      .col-12.col-md-10
        .tabla-b.bgr_6.mb-5
          .tabla-b__header
            h4.mb-0 Aumento visual para inspección (ancho de pistas)
          table.pst_2
            tr.bgr_7
              th(rowspan="2") Ancho de pistas o diámetro de <em>pads<sup>1</sup></em>
              th(colspan="2").text-center Potencia de aumento visual
            tr
              th.text-center Rango de inspección
              th.text-center Arbitraje máximo
              
            tr
              td.text-center >1.0 mm [0.0394 pulg.]
              td.text-center 1.5X to 3X
              td.text-center 4X
            tr
              td.text-center >0.5 to ≤1.0 mm 
                br
                span [0.0197 a 0.0394 pulg.]
              td.text-center 3X to 7.5X
              td.text-center 10X
            tr
              td.text-center ≥0.25 to ≤0.5 mm 
                br
                span [0.00984 a 0.0197 pulg.]
              td.text-center 7.5X to 10X
              td.text-center 20X
            tr
              td.text-center 0.25 mm [0.00984 in]
              td.text-center 20X
              td.text-center 40X
            tr
              td(colspan="3") Nota 1: una porción de un patrón conductivo usado para hacer la conexión y/o unión de componentes
    
    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Tabla 2.
      span Normatividad en la aplicación del aumento de imágenes
    .row.mb-5.justify-content-center(data-aos="flip-left")
      .col-12.col-md-10
        .tabla-b.bgr_6.mb-5
          .tabla-b__header
            h4.mb-0 Aplicaciones de ayuda de aumento visual
          table.pst_2
            tr
              td.text-center Limpieza (con o sin procesos de limpieza)
              td.text-center No se requiere aumento visual. Ver nota 1
            tr
              td.text-center Limpieza (procesos <em>no-clean</em>)
              td.text-center Nota 1
            tr
              td.text-center Recubrimientos conformal y encapsulados
              td.text-center Notas 1, 2
            tr
              td.text-center Marcados
              td.text-center Nota 2
            tr
              td.text-center Otros (daños a componentes y alambres, etc.)
              td.text-center Nota 1
            tr
              td(colspan="2") Nota 1: la inspección visual puede requerir el uso de un aumento visual; por ejemplo, cuando está presente un <em>fine pitch</em>, o un ensamble de alta densidad, pudiera ser necesaria la ayuda de un aumento visual mayor, para determinar si hay una contaminación que afecte forma, ajuste o función.
            tr  
              td(colspan="2") Nota 2: si se utiliza aumento visual, está limitado a 4X máximo.
    
    .cajon.bgr.mb-5.p-4
      .row
        .col-12.col-md-1.mb-3.mb-md-0
          figure.d-flex.justify-content-center
            img.img90(src=  '@/assets/curso/tema1/t1-24.svg', alt='Texto que describa la imagen')
        .col-12.col-md-11.d-flex.align-items-center
          p.mb-0 Como se puede observar en la anterior tabla, se puede notar que, dependiendo de la tarea y del ancho de las pistas, se establece un aumento visual determinado. La norma establece, sin embargo, que el aumento máximo para tareas como la inspección de la limpieza no puede ser superior a 4X.
    
    separado

    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Funcionalidades y características de accesorios
    
    p.mb-5 Dentro de la tarea de ensamblar una tarjeta, existen muchos accesorios que pueden ser utilizados para facilitar este proceso, lo que se aplica exclusivamente a la tarea de ensamble manual. A continuación, se presentarán algunas herramientas útiles para ello.
    
    .tarjeta.bgr_8.p-4
      SlyderA.bgr_9(tipo="b")
        .row.p-4
          .col-md-5.mb-4.mb-md-0
            h4.mb-5 Pinzas de puntas planas 
            p Estas pinzas tienen como propósito el agarre de piezas relativamente pequeñas. En ensamble electrónico, lo recomendado es que su punta sea completamente lisa.
          .col-md-7
            figure
              img(src='@/assets/curso/tema1/t1-25.png', alt='Texto que describa la imagen')
        .row.p-4
          .col-md-5.mb-4.mb-md-0
            h4.mb-5 Pinzas de precisión 
            p Las pinzas de precisión, tipo <em>Tweezers</em> o pinza de Bruselas, son altamente recomendadas para el ensamble de componentes de superficie. Es indicado, además, que estas tengan un recubrimiento de pintura antiestática.
          .col-md-7
            figure
              img(src='@/assets/curso/tema1/t1-26.png', alt='Texto que describa la imagen')
        .row.p-4
          .col-md-5.mb-4.mb-md-0
            h4.mb-5 Juego de destornilladores 
            p Es conveniente contar con un variado juego de destornilladores, ya que en la tarjeta es necesario ajustar elementos como disipadores de calor o postes, que se ajustan con tornillos y tuercas.
          .col-md-7
            figure
              img(src='@/assets/curso/tema1/t1-27.png', alt='Texto que describa la imagen')
        .row.p-4
          .col-md-5.mb-4.mb-md-0
            h4.mb-5 Cortafríos 
            p Esta herramienta es útil para cortar los pines sobrantes de los componentes o realizar el corte de cables que van sujetos al ensamble.
          .col-md-7
            figure
              img(src='@/assets/curso/tema1/t1-28.png', alt='Texto que describa la imagen')
        .row.p-4
          .col-md-5.mb-4.mb-md-0
            h4.mb-5 Manta estática 
            p Esta cumple la función exclusiva de proteger todos los componentes de daños por descargas de estática generadas por una mala manipulación.
          .col-md-7
            figure
              img(src='@/assets/curso/tema1/t1-29.png', alt='Texto que describa la imagen')
        .row.p-4
          .col-md-5.mb-4.mb-md-0
            h4.mb-5 Manilla antiestática 
            p Cumple la misma función de la manta solo que esta va sujeta a la mano del ensamblador. El uso de una no excluye necesariamente el uso de la otra, toda la protección antiestática es requerida.
          .col-md-7
            figure
              img(src='@/assets/curso/tema1/t1-30.png', alt='Texto que describa la imagen')
        .row.p-4
          .col-md-5.mb-4.mb-md-0
            h4.mb-5 Prensa para placa de circuito impreso 
            p También se les conoce como tercera mano, su función es precisamente brindar al ensamblador un soporte adicional para sostener en la posición adecuada la tarjeta.
          .col-md-7
            figure
              img(src='@/assets/curso/tema1/t1-31.png', alt='Texto que describa la imagen')
    
    separador

    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.4 Métodos de uso, procesos de ensamble, accionamiento y configuración
    
    .row.mb-5
      .col-12.col-md-1.mb-3.mb-md-0
        figure.d-flex.justify-content-center
          img.img90(src='@/assets/curso/tema1/t1-32.svg', alt='Texto que describa la imagen')
      .col-12.col-md-11
        p.mb-0 En el ensamble electrónico, hay muchos factores que demarcan su calidad y el uso adecuado de las herramientas dentro de los procesos. La correcta planeación de la producción, junto con un seguimiento minucioso de los detalles, puede hacer la diferencia entre un ensamble con criterios de aceptabilidad o un ensamble con defectos.
    
    .row.mb-5
      .col-12.col-md-6.mb-3.mb-md-0(data-aos="fade-right")
        .cajon.bgr_2.p-4.mb-3
          p.mb-0 No existe gran literatura acerca de las técnicas más adecuadas, las normas solo nos hablan de cómo debe quedar el resultado final y los criterios para determinar los defectos del ensamble en aspectos como la orientación de los componentes, la limpieza, aspectos eléctricos, entre otros.
        p Vale la pena resaltar que, luego de inspeccionar las tarjetas a ensamblar en busca de defectos, el paso a seguir es realizar una correcta limpieza de la tarjeta, con alcohol isopropílico; después, se procede a hacer el alistamiento de la documentación necesaria para el ensamble. Es necesario tener disponibles los planos esquemáticos y los diagramas de posicionamiento de los componentes, brindados por el diseñador; estos serán la guía para el ensamblador, ya que le brindarán la información requerida para posicionar cada uno de los componentes.
        span.colr.text-bold En procesos industriales, las máquinas de posicionamiento automático, o <em>Pick and Place</em>, se alimentan de los archivos digitales del diseño para realizar esta tarea de forma automática. 
      .col-12.col-md-6(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema1/t1-33.png', alt='Texto que describa la imagen')
    
    .row.mb-5
      .col-12.col-md-6.mb-3.mb-md-0(data-aos="fade-left")
          figure
            img(src='@/assets/curso/tema1/t1-34.png', alt='Texto que describa la imagen')
            figcaption.text-center Nota. Tomada de ImageQuest (s. f .)
      .col-12.col-md-6(data-aos="fade-right")
        .cajon.bgr.p-5.mb-3
          p.mb-0 De manera general, en los procesos industriales, luego de que todos los componentes son posicionados, se procede al proceso de soldadura; la interacción humana allí es mínima y solo se interviene supervisando el correcto funcionamiento de las máquinas y poniendo los carretes con componentes que se requieran para el ensamble. Al final, la inspección de calidad se hace o por el ojo experto de un técnico supervisor o con la ayuda de máquinas de visión artificial que están programadas para ello.
        span En un ensamble manual, se procede, con la ayuda de la documentación mencionada, a posicionar componente por componente y se dispone entonces a su soldadura, de tal manera que componente que se posiciona, componente que se suelda a la placa; esa es la gran diferencia con los procesos industriales automatizados: 
        span.colr.text-bold el posicionamiento de los componentes no es un proceso al azar ni algo que se deba ejecutar de cualquier manera, dados los parámetros que debe cumplir de acuerdo con las normas internacionales, como la IPC-610.
    
    p La secuencia recomendada dependerá del tipo de tarjeta. Si esta solo contiene componentes de hueco pasante <em>(thru-hole)</em> o solamente de montaje superficial <em>(surface mount)</em> se le conoce como tarjeta de tecnología; por el contrario, en caso de que la tarjeta contenga de los dos tipos de componentes, se le conoce como una tarjeta de tecnología mixta.
    p.mb-5 A continuación, se explica cuáles son los pasos a seguir de acuerdo con esta clasificación.

    TabsA.color-acento-contenido.mb-5.bgr_10
      .tarjeta.color-acento-contenido--borde.p-5(titulo="Tarjeta de tecnología de hueco")
        h4 Tarjeta de tecnología de hueco
        p Los pasos para seguir con una tarjeta de una tecnología de hueco pasante son:
        ol.lista-ol
          li 
            span.text-bold a. 
            | Hay que comenzar por hacer el alistamiento de cada componente a ubicar y soldar. Para elementos axiales, como las resistencias, asegúrese de que el doblez de los pines de conexión cumpla con el estándar IPC. Es recomendable que antes de insertarlos en la tarjeta se limpien los pines con un poco de alcohol isopropílico, para retirar cualquier impureza que pueda afectar la soldadura del mismo.

        .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
          h5 Figura 10
          span Doblez recomendado de los elementos de tipo axial
        .row.mb-5.justify-content-center.mb-5
          .col-12.col-md-8
            figure
              img(src='@/assets/curso/tema1/t1-35.svg', alt='Texto que describa la imagen')
        
        ol.lista-ol
          li 
            span.text-bold b. 
            | Ubicar primero los elementos más cortos en el espacio vertical, es decir, entre una resistencia y un condensador, el orden de ensamble sería: primero la resistencia y luego el condensador. 

        .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
          h5 Figura 11
          span Orden de ensamble de acuerdo con su altura
        .row.mb-5.justify-content-center.mb-5
          .col-12.col-md-8
            figure
              img(src='@/assets/curso/tema1/t1-36.svg', alt='Texto que describa la imagen')
      
        ol.lista-ol
          li 
            span.text-bold c. 
            | Asegurar, con la documentación del diseño, la orientación de componentes que tienen polaridad, como diodos y condensadores, con elementos sin polaridad. Se recomienda que las resistencias estén orientadas de tal manera que su código de colores se pueda leer de derecha a izquierda y todas queden en la misma orientación.
        ol.lista-ol
          li 
            span.text-bold d. 
            | Proceder con el proceso de soldadura.

      .tarjeta.color-acento-contenido--borde.p-5(titulo="Tarjeta de tecnología de superficie")
        h4 Tarjeta de tecnología de superficie
        p Los pasos a seguir con una tarjeta de una tecnología de superficie son:
        ol.lista-ol
          li 
            span.text-bold a. 
            | Aplicar la misma regla de tamaño que con los componentes de tipo hueco pasante: primero se ponen los componentes más bajos y luego los más altos.
          li 
            span.text-bold b. 
            | Se sugiere ubicar y soldar primero los componentes con mayor cantidad de pines, es decir, entre un transistor de tres pines y un integrado de 16 pines primero se ensambla el integrado y luego el transistor.

        .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
          h5 Figura 12
          span Orden de ensamble de acuerdo con su cantidad de pines.
        .row.mb-5.justify-content-center.mb-5
          .col-12.col-md-8
            figure
              img(src='@/assets/curso/tema1/t1-37.svg', alt='Texto que describa la imagen')
        
        .bgr_11.p-4
          p.mb-0 Hay que tener especial precaución con la orientación de elementos polarizados, como diodos, y asegurarse muy bien antes de proceder a soldar. Se recomienda que antes de ubicar cada elemento, se aplique una pequeña capa de fundente tipo flux. 

      .tarjeta.color-acento-contenido--borde.p-5(titulo="Tarjeta de tecnología mixta")
        h4 Tarjeta de tecnología mixta
        p En el caso de tener una tarjeta de tecnología mixta, se recomienda lo siguiente:
        ol.lista-ol
          li 
            span.text-bold a. 
            span Primero se ubican y se sueldan los elementos de montaje superficial, siguiendo las recomendaciones dadas anteriormente.
          li 
            span.text-bold b. 
            span Proceda así mismo con los elementos de hueco pasante <em>(thru-hole)</em>, teniendo también en cuenta las recomendaciones.
          li 
            span.text-bold c. 
            span Al soldar los elementos de hueco pasante <em>(thru-hole)</em>, tenga especial precaución en no llegar a calentar por accidente los elementos de superficie, ya que esto podría ocasionar graves daños.




    

      
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    mostrarIndicadorAudio: true,
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
