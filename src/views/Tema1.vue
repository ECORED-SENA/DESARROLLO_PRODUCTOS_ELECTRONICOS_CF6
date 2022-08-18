<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Titulo de primer nivel
    
    .row.mb-5
      .col-12.col-md-6.mb-3.mb-md-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/tema1/t1-1.png', alt='Texto que describa la imagen')
      .col-12.col-md-6(data-aos="fade-left")
        .cajon.bgr.p-5.mb-3
          p.mb-0 La planificación es una fase importante de cualquier proceso. En el ensamble de tarjetas, esto influye mayormente en el resultado de la producción general de cualquier equipo electrónico. Una mala planificación traerá muchas consecuencias, desde errores de ensamble hasta pérdidas económicas para una empresa.
        .row
          .col-12.col-md-2.d-flex.align-items-center
            figure
              img(src='@/assets/curso/tema1/t1-2.svg', alt='Texto que describa la imagen')
          .col-12.col-md-10
            p.mb-0 La planificación requiere que se tenga un conocimiento amplio de la naturaleza de la tarjeta a ensamblar, es necesario contar con los planos y la documentación completa del proyecto, tal como se observa en la figura.
    
    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 2.
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
      h5 Figura 3.
      span Equipos destacados
    
    .row.mb-5.justify-content-center(data-aos="zoom-in")
      .col-12.col-md-10
        figure
          img(src='@/assets/curso/tema1/t1-5.svg', alt='Texto que describa la imagen')
    
    p.mb-5 A continuación, se explica cada uno de ellos: 

    .bgr_3.p-2.mb-5(data-aos="fade-down-right")
      h4.mb-0 a. Estación de soldadura
    
    .row.mb-5
      .col-12.col-md-4
        .cajon.bgr.p-4
          .row
            .col-12.col-md-3
              figure
                img(src='@/assets/curso/tema1/t1-6.svg', alt='Texto que describa la imagen')
            .col-12.col-md-9
              p.mb-0 La estación de soldadura es un equipo que reemplazó, con el paso de los años, el uso del típico cautín. Es un equipo encargado básicamente de regular a través de la potencia que entrega al elemento calefactor la temperatura en la punta del mango que es el elemento que tiene contacto final con el estaño y el elemento a soldar.
      .col-12.col-md-4
        figure
          img(src='@/assets/curso/tema1/t1-7.png', alt='Texto que describa la imagen')
      .col-12.col-md-4
        p.mb-0 Esta se caracteriza por ser una caja metálica que cuenta con controles manuales digitales o analógicos para dominar la temperatura de cada mango por separado. Generalmente, cuenta con algún tipo de elemento de visualización, como <em>display</em> o pantalla, que permite observar de forma precisa la temperatura presente en cada mango, y en algunos casos, si hay algún tipo de fallo, también cuenta con puertos conectores donde se ancla el cable que lleva la alimentación al elemento calefactor; en la mayoría de casos, cada mango es también la entrada de señal de algún sensor que detecta la temperatura en la punta del mismo. 
    
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/t1-8.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 En algunas estaciones se cuenta con una función adicional, que consiste en brindar un flujo de aire caliente para soldar (mangos de aire caliente) o desoldar componentes, y en las estaciones más especializadas se cuenta con una función de succión, donde se tiene un mango especial hueco, el cual tiene también un calefactor, que ayuda, mediante una bomba ubicada en la estación, a absorber la soldadura fundida (mango extractor). Esta función es usada para desoldar componentes de hueco pasante <em>(thru-hole)</em>.
    
    p.mb-5 En la siguiente imagen, se pueden observar varios tipos de estaciones de soldadura electrónica.

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 4.
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
              :audio="require('@/assets/componentes/audios/audio-ej.mp3')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
    
    p.mb-5 Las estaciones de soldadura electrónica que más mantenimiento requieren por parte del ensamblador, el técnico/tecnólogo u operador son las que cuentan con mango extractor, ya que estas cuentan con un filtro que evita que los trozos de soldadura extraídos paren dentro de la bomba que genera la succión.

    .cajon.bgr_2.p-3.mb-5(data-aos="flip-down")
      .row.justify-content-center
        .col-12.col-md-1
          figure
            img(src='@/assets/curso/tema1/t1-11.svg', alt='Texto que describa la imagen')
        .col-12.col-md-10.d-flex.align-items-center
          p.mb-0 Es necesario que cada vez que el mango pierde poder de succión, se extraiga este filtro, se desocupe y se limpie, para evitar su avería .

    .bgr_3.p-2.mb-5(data-aos="fade-down-right")
      h4.mb-0 b. Hornos de reflujo
    
    .row.mb-5
      .col-12.col-md-4
        span A nivel industrial, se hace necesario que la producción y el ensamble de las tarjetas sea un proceso más ágil. El ensamble manual es engorroso y toma tiempo, además de requerir de una gran experticia por parte del ensamblador, por esto son muy útiles equipos como el horno de reflujo. 
        span.colr.text-bold Es una máquina de convección, que posee un control sofisticado de temperatura que permite crear el llamado “perfil”, el cual es la curva de temperatura durante el proceso de reflujo de la soldadura.
        .cajon.bgr_2.p-4.mt-3
          p.mb-0 El reflujo es el proceso mediante el cual la soldadura en pasta se derrite mientras se sueldan así los componentes . 
      .col-12.col-md-4
        figure
          img(src='@/assets/curso/tema1/t1-12.png', alt='Texto que describa la imagen')
      .col-12.col-md-4
        .bgr_4.p-3
          p.mb-0 El perfil depende de varios factores asociados: el tamaño del horno, el tipo de la soldadura, el tipo de fundente y, por supuesto, las características del horno como tal. Generalmente, los fabricantes de estos hornos ya tienen caracterizados estos perfiles, los cuales son los recomendados, pero en el proceso se pueden ir ajustando de acuerdo con las necesidades de la parametrización que se hace con el control mismo del horno.
          p.mb-0 Los perfiles son muy similares y tienen como objeto hacer un control preciso de la temperatura, para asegurar una correcta soldadura protegiendo así la integridad de los componentes. La siguiente imagen presenta una estructura básica de un perfil.
 
    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 5.
      span Perfil de temperatura
    .bg_grad-03
      .row.mb-5.justify-content-center.mb-5
        .col-12.col-md-8
          figure
            img(src='@/assets/curso/tema1/t1-13.svg', alt='Texto que describa la imagen')
    
    .row.mb-5
      .col-12.col-md-8
        p Existen hornos de reflujo prácticamente de todos los tipos, pero en general todos funcionan igual y su perfil es parecido al mostrado en la figura anterior. Los hornos de tipo industrial cuentan con una banda que mueve las tarjetas por diferentes zonas de calentamiento, de forma que aseguran la ejecución del perfil y permiten procesar una gran cantidad de tarjetas al mismo tiempo, generando un proceso continuo y en serie.
        #carouselExampleIndicators.carousel.slide.pst_1(data-bs-ride='carousel')
          .carousel-indicators
            button.active(type='button' data-bs-target='#carouselExampleIndicators' data-bs-slide-to='0' aria-current='true' aria-label='Slide 1')
            button(type='button' data-bs-target='#carouselExampleIndicators' data-bs-slide-to='1' aria-label='Slide 2')
          .carousel-inner
            .carousel-item.active
              figure
                img.p-4(src='@/assets/curso/tema1/t1-15.png', alt='Texto que describa la imagen')
                figcaption Nota. Tomada de Das (2021).
            .carousel-item
              figure
                img.p-4(src='@/assets/curso/tema1/t1-16.png', alt='Texto que describa la imagen')
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
