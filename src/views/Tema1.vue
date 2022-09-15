<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Técnicas de redacción y escritura
    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La comunicación se basa en la interacción entre el receptor, emisor, el mensaje y el canal con base en el diálogo oral, todo en un mismo contexto o escenario, pero como es sabido existe otro tipo de diálogo que encontramos en composiciones literaria como narraciones, cuentos, novelas, fábulas, obras de teatro, noticias entre otros, referidas al diálogo escrito el cual maneja variedad de recursos y una interacción diferente entre emisor y receptor, convirtiéndose en una relación escritor-lector y aunque se fundamenta en el mismo sistema lingüístico de la oralidad, sus características son diferentes.
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/X3Cv9sKaYo0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video
    .row.justify-content-center.mb-5
      .col-lg-9
        .tarjeta.color-primario.rounded-pill.p-3.d-inline-block.mb-5
          h4.mb-0 La comunicación escrita
        p.mb-5(data-aos='fade-right') Una de las críticas más antiguas para abordar la escritura, es que las personas al escribir lo hacen igual a como hablan, se asume que es por falta de conocimiento y comprensión de las reglas de sintaxis, gramática y en general del lenguaje escrito que efectivamente necesita estudio y apropiación profunda.  
          br
          br
          |Las características de la comunicación escrita están referidas a: 
      .col-lg-3: img(src='@/assets/curso/temas/tema1/2.svg', alt='') 
    SlyderD.mb-5(:datos="datosSlyder")
    p.mb-5(data-aos='fade-right') Por lo anterior se ratifica que estos aspectos son mayormente la talanquera para que las personas puedan expresarse con comunicación escrita.  No es imposible, la disciplina y el interés ayuda a mejorar la técnica escritural.
    .row.justify-content-center.mb-5
      .col-lg-9
        .tarjeta.color-primario.rounded-pill.p-3.d-inline-block.mb-5
          h4.mb-0 Función comunicativa de la escritura
        p.mb-5(data-aos='fade-right') La escritura cumple en sí misma una función comunicativa, la misma en su funcionamiento ofrece las respuestas que da el lenguaje para el desarrollo de la comprensión de símbolos y la capacidad del ser humano para contextualizarla de acuerdo con sus diferentes roles. Como su fin es comunicar tiene que cumplir con ciertos parámetros y estructura que permitirá que lo que se escriba cumpla su función misional de llevar el mensaje deseado a sus correspondientes receptores.
          br
          br
          |Desde el estudio estructural del lenguaje, podemos derivar varias funciones, entre las más divulgadas por expertos tenemos:

      .col-lg-3: img(src='@/assets/curso/temas/tema1/11.svg', alt='') 
    SlyderD.mb-5(:datos="datosSlyder2")
    p.mb-5(data-aos='fade-right') Cada una de 
      span.r--3 estas funciones ayuda a comprender la importancia de hacer de la redacción un tema de estudio permanente y nos ubica en la importancia de aprender a expresarse de forma escrita con alto nivel.
      br
      br
      |Para cerrar, la comunicación no es solo intercambio de información mecánica, sino la posibilidad de codificar y decodificar palabras y mensajes que tienen intención, que generan inclusive emociones, lo cual es parte fundamental del trabajo en guianza.
    .row.justify-content-center.mb-5
      .col-lg-9
        .tarjeta.color-primario.rounded-pill.p-3.d-inline-block.mb-5
          h4.mb-0 Tipos de textos, géneros y figuras literarias más comunes
        p.mb-5(data-aos='fade-right') Hay diferentes tipos de textos, géneros y figuras literarias, por ser un tema lo suficientemente amplio es posible no conocerlo en un primer momento, pero si es bueno saber que mientras más profundicemos en estos temas mejor va a ser nuestro desempeño a la hora de desarrollar textos de diferente tipo, porque podremos traer estos elementos para una correcta y profunda construcción de textos que sean enriquecedores y logren el objetivo que se espera que produzcan en las audiencias a las que sea dirigido el mismo.
          br
          br
          |Veamos algunos de estos elementos a continuación, donde podremos identificarlos y podremos utilizarlos como hemos dicho a la hora de empezar a redactar textos con un propósito firme.
          br
          br
          | Entre los tipos de textos tenemos:  

      .col-lg-3: img(src='@/assets/curso/temas/tema1/19.svg', alt='') 
    SlyderD.mb-5(:datos="datosSlyder3")
    p.mb-5(data-aos='fade-right') Dentro de los géneros o categorías que podemos encontrar dentro de la literatura tenemos:
    SlyderF.mb-5.slyder-100(columnas="col-lg-4 col-xl-4")
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema1/26.svg' alt='AvatarTop' style='width: 235px')
        .tarjeta(style='background-color: #FFEFC2').w-100
          .text-center.p-4.mt-5
            h4.text-center Género Narrativo
            p Que es la interpretación de un autor que la presenta en situaciones míticas, haciéndolas pasar por verdaderas o son verdaderas y él agrega algunos otros aspectos.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema1/27.svg' alt='AvatarTop' style='width: 235px')
        .tarjeta(style='background-color: #FFEFC2').w-100
          .text-center.p-4.mt-5
            h4.text-center Género Lírico
            p Es la comunicación del autor de sus emociones, sentimientos o sensaciones, como en el poema.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema1/28.svg' alt='AvatarTop' style='width: 235px')
        .tarjeta(style='background-color: #FFEFC2').w-100
          .text-center.p-4.mt-5
            h4.text-center Género Dramático
            p Relacionado directamente con el teatro, allí se representan en situaciones de conflicto o episodios de los actores que lo personifican y las interacciones entre ellos.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema1/29.svg' alt='AvatarTop' style='width: 235px')
        .tarjeta(style='background-color: #FFEFC2').w-100
          .text-center.p-4.mt-5
            h4.text-center Género Didáctico
            p Que tiene como función, la divulgación o la recopilación de experiencias para la enseñanza. Los recursos en los cuales se basa este tipo de género son la filosofía y la ética o componentes de teoría de las sociales que aporta los lenguajes necesarios para dejar mensajes precisos.
    p.mb-5(data-aos='fade-right') Las figuras literarias se usan como recursos para dar belleza, vivacidad y expresividad a las situaciones, permite que el lector u oyente se emocione o para sugerir o convencer sobre un tema.  
      br
      br
      |El discurso literario o del orador se enriquece con este recurso ya que tiene un toque artístico y poético.
    .row.justify-content-center.mb-5
      .col-lg-4: img.mb-5(src='@/assets/curso/temas/tema1/30.svg', alt='')
      .col-lg-8
        p.mb-5(data-aos='fade-right') Entre las figuras literarias usadas con frecuencia, están la metáfora, la hipérbole, la anáfora, el símil y otros.  
        ul.lista-ul--color
          li
            i.vineta
            | El símil consta de dos expresiones que comparan de forma indirecta o directa para acentuar alguna cualidad entre ellos que puede ser de:  diferencia, semejanza o sentido figurado.
          li
            i.vineta
            | La metáfora lo hace de forma directa, reemplazando términos; la similitud directa se realiza con un vínculo comparativo usando expresiones como “Semejante a”, “como” y otras.
          li
            i.vineta
            | La hipérbole se reconoce porque es una expresión exagerada con intenciones expresivas ya sea para minimizar o   engrandecer algún atributo particular de algo en particular.
          li
            i.vineta
            | En la personificación se destacan propiedades humanas otorgadas a un objeto o animal o elementos inanimados.
          li
            i.vineta
            | La anáfora consiste en la reiteración rítmica de sílabas o sonidos dentro de una frase o verso.
          li
            i.vineta
            | Finalmente, la alegoría cuando se habla de algo sin mencionarlo específicamente a través de un conjunto de   agrupaciones metafóricas o referenciaciones indirectas 
    .row.justify-content-center.align-items-end.mb-5
      .col-lg-7
        .tarjeta.color-primario.rounded-pill.p-3.d-inline-block.mb-5
          h4.mb-0 Técnicas tradicionales
        p.mb-5(data-aos='fade-right') En la redacción encontramos muchas técnicas, que son usadas a diario por muchas personas dedicadas a la creación y producción de contenido, como por ejemplo un #[i community manager] que debe redactar #[i copys], que son mensajes para transmitir a través de las redes sociales o un periodista que debe redactar los sucesos noticiosos acaecidos durante el día o aquella persona que lleva un blog para llevar información a su comunidad, así como millones de casos más que a través del tiempo, incluso de forma innata han usados estas técnicas tradicionales para la redacción de contenidos.
          br
          br
          |Algunas de estas técnicas son:
      .col-lg-5: img(src='@/assets/curso/temas/tema1/31.jpg', alt='') 
    .row.mb-5
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false" )
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/temas/tema1/32.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5(style='background-color: #FFE6A1')
              img.mb-3(src='@/assets/curso/temas/tema1/35.svg', alt='' style='width: 67px')
              h4 La técnica de las “W”
              p Su nombre se deriva de cómo se escriben las diferentes interrogantes al inglés #[i (Why, What, Where, etc.)] pero al español reúne todas las posibles interrogantes que nos podemos hacer frente a un tema como, por ejemplo: 
                br
                br
                |¿Qué?, ¿Quién?, ¿Dónde?, ¿Cuándo?, ¿Por qué?, ¿Cómo?, ¿Cuál?, ¿Para qué? De seguro que al tener esta información sobre alguna temática no tendría problema alguno para redactar un texto.

      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false" style='background-color: #FFE6A1')
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/temas/tema1/33.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5(style='background-color: #FFE6A1')
              img.mb-3(src='@/assets/curso/temas/tema1/36.svg', alt='' style='width: 67px')
              h4 La técnica de los 7 imperativos
              p La misma busca orientar en la argumentación o exposición de acontecimientos o hechos, usando como medio siete imperativos (Describir, Comparar, Relacionar, Analizar, Aplicar, Argumentar y Concluir) dando robustez al contenido desarrollado al tener muchos elementos para desarrollar la narrativa.
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false" style='background-color: #FFE6A1')
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/temas/tema1/34.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5(style='background-color: #FFE6A1')
              img.mb-3(src='@/assets/curso/temas/tema1/37.svg', alt='' style='width: 67px')
              h4 Pirámide invertida
              p Técnica muy utilizada en el entorno periodístico o digital donde se hace una organización de la información de forma jerárquica donde el grueso de la información (base de la pirámide) se indica al principio para dejar de último los elementos en menor importancia (punta de la pirámide), al ir de más a menos.
    p.mb-5(data-aos='fade-right') Si bien estas son sólo algunas e incluso las mismos pudiesen ser desarrollados en una escritura creativa, pero 
      span.r--3 han sido estas algunas de las técnicas tradicionales desarrolladas a través del tiempo por conocedores y neófitos de la escritura para la construcción de diferentes textos.


</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    datosSlyder: [
      {
        titulo: '',
        texto:
          'Entre estas características, está el uso correcto de la ortografía, característica que no se usa en la comunicación oral.',
        imagen: require('@/assets/curso/temas/tema1/3.jpg'),
      },
      {
        titulo: '',
        texto:
          'La comunicación escrita requiere estrategias como la descripción detallada de roles, gestos o movimientos del cuerpo que son visibles en la comunicación oral.',
        imagen: require('@/assets/curso/temas/tema1/4.jpg'),
      },
      {
        titulo: '',
        texto:
          'La misma sustituye a través de la acentuación y puntuación la tonalidad verbal en la comunicación oral.',
        imagen: require('@/assets/curso/temas/tema1/5.jpg'),
      },
      {
        titulo: '',
        texto:
          'La comunicación escrita puede verse como limitación a la comunicación, esto, porque no todos saben leer o tienen un nivel de lectura literal pudiendo convertirse en una limitante.',
        imagen: require('@/assets/curso/temas/tema1/6.jpg'),
      },
      {
        titulo: '',
        texto:
          'Escribir requiere del escritor un conocimiento de léxico, sintáctica y semántica para hacerlo de forma eficaz.',
        imagen: require('@/assets/curso/temas/tema1/7.jpg'),
      },
      {
        titulo: '',
        texto:
          'La escritura debe hacerse de forma cohesiva y coherente, usando la planeación como herramienta, lo que pocos hacen.',
        imagen: require('@/assets/curso/temas/tema1/8.jpg'),
      },
      {
        titulo: '',
        texto:
          'Escribir es una acción exigente en el cumplimiento de normas y reglas que se deben seguir, aunque pocos son cuidadosos.',
        imagen: require('@/assets/curso/temas/tema1/9.jpg'),
      },
      {
        titulo: '',
        texto:
          'La escritura tiene este carácter conservador convalidado por la Real Academia de la lengua, ya que lo que no esté aprobado por esta entidad, no existe en el lenguaje español. ',
        imagen: require('@/assets/curso/temas/tema1/10.jpg'),
      },
    ],
    datosSlyder2: [
      {
        titulo: 'Función referencial',
        texto:
          'Que define la relación entre mensaje y el objeto al que hace referencia.  Da significación a la información de manera objetiva, conceptual y lógica. ',
        imagen: require('@/assets/curso/temas/tema1/12.jpg'),
      },
      {
        titulo: 'Función emotiva',
        texto:
          'Que da la relación entre el mensaje y el emisor correspondiendo a la expresividad de sentimientos, actitudes y emociones.',
        imagen: require('@/assets/curso/temas/tema1/13.jpg'),
      },
      {
        titulo: 'Función conminativa',
        texto:
          'Que determina la relación entre el mensaje y el receptor en donde se espera una reacción de parte del último.',
        imagen: require('@/assets/curso/temas/tema1/14.jpg'),
      },
      {
        titulo: 'Función estética',
        texto:
          'Determina la relación del mensaje consigo mismo como por ejemplo un poema.',
        imagen: require('@/assets/curso/temas/tema1/15.jpg'),
      },
      {
        titulo: 'Función de contacto',
        texto:
          'Que establece el enlace comunicativo como un dispositivo que permite el flujo de palabras.',
        imagen: require('@/assets/curso/temas/tema1/16.jpg'),
      },
      {
        titulo: 'Función metalingüística',
        texto:
          'Que consiste en parafrasear o explicar hechos usando conectores para sustentar ideas.',
        imagen: require('@/assets/curso/temas/tema1/17.jpg'),
      },
    ],
    datosSlyder3: [
      {
        titulo: 'Texto descriptivo',
        texto:
          'Representa a lugares, fenómenos, personas o elementos por medio del lenguaje, enumerando sus partes, señalando, cualidades o condiciones.',
        imagen: require('@/assets/curso/temas/tema1/20.jpg'),
      },
      {
        titulo: 'Texto narrativo',
        texto:
          'Narra, cuenta o relata un evento, algo que ocurre u ocurrió, en un núcleo espacial y temporal definido.',
        imagen: require('@/assets/curso/temas/tema1/21.jpg'),
      },
      {
        titulo: 'Texto expositivo o explicativo',
        texto:
          'El objetivo de este tipo de texto es comunicar al lector sobre un asunto determinado',
        imagen: require('@/assets/curso/temas/tema1/22.jpg'),
      },
      {
        titulo: 'Texto argumentativo',
        texto:
          'Pretende persuadir o emocionar al lector por medio del lenguaje, utilizando la retórica y el convencimiento.',
        imagen: require('@/assets/curso/temas/tema1/23.jpg'),
      },
      {
        titulo: 'Texto científico y técnico',
        texto:
          'Se utiliza en la invención, investigación y difusión de la tecnología y la ciencia.',
        imagen: require('@/assets/curso/temas/tema1/24.jpg'),
      },
      {
        titulo: 'Textos periodísticos',
        texto:
          'Comunican sobre hechos y asuntos de interés general y que se utilizan en la comunicación periodística. Utilizan políticamente lo correcto e influyen en la creación del   criterio público.',
        imagen: require('@/assets/curso/temas/tema1/25.jpg'),
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
