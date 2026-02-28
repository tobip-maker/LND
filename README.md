URL del hosting: https://github.com/tobip-maker/AE6.1_Byron_LorenzoSanJuan?tab=readme-ov-file

URL de enlace directo a la página: https://tobip-maker.github.io/AE6.1_Byron_LorenzoSanJuan/

🔹 Organización de estilos

Cada página HTML enlaza:

Un CSS genérico (generico.css), que contiene:

Reset de márgenes y padding

Configuración global

Estilos comunes (cabecera, títulos, estructura base)

Un CSS propio de cada página, que define:

Distribución específica

Componentes exclusivos

Ajustes visuales particulares

Un CSS específico para el footer (footer.css), compartido por todas las páginas.

Esta separación permite:

Mejor mantenimiento

Escalabilidad futura

Mayor claridad estructural

Reutilización de estilos comunes

2. Navegación del sitio

El sitio cuenta con una navegación superior fija en todas las páginas, compuesta por:

Logo corporativo

Nombre de la marca

Menú principal con enlaces a:

Inicio

Sobre Nosotros

Cursos

Tienda

Contacto

La navegación es completamente funcional y permite desplazarse entre páginas de forma intuitiva.

3. Diseño y comportamiento responsive

El proyecto ha sido desarrollado con un enfoque responsive, lo que significa que:

La web se adapta automáticamente al tamaño de la ventana.

No aparecen barras de desplazamiento horizontales.

Las imágenes principales utilizan object-fit: cover para evitar deformaciones.

El texto superpuesto en la página principal escala dinámicamente mediante clamp().

El diseño mantiene coherencia visual tanto en pantalla completa como en ventana reducida.

4. Página principal (Inicio)

La página de inicio incorpora:

Una sección tipo hero adaptable al alto de la pantalla.

Imagen principal escalable.

Texto superpuesto dinámico que mantiene proporción visual.

Diseño sin scroll innecesario.

Esto garantiza una primera impresión visual impactante y profesional.

5. Página de Contacto

La sección de contacto está estructurada en dos columnas:

Columna izquierda:

Texto informativo

Datos de contacto

Bloque de redes sociales con disposición circular alrededor del logotipo

Columna derecha:

Formulario funcional con:

Campos validados

Checkbox obligatorio para aceptar condiciones

Botón de envío estilizado

El formulario está correctamente estructurado semánticamente y preparado para futura integración backend.

6. Footer

El pie de página incluye:

Secciones organizadas por categorías

Enlaces informativos

Iconos de redes sociales 

Diseño coherente con la identidad visual del sitio

El footer está preparado para permanecer correctamente posicionado incluso en páginas con poco contenido.

7. Aspectos técnicos relevantes

Uso de box-sizing: border-box para control preciso del layout.

Eliminación de márgenes por defecto del navegador.

Control del overflow horizontal.

Separación de responsabilidades en CSS.

Estructura HTML limpia y semántica.

8. Posibilidades de ampliación futura

El proyecto está preparado para:

Integración con base de datos.

Conexión con backend (PHP, Node, etc.).

Implementación de sistema de usuarios.

Añadir animaciones o mejoras visuales.

Adaptación completa a dispositivos móviles.

9. Recomendaciones para el cliente

Mantener organizada la estructura de carpetas.

No mezclar estilos específicos en el archivo genérico.

Optimizar imágenes antes de subirlas al servidor.

Revisar enlaces periódicamente.

Implementar certificado SSL en producción
