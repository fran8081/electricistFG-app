# ⚡ Relevamiento Eléctrico — Diamante, Entre Ríos

App PWA para electricistas: calcula materiales, mano de obra y gestiona el historial de clientes.

---

## 🚀 Publicar en GitHub Pages (una sola vez)

1. Entrá a **github.com** con tu cuenta
2. Click en **"New repository"** (botón verde arriba a la derecha)
3. Nombre del repositorio: `electricista-app`
4. Dejalo en **Public** → click **"Create repository"**
5. Subí estos archivos (arrastrá al repositorio o usá "uploading an existing file"):
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
6. Andá a **Settings** → **Pages** (menú izquierdo) → 
   Source: **Deploy from a branch** → Branch: **main** → **Save**
7. En 2 minutos tu app estará en:
   **https://TU-USUARIO.github.io/electricista-app/**

---

## 🗄️ Activar historial en la nube (Supabase) — opcional

1. Creá cuenta en **supabase.com** (gratis con GitHub)
2. Nuevo proyecto → región **South America (São Paulo)**
3. Andá a **SQL Editor** → **New Query**
4. Pegá el contenido de `supabase_setup.sql` y ejecutá (▶ Run)
5. Andá a **Settings → API** y copiá:
   - `Project URL`
   - `anon public` key
6. En la app, abrí el banner amarillo y pegá esos dos datos

Sin Supabase, el historial se guarda igual en el celular (localStorage).

---

## 📱 Instalar en el celular

### Android (Chrome):
- Abrí la URL de la app en Chrome
- Menú (3 puntos) → **"Agregar a la pantalla de inicio"**

### iPhone (Safari):
- Abrí la URL en Safari
- Botón compartir (□↑) → **"Agregar a la pantalla de inicio"**

---

## 📋 Qué incluye la app

- ✅ Formulario de relevamiento (cliente, ambientes, tablero)
- ✅ Calculadora automática de materiales con metros de cable
- ✅ Precios en tiempo real de Mercado Libre (con fallback offline)
- ✅ Mano de obra según tabla AAIERIC mayo 2026 −15% (zona interior)
- ✅ Historial de clientes buscable
- ✅ Funciona sin internet (PWA offline)
- ✅ Botón imprimir / guardar PDF
- ✅ Instalable como app en el celular
