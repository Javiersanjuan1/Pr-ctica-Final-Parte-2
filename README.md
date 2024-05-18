# Pr-ctica-Final-Parte-2
Memoria: Aplicación de Gestión de Cultivos de Bacterias
Nombre del Alumno:F.Javier San Juan Patrón
Análisis y Descripción de la Aplicación
Organización y Estructuración de Clases
La aplicación está organizada en tres clases principales: GestionCultivosDeBacterias, Experimento, y PoblacionDeBacterias.

GestionCultivosDeBacterias: Esta clase es la interfaz principal de la aplicación y se encarga de manejar la interfaz de usuario, incluyendo la ventana principal, menús, botones y paneles. También coordina las acciones del usuario con la lógica de negocio de la aplicación.

Experimento: Representa un experimento completo de cultivo de bacterias. Contiene una lista de PoblacionDeBacterias y métodos para agregar, eliminar y obtener información sobre las poblaciones.

PoblacionDeBacterias: Representa una población específica de bacterias en un experimento. Contiene información sobre el nombre, número inicial de bacterias, duración del experimento, patrón de comida, y fecha de creación. También realiza simulaciones de crecimiento de bacterias.

Decisiones de Diseño
Se utilizó el patrón Modelo-Vista-Controlador (MVC) para separar la lógica de presentación de la lógica de negocio.
Se optó por una interfaz de usuario basada en Swing para una experiencia de usuario intuitiva y fácil de usar.
Se implementó la serialización de objetos para guardar y cargar experimentos desde archivos.
Comprobaciones de Integridad y Excepciones
Se implementaron comprobaciones para evitar operaciones inválidas, como crear un experimento sin nombre o con duración negativa.
Se manejan excepciones relacionadas con la lectura y escritura de archivos, así como errores en la simulación de bacterias.
Estructuras de Datos Utilizadas
Se utilizan listas para almacenar poblaciones de bacterias en un experimento.
Se emplean matrices tridimensionales para representar la distribución de bacterias en un plato de cultivo a lo largo del tiempo.
Técnicas de Ordenación y Búsqueda
No se implementaron técnicas de ordenación y búsqueda, ya que no son necesarias para la funcionalidad principal de la aplicación.
Diagramas de Clases UML
Se adjuntan los diagramas de clases UML que representan la estructura y relaciones entre las clases GestionCultivosDeBacterias, Experimento, y PoblacionDeBacterias.

