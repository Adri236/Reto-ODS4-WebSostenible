## 2. Arquitectura de la Solución Web (Responsable: Alumno B)

### Funcionalidades Principales
1. **Repositorio de Apuntes Ligeros:** Subida y lectura de apuntes en formato texto plano o Markdown para evitar PDFs pesados y ahorrar datos.
2. **Foro de Dudas Diferido:** Sistema básico de preguntas y respuestas donde los alumnos se ayudan mutuamente consumiendo el mínimo ancho de banda.
3. **Modo "Cero Distracciones":** Interfaz minimalista que oculta menús innecesarios para facilitar la concentración y reducir la carga visual.

### Entidades de Datos Básicas
| Entidad | Descripción | Ejemplo de datos a guardar |
|---|---|---|
| Usuarios | Personas registradas en la plataforma. | ID_Usuario, Nombre, Email, Contraseña, Rol (Profe/Alumno). |
| Apuntes | Documentos de texto compartidos. | ID_Apunte, Título, Contenido_Texto, Fecha, ID_Autor. |
| Dudas | Preguntas del foro. | ID_Duda, Texto_Pregunta, Fecha, ID_Usuario, Resuelta (Sí/No). |
