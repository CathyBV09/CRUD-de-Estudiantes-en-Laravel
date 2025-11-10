## Ejercicio: CRUD de Gestión Académica

Nombre: Brenda Buenrostro Valencia 

Número de Control: 23150310

Materia: Programacion Web 

## 📌 Descripción

Este proyecto es un sistema CRUD (Create, Read, Update, Delete) completo desarrollado en el framework Laravel. Su propósito es gestionar la información académica de los estudiantes, permitiendo:

Registrar nuevos estudiantes (Crear).
Visualizar el listado completo de estudiantes y sus datos asociados (Leer).
Modificar la información de un estudiante existente (Actualizar).
Eliminar registros de estudiantes (Eliminar).

El sistema maneja dos entidades principales: Estudiantes y Carreras, estableciendo una relación para que cada estudiante esté asociado a una única carrera.

## 🚀 Tecnologías utilizadas
Framework: Laravel (PHP)

Base de Datos: SQLite (configuración inicial) / MySQL (Producción)

Frontend/Estilos: Blade Templates y Tailwind CSS

Manejo de Datos: Eloquent ORM


## 🔗 Enlace al proyecto
Repositorio en GitHub: https://github.com/CathyBV09/CRUD-de-estudiantes

Deploy: https://github.com/CathyBV09/CRUD-de-estudiantes

## 📝 Reflexión Personal
Este proyecto representó una inmersión completa en el flujo de trabajo MVC de Laravel, con un enfoque principal en la creación de formularios de edición robustos. El aprendizaje clave fue la gestión crítica de rutas, donde la resolución de un error '404 Not Found' demostró la necesidad imperativa de usar el helper route() en lugar de rutas manuales para garantizar la correcta conexión con el método update del controlador.Un pilar técnico fue dominar la sintaxis del helper old('campo', $valor_existente). Esta técnica de doble argumento es esencial, ya que no solo pre-carga los datos existentes al editar, sino que también garantiza la persistencia de los datos ingresados por el usuario si la validación del servidor falla, mejorando significativamente la usabilidad. Finalmente, la integración de Tailwind CSS fue crucial para la experiencia de usuario (UX), permitiendo desarrollar una interfaz limpia, moderna y completamente responsive. Esto optimizó el diseño, enfocándose en la usabilidad y la alineación precisa de elementos sin recurrir a archivos CSS separados.