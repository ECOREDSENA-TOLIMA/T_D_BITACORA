<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Bitácora
    
    .titulo-segundo.color-acento-contenido
      h2#t_1_1 1.1 Definición
    
    .row.justify-content-center.align-items-center 
      .col-lg-5.col-8.mb-3
        figure
          img(src='@/assets/curso/temas/tema1/1.jpg', alt='Imagen decorativa')
      .col-lg-7.col-12.mb-3
        .cajon.color-primario.p-4(style="background: #CDF5E2")
          p(data-aos="fade-left") La bitácora es una técnica pedagógica y didáctica, que apoya el proceso de enseñanza y aprendizaje, permite registrar de forma cronológica diversas acciones, facilitando la revisión de su contenido y la explicación de procesos que son susceptibles de ser compartidos como experiencias.
        p(data-aos="fade-left") Si se aborda como estrategia pedagógica, permite el aprendizaje significativo, además de posibilitar entre otras cosas, la socialización del conocimiento. También puede ser utilizada como método de valoración de procesos cognitivos que llevan cierto tiempo de aprendizaje.
        p(data-aos="fade-left") Otra ventaja es que puede ser utilizada como una herramienta de evaluación para el instructor, ya que permite conocer el proceso de aprendizaje y su evolución a lo largo del tiempo.

    separador
    .titulo-segundo.color-acento-contenido
      h2#t_1_2 1.2 Elementos que componen la bitácora
    
    .row.justify-content-center 
      .col-lg-8.col-12.mb-3
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span(style="color: #12263F") <b>1</b>
            | <b>Portada:</b> debe tener el nombre del programa, datos del aprendiz, fecha en la que se realizó la bitácora y nombre de quien recibe la bitácora (instructor), entre otros aspectos comunes a una portada.
            li 
            .lista-ol--cuadro__vineta
              span(style="color: #12263F") <b>2</b>
            | <b>Resumen:</b> en esta parte, se debe anexar el índice o la tabla de contenido, además de una lista de tablas y gráficas que se anexen al reporte y que permitan su clarificación.
            li 
            .lista-ol--cuadro__vineta
              span(style="color: #12263F") <b>3</b>
            | <b>Cuerpo de la bitácora:</b>
            .row.justify-content-center   
              .col-lg-11.col-12
                p ● Introducción (breve descripción del proyecto)
                p ● Objetivos y el alcance del proyecto.
                p ● Justificación (las razones por las que hace el proyecto).
                p ● Los antecedentes (donde se exponga el marco teórico del trabajo y casos relacionados a este).
                p ● El desarrollo o una descripción del trabajo.
                p ● Resultados.
                p ● Conclusiones.
            li 
            .lista-ol--cuadro__vineta
              span(style="color: #12263F") <b>4</b>
            | <b>Apéndices o anexos:</b> en este espacio se agregan documentos, gráficas o tablas que estén relacionados al trabajo.
            li 
            .lista-ol--cuadro__vineta
              span(style="color: #12263F") <b>5</b>
            | <b>Referencias:</b> se escribe una lista de los documentos o páginas usados durante el trabajo, se deben citar con normas APA 7a edición.
      .col-lg-4.col-8.mb-3
        figure
          img(src='@/assets/curso/temas/tema1/2.svg', alt='Imagen decorativa')

    separador
    .titulo-segundo.color-acento-contenido
      h2#t_1_3 1.3 Pasos para elaborar una bitácora

    .row.justify-content-center
      .col-lg-8.col-12 
        .row.justify-content-center
          .col-12 
            figure.desktop(data-aos="fade-right")
              img(src='@/assets/curso/temas/tema1/3.svg' alt='Existen 3 pasos para elaborar una bitácora. 1 - Seleccionar la temática de la bitácora. 2 - Realizar la bitácora día por día, semanal o por pasos del proyecto, eso depende de la rigurosidad que se ponga a la hora de contar las experiencias. 3 - Desarrollar cada uno de los aspectos o elementos que componen la bitácora.')
        .row.justify-content-center
          .col-12 
            figure.movil(data-aos="fade-right")
              img(src='@/assets/curso/temas/tema1/4.svg' alt='Existen 3 pasos para elaborar una bitácora. 1 - Seleccionar la temática de la bitácora. 2 - Realizar la bitácora día por día, semanal o por pasos del proyecto, eso depende de la rigurosidad que se ponga a la hora de contar las experiencias. 3 - Desarrollar cada uno de los aspectos o elementos que componen la bitácora.')

    separador
    .titulo-segundo.color-acento-contenido
      h2#t_1_4 1.4 Recomendaciones para desarrollar una bitácora
    
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/5.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        ul.lista-ul
          li 
            i.fas.fa-angle-right
            | Abrir un archivo en <i>word</i>.
          br
          li 
            i.fas.fa-angle-right
            | En la primera página diseñar la portada. 
          br
          li 
            i.fas.fa-angle-right
            | En las siguientes hojas iniciar la tabla de contenido, la cual se debe ir completando a medida que avanza el trabajo a relacionar en la bitácora.
          br
          li 
            i.fas.fa-angle-right
            | Es importante describir los pasos del trabajo en forma cronológica completando el cuerpo de la bitácora.
          br
          li 
            i.fas.fa-angle-right
            | Colocar en la parte final las referencias que se van consultando. 
          br
          li 
            i.fas.fa-angle-right
            | Reseñar los anexos. 
          br
          br
          br
          | 

    separador
    .titulo-segundo.color-acento-contenido
      h2#t_1_5 1.5 Herramientas digitales que se pueden utilizar para la elaboración de la bitácora
    
    ol.lista-ol--cuadro
        li 
          .lista-ol--cuadro__vineta
            span(style="color: #12263F") <b>1</b>
          | <i><b>Word:</b></i> facilita la descripción y recopilación de cada uno de los elementos de la bitácora.
          li 
          .lista-ol--cuadro__vineta
            span(style="color: #12263F") <b>2</b>
          | <i><b>Narrato Journal:</b></i> es un servicio que permite registrar el día reuniendo no solo texto, sino también fotografías, estados de ánimo e incluso movimientos. Es una excelente agenda de recuerdos.
          li 
          .lista-ol--cuadro__vineta
            span(style="color: #12263F") <b>3</b>
          | <i><b>Grid Diary:</b></i> es un diario digital bastante sencillo que tiene como principal función registrar eventos a modo de bitácora, apoyándose en textos e imágenes. Además de este servicio, la App también es una agenda que emite notificaciones e incluye un calendario para poder organizar actividades con meses de anticipación.
          li 
          .lista-ol--cuadro__vineta
            span(style="color: #12263F") <b>4</b>
          | <i><b>Everyday.me:</b></i> la aplicación es un diario inteligente que trabaja con texto, fotos y videos. Entre sus servicios está la posibilidad de administrar un calendario que se basa en etiquetas para organizar las actividades que se almacenan dentro de él.
          

    separador
    .titulo-segundo.color-acento-contenido
      h2#t_1_6 1.6 Ejemplo de una bitácora
    
    .row.justify-content-center
      .col-lg-10.col-12 
        .titulo-sexto.color-acento-contenido
          h5 Figura 1.
          span #[i Bitácora]
        .col-12 
          figure.desktop(data-aos="fade-right")
            img(src='@/assets/curso/temas/tema1/6.svg' alt='Bitacora')
            figcaption Nota. Tomado de GFPI-F-147_formato_bitacora_etapa_productiva. SENA. 
          .col-sm-auto
            a.boton.color-acento-botones.texto-blanco.movil(:href="obtenerLink('/downloads/anexo1.pdf')" target="_blank")
              span Descargar
              i.fas.fa-file-download
        //-.row.justify-content-center
          .col-12 
            figure.movil(data-aos="fade-right")
              img(src='@/assets/curso/temas/tema1/7.svg' alt='La figura 1, indica a que características que definen el DOFA empresarial.')
      
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
