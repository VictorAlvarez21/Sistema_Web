# Sistema Web de Administración de Usuarios

## Descripción

Sistema web desarrollado para administrar usuarios mediante un mecanismo de inicio de sesión y control de acceso basado en roles.

El sistema permite autenticar usuarios y dirigirlos a diferentes paneles dependiendo de los permisos asignados. Además, cuenta con un módulo de administración desde el cual es posible registrar, consultar, modificar y eliminar usuarios.

El proyecto utiliza PHP para el procesamiento del lado del servidor, MySQL para el almacenamiento de información y Bootstrap 5.3.3 para construir una interfaz gráfica sencilla, intuitiva y adaptable a diferentes dispositivos.

## Características principales

### 1. Inicio de sesión
- Autenticación mediante nombre de usuario y contraseña.
- Validación de credenciales.
- Administración de sesiones mediante PHP.
- Redirección automática según el rol del usuario.

### 2. Control de acceso por roles

El sistema cuenta con tres tipos de usuarios:

| Rol | Tipo de usuario | Permisos |
|---|---|---|
| 1 | Administrador | Acceso al panel administrativo y gestión de usuarios. |
| 2 | Maestro | Acceso al panel correspondiente al maestro. |
| 3 | Alumno | Acceso al panel correspondiente al alumno. |

### 3. Administración de usuarios

El administrador puede realizar las siguientes operaciones:

- **Crear:** registrar nuevos usuarios y asignarles un rol.
- **Leer:** consultar los usuarios registrados.
- **Actualizar:** modificar nombres y roles.
- **Eliminar:** eliminar usuarios existentes.

### 4. Seguridad y sesiones
- Verificación de sesiones activas.
- Restricción de páginas según el rol.
- Consultas preparadas para operaciones con datos de usuarios.
- Validación de información recibida mediante formularios.
- Protección para evitar que el administrador elimine su propia cuenta.

## Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| PHP | Lógica del servidor y procesamiento de formularios. |
| MySQL | Administración de la base de datos. |
| HTML5 | Estructura de las páginas web. |
| Bootstrap 5.3.3 | Diseño y estilos de la interfaz. |
| JavaScript | Funcionalidades de los componentes de Bootstrap. |
| Apache | Servidor web local mediante WAMP. |
| phpMyAdmin | Administración e importación de la base de datos. |
