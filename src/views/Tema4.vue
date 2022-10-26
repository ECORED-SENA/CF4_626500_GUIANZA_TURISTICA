<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Técnicas de redacción creativa
    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema4/1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Para abordar las técnicas de redacción creativa, es importante primero poder abordar algunos conceptos, reglas y recomendaciones que nos permitirán tener un mejor desarrollo de los contenidos a redactar y las cuales desarrollaremos.
    .tarjeta.color-primario.rounded-pill.p-3.d-inline-block.mb-5
      h4.mb-0 Gramática y semántica 
    p.mb-5(data-aos='fade-right') Igual que cualquier otro texto, la narración requiere del seguimiento de reglas y normas de gramática y semántica para darle calidad al producto creativo. 
    .cajon.color-primario(style='background-color: #ffd667').p-4.mb-4
      p.mb-0 La gramática es lo que se define como las reglas ortográficas y que dan claridad y corrección a los textos o al habla. Y la semántica, es la que permite identificar los patrones lingüísticos, los temas y atributos del escrito permitiendo la simplificación de este y por ende la comprensión de lo que leemos o escuchamos.  Todos los idiomas cuentan con las reglas o instrucciones válidas para cada una, esta es la sintáctica y tiene que ver con el componente gramatical de escribir correctamente las palabras y al significado que le encontramos a este orden, se le define como semántica.
    .row.justify-content-center.mb-3
      .col-lg-6.mb-lg-0.mb-3: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema4/2.jpg', alt='')
      .col-lg-6 
        p.mb-5(data-aos='fade-right') 
          span.r--3 La semántica tiene dos componentes llamados denotación, es decir el significado de las palabras, el sentido de lo oficial que es evidente por el diccionario y el de connotación que dependerá del lenguaje coloquial o popular como parte de un costumbrismo.  Como la semántica se basa en estructuras lingüísticas puede tener conceptos asociados a la lógica, la cognición y por supuesto al lenguaje en donde la semántica es una cuestión de significado, definida por la sintaxis y la pragmática. 
          br 
          br
          | En las técnicas de redacción definir o caracterizar, las diferencian entre narrar, exponer, argumentar, dialogar o resumir.
    p.mb-5(data-aos='fade-right') En las técnicas de redacción definir o caracterizar, las diferencias entre narrar, exponer, argumentar, dialogar o resumir,  la precisión, la prudencia y la empatía son necesarias para el buen desarrollo de la escritura.  Para escribir mejor se debe empezar por obtener un alto nivel de lectura, lo cual se desarrolla con el hábito, además de esto, se debe tener en cuenta:
    .row.justify-content-center.mb-5
      .col-lg-6
        ul.lista-ul--color
          li
            i.vineta 
            | Adquiera el hábito de escribir y corregir los textos.
          li
            i.vineta 
            | Escribir guardando las normas ortográficas.  
          li
            i.vineta 
            | Leer lo que se escribe identificando tipos, cacofonías y otros errores sencillos para corregirlos.
          li
            i.vineta 
            | No hay que confiarse de los correctores de textos, hay que revisar varias veces. 

          li
            i.vineta 
            | La revisión debe incluir puntuación. 
          li
            i.vineta 
            |  Tenga en cuenta no usar palabras en otro idioma si estas existen en español.
          li
            i.vineta 
            | Estar al tanto de nuevas palabras y las que van en desuso o desaparecen, consultando siempre en la Real Academia Española (RAE)
      .col-lg-6: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema4/3.jpg', alt='')
    .tarjeta.color-primario.rounded-pill.p-3.d-inline-block.mb-5
      h4.mb-0 Las normas ortográficas
    .row.justify-content-center.mb-5
      .col-lg-1.col-3.mb-lg-0.mb-3: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema3/2.svg', alt='')
      .col-lg-11 
        p Corresponde a las correcciones para tener en cuenta en la escritura.  Estas reglas y su uso dan calidad y claridad textual. A continuación, veremos algunas de las normas básicas de la RAE para una ortografía básica para tener en cuenta.
          br
          br
          |Si bien hay muchas normas para conocer y desarrollar, veamos a continuación algunas sobre acentuación y el uso correcto de algunas letras, comencemos con las normas de acentuación:
    .titulo-sexto.color-acento-contenido(data-aos='fade-right')
      h5 Tabla 2.
      span Normas de acentuación RAE (2010)
    .tabla-a.tabla-editada.mb-5
      table
        thead
          tr
            th.fw-bold.text-center(colspan='3') Acentuación
            
        tbody
          tr
            td.text-center Solo
            td.text-center No debe tener tilde nunca cuando no hay riesgo de ambigüedad. Cuando hay riesgo de ambigüedad y es adverbio, se desaconseja la tilde y en su lugar se prefieren las formas sinónimas únicamente o solamente.
            td Solo adultos
              br
              | Metió solamente un gol

          tr
            td.text-center Este, esta, estos, estas, ese, esa, esos, esas, aquel, aquella, aquellos, aquellas
            td.text-center No debe tener tilde nunca cuando no hay riesgo de ambigüedad. Cuando hay riesgo de ambigüedad y es pronombre, se desaconseja la tilde.
            td Esta es bonita, aunque prefiero aquella
          tr
            td.text-center Monosílabos
            td.text-center Los monosílabos ortográficos no se tildan nunca, salvo en los casos de tilde diacrítica. En concreto, ya no se tildan las palabras en las que todas sus vocales forman un diptongo o un triptongo ortográfico (antes se admitía como excepción).
            td Guion, Sion, ion, prion, truhan, frio, friais, lie, lio, liais, hui, huis (y no guión, Sión, ión, prión, truhán, frió, friáis, lié, lió, liáis, huí, huís) Con voseo: fias, lia (y no fiás, liá)

          tr
            td.text-center o entre cifras
            td.text-center No se tilda nunca, pues el riesgo de confundir la letra o con el 0 (cero) es mínimo. Recuérdese que ante un número que empieza por o se convierte en u.
            td 4 o 5
              br
              |23 o 24
              br
              |79 u 80

          tr
            td.text-center ý
            td.text-center Se acentúa la letra y en nombres de ortografía arcaizante donde tiene el valor de la vocal i, si le corresponde por las normas generales.
            td Ýñigo, Aýna
    p.mb-5(data-aos='fade-right') También como indicamos veamos a continuación otras normas ya relacionadas con el uso de determinadas letras.
    .titulo-sexto.color-acento-contenido(data-aos='fade-right')
      h5 Tabla 3.
      span Normas de acentuación RAE (2010)
    .tabla-a.tabla-editada.mb-5
      table
        thead
          tr
            th.fw-bold.text-center(colspan='3') Letras
            
        tbody
          tr
            td.text-center h
            td.text-center En las palabras que se pueden escribir con hache o sin ella, se prefiere siempre la forma sin hache, con independencia del uso.
            td Ala, ale, alacena, alelí, armonía, arpa, arpillera, atajo, boardilla, baraúnda, desarrapado, ológrafo, sabiondo, uy.
          tr
            td.text-center g, j
            td.text-center En los préstamos lingüísticos en los que la g y la j tiene un sonido parecido al de y, se recomienda adaptar bien la pronunciación, bien la escritura.
            td Banjo, júnior, mánager pronunciados [bánjo], [júnior], [mánajer] banyo, júnior, mánayer.
          tr
            td.text-center w
            td.text-center Se admite la w en préstamos lingüísticos, letra que se considera preferible en las voces en las que su uso está asentado. Por tanto, no necesitan cursiva.
            td Kiwi, sándwich, web, wéstern, taiwanés, kuwaití.
          tr
            td.text-center k
            td.text-center En préstamos lingüísticos, se prefiere conservar la k en las palabras que se usan mayoritariamente con ella.
            td Alaskeño, askenazi, bikini, euskera, harakiri, kamikaze, karst, kimono, kurdo, moka, musaka, póker, uzbeko Irak, Alaska, Marrakech, Pakistán.
          tr
            td.text-center c, qu
            td.text-center En préstamos lingüísticos, se prefiere la forma adaptada con c o qu cuando es mayoritaria en el uso.
            td Caqui, cuáquero, iraquí, neoyorquino, polca, queroseno, quiosco, quiosquero, telequinesia, valquiria Tanganica, Turquestán
          tr
            td.text-center qa, qe, qi, qo, qu
            td.text-center Se recomienda cambiar las combinaciones qa, qe, qi, qo, qu en nombres comunes adaptados y macrotopónimos a ca, que, qui, co, cu, cuando tienen estos valores. En el resto de los nombres, se pueden conservar.
            td Cuórum, execuátur, cuadrivio, cuark, cuásar, catarí Catar (se prefiere a Qatar) Al Qaeda
          tr
            td.text-center y final tras vocal 
            td.text-center Como norma general, se prefiere -ay, -ey, -oy, -uy en estos diptongos a final de palabra, aunque hay excepciones en préstamos donde se escribe -ai, -ei, -oi, -ui. Cuando ambas formas son válidas, se prefiere la mayoritaria en el uso.
            td Carey, yóquey, tepuy, jagüey agnusdéi, saharaui bonsái, paipái, samurái, tipoy
          tr
            td.text-center y final tras consonante
            td.text-center Al adaptar extranjerismos que terminan en consonante + y, esta se transforma en i. También se escriben con i latina final los hipocorísticos.
            td Bodi, curri, ferri, panti, rali, sexi Mari, Cati, Toni, Dani
          tr
            td.text-center y medial
            td.text-center En préstamos lingüísticos, y pasa a i cuando tiene este valor de vocal. Se recuerda que también se cambia al formar el plural de algunas palabras que terminan en vocal + y.
            td Licra, géiser, aimara gais, yoqueis, jerséis
          tr
            td.text-center ng final
            td.text-center Se recomienda suprimir la g final al adaptar palabras terminadas en -ng. El diccionario académico recoge como casos excepcionales fang, gong y yang.
            td Cáterin, campin, castin, esmoquin, márquetin, piercin, parquin, pudin o pudín
          tr
            td.text-center ps inicial
            td.text-center El uso culto sigue prefiriendo la grafía con ps- inicial, aunque en todos los casos se admiten las formas con s-.
            td Psicología, psicosis, psiquiatra, pseudoprofeta, psoriasis, seudología, seudónimo, seudópodo
          tr
            td.text-center Derivados de nombres propios
            td.text-center En los derivados de nombres propios se conservará la escritura del nombre del que procede. Esta norma no se aplica a los nombres comunes que han pasado a designar objetos, enfermedades, productos...
            td Beethoveniano, picassiano, taylorismo, shakespeariano, darwinista pero alzhéimer, boicot, yacusi, zepelín o zeppelin.
    .contenedor(style='background-color: #ffd667').p-4
      .row.justify-content-center.align-items-center
        .col-lg-1.col-3.mb-lg-0.mb-3: img(data-aos='zoom-in')(src='@/assets/curso/temas/tema4/5.svg', alt='')
        .col-lg-11 
          p.mb-0 Estas son solo algunas normas extraídas de la última actualización en ortografía, publicada por la Real Academia Española en 2010. Para poder ver todas e información adicional sobre la ortografía te invitamos a revisar el material complementario relacionado a Técnicas de Redacción Creativa.



</template>

<script>
export default {
  name: 'Tema4',
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
