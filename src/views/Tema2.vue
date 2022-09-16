<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Soldadura en electrónica
    
    span La soldadura tiene un propósito doble. Por un lado, 
    span.colr.text-bold provee la conexión eléctrica efectiva entre los componentes, 
    | al unir cada uno a la tarjeta donde los caminos llevan esta interconexión a los demás elementos. 
    span.colr.text-bold Su segundo propósito es brindar una sujeción mecánica de los componentes.  

    .row.mt-5
      .col-12.col-md-6.mb-3.mb-md-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/tema2/t2-1.svg', alt='Texto que describa la imagen')
      .col-12.col-md-6(data-aos="fade-left")
        .row
          .col-12.col-md-2.mb-3.mb-md-0
            figure.d-flex.justify-content-center
              img.img90(src='@/assets/curso/tema2/t2-2.svg', alt='Texto que describa la imagen')
          .col-12.col-md-10
            p Un ejemplo claro de ello son los conectores de puertos periféricos, como el USB, que, a parte de los pines que hacen la conexión con el puerto, tienen generalmente dos pines más, cuyo propósito principal es el anclaje mecánico del puerto como tal; sin estos pines, la conexión de este elemento quedaría vulnerable a fracturas por desgaste mecánico al conectar y desconectar elementos de este puerto.
        .cajon.bgr_2.p-3
          p.mb-0 La soldadura es el proceso de unir por medio de una fusión dos metales que, en este caso, resultan ser conductores. Esta fusión requiere un proceso térmico de calentamiento, que da como resultado, al fundirse perfectamente los metales, que queden como un solo elemento metálico y conductor.

    separador

    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.1 Técnicas, tipos y propiedades de aleaciones y aceleradores
    
    p.mb-5 Existen básicamente dos tipos de soldaduras para el uso en electrónica: soldadura con plomo y libre de plomo. Están compuestas a base de estaño y se les conoce, a veces, como soldaduras blandas, ya que requieren una temperatura baja, con respecto a otros tipos de soldaduras, para generar esa fusión. En el caso de la electrónica, esta es una capa que mide apenas unos pocos micrómetros, por lo que se le conoce como capa intermetálica.

    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/t2-3.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 La capa intermetálica es una microfusión del estaño y el metal sobre el que se está soldando, que puede ser la pista de cobre o el pin de un componente.

    .row.mb-5
      .col-12.col-md-1.mb-3.mb-md-0
        figure.d-flex.justify-content-center
          img.img90(src='@/assets/curso/tema2/t2-4.svg', alt='Texto que describa la imagen')
      .col-12.col-md-11
        span Una soldadura bien adherida requiere, según Microensamble (2016), de lo siguiente: 
        span.colr.text-bold “su componente primario debe disolver parte del metal de la superficie donde se va a soldar. Este proceso forma una capa compuesta básicamente por una aleación de los dos metales a unir, recibiendo el nombre de intermetálicos”.
    
    .row.mb-5.justify-content-center(data-aos="flip-right")
      .col-12.col-md-10
        .tabla-a.color-acento-contenido.mb-5 
          table
            thead
              tr
                th Soldadura
            tbody
              tr
                td.p-0
                  figure
                    img(src='@/assets/curso/tema2/t2-5.png', alt='Texto que describa la imagen')
              tr
                td.bgr_12.text-center Capas intermetálicas formadas por soldaduras con plomo y libres de plomo. 
                  br
                  span Nota. Tomada de Microensamble (2016). 
    
    .row.mb-5
      .col-12.col-md-6.mb-3.mb-md-0(data-aos="fade-up-right")
        p La soldadura con plomo está compuesta en un 63% de estaño con un contenido de 37% de plomo, también existe una proporción de 60/40 de estaño – plomo. Aunque aún se encuentra comercialmente esta soldadura, está destinada a desaparecer porque el plomo es un elemento altamente tóxico para el hombre y la naturaleza, mientras la soldadura sin plomo  es una soldadura que no tiene ese inconveniente y, por lo tanto, se ha venido posicionando cada vez más en la producción de todo tipo de equipos electrónicos.
        .cajon.bgr_2.p-4.mb-3
          p.mb-0 Según Microensamble (2016): “existe una gran variedad de soldaduras que no contienen plomo, como las aleaciones SnAg3.5 y Sn96.5Ag3Cu0.5 (SAC 305), entre otras”
        span Ahora bien, dejando a un lado el aspecto químico, 
        span.colr.text-bold lo más importante aquí es tener en cuenta la temperatura a la cual se funden estos dos tipos de soldadura, lo cual genera una de las diferencias más trascendentales a la hora de ensamblar o planear una producción. 
      .col-12.col-md-6(data-aos="fade-up-left")
        figure
          img(src='@/assets/curso/tema2/t2-6.png', alt='Texto que describa la imagen')
    
    .bgr_13.p-4.mb-5
      p.mb-0 La soldadura con plomo se funde entre 183 ºC a 225 ºC mientras que la soldadura sin plomo se funde entre 217ºC y 227ºC, como es evidente se requiere de mayor temperatura para lograr fundir soldadura libre de plomo, por esta razón, es necesario trabajar siempre con una estación que nos permita llevar ese control preciso de la misma.

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/t2-7.svg')})`}"
      )
      .bloque-texto-g__texto.p-5
        h4 Símbolo libre de plomo
        br
        br
        p.mb-0 La identificación entre una y otra puede hacerse fácilmente por color o por el símbolo de libre de plomo característico. Generalmente, todas las soldaduras libres de plomo vienen en un empaque de color verde con el símbolo de libre de plomo.
    
    p.mb-5 La presentación de la soldadura también permite una clasificación, ya que existen soldaduras en alambre blando, soldaduras en pasta y lingotes de soldadura. Dependiendo de la manera como se ensamblen las tarjetas se requerirá uno u otro, tal como se aprecia en la siguiente figura.

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 13
      span Uso de los tipos de soldadura
    
    .row.mb-5
      .col-12.col-md-4.mb-3.mb-md-0(data-aos="flip-up")
        figure
          img(src='@/assets/curso/tema2/t2-8.png', alt='Texto que describa la imagen')
        .bgr_14.p-4.text-center
          p.mb-0 El alambre blando es el indicado para el ensamble manual.
      .col-12.col-md-4.mb-3.mb-md-0(data-aos="flip-down")
        figure
          img(src='@/assets/curso/tema2/t2-9.png', alt='Texto que describa la imagen')
        .bgr_14.p-4.text-center
          p.mb-0 La soldadura en pasta es indicada para componentes que se van a soldar con horno de reflujo.
      .col-12.col-md-4(data-aos="flip-up")
        figure
          img(src='@/assets/curso/tema2/t2-10.png', alt='Texto que describa la imagen')
        .bgr_14.p-4.text-center
          p.mb-0 El lingote de soldadura es el insumo que alimenta un equipo de soldadura por ola.

    .row.mb-5
      .col-12.col-md-6.mb-3.mb-md-0
        figure
          img(src='@/assets/curso/tema2/t2-11.png', alt='Texto que describa la imagen')
      .col-12.col-md-6
        p Los fundentes, por su parte, son básicamente substancias que proveen dos funcionalidades importantes a la hora de soldar:
        ol.lista-ol--cuadro.mb-4
          li 
            .lista-ol--cuadro__vineta
              span 1.
            | Proteger la capa intermetálica de la formación del óxido, proveniente de las partículas de agua presentes en el momento de la soldadura.
          li 
            .lista-ol--cuadro__vineta
              span 2.
            | Concentrar la temperatura y distribuirla de manera más uniforme.
        .row.bgr_5.p-4
          .col-12.col-md-2.mb-3.mb-md-0
            figure.d-flex.justify-content-center
              img.img90(src='@/assets/curso/tema2/t2-12.svg', alt='Texto que describa la imagen')
          .col-12.col-md-10
            p Estos fundentes pueden clasificarse básicamente en dos tipos: los que contienen colofonia (un tipo de resina) y los que no la contienen. También, podría decirse que uno es del tipo No <em>clean</em>, es decir, que no requiere limpieza, y el que requiere limpieza por tener colofonia. 
    
    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 14
      span Limpieza de soldadura
    
    .row.mb-5.justify-content-center(data-aos="zoom-in")
      .col-12.col-md-8
        figure
          img(src='@/assets/curso/tema2/t2-13.svg', alt='Texto que describa la imagen')
    
    p.mb-5 Las presentaciones comerciales de los fundentes conocidos comúnmente como <em>FLUX</em> son muy variadas, ya que hay desde aerosoles, geles y líquidos, hasta presentaciones en polvo. La selección de cada presentación depende del tipo de ensamble que se hará, es decir si este es automatizado o manual.

    .row.justify-content-center(data-aos="zoom-out")
      .col-12.col-md-10
        .tabla-a.color-acento-contenido.mb-5 
          table
            thead
              tr
                th Variedad de presentaciones de los fundentes comerciales
            tbody
              tr
                td.p-0.bgr_15
                  figure.p-5
                    img(src='@/assets/curso/tema2/t2-14.png', alt='Texto que describa la imagen')
              tr
                td.bgr_12 En el mercado podemos encontrar presentaciones en jeringa, botes y hasta en lápiz tipo marcador que permite, literalmente, pintar las pistas con la cantidad de <em>flux</em> necesaria.
                  br
                  br
                  p.mb-0.text-center Nota. Tomada de MovilOne (2018).  
    
    separador

    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.2 Métodos de uso y mantenimiento de herramientas
    
    p.mb-5 El procedimiento general de la soldadura es el mismo, pero se debe tener en cuenta, como siempre, si este es automático o si es manual. En general, el procedimiento para soldar dos piezas se expone en el siguiente recurso.

    p.text-bold.mb-5 Procedimiento para soldar piezas con estaño

    .row.mb-5
      .col-12.col-md-7.mb-3.mb-md-0(data-aos="fade-right")
        LineaTiempoD.color-primario
          .row(numero="A" titulo="Limpieza de las superficies")
            .col-md-8.mb-4.mb-md-0
              p Las dos superficies a soldar deben estar limpias y libres de cualquier tipo de impureza, en especial grasas u óxido.
            .col-md-3
              figure.d-flex.justify-content-center
                img.img120(src='@/assets/curso/tema2/t2-16.svg', alt='Texto que describa la imagen')
          .row(numero="B" titulo="Unión de las piezas")
            .col-md-8.mb-4.mb-md-0
              p Ya sea un componente posicionado en la tarjeta o dos cables entorchados, previo a aplicar la soldadura, las piezas deben estar juntas y en contacto mecánico.
            .col-md-3
              figure.d-flex.justify-content-center
                img.img120(src='@/assets/curso/tema2/t2-17.svg', alt='Texto que describa la imagen')
          .row(numero="C" titulo="Aplicación del fundente")
            .col-md-8.mb-4.mb-md-0
              p Este paso, dependiendo del caso, puede ir previamente, ya que el fundente se aplica justo antes de soldar y no puede permanecer por mucho tiempo aplicado, pues puede llegar a corroer los metales. En el caso de las tarjetas de montaje superficial, este se aplica previo al posicionamiento de los componentes.
            .col-md-3
              figure.d-flex.justify-content-center
                img.img120(src='@/assets/curso/tema2/t2-18.svg', alt='Texto que describa la imagen')
          .row(numero="D" titulo="Se aplica temperatura a la unión de las partes")
            .col-md-8.mb-4.mb-md-0
              p Dependiendo del tipo de soldadura aplicada, se ajusta la temperatura del elemento calefactor, ya sea horno o punta de mango soldador, teniendo en cuenta si es soldadura con o sin plomo.
            .col-md-3
              figure.d-flex.justify-content-center
                img.img120(src='@/assets/curso/tema2/t2-19.svg', alt='Texto que describa la imagen')
          .row(numero="E" titulo="Aplicación de la soldadura")
            .col-md-8.mb-4.mb-md-0
              p Se aplica la soldadura formando un puente entre las partes y el elemento calefactor; en el caso de la soldadura manual, con mango soldador o cautín, en los casos industrializados, se aplica por una pequeña ola de estaño fundido.
              P Si la soldadura es hecha en un horno de reflujo, al aplicar el flux o fundente, también se aplica una delgada capa de soldadura, pero en pasta.
            .col-md-3
              figure.d-flex.justify-content-center
                img.img120(src='@/assets/curso/tema2/t2-20.svg', alt='Texto que describa la imagen')
      
      .col-12.col-md-5(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema2/t2-15.png', alt='Texto que describa la imagen')
      
    p.mb-5 Ahora bien, hay algunas consideraciones muy particulares para la soldadura manual que deben ser tenidas en cuenta, si se quiere lograr una soldadura de calidad. Entre ellas, se encuentran las siguientes:

    .tarjeta.bgr_8.p-4
      SlyderA.bgr_9(tipo="b")
        .row.p-4
          .col-md-4.mb-4.mb-md-0 
            p Se recomienda el uso de guantes de nitrilo para evitar contaminarse con el plomo de la soldadura, si es el caso, o para evitar contaminar con el sudor los pines, las pistas y <em>pads</em> de la tarjeta. Este tipo de contaminación afecta de gran manera la soldadura.
          .col-md-8
            figure
              img(src='@/assets/curso/tema2/t2-21.png', alt='Texto que describa la imagen')
        .row.p-4
          .col-md-4.mb-4.mb-md-0
            p Cuando se aplica la soldadura en alambre blando, esta empezará a derretirse inmediatamente y entra en contacto con la temperatura de los elementos a soldar. Se recomienda que este alambre sea movido para que la soldadura se esparza por toda el área. 
            p Erróneamente, se piensa que se debe mover la punta del mango soldador, pero, por el contrario, esta debe permanecer en este proceso firme calentando las dos superficies a unir; si se mueve el soldador, habrá una pequeña pérdida de temperatura que afectará el resultado final.
          .col-md-8
            figure
              img(src='@/assets/curso/tema2/t2-22.png', alt='Texto que describa la imagen')
        .row.p-4
          .col-md-4.mb-4.mb-md-0
            p El tiempo de aplicación del calor y la soldadura es fundamental, ya que muy poco daría como resultado una soldadura fría, que se agrieta fácilmente, y mucho tiempo dará como resultado una capa intermetálica demasiado gruesa, que también puede sufrir grietas fácilmente. Este procedimiento dura unos pocos segundos, dependiendo del tamaño de las piezas a soldar.
          .col-md-8
            figure
              img(src='@/assets/curso/tema2/t2-23.png', alt='Texto que describa la imagen')
        .row.p-4
          .col-md-4.mb-4.mb-md-0
            p En cuanto al mantenimiento de las herramientas, el más importante en la soldadura manual es el de las puntas de los mangos soldadores. Al terminar el trabajo, se recomienda dejar una gruesa capa de estaño sobre estas y dejar que se seque y se enfríe. Si la punta queda demasiado “limpia”, es decir, libre de soldadura, esta tenderá con el tiempo a oxidarse y su vida útil será mucho más corta.
          .col-md-8
            figure
              img(src='@/assets/curso/tema2/t2-24.png', alt='Texto que describa la imagen')
    
    separador

    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.3 Características de soldabilidad
    
    .row.mb-5
      .col-12.col-md-6.mb-3.mb-md-0(data-aos="fade-left")
        p.mb-5 En general el estaño es un material soldable al cobre, bronce y a la chapa de hierro; y aunque es válido tenerlo presente, no es una propiedad relevante,  ya que todos los materiales usados en los ensambles electrónicos están diseñados para asegurar la solubilidad con el estaño. 
        .cajon.bgr_2.p-4
          p Lo que sí se debe tener en cuenta es que esta propiedad puede llegar a perderse por culpa de contaminantes tan comunes como el sudor humano, el polvo y la corrosión generada por la humedad; por lo tanto, los componentes electrónicos y las tarjetas deben estar almacenados por corto tiempo y, en caso de que deban permanecer por largos periodos, se recomienda usar indicadores de humedad y un correcto almacenaje, así como manipulación por parte del ensamblador, quien debe usar siempre guantes de nitrilo para que no se transfieran impurezas a las tarjetas ni a los componentes.
      .col-12.col-md-6(data-aos="fade-right")
        figure
          img(src='@/assets/curso/tema2/t2-25.png', alt='Texto que describa la imagen')
    
    .row
      .col-12.col-md-1.mb-3.mb-md-0
        figure.d-flex.justify-content-center
          img.img90(src='@/assets/curso/tema2/t2-26.svg', alt='Texto que describa la imagen')
      .col-12.col-md-11
        span.colr.text-bold Un consejo muy útil es que, en caso de que los componentes o la tarjeta hayan sufrido contaminación, se deben limpiar con alcohol isopropílico. 
        | También algunos pines de considerable tamaño, como los de las borneras, pueden ser ligeramente raspados con la ayuda de un bisturí, antes de proceder a hacer la soldadura. Este último procedimiento no es recomendado con componentes nuevos y sellados.
    
    separador

    #t_2_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.4 Técnicas de retiro y limpieza de excesos
    
    p.mb-5 Así como el proceso de ubicar los componentes y soldarlos es crucial en el ensamble, el proceso de retiro de excesos de soldadura y la limpieza de impurezas posterior también es de vital importancia, ya que los restos de fundente son extremadamente peligrosos, especialmente de aquellos con mayor capacidad. 

    .row  
      .col-12.col-md-6(data-aos="fade-right")
        figure
          img(src='@/assets/curso/tema2/t2-27.png', alt='Texto que describa la imagen')
      .col-12.col-md-6(data-aos="fade-left")
        .bgr_5.p-4.mb-3
          p.mb-0 Desafortunadamente, los mejores fundentes son extremadamente resinosos (grasosos) y,  al enfriarse, se vuelven conductores, generando resistencias parásitas y cortos dentro de la placa ensamblada.
        p A nivel industrial, se usan lavadoras que utilizan ultrasonido, combinado con alcohol isopropílico, para limpiar las impurezas. Su funcionamiento es muy simple, en realidad. Se trata de un receptáculo metálico que puede vibrar a muy altas frecuencias; dentro de este, se pone una cantidad de alcohol que apenas cubre las tarjetas que son puestas allí; la lavadora, al vibrar, genera ondas dentro del alcohol que disuelven y desprenden las impurezas.
        .row
          .col-12.col-md-3.mb-3.mb-md-0
            figure.d-flex.justify-content-center
              img.img90(src='@/assets/curso/tema2/t2-28.svg', alt='Texto que describa la imagen')
          .col-12.col-md-9
            p Cuando no se cuenta con estos equipos de limpieza, se debe recurrir a técnicas manuales tradicionales. Una de las más reconocidas por los ensambladores es la llamada técnica japonesa, la cual consiste en poner un paño especial para la limpieza de PCB sobre la tarjeta; luego, se rocía alcohol sobre este, de tal manera que se humedezca por completo; luego, con un cepillo antiestático, se frota el paño contra la tarjeta, de tal forma que las impurezas quedan pegadas a este.


    



      

                
                
  
  
    


</template>

<script>
export default {
  name: 'Tema2',
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
