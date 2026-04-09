# CyberGuard Solutions - Solemne 01

## 👥 Integrantes
* Constanza Araya
* Andrés Leiva

## 📄 Descripción del Proyecto
Micrositio corporativo desarrollado para **CyberGuard Solutions**, una firma ficticia especializada en consultoría de ciberseguridad. El sitio presenta un diseño moderno (Dark Mode tecnológico), manteniendo coherencia visual en todas sus vistas mediante el uso de CSS nativo organizado. El proyecto cumple con la lógica de diseño responsivo y la integración de componentes de Bootstrap 5 en áreas interactivas.

## 🗺️ Listado de Páginas (7 Vistas)
1. `index.html` - Inicio y presentación general.
2. `nosotros.html` - Descripción de la firma y metodología.
3. `servicios.html` - Catálogo de servicios de seguridad.
4. `equipo.html` - Perfiles de nuestros expertos.
5. `recursos.html` - Casos de éxito y resoluciones (Desarrollado con **Bootstrap**).
6. `contacto.html` - Formulario de solicitud de auditoría (Desarrollado con **Bootstrap**).
7. `faq.html` - Preguntas frecuentes (Uso de HTML5 semántico con `<details>`).

## 🧩 Componentes Principales de Interfaz Utilizados
Siguiendo la clasificación vista en clases, se implementaron los siguientes componentes:
* **Navegación:** Menú principal (Navbar) coherente en las 7 páginas.
* **Contenido:** Cards (`.card` de Bootstrap en Recursos y `.info-card` nativo en el resto), Acordeones nativos HTML5 (`<details>` en FAQ).
* **Interacción:** Formulario de contacto (`.form-control`, `.form-select`), Modales emergentes (`.modal` en Casos de Éxito), Botones (`.btn`).
* **Feedback:** Alertas visuales (`.alert` en Contacto), Badges identificadores (`.badge` en Recursos), validaciones visuales de enlaces activos (`:hover` y `.active`).

## 🐳 Instrucciones para Ejecutar con Docker
Este proyecto está preparado para desplegarse fácilmente usando un contenedor Nginx. 
Para levantar el sitio en un entorno local, ejecutar en la terminal desde la raíz del proyecto:

1. Construir la imagen de Docker:
   ```bash
   docker build -t cyberguard-web .
