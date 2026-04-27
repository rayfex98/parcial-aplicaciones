# Parcial Aplicaciones — Formulario de Contacto Docente

Página web desarrollada como parte del parcial de la materia Aplicaciones Web. Implementa un formulario de contacto funcional para que los estudiantes puedan enviar mensajes directamente al docente.

## Tecnologías utilizadas

- **HTML5** semántico
- **Bootstrap 5.3** (via CDN) para el diseño responsivo
- **Bootstrap Icons 1.11** para iconografía
- **Google Fonts — Inter** para tipografía
- **Formspree** para el procesamiento del formulario sin backend

## Funcionalidades

- Formulario con campo de correo electrónico y área de texto para el mensaje
- Validación nativa de HTML5 (campos requeridos, formato de email)
- Feedback visual al enviar (spinner en el botón)
- Diseño responsivo adaptado a dispositivos móviles y escritorio
- Año dinámico en el footer via JavaScript

## Uso de Formspree

El formulario envía los datos a `https://formspree.io/f/xeevwapo`. Los mensajes llegan directamente al correo del docente configurado en la cuenta de Formspree.

## Estructura del proyecto

```
parcial-aplicaciones/
└── index.html    # Página principal con formulario
└── README.md     # Este archivo
```

## Demo en línea

[parcial-sigma-brown.vercel.app](https://parcial-sigma-brown.vercel.app)
