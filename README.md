# 🇪🇸 RadarX España | Monitor Electoral en X

Monitor en tiempo real del engagement, impacto y repercusión de los candidatos y partidos en X durante las Elecciones Generales en España. Optimizado 100% para dispositivos móviles.

---

## 🚀 Subir cambios a tu GitHub

El repositorio ya está configurado con:
```bash
https://github.com/Pablorm-esp/radarx.git
```

Para subir los cambios:
```bash
git add .
git commit -m "✨ Rediseño mobile-first, integración Caffutio.com y actualización horaria"
git push -u origin main
```

---

## 🌐 Activar la web en GitHub Pages (Solo una vez)

1. Ve a tu repositorio: [https://github.com/Pablorm-esp/radarx](https://github.com/Pablorm-esp/radarx)
2. Entra en **Settings** > **Pages** (menú izquierdo).
3. En **Branch**, selecciona `main` y carpeta `/ (root)`.
4. Haz clic en **Save**.
5. Tu web estará visible en: `https://pablorm-esp.github.io/radarx/`

---

## 🤖 Actualización automática horaria

El archivo `.github/workflows/update_data.yml` está programado para ejecutarse **cada hora** (`cron: '0 * * * *'`).
GitHub Actions ejecutará el script, actualizará las estadísticas en `data/data.json` y desplegará los datos frescos automáticamente sin que tengas que hacer nada.

---

## ☕ Publicidad de Caffutio.com

Se ha integrado publicidad nativa y contextual de **[caffutio.com](https://caffutio.com)**:
- **Barra superior inteligente**: *"¿Noches de debate y campaña? Sobrevive con café de verdad"*.
- **Card destacada**: Enfoque de supervivencia a debates y tertulias electorales recomendando cafeteras espresso y superautomáticas.
- **Enlaces con parámetros UTM** (`?utm_source=radarx...`) para que puedas medir en Google Analytics cuántas visitas te manda RadarX a Caffutio.
