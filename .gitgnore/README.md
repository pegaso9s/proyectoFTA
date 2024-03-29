# Aplicativo de Diagramas de Árbol de Fallas (FTA) para la Fabricación de Productos Aeronáuticos / voy a subirlo asi pero sigo haciendo modificaciones entre hoy y mañana solo mientras vos los revisas

Este repositorio contiene el código fuente y la documentación del aplicativo web que permite realizar diagramas de árbol de fallas (FTA) en la fabricación de productos aeronáuticos de la Fuerza Aérea Colombiana.

## Descripción

El aplicativo FTA es una herramienta diseñada para asistir en el análisis de riesgos y la identificación de las causas raíz de fallas potenciales en la fabricación de productos aeronáuticos. Permite a los usuarios crear, editar y visualizar diagramas de árbol de fallas de manera intuitiva y eficiente.

## Requisitos previos

Antes de clonar y ejecutar el proyecto, asegúrate de tener instalado lo siguiente en tu sistema:

- Visual Studio Code
- PHP
- MySQL
- Git

## Clonación del repositorio

Para clonar este repositorio en tu máquina local, sigue estos pasos:

1. Abre una terminal o línea de comandos.
2. Navega hasta el directorio donde deseas clonar el repositorio.
3. Ejecuta el siguiente comando:

   ```
   git clone https://github.com/fac/aplicativo-fta.git
   ```

4. Espera a que se complete la clonación del repositorio.

## Configuración del proyecto

Una vez clonado el repositorio, sigue estos pasos para configurar el proyecto:

1. Abre Visual Studio Code.
2. Ve a "File" (Archivo) y selecciona "Open Folder" (Abrir carpeta).
3. Navega hasta el directorio del proyecto clonado y haz clic en "Select Folder" (Seleccionar carpeta).
4. Configura la conexión a la base de datos MySQL:
   - Abre el archivo `config.php` en la carpeta `backend/`.
   - Modifica los valores de `$servername`, `$username`, `$password` y `$dbname` según tu configuración de MySQL.

## Ejecución del proyecto

Para ejecutar el aplicativo FTA, sigue estos pasos:

1. Inicia tu servidor web local (por ejemplo, Apache).
2. Asegúrate de que MySQL esté en ejecución.
3. Abre un navegador web y visita `http://localhost/aplicativo-fta` para acceder al aplicativo FTA.

## Documentación adicional

Para obtener más información sobre el uso y la funcionalidad del aplicativo FTA, consulta la documentación adicional en la carpeta `docs/`:

- `docs/user-manual/`: Manual de usuario para el aplicativo FTA.
- `docs/architecture-diagram.md`: Diagrama de arquitectura del proyecto.

## Contribución

Si deseas contribuir a este proyecto, por favor lee las pautas de contribución en `CONTRIBUTING.md` antes de enviar un pull request.

## Licencia

Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo `LICENSE` para obtener más información.

---

Si tienes alguna pregunta o problema al configurar o ejecutar el aplicativo FTA, no dudes en abrir un issue en este repositorio. ¡Gracias por tu interés en nuestro proyecto!