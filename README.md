
# Aplicación CRUD de PHP

Este repositorio muestra una aplicación PHP CRUD (Create, Read, Update, Delete) que maneja datos de usuarios en una base de datos MySQL. A continuación, detallo los formularios y funcionalidades asociadas:
## Tecnologías Utilizadas

- **PHP**: Lenguaje de servidor para desarrollo web.
**MySQL**: Sistema de gestión de base de datos para almacenamiento de usuarios.
**HTML & CSS**: Estructura y estilo de páginas web.
**Tailwind CSS**: Framework de CSS para interfaces de usuario.
## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

-**Funcionalidad**: Muestra todos los usuarios en una tabla.
**Características**:
**Visualización de usuario**s.
Enlaces para agregar, editar o eliminar usuarios

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad**: Permite agregar un nuevo usuario.
**Características**:
Formulario con campos para datos del usuario.
Validación y almacenamiento en la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

-**Funcionalidad**: Permite editar detalles de usuarios existentes.
**Características**:
Formulario prellenado con información actual.
Actualización de datos en la base de datos..

### 4. Eliminar Usuario (`delete.php`)

**Funcionalidad**: Facilita la eliminación de un usuario.
**Características**:
Eliminación basada en el ID de usuario.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Ejecución
Clona el repositorio en tu máquina local.
Configura entorno PHP y MySQL (como XAMPP).
Crea la base de datos usando phpMyAdmin.
Ejecuta la aplicación en servidor local.

## Nota de Seguridad

Esta aplicación es básica y no incluye medidas avanzadas de seguridad. Se recomienda usar declaraciones preparadas u ORM para evitar ataques de inyección SQL.

¡Siéntete libre de contribuir o sugerir mejoras! Para consultas o problemas, abre un issue en el repositorio.

