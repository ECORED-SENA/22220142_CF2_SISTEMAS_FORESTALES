<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1  Captura de información geográfica

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6
        p.mb-3  Los sistemas de información geográfica SIG, en un comienzo se enfocan principalmente en el componente geográfico, es decir la ubicación espacial de la entidad territorial por medio de coordenadas en un plano bidimensional; hoy en día con el avance de la tecnología, se incorpora, la información de las características o atributos de cada entidad, por ejemplo cuando se trabaja con sistemas forestales, además  de las coordenadas con las cuales se  puede ubicar un árbol dentro del espacio, los SIG  permiten almacenar información como es el tipo de especie, el estado fitosanitario, y parámetros dendrométricos como alturas, diámetros, entre otros; toda esta información almacenada dentro de una base datos.
      .col-lg-6.mb-5.mb-lg-0
        img(src="@/assets/curso/images/tema1/img_1.jpg", alt="")
   
    p.mb-3 Anteriormente, la información geográfica era suministrada sobre la base de levantamientos topográficos o mediante trabajos fotogramétricos a partir de la restitución de fotografías aéreas o imágenes satelitales; hoy en día, con los avances tecnológicos han surgido los sistemas de posicionamiento global denominados GPS de sus siglas en inglés <i>Global  Positioning System</i> los cuales permiten de una manera más ágil, la captura de la información espacial (puntual, lineal y poligonal) y dependiendo del dispositivo de captura dispuesto, se puede levantar información atributiva para integrar al Sistema de Información Geográfica. 

    Separador 
   
    #t_1_1.titulo-segundo
      h2 1.1  Sistemas de Posicionamiento Global GPS
    
    p.mb-5 Los sistemas de información geográfica SIG, en un comienzo se enfocan principalmente en el componente geográfico, es decir la ubicación espacial de la entidad territorial por medio de coordenadas en un plano bidimensional; hoy en día con el avance de la tecnología, se incorpora la información de las características o atributos de cada entidad, por ejemplo cuando se trabaja con sistemas forestales, además  de las coordenadas con las cuales se  puede ubicar un árbol dentro del espacio, los SIG permiten almacenar información como es el tipo de especie, el estado fitosanitario, y parámetros dendrométricos como alturas, diámetros, entre otros; toda esta información almacenada dentro de una base datos.

    .jumbotron
      .row.mb-5.p-3
        .col-lg-3.mb-lg-0
          img.my-3(src="@/assets/curso/images/tema1/img_2.svg", alt="")
        .col-lg-9
          p.mb-0 Anteriormente, la información geográfica era suministrada sobre la base de levantamientos topográficos o mediante trabajos fotogramétricos a partir de la restitución de fotografías aéreas o imágenes satelitales; hoy en día, con los avances tecnológicos han surgido los sistemas de posicionamiento global denominados GPS de sus siglas en inglés Global  Positioning System; los cuales permiten de una manera más ágil, la captura de la información espacial (puntual, lineal y poligonal), y dependiendo del dispositivo de captura que se disponga, se puede levantar información atributiva para integrarla al Sistema de Información Geográfica.

    p.mb-3 El Sistema de Posicionamiento Global (GPS), como su nombre lo indica, es un sistema que se compone por una red satélites, los cuales continuamente envían información codificada a unos receptores ubicados en la tierra, y por medio de mediciones de tiempos y distancias entre ellos, pueden identificar con precisión la ubicación en la tierra.

    p.mb-5 Todo Sistema de Posicionamiento Global, está conformado por tres segmentos o componentes así:


    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        ImagenInfografica.color-secundario.mb-5
          template(v-slot:imagen)
            figure
              img(src="@/assets/curso/images/tema1/img_3.svg")
          

          .tarjeta.back-info.p-3(x="7%" y="32%" numero="1")
            .h5.mb-2 Segmento Espacial
            p Conformado por el conjunto de satélites o constelaciones que están orbitando la tierra, enviando la información.

          .tarjeta.back-info.p-3(x="92%" y="46%" numero="2")
            .h5.mb-2 Segmento Control
            p Corresponde a estaciones de recepción ubicadas en todo el territorio de la tierra.

          .tarjeta.back-info.p-3(x="59%" y="95%" numero="3")
            .h5.mb-2 Segmento Usuario
            p Formado por los usuarios finales quienes mediante sus receptores GPS, obtienen la información para definir su posición exacta en este globo terrestre.
       
    Separador 
   
    #t_1_2.titulo-segundo
      h2 1.2 Constelaciones satelitales

    p.mb-3 El Sistema GPS, fue originalmente creado por el gobierno de Estados Unidos, principalmente como una estrategia militar, pero con el pasar de los años se ha visto la necesidad de tener información de la tierra para diferentes áreas del conocimiento, es así como, otros países del mundo han desarrollado sus propios sistemas GPS para uso a nivel local o mundial.

    p.mb-5 En el siguiente recurso, se describen los principales sistemas o constelaciones satelitales disponibles en el mundo.

    TabsB.color-acento-contenido.mb-5.mx-0
      .py-4.py-md-5(titulo="GPS" :icono="require('@/assets/curso/images/tema1/ico_1.svg')")
        .row.fondo_2
          .col-lg-3
            img(src="@/assets/curso/images/tema1/ban_1.svg",alt='', style="width:1000px; display:block; margin:2rem -1rem;")
          .col-lg-9.mt-5
            p.aling-1-text <b>Operador:</b> comando Espacial de la Fuerza Área <br> <b>Satélites y órbitas (último diseño, excluyendo reemplazos):</b> 24 en 6 planos a 20.180 km (55° MEO) <br> <b>Cobertura:</b> global <br><b>Servicios:</b><br> navegación <b>Estado:</b> <br> operacional <b>Años en servicio:</b> 1993 - 
      .py-4.py-md-5(titulo="GLONASS" :icono="require('@/assets/curso/images/tema1/ico_2.svg')")
        .row.fondo_3
          .col-lg-3
            img(src="@/assets/curso/images/tema1/ban_2.svg",alt='', style="width:170px; display:block; margin:2rem -1rem;")
          .col-lg-9.mt-5
            p.aling-1-text <b>Operador:</b> Agencia Espacial Federal Rusa <br> <b>Satélites y órbitas (último diseño, excluyendo reemplazos):</b> 24 en 3 planos a 19.130 km (64° 8’ MEO) <br> <b>Cobertura:</b> Global <br> <b>Servicios:</b> Navegación <br> <b>Estado:</b> Operacional <br> <b>Años en servicio:</b> 1995 -
           
      .py-4.py-md-5(titulo="Galilleo" :icono="require('@/assets/curso/images/tema1/ico_3.svg')")
        .row.fondo_4
          .col-lg-3
            img(src="@/assets/curso/images/tema1/ban_3.svg",alt='', style="width:1000px; display:block; margin:2rem 1rem;")
          .col-lg-9.mt-5
            p.aling-4-text  <b>Operador:</b> Agencia de la Unión Europea para la Administración Espacial
             <b>Satélites y órbitas (último diseño, excluyendo reemplazos):</b> 24 en 3 planos a 23.222 km (56° MEO) <br> <b>Cobertura:</b> Global <br> <b>Servicios:</b> Navegación<b>Estado:</b> Operacional <br> <b>Años en servicio:</b> 2019-

      .py-4.py-md-5(titulo="BeiDou" :icono="require('@/assets/curso/images/tema1/ico_4.svg')")
        .row.fondo_5
          .col-lg-3
            img(src="@/assets/curso/images/tema1/ban_4.svg",alt='', style="width:200px; display:block; margin:5rem 3rem;")
          .col-lg-9.mt-5
            p.aling-5-text  <b>Operador:</b> Administración Espacial Nacional China <br><b>Satélites y órbitas (último diseño, excluyendo reemplazos):</b> <br>3 geoestacionarios a 35.786 km (GEO) / 3 en 3 planos a 35.786 km (55° GSO) / 24 en 3 planos a 21,150 km (55° MEO) <br> <b>Cobertura:</b>  Regional - Global <br> <b>Servicios:</b> Navegación <br> <b>Estado:</b> Operacional <br> <b>Años en servicio:</b> 2012- (Asia) / 2018- (a nivel mundial)

      .py-4.py-md-5(titulo="NAVIC" :icono="require('@/assets/curso/images/tema1/ico_5.svg')")
        .row.fondo_6
          .col-lg-3
            img(src="@/assets/curso/images/tema1/ban_5.svg",alt='', style="width:200px; display:block; margin:4rem 3rem;")
          .col-lg-9.mt-5
            p.aling-5-text  <b> Operador:</b> Agencia India de Investigación Espacial <br> <b> Satélites y órbitas (último diseño, excluyendo reemplazos): </b> <br> 3 geoestacionarios a 35.786 km (GEO) / 4 en 2 planos a 250-24.000 km (29 ° GSO) <br> <b> Cobertura: </b> Regional <br> <b> Servicios: </b> Navegación <br> <b> Estado: </b> Operacional <br> <b> Años en servicio: </b> 2018 -
      
      .py-4.py-md-5(titulo="QZSS" :icono="require('@/assets/curso/images/tema1/ico_6.svg')")
        .row.fondo_7
          .col-lg-3
            img(src="@/assets/curso/images/tema1/ban_6.svg",alt='', style="width:200px; display:block; margin:4rem 4rem;")
          .col-lg-9.mt-5
            p.aling-5-text  <b> Operador:</b> JAXA (Agencia Japonesa de Exploración Aeroespacial) <br> <b> Satélites y órbitas (último diseño, excluyendo reemplazos):</b> <br>1 geoestacionario a 35.786 km (GEO) / 3 en 3 planos a 32.600-39.000 (43 ° GSO) <br><b>Cobertura:</b> Regiona <br> <b>Servicios: </b> Navegación <br> <b>Estado:</b> Operacional <br> <b>Años en servicio:</b> 2018-
    
    
    Separador 
   
    #t_1_3.titulo-segundo
      h2 1.3 Equipos y aplicaciones
    
    p.mb-3 Dentro del segmento “Usuario”, existe una variada gama de equipos receptores GPS, de diferentes marcas, especificaciones y precios; cada uno brinda diferentes posibilidades de uso, dependiendo del objetivo del trabajo y del presupuesto con el que se cuenta. 

    p.mb-3 Algunos tipos de receptores disponibles en el mercado son los siguientes:

    SlyderB.mb-5(:datos="datosSlyderl")
    
    .row.align-items-center.fondo_8.mb-5
      .col-12.col-md-8.col-lg-3.col-xl-3
        img(src="@/assets/curso/images/tema1/img_13.svg" alt="AvatarTop", style="width:370px; display:block; margin:-2rem 0;")
      .col-12.col-md-4.col-lg-8.col-xl-8.mb-3
        p.aling A partir del año 2010, con la aparición de los teléfonos inteligentes (<i>smartphones</i>), muchos aparatos traen incorporado un chip GPS, el cual permite la ubicación, navegación y captura de información en campo, proceso que se denomina georreferenciación. 
    
    .row.mb-5 
      p En este orden de ideas, hoy en día se encuentra una gran variedad de aplicaciones para los diferentes sistemas operativos Android y IOS, estas aplicaciones permiten tomar coordenadas, hacer mediciones de geometrías (áreas, distancias) y descargar la información para procesarla en un software SIG estas son algunas de las aplicaciones disponibles. 
    
    .row.justify-content-center
      .col-lg-10
        ImagenInfografica.color-secundario
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/images/tema1/info.svg')

          .tarjeta.p-3.tarjeta--gris(x="61%" y="8%" numero="01")
              .pRelative_1
                .backtoTop_1
                  figure
                    img(src='@/assets/curso/images/tema1/ico_7.svg' alt='' , style="width:120px; display:block; margin:auto 5rem;")

          .tarjeta.p-3.tarjeta--gris(x="80%" y="20%" numero="02")
              .pRelative_1
                .backtoTop_1
                  figure
                    img(src='@/assets/curso/images/tema1/ico_8.svg' alt='' , style="width:100px; display:block; margin:auto 5rem;")
                  
          .tarjeta.p-3.tarjeta--gris(x="91%" y="38%" numero="03")
              .pRelative_1
                .backtoTop_1
                  figure
                    img(src='@/assets/curso/images/tema1/ico_9.svg' alt='' , style="width:130px; display:block; margin:auto 4rem;")

          .tarjeta.p-3.tarjeta--gris(x="91%" y="60%" numero="04")
              .pRelative_1
                .backtoTop_1
                  figure
                    img(src='@/assets/curso/images/tema1/ico_10.svg' alt='' , style="width:100px; display:block; margin:auto 5rem;")
      
          .tarjeta.p-3.tarjeta--gris(x="81%" y="79%" numero="05")
              .pRelative_1
                .backtoTop_1
                  figure
                    img(src='@/assets/curso/images/tema1/ico_11.svg' alt='' , style="width:100px; display:block; margin:auto 5rem;")

          .tarjeta.p-3.tarjeta--gris(x="62%" y="91%" numero="06")
              .pRelative_1
                .backtoTop_1
                  figure
                    img(src='@/assets/curso/images/tema1/ico_12.svg' alt='' , style="width:100px; display:block; margin:auto 5rem;")
                  
          .tarjeta.p-3.tarjeta--gris(x="37%" y="91%" numero="07")
              .pRelative_1
                .backtoTop_1
                  figure
                    img(src='@/assets/curso/images/tema1/ico_13.svg' alt='' , style="width:100px; display:block; margin:auto 5rem;")

          .tarjeta.p-3.tarjeta--gris(x="19%" y="79%" numero="08")
              .pRelative_1
                .backtoTop_1
                  figure
                    img(src='@/assets/curso/images/tema1/ico_14.svg' alt='' , style="width:100px; display:block; margin:auto 5rem;")

          .tarjeta.p-3.tarjeta--gris(x="8%" y="59%" numero="09")
              .pRelative_1
                .backtoTop_1
                  figure
                    img(src='@/assets/curso/images/tema1/ico_15.svg' alt='' , style="width:100px; display:block; margin:auto 5rem;")

          .tarjeta.p-3.tarjeta--gris(x="8%" y="38%" numero="10")
              .pRelative_1
                .backtoTop_1
                  figure
                    img(src='@/assets/curso/images/tema1/ico_16.svg' alt='' , style="width:100px; display:block; margin:auto 5rem;")
                  
          .tarjeta.p-3.tarjeta--gris(x="19%" y="20%" numero="11")
              .pRelative_1
                .backtoTop_1
                  figure
                    img(src='@/assets/curso/images/tema1/ico_17.svg' alt='' , style="width:130px; display:block; margin:auto 5rem;")

          .tarjeta.p-3.tarjeta--gris(x="38%" y="8%" numero="12")
              .pRelative_1
                .backtoTop_1
                  figure
                    img(src='@/assets/curso/images/tema1/ico_18.svg' alt='' , style="width:100px; display:block; margin:auto 5rem;")
    Separador 
   
    #t_1_4.titulo-segundo
      h2 1.4  Captura, descarga y manipulación de la información
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5
        p.mb-5  Cada dispositivo o aplicación receptora GPS maneja su propio sistema y, por ende, su propia manera de capturar la información.
        p.mb-3 En los receptores monofrecuencia, se puede capturar información puntual, lineal y también área o superficies que se denominan polígonos. Con estos receptores es necesario la creación de un proyecto, el cual va a contener las diferentes capas que se requiere levantar. 
        p.mb-3 Los navegadores, los receptores mono frecuencias y doble frecuencia, al igual que algunas de las aplicaciones manejan varios formatos vectoriales para la descarga de la información, los navegadores Garmin, manejan archivos vectoriales en formato GPX; los receptores monofrecuencia manejan datos en formato Shape File y los de doble frecuencia por lo general la información se descarga como texto plano en formato CSV o TXT. 
      .col-lg-7.mb-5.mb-lg-0
        p.my-3 En lo que respecta a los navegadores GARMIN, que son los más populares en el mercado, la captura de información geográfica de entidades se realiza por medio de <i>waypoints</i>, cuando la información es de tipo puntual, por ejemplo, árboles, postes, hidrantes, etc., y por medio de <i>tracks</i> cuando se desarrollan trayectos tipo rutas, vías, y cualquier información lineal. 
        img(src="@/assets/curso/images/tema1/img_7.jpg", alt="")


    p.mb-5 Algunas aplicaciones para <i>smartphones</i>, trabajan con formato KML/KMZ, lenguaje propio de Google; todos estos formatos son compatibles con cualquier software SIG así:

    TabsA.color-acento-contenido.mb-5
    
      .tarjeta.back-tab.p-4(titulo="CSV")
        
        .row 
          .col-lg-4.mb-4
              figure
                img(src='@/assets/curso/images/tema1/img_8.jpg')
          .col-lg-8.mb-4
            h4 CSV
            p.mb-0  Un CSV (<i>Comma-separated values</i>) representa datos en forma de tabla. Sirve para almacenar información alfanumérica con la posibilidad de almacenar las coordenadas y posteriormente poder crear una capa.
             
             
      .tarjeta.back-tab.p-4(titulo="KML / KMZ")
        
        .row 
          .col-lg-4.mb-4
              figure
                img(src='@/assets/curso/images/tema1/img_9.jpg')
          .col-lg-8.mb-4
            h4 KML / KMZ
            p.mb-0 Aunque desarrollado para Google Earth, desde el año 2008 KML es estándar de la OGC (<i>Open Geospatial Consortium</i>) también es muy popular y ha hecho que se ha democratizado mucho. KML significa <i>Keyhole Markup Language</i>, y es un lenguaje de marcado basado en XML para representar datos geográficos en tres dimensiones.
          
        
      
      .tarjeta.back-tab.p-4(titulo="GPX")
         
        .row 
          .col-lg-4.mb-4
                figure
                  img(src='@/assets/curso/images/tema1/img_10.jpg')
          .col-lg-8.mb-4
            h4 GPX
            p.mb-0 GPX o GPS <i>eXchange Format</i> (Formato de Intercambio GPS) es un esquema XML pensado para transferir datos GPS entre aplicaciones. Se puede usar para describir puntos (<i>waypoints</i>), recorridos (<i>tracks</i> ), y rutas (routes).
          

      .tarjeta.back-tab.p-4(titulo="DWG/ DXF")
        
        .row 
          .col-lg-4.mb-4
              figure
                img(src='@/assets/curso/images/tema1/img_11.jpg')
          .col-lg-8.mb-4
            h4 DWG/ DXF
            p.mb-0 El DWG es el formato de CAD (utilizado principalmente por el programa AutoCAD), para facilitar la lectura de este tipo de archivos por parte de otros programas se utilizó un archivo de intercambio: el DXF (<i>Drawing eXchange File</i>)
          

      .tarjeta.back-tab.p-4(titulo="<i>shapefile</i>")
        
        .row 
          .col-lg-4.mb-4
              figure
                img(src='@/assets/curso/images/tema1/img_12.jpg')
          .col-lg-8.mb-4
            h4 <i>Shapefile</i>
            p.mb-0 Es un formato propiedad de ESRI, pero es difícil encontrar un SIG que no lea este sistema de archivos. No es un único archivo, un <i>shapefile</i> se compone de varios archivos que un cliente SIG lee como uno único. El mínimo requerido es de tres: el .shp almacena las entidades geométricas, el .shx almacena el índice de las entidades geométricas y el .dbf es la base de datos, en formato dBASE.
          




  
</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
  data: () => ({
    datosSlyderl: [
      {
        titulo: 'Receptores de navegación',
        texto:
          'Son los tipos de receptores más conocidos, permiten conocer las coordenadas de posición en varios formatos, ofrecen navegación asistida indicando rumbos y direcciones. <br> <br> Precisión: 3-30 metros',
        imagen: require('@/assets/curso/images/tema1/img_4.svg'),
      },
      {
        titulo: 'Receptores de posicionamiento monofrecuencia (L1)',
        texto:
          'La mono frecuencia significa que el receptor recibe <br> solamente la onda portadora conocida como L1. Permiten el levantamiento de vectores (Puntos, líneas y polígonos).<br> <br> Precisión:  1-5 metros, con postproceso < 1 metros formatos, ofrecen navegación asistida indicando rumbos y direcciones. <br> <br> Precisión: 3-30 metros',
        imagen: require('@/assets/curso/images/tema1/img_5.svg'),
      },
      {
        titulo: 'Receptores de posicionamiento de doble frecuencia (RTK)',
        texto:
          'Descripción: Manejan dos frecuencias conocidas como L1 y L2; permiten la disminución de errores sistemáticos, en especial los que <br> se refieren a la dispersión de la señal en la Ionosfera.<br> <br> Precisión: ± 5mm',
        imagen: require('@/assets/curso/images/tema1/img_6.svg'),
        leyendaImagen: 'Leyenda de la imagen',
      },
    ],
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
