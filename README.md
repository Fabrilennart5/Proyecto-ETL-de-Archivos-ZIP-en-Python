# Proyecto ETL 🚀

Este proyecto se enfoca en realizar un proceso ETL (Extract, Transform, Load), que abarca la extracción de datos desde una fuente web, su transformación mediante la biblioteca pandas y la carga de estos datos en una base de datos PostgreSQL.

## Descripción 📝

El proceso ETL es fundamental en la gestión de datos, ya que permite la recopilación, limpieza y almacenamiento eficiente de información. En este proyecto, realizamos las siguientes etapas:

### Paso 1: Descarga del Archivo ZIP 📥

En esta fase, descargamos un archivo ZIP desde una fuente web. Esto se logra mediante la biblioteca `requests`. Aquí es donde comienza nuestro viaje de ETL.

### Paso 2: Transformación de Datos 🔄

Una vez que tenemos el archivo ZIP, utilizamos la potente biblioteca pandas para realizar transformaciones en los datos. Esto puede incluir cambiar formatos, eliminar valores nulos o modificar columnas según nuestras necesidades.

### Paso 3: Carga en la Base de Datos 📊

En esta etapa, creamos una base de datos PostgreSQL y luego cargamos los datos transformados en ella. La conexión a la base de datos se logra mediante la biblioteca `psycopg2` y la librería `sqlalchemy`.

## Ejecución 🏃‍♀️

El proyecto está dividido en bloques de código, que puedes encontrar en el código fuente. Para ejecutarlo en tu propio entorno, asegúrate de tener todas las bibliotecas necesarias instaladas.

## Requisitos 📦

Asegúrate de tener las siguientes bibliotecas instaladas:

- `requests`
- `pandas`
- `psycopg2`
- `sqlalchemy`

## Contribuir 💡

Si deseas contribuir a este proyecto, ¡estoy abierto a sugerencias! Siéntete libre de hacer un fork del repositorio, implementar mejoras y crear una solicitud de extracción.

## Licencia 📜

Este proyecto está bajo la licencia Apache 2.0, lo que significa que puedes utilizar, modificar y distribuir el código libremente. Consulta el archivo [LICENSE](LICENSE) para obtener más información.

## Autor ✍️

- Fabricio Lennart Flores Ledezma
- [Mi perfil de GitHub](https://github.com/Fabrilennart5)

## Información Adicional 📖

Puedes encontrar más información en mi [perfil de enlace](https://linktr.ee/fabriciolennart).