# 🚀 Configuración de GitHub Pages para Lightroom SDK

## Pasos para subir a GitHub:

### 1. Crear repositorio en GitHub
1. Ve a [GitHub.com](https://github.com)
2. Haz clic en "New repository"
3. Nombre: `lightroom-sdk-docs`
4. Descripción: `Adobe Lightroom Classic SDK Documentation for RAG systems`
5. **IMPORTANTE**: Marca como **Public** (necesario para GitHub Pages)
6. **NO** inicialices con README (ya tenemos uno)
7. Haz clic en "Create repository"

### 2. Conectar repositorio local con GitHub
```bash
# Reemplaza [tu-usuario] con tu nombre de usuario de GitHub
git remote add origin https://github.com/[tu-usuario]/lightroom-sdk-docs.git
git branch -M main
git push -u origin main
```

### 3. Activar GitHub Pages
1. Ve a tu repositorio en GitHub
2. Ve a **Settings** → **Pages**
3. En "Source", selecciona **"Deploy from a branch"**
4. En "Branch", selecciona **"main"** y **"/ (root)"**
5. Haz clic en **"Save"**

### 4. Configurar GitHub Actions (Opcional)
1. Ve a **Actions** en tu repositorio
2. GitHub detectará automáticamente el workflow
3. Haz clic en **"Run workflow"** para el primer despliegue

## 🌐 URLs resultantes:

Una vez configurado, tu documentación estará disponible en:
- **URL principal**: `https://[tu-usuario].github.io/lightroom-sdk-docs/`
- **API Reference**: `https://[tu-usuario].github.io/lightroom-sdk-docs/API Reference/index.html`
- **Módulos**: `https://[tu-usuario].github.io/lightroom-sdk-docs/API Reference/modules/`

## 🔧 Para el sistema RAG:

Usa estas URLs en tu sistema RAG:
- `https://[tu-usuario].github.io/lightroom-sdk-docs/`
- `https://[tu-usuario].github.io/lightroom-sdk-docs/API Reference/index.html`

## ✅ Ventajas de GitHub Pages:

- ✅ **Sin páginas de advertencia** (como ngrok)
- ✅ **URLs estables** y confiables
- ✅ **Acceso público** sin restricciones
- ✅ **Actualizaciones automáticas** con cada push
- ✅ **HTTPS** por defecto
- ✅ **CDN global** de GitHub

---

**Nota**: Reemplaza `[tu-usuario]` con tu nombre de usuario real de GitHub en todos los comandos y URLs.
