# Plantilla de LaTeX para las carátulas de los DT - IECON

Adaptado tomando en cuenta la carátula que estaba en formato de Word

Elaborada por: Juan Ignacio Urruty.

## Objetivos

1) El primer objetivo es brindar una carátula en formato Latex. Esto para que
los trabajos tengan cierta homogeneidad.

2) El segundo objetivo podría ser el de brindar una plantilla más completa. Es
decir, además de la carátula, pensar en un archivo general para estructurar
todo el trabajo.

### Usos de la carátula

- En caso de que solamente quieran usar la carátula. Pueden completar la info
y luego unirla a su pdf. 'Mergeando' los pdf.

- Otra posibilidad es incorporar el código de la plantilla a su documento y
editarlo desde ahi mismo. No se cuán recomendable o práctica puede resultar esta opción.

### Tutorial sobre el uso

- Pueden encontrar un breve tutorial sobre cómo bajar el repositorio y hacerlo funcionar en Overleaf o un editor de Latex local como puede ser Texmaker: [Tutorial](https://fcea.udelar.edu.uy/images/micrositios/programa_posgrados/maestria_economia/2023/Tutorial_plantilla_latex.pdf)

- Luego de tener acceso al archivo .tex, deben leer los comentarios del documento. Tienen que editar la información respecto de autoras/es, título del trabajo, resumen y abstract.

- **Importante:** la página donde aparece el resumen-abstract ya cuenta comienza con la numeración de las páginas, es decir, esa tiene que ser la página 1 del trabajo. En caso de que quieran usar la carátula uniendo dos pdf deben poner que en el otro pdf la numeración comience en la página 2.

- Esto se puede hacer de la siguiente manera. Se agrega esta línea en donde comience la primera página del otro documento: 

- \setcounter{page}{2}
