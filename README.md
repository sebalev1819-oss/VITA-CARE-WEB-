# Care Assistance — Sitio Web Oficial

Sitio web completo de **Care Assistance**, ecosistema líder de bienestar corporativo en LATAM.

## 🚀 Cómo subir a GitHub Pages

### Opción A — Desde GitHub.com (más fácil)

1. Creá un repositorio nuevo en [github.com](https://github.com) → **New repository**
2. Nombralo `care-assistance-web` (o el nombre que prefieras)
3. Marcá ✅ **Public**
4. Click en **Add file → Upload files**
5. Arrastrá el archivo `index.html` al área de carga
6. Click en **Commit changes**
7. Andá a **Settings → Pages**
8. En "Source" seleccioná **main** y carpeta **/ (root)**
9. Click **Save**
10. Tu sitio estará en: `https://[tu-usuario].github.io/care-assistance-web/`

---

### Opción B — Desde la terminal (Git)

```bash
# 1. Creá carpeta y mové el archivo
mkdir care-assistance-web
cp index.html care-assistance-web/
cd care-assistance-web

# 2. Inicializá git y subí
git init
git add .
git commit -m "feat: sitio web Care Assistance v1.0"
git branch -M main
git remote add origin https://github.com/[TU-USUARIO]/care-assistance-web.git
git push -u origin main
```

Luego activá GitHub Pages en **Settings → Pages → Source: main**.

---

## 📁 Estructura del proyecto

```
care-assistance-web/
└── index.html          ← Todo el sitio (HTML + CSS + JS en un solo archivo)
```

## ✅ Qué incluye el sitio

- **Hero** con métricas clave y dashboard animado
- **6 Pilares** de bienestar (Físico, Mental, Financiero, Social, Profesional, Familia)
- **Plataforma** con features interactivos y dashboard mock
- **Métricas** con contadores animados (73%, 25%, +100 empresas, 96%)
- **Cómo funciona** en 4 pasos
- **Testimonios** de clientes reales
- **Tendencias 2026** del mercado global
- **Blog / Insights** con 3 artículos destacados
- **CTA** con formulario de demo
- **Footer** completo con 4 países LATAM

## 🎨 Tecnologías

- HTML5 + CSS3 puro (sin frameworks)
- JavaScript vanilla
- Google Fonts (Sora + DM Serif Display)
- Totalmente responsive (mobile, tablet, desktop)
- Sin dependencias externas — funciona offline

## 📞 Personalización

Para actualizar el sitio, buscá en `index.html`:
- **Emails/teléfonos** → buscá `hola@careassistance.com`
- **Logos de clientes** → sección `#logos`
- **Testimonios** → sección `#testimonios`
- **Métricas** → atributos `data-target` en sección `#metricas`
