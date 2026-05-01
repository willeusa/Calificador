# **📊 Calificador Automatizado \- Odoo ERP (Sprint UD7)**

Una herramienta de calificación ágil, visual y automatizada construida con React (encapsulada en un único archivo HTML). Diseñada específicamente para facilitar la evaluación de las prácticas de despliegue, configuración y extracción de datos en sistemas ERP/CRM (Odoo) en los Ciclos Formativos de Grado Superior de **Desarrollo de Aplicaciones Web (DAW)** y **Desarrollo de Aplicaciones Multiplataforma (DAM)**.

## **🎯 Contexto Académico**

Esta herramienta está parametrizada para evaluar el **Resultado de Aprendizaje 7 (RA7)** del módulo profesional *Lenguajes de Marcas y Sistemas de Gestión de Información*, que establece:

*"Opera sistemas empresariales de gestión de información realizando tareas de importación, integración, aseguramiento y extracción de la información."*

Se evalúan tres criterios de evaluación (CE) clave mediante una rúbrica integrada de cuatro niveles (Excelente, Adecuado, En Desarrollo, Insuficiente):

* **CE b:** Integración de módulos y componentes.  
* **CE g:** Elaboración y modificación de informes (XML/QWeb).  
* **CE h:** Procedimientos de extracción de información (Exportación CSV).

## **✨ Características Principales**

* **Cero Configuración (Plug & Play):** No requiere npm install, ni Node.js, ni servidores. Es un único archivo calificador.html que compila React en tiempo real en el navegador gracias a Babel standalone.  
* **Cálculo Automático:** Asigna pesos automáticos a las decisiones de la rúbrica y calcula la nota media al instante.  
* **Privacidad por Diseño:** Los datos se guardan en la memoria temporal del navegador. No hay bases de datos externas, cumpliendo estrictamente con la protección de datos del alumnado.  
* **Exportación CSV:** Permite descargar un archivo .csv con todas las calificaciones del grupo al finalizar la sesión, listo para ser importado en cuadernos de notas o plataformas LMS como Google Classroom o Moodle.  
* **Diseño Responsivo y Moderno:** Interfaz de usuario limpia e intuitiva construida con Tailwind CSS.

## **🚀 Cómo Empezar**

El uso de esta herramienta está pensado para ser lo más rápido posible durante el transcurso de una clase práctica:

1. **Descargar:** Clona este repositorio o descarga directamente el archivo calificador.html.  
2. **Ejecutar:** Haz doble clic sobre el archivo calificador.html para abrirlo en cualquier navegador web moderno (Chrome, Firefox, Edge). *Es necesaria conexión a internet la primera vez para cargar las librerías CDN.*  
3. **Evaluar:** \* Introduce el nombre del alumno/a.  
   * Haz clic en el nivel alcanzado para cada uno de los 3 criterios.  
   * Visualiza la calificación generada y pulsa **"Guardar Calificación"**.  
4. **Exportar:** Una vez finalizada la evaluación de todo el grupo, pulsa el botón **"Exportar"** en el panel de registro para descargar el listado completo en tu disco duro.

## **🛠️ Stack Tecnológico**

A pesar de ser un único archivo HTML, bajo el capó utiliza tecnologías modernas servidas a través de CDN:

* [React 18](https://reactjs.org/) \- Librería UI (Hooks: useState, useMemo, useEffect).  
* [Tailwind CSS](https://tailwindcss.com/) \- Framework CSS de utilidades para el diseño.  
* [Babel Standalone](https://babeljs.io/docs/babel-standalone) \- Para compilar el código JSX directamente en el navegador.  
* [Lucide Icons](https://lucide.dev/) \- Paquete de iconos SVG limpios y ligeros.

## **👨‍🏫 Autor y Licencia**

Creado para optimizar la labor docente en los ciclos de la familia profesional de Informática y Comunicaciones (IFC). Siéntete libre de hacer un *fork*, modificar los pesos de la rúbrica o adaptar los criterios a tus propias Unidades Didácticas.