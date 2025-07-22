# Guía Interactiva de Diseño Instruccional STEAM (NEM)

## Descripción

Esta es una aplicación web interactiva de una sola página (SPA) diseñada como una herramienta dinámica para educadores, diseñadores instruccionales y líderes de programas educativos. El propósito de esta guía es traducir el "Plan de Estudios para la Educación Preescolar, Primaria y Secundaria" de la Secretaría de Educación Pública de México en un formato accesible e interactivo, facilitando la creación de programas STEAM (Ciencia, Tecnología, Ingeniería, Artes y Matemáticas) que se alineen con el marco curricular de la Nueva Escuela Mexicana (NEM).

La aplicación permite a los usuarios explorar los fundamentos de la NEM, navegar por las distintas fases de aprendizaje, consultar ideas de proyectos y entender la estructura curricular de una manera visual e intuitiva.

## Características Principales

* **Contenido Interactivo:** Transforma un documento PDF denso en una experiencia de usuario navegable y fácil de consumir.
* **Soporte Bilingüe:** Totalmente funcional en **Español** e **Inglés**. La selección de idioma se guarda localmente para futuras visitas.
* **Temas Visuales:** Incluye modos **Claro (Light)**, **Oscuro (Dark)** y **Automático** (se sincroniza con las preferencias del sistema operativo del usuario). La preferencia de tema también se guarda.
* **Navegación Intuitiva:** Una barra lateral fija permite el acceso rápido a todas las secciones principales, mientras que un sistema de pestañas y acordeones organiza el contenido detallado de manera eficiente.
* **Visualización de Datos:** Utiliza Chart.js para presentar la estructura curricular de la NEM (Campos Formativos y Ejes Articuladores) en un gráfico de dona interactivo.
* **Diseño Responsivo:** La interfaz se adapta fluidamente a diferentes tamaños de pantalla, desde dispositivos móviles hasta monitores de escritorio.
* **Cero Dependencias Externas (excepto CDNs):** Construido como un único archivo HTML con Vanilla JavaScript, lo que lo hace extremadamente portátil y fácil de desplegar.

## Cómo Utilizar

1.  **Navegación:** Utilice los enlaces en la barra lateral izquierda para cambiar entre las diferentes secciones de la guía (Introducción, Fundamentos, Detalles Curriculares, Fases, etc.).
2.  **Cambiar Idioma:** En la parte inferior de la barra lateral, utilice el menú desplegable "Idioma" para cambiar entre "Español" e "English". El contenido de toda la página se actualizará instantáneamente.
3.  **Cambiar Tema:** Debajo del selector de idioma, haga clic en los botones "Claro", "Oscuro" o "Auto" para cambiar la apariencia visual del sitio.

## Tecnologías Utilizadas

* HTML5
* Tailwind CSS
* JavaScript (ES6+) (Vanilla)
* Chart.js

## Fuente de Datos

Todo el contenido curricular presentado en esta aplicación se basa en el documento oficial: **"Plan de Estudios para la Educación Preescolar, Primaria y Secundaria"**, emitido por la Secretaría de Educación Pública (SEP) de México.
