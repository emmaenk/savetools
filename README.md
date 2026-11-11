<div align="center">

# SaveTools

**Descarga videos a tu Android desde TikTok, YouTube, Instagram, X, Facebook y más. Rápido, directo y sin complicaciones.**

## [Descargar la app (APK)](https://github.com/emmaenk/savetools/releases/latest/download/SaveTools.apk)

[![Descargar APK](https://img.shields.io/badge/Descargar_APK-2ea44f?style=for-the-badge)](https://github.com/emmaenk/savetools/releases/latest/download/SaveTools.apk)
&nbsp;
[![Android 8.0+](https://img.shields.io/badge/Android-8.0%2B-555?style=for-the-badge)](#requisitos)

[![Descargas totales](https://img.shields.io/github/downloads/emmaenk/savetools/total?style=flat-square&label=descargas&color=2ea44f)](https://github.com/emmaenk/savetools/releases)
&nbsp;
[![Kotlin](https://img.shields.io/badge/Kotlin-Android_nativo-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](#con-qué-está-hecha)
&nbsp;
[![Última versión](https://img.shields.io/github/v/release/emmaenk/savetools?style=flat-square&label=versión&color=555)](https://github.com/emmaenk/savetools/releases/latest)
&nbsp;
[![VirusTotal](https://img.shields.io/badge/VirusTotal-ver_análisis-394eff?style=flat-square)](https://www.virustotal.com/gui/file/fa7e828ccffecb557529d555231b7b593287642cb8925ffb16e3d2da1279a9ab)

<sub>Un solo toque para bajar el APK. Android 8.0 o superior.</sub>

<br>

<img src="screenshot.png" alt="Pantalla principal de SaveTools" width="300">

</div>

---

## Qué es

SaveTools es una app de Android para descargar videos sin vueltas. Pega uno o varios enlaces, elige la calidad y descarga. También puedes compartir un video desde cualquier otra app y SaveTools lo baja por ti.

## Características

- **Varios a la vez.** Pega varios enlaces (uno por línea) y bájalos en lote.
- **Muchas plataformas.** TikTok, YouTube, Instagram, X (Twitter), Facebook y más.
- **Elige la calidad** antes de descargar.
- **Audio en MP3 o M4A.** MP3 para máxima compatibilidad; M4A conserva el audio original (mejor calidad y más rápido).
- **Instagram completo.** Baja reels, publicaciones y **carruseles de fotos y videos** (conecta tu cuenta para el contenido que lo pide).
- **TikTok sin marca de agua.**
- **Botón Pegar.** Toma el enlace del portapapeles con un toque.
- **Integración con "Compartir".** Aparece en el menú de Android como *Guardar en SaveTools*, así bajas desde donde sea.
- **Cuentas opcionales.** Inicia sesión (o importa `cookies.txt`) solo para contenido que lo pide: reels e historias privadas, carruseles de Instagram, publicaciones de grupos, contenido sensible.
- **Audio, video y fotos separados.** Se guardan en subcarpetas `Audio/`, `Video/` y `Fotos/`, para no mezclarlas. Puedes elegir otra carpeta base.
- **Lista limpia.** Al terminar, cada descarga se quita sola de la lista; solo ves lo que falta.
- **Registro persistente.** El registro de abajo se guarda aunque cierres la app (mantén presionado *Ver registro* para borrarlo).
- **Se actualiza sola.** Desde la 2.3, la app te avisa cuando hay una versión nueva y la instala sin salir a GitHub.
- **Modo claro y oscuro.** Sigue el tema de tu teléfono.
- **Mis descargas** para ver, reproducir, compartir o borrar lo que bajaste.

## Recomendaciones de uso

- **Conecta tus cuentas para el contenido que pide sesión.** Los **carruseles de fotos de Instagram**, las historias y los reels privados necesitan que tu cuenta de Instagram esté conectada (*Cuentas → Conectar*). Lo mismo para videos privados de YouTube, grupos de Facebook o posts sensibles de X.
- **Audio: M4A vs MP3.** Para música elige **M4A** (es el audio original, mejor calidad y descarga más rápida). Usa **MP3** solo si el reproductor donde lo vas a oír es viejito. Ojo: ninguna app puede sacar más calidad de la que la plataforma entrega (no esperes FLAC real de YouTube).
- **Elige tu carpeta.** Por defecto se guarda en `Descargas › SaveTools`, con `Audio/`, `Video/` y `Fotos/` separadas. Puedes cambiar la carpeta base desde *Elegir carpeta*.
- **Descarga en lote.** Pega varios enlaces (uno por línea) y usa *Calidad* para aplicar la misma calidad a toda la lista.
- **Si una plataforma deja de funcionar**, toca *Actualizar motor* (actualiza el componente que lee los sitios). Mantén presionado ese botón para buscar actualización de la app.
- **Permiso de instalación.** La primera vez Android pedirá permitir *instalar apps de orígenes desconocidos*; es normal en apps fuera de Play Store.

## Con qué está hecha

- **Lenguaje:** [Kotlin](https://kotlinlang.org/).
- **Plataforma:** Android nativo (Activities + layouts XML, Material 3).
- **Motor de descarga:** [youtubedl-android](https://github.com/yausername/youtubedl-android) (yt-dlp) + **ffmpeg** para unir y reparar archivos.
- **Build:** Gradle (Kotlin DSL), compilado y firmado automáticamente con GitHub Actions.
- Solo `arm64-v8a` (teléfonos modernos de 64 bits).

## Descargar

**Descarga directa:** **[SaveTools.apk](https://github.com/emmaenk/savetools/releases/latest/download/SaveTools.apk)** — un solo toque y se baja al teléfono. Este enlace siempre sirve la versión más reciente.

También puedes entrar a la sección de **[Releases](../../releases/latest)**.

## Instalar

1. Descarga el APK en tu teléfono.
2. Ábrelo. Si Android lo pide, activa *Instalar apps de orígenes desconocidos*.
3. Toca **Instalar**. Listo.

## Requisitos

| Dato        | Valor                    |
|-------------|--------------------------|
| Android     | 8.0 (API 26) o superior  |
| Versión     | 2.5 (versionCode 14)     |
| Arquitectura| arm64-v8a                |
| Tamaño      | ~58 MB                   |

## Verificación y seguridad

Como la app se instala fuera de Play Store, aquí tienes con qué comprobar que es segura y legítima:

- **APK firmado.** Cada versión se firma con la misma llave (por eso la app se actualiza sola sin reinstalar). Un APK alterado por un tercero no coincide con esa firma.
- **Compilado a la vista.** El APK se construye y firma automáticamente con GitHub Actions en cada versión; nada se sube a mano desde una compu cualquiera.
- **Huella del archivo (SHA-256).** Comprueba que el APK que bajaste es idéntico al oficial, byte por byte:

  ```
  fa7e828ccffecb557529d555231b7b593287642cb8925ffb16e3d2da1279a9ab
  ```

  En PC o en el teléfono (Termux): `sha256sum SaveTools.apk` debe dar exactamente ese valor.
- **Permisos mínimos.** Internet, notificaciones, instalar la actualización y guardar archivos. Nada de contactos, SMS ni ubicación.
- **Análisis antivirus.** El APK está revisado en **[VirusTotal](https://www.virustotal.com/gui/file/fa7e828ccffecb557529d555231b7b593287642cb8925ffb16e3d2da1279a9ab)**. Míralo tú mismo.

## Aviso

Descarga únicamente contenido sobre el que tengas derecho. El uso de la app es tu responsabilidad.

---

<div align="center">

Hecho por [@emmaenk](https://github.com/emmaenk)

</div>
