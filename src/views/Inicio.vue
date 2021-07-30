<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.svg')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Diseño y planos en AutoCAD 2D
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Diseño y planos en AutoCAD 2D
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 22520107
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Total: 
                p.banner-principal__datos__item__texto 48 horas
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Duración: 
                p.banner-principal__datos__item__texto 4 semanas
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual              

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/yAk3O1i0qiY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>                       
                      

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p.mb-0 AutoCAD es un #[i software] que está en la vida laboral de un profesional desde hace más de 30 años y es compatible con muchos formatos editables universales, permitiendo una interfaz de gráficos y un espacio ilimitado de trabajo como la creación de cotas, trazado de líneas y bocetos de cualquier índole. Este #[i software] se encuentra presente en diferentes disciplinas como la Arquitectura, la Ingeniería, el Diseño de interiores y el Diseño gráfico y publicitario por su amplio número de herramientas, lo que convierte a AutoCAD en una necesidad así como lo es aprender un segundo idioma para un profesional en diseño.
      br
      br
      | Este programa de Diseño y planos en AutoCAD 2D está orientado a personas que trabajan en ramas de la Ingeniería, la Logística, la Arquitectura o la Construcción, las Telecomunicaciones, entre otras; con el fin de encontrar un curso que describa el uso del #[i software] de manera universal.
      br
      br
      | Durante la primera parte del curso se inicia con los principios básicos de dibujo técnico, algunas explicaciones de expresión gráfica, los diferentes tipos de diseño que puede elaborar un ingeniero o incluso un diseñador industrial o gráfico apoyado de la definición, aplicación e importancia del CAD en la industria.
      br
      br
      | Adicionalmente, puede contar con la descripción de cada una de las herramientas de dibujo que se encuentran y permiten la elaboración de un ejercicio general, sin especializar el #[i software] en un área del conocimiento y que se puede aplicar a cualquier disciplina para la creación de bocetos de dibujos o planos 2D. 
      br
      br
      | Por último, se describirán las herramientas necesarias para la creación de ventanas gráficas para el apoyo y creación de documentos físicos de ingeniería o arquitectura como los planos y la importancia de formatos, tipos de cotas, directrices, partes de un plano básico e incluso la digitalización de documentos.
      br
      br
      | Es ideal que para el desarrollo del curso revise todo el material de estudio, en el que se describe cada uno de los comandos con ejemplos simples para ayudar a la adquisición del conocimiento por parte del aprendiz.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p.mb-0 En el informe de gestión 2018-2019 realizado por CAMACOL ofertó como su objeto principal de responsabilidad social y ambiental AutoCAD 2D como un #[i software] necesario para incentivar la economía por medio de la infraestructura y la construcción, la cual en el período de 2015-2019 ha licenciado 130.393 viviendas solo en la región comprendida entre Bogotá y Cundinamarca, las cuales necesariamente requieren del desarrollo de planimetrías, modelos y diseños CAD para poder iniciar su proceso constructivo.
      br
      br
      | Se determina la necesidad del manejo de un #[i software] como una herramienta que brinde resultados precisos y confiables sobre aproximaciones realistas para el prototipado de diseños; por esta razón, se considera que el #[i software] AutoCAD 2D ofrece las ventajas para ser competitivo en el medio, dando respuesta a las necesidades de distintos sectores económicos. Los resultados mencionados buscan promover conocimientos y habilidades en los aprendices para elaborar y modificar diseños, vistas y planos mediante el AutoCAD 2D, aplicando los conocimientos adquiridos y demostrando la capacidad de interpretar un plano en su estructura básica, junto con la creación de dibujos precisos a escala según su rama del conocimiento.
      br
      br
      | Según Arellano Núñez (2018) "es de vital importancia mencionar que este #[i software] se utiliza en todos los ámbitos científico, creativo, artístico, y se ha venido transformando en una herramienta básica en las universidades, siendo así que aquellos estudiantes que la conozcan tengan claro el uso y las aplicaciones de AutoCAD, así tendrán grandes oportunidades de crecer y evolucionar en el área de la Ingeniera, por consiguiente se tienen ejemplos donde mediante este #[i software] se han creado grandes diseños ingenieriles" (p. 6).


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Población <br>objetivo

    p.mb-0 El curso de Diseño y planos en AutoCAD 2D está dirigido a jóvenes y adultos en todo el territorio nacional, interesados en adquirir conocimientos y habilidades técnicas para ser aplicadas en procesos de diseño de cualquier elemento en áreas de la Ingeniería, la Logística, la Arquitectura o la Construcción y, las Telecomunicaciones, etc., por medio de la descripción de herramientas y funciones universales del #[i software]. 


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Estrategia metodológica

    p.mb-4 El desarrollo del curso se centra en la construcción de autonomía para garantizar la calidad de la formación por competencias, el aprendizaje por trabajo autónomo y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en la utilización de las herramientas virtuales, las Tecnologías de la Información y la Comunicación (TIC), integradas en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
      br
      br
      | Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
    
    ul.lista-ul--color.mb-4
      li
        i.fas.fa-chevron-right
        | El instructor – Tutor
      li
        i.fas.fa-chevron-right
        | El entorno
      li
        i.fas.fa-chevron-right
        | Las TIC
      li
        i.fas.fa-chevron-right
        | El trabajo colaborativo

    p.mb-0 Las cuales son presentadas al aprendiz por medio de diferentes herramientas como los encuentros sincrónicos y asincrónicos, que permiten la retroalimentación constante por parte del instructor; las guías de aprendizaje que orientan las actividades a desarrollar y los contenidos formativos que se encontrarán dispuestos en un espacio LMS, organizados por unidades temáticas que refuerzan los conocimientos de saber y de proceso que va a desarrollar el aprendiz.


  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
