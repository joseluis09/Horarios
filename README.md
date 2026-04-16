🕒 Control de Turnos
Una aplicación web progresiva y minimalista diseñada para la gestión visual de turnos del personal de monitoreo y análisis. Optimizado para ofrecer una experiencia fluida tanto en escritorio como en dispositivos móviles, permitiendo conocer el estado del personal en tiempo real.

✨ Características Principales
Estado en Tiempo Real: Identifica automáticamente quién está en turno activo, quién entrará próximamente y quién está libre.

Vista de Calendario Mensual: Tabla interactiva con resaltado de filas para un seguimiento detallado de todo el personal durante el mes de abril.

Desglose de Horas Nocturnas: Sistema inteligente que calcula automáticamente las horas laboradas en horario nocturno (19:00 - 06:00), divididas por quincenas.

Modo Oscuro/Claro: Interfaz adaptable según la preferencia del usuario.

Slider Automático: Panel informativo que alterna entre los detalles del día de hoy y la programación de mañana.

Filtro por Roles: Capacidad de filtrar la vista entre Técnicos de Monitoreo y Analistas de Comportamiento.

Diseño Responsive: Basado en la fuente Inter con un estilo moderno tipo "Dashboard".

🛠️ Tecnologías Utilizadas
Frontend: HTML5 semántico.

Estilos: CSS3 utilizando Variables CSS para temas dinámicos, Flexbox y Grid Layout para la estructura.

Lógica: JavaScript (Vanilla JS) para el procesamiento de fechas, cálculos de horas y manipulación del DOM.

Iconografía: Emojis dinámicos y Favicon personalizado.

🚀 Instalación y Uso
Clona el repositorio:

Bash
git clone https://github.com/tu-usuario/control-turnos-telemedicina.git
Abre el proyecto:
Simplemente abre el archivo index.html en cualquier navegador moderno. No requiere dependencias externas ni servidores backend.

📊 Lógica de Negocio (Horas Nocturnas)
El sistema incluye una función crítica para la administración:

Rango Nocturno: 07:00 P.M. a 06:00 A.M.

Cálculo: El script analiza el string de turno (ej. 10:00 P.M. - 06:00 A.M.) y determina cuántas horas caen dentro del rango nocturno para la liquidación de nómina.

📁 Estructura del Código
staff[]: Array de objetos que contiene la base de datos local del personal y sus turnos.

renderApp(): Función principal que orquestal la actualización de la interfaz basada en la hora del sistema.

openIndividual(): Genera un modal con el calendario específico de un colaborador.

toggleHighlightRow(): Mejora la legibilidad en la vista general mediante interacción.

✒️ Créditos
Este proyecto fue desarrollado por:

Jose Rojas - Desarrollo y Lógica 💻

Esaú Aguilar - Control de Calidad (QA) 🧠
