<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Género narrativo creativo
    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La narrativa, es la base del género, consiste en contar creativamente historias del mismo autor o de otras situaciones y personajes sin relación a su vida o cotidianidad de forma armónica, libre y creativa. Incluyendo elementos atractivos en cada oración o frase, imprimiendo en estas una emotividad o una forma de poder vivir o sentir estos escritos.
    .tarjeta.color-primario.rounded-pill.p-3.d-inline-block.mb-5
      h4.mb-0 Técnicas y estrategias en la creatividad narrativa
    p.mb-5(data-aos='fade-right') Con el fin de potenciar al máximo la narrativa creativa, 
      span.r--3 se usa un conjunto de técnicas o herramientas que facilitan llegar a la historia, de una manera natural y cumpliendo el objetivo.  
      |Se sugiere partir del conocimiento y aplicación de saberes como gramática, sintaxis y tener claridad de las fases de la escritura y hacer ejercicios para afianzar cada una de ellas:  elaborar la idea inicial, hacer un borrador de varias ideas anexas, escribir técnicamente, hacer una revisión y ajustar o reescribir el texto.  
    .row.justify-content-center
      .col-lg-4.mb-lg-0.mb-3: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema2/2.jpg', alt='')
      .col-lg-8
        .cajon.color-primario(style='background-color: #FFD667').p-4.mb-4
          p.mb-0 La creatividad está asociada a la fluidez y flexibilidad en la escritura demostrada en la capacidad de planificar el escrito para lo cual debe partir de un listado de ideas para jerarquizar de acuerdo con las variables como intención o población objetivo. 
        p.mb-5(data-aos='fade-right') Según el listado de ideas, se seleccionan de forma concreta y organizan desde la idea inicial y las secundarias para la estructura del escrito que desemboca en la elaboración de los párrafos que se escriben de forma conectada, cohesiva y coherente precisa cronológicamente en la que se usan recursos como la formulación de una hipótesis la cual se comprueba durante el escrito.  
          br
          br
          |Este momento necesita de originalidad y paciencia en la redefinición permanente y ajustes de acuerdo con factores como claridad y concisión. La corrección es una acción permanente en un escrito, reescribir y estar en ese proceso cíclico ayuda a tener un documento de calidad.
    .row.justify-content-center.mb-5
      .col-lg-1.col-3.mb-lg-0.mb-3: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema2/3.svg', alt='')

      .col-lg-11
        p En el proceso de la escritura creativa se presentan inconvenientes que van desde el desconocimiento de las técnicas escriturales hasta el bloqueo de ideas por falta de claridad en el tema y otros aspectos.  
          br
          br
          |Para solucionar estas situaciones técnicamente, existen un conjunto de técnicas que ayudan al desarrollo creativo como:
    ImagenInfografica.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img(data-aos='zoom-in')(src='@/assets/curso/temas/tema2/4.svg', alt='Texto que describa la imagen')
      .tarjeta.p-3(x="28.3%" y="14.8%" numero="" style='background-color: #F3F9FF')
        .titulo-sexto.color-acento-contenido(data-aos='fade-right')
          h5 La hoja en blanco
        p La hoja en blanco es una técnica grupal, cada participante tiene una hoja en blanco, se define el objetivo y cada uno escribe mínimo 8 ideas en 3 minutos, se leen y socializan seleccionando las que más se acerquen a la propuesta.  
      .tarjeta.p-3(x="63.8%" y="11%" numero="" style='background-color: #F3F9FF')
        .titulo-sexto.color-acento-contenido(data-aos='fade-right')
          h5 Historia sorpresa
        p La historia sorpresa es grupal.  Un miembro del grupo con base en el objetivo escribe en papeletas temas, palabras o situaciones, colocándolas en una bolsa.  Cada participante saca una papeleta, tienen tres (3) minutos para contar la historia teniendo en cuenta:  inicio, nudo y desenlace.  Contar con grabadora y un apuntador tomando nota de las ideas que salgan del ejercicio.

      .tarjeta.p-3(x="16.3%" y="34%" numero="" style='background-color: #F3F9FF')
        .titulo-sexto.color-acento-contenido(data-aos='fade-right')
          h5 Organizadores gráficos 
        p El organizador gráfico puede ser un mapa mental o un mándala o cualquier estrategia para organizar información de una lectura o la comprensión de un tema o desarrollo de una idea central hacia otras secundarias.  La información pueden ser ideas o conceptos.
      .tarjeta.p-3(x="71.3%" y="28%" numero="" style='background-color: #F3F9FF')
        .titulo-sexto.color-acento-contenido(data-aos='fade-right')
          h5 Historia en trozos
        p Historia La historia en trozos consiste en que el grupo, siguiendo el orden de:  introducción, nudo, desarrollo y conclusión, construye o se cuenta una situación de acuerdo con el objetivo planteado, se da la palabra a cada participante con un tiempo definido; el primero inicia la historia y al minuto, la sigue otro miembro del equipo y así hasta llegar a la conclusión.  Tener a mano una grabadora y un apuntador tomando nota de ideas que salgan del ejercicio.

      .tarjeta.p-3(x="54.3%" y="47.5%" numero="" style='background-color: #F3F9FF')
        .titulo-sexto.color-acento-contenido(data-aos='fade-right')
          h5 #[em Brainstorming]
        p El Brainstorming o lluvia de ideas es una técnica grupal; de acuerdo con el objetivo cada participante expresa una idea de cómo puede hacerse un trabajo o escribir sobre situaciones, usando respuestas a preguntas motivadoras: ¿Qué pasó, cuando, que lo produjo?, ¿Quién…?
    .tarjeta.color-primario.rounded-pill.p-3.d-inline-block.mb-5
      h4.mb-0 Desarrollo de la creatividad narrativa
    p.mb-5(data-aos='fade-right') La narrativa se desarrolla de acuerdo con principios relacionados con la creatividad, los textos están escritos en prosa propiciando amplitud de la descripción detallada en la historia.  También, el verso, aunque menos usado, hace parte de la narrativa, aunque esta, limita la descripción. Pero es importante saber que es una habilidad que hay que entrenar y desarrollar a través del tiempo.
    .row.justify-content-center.mb-5
      .col-lg-8
        .cajon.color-secundario(style='background-color: #B7CEAC').p-4.mb-4
          p.mb-0 El objetivo es comunicar por medio del relato o de una serie de acontecimientos, historias que se compongan de un narrador, personajes, el espacio, escenario o ambiente, el relato y el estilo de narración.  Para desarrollar la historia casi siempre se inicia por la presentación de los personajes y el lugar donde se desarrollan los hechos y a continuación el desarrollo de los hechos en un nudo o momento de tensión que se cierra con el desenlace o fin de la historia, pero aun, así como su nombre lo indica en la creatividad siempre puede haber un estilo diferenciador o nuevo.
        p La narración se hace generalmente en tercera persona, sin embargo, se puede realizar en primera o segunda persona.  Igualmente, el narrador puede estar integrado o no entre los personajes.  La narración hace parte de la comunicación escrita y en diferentes tipos de diálogos relacionados con el teatro, el cine, las historietas y en los formatos televisivos, en las telenovelas, modalidades de transmisión de contenido e información innovadoras del siglo XXI, en la que no se puede dejar a un lado lo concerniente al contenido para la #[i web] e #[i internet.]
      .col-lg-4: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema2/5.jpg' alt='')
    .tarjeta.color-primario.rounded-pill.p-3.d-inline-block.mb-5
      h4.mb-0 Pensamiento visual y narrativa
    .row.justify-content-center.mb-4
      .col-lg-4.mb-lg-0.mb-3: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema2/6.jpg', alt='')
      .col-lg-8
        p El siglo XXI trae consigo novedades en todas las disciplinas y saberes, donde la escritura no fue la excepción.  
        .cajon.color-primario(style='background-color: #FFD667').p-4.mb-3
          p.mb-0 El desarrollo de las artes con base en lo visual generó técnicas como el Pensamiento Visual o #[i Visual Thinking] que consiste en pasar las ideas a imágenes y gráficos para transmitir mensajes o manejar información.
        p.mb-0 La representación de ideas y conceptos en gráficas, fotos e imágenes hace en curso dentro de las herramientas de aprendizaje más usadas y es común ver la propuesta en infografías, mapas de procesos, organizadores de información gráfica entre otros y afirman los expertos que ha calado porque es muy innato del ser humano en sus expresiones el interés por la imagen ya sea en video o estática.
          br
          br
          span.r--3 El pensamiento visual trae consigo otras herramientas como la Grabación Gráfica o #[i Graphic Recording] que ayudan a la sistematización o síntesis de la información con amplitud de opciones que, como el dibujo, la fotografía, el video, los audios, generan una gama de formas narrativas que exploran otras habilidades.
    .row.justify-content-center.mb-5
      .col-lg-1.col-3.mb-lg-0.mb-3: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema2/3.svg', alt='')

      .col-lg-11
        p Transmitir ideas de forma dinámica, concisa y clara es un apoyo en el entorno educativo, artístico, comercial y permea los mensajes y la forma comunicativa de todas las generaciones flexibilizando el trabajo en equipo y los lenguajes, ya que está comprobado que el contenido digital genera motivación e impacta la mente humana haciendo parte de las nuevas propuestas de #[i marketing] y de otras actividades del ser humano.
    .row.justify-content-center.mb-5
      .col-lg-8
        p El paso de la narración literaria a la narración visual es un fenómeno reconocido en la fuerza que toma la ilustración y la imagen en el hecho de contar historias en otras formas de escritura, lo que es un reto para el guía que además de integrar estas formas de comunicación en la presentación de recorridos.
          br
          br
          span.r--3 Se aconseja que el guía apropie rápidamente dentro de la narrativa creativa las herramientas del pensamiento visual incluyendo los aprendizajes relacionados con ver, imaginar y mostrar.  Ampliar sus narraciones y asumir las propuestas del pensamiento visual diversificando la comunicación.  
          | Aprender sobre la función de lo visual en la narración convirtiendo esta actividad en un arte; desarrollar competencias de pensamiento visual, la comunicación visual, la creación y desarrollo de ideas integrando la imagen, la iniciativa e imaginación en propuestas narrativas que despierten interés y motivación en diferentes canales y medios teniendo en cuenta la percepción y el estudio de emociones y el cerebro humano.
      .col-lg-4: img.mb-5(src='@/assets/curso/temas/tema2/7.jpg', alt='')
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
