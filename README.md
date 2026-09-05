# 🚀 ZaroLauncher - Servidor de Distribución Remota

Este repositorio contiene los archivos de configuración remota, servidores, noticias y assets para **ZaroLauncher**. Está preparado para ser alojado **100% gratis** en **GitHub Pages** o **Cloudflare Pages**.

---

## 📁 Estructura del Proyecto

* **`distribution.json`**: El archivo principal que lee el Launcher. Aquí configuras tus servidores de Minecraft, versión de juego (ej. 1.20.4), Forge/Fabric/Vanilla, y presencia de Discord.
* **`rss.xml`**: Canal de noticias en formato RSS para el panel de novedades del launcher.
* **`index.html`**: Página web oficial y punto de acceso web para la distribución.
* **`servers/`**: Carpeta para los iconos y logos de tus servidores (`server.png`).
* **`assets/`**: Logos y recursos gráficos.

---

## 🌐 Cómo Alojarlo Gratis en GitHub Pages (Opción Recomendada)

### 1. Crear el repositorio en GitHub
1. Ve a [github.com/new](https://github.com/new).
2. Nombra tu repositorio: `ZaroLauncher-Distribution` (o el nombre que prefieras).
3. Selecciona **Public** y haz clic en **Create repository**.

### 2. Subir estos archivos
En una terminal dentro de esta carpeta (`ZaroLauncher-Distribution`), ejecuta:

```bash
git init
git add .
git commit -m "Initial ZaroLauncher Distribution"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/ZaroLauncher-Distribution.git
git push -u origin main
```

### 3. Activar GitHub Pages
1. En tu repositorio en GitHub, ve a **Settings** -> **Pages** (menú izquierdo).
2. En **Build and deployment** -> **Branch**:
   - Selecciona rama: `main`
   - Carpeta: `/ (root)`
3. Haz clic en **Save**.
4. En unos segundos, tu URL pública estará lista en:
   ```text
   https://TU_USUARIO.github.io/ZaroLauncher-Distribution/
   ```

### 4. Tus URLs Públicas Finales:
* **distribution.json**: `https://TU_USUARIO.github.io/ZaroLauncher-Distribution/distribution.json`
* **Noticias RSS**: `https://TU_USUARIO.github.io/ZaroLauncher-Distribution/rss.xml`

---

## ⚡ Cómo Alojarlo en Cloudflare Pages

1. Entra a [dash.cloudflare.com](https://dash.cloudflare.com/) -> **Workers & Pages**.
2. Haz clic en **Create application** -> **Pages** -> **Connect to Git**.
3. Selecciona tu repositorio `ZaroLauncher-Distribution`.
4. En configuración de compilación deja todo por defecto (Build output: `/`).
5. Haz clic en **Save and Deploy**. Tendrás una URL rápida con CDN global gratuita como: `https://zarolauncher.pages.dev/distribution.json`.
