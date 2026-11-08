# Visual Impacto — instrucciones para Claude

Sitio de Visual Impacto, la marca de servicios digitales de Mey (páginas web, sistemas, asistentes para negocios).
Mey no es programadora: explicar en castellano simple, sin jerga.

## Publicación
- Sitio estático publicado con GitHub Pages desde `main`, en el dominio visualimpacto.com (archivo `CNAME`; no tocarlo).
- Cada push a `main` publica al instante: no hacer push sin el OK de Mey.
- **El repositorio es público.** No subir claves, datos de clientes ni nada que no pueda ver cualquiera.

## Contenido
- `index.html`: página principal de servicios.
- `demo-peluqueria.html`, `demo-consultorio.html`, `demo-asistente.html`: demos para mostrar a clientes.
- `propuestas/<cliente>/`: propuestas y presupuestos para clientes. Llevan `noindex` para que no aparezcan en Google;
  toda propuesta nueva tiene que llevarlo también.
- `jorge-primero/`: página de prueba (también con `noindex`).
- Todo en HTML/CSS/JS puro, un archivo por página, sin build.
