<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Escritura creativa
    .row.justify-content-center.mb-5
      .col-lg-6.mb-lg-0.mb-3
        .cajon.color-primario(style='background-color: #ffd667').p-4.mb-4
          p.mb-0 La escritura creativa es aquella que posee sus propias características y formas, ubicándose muy aparte de la escritura periodística, académica, técnica, o literaria. La escritura creativa es original y única, lo que hace que se aleje sustancialmente de las escrituras convencionales existentes.
        p.mb-5(data-aos='fade-right') Esta escritura permite crear, inventar, y mostrar temas novedosos, que buscan cumplir con un objetivo, buscando a través de su originalidad captar la atención del receptor y causar en este un efecto que lleve a la vivencia de momentos o generar experiencias. 
          br
          br
          | Veamos a continuación, varios elementos de la escritura creativa:
      .col-lg-6: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/1.jpg', alt='')
    TabsC.color-primario.mb-5
      .py-3.py-md-4(titulo="Características de la escritura creativa").bg-tabs
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-6
            p Tenemos características de la escritura creativa:
            p Es original: es un género libre y espontaneo, el autor aporta un punto de vista fresco, distinto, novedoso, por lo tanto no existe un texto o guion igual, logrando además causar una sensación de innovación en el receptor.
              br
              br
              |No imita otros géneros: es precisamente por su originalidad, repentismo y autenticidad, que los productos de la escritura creativa están totalmente alejados de esquemas de la escritura tradicional.
              br
              br
              |Revela el talento y la imaginación: la creatividad y la imaginación caracterizan al autor  quien revela su personalidad, sus objetivos.
          .col-lg-5: img.mb-5(data-aos='zoom-in-up')(src='@/assets/curso/temas/tema5/2.jpg', alt='')
      .py-3.py-md-4(titulo="Tipos de escritura creativa")
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-6
            p Los tipos de escritura creativa se resumen en: 
            ul.lista-ul--color.ms-4
              li
                i.vineta
                | Poesía
              li
                i.vineta
                | Cuento
              li
                i.vineta
                | Teatro
              li
                i.vineta
                | Novela
              li
                i.vineta
                | Relato
              li
                i.vineta
                | Ensayo
              li
                i.vineta
                | Guiones
          .col-lg-5: img.mb-5(data-aos='zoom-in-up')(src='@/assets/curso/temas/tema5/3.jpg', alt='')
      .py-3.py-md-4(titulo="Diferencias entre escritura académica y la creativa")
          p La escritura creativa tiene diferencias de la escritura académica, entre las que se describen las siguientes:
          .tabla-a.tabla-editada.mb-5
            table
              thead
                tr
                  th(style='background-color: #ffb338; color: black') Escritura académica
                  th(style='background-color: #2b6e17; color: white') Escritura creativa
              tbody
                tr
                  td La escritura académica es propia del ámbito universitario y científico.
                  td La escritura creativa se sale de los esquemas de la escritura tradicional como puede ser la escritura académica, por ejemplo.

                tr
                  td Su finalidad es didáctica, casi siempre.
                  td La originalidad, y la imaginación son dos de sus armas más características.
                tr
                  td Persuadir, argumentar e informar son claves a la hora de confeccionar este tipo de escrituras.

                  td Los autores que la llevan a cabo tienden a inventarse temas, situaciones o cosas generando así la sensación de novedad e innovación.
                tr
                  td Utiliza una serie de recursos muy elaborados.
                  td La escritura creativa no imita ningún género, ni sigue un patrón clásico de escritura.
      .py-3.py-md-4(titulo="Finalidad creativa")
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-6
            p La escritura incentiva la imaginación al tener una finalidad creativa lo cual permite:
            p El desarrollo de procesos de aprendizaje: generación de empatía con el receptor del mensaje y además motiva el pensamiento creativo, elementos esenciales en el quehacer del guía de turismo.
              br
              | Mejora el vocabulario y léxico: así como ampliar el conocimiento y aplicaciones de nuevas expresiones.
              br
              | Al crear, mejora la capacidad de concentración, y a ser más reflexivo a la hora de pensar. 
              br
              | Transmite a través de la información vivencias y experiencias a los receptores.
              br
              | Crear textos desde la imaginación y con la utilización de la propia invención.


          .col-lg-5: img.mb-5(data-aos='zoom-in-up')(src='@/assets/curso/temas/tema5/4.jpg', alt='')
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6
        p 
          span.r--3 El proceso creativo está relacionado con dos aspectos humanos: el cerebral y la habilidad o chispa creativa, 
          | que técnicamente, se convierte en la forma creativa de expresar de forma escrita o verbal.  
          br
          br
          |Los expertos sustentan que el proceso creativo necesita de un desarrollo técnico con las siguientes recomendaciones y tips a tener en cuenta para lograr un efecto con sensaciones a quien lo escuche o lea: 
      .col-lg-6 
        SlyderF.mb-5.slyder-100(columnas="col-lg-6 col-xl-6")
          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema5/5.svg' alt='AvatarTop' style='width: 130px')
            .tarjeta(style='background-color: #e1f3d7').w-100
              .text-center.p-4
                h4.text-center Planear  rutina
          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema5/6.svg' alt='AvatarTop' style='width: 130px')
            .tarjeta(style='background-color: #e1f3d7').w-100
              .text-center.p-4
                h4.text-center Practicar, escribir a diario
          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema5/7.svg' alt='AvatarTop' style='width: 130px')
            .tarjeta(style='background-color: #e1f3d7').w-100
              .text-center.p-4
                h4.text-center Leer textos ejemplo

          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema5/8.svg' alt='AvatarTop' style='width: 130px')
            .tarjeta(style='background-color: #e1f3d7').w-100
              .text-center.p-4
                h4.text-center Escribir las ideas
          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema5/9.svg' alt='AvatarTop' style='width: 130px')
            .tarjeta(style='background-color: #e1f3d7').w-100
              .text-center.p-4
                h4.text-center Hacer una estructura antes de escribir
          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema5/10.svg' alt='AvatarTop' style='width: 130px')
            .tarjeta(style='background-color: #e1f3d7').w-100
              .text-center.p-4
                h4.text-center Utilizar figuras literarias
          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema5/11.svg' alt='AvatarTop' style='width: 130px')
            .tarjeta(style='background-color: #e1f3d7').w-100
              .text-center.p-4
                h4.text-center Escribir para llamar la atención del lector
          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema5/12.svg' alt='AvatarTop' style='width: 130px')
            .tarjeta(style='background-color: #e1f3d7').w-100
              .text-center.p-4
                h4.text-center Hacer proceso de empatía con la historia
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-1.col-3.mb-lg-0.mb-3
        img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/13.svg', alt='')
      .col-lg-11 Cada técnica necesita de unas acciones concretas, en el caso de la escritura, debe seleccionarse el tiempo o una franja diaria, en un lugar con luz, ambiente cómodo y tener cerca lo que genera inspiración;  dicen los expertos que la práctica hace al maestro, aprovechar los tiempos libres, escribir diariamente y usando normas gramaticales y estructuras semánticas es una ayuda para desarrollo de la habilidad;  igualmente, la lectura de textos de autores reconocidos y de los temas a escribir, ayuda a la estructuración semántica y creativa de fluidez. 
    .row.justify-content-center.mb-5
      .col-lg-6
        p Depender de la inspiración puede ser poco efectivo, siempre tenga a mano una libreta y escriba ideas que ayuden a la elaboración del texto, igual, el ejercicio permanente de pensar y escribir genera la posibilidad de riqueza textual y variada; el plan de escritura y ordenamiento de un texto en una línea temporal y que permita definir el nudo o situaciones de la historia, esto dará coherencia y cohesión al texto.  La metáfora, paradoja, ironía entre otras figuras literarias le da belleza, sorpresa y pertinencia al escrito, evitar siempre los adjetivos o palabras exageradas o enfáticas que no aportan a la historia.
          br
          br
          |El lector o receptor, sus expectativas y necesidades deben ser parte del escrito o la historia, así se conecta con el escrito y desde luego que la empatía, ayuda a crear personajes y situaciones comprensible y reales para él. 
      .col-lg-6: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/14.jpg', alt='')  
    .cajon.color-primario(style='background-color: #ffd667').p-4.mb-4
      p.mb-0 Finalmente, el proceso creativo y los pasos para armar una historia o relatar un suceso necesita de un camino metodológico que además permita llegar al reconocimiento de la propia posibilidad de desarrollar la escritura, paso a paso, de forma atenta y dedicada.  
    p.mb-5(data-aos='fade-right') Cada etapa del trabajo es crucial para llegar al resultado:
    TabsA.color-acento-contenido.mb-5
      .tarjeta.p-4(titulo="Introspección / Acopio" style='background-color:#d0eac3')
        .row.justify-content-center.align-items-center
          .col-lg-10.mb-lg-0.mb-3
            h5 Introspección / Acopio
            p Es un momento de encuentro con el yo creativo, escribiendo ideas, dibujando, activando la imaginación. 

          .col-lg-2.col-4: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/15.svg', alt='')
      .tarjeta.p-4(titulo="Primer borrador" style='background-color:#d0eac3')
        .row.justify-content-center.align-items-center
          .col-lg-10.mb-lg-0.mb-3
            h5 Primer borrador
            p Decantar las ideas escribiendo un primer texto muy generoso y amplio con posibilidades de ajustar y trabajar.
          .col-lg-2.col-4: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/16.svg', alt='')
      .tarjeta.p-4(titulo="Corrección y divulgación" style='background-color:#d0eac3')
        .row.justify-content-center.align-items-center
          .col-lg-10.mb-lg-0.mb-3
            h5 Corrección y divulgación
            ul.lista-ul--color
              li
                i.vineta2
                | Pulir el primer borrador, corregir lenguaje, oírlo en voz alta y ajustar.
              li
                i.vineta2
                | Presentar o publicar.

          .col-lg-2.col-4: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/17.svg', alt='')
    .tarjeta.color-primario.rounded-pill.p-3.d-inline-block.mb-5
      h4.mb-0 #[i Marketing] de contenidos para el turismo
    p.mb-5(data-aos='fade-right') El #[i marketing] o técnicas para comercializar productos y servicios, hace parte de la creatividad y saberes que en el turismo se desarrollan habitualmente.  
      br
      br
      |Los estudiosos del #[i marketing] y sus estrategias sobre contenidos recomiendan que al implementarlas los contenidos e imagen deben ser equilibrados, claros y de impacto para aprovechar las numerosas ventajas de la  internet, como:
    .row.justify-content-center.mb-5
      .col-lg-7
        AcordionA.mb-5(tipo="b" clase-tarjeta="tarjeta acordeon-inactivo"  )
          .div(titulo="Reconocimiento fácil de producto y servicios a ofrecer")
            p La publicación en  internet es el mejor aliado; servicios ofrecidos en una tienda virtual que funciona 24 horas, 7 días a la semana.   
              br
              br
              |Los contenidos para clientes potenciales y que demandan, conocen y buscan sobre sus intereses, deben encontrar en el espacio creado, las ventajas competitivas de lo ofrecido.
          .div(titulo="Posicionamiento y conquista de la autoridad en el mercado")
            p La presencia en  Internet permite dar visibilidad a un amplio público y ante la competencia; se necesita un portafolio de servicios y productos de la empresa ya sea propia o que sea un empleado.  
              br
              br
              |Para convertirse en autoridad del mercado es indispensable, la buena imagen y la generación de confiabilidad de lo que allí se presenta e informa, lo que da el poder de negociación concretar las acciones de fidelizar el cliente efectivo y llegar al potencial con experiencias y calificación del servicio o producto, clave del mercadeo 

          .div(titulo="Sostenibilidad y reducción de gastos")
            p Los contenidos de mercadeo son costosos y generan gastos en papel y propaganda que, aunque es importante, generar alto valor económico.  
              br
              br
              |El #[i marketing] por # internet es una estrategia económica y que puede reducir costos de inversión en la comercialización. Parte de ser empresario o trabajar para una empresa, implica responsabilidad en el uso de los recursos ya sean financieros o materiales 

          .div(titulo="Acelera el ciclo de ventas")
            p El tiempo que la empresa invierte entre contactar inicialmente al cliente,  hasta el cierre de la venta, y todo lo que acontece en ese espacio, son etapas de un ciclo de venta.
              br
              br
              |El #[i marketing]  de contenidos dentro de este espacio de tiempo, es veloz y altamente efectivo porque el mensaje llega a cada persona y además se siente realizado para la individualidad, lo que parece que es personalizado y de fácil acceso lo que impacta al cliente y sus decisiones ubicándolo de manera ágil, en el momento o etapa de compra.
      .col-lg-5.col-8: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/18.png', alt='')










    p.mb-5(data-aos='fade-right') Todo lo anterior reafirma la importancia de la escritura creativa en procesos como el #[i marketing] que se pueden publicar en diferentes tipos de canales como:  
    .row.justify-content-center.align-items-center
      .col-lg-10
    
        .tarjeta.tarjeta-wrap(style='background-color: #dee4f0').p-2.mb-5
          .d-flex.m-3.align-items-center.justify-content-center
            img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/i1.svg', alt='' style='width: 30px ').me-2
            h4.mb-0  Blog
          .d-flex.m-3.align-items-center.justify-content-center
            img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/i2.svg', alt='' style='width: 30px ').me-2
            h4.mb-0  E-books
          .d-flex.m-3.align-items-center.justify-content-center
            img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/i3.svg', alt='' style='width: 30px ').me-2
            h4.mb-0  Newsletter
          .d-flex.m-3.align-items-center.justify-content-center
            img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/i4.svg', alt='' style='width: 30px ').me-2
            h4.mb-0  Videos
          .d-flex.m-3.align-items-center.justify-content-center
            img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/i5.svg', alt='' style='width: 30px ').me-2
            h4.mb-0  Infografías
          .d-flex.m-3.align-items-center.justify-content-center
            img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/i6.svg', alt='' style='width: 30px ').me-2
            h4.mb-0  Podcasts
    .tarjeta.color-primario.rounded-pill.p-3.d-inline-block.mb-5
      h4.mb-0 #[i Storytelling, storyscaping, storydoing]
    p.mb-5(data-aos='fade-right') Las técnicas para materializar la escritura creativa no solo en #[i marketing] si no en otros escenarios como el de generar experiencia cliente en el turismo se diseñan al tener en cuenta que, desde la generación de ideas hasta la divulgación, el lenguaje inspirador es esencial.  Relacionado a que el #[i marketing] incluye la emoción como parte del objetivo, creando vínculos afectivos entre todas las personas o clientes, para volverlos protagonistas de las historias por lo que el uso de técnicas que lo permitan como el #[i storytelling, storyscaping, storydoing] están de moda, haciendo parte de la forma de presentar contenidos de la narrativa creativa o #[i branded content.]
    .row.justify-content-center.mb-5
      .col-lg-8
        .cajon.color-primario(style='background-color:#ffd667 ').p-4.mb-4
          p El #[i storytelling], es una palabra del idioma inglés compuesta por: #[i “story”] que traduce historia y #[i “telling”], que traduce contar.  Varios autores concuerdan que es un arte que a través de la creación, descripción, desarrollo y adaptación de historias que se escriben con elementos de la narrativa como personajes, contextos o ambientes, nudo o conflicto y un mensaje o moraleja, cuentan con una estructura que presentan el inicio, medio y fin, de un relato, con el objetivo de enclavar un mensaje llevando a la conexión con el receptor, lector u oyente a nivel emocional, concepto que es propicio porque el guía, es un facilitador de experiencias.
        p.mb-5(data-aos='fade-right') La originalidad o impronta personal de quien la realiza o sea el autor se deriva de la experiencia y la perspectiva con que este la narra permitiendo que las buenas historias conduzcan al público a lo largo de una jornada y que esta sea inolvidable.  
          br
          br
          |Los elementos del #[i storytelling] como técnica de narrativa creativa son:  

      .col-lg-4: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/20.jpg', alt='')
    .titulo-sexto.color-acento-contenido(data-aos='fade-right')
      h5 Tabla 4. 
      span Elementos del #[i storytelling]
    .tabla-a.tabla-editada.mb-5
      table
        thead
          tr
            th(colspan='2') Elementos del #[i storytelling]
        tbody
          tr
            td.text-center.fw-bold Mensaje
            td
              p El mensaje está compuesto por dos partes:
              ul.lista-ul--color1.ms-3
                li
                  i.fas.fa-circle.fa-xs.me-2
                  | #[em Story:] la historia y el mensaje que serán transmitidos. 

                li
                  i.fas.fa-circle.fa-xs.me-2
                  | #[em Telling:] la forma como ese mensaje es presentado. 
              p Se usan buscando equilibrio lingüístico en el texto y estos componentes, en otras palabras, si el mensaje es fuerte, puede surtir el efecto aun teniendo un telling débil; de otra parte, si el telling, es débil o plano difícilmente se salvará el mensaje, pese a que se utilicen técnicas de calidad. 

          tr
            td.text-center.fw-bold Personaje
            td El personaje, puede ser real o ficticio, pero es en quien recae toda la acción de la historia.
          tr
            td.text-center.fw-bold Ambiente o contexto
            td Puede ser real o ficticio, es el lugar donde sucede la historia. Es importante hacer una excelente descripción para posibilitar que el lector, oyente o receptor vivencie la historia y el momento lo más cercano posible. 
          tr
            td.text-center.fw-bold Trama/Nudo/Conflicto
            td 
              p La trama, nudo o conflicto es el elemento que atrae y atrapa el interés del lector, oyente o receptor. Se afirma que es el desafío motivante del receptor, lo mantiene atento y al integrarse disfruta de toda la jornada.
                br
                | Este elemento debe ser elaborado con calidad, profundidad y evitando una solución facilista, pues esto crea desconexión con el lector, oyente o receptor. Por lo tanto, la trama, nudo o el conflicto debe ser elaborado de forma compleja, con expectativa para mantener la atención durante el desarrollo de las actividades y dejar sensaciones variadas hasta mucho tiempo después. 
    p.mb-5(data-aos='fade-right')
      span.r--3 El #[i storyscaping] busca conectar al receptor con una historia, esta técnica pretende que el lector, oyente o receptor viva la historia
      | , se busca un mundo en el que el receptor no solo participe y se relacione sintiéndose identificado, sino que es protagonista y parte importante de la historia, la puede ayudar a construir o deconstruir, se apropia de ella.
    .row.justify-content-center.mb-5
      .col-lg-5.mb-lg-0.mb-3: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/21.jpg', alt='')
      .col-lg-7
        p En cuanto al uso en el #[i marketing], Darren McColl y Gaston Legorburu – 2014, sostienen que:
        div(style='background-color: #ffe6a1').p-4.mb-4
          .row.justify-content-center
            .col-lg-1.col-3.mb-lg-0.mb-3: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema5/22.svg', alt='')
            .col-lg-11 
              p.fst-italic.mb-0 #[b "Storyscaping:] Stop Creating Ads, Start Creating Worlds"
                br
                | #[b "Storyscaping:] deje de crear anuncios, comience a crear mundos"
        p.mb-0 De otra parte, la técnica #[i storydoing] aplicada en el turismo tiene como objetivo permitir que el viajero tenga contacto con otras cotidianidades diferentes a la suya y otorgar la oportunidad de que sean transformadas en experiencia de vida. Este renacimiento del turismo hacia la construcción y mejora de la identidad del viajero se edifica a través de sentir nuevas emociones, lo que implica que las historias y experiencias se diseñan desde la base personal de la percepción creada en la mente del turista como respuesta a la comparación entre las expectativas del viaje o imaginario y su experiencia concreta, es decir, la experiencia realizada. 
          br
          br
          | Esta técnica 
          span.r--3 es efectiva para el desarrollo en la concepción del turismo alternativo puesto que desde este enfoque el turista deja de ser un sujeto pasivo para convertirse en activo, 
          | al interactuar con el entorno que visita convirtiendo esta, en una experiencia única y totalmente emocional.
    p.mb-5(data-aos='fade-right') El #[i storydoing] (#[i story:] historia – #[i doing:] haciendo) es interactividad pura, pues se reconoce que transmitir una historia y unos valores y hacer que el participante empatice con ella #[i (storytelling)], llevando a la demostración de las ventajas sobre migrar a la acción incluyente en donde el receptor puede ser protagonista y ser parte de la historia, haciendo historia #[i (storydoing).]  
      br
      br
      | Existen diferencias a tener en cuenta:   
    .row.justify-content-center.mb-5
      .col-lg-4.mb-lg-0.mb-3
        .tarjeta.text-center(style='background-color: #ffe6a1').p-4.h-100
          img.m-auto.mb-3(src='@/assets/curso/temas/tema5/23.svg', alt='' style='width: 119px')  
          h5 #[i Storytelling]
          p.mb-0 Simplemente cuenta una historia al receptor
          hr.my-1
          p #[i Storytelling] busca contar historias
      .col-lg-4
        .tarjeta.text-center(style='background-color: #ffe6a1').p-4.h-100
          img.m-auto.mb-3(src='@/assets/curso/temas/tema5/24.svg', alt='' style='width: 119px')  
          h5 #[i Storydoing]
          p.mb-0 Crea experiencias para el receptor
          hr.my-1
          p #[i Storydoing] las lleva a cabo

 




</template>

<script>
export default {
  name: 'Tema5',
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
