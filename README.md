# 🇪🇸 RadarX España | Monitor Electoral en X

Monitor web en tiempo real del engagement, interacciones y tweets más virales de los candidatos y partidos políticos en España durante la campaña electoral.

---

## 🚀 Cómo ver la web en tu ordenador ahora mismo

Puedes abrir el archivo directamente en tu navegador:
1. Abre tu navegador (Chrome, Safari, Firefox).
2. Arrastra el archivo `index.html` a una pestaña nueva, o abre desde la terminal:
   ```bash
   open index.html
   ```

---

## 🌐 Cómo publicarlo GRATIS en Internet (GitHub Pages)

Para que tu web tenga una dirección web pública gratuita (tipo `https://tu-usuario.github.io/radarx`) sin pagar dominio ni hosting:

### Paso 1: Crear tu cuenta de GitHub (1 minuto)
1. Entra en [github.com/signup](https://github.com/signup).
2. Pon tu correo, contraseña y elige tu nombre de usuario (ejemplo: `radar-elecciones` o tu apodo).
3. Confirma el correo que te mandan. ¡Listo, es 100% gratis!

### Paso 2: Crear el repositorio en GitHub
1. Una vez dentro de GitHub, pulsa el botón verde **"New"** (o **"Create repository"**).
2. Ponle de nombre: `radarx` (o el nombre que prefieras).
3. Déjalo en **Public** (Público).
4. Pulsa **"Create repository"**.

### Paso 3: Subir este proyecto
En tu terminal dentro de esta carpeta, ejecuta estos 3 comandos:
```bash
git remote add origin https://github.com/TU_USUARIO/radarx.git
git branch -M main
git push -u origin main
```

*(Si prefieres no usar terminal para subirlo, también puedes descargar la app [GitHub Desktop](https://desktop.github.com/) y arrastrar la carpeta).*

### Paso 4: Activar la web pública (1 clic)
1. En tu repositorio de GitHub, ve a la pestaña **Settings** (Configuración).
2. En el menú de la izquierda, entra en **Pages**.
3. En **Build and deployment > Source**, selecciona **Deploy from a branch**.
4. En **Branch**, selecciona `main` y la carpeta `/ (root)`, luego pulsa **Save**.
5. ¡En 1 minuto tu web estará disponible en: `https://TU_USUARIO.github.io/radarx`!

---

## 🤖 Actualización automática en piloto automático

Este proyecto incluye un archivo en `.github/workflows/update_data.yml`.
Cada 6 horas, GitHub ejecutará el script `scripts/update_data.py` de forma 100% gratuita y actualizará los números en tu web sin que tengas que tocar nada.

---

## 📢 Consejos para tu cuenta de X y monetización

1. **Crear la cuenta en X**:
   - Entra en [x.com/signup](https://x.com/signup).
   - Elige un handle claro, por ejemplo: `@RadarElectoralES`, `@TermometroX_ES` o `@PulsoPoliticoX`.
   - Pon en la biografía: *"Datos y engagement diario de la campaña electoral en España 🇪🇸 | Gráficos neutrales y abiertos | Web: [tu enlace de github.io]"*.
2. **Cómo ganar visitas**:
   - Todos los días a las 21:00h, haz una captura de pantalla del podio o las gráficas de la web y súbelo a X:
     > *"📊 [Día X de Campaña] Podio de interacción de hoy en X: 1º @Santi_ABASCAL (99k), 2º @sanchezcastejon (90k)... Datos completos y gráficos en directo: [enlace a tu web]"*
   - Cita a las cuentas de los políticos. A sus simpatizantes les encanta debatir y retuitear si su candidato va primero.
3. **Monetización**:
   - En `index.html` ya tienes configurado el espacio para donaciones (Ko-fi o Bizum) y el banner para anunciantes o podcasts de actualidad.
