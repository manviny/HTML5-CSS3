## Inline, Block, Inline-block



### BLOCK
Los elementos con este estilo se van colocando verticalmente y respetan el width y el height (el ancho y el alto) que les hemos asignado. Este es el estilo por defecto de los divs.
```html
<address>  <article>  <aside>  <blockquote>  <canvas>  <dd>  <div>  <dl>  <dt>  <fieldset>  <figcaption>  <figure>  <footer>  <form>  <h1>  -<h6>  <header>  <hr>  <li>  <main>  <nav>  <noscript>  <ol>  <output>  <p>  <pre>  <section>  <table>  <tfoot>  <ul>  <video>  
```
- ocupan todo el ancho del navegador
- los elemento de bloque pueden contener elementos inline y block.
- se les puede aplicar width y height

### INLINE
Los elementos con este estilo se van apilando en horizontal y hacen caso omiso del width y el height que les indicamos. Tampoco procesan muy bien el padding asignado. Este es el estilo por defecto de las etiquetas a y span. Se utiliza fundamentalmente para contener texto.
```html
<a>  <abbr>  <acronym>  <b>  <bdo>  <big>  <br>  <button>  <cite>  <code>  <dfn>  <em>  <i>  <img>  <input>  <kbd>  <label>  <map>  <object>  <q>  <samp>  <script>  <select>  <small>  <span>  <strong>  <sub>  <sup>  <textarea>  <time>  <tt>  <var>  
```
- ocupan el espacio de los elementos contenidos
- los elementos inline solo pueden contener elementos inline.
- NO se les puede aplicar width y height

### INLINE-BLOCK
A medio camino entre el estilo display:block, y el estilo display:inline, está el estilo display:inline-block. Los elementos con este estilo se apilan en horizontal y SÍ respetan el width y el height que les hemos asignado. Este es el estilo por defecto de las imágenes.


#### Ejercicios
  1. hacer un parrafo con color de fondo, veremos que ocupa todo el ancho de la pantalla, se trata de un elemento de tipo block
  2. poner el css inline (display:inline) y veremos que ahora solo ocupa el ancho del texto
  3. escribir en github todos elementos  block e inline
  4. convertir un elemento block (img) a inline
  5. Hacer una lsita con <ul> y que se va en horizontal
  
```html
<div>Esto es un DIV</div>  
<p>esto es un párrafo</p>
```
  - cambiar width and height a los elementos de tipo block al código siguiente a




