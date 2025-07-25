# Manual de Buenas Prácticas para Trabajos Universitarios en Grupo

## 🎯 Objetivo del Proyecto

Fomentar el uso de Git y GitHub como herramienta de colaboración y control de versiones en la creación de documentos, promoviendo buenas prácticas de trabajo en equipo. Buscamos promover una colaboración fluida y efectiva para garantizar un desarrollo organizado y un historial de cambios transparente.

## 🧩 Descripción del Manual

Este manual recopila buenas prácticas esenciales para la realización de trabajos universitarios en grupo, abarcando temas clave como:

* **Organización del equipo y roles:** Cómo establecer una base sólida para el trabajo grupal.
* **Gestión de tiempos y responsabilidades:** Estrategias para cumplir con plazos y asegurar la participación de todos.
* **Formatos y estilos de documentos:** Unificación de criterios para presentaciones y trabajos escritos.
* **Citación y referencias:** Guías para el uso correcto de fuentes académicas (ej., estilo APA).
* **Preparación de presentaciones orales:** Consejos para exposiciones efectivas.

Este manual se mantendrá y gestionará completamente en un repositorio GitHub, utilizando archivos en formato **Word** para facilitar la edición y el control de versiones.

---

## 🛠️ Estructura del Repositorio

El proyecto se organiza en las siguientes carpetas y archivos principales para mantener la claridad y facilitar la navegación:

* `/documentos`: Contiene el archivo principal del manual (`manual-practicas-universitarias.docx`).
* `/imagenes`: Almacena todas las imágenes, gráficos o diagramas utilizados en el manual.
* `/referencias`: Guarda materiales de consulta, bibliografía o enlaces útiles.
* `CHANGELOG.md`: Registro de los cambios significativos y versiones del manual.
* `README.md`: Descripción general del proyecto, objetivo, estructura y guía de contribución.
* `.gitignore`: Define los archivos y carpetas a ser ignorados por Git.

---

## 👥 Colaboradores

* **Luisiana Carreño**
* **Chrisbel Briceño**

---

## 🚀 Cómo Contribuir (Guía de Colaboración)

Para contribuir al desarrollo de este manual, por favor, sigue estas buenas prácticas de flujo de trabajo con Git y GitHub:

### **1. Configuración Inicial (Solo la primera vez)**

* **Clona el repositorio:**
    ```bash
    git clone [https://github.com/LuisICarre19/Manual-buenas-practicas-universitarias.git](https://github.com/LuisICarre19/Manual-buenas-practicas-universitarias.git)
    cd Manual-buenas-practicas-universitarias
    ```

### **2. Flujo de Trabajo para Nuevas Secciones o Mejoras**

1.  **Asegúrate de tener la última versión de la rama `main`:**
    ```bash
    git checkout main
    git pull origin main
    ```

2.  **Crea una nueva rama para tus cambios:**
    Usa nombres descriptivos para tu rama, siguiendo el formato `feature/nombre-seccion` o `fix/descripcion-corta`.
    ```bash
    git checkout -b feature/nombre-de-tu-rama
    ```
    *(**Ejemplo:** `git checkout -b feature/organizacion-equipo`)*

3.  **Realiza tus modificaciones en el archivo del manual:**
    Trabaja en el archivo principal ubicado en `documentos/manual-practicas-universitarias.docx`.

4.  **Guarda tus cambios y haz `commits` frecuentemente con mensajes claros:**
    Cada `commit` debe representar un cambio lógico y pequeño.
    ```bash
    git add documentos/manual-practicas-universitarias.docx # Asegúrate de que es .docx
    # O para añadir todos los cambios en la carpeta actual:
    # git add .
    git commit -m "feat: Agrega contenido inicial a la sección de organización del equipo"
    ```

5.  **Sube tu rama a GitHub:**
    ```bash
    git push origin nombre-de-tu-rama
    ```

6.  **Crea un Pull Request (PR) en GitHub:**
    * Una vez que hayas subido tu rama, ve a la página del repositorio en GitHub.
    * Verás un aviso para "Compare & pull request". Haz clic ahí.
    * Asegúrate de que el PR vaya de tu rama (`feature/nombre-de-tu-rama`) a `main`.
    * Dale un título claro y una descripción detallada de los cambios.
    * **Asigna revisores** (tus compañeros de grupo) para que revisen tus contribuciones.

7.  **Revisa los Pull Requests de tus compañeros:**
    * Participa activamente en la revisión de los PRs de otros.
    * Ofrece comentarios constructivos y sugiere mejoras directamente en el código o documento.

8.  **Resuelve conflictos (si es necesario):**
    * Si hay conflictos al intentar fusionar un PR (indicado por Git), deberás resolverlos manualmente en tu editor local.
    * Una vez resueltos, haz un nuevo `commit` y `push` a tu rama.

9.  **Fusión del Pull Request:**
    * Una vez que el PR sea aprobado por los revisores y no haya conflictos, se procederá a fusionar la rama a `main`.

---

## 📊 Gestión de Tareas (Project Board & Issues)

Utilizamos el sistema de `Issues` y el `Project Board` de GitHub para organizar y seguir el progreso del proyecto:

* **Issues:** Cada sección del manual o tarea importante tendrá un `Issue` asignado con su respectivo responsable y descripción. Puedes ver la lista de `Issues` [aquí](https://github.com/LuisICarre19/Manual-buenas-practicas-universitarias/issues).
* **Project Board (Kanban):** El tablero de proyecto nos permite visualizar el estado de cada tarea (Pendiente, En Progreso, En Revisión, Completado). Puedes acceder al `Project Board` [aquí](https://github.com/LuisICarre19/Manual-buenas-practicas-universitarias/projects/1).

---

## 🏷️ Control de Versiones del Manual

Para mantener un registro claro del desarrollo del manual, utilizamos:

* **Tags:** Marcamos versiones importantes del manual (ej., `v1.0`) usando `tags` en GitHub.
* **CHANGELOG.md:** Documentamos todos los cambios relevantes y adiciones en este archivo para cada **versión etiquetada y fase de desarrollo importante**.

---

## 📦 Entrega Final

La entrega del proyecto incluirá:

* **Manual en PDF y DOCX:** Una versión final del manual generada a partir del archivo fuente (.docx).
* **Historial de Repositorio Completo:** Un historial de `commits` limpio y claro en GitHub.
* **Tablero de Proyecto Actualizado:** El `Project Board` con todas las tareas completadas y su progreso.