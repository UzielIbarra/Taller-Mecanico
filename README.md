Sistema de Gestión de Reparaciones y Contactos
Este proyecto consiste en una aplicación desarrollada en Python diseñada para gestionar registros de usuarios, piezas, reparaciones y contactos a través de una arquitectura modular que separa la lógica de la base de datos de la lógica de negocio.

Estructura del Proyecto
La organización de los archivos sigue una estructura funcional:

app.py / main.py: Puntos de entrada principales de la aplicación.

Módulos de Base de Datos (db...): Manejan la persistencia y conexión:

conexion.py: Configuración de la conexión a la base de datos.

db_reparacion.py, dbPieza.py, dbUsuario.py, dbcontacto.py: Consultas y operaciones CRUD específicas.

Modelos de Negocio:

usuario.py, pieza.py, reparacion.py, contacto.py: Definen las clases y la lógica de los objetos del sistema.

Requisitos Previos
Antes de ejecutar el proyecto, asegúrate de tener instalado:

Python 3.x

Un gestor de base de datos compatible (según lo configurado en conexion.py).

Dependencias adicionales (si existen, se recomienda instalarlas vía pip).

Instalación y Uso
Clonar el repositorio:

Bash
git clone https://github.com/Uziellbarra/nombre-del-repo.git
Configurar la base de datos:
Ajusta las credenciales en el archivo conexion.py.

Ejecutar la aplicación:

Bash
python main.py
Funcionalidades Principales
Gestión de Usuarios: Registro y control de perfiles en el sistema.

Control de Inventario (Piezas): Seguimiento de piezas disponibles para reparaciones.

Registro de Reparaciones: Historial detallado de los trabajos realizados y su estado.

Módulo de Contactos: Administración de información de contacto relacionada con el servicio.

Contribuciones
Para realizar cambios:

Haz un Fork del proyecto.

Crea una nueva rama (git checkout -b feature/NuevaMejora).

Realiza un Commit de tus cambios.

Haz un Push a la rama y abre un Pull Request.
