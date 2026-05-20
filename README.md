# 🍔 FastBurguer PWA

Sistema de pedidos online para restaurante de hamburguesas. 100% gratuito, funciona offline, instalable en cualquier móvil.

## ✨ Características

- ✅ **PWA Instalable** - Se instala como app nativa en iOS/Android
- ✅ **Modo Oscuro Premium** - Diseño negro/naranja profesional
- ✅ **Menú por categorías** - Hamburguesas, salchipapas, bebidas, promociones
- ✅ **Carrito de compras** - Funciona offline
- ✅ **Multimoneda** - USD y Bs con conversión automática
- ✅ **Tipos de servicio** - En sitio, Pick Up, Delivery
- ✅ **Pedido por WhatsApp** - Se envía directo al restaurante
- ✅ **Panel Admin** - Gestión de pedidos, productos, tasas
- ✅ **Sin backend costoso** - Todo en localStorage + JSON

## 🚀 Cómo usar

### Para clientes:
1. Abre la app en tu navegador
2. Navega el menú por categorías
3. Agrega productos al carrito
4. Completa tus datos y tipo de servicio
5. Envía por WhatsApp

### Para administrador:
1. Toca el icono 👤 (Admin)
2. Usuario: `admin` | Contraseña: `123`
3. Gestiona pedidos, productos y tasas

## 🛠️ Tecnologías (100% gratis)

| Componente | Tecnología | Costo |
|-----------|-----------|-------|
| Frontend | HTML5 + Tailwind CSS + Vanilla JS | Gratis |
| Datos | JSON local | Gratis |
| Estado | localStorage | Gratis |
| Hosting | GitHub Pages / Cloudflare | Gratis |
| Iconos | Generados localmente | Gratis |

## 📦 Estructura de archivos

```
fastburguer/
├── index.html      # App principal
├── manifest.json   # Config PWA
├── sw.js           # Service Worker (offline)
├── data.json       # Datos del menú
├── icon-192.png    # Icono app
└── icon-512.png    # Icono app grande
```

## 🌐 Despliegue gratuito

### Opción 1: GitHub Pages (Recomendado)
1. Crea cuenta en github.com
2. Crea nuevo repositorio: `fastburguer`
3. Sube estos archivos
4. Ve a Settings > Pages > Source: main branch
5. Tu app estará en: `https://tusuario.github.io/fastburguer`

### Opción 2: Cloudflare Pages
1. Cuenta en cloudflare.com
2. Pages > Create a project > Upload assets
3. Sube la carpeta completa
4. Obtienes HTTPS gratis + CDN global

### Opción 3: Netlify Drop
1. Ve a netlify.com/drop
2. Arrastra la carpeta fastburguer
5. Listo, tienes URL en segundos

## 💰 Monetización

### Fase 1: Uso propio
- Usa la app para tu restaurante
- Recibe pedidos por WhatsApp
- Ahorra comisiones de delivery apps (30%)

### Fase 2: Venta a otros restaurantes
- Personaliza colores/logo
- Vende la "plantilla" por $200-500
- Incluye configuración inicial

### Fase 3: SaaS mensual
- Alojas la app para clientes
- Cobras $20-50/mes por restaurante
- Mantienes menú actualizado

## 🔧 Personalización

### Cambiar datos del menú:
Edita `data.json` con tus productos, precios y categorías.

### Cambiar número de WhatsApp:
En `index.html`, busca `584127778888` y reemplázalo con tu número.

### Cambiar colores:
En el `<style>` del HTML, modifica:
- `#FF6B00` (naranja principal)
- `#FFCC00` (amarillo secundario)
- `#000000` (fondo oscuro)

### Cambiar logo:
Reemplaza `icon-192.png` y `icon-512.png` con tu logo.

## 📱 Instalación en móviles

### Android (Chrome):
1. Abre la app en Chrome
2. Toca ⋮ > "Agregar a pantalla de inicio"
3. ¡Listo! Aparece como app nativa

### iPhone (Safari):
1. Abre la app en Safari
2. Toca Compartir > "Agregar a pantalla de inicio"
3. ¡Listo! Funciona como app nativa

## ⚠️ Limitaciones (y soluciones)

| Limitación | Solución |
|-----------|----------|
| Datos solo en un dispositivo | Exportar/importar JSON |
| Sin pagos online | WhatsApp + Pago Móvil/Zelle |
| Sin notificaciones push | WhatsApp Business API (gratis) |
| Sin base de datos central | Google Sheets API (gratis) |

## 📝 Licencia

MIT License - Úsala, modifícala, véndela. Lo que necesites para salir adelante.

---

**Hecho con ❤️ para emprendedores que no se rinden.**
