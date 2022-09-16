---
layout: default
books:
  -
    title: A ciegas
    img: "../images/books/a-ciegas.jpg"
  -
    title: Anthony Bourdain. Confesiones de un chef
    img: "../images/books/confesiones-de-un-chef.jpg"
  -
    title: Así se manipula al consumidor
    img: "../images/books/asi-se-manipula-al-consumidor.jpg"
  -
    title: Barack Obama. Biografía
    img: "../images/books/barack-obama.jpg"
  -
    title: Bruce Dickinson. Biografía
    img: "../images/books/bruce-dickinson.jpg"
  -
    title: Celda de aislamiento
    img: "../images/books/celda-aislamiento.jpg"
  -
    title: Creatividad S.A.
    img: "../images/books/creatividad-sa.jpg"
  -
    title: Cultura Innovadora
    img: "../images/books/cultura-innovadora.jpg"
  -
    title: De cero a uno
    img: "../images/books/de-cero-a-uno.jpg"
  -
    title: De entrada diga no
    img: "../images/books/diga-no.jpg"
  -
    title: El alquimista
    img: "../images/books/el-alquimista.jpg"
  -
    title: El caballero de la armadura oxidada
    img: "../images/books/el-caballero-de-la-armadura-oxidada.jpg"
  -
    title: El elogio de la lentitud
    img: "../images/books/elogio-de-la-lentitud.jpg"
  -
    title: El estilo Virgen. Richard Branson
    img: "../images/books/estilo-virgin.jpg"
  -
    title: El hombre más rico de Babilonia
    img: "../images/books/el-hombre-mas-rico-de-babilonia.jpg"
  -
    title: El monje que vendió su ferrari
    img: "../images/books/el-monje-que-vendio-su-ferrari.jpg"
  -
    title: El poder de los hábitos
    img: "../images/books/el-poder-de-los-habitos.jpg"
  -
    title: El legado de Mandela
    img: "../images/books/el-legado-de-mandela.jpg"
  -
    title: El sutil arte de que te importe un carajo
    img: "../images/books/el-sutil-arte.jpg"
  -
    title: Empieza con el porqué
    img: "../images/books/empieza-con-el-porque.jpg"
  -
    title: En sólo 20 horas
    img: "../images/books/en-20-horas.jpg"
  -
    title: Equipos ideales
    img: "../images/books/equipos-ideales.jpg"
  -
    title: Feminismo para torpes
    img: "../images/books/feminismo-para-torpes.jpg"
  -
    title: Generación de Modelos de Negocio
    img: "../images/books/generacion-bm.jpg"
  -
    title: Hábitos atómicos
    img: "../images/books/habitos-atomicos.jpg"
  -
    title: I am Ozzy
    img: "../images/books/i-am-ozzy.jpg"
  -
    title: Ikigai esencial
    img: "../images/books/ikigai.jpg"
  -
    title: La meta
    img: "../images/books/la-meta.jpg"
  -
    title: La verdadera historia de Twitter
    img: "../images/books/twitter.jpg"
  -
    title: Lean Startup
    img: "../images/books/lean-startup.jpg"
  -
    title: Lecciones de liderazgo
    img: "../images/books/steve-jobs.jpg"
  -
    title: Los 4 acuerdos
    img: "../images/books/los-4.jpg"
  -
    title: Los 7 hábitos de la gente altamente efectiva
    img: "../images/books/los-7.jpg"
  -
    title: Myke Tyson. Toda mi verdad
    img: "../images/books/myke.png"
  -
    title: No es por el café
    img: "../images/books/no-es-por-el-cafe.jpg"
  -
    title: No te ahoges en un vaso de agua
    img: "../images/books/no-te-ahoges.jpg"
  -
    title: Nunca pares. Phil Knight
    img: "../images/books/nunca-pares.jpg"
  -
    title: OPEN. Andre Agassi
    img: "../images/books/open.jpg"
  -
    title: Oprime refrescar
    img: "../images/books/refrescar.jpg"
  -
    title: Papillon
    img: "../images/books/papillon.jpg"
  -
    title: Porque amamos a los perros, nos comemos a los cerdos y nos vestimos con vacas
    img: "../images/books/porque-amamos-a-los-perros.jpg"
  -
    title: Querido lider
    img: "../images/books/querido-lider.jpg"
  -
    title: REC
    img: "../images/books/rec.jpg"
  -
    title: Reinventarse
    img: "../images/books/reinventarse.jpg"
  -
    title: Scar Tissue
    img: "../images/books/scar.jpg"
  -
    title: SCRUM
    img: "../images/books/scrum.jpg"
  -
    title: Seis sombreros para pensar
    img: "../images/books/seis-sombreros.jpg"
  -
    title: Soy solo
    img: "../images/books/soy-solo.jpg"
  -
    title: Sprint
    img: "../images/books/sprint.jpg"
  -
    title: Transformación Digital
    img: "../images/books/td.jpg"
  -
    title: Un ataque de lucidez
    img: "../images/books/lucidez.jpg"
  -
    title: Un click. Amazon
    img: "../images/books/amazon.jpg"
  -
    title: Vigilancia permanente
    img: "../images/books/vigilancia.jpg"

---

<style type="text/css">
  table, th, td {
    border: 1px solid black;
    border-collapse: collapse;
    padding: 10px;
  }

  .book-img {
    float: center;
    width:  150px;
    height: 230px;
    object-fit: cover;
  }
</style>

<div>

  <h1>Lecturas</h1>
  La siguiente es una lista curada de libros que, en algún momento, me fueron de utilidad o me gustaron más que otros, y que sin lugar a dudas <strong>volvería a leer </strong>.<br>
  No están ordenados por categoría ni por orden de preferencia, sino por orden alfabético.
  <br>
  <br>
  No hay libros técnicos, de programación, arquitectura y demás. Esa es otra lista.
  <br>
  <br>
  <strong>Enjoy it! </strong>
  <br>
  <br>

  <table>
    <tbody style="text-align: center">
      {% tablerow book in page.books cols:4 %}
        <img class="book-img" src="{{ book.img }}" alt="{{ book.title }}">
        <h5>{{book.title}}</h5>
      {% endtablerow %}
    </tbody>
  </table>
</div>