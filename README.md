# Reto-ODS4-WebSostenible
# Proyecto Web: EcoApuntes - ODS 4
Este proyecto es una propuesta tecnológica para mejorar la calidad educativa (ODS 4) desde la perspectiva del Desarrollo de Aplicaciones Web (DAW).

## 1. Análisis del Problema y Sostenibilidad (Responsable: Alumno A)
### El "Bug" Educativo
> El problema principal en nuestro entorno educativo es el consumo excesivo de papel en fotocopias para apuntes, exámenes impresos y boletines de notas. Esto no solo genera un alto impacto ambiental por la tala de árboles, sino que supone un gasto económico importante.

### Nuestro "Parche" Sostenible
- [ ] Medida 1: Digitalización total de entregas y firmas.
- [ ] Medida 2: Interfaz con modo oscuro nativo para ahorrar batería.
- [ ] Medida 3: Diseño web ultraligero para consumir pocos datos.
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
