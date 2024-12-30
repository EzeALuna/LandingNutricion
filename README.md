# Nutrición - Reserva tu Consulta
Este proyecto es una página web estática diseñada para un sitio de nutrición, donde los usuarios pueden reservar una consulta fácilmente. La página incluye un formulario de reservas, secciones informativas y enlaces a redes sociales.

## Tecnologías utilizadas
- **HTML5**: Estructura principal de la página.
- **CSS3**: Estilo visual y diseño responsivo.
- **JavaScript**: Funcionalidades interactivas como animaciones y scroll suave.
- **Formspree**: Manejo del formulario de contacto.
- **Font Awesome**: Iconos para enriquecer la interfaz de usuario.

## Características
### 1. Encabezado
- Logo del sitio.
- Menú de navegación con enlaces anclados para un scroll suave hacia las secciones de la página.

### 2. Hero (Sección principal)
- Título llamativo con un mensaje inspirador.
- Botón de llamado a la acción que dirige al formulario de reservas.

### 3. Beneficios
- Tres tarjetas destacando los beneficios del servicio de nutrición.
- Animaciones que se activan al hacer scroll.

### 4. Formulario de Reservas
- Recoge información básica del usuario:
  - Nombre completo
  - Correo electrónico
  - Teléfono
  - Fecha y hora de la consulta
- Validación básica de campos requerida.
- Utiliza Formspree para manejar las reservas.

### 5. Footer
- Enlaces a redes sociales: WhatsApp, Facebook e Instagram.

## Personalización
### Cambiar colores
Los colores principales están definidos en las variables CSS al inicio del archivo `index.html`:
```css
:root {
    --primary-color: #ff7f50;
    --secondary-color: #ffa07a;
    --text-color: #4a4a4a;
    --background-color: #fff5e6;
}
```
Modifica estos valores para personalizar el esquema de colores de la página.

### Enlaces de redes sociales
Ubicados en el footer, puedes actualizar las URLs de las redes sociales según tus necesidades:
```html
<a href="https://wa.link/14ocjm" target="_blank">...</a>
<a href="https://www.facebook.com/DLDigital.SanJusto/" target="_blank">...</a>
<a href="https://www.instagram.com/d.l.digital/" target="_blank">...</a>
```

## Mejoras futuras
- **Backend**: Implementar un sistema de gestión de citas para almacenar reservas en una base de datos.
- **Notificaciones**: Enviar confirmaciones automáticas por correo electrónico.
- **Multilenguaje**: Soporte para diferentes idiomas.
- **Diseño adicional**: Añadir más estilos responsivos para dispositivos móviles.

## Créditos
- **Diseño y desarrollo**: DLDigital. https://www.instagram.com/d.l.digital/
- **Iconos**: [Font Awesome](https://fontawesome.com/).

 
