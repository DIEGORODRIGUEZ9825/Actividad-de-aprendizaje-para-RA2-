El dashboard de Autos DARM fue diseñado como un sistema administrativo para un concesionario de automóviles.
Su propósito principal es ofrecer a los administradores y empleados una vista centralizada de la información más relevante del negocio, como inventario de vehículos, ventas, clientes y estadísticas de desempeño.

El diseño incluye:

Una barra lateral de navegación con accesos rápidos a las secciones principales (Inventario, Ventas, Clientes, Reportes).

Un header superior con título de la aplicación y accesos rápidos.

Un área principal con tarjetas de resumen que muestran indicadores claves (ej. autos vendidos, autos en stock, ingresos).

Una tabla de datos para gestionar información de autos disponibles.

Un footer informativo con datos legales y de contacto de la empresa.

⚙️ Tecnologías Usadas

HTML5 → estructura semántica del dashboard.

CSS3 (Grid + Flexbox) → distribución del layout, diseño responsivo y efectos visuales.

JavaScript (básico) → interactividad para menús y transiciones.

Variables CSS (custom properties) → manejo centralizado de colores y fuentes.
Decisiones de Diseño y Accesibilidad

Colores llamativos y contrastados: se usaron paletas que resaltan los indicadores clave sin perder legibilidad.

Distribución con CSS Grid: garantiza una organización clara de sidebar, header, main y footer.

Flexbox interno: usado en tarjetas, tabla y menús para mantener alineación y adaptabilidad.

Transiciones y pseudo-clases (:hover, :focus): añaden interactividad al pasar el ratón o navegar con teclado.

Responsividad: media queries permiten que el dashboard sea usable en escritorio, tablet y móvil.

Accesibilidad ARIA: se usaron roles (role="navigation", role="main", etc.) y alt en imágenes para usuarios con lectores de pantalla.

Navegación por teclado: todos los elementos son accesibles mediante tabulación.
