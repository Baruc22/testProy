# testProy
# Sistema de Gestión de Alumnos y Calificaciones

Este es un proyecto de sistema CRUD básico desarrollado como parte de una prueba. El sistema permite a los profesores acceder a su información personal, gestionar el alta de alumnos y asignarles calificaciones, entre otras funcionalidades.

## Características

- Visualización y edición de información personal de los profesores.
- Alta de alumnos en el sistema.
- Asignación y gestión de calificaciones de los alumnos.
- Funcionalidades CRUD básicas para manejar los datos de los alumnos y profesores.

## Tecnologías Utilizadas

- *Frontend*: Angular
- *Backend*: Node.js con TypeScript
- *Base de Datos*: MySQL

## Instalación

Sigue los siguientes pasos para clonar el repositorio y configurar el proyecto en tu máquina local.

### Prerrequisitos

Asegúrate de tener instalado:

- [Node.js](https://nodejs.org/) (versión 18 o superior)
- [Angular CLI](https://angular.io/cli) (versión 16 o superior)
- Base de datos compatible [MySQL](https://www.mysql.com/)
- Gestor de base de datos [phpMyAdmin](https://www.phpmyadmin.net/)

### Clonación del Repositorio

Clona el repositorio en tu máquina local usando el siguiente comando:

```bash
git clone https://github.com/Baruc22/testProy.git
```
### Importación de la Base de Datos

Para importar la base de datos, sube el archivo de la base de datos a tu gestor de base de datos. Este proyecto fue desarrollado usando *MySQL* junto con *phpMyAdmin* para la administración de la base de datos. 

1. Entra a phpMyAdmin o el gestor de tu elección.
2. Crea una nueva base de datos o selecciona una existente.
3. Importa el archivo SQL proporcionado para cargar las tablas y datos iniciales del sistema.

*Nota*: Asegúrate de usar la misma contraseña de tu base de datos en el archivo keys.ts dentro del proyecto cliente. Este archivo contiene las credenciales necesarias para que el sistema se conecte correctamente a la base de datos.


### Intalacion de dependencias

Una vez clonado el repositorio, navega a las carpetas del cliente y del servidor e instala las dependencias necesarias con los siguientes comandos:

1. Backend:
```bash
cd testProy/server
npm install
```
2. Frontend:
```bash
cd testProy/client
npm install
```
### Ejecucion del proyecto (en modo desarrollo)

Para levantar el proyecto sigue estos pasos:

1. Backend:

   Navega a la carperta del servidor y ejecuta los siguientes comandos:
   - Compilación en tiempo real de TypeScript:
     ```bash
     cd testProy/server/src
     tsc -w
     ```
  - Ejecución del servidor (modo desarrollo):
     ```bash
     cd testProy/server/src
     npm run dev
     ```
  Esto iniciará el servidor backend y lo mantendrá en escucha de cualquier cambio.
  
2. Frontend:

   En la carpeta del cliente ejecuta el siguiente comando:
   ```bash
   cd testProy/client
   ng serve
   ```

   Esto iniciará el servidor de Angular para el frontend. Una vez iniciado, puedes acceder a la aplicación en (http://localhost:4200)
