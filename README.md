Tienda Virtual

1. Descripción del sistema
Tienda Virtual es un proyecto académico de Ingeniería de Software orientado a organizar la consulta de productos y la gestión de compras mediante un sistema digital.

2. Objetivo
Diseñar y desarrollar un sistema que facilite la consulta de productos y la organización de pedidos, ofreciendo una solución que permita mejorar la gestión de una tienda.

3. Problema que resuelve
La gestión manual de productos y pedidos puede ocasionar pérdida de información, dificultades para consultar los artículos y retrasos en las compras. El sistema busca centralizar esta información y facilitar su administración.

4. Funcionalidades principales
Consulta de productos.
Visualización de información y precios.
Búsqueda de productos.
Carrito de compras.
Registro y seguimiento de pedidos.
Administración de productos.

Nota: las funcionalidades anteriores representan el alcance previsto y deberán verificarse según la implementación real.

5. Arquitectura seleccionada
Se propone una arquitectura cliente-servidor organizada en tres partes: frontend, backend y base de datos.

Frontend
Es la parte visual con la que interactúa el usuario. Presenta los productos, formularios, carrito de compras y la información de los pedidos.

Backend
Es responsable de procesar las solicitudes, validar los datos, aplicar las reglas de negocio y gestionar las operaciones del sistema.

Base de datos
Almacena la información de los usuarios, productos y pedidos, según el diseño definitivo del sistema.

Comunicación entre frontend y backend
El frontend enviará solicitudes al backend mediante una API HTTP. El backend procesará cada solicitud, consultará o actualizará la base de datos y devolverá una respuesta al frontend, preferiblemente en formato JSON.

Flujo: Usuario → Frontend → Backend → Base de datos → Backend → Frontend.

6. Herramientas utilizadas
GitHub para alojar y documentar el proyecto.
Git para el control de versiones.
GitHub Issues para registrar tareas e incidencias.
GitHub Projects para organizar el avance.
UML para modelar los requisitos y la estructura del sistema.
Markdown para la documentación.

7. Estado actual del proyecto
Proyecto académico en etapa inicial de organización documental. La implementación de las funcionalidades deberá verificarse y actualizarse conforme avance el desarrollo.

8. Gestión del proyecto
El seguimiento se realizará mediante GitHub Issues y GitHub Projects, registrando las tareas pendientes, las actividades en progreso y las tareas completadas.

9. Próximos pasos
Documentar los requisitos y modelos UML.
Definir la arquitectura técnica definitiva.
Registrar las tareas e incidencias en GitHub Issues.
Organizar el tablero de GitHub Projects.
Implementar y probar las funcionalidades.
Actualizar la documentación según los avances.
