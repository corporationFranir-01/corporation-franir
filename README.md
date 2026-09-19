# CORPORATION FRANIR E.I.R.L.
### Plataforma Web & Catálogo Digital de Equipos de Izaje y Seguridad Industrial

Sitio web corporativo y catálogo interactivo para **Corporation Franir E.I.R.L.** (RUC: 20615462463), especializado en equipos de izaje, maniobras pesadas, trabajos en altura y seguridad industrial en Lima, Perú.

---

## 🚀 Características Principales

- **Catálogo Digital Interactivo:** Exploración por categorías (*Tecles, Eslingas, Arneses, Líneas de Vida, Accesorios de Izaje*).
- **Buscador Inteligente (Spotlight Search):** Búsqueda rápida en tiempo real con chips de filtrado y atajo `Ctrl + K`.
- **Cotizador Instantáneo vía WhatsApp:** Carrito de cotización con generación de mensaje estructurado y descarga en PDF oficial.
- **Reloj y Estado Operativo en Vivo:** Indicador en tiempo real de horario de atención comercial.
- **Panel Administrativo Completo:**
  - Gestión de Productos (CRUD completo).
  - Gestión de Categorías.
  - Gestión de Marcas y Logos para portada.
  - Personalización de Identidad Visual (Logotipo, Sliders de tamaño).
  - Métricas y Analytics en tiempo real con gráficos.
- **Sincronización en la Nube:** Integración con **Supabase** (PostgreSQL) + persistencia local segura.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 semántico & CSS3**
- **Tailwind CSS (CDN)** para diseño moderno y responsivo
- **Supabase JS SDK v2** para sincronización en la nube en tiempo real
- **Chart.js** para gráficos estadísticos del panel administrativo
- **html2pdf.js** para exportación de cotizaciones en formato PDF
- **FontAwesome 6** para iconografía industrial

---

## 💻 Desarrollo Local

Para ejecutar el proyecto localmente:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/TU_USUARIO/corporation-franir.git
   cd corporation-franir
   ```

2. Inicia un servidor local:
   ```bash
   npx serve .
   ```
   o simplemente abre el archivo `index.html` en tu navegador.

---

## ☁️ Despliegue en Vercel (Gratuito)

1. Sube tu proyecto a un repositorio en **GitHub**.
2. Ingresa a [Vercel](https://vercel.com) e inicia sesión con tu cuenta de GitHub.
3. Haz clic en **"Add New..."** > **"Project"**.
4. Selecciona el repositorio de **corporation-franir**.
5. En **Framework Preset**, déjalo en **"Other"** (Vercel detectará la configuración automáticamente mediante `vercel.json` y `package.json`).
6. Haz clic en **"Deploy"**.

¡Tu sitio estará publicado y funcionando en internet en menos de 1 minuto con certificado SSL HTTPS gratuito!
