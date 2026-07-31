<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Planeación del registro de información en programas de saneamiento


    .bg-full-width.mb-5
      img(src="@/assets/curso/tema3/img01.png", alt="")
      .row.align-items-center.justify-content-center
        .col-lg-10(data-aos="")
          p.banner-text "Lo que no se registra, no se hace". Esta frase es un lema fundamental en la industria alimentaria. La planeación del registro de información es tan importante como la ejecución misma de las tareas. Los registros son la evidencia objetiva del cumplimiento y la herramienta principal para verificar, rastrear y mejorar los procesos. 

    separador

    .bg-full-width.bg-fondo-1
    
      #t_3_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
        h2 3.1 Concepto de programa de saneamiento: objetivos y estructura


    
      .row.mb-5.justify-content-center.align-items-center
        .col-lg-6.col-md-12.mb-4.mb-lg-0.order-1.order-lg-2
          figure
            img(src="@/assets/curso/tema3/img02.png", data-aos="zoom-in")
        .col-lg-6.order-2.order-lg-1
          p.mb-3 Un Programa de Saneamiento es un documento formal, planificado y sistemático que reúne todas las actividades y procedimientos necesarios para mantener las condiciones higiénicas y sanitarias en un establecimiento de alimentos. Su objetivo principal es prevenir la contaminación de los alimentos, protegiendo así la salud del consumidor.
          p.mb-0 Todo programa de saneamiento debe estar documentado y debe incluir, al menos, cuatro subprogramas o componentes esenciales:
      
      .row.mb-4.justify-content-center
        .col-md-6.col-xl-3.col-lg-6.mb-4.mb-xl-0
          .tarjeta.tarjeta-slide.arriba.bg-color-2(@mouseover="indicadorTarjetaSlide = false")
            .indicador--hover(v-if="indicadorTarjetaSlide")
            .tarjeta-slide__contenedor.h-100
              .tarjeta-slide__contenido.p-3.p-xl-4
                h4.text-center Programa de limpieza y desinfección
                p.mb-0 Establece los procedimientos estandarizados de limpieza y desinfección de instalaciones, equipos y utensilios. Incluye fichas técnicas, concentraciones, frecuencias y responsables de cada actividad. Su eficacia se verifica mediante inspección visual, pruebas de ATP o análisis microbiológicos.
              .tarjeta-slide__img(:style="{'background-image': `url(${require_src('@/assets/curso/tema3/img03.png')})`}")

        .col-md-6.col-xl-3.col-lg-6.mb-4.mb-xl-0
          .tarjeta.tarjeta-slide.arriba.bg-color-2
            .tarjeta-slide__contenedor.h-100
              .tarjeta-slide__contenido.p-3.p-xl-4
                h4.text-center Programa de control de plagas y vectores
                p.mb-0 Comprende las actividades de manejo integrado de plagas (MIP), incluyendo monitoreo, medidas preventivas, controles físicos y químicos realizados por empresas autorizadas y el registro de las intervenciones.
              .tarjeta-slide__img(:style="{'background-image': `url(${require_src('@/assets/curso/tema3/img04.png')})`}")

        .col-md-6.col-xl-3.col-lg-6.mb-4.mb-xl-0
          .tarjeta.tarjeta-slide.arriba.bg-color-2
            .tarjeta-slide__contenedor.h-100
              .tarjeta-slide__contenido.p-3.p-xl-4
                h4.text-center Programa de abastecimiento de agua potable
                p.mb-0 Garantiza que el agua utilizada durante la producción cumpla con los requisitos de potabilidad mediante controles periódicos, mantenimiento de tanques y análisis fisicoquímicos y microbiológicos.
              .tarjeta-slide__img(:style="{'background-image': `url(${require_src('@/assets/curso/tema3/img05.png')})`}")

        .col-md-6.col-xl-3.col-lg-6.mb-4.mb-xl-0
          .tarjeta.tarjeta-slide.arriba.bg-color-2
            .tarjeta-slide__contenedor.h-100
              .tarjeta-slide__contenido.p-3.p-xl-4
                h4.text-center Programa de manejo de residuos sólidos y líquidos
                p.mb-0 Establece los procedimientos para la separación en la fuente, el almacenamiento temporal, la recolección y la disposición final de los residuos generados durante el proceso productivo.
              .tarjeta-slide__img(:style="{'background-image': `url(${require_src('@/assets/curso/tema3/img06.png')})`}")

      separador
    
    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 3.2 Tipos de formatos y registros: características y criterios de diligenciamiento

    .container
      .row.align-items-center.bg-color-9.br-15.p-3.mb-5
        .col-lg-auto.d-none.d-lg-flex
          img(src="@/assets/curso/tema3/img07.svg").mx-auto
        .col-lg
          p.mb-0 Para planear el registro, es necesario diseñar los formatos adecuados. Un formato es el documento prediseñado que será diligenciado. Un registro es el formato ya diligenciado, que contiene datos y evidencia de una actividad realizada.




    .container
      .titulo-con-imagen.mb-5(data-aos="fade-right")
        .titulo-con-imagen__fondo
          img.titulo-con-imagen__imagen(src="@/assets/curso/img-subtitulo.svg")
          h3.titulo-con-imagen__texto Características de un buen formato:



  
    .row.mb-4.justify-content-center.align-items-center
      .col-lg-6.col-md-12.mb-4.mb-lg-0.order-1.order-lg-1
        figure
          img(src="@/assets/curso/tema3/img09.png", data-aos="zoom-in")
      .col-lg-6.order-2.order-lg-2
        p.mb-3 <b>Claro y sencillo:</b> debe ser fácil de entender para quien lo diligencie.
        p.mb-3 <b>Identificable:</b> debe tener un código, nombre y fecha de versión únicos.
        p.mb-3 <b>Estructurado:</b> debe tener espacios definidos para la información requerida (fecha, hora, actividad, responsable, observaciones, etc.).
        p.mb-0 <b>Con campos para verificación:</b> debe permitir dejar constancia de que se realizó una actividad y que se cumplió con el parámetro esperado (ej. Casillas de verificación, espacios para anotar una medición).

    p.mb-5 Criterios para el correcto diligenciamiento de registros:

    .row.justify-content-center.mb-3
      .col-lg-8.mb-0
        AcordionA(tipo="b" clase-tarjeta="tarjeta bg-color-3")
          div(titulo="Uso de lápiz")
            p.mb-3 Un registro diligenciado con lápiz, con información borrosa, manchada y poco clara. Con el tiempo, la información puede perderse o alterarse.
            p.mb-0 <b>Acción correcta:</b> utilizar siempre bolígrafo de tinta azul o negra. La tinta es permanente e indeleble, lo que garantiza que la información perdure en el tiempo y no pueda ser alterada.

          div(titulo="Uso de corrector")
            p.mb-3 Un formato en el que se utilizó corrector líquido (blanquero) para tapar un error. Esto genera desconfianza y puede interpretarse como un intento de ocultar información.
            p.mb-0 <b>Acción correcta:</b> tachar el error con una línea horizontal (dejando visible el dato incorrecto), escribir el dato correcto al lado o encima, y firmar o colocar las iniciales de quien realiza la corrección.

          div(titulo="Registro fuera de tiempo")
            p.mb-3 Un formato diligenciado al final del día, con información genérica como "todo bien" o "todo en orden", sin horarios específicos ni detalles de las actividades realizadas.
            p.mb-0 <b>Acción correcta:</b> diligenciar el registro en el momento exacto en que se realiza la actividad. Ejemplo: "10:30 a. m. - Inicio de pasteurización, temperatura: 72 °C; 11:00 a. m. - Verificación, temperatura: 72 °C."

          div(titulo="Información incompleta")
            p.mb-3 Un formato con espacios en blanco para datos fundamentales, como la fecha, la hora, el nombre del responsable o la firma de verificación.
            p.mb-0 <b>Acción correcta:</b> asegurarse de que todo registro incluya y diligencie los campos obligatorios: fecha completa, hora exacta, nombre completo y legible, firma del responsable y, cuando aplique, visto bueno del supervisor.

      .col-lg-4.col-md-8.mb-0
        img(src="@/assets/curso/tema3/img10.png", data-aos="zoom-in")

    separador
    
    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 3.3 Elaboración de un plan de muestreo: técnicas, tamaños y conservación de muestras

    .row.align-items-center.mb-5
      .col-lg-auto.d-none.d-lg-flex
        img(src="@/assets/curso/tema3/img11.svg").mx-auto
      .col-lg
        p.mb-0 El muestreo es una actividad clave para verificar la calidad y la inocuidad de los insumos, los productos en proceso y los productos terminados. Planear el muestreo implica definir un "plan de muestreo", que es un protocolo que establece:



  
    .row.mb-5.justify-content-center.align-items-center
      .col-lg-6.col-md-10.mb-4.mb-lg-0.order-1.order-lg-1
        figure
          img(src="@/assets/curso/tema3/img12.png", data-aos="zoom-in")
      .col-lg-6.col-md-12.order-2.order-lg-2
        .bg-fondo-5.p-4
          SlyderA(tipo="b").bg-color-white.p-3.tarjeta
            .tarjeta.p-4.h-100
              h4 Objetivo del muestreo
              p.mb-0 ¿Para qué se toma la muestra? (Ej. análisis microbiológico de rutina, verificación de un lote sospechoso, liberación de un producto terminado).

            .tarjeta.p-4.h-100
              h4 Tipo de muestra
              p.mb-0 ¿Se toman muestras al azar, representativas de un lote, o muestras dirigidas a puntos específicos?

            .tarjeta.p-4.h-100
              h4 Tamaño de la muestra
              p.mb-0 ¿Cuántas unidades o qué cantidad de producto se debe tomar para que la muestra sea representativa del lote? Esto puede basarse en normas técnicas (como las NTC) o en el criterio del experto. Por ejemplo, en un lote de 100 cajas de galletas, se podrían muestrear 5 cajas al azar.

            .tarjeta.p-4.h-100
              h4 Técnica de muestreo
              p.mb-0 ¿Cómo se toma la muestra para evitar contaminarla? Se deben usar utensilios y recipientes estériles, y seguir procedimientos asépticos.

            .tarjeta.p-4.h-100
              h4 Conservación y transporte de la muestra
              p.mb-0 ¿Cómo se preserva la muestra hasta que llegue al laboratorio para que sus condiciones no se alteren? Para análisis microbiológicos, las muestras deben refrigerarse (entre 2 °C y 8 °C) y transportarse en neveras portátiles. Para análisis fisicoquímicos, pueden requerir congelación o simplemente temperatura ambiente, dependiendo del análisis.

            .tarjeta.p-4.h-100
              h4 Rotulado de la muestra
              p.mb-0 Toda muestra debe estar claramente identificada con una etiqueta que incluya, como mínimo: nombre del producto, fecha de muestreo, hora, lote (si aplica), tipo de análisis solicitado y nombre de quien tomó la muestra.

            .tarjeta.p-4.h-100
              h4 Registro de la información
              p.mb-0 Se debe diligenciar un formato de "Acta de Toma de Muestras" donde se consigne toda la información anterior.



    .row.mb-5.justify-content-center.align-items-center
      .col-lg-8.col-md-12.mb-0.mb-lg-0
        .titulo-sexto.color-acento-contenido.mb-3
          h5 
            b Tabla 2.
          span Ejemplo de plan de muestreo para la recepción de leche cruda
        .tabla-a.color-acento-contenido.tb-custom.mb-0
          table
            caption <span style="font-weight: normal">Nota. SENA, (2026).</span>
            thead
              tr
                th Variable
                th Especificación
            tbody
              tr
                td Objetivo
                td Verificar la calidad microbiológica y fisicoquímica de la leche cruda al ingreso a planta.
              tr
                td Tipo de muestra
                td Muestra compuesta representativa del carro tanque.
              tr
                td Tamaño de la muestra
                td 1 litro de leche, tomado de diferentes puntos del tanque después de la agitación.
              tr
                td Técnica de muestreo
                td Usar un muestreador de acero inoxidable previamente esterilizado. Verter la leche en un frasco de vidrio estéril de boca ancha.
              tr
                td Conservación
                td Refrigerar inmediatamente a 4 °C en una nevera portátil con geles refrigerantes.
              tr
                td Rotulado
                td Etiqueta con: "leche cruda", fecha, hora, proveedor, placa del vehículo, "análisis: recuento de mesófilos, grasa, proteína", "tomado por: [nombre]"

    separador
    
    #t_3_4.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 3.4 Registro en el programa de limpieza y desinfección

    .row.align-items-center.mb-5
      .col-lg-auto.d-none.d-lg-flex
        img(src="@/assets/curso/tema3/img14.svg").mx-auto
      .col-lg
        p.mb-0 Este programa debe contar con registros que permitan hacer seguimiento a cada una de las actividades. Planear estos registros implica diseñar formatos para:

    .row.justify-content-center.mb-5
      .col-xl-4.col-lg-6.col-md-12.col-12.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left").tarjeta
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/tema3/img15.png", alt="Registro diario de limpieza")
          .crd_hover_txt--body
            h4.mb-3.text-center Registro diario de limpieza y desinfección
            p.mb-0 Un formato en el que, por cada área o equipo, el operario anote la fecha, la hora, la actividad realizada (ej. "limpieza de mesón de acero inoxidable"), los productos utilizados (nombre y concentración) y su firma como constancia.

      .col-xl-4.col-lg-6.col-md-12.col-12.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left").tarjeta
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/tema3/img16.png", alt="Preparación de soluciones desinfectantes")
          .crd_hover_txt--body.pd-1-3
            h4.mb-3.text-center Registro de preparación de soluciones desinfectantes
            p.mb-0 Un formato para llevar el control de la preparación de las soluciones, verificando que se respeten las concentraciones indicadas (ej. "para preparar 10 litros de solución de hipoclorito a 200 ppm, se agregaron X ml de hipoclorito al 5 %").

      .col-xl-4.col-lg-6.col-md-12.col-12.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left").tarjeta
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/tema3/img17.png", alt="Verificación de limpieza y desinfección")
          .crd_hover_txt--body.pd-1-3
            h4.mb-3.text-center Registro de verificación de la limpieza y desinfección
            p.mb-0 Un formato que puede ser diligenciado por un supervisor, mediante la toma de muestras con hisopos en superficies para verificar la eficacia de la limpieza (pruebas de ATP o recuento microbiológico) o simplemente mediante inspección visual.

    separador
    
    #t_3_5.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 3.5 Registro en el programa de control de plagas y vectores

    p.mb-5 La planeación de registros para este programa es vital para demostrar que se está llevando a cabo un control efectivo. Los registros típicos incluyen:


    .row.mb-5.justify-content-center.align-items-center
      .col-lg-12.col-md-12.mb-0.mb-lg-0
        .titulo-sexto.color-acento-contenido.mb-3
          h5 
            b Tabla 3.
          span Ejemplo de formato de inspección interna de plagas
        .tabla-a.color-acento-contenido.tb-custom.mb-0
          table
            caption <span style="font-weight: normal">Nota. SENA, (2026).</span>
            thead
              tr
                th Área
                th Fecha
                th Inspeccionado por
                th Evidencia de plagas (Sí/No)
                th Tipo de plaga / Hallazgo
                th Condiciones de riesgo
                th Acción tomada / Observación
            tbody
              tr
                td Bodega de secos
                td 15/03/2026
                td Juan Pérez
                td Sí
                td Roedores
                td Heces pequeñas en esquina, cerca de estiba de harina.
                td Se reportó a la empresa de control de plagas para revisión de trampas. Se limpió el área.
              tr
                td Área de producción
                td 15/03/2026
                td Juan Pérez
                td No
                td -
                td Rejilla de piso levantada.
                td Se solicitó a mantenimiento su reparación para evitar el ingreso de roedores.

    separador
    
    #t_3_6.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 3.6 Registro en el programa de abastecimiento de agua potable

    
    .row.align-items-center.mb-5
      .col-lg-auto.d-none.d-lg-flex
        img(src="@/assets/curso/tema3/img18.svg").mx-auto
      .col-lg
        p.mb-0 El agua es un ingrediente fundamental y un medio de limpieza esencial. Los registros de este programa deben demostrar que el agua utilizada es potable y apta para el uso previsto. Se deben planear formatos para:



    .row.justify-content-center.mb-5
      .col-lg-8
        AcordionA(tipo="b" clase-tarjeta="tarjeta bg-color-3")
          div(titulo="Registro de cloro residual")
            p.mb-0 En plantas con tanques de almacenamiento propios, se debe medir y registrar diariamente el nivel de cloro residual libre en el agua al inicio de la jornada y, preferiblemente, en varios puntos de la planta. El valor debe estar dentro del rango establecido por la norma (generalmente entre 0,3 y 2,0 ppm).

          div(titulo="Registro de mantenimiento de tanques de agua")
            p.mb-0 Se debe llevar un control de las actividades de limpieza y desinfección periódicas de los tanques de almacenamiento (al menos cada seis meses), registrando la fecha, el procedimiento realizado, los productos utilizados y el responsable.

          div(titulo="Registro de resultados de análisis microbiológicos y fisicoquímicos")
            p.mb-0 La norma exige realizar análisis periódicos del agua para confirmar su potabilidad. Los resultados de estos análisis, realizados por un laboratorio acreditado, deben archivarse y registrarse para su control y seguimiento.

      .col-lg-4.col-md-8
        img(src="@/assets/curso/tema3/img19.png", data-aos="zoom-in")

    separador
    
    #t_3_7.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 3.7 Registro en el programa de manejo de residuos sólidos y líquidos

    .row.align-items-center.mb-5
      .col-lg-auto.d-none.d-lg-flex
        img(src="@/assets/curso/tema3/img20.svg").mx-auto
      .col-lg
        p.mb-0 Un manejo inadecuado de residuos atrae plagas y contamina el ambiente. Los registros ayudan a controlar este aspecto. Se deben planear formatos para:

    .row.justify-content-center.mb-5
      .col-lg-6.col-md-12.mb-4.mb-lg-0
        .bg-color-2.p-4.h-100.br-15
          .row.align-items-center.mb-0
            .col-12.col-lg-auto.mb-3.mb-lg-0
              img(src="@/assets/curso/tema3/img21.svg", style="max-width: 150px;").mx-auto
            .col-lg
              h4 Registro de generación y disposición de residuos: 
              p.mb-0 Un formato sencillo donde se lleve un control diario o semanal de la cantidad de residuos generados (orgánicos, reciclables, peligrosos) y se registre su disposición final (ej. "entregado al servicio de recolección municipal", "entregado a gestor externo autorizado para aceite usado").

      .col-lg-6.col-md-12.mb-4.mb-lg-0
        .bg-color-2.p-4.h-100.br-15
          .row.align-items-center.mb-0
            .col-12.col-lg-auto.mb-3.mb-lg-0
              img(src="@/assets/curso/tema3/img22.svg", style="max-width: 150px;").mx-auto
            .col-lg
              h4 Registro de limpieza de áreas de almacenamiento de residuos:
              p.mb-0 Se debe registrar la limpieza y desinfección periódica de los contenedores y del cuarto de basuras para evitar malos olores y proliferación de plagas.












    //- .bg-full-width.bg-fondo-1

    //-   .bloque-texto-g.bloque-texto-g--inverso.bg-color-31.p-3.p-sm-4.p-md-5.mb-5
    //-     //- .bloque-texto-g__img(
    //-     //-   :style="{'background-image': `url(${require('@/assets/curso/tema3/img01.png')})`}"
    //-     //- )
    //-     .bloque-texto-g__texto.p-4
    //-       p.mb-0 El cargue y descargue de mercancías corresponde al conjunto de actividades destinadas a movilizar los productos entre los diferentes medios de transporte, zonas de almacenamiento y puntos de distribución. Estas operaciones requieren la aplicación de procedimientos técnicos, normas de seguridad y buenas prácticas de manipulación para garantizar la integridad de las mercancías, la seguridad del personal y la eficiencia de la operación logística.


    //-   separador
      
    //-   #t_3_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
    //-     h2 3.1 Concepto

    //-   .row.mb-4.justify-content-center.align-items-center
    //-     .col-lg-3.col-md-8.mb-4.mb-lg-0
    //-       figure
    //-         //- img(src="@/assets/curso/tema3/img02.png", data-aos="zoom-in")
    //-     .col-lg-9
    //-       p.mb-5(data-aos="fade-right") El cargue y descargue de mercancías consiste en las actividades de ingreso, movilización y retiro de productos desde o hacia vehículos, bodegas, centros de distribución o puntos de transferencia, utilizando técnicas y equipos apropiados para evitar daños a la carga y riesgos durante la operación. Estas actividades representan una etapa crítica dentro de la cadena logística, ya que influyen directamente en los tiempos de operación, el control de inventarios y el cumplimiento de las entregas.
          
    //-       .cita-decorada.mb-0
    //-         blockquote.cita-decorada__caja.cita-decorada__caja--fondo-4.p-3.bg-color-2.br-15
    //-           .row.justify-content-center.align-items-center
    //-             .col-12.col-lg-3.mb-3.mb-lg-0
    //-               //- img(src="@/assets/curso/tema1/img04.svg", class="img-fluid cita-decorada__imagen-flotante-3")
    //-             .col-12.col-lg-9.cita-decorada__texto.mb-4.mb-lg-0.p-4
    //-               .d-flex.align-items-start
    //-                 i.fas.fa-circle-check.icon-check-custom.me-2.mt-1.txt-dark
    //-                 p.mb-0 <b>Ejemplo:</b> durante la recepción de un vehículo de transporte, el personal descarga las mercancías verificando cantidades, estado físico y documentación correspondiente.


    //- separador
    
    //- #t_3_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
    //-   h2 3.2 Zonas de cargue y descargue

    //- p.mb-3 Las zonas de cargue y descargue son espacios destinados exclusivamente para realizar las operaciones de recepción y despacho de mercancías de forma segura, organizada y eficiente. Estas áreas deben cumplir condiciones que faciliten la movilización de la carga y reduzcan riesgos para las personas y los productos. 

    //- p.mb-5 Entre sus principales características se encuentran:


    //- .row.mb-5.justify-content-center.align-items-center
    //-   .col-lg-4.mb-4.mb-lg-0.col-md-8.order-2.order-lg-2
    //-     figure
    //-       //- img(src="@/assets/curso/tema3/img03.png", data-aos="zoom-in")
    //-   .col-lg-8.order-1.order-lg-1.col-md-12.mb-4.mb-lg-0
    //-     SlyderF(columnas="col-lg-12 col-xl-6 col-md-12 col-sm-12 p-3")
    //-       .tarjeta.bg-color-8.br-15.shadow-sm.p-4.h-100
    //-         .bg-color-c1.p-2.mb-3
    //-           h4.text-center.mb-0 Señalización adecuada
    //-         p.text-center Incorporar señales horizontales y verticales que orientan la circulación de vehículos, equipos y peatones; delimitan las áreas de operación y promueven el cumplimiento de las normas de seguridad durante las actividades de cargue y descargue.
    //-       .tarjeta.bg-color-8.br-15.shadow-sm.p-4.h-100
    //-         .bg-color-c1.p-2.mb-3
    //-           h4.text-center.mb-0 Espacio suficiente para la maniobra de vehículos
    //-         p.text-center Disponer de áreas amplias que facilitan el ingreso, estacionamiento, giro y salida de vehículos de carga, permitiendo realizar las operaciones logísticas de manera segura, eficiente y sin afectar la circulación interna.
    //-       .tarjeta.bg-color-8.br-15.shadow-sm.p-4.h-100
    //-         .bg-color-c1.p-2.mb-3
    //-           h4.text-center.mb-0 Iluminación apropiada
    //-         p.text-center Contar con un sistema de iluminación suficiente y uniforme que favorece la visibilidad de personas, vehículos y mercancías, permitiendo desarrollar las operaciones con seguridad tanto en horario diurno como nocturno.
    //-       .tarjeta.bg-color-8.br-15.shadow-sm.p-4.h-100
    //-         .bg-color-c1.p-2.mb-3
    //-           h4.text-center.mb-0 Pisos en buen estado
    //-         p.text-center Presentar superficies firmes, niveladas y resistentes que soportan el tránsito constante de vehículos y equipos de manipulación, reduciendo el riesgo de accidentes y facilitando el desplazamiento seguro de las mercancías.
    //-       .tarjeta.bg-color-8.br-15.shadow-sm.p-4.h-100
    //-         .bg-color-c1.p-2.mb-3
    //-           h4.text-center.mb-0 Acceso para equipos de manipulación
    //-         p.text-center Facilita la circulación de montacargas, transpaletas y demás equipos utilizados para movilizar mercancías, mediante accesos adecuados que optimizan las operaciones y disminuyen los tiempos de cargue y descargue.
    //-       .tarjeta.bg-color-8.br-15.shadow-sm.p-4.h-100
    //-         .bg-color-c1.p-2.mb-3
    //-           h4.text-center.mb-0 Condiciones de seguridad industrial
    //-         p.text-center Implementa medidas como uso de elementos de protección personal, demarcación de áreas, control del tránsito y cumplimiento de protocolos que protegen a los trabajadores, las mercancías y los equipos durante la operación.
    
    
    //- .row.mb-3.justify-content-center.align-items-center
    //-   .col-lg-8
    //-     .cajon.bg-color-c1.p-4.mb-0
    //-       p.mb-0 Una correcta organización de estas zonas mejora el flujo de las operaciones logísticas.



    //- separador
    
    //- #t_3_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
    //-   h2 3.3 Puntos de transferencia


    
    //- .row.mb-4.justify-content-center.align-items-center
    //-   .col-lg-4.col-md-12.order-1.order-lg-1.mb-4.mb-lg-0
    //-     .row.align-items-center
    //-       .col-lg-12.mb-2.d-none.d-lg-block
    //-         //- img(src="@/assets/curso/tema3/img04.svg", style="max-width: 90px")
    //-       .col-lg
    //-         p.mb-2 Los puntos de transferencia corresponden a los lugares donde las mercancías son trasladadas de un medio de transporte a otro o de una unidad logística a otra, sin que necesariamente permanezcan almacenadas por largos periodos. Estos puntos permiten optimizar la distribución de mercancías y facilitar la continuidad de la cadena logística.
    //-         p.mb-0 Entre sus principales funciones se destacan:

    //-   .col-lg-8.order-2.order-lg-2.col-md-12.mb-0
    //-     .bg-fondo-5.p-4
    //-       SlyderA(tipo="b").bg-color-white.p-4.tarjeta
    //-         .tarjeta.p-4.h-100
    //-           h4 Consolidación de mercancías
    //-           p.mb-0 Agrupa mercancías de diferentes pedidos o remitentes en una sola unidad de carga, optimizando el espacio disponible, reduciendo costos de transporte y facilitando una distribución más eficiente durante las operaciones logísticas.

    //-         .tarjeta.p-4.h-100
    //-           h4 Clasificación de productos
    //-           p.mb-0 Organiza las mercancías según criterios como tipo, destino, peso, dimensiones o condiciones de manejo, facilitando su identificación, manipulación y distribución durante los procesos de almacenamiento y transporte.

    //-         .tarjeta.p-4.h-100
    //-           h4 Cambio de medio de transporte
    //-           p.mb-0 Traslada la mercancía de un vehículo a otro para dar continuidad a la operación logística, garantizando la conservación de los productos y el cumplimiento de la ruta establecida.

    //-         .tarjeta.p-4.h-100
    //-           h4 Redistribución de carga
    //-           p.mb-0 Reorganiza la ubicación de las mercancías dentro del vehículo o entre diferentes unidades de transporte para mejorar la estabilidad, aprovechar la capacidad disponible y facilitar las operaciones de entrega.

    //-         .tarjeta.p-4.h-100
    //-           h4 Control documental
    //-           p.mb-0 Verifica que la mercancía esté respaldada por los documentos requeridos, asegurando la correspondencia entre la carga transportada y la información registrada para garantizar la trazabilidad de la operación logística.

    //- p.mb-5 El adecuado funcionamiento de los puntos de transferencia contribuye a disminuir tiempos de entrega y mejorar la eficiencia operativa. 

    //- .row.justify-content-center.mb-3
    //-   .col-12.col-lg-8.mb-0.col-md-12
    //-     .cita-decorada
    //-       blockquote.cita-decorada__caja.cita-decorada__caja--fondo-4.p-3.bg-color-2.br-15
    //-         .row.justify-content-center.align-items-center
    //-           .col-12.col-lg-3.mb-3.mb-lg-0
    //-             //- img(src="@/assets/curso/tema1/img04.svg", class="img-fluid cita-decorada__imagen-flotante-3")
    //-           .col-12.col-lg-9.cita-decorada__texto.mb-4.mb-lg-0.p-4
    //-             .d-flex.align-items-start
    //-               i.fas.fa-circle-check.icon-check-custom.me-2.mt-1.txt-dark
    //-               p.mb-0 <b>Ejemplo:</b> un operador logístico recibe mercancías provenientes de diferentes proveedores y las redistribuye hacia varias rutas de entrega desde un centro de transferencia.


    //- separador
    
    //- #t_3_4.titulo-segundo.color-acento-contenido(data-aos="flip-up")
    //-   h2 3.4 Técnicas de cargue y descargue 

    //- p.mb-3 Son los procedimientos utilizados para movilizar mercancías de forma segura, ordenada y eficiente durante las operaciones logísticas; preservando sus características físicas y evitando accidentes laborales. 
    //- p.mb-5 Entre las principales técnicas utilizadas se encuentran:

    //- TabsC.color-primario(data-aos="zoom-in").mb-5
    //-   .p-3.p-md-4(titulo="Manipulación manual segura")
    //-     .row.justify-content-center.align-items-center
    //-       .col-lg-8.mb-4.mb-lg-0.order-1.order-lg-2
    //-         p Usar posturas correctas para levantar y mover cargas livianas, evitando lesiones.
    //-         .d-flex.align-items-start
    //-           i.fas.fa-circle-check.icon-check-custom.me-2.mt-1.txt-dark
    //-           p.mb-0 <b>Ejemplos:</b> Levantando una caja flexionando las rodillas y manteniendo la espalda recta.
    //-       .col-lg-4.col-md-8.mb-0.mb-lg-0.order-2.order-lg-1
    //-         figure
    //-           //- img(src='@/assets/curso/tema3/img06.png', alt='')

    //-   .p-3.p-md-4(titulo="Utilizar equipos de manipulación.")
    //-     .row.justify-content-center.align-items-center
    //-       .col-lg-8.mb-4.mb-lg-0.order-1.order-lg-2
    //-         p Emplear equipos como montacargas o transpaletas para mover cargas pesadas o voluminosas.
    //-         .d-flex.align-items-start
    //-           i.fas.fa-circle-check.icon-check-custom.me-2.mt-1.txt-dark
    //-           p.mb-0 <b>Ejemplos:</b> Transportar un pallet con un montacargas desde el muelle hasta la zona de almacenamiento.
    //-       .col-lg-4.col-md-8.mb-0.mb-lg-0.order-2.order-lg-1
    //-         figure
    //-           //- img(src='@/assets/curso/tema3/img07.png', alt='')

    //-   .p-3.p-md-4(titulo="Distribuir la carga equitativamente.")
    //-     .row.justify-content-center.align-items-center
    //-       .col-lg-8.mb-4.mb-lg-0.order-1.order-lg-2
    //-         p Colocar la mercancía de forma uniforme para mantener la estabilidad durante el transporte.
    //-         .d-flex.align-items-start
    //-           i.fas.fa-circle-check.icon-check-custom.me-2.mt-1.txt-dark
    //-           p.mb-0 <b>Ejemplos:</b> Ubicar los productos de mayor peso en la parte inferior y distribuirlos de forma uniforme.
    //-       .col-lg-4.col-md-8.mb-0.mb-lg-0.order-2.order-lg-1
    //-         figure
    //-           //- img(src='@/assets/curso/tema3/img08.png', alt='')

    //-   .p-3.p-md-4(titulo="Apilar adecuadamente.")
    //-     .row.justify-content-center.align-items-center
    //-       .col-lg-8.mb-4.mb-lg-0.order-1.order-lg-2
    //-         p Apilar las mercancías según su resistencia y tamaño para evitar daños o caídas.
    //-         .d-flex.align-items-start
    //-           i.fas.fa-circle-check.icon-check-custom.me-2.mt-1.txt-dark
    //-           p.mb-0 <b>Ejemplos:</b> Apilar cajas resistentes en la base y las más livianas en la parte superior.
    //-       .col-lg-4.col-md-8.mb-0.mb-lg-0.order-2.order-lg-1
    //-         figure
    //-           //- img(src='@/assets/curso/tema3/img09.png', alt='')

    //-   .p-3.p-md-4(titulo="Asegurar la carga.")
    //-     .row.justify-content-center.align-items-center
    //-       .col-lg-8.mb-4.mb-lg-0.order-1.order-lg-2
    //-         p Fijar la mercancía con elementos de sujeción para evitar movimientos durante el transporte.
    //-         .d-flex.align-items-start
    //-           i.fas.fa-circle-check.icon-check-custom.me-2.mt-1.txt-dark
    //-           p.mb-0 <b>Ejemplos:</b> Fijar un pallet con película stretch antes de cargarlo al vehículo.
    //-       .col-lg-4.col-md-8.mb-0.mb-lg-0.order-2.order-lg-1
    //-         figure
    //-           //- img(src='@/assets/curso/tema3/img10.png', alt='')

    //-   .p-3.p-md-4(titulo="Verificar durante la operación.")
    //-     .row.justify-content-center.align-items-center
    //-       .col-lg-8.mb-4.mb-lg-0.order-1.order-lg-2
    //-         p Revisar el estado de la mercancía, los equipos y las condiciones de seguridad continuamente.
    //-         .d-flex.align-items-start
    //-           i.fas.fa-circle-check.icon-check-custom.me-2.mt-1.txt-dark
    //-           p.mb-0 <b>Ejemplos:</b> Revisar que los pallets no presenten daños antes de iniciar el descargue.
    //-       .col-lg-4.col-md-8.mb-0.mb-lg-0.order-2.order-lg-1
    //-         figure
    //-           //- img(src='@/assets/curso/tema3/img11.png', alt='')

    //-   .p-3.p-md-4(titulo="Descargar ordenadamente y secuencialmente.")
    //-     .row.justify-content-center.align-items-center
    //-       .col-lg-8.mb-4.mb-lg-0.order-1.order-lg-2
    //-         p Retirar la mercancía siguiendo el orden establecido para facilitar la entrega.
    //-         .d-flex.align-items-start
    //-           i.fas.fa-circle-check.icon-check-custom.me-2.mt-1.txt-dark
    //-           p.mb-0 <b>Ejemplos:</b> Descargar primero los productos destinados al primer punto de entrega.
    //-       .col-lg-4.col-md-8.mb-0.mb-lg-0.order-2.order-lg-1
    //-         figure
    //-           //- img(src='@/assets/curso/tema3/img12.png', alt='')

    //-   .p-3.p-md-4(titulo="Aplicar normas de seguridad.")
    //-     .row.justify-content-center.align-items-center
    //-       .col-lg-8.mb-4.mb-lg-0.order-1.order-lg-2
    //-         p Usar elementos de protección y cumplir los procedimientos seguros durante toda la operación.
    //-         .d-flex.align-items-start
    //-           i.fas.fa-circle-check.icon-check-custom.me-2.mt-1.txt-dark
    //-           p.mb-0 <b>Ejemplos:</b> Utilizar casco, chaleco reflectivo y botas de seguridad en la zona de operación.
    //-       .col-lg-4.col-md-8.mb-0.mb-lg-0.order-2.order-lg-1
    //-         figure
    //-           //- img(src='@/assets/curso/tema3/img13.png', alt='')
    

    //- p.mb-5 La aplicación de estas técnicas disminuye pérdidas económicas y mejora la productividad de las operaciones.
    
    //- .bg-full-width.bg-fondo-1

    //-   separador
      
    //-   #t_3_5.titulo-segundo.color-acento-contenido(data-aos="flip-up")
    //-     h2 3.5 Listas de chequeo

    //-   p.mb-5 Son herramientas de verificación que permiten confirmar el cumplimiento de los requisitos establecidos antes, durante y después de las operaciones de cargue y descargue. Además, que estas se desarrollen conforme a los procedimientos establecidos y a las condiciones de seguridad requeridas. <br><br>Entre las más comunes se encuentran:


    //-   .row.mb-5.justify-content-center.align-items-center
    //-     .col-lg-4.mb-4.mb-lg-0.col-md-8.order-1.order-lg-2.d-none.d-lg-block
    //-       figure
    //-         //- img(src="@/assets/curso/tema3/img14.png", data-aos="zoom-in")
    //-     .col-lg-8.order-2.order-lg-1
      
    //-       AcordionA(tipo="a" clase-tarjeta="tarjeta bg-color-22")
    //-         div(titulo="Inspección del vehículo")
    //-           p.ms-1.ms-lg-5 Verifica el estado mecánico, la limpieza, las condiciones de seguridad y la disponibilidad del vehículo antes de iniciar la operación.

    //-         div(titulo="Recepción de mercancías")
    //-           p.ms-1.ms-lg-5 Valida que las mercancías recibidas correspondan con la documentación, las cantidades, el estado físico y las especificaciones acordadas.

    //-         div(titulo="Cargue y descargue de mercancías")
    //-           p.ms-1.ms-lg-5 Ayuda a comprobar que las operaciones de cargue y descargue se desarrollen de forma segura, ordenada y conforme a los procedimientos establecidos, garantizando la correcta manipulación de la mercancía y el cumplimiento de las medidas de seguridad.

    //-         div(titulo="Equipos de manipulación")
    //-           p.ms-1.ms-lg-5 Revisa el estado operativo de montacargas, transpaletas, apiladores y demás equipos antes de su utilización.

    //-         div(titulo="Seguridad industrial")
    //-           p.ms-1.ms-lg-5 Supervisa el uso de elementos de protección personal, la señalización, la demarcación de áreas y el cumplimiento de los protocolos de seguridad.

    //-         div(titulo="Control documental")
    //-           p.ms-1.ms-lg-5 Comprueba la disponibilidad y correspondencia de documentos como órdenes de despacho, remisiones, facturas, manifiestos y registros de transporte.

    //-         div(titulo="Despacho de mercancías")
    //-           p.ms-1.ms-lg-5 Confirma que la mercancía, la documentación, el vehículo y el destino coincidan con la orden de entrega antes de la salida.

    //-         div(titulo="Almacenamiento")
    //-           p.ms-1.ms-lg-5 Evalúa las condiciones de ubicación, apilamiento, identificación y conservación de las mercancías dentro de la bodega.
   
    //- p.mb-5 La aplicación de estas técnicas disminuye pérdidas económicas y mejora la productividad de las operaciones.


    //- .row.justify-content-center.mb-3
    //-   .col-12.col-lg-8.mb-0.col-md-12
    //-     .cita-decorada
    //-       blockquote.cita-decorada__caja.cita-decorada__caja--fondo-4.p-3.bg-color-2.br-15
    //-         .row.justify-content-center.align-items-center
    //-           .col-12.col-lg-3.mb-3.mb-lg-0
    //-             //- img(src="@/assets/curso/tema1/img04.svg", class="img-fluid cita-decorada__imagen-flotante-3")
    //-           .col-12.col-lg-9.cita-decorada__texto.mb-4.mb-lg-0.p-4
    //-             .d-flex.align-items-start
    //-               i.fas.fa-circle-check.icon-check-custom.me-2.mt-1.txt-dark
    //-               p.mb-0 <b>Ejemplo:</b> antes de autorizar el despacho, el supervisor verifica cada uno de los puntos establecidos en la lista de chequeo.


    //- separador
    
    //- #t_3_6.titulo-segundo.color-acento-contenido(data-aos="flip-up")
    //-   h2 3.6 Técnicas de manipulación del producto

    //- p.mb-5 Son el conjunto de procedimientos utilizados para movilizar, transportar y almacenar mercancías de forma segura y eficiente durante las operaciones logísticas. <br><br> Las principales técnicas incluyen:

  

    //- .bg-full-width.bg-fondo-4
    //-   .row.mb-5.justify-content-center.align-items-center
    //-     .col-lg-12.col-md-12.mb-0.mb-lg-0
    //-       .titulo-sexto.color-acento-contenido.mb-3
    //-         h5 
    //-           b Tabla 3.
    //-         span Técnicas de manipulación de productos
    //-       .tabla-a.tb-custom.mb-0
    //-         table
    //-           caption <span style="font-weight: normal">Nota. SENA, (2026).</span>
    //-           thead
    //-             tr
    //-               th Técnica
    //-               th Definición
    //-               th Ejemplo
    //-           tbody
    //-             tr
    //-               td Levantamiento seguro
    //-               td Consiste en aplicar posturas y movimientos adecuados para levantar mercancías, reduciendo el esfuerzo físico y el riesgo de lesiones durante la manipulación manual.
    //-               td Levantar una caja flexionando las rodillas y manteniendo la espalda recta.
    //-             tr
    //-               td Manipulación según el tipo de producto
    //-               td Adapta la forma de manipular la mercancía de acuerdo con sus características, como peso, fragilidad, dimensiones o condiciones especiales de conservación.
    //-               td Transportar productos de vidrio con equipos acolchados y movimientos controlados.
    //-             tr
    //-               td Uso de ayudas mecánicas
    //-               td Emplea equipos como montacargas, transpaletas o bandas transportadoras para movilizar cargas pesadas con mayor seguridad y eficiencia.
    //-               td Mover un pallet utilizando un montacargas.
    //-             tr
    //-               td Apilamiento adecuado
    //-               td Organiza las mercancías respetando su resistencia, estabilidad y capacidad de carga para evitar daños o colapsos durante el almacenamiento y transporte.
    //-               td Colocar las cajas más pesadas en la base del apilamiento.
    //-             tr
    //-               td Sujeción y aseguramiento
    //-               td Utiliza elementos de fijación para mantener la estabilidad de la mercancía durante su movilización y evitar desplazamientos o caídas.
    //-               td Asegurar un pallet con película stretch y correas de sujeción.
    //-             tr
    //-               td Manipulación con equipos de protección personal
    //-               td Incorpora el uso de elementos de protección personal para reducir los riesgos durante la manipulación de mercancías y proteger la integridad del trabajador.
    //-               td Utilizar guantes de seguridad para manipular cajas con superficies cortantes.
    //-             tr
    //-               td Inspección previa del producto
    //-               td Verifica el estado físico de la mercancía antes de moverla para identificar daños, fugas o condiciones que puedan afectar la operación logística.
    //-               td Revisar que un embalaje no presente golpes antes de trasladarlo.
    //-             tr
    //-               td Traslado controlado
    //-               td Desplaza la mercancía de forma estable, evitando movimientos bruscos, impactos o inclinaciones que puedan ocasionar daños al producto.
    //-               td Transportar equipos electrónicos a baja velocidad sobre un transpaleta.

      
    //-   .row.mb-5.justify-content-center.align-items-center
    //-     .col-lg-10
    //-       .cajon.bg-color-c1.p-4.mb-0
    //-         p.mb-0 La aplicación de estas técnicas protege la integridad del trabajador, disminuye daños a las mercancías y mejora la eficiencia de la operación logística.

    //-   .row.justify-content-center.mb-5
    //-     .col-12.col-lg-10.mb-5.col-md-12
    //-       .cita-decorada
    //-         blockquote.cita-decorada__caja.cita-decorada__caja--fondo-4.p-3.bg-color-2.br-15
    //-           .row.justify-content-center.align-items-center
    //-             .col-12.col-lg-3.col-xl-2.mb-3.mb-lg-0
    //-               //- img(src="@/assets/curso/tema1/img04.svg", class="img-fluid cita-decorada__imagen-flotante-3")
    //-             .col-12.col-lg-9.col-xl-10.cita-decorada__texto.mb-4.mb-lg-0.p-4
    //-               .d-flex.align-items-start
    //-                 i.fas.fa-circle-check.icon-check-custom.me-2.mt-1.txt-dark
    //-                 p.mb-0 <b>Ejemplo:</b> los productos frágiles o perecederos requieren procedimientos especiales de manipulación para garantizar que lleguen al cliente final en óptimas condiciones.


    //-     .col-lg-10.mb-4
    //-       .tarjeta.bg-color-1.p-3
    //-         .row.justify-content-center.align-items-center
    //-           .col-6.col-sm-3.col-md-2.mb-3.mb-md-0
    //-             //- img(src="@/assets/curso/tema1/img25.svg", style="max-width: 120px;").mx-auto
    //-           .col-md-10
    //-             .row.justify-content-between.align-items-center
    //-               .col-md.mb-3.mb-md-0.text-center.text-md-start
    //-                 h4.mb-2 Video sugerido:
    //-                 p.mb-0 A continuación, se invita a ir al siguiente video para fortalecer los conocimientos relacionados con cargue y descargue de mercancías:
    //-               .col-md-auto.text-center
    //-                 a.boton.color-acento-botones.texto-blanco(href="https://www.youtube.com/watch?v=l5djXZcO85Q" target="_blank")
    //-                   span Ir al video
    //-                   i.fas.fa-play-circle

    //-     .col-lg-10.mb-0
    //-       .tarjeta.bg-color-6.p-3
    //-         .row.justify-content-center.align-items-center
    //-           .col-6.col-sm-3.col-md-2.mb-3.mb-md-0
    //-             //- img(src="@/assets/curso/tema1/img12.svg", style="max-width: 120px;").mx-auto
    //-           .col-md-10
    //-             .row.justify-content-between.align-items-center
    //-               .col-md.mb-3.mb-md-0.text-center.text-md-start
    //-                 h4.mb-2 Lectura sugerida:
    //-                 p.mb-0 Se invita al aprendiz a profundizar en cargue y descargue de mercancías, a través del siguiente artículo:

    //-               .col-md-auto.text-center
    //-                 a.boton.color-acento-botones.texto-blanco(href="https://www.simur.gov.co/sites/simur.gov.co/files/2021-06-16/basico/Buenas_Practicas_carga_descarga_Bogota__0.pdf" target="_blank")
    //-                   span Ver enlace
    //-                   i.fas.fa-link
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
