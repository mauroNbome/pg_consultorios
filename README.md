# P&G Consultorios — Sitio estático

Sitio web estático de propuesta para P&G Consultorios (odontología en Rosario). Incluye una única página (`index.html`) con estilos embebidos y recursos en `assets/`.

## Contenido principal
- **Hero y CTA**: mensaje principal y botón de reserva.
- **Servicios**: grilla con tratamientos (alineadores, implantes, prótesis, blanqueamiento, etc.).
- **Opiniones**: testimonios con calificación.
- **Sobre el profesional**: perfil del Dr. Pablo Pozzo.
- **Beneficios**: motivos para elegir el consultorio.
- **FAQ**: preguntas frecuentes.
- **Contacto y ubicación**: dirección, teléfono, horario y mapa embebido.
- **SEO**: metadatos, Open Graph/Twitter y `application/ld+json` (Schema.org/Dentist).

## Estructura del proyecto
```
pg_consultorios/
├─ index.html
└─ assets/
   ├─ pg_logo.png
   ├─ hero.png
   ├─ cta.png
   └─ servicios/
```

## Ver el sitio localmente
Puedes abrir `index.html` directamente en el navegador. Para servirlo con un servidor local (recomendado para rutas relativas):

- **Python 3**
  ```bash
  cd /root/coding/pg_consultorios
  python3 -m http.server 8080
  ```
  Luego visita `http://localhost:8080`.

- **Node.js (npx serve)**
  ```bash
  cd /root/coding/pg_consultorios
  npx --yes serve . -l 8080
  ```


