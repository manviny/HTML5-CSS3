## Inline, Block, Inline-block



### BLOCK
Los elementos con este estilo se van colocando verticalmente y respetan el width y el height (el ancho y el alto) que les hemos asignado. Este es el estilo por defecto de los divs.
```html
<address>  <article>  <aside>  <blockquote>  <canvas>  <dd>  <div>  <dl>  <dt>  <fieldset>  <figcaption>  <figure>  <footer>  <form>  <h1>  -<h6>  <header>  <hr>  <li>  <main>  <nav>  <noscript>  <ol>  <output>  <p>  <pre>  <section>  <table>  <tfoot>  <ul>  <video>  
```
- ocupan todo el ancho del navegador
- los elemento de bloque pueden contener elementos inline y block.
- se les puede aplicar width y height
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Block and Inline</title>
</head>
<body>
    <nav>
        <ul style="border: 1px solid blue">
            <li>First</li>
            <li>Second</li>
            <li>Third</li>
        </ul>
    </nav>
</body>
</html>
```

### INLINE
Los elementos con este estilo se van apilando en horizontal y hacen caso omiso del width y el height que les indicamos. Tampoco procesan muy bien el padding asignado. Este es el estilo por defecto de las etiquetas a y span. Se utiliza fundamentalmente para contener texto.
```html
<a>  <abbr>  <acronym>  <b>  <bdo>  <big>  <br>  <button>  <cite>  <code>  <dfn>  <em>  <i>  <img>  <input>  <kbd>  <label>  <map>  <object>  <q>  <samp>  <script>  <select>  <small>  <span>  <strong>  <sub>  <sup>  <textarea>  <time>  <tt>  <var>  
```
- ocupan el espacio de los elementos contenidos
- los elementos inline solo pueden contener elementos inline.
- NO se les puede aplicar width y height
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Block and Inline</title>
</head>
<body>
    <img src="http://placekitten.com/300/450" alt="">
    <img src="http://placekitten.com/300/500" alt="">
    <img src="http://placekitten.com/350/600" alt="">
</body>
</html>
```

### INLINE-BLOCK
A medio camino entre el estilo display:block, y el estilo display:inline, está el estilo display:inline-block. Los elementos con este estilo se apilan en horizontal y SÍ respetan el width y el height que les hemos asignado. Este es el estilo por defecto de las imágenes.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Block and Inline</title>
</head>
<body>
    <p style="display: inline-block; width: 30%">Nullam nulla eros, ultricies sit amet, nonummy id, imperdiet feugiat, pede. Nullam nulla eros, ultricies sit amet, nonummy id, imperdiet feugiat, pede. Nullam nulla eros, ultricies sit amet, nonummy id, imperdiet feugiat, pede. Nullam nulla eros, ultricies sit amet, nonummy id, imperdiet feugiat, pede.</p>
    <p style="display: inline-block; width: 30%">Nullam nulla eros, ultricies sit amet, nonummy id, imperdiet feugiat, pede. Nullam nulla eros, ultricies sit amet, nonummy id, imperdiet feugiat, pede.</p>
    <p style="display: inline-block; width: 30%">Nullam nulla eros, ultricies sit amet, nonummy id, imperdiet feugiat, pede. Nullam nulla eros, ultricies sit amet, nonummy id, imperdiet feugiat, pede. Nullam nulla eros, ultricies sit amet, nonummy id, imperdiet feugiat, pede. Nullam nulla eros, ultricies sit amet, nonummy id, imperdiet feugiat, pede. Nullam nulla eros, ultricies sit amet, nonummy id, imperdiet feugiat, pede. Nullam nulla eros, ultricies sit amet, nonummy id, imperdiet feugiat, pede.</p>
</body>
</html>
```

### Cambiar la propiedad Display
´´´css
display: inline
display: block
display: inline-block
display: none
```

#### Ejercicios
  - escribir en github todos elementos block e inline
  - crear parrafo, img, div y span con color de fondo verde, veremos la diferencia entre block e inline.
  - dar margin y padding al div y al span, ¿qué ocurre?
  - poner img (display:block) y veremos que ahora ocupa todo el ancho
  - Hacer una lista con "ul" y que se vea en horizontal
  - crear 3 columnas div que se vean en horizontal y que contengan un parrafo y 2 fotos cada una, usar inline-block
  - crear pagina con titulo, navegacion y los tres divs del ejercicio anterior.
  




