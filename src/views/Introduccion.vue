<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    figure.mb-3
      img(src='@/assets/curso/introduccion/img1.png', alt='Texto que describa la imagen')
    
    p Dentro del proceso de fabricación de equipos electrónicos está el subproceso de ensamble de las tarjetas electrónicas, el cual implica una serie de elementos muy importantes que influyen de gran manera en la calidad del producto final. 
    p.mb-5 A continuación, se expone un proceso general de ensamble de tarjetas electrónicas.

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
        h5 Figura 1.
        span Proceso de ensamble

    .row.mb-5.justify-content-center(data-aos="zoom-in")
      .col-12.col-md-8
        figure
          img(src='@/assets/curso/introduccion/img2.svg', alt='Texto que describa la imagen')
    
    .row
      .col-12.col-md-7.d-flex.align-items-center(data-aos="fade-right")
        div  
          .cajon.bgr.p-4.mb-3
            .row
              .col-12.col-md-3
                figure
                  img(src='@/assets/curso/introduccion/img3.svg', alt='Texto que describa la imagen')
              .col-12.col-md-9.d-flex.align-items-center
                p.mb-0 El ensamble de tarjetas electrónicas requiere de técnicas adecuadas y de la aplicación de normas de calidad que aseguren que este proceso cumpla con los parámetros solicitados.
          
          span Para la elaboración de este componente, se abordaron varios autores conocidos en 
          span.colr.text-bold ensamble de tarjetas electrónicas, 
          | de quienes se han citado y referenciado conceptos y ejemplos para los fines educativos de esta materia, en el entendido de que el conocimiento es social y, por lo tanto, es para ser usado por quienes necesitan adquirirlo. Se espera que este documento sea útil para todos aquellos, aprendices y lectores en general, que estén interesados en acercarse a asuntos básicos del 
          span.colr.text-bold desarrollo de productos electrónicos.
    
      .col-12.col-md-5(data-aos="fade-left")
        figure
          img(src='@/assets/curso/introduccion/img4.svg', alt='Texto que describa la imagen')
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
