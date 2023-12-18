# SASS, SEO y Hosting
Este es un repo con ejemplos y técnicas de SASS al que le aplicamos técnivas de SEO durante la clase.

## SEO
Search engine optimization: optimización de motor de busqueda. Aumenta la visibilidad de la página web adaptando la aplicación a los motores de búsqueda.


## Técnicas de SEO on-page

### Etiquetas meta
* description: una descripción breve de la página entre 70-160 carácteres, de manera óptima de 155-160 (más carácteres no se terminan mostrando aunque acepta ahsta 320). En sí no afecta el SEO pero atrae a más usuarios.

```html
<meta name="description" content=""> 
```
* keywords: son un conjunto de palabras claves relevantes al buscador con respecto al contenido de la página (no a las tecnologías utilizadas).
```html
<meta name="keywords" content=""> 
```
* favico: generar un favico para su sitio

### Buenas Prácticas
* 1 h1 por .html, ni más ni menos.
* 1-3 h2 por html.
* Que ka etiqueta title sea relevante al html, muchas vexes se aplica la estructura "SitioWeb - Contenido". Se suelen preferir 35-65 carácteres.
* Atributos alt de imágenes. Sin esto no solo el motor de busqueda no puede entender de que son las imágenes sino que los no videntes no podran entender la página.
* Buena navegación interna (que esten todos los html conectados de la mejor manera). Uso del rel="nofollow", rel="sponsored" y rel="ugc" (los rel no los evaluamos). Que los links externos se abran en una pestaña aparte y los internos en la misma pestaña (atributo target).
* Aplicar nav en lugares que sean "centros de navegación" de su página, como menús de navegación.
* Evita cantidad excesiva de carpetas en profundidad (más de 4-5 niveles)
* Buen uso de etiquetas semánticas.
* Minimizar la cantidad de clicks requeridas para navegar/realizar procesos.


### Herramientas externas
* Sitemaps: https://www.xml-sitemaps.com/ . Para generar un sitemap para el motor de búscqueda, requiere de un sitio levantado.
* Resukmen de Coder: https://view.genial.ly/6418742b0823430011938d06
* Contador de carácteres: https://www.charactercountonline.com/

## SEO off-page
* Publicaciónes
* Google my business

## Prolijidad de código
Citando a un amigo mio, la desprolijidad de código lleva a lo siguiente:

"Y despues ((respondiendo a un código desprolijo)) hay q poder modificarlo si es necesario, por ende hay q entenderlo. Ademas tambien si tiene algun fallo, hay q poder arreglarlo, lo cual lleva a lo mismo. Adicionalmente seguro q si esta desprolijo es mas propenso a q te equivoques e introduzcas errores sin darte cuenta."

"Si queres reutilizarlo y no lo entendes, tampoco podes."

"Por culpa de esas cosas, despues tenes sillas q se rompen, q se tambalean, platos q no sirven, tazas q no se pueden usar. Etc."

"Esa misma forma de pensamiento es lo q te lleva a desastres."

## Hosting
Además de google pages, utilicen uno de los siguientes:
* [Filezilla+000webhost](https://docs.google.com/document/d/1Ve2nVq8xJtohinGj32lcG40woa2sqvfFDo1lYYR6rPk/edit): Es un link a una guía paso por paso
* [Vercel](https://vercel.com/): linkeando un repo público a
* [Netlify](https://www.netlify.com/)

### Nivel superior genérico
* com
* net
* org
* edu
* gov

### Nivel inferior genérico
Por ubicación como .ar