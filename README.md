# All in Night para Usuarios - Protipo de UX

El objetivo del repositorio es versionar los diferentes diseños y prototipos desde el punto de vista de UX/UI.
##Flujo de trabajo
El proyecto actualmente cuenta con 2 ramas:

- master: Que es la rama princial del proyecto
- develop: Que es la rama que contiene la última versión estable de desarrollo.

Cuando trabaje en una nueva fucionalidad debe crear un nuevo branch a partir de la rama **develop** con el siguiente nombre:

- feature-MODULO-funcionalidad.
- fix-MODULO-codigoError-funcionalidad

**Explicación:**

- _feature_: Se refiere a una nueva funcionalidad de desarrollo, por ejemplo una nueva pantalla o componente.
- _fix_: Para registrar alguna corrección por algún error detectado durante la fase de pruebas de la entrega.
- _MODULO_: Es el nombre del módulo al que pertenece la branch, por ejemplo: HOME, BUSCAR, CARRITO, PERFIL, etc.
- _funcionalidad_: Breve descripción del cambio, seperado por guiones bajos en vez de espacios.
- _codigoError_: Es el código de error con el que reportamos el error detectado. Lo crea el equipo de All in Night y se le pasa al desarrollador para que lo corrija.

**Ejemplos:**

- feature-HOME-actividades-dirigidas-por-user-id
- fix-HOME-099-se-gira-pantalla-y-queda-al-reves

Cada vez que haga un commit y un push de los archivos debe describir claramente los cambios que hizo.

Cuando se formalice la entrega de la corrección debe generar un Pull Request a la rama develop y avisarle a los integrantes del equipo de All in Night enviando un mail a it@allinnightapp.com o a franco@allinnight.com o dmernies@allinnight.com.

Si la entrega fue satisfactoria el equipo de All in Night realizará el merge a la rama develop y se avisará que la entrega fue satisfactorios.

Si la entrega tuvo fallas el equipo de All in Night creará un documento con los errores reportados y sus respectivos codigos para proceder con la solución de las incidencias.

## Entregas rechazadas

Una entrega se rechaza si:

- El código fuente no es legible o utiliza variables poco apropiadas con nombres como "x" o "y".
- El código fuente no compila o los archivos entreados no se pueden abrir.
- El código compila, pero no se puede probar la aplicación.
- El código compila, se puede ejecutar la aplicación con en emulador, pero no en dispositivos.
