# Django CRUD Application

## Descripción

Este es un proyecto de aplicación CRUD (Crear, Leer, Actualizar, Eliminar) desarrollado con Django. La aplicación permite a los usuarios gestionar tareas de manera eficiente, incluyendo la creación de nuevas tareas, la visualización de tareas pendientes y completadas, así como la edición y eliminación de tareas existentes.

## Características

- **Registro de Usuarios**: Los usuarios pueden registrarse y crear una cuenta.
- **Inicio de Sesión**: Los usuarios pueden iniciar sesión para acceder a sus tareas.
- **Gestión de Tareas**: Los usuarios pueden crear, ver, actualizar y eliminar tareas.
- **Interfaz Amigable**: La aplicación utiliza Bootstrap para un diseño responsivo y atractivo.

## Requisitos

- Python 3.x
- Django 5.1.4
- PostgreSQL (o cualquier otro sistema de base de datos compatible)
- pip (para instalar dependencias)

## Instalación

1. **Clonar el repositorio**:

   ```bash
   git clone https://github.com/Arlo-O/django-crud.git
   cd django_crud

2. **Crea un entorno virtual (opcional pero recomendado)**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows usa `venv\Scripts\activate`
   
3. **Instalar las dependencias**:
   ```bash
   pip install -r requirements.txt
4. **Configurar la base de datos**:
- Asegúrate de tener PostgreSQL instalado y en funcionamiento.
- Crea una base de datos para la aplicación.
- Actualiza la configuración de la base de datos en settings.py.
5. **Realizar migraciones**:
   ```bash
   python manage.py migrate
6. **Crear un superusuario (opcional)**:
   ```bash
   python manage.py createsuperuser
7. **Ejecutar el servidor**:
   ```bash
   python manage.py runserver
8. **Acceder a la aplicación**:
   Abre tu navegador y ve a http://127.0.0.1:8000/.
## Acceso en línea
La aplicación también está disponible en línea. Puedes acceder a ella a través del siguiente enlace:

[Acceder a la aplicación](https://django-auth-crud-5luv.onrender.com)

## Manual de Usuario

### Funcionalidades de la Aplicación

#### 1. Registro de Usuario

- **Descripción**: Permite a nuevos usuarios crear una cuenta en la aplicación.
- **Cómo usar**:
  - Dirígete a la página de registro (`/signup/`).
  - Completa el formulario con un nombre de usuario y una contraseña.
  - Haz clic en "Sign Up" para crear tu cuenta.

#### 2. Inicio de Sesión

- **Descripción**: Permite a los usuarios registrados acceder a su cuenta.
- **Cómo usar**:
  - Dirígete a la página de inicio de sesión (`/signin/`).
  - Ingresa tu nombre de usuario y contraseña.
  - Haz clic en "Sign In" para acceder a tus tareas.

#### 3. Crear Tarea

- **Descripción**: Permite a los usuarios crear nuevas tareas.
- **Cómo usar**:
  - Una vez que hayas iniciado sesión, dirígete a la página de creación de tareas (`/tasks/create/`).
  - Completa el formulario con el título, descripción y marca si la tarea es importante.
  - Haz clic en "Save" para guardar la tarea.

#### 4. Ver Tareas Pendientes

- **Descripción**: Muestra una lista de todas las tareas pendientes del usuario.
- **Cómo usar**:
  - Después de iniciar sesión, dirígete a la página de tareas (`/tasks/`).
  - Verás una lista de tus tareas pendientes.

#### 5. Ver Detalle de Tarea

- **Descripción**: Permite ver los detalles de una tarea específica.
- **Cómo usar**:
  - En la lista de tareas, haz clic en el título de la tarea que deseas ver.
  - Se abrirá una página con los detalles de la tarea y opciones para actualizar o completar la tarea.

#### 6. Actualizar Tarea

- **Descripción**: Permite a los usuarios editar los detalles de una tarea existente.
- **Cómo usar**:
  - Ve al detalle de la tarea que deseas actualizar.
  - Realiza los cambios necesarios en el formulario.
  - Haz clic en "Update" para guardar los cambios.

#### 7. Completar Tarea

- **Descripción**: Marca una tarea como completada.
- **Cómo usar**:
  - Ve al detalle de la tarea que deseas completar.
  - Haz clic en el botón "Complete" para marcar la tarea como completada.

#### 8. Eliminar Tarea

- **Descripción**: Permite a los usuarios eliminar una tarea existente.
- **Cómo usar**:
  - Ve al detalle de la tarea que deseas eliminar.
  - Haz clic en el botón "Delete" para eliminar la tarea.
  - Confirma la acción si se te solicita.

#### 9. Ver Tareas Completadas

- **Descripción**: Muestra una lista de todas las tareas que han sido completadas por el usuario.
- **Cómo usar**:
  - Después de iniciar sesión, dirígete a la página de tareas completadas (`/tasksCompleted/`).
  - Verás una lista de tus tareas completadas.

## Contribuciones

Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-caracteristica`).
3. Realiza tus cambios y haz commit (`git commit -m 'Añadir nueva característica'`).
4. Haz push a la rama (`git push origin feature/nueva-caracteristica`).
5. Abre un Pull Request.

## Autores ✒️
* **Arlo Ocampo** - [Arlo-O](https://github.com/Arlo-O)
