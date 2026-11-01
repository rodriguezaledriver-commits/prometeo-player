cd ~/prometeo
cat > README.md <<'EOF'
<div align="center">

# 🔥 Prometeo Player

**Reproductor de música para Android 100% offline, sin anuncios y sin recopilar datos.**

![Versión](https://img.shields.io/badge/versión-v40-00e5ff?style=for-the-badge)
![Android](https://img.shields.io/badge/Android-APK-3ddc84?style=for-the-badge&logo=android&logoColor=white)
![Offline](https://img.shields.io/badge/100%25-offline-0a0a0a?style=for-the-badge)

[**⬇️ Descargar APK v40**](https://github.com/rodriguezaledriver-commits/prometeo-player/releases/tag/v40)

<img src="captura-v40.png" alt="Prometeo Player v40" width="300">

</div>

---

## ✨ Funciones

- 🎵 **Biblioteca offline**: tus canciones se guardan dentro de la app y suenan sin internet.
- 📂 **Playlists**: crea, renombra, borra y organiza tus listas. Todo queda guardado.
- 🔀 **Aleatorio y repetir**: sin repetir, repetir toda la cola o repetir una canción.
- 🌈 **4 visualizadores**: Barras, Onda, Círculo y Fuego, que se mueven con la música.
- 🔍 **Buscador** de canciones por nombre.
- ⏱️ **Barra de progreso** con tiempo actual y duración total.
- 🎧 **Mini reproductor** visible en todas las pestañas.
- 💾 **Recuerda** la última canción, la posición y tus ajustes al volver a abrir.
- 🔒 **Controles en la pantalla de bloqueo** y en los audífonos.
- 🩺 **Diagnóstico de audio**: toca la versión arriba a la derecha.

## 🎶 Formatos compatibles

| Funciona ✅ | No funciona ❌ |
|---|---|
| MP3, M4A / AAC, OGG, Opus, FLAC, WAV | WMA, AIFF, APE, ALAC (según el teléfono) |

La app detecta el formato real del archivo por su contenido, aunque tenga un nombre o una extensión incorrectos.

## 🔒 Privacidad

- **No usa internet**: el código no hace ninguna conexión externa.
- **No recopila datos**: sin anuncios, sin estadísticas, sin cuentas.
- **No pide permisos** de ubicación, contactos, cámara ni micrófono.
- Tus canciones y playlists quedan **solo en tu teléfono**. Si desinstalas la app, se borran.

## 📲 Instalación

1. Descarga **`Prometeo-v40.apk`** desde [Releases](https://github.com/rodriguezaledriver-commits/prometeo-player/releases/tag/v40).
2. Ábrelo y permite **"Instalar apps desconocidas"** si Android lo pide.
3. Abre Prometeo, toca **＋ Agregar canciones** y elige tu música.

## 🛠️ Compilar desde el código (Termux + Cordova)

Todo el reproductor es un solo archivo: [`www/index.html`](www/index.html) (HTML + CSS + JavaScript, sin librerías externas).

```bash
cd ~/prometeo
cordova build android
```

---

<div align="center">

Hecho en Android, desde Termux 📱

</div>
EOF
head -3 README.md
