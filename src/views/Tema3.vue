<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Titulo de primer nivel

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/t3-1.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 La temperatura es un factor determinante dentro de todo el proceso de ensamble, ya que establece tanto la calidad del ensamble como la integridad de los componentes que se están soldando. Por tanto, es importante conocer y dominar las características específicas térmicas de cada uno de los elementos que interactúan en el proceso de ensamble.
    
    p A continuación, se abarcarán los efectos del calor, la técnica de reflujo y el perfil ideal de temperatura.

    separador

    
    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.1 Efectos del calor en componentes electrónicos
    
    .row.mb-5
      .col-12.col-md-6
        figure
          img(src='@/assets/curso/tema3/t3-2.png', alt='Texto que describa la imagen')
      .col-12.col-md-6
        .cajon.bgr.p-4.mb-3
          p.mb-0 Todos los componentes electrónicos se ven afectados con los cambios de temperatura. Los fabricantes especifican en sus hojas de datos los límites máximos que pueden soportar los componentes; esto es un insumo para los ensambladores y diseñadores como referencia para saber las capacidades de cada componente.
        p De manera típica, cada componente tiene un par de parámetros que indican las temperaturas máximas que puede aguantar. Como se puede observar en la siguiente imagen, el último ítem indica las recomendaciones del fabricante a la hora de soldar. El “<em>lead temperature</em>” se refiere a la temperatura máxima que puede aguantar por 10 segundos alejado del cuerpo del componente, que en este caso es hasta los 300°C.
    
    figure.mb-5
      img(src='@/assets/curso/tema3/t3-3.svg', alt='Texto que describa la imagen')
    
    .cajon.bgr_16.p-4
      .row
        .col-12.col-md-1
          figure
            img(src='@/assets/curso/tema3/t3-4.svg', alt='Texto que describa la imagen')
        .col-12.col-md-11.d-flex.align-items-center
          p.mb-0 La temperatura puede llegar a afectar de gran manera el desempeño óptimo de un componente electrónico, cambiando las propiedades resistivas de los materiales, lo que afectará  el comportamiento en general del circuito.
    
    separador

    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.2 Técnica de reflujo
    
    .row.mb-5
      .col-12.col-md-1
        figure
          img(src='@/assets/curso/tema3/t3-5.svg', alt='Texto que describa la imagen')
      .col-12.col-md-11
        p.mb-0 Las tarjetas con componentes de montaje superficial usualmente son soldadas con la técnica de reflujo, la cual no es más que derretir la soldadura puesta previamente sobre los <em>pads</em> de la tarjeta y sobre la cual se han posicionado los componentes para que esta fusión de soldadura genere en sí misma las uniones requeridas entre los pines de los componentes y la tarjeta.
    
    .row.mb-5
      .col-12.col-md-6
        figure
          img(src='@/assets/curso/tema3/t3-6.png', alt='Texto que describa la imagen')
      .col-12.col-md-6
        p Lograr que este proceso, llamado en inglés <em>reflow</em>, que se traduce literalmente como “reflujo”, pero en un sentido más simple es la fusión de la pasta de soldadura, sea exitoso (es decir, que genere los puntos adecuados de soldadura con una capa intermetálica idónea) se ha vuelto unos de los principales problemas de la industria, ya que un reflujo exitoso no solo depende de un adecuado perfil. El problema se debe considerar desde el mismo diseño.
        .bgr_5.px-5.py-4
          p.mb-0 Existe, por ejemplo, un fenómeno conocido como “lápida”, en el cual, si no están adecuadamente equilibradas las áreas circundantes de los pad de un elemento de dos pines, como un condensador o una resistencia, al pasar por el horno de reflujo, los condensadores tienden a levantarse y a quedar literalmente como una lápida despegándose de uno de los <em>pads</em>, lo cual obviamente es un defecto grave de la tarjeta .
    
    p Hay otras consideraciones importantes, como el diseño de zonas de cobre que sirven como disipadores de calor y que, a su vez, ayudan a mantener la integridad de ciertos circuitos. En este proceso, llega a influir, incluso, la calidad de la pasta de soldadura usada. 

    .cajon.bgr_2.p-4.mb-3
      p.mb-0 Es importante recalcar que las soldaduras tienen un tiempo de vida útil de dos años. Cuando este tiempo se excede o está por cumplirse, la calidad de los puntos de soldadura obtenidos no es la misma que cuando la soldadura está fresca.
    
    p.mb-5 El proceso completo puede ilustrarse con la siguiente figura, donde se ve la secuencia completa.

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 13.
      span Proceso de reflujo e inspección de calidad
    
    .row.mb-5.justify-content-center(data-aos="zoom-in")
      .col-12.col-md-8
        figure
          img(src='@/assets/curso/tema3/t3-7.svg', alt='Texto que describa la imagen')
    
    separador

    #t_3_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.4 Perfil ideal de temperatura
    
    .row.mb-5
      .col-12.col-md-6
        figure
          img(src='@/assets/curso/tema3/t3-8.png', alt='Texto que describa la imagen')
      .col-12.col-md-6
        .cajon.bgr.p-5.mb-3
          p.mb-0 Tal vez el elemento más crucial y determinante en el proceso de soldadura por horno de reflujo es el perfil idóneo de temperatura, que nos permita obtener los mejores resultados de ensamble soldado. Este perfil no es otra cosa que una función que describe el comportamiento de la temperatura dentro del horno versus el tiempo o la velocidad de la banda que transporta las tarjetas.
        span En general, un perfil de temperatura tiene cuatro partes o zonas. 
        span.colr.text-bold A continuación, a través de un perfil ideal de temperatura de un horno típico de reflujo, se amplía un poco más sobre cada una de ellas.
    
    .row.justify-content-center
      .col-12.col-md-8
        ImagenInfografica.pst_3.color-acento-botones.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema3/t3-9.svg', alt='Texto que describa la imagen')
          .tarjeta.color-acento-botones.p-4(x="15%" y="76%" numero="+")
            p <b>|</b> En la <b>zona de precalentamiento</b> es donde la tarjeta, como su nombre lo indica, empieza un precalentamiento. Allí puede pasar de la temperatura ambiente a aproximadamente 100°C.
            p Esto es un promedio cada perfil, ya que puede variar de acuerdo con la densidad de los componentes, el tipo de soldadura y hasta el diseño.
            p.mb-0 Se recomienda un incremento gradual casi lineal, ya que, de tener una curva logarítmica donde el aumento de la temperatura exceda el tiempo transcurrido, o la velocidad de movimiento de la tarjeta en el horno, los componentes se verán afectados junto con sus características de funcionamiento

          .tarjeta.color-acento-botones.p-4(x="37%" y="76%" numero="+")
            p En la <b>zona de activación</b> es donde literalmente se activa el proceso, ya que el fundente, al calentarse, protege la unión del óxido y los componentes alcanzan un temperatura segura para reducir la tensión superficial. Idealmente, esta parte de la gráfica debería permanecer prácticamente plana, es decir, a una temperatura constante en este periodo de tiempo.
            p.mb-0 En esta zona, puede suceder que, en vez de mantenerse estable la temperatura, esta baje, afectando la activación del flux y, por ende, el calentamiento requerido de los componentes para llegar adecuadamente a la zona de reflow. Esto produce soldaduras frías, que pueden generar grietas en la unión,

          .tarjeta.color-acento-botones.p-4(x="54.5%" y="76%" numero="+")
            p <b>La zona de fundición o de <em>reflow</em></b> es donde la curva alcanza su máximo pico y este no debería exceder ni en temperatura ni en tiempo las recomendaciones de los fabricantes.
            p En este punto es donde se funde la soldadura y la tensión superficial es la adecuada para lograr la unión, y la capa intermetálica se forma.
            p.mb-0 Sin embargo, también en la zona de reflow, una excesiva temperatura podría literalmente generar una carbonización de los puntos de soldadura y, en algunos casos, puede generar el levantamiento de las pistas de la PCB.

          .tarjeta.color-acento-botones.p-4(x="70%" y="76%" numero="+")
            p La <b>zona de enfriamiento</b> es donde la curva debe describir una pendiente igual a la de subida de la zona de reflow, ya que esto garantiza que la soldadura no se cristalice y termine de formar una adecuada capa intermetálica.
            p.mb-0 Asimismo, hay que tener presente que una temperatura que baja demasiado rápido generaría, a parte de soldaduras cristalizadas, un riesgo de fractura en los componentes
    

    

   



        

</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
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
