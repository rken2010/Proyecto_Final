# Proyecto Final curso Diseño Web
## Proyecto final CoderHouse para Diseño Web
Este es el trabajo final desarrollado para el curso de Diseño Web en **CoderHouse**

## Desarrollo
El sitio fue desarrollado en **HTML**, aplicando estilos en **SASS** para el diseño. Para el control de versiones se utilizó **Git** y como repositor **GitHub**. Se aplicaron **mediaQueries** para el diseño responsive, como también Bootstrap para el menú.

### Librerias
Se aplico la libreria de **Bootstrap** para la creación del menú hamburguesa responsive, las tarjetas en la sección Marketing y el diseño de botones del sitio.
Se usó **animate.css** para las animaciones aplicadas en el sitio (https://animate.style/)

### Estilos

Los estilos predeterminados de colores y tipografias se establecieron en el index.css con las siguientes variables:

$color_primario:#E69600;  
$color_secundario:#FF5000;  
$color_titulo:#AA1E1E;  
$fuente-titulo:'Special Elite', cursive;  

### Estructura
```mermaid
graph LR
A[Home]  
A --> B(Contacto)-->I(Formulario de contacto estático en HTML y CSS )
A --> C(Marketing)-->H(Pag. de servicios de Marketing Online)
A --> D(Web)-->G(Pag. de servicios de Diseño Web)
A --> E(Portfolio)-->F(cuadricula con imagenes de trabajos)
