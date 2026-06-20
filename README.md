# Mi Proyecto: Portal Web Oficial - Clase 1114

¡Holi! Este es mi repositorio para el **Portal Web de la Clase 1114**. En este proyecto estoy construyendo paso a paso un entorno web interactivo utilizando **Python y Flask**, aplicando los conceptos aprendidos en clase a lo largo de 8 tareas prácticas.

El portal permite a estudiantes y profesores gestionar información académica, tareas, calificaciones y recursos en un solo lugar, simulando un sistema escolar real.

---

##  Información de la Estudiante
* **Nombre:** Luna Castro
* **Sección:** Clase 1114
* **Profesor:** Henry Ortegon

---

##  Progreso del Proyecto (Las 8 Tareas)
Aquí detallo los módulos y conceptos que voy desarrollando paso a paso en este repositorio:

- [ ] **Tarea 1:** Configuración inicial de Flask, creación de rutas básicas y plantillas iniciales.
- [ ] **Tarea 2:** Uso de Jinja2 para enviar y renderizar datos dinámicos en las vistas.
- [ ] **Tarea 3:** Diseño de múltiples páginas y barra de navegación interactiva (Navbar).
- [ ] **Tarea 4:** Implementación de bucles en HTML para mostrar listas de tareas y recursos.
- [ ] **Tarea 5:** Creación y procesamiento del Formulario de Inscripción para nuevos alumnos.
- [ ] **Tarea 6:** Conexión a la base de datos SQLite para registrar y persistir a los estudiantes.
- [ ] **Tarea 7:** Sistema de autenticación (Login), manejo de sesiones de usuario y control de roles.
- [ ] **Tarea 8:** Desarrollo del panel CRUD completo para que el profesor gestione las tareas académicas.

---

## Características que incluye mi Portal

###  Para la Comunidad de la Clase
* **Página de Inicio:** Información general de la materia y acceso rápido a recursos.
* **Formulario de Inscripción:** Sistema dinámico para que los estudiantes se registren.
* **Sistema de Roles:** Acceso diferenciado con Login para Profesor y Login para Estudiante.

###  Módulo del Profesor (Panel de Control)
* Vista de la base de datos con todos los estudiantes inscritos.
* Herramientas CRUD para crear, editar y eliminar tareas académicas de forma dinámica.

###  Módulo del Estudiante (Mi Panel)
* Vista personalizada con las tareas asignadas por el profesor, recursos y notas.

---

## 🛠️ Tecnologías y Requisitos Utilizados
* **Lenguaje:** Python 3.8+
* **Backend:** Flask Framework & Jinja2 (Plantillas)
* **Base de Datos:** SQLite
* **Frontend:** HTML5, CSS3
* **Entorno de desarrollo:** [Menciona aquí tu editor, ej: VS Code, PyCharm, etc.]

---

##  Cómo ejecutar mi proyecto localmente

Para que el profesor o mis compañeros puedan probar mi código, deben seguir estos pasos:

1. **Clonar este repositorio:**
   ```bash
   git clone https://github.com
   cd tu-repositorio
   ```

2. **Crear y activar un entorno virtual (Opcional pero recomendado):**
   ```bash
   python -m venv venv
   # En Windows:
   .\venv\Scripts\activate
   # En Mac/Linux:
   source venv/bin/activate
   ```

3. **Instalar Flask:**
   ```bash
   pip install Flask
   ```

4. **Correr el servidor local:**
   ```bash
   python app.py
   ```
   *Luego, abrir en el navegador la dirección: `http://127.0.0.1:5000`*
