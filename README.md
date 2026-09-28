# Vitrina Web · Pymes de Chile

Ejemplos de landing pages a medida para negocios locales de Talagante y alrededores. Cada página es un solo archivo HTML, sin dependencias ni instalación: se abre en el navegador y funciona.

| Rubro | Negocio de ejemplo | Archivo |
|---|---|---|
| 🐾 Veterinaria | Huellitas del Maipo | [`veterinaria/`](veterinaria/index.html) |
| 🦷 Odontología | Nácar Clínica Dental | [`odontologia/`](odontologia/index.html) |
| 🏠 Corredora de propiedades | Raíces del Valle Propiedades | [`corredora/`](corredora/index.html) |
| 📊 Estudio contable | Cuadra Contadores | [`contable/`](contable/index.html) |
| 💪 Gimnasio | Voltio Gym | [`gimnasio/`](gimnasio/index.html) |

La portada [`index.html`](index.html) reúne los cinco ejemplos.

## Qué incluye cada página

- Reservas y formularios que abren WhatsApp con el mensaje ya escrito
- Asistente virtual en burbuja de chat (demo por reglas, con el punto marcado para conectar una IA real)
- Horarios con aviso "Abierto ahora / Cerrado" según la hora de Chile
- Mapa de Google, reseñas estilo Google, diseño adaptado a celular

## Cómo personalizar para un cliente

1. Abre el `index.html` del rubro.
2. Al inicio del archivo busca el bloque **CONFIGURACIÓN RÁPIDA** y el objeto `CONFIG`: nombre, WhatsApp, dirección, horarios, precios.
3. Los colores están como variables CSS en `:root`.
4. Cambia a mano el `<title>` y las etiquetas `og:` (son las que muestra WhatsApp al compartir el link).

**Odontología con AgendaPro:** pon `modoReserva: "agendapro"` y el link en `agendaProUrl`, o abre la página con `?reserva=agendapro`.

## Publicar con GitHub Pages

Settings → Pages → Branch `main` / carpeta raíz. Quedará en `https://<usuario>.github.io/vitrina-web-pymes-chile/`.

---

Los negocios, teléfonos, reseñas y cifras de estos ejemplos son ficticios.
