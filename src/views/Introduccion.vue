<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción 


    p.mb-3 En este componente, se trabajarán instrumentos y métodos para la captura de información geográfica a través de Sistemas de Posicionamiento Global (GPS); el acceso, descarga y procesamiento de información geográfica disponible en la <i>web</i>, la manipulación de <i>software</i> SIG de código abierto y el manejo de información geográfica para toma de decisiones y planificación de actividades en los sistemas forestales y agroecológicos. Para ampliar la información lo invitamos a revisar el siguiente recurso: 
    
    
    .row.justify-content-center.align-items-center.fondo-1.mb-5
      .col-lg-10
        figure.aling.mb-5
          .col-lg-12.mt-5
            .video
              <iframe width="560" height="315" src="https://www.youtube.com/embed/nSldfznwxMg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          
      
    

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
