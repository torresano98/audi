# 🚗 Audi A4 Maintenance Web

Página web personal para gestionar el mantenimiento de un Audi A4 B8 (2011, 2.0 TDI).

## 📁 Estructura

```
audi_web/
├── index.html          → Dashboard general (KPIs, alertas, progreso)
├── mantenimiento.html  → Plan completo por componente
├── historial.html      → Registro de servicios realizados/pendientes
├── costes.html         → Estimaciones económicas y plan a 5 años
├── documentos.html     → Datos técnicos, documentos y contactos
└── styles.css          → Estilos compartidos (1 sola fuente de verdad)
```

## 🚀 Uso

1. Abre `index.html` en cualquier navegador
2. Navega entre páginas con la barra superior
3. Para personalizar tus datos, edita directamente el HTML

## 🔧 Personalización rápida

### Actualizar kilometraje
Buscar en `index.html` y `mantenimiento.html`:
```
79.500 km
```

### Añadir una operación al historial
Editar `historial.html`, sección **Servicios Realizados**, añadir nueva fila a la tabla.

### Cambiar imagen del hero
En `styles.css`, modificar la URL de la sección `.hero`:
```css
background: ... url('TU_IMAGEN.jpg') ...
```

## 🏗️ Despliegue

### Local
Abrir `index.html` directamente en el navegador.

### Web (gratis)
- **GitHub Pages:** subir carpeta a un repo y activar Pages
- **Netlify:** drag & drop de la carpeta en netlify.com/drop
- **Vercel:** `vercel deploy` desde la carpeta

## 📌 Datos del coche

- Audi A4 B8 (2011)
- 2.0 TDI · Diésel
- 79.500 km (Mayo 2026)
- Aceite 5W-30 · VW 507.00
- Bujías incandescencia: cambiadas en 2025
