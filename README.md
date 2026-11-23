# Crema y Pastel · App Android

Tienda de Crema y Pastel (cremaypastel.com) como app de Android: catálogo con búsqueda y filtros, y pedidos por WhatsApp al +51 941 064 819.

- La tienda está en `app/src/main/assets/www/` (index.html + fotos en img/).
- Cada push a `main` compila el APK con GitHub Actions y lo publica en **Releases** (descarga directa: `releases/latest`).
- Firma: si existen los secretos `KEYSTORE_BASE64`, `KEYSTORE_PASSWORD`, `KEY_ALIAS` y `KEY_PASSWORD`, el APK se firma con esa llave (necesario para que las actualizaciones se instalen encima de la versión anterior).
