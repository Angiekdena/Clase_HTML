# Intro a la Web

## HTML

Hyper text markup language

Lenguaje que por medio de etiquetas idenificas elementos

Por ejemplo:

La etiqueta de encabezado H1 se puede usar para el titulo en el sitio web:

`<h1> Título </h1>`

### ¿como se crea un sitio web?

1. Crear una carpeta donde mantendre mis archivos.

2. Crear dentro la carpeta mi archivo `index.html`

3. Crear la estructura del HTML:
   - Escribiendo "!" o "html:5" y dando enter.
   - Cambiar `<title>Documento</title>` con mi titulo.

4. Recordar la estructura del HTML:
   - `<head></head>` : Metadatos, cabeceras, configuraciones, el titulo e importaciones.
   - `<body></body> : Estructura visula de la pagina. El contenido.

5. Utilizar etiquetas semanticas:

```
<header>
    <nav></nav>
</header>
<main>
    <section></section>
    <section></section>
    <aside></aside>
</main>
<footer>
</footer>
```

- NOTA : Si quieres dar formato a tu documento, click derecho + format document

6. Empieza a añadir las etiquetas que requieras, no olvides que cada una puede tener atributos diferentes y atributos en comun:
    -En comun:
        - class: etiquetas para clasificar elementos
            - Por ejemplo:
                - `<p class="primero">`
                - `<p class="primero bg-negro">`
                - `<p class="primero texto>`
        - id: identificador ara tratar los elementos sean unicos y tener una forma de acceder directamente a ellos.

7. Agregar estilos:
    - Inline
    - Interno
    - Externo: Es importar los estilos que viven en un archivo fuera del html con la extension `.css`
        - Siguiendo los pasos:
            1. Crear archivo: `style.css`.
            2. Enlazar con html escribiendo dentro del head al final: `link:css` y enter. Y empiezo a escribir usando selectores.

8. Los selectores son:
    - nombre de la etiqueta
    - clases
    - id

9. Este es el orden de especificidad o de prioridad que da CSS a los selectores de mayor  a menor: 

    - !important
    - Estilos en linea
    - #Id
    - Clases, atributos y pseudoclases
    - Elementos y pseudoelementos
    - Selector universal
