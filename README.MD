# HTML
Lenguaje de marcado de texto, es la parte que nos permite estructurar nuestra pagina web, 
es como el esqueleto de nuestra apicacion .
Su principal objetivo es darle formato semantico a nuestra informacion a travez de uso 
de 'elementos' que esta a su vez esta conformado por 'etiquetas' de apertura y cierre y 'contenido'
>[!TIP] En algunos casos encontraremos los 'elementos' huerfano estos solo estan conformados
por una sola etiqueta.

# 🏗️ Estructura de un elemento en HTML

Un **elemento en HTML** está compuesto por varias partes que definen cómo se interpreta y muestra el contenido en el navegador:

1. **Etiqueta de apertura**  
   - Indica el inicio del elemento.  
   - Se escribe entre corchetes angulares `< >`.  
   - Puede incluir **atributos** que añaden información extra.  
   Ejemplo:  
   ```html
   <p class="texto">


## Estructura fundmental del documento HTML 
- <!DOCTYPE html> - Declaramos el tipo de documento, este elemento huerfano indica al navegador 
que el documento con el que se esta trabajando y que debera renderizar es 'html',
*siempre debe estar en la primera linea*
- '<html></html>' - Elemento raiz, envuelve todo el contenido de la pagina HTML, este elemento tiene 
dos hijos principales.
- '<head></head>' -Elemento de configuracion, contiene informacion importante sobre el documento como
(titulo,enlaces css, informacion para motores de busqueda, descripcion entre otros).
 - '<title></title>' - Elemento de titulo de pagina, es el hijo de 'head' y define el titulo
que aparecera en la pestaña del navegador
- '<body></body>' -


## Estructura de contenido semantico (secciones principales)

# Estructura de contenido semántico 

## Descripción
La **estructura semántica** en HTML5 organiza el contenido de una página web usando etiquetas que tienen un significado específico.  
Esto ayuda a que el código sea más claro y accesible, tanto para desarrolladores como para navegadores y buscadores.

## Secciones principales

- **`<header>`** → Encabezado de la página. Contiene el título, logo o menú principal.  
- **`<nav>`** → Barra de navegación con enlaces a otras secciones o páginas.  
- **`<main>`** → Contenido principal único de la página.  
- **`<section>`** → Agrupa bloques temáticos (ejemplo: noticias, artículos, productos).  
- **`<article>`** → Contenido independiente dentro de una sección (ejemplo: un post o noticia).  
- **`<aside>`** → Información secundaria o complementaria (ejemplo: publicidad, enlaces relacionados).  
- **`<footer>`** → Pie de página con créditos, contacto o enlaces finales.

## Objetivo
Explicar cómo se organiza un documento HTML5 de manera semántica, identificando las **secciones principales** que se deben usar en un proyecto.




 ## ESTRUCTURA DE TEXTO
 ### jerarquia de encabezados
 descripcion
 ejemplo
 '''html
 <|--el html de ejemplo-->
 '''
 ### parrafos y enfasis
<p>Este es un párrafo normal.</p>
<p><strong>Texto en negrita</strong> y <em>texto en cursiva</em>.</p>

 ### lsita
 <ul>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
</ul>

<ol>
  <li>Paso 1</li>
  <li>Paso 2</li>
</ol>

 ### citas y referencias
<blockquote>"La práctica hace al maestro."</blockquote>
<cite>Autor desconocido</cite>

 ### codigo y texto tecnico
 <code>&lt;h1&gt;Hola mundo&lt;/h1&gt;</code>

 ### lineas y saltos
<hr>
<p>Texto antes del salto<br>Texto después del salto</p>

 #### ejemplo practico que  contenga todos antterios
ejemplo practico que contenga todo anterios
en carpeta raiz crearan una carpeta de nombre ejercicio_01 dentro de la carpeta crearan el archivo index.html dentro de este archivo aran el ejemplo practico integrador (que tendra todas etiquetas trabajas hasta el momento)