<p align="center">
  <img src="docs/banner.svg" alt="HundoHunter: tus adorables compañeras en el camino al 100%" width="100%">
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/descargar-v4.1.0-ff7aa8?style=for-the-badge" alt="descargar"></a>
  <img src="https://img.shields.io/badge/Windows%20%7C%20Linux%20%7C%20macOS-3ce0d0?style=for-the-badge" alt="Windows | Linux | macOS">
  <img src="https://img.shields.io/badge/Steam-logros-1b2838?style=for-the-badge&logo=steam&logoColor=white" alt="Steam">
  <img src="https://img.shields.io/badge/idiomas-12-b48cff?style=for-the-badge" alt="12">
</p>

<p align="center">
  <a href="README.md">English</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.ru.md">Русский</a> · <b>Español</b> · <a href="README.zh.md">中文</a> · <a href="README.de.md">Deutsch</a> · <a href="README.fr.md">Français</a> · <a href="README.ja.md">日本語</a>
</p>

---

**HundoHunter** es una pequeña ventana superpuesta que se queda en una esquina de la pantalla mientras juegas. Reconoce el juego de Steam que tienes abierto y te dice **qué logro conseguir después**, **cómo conseguirlo** y **cuáles podrías perder para siempre**. Un solo objetivo: completar cada juego al 100%, un *hundo*.

Y nunca cazas solo. Te presentamos a las **Hundos** 💖

<p align="center">
  <img src="docs/hundos/group.svg" alt="Hundos" width="640">
</p>

## 🆕 Novedades de la v4.1

<p align="center">
  <img src="docs/img/hub.png" alt="La ventana grande" width="100%">
</p>

- **La ventana grande** (`Ctrl` + `Shift` + `A`): todos tus juegos y logros lado a lado, con filtros, orden, guías, notas y amigos. La búsqueda encuentra cualquier juego que tengas, incluso los que nunca abriste, y perdona las erratas.
- **Listas de seguimiento**: reúne logros de cualquier juego en listas con nombre. El HUD pequeño muestra la lista que elijas.
- **Ruta al 100 %**: la IA divide los logros de un juego en etapas lógicas, primero los que se pueden perder y al final el farmeo.
- **Pestaña de amigos**: clasificación por juego, "ellos lo tienen y tú no", quién consiguió qué y cuándo, y un aviso cuando un amigo te adelanta.
- **Estadísticas y resumen de sesión**: totales, racha y gráfico mensual, y una tarjeta breve después de cada sesión de juego.
- **Tarjeta para compartir**: una imagen de progreso de 1200×630 con los colores de tu tema y la captura tomada en el momento del logro.
- **Modo streamer**: una página de overlay transparente para OBS / Streamlabs (fuente de navegador).
- **Estado en Discord**, **mostrar/ocultar con mando** (Xbox, PlayStation, Steam Deck; Windows y Linux) y soporte para el **Modo Juego de Steam Deck**.
- **Descripciones de logros ocultos** tomadas de los datos de Steam, que siguen borrosas hasta que las pidas.
- **Actualización con un clic**, verificada con SHA256, y un botón para **informar de errores** que oculta tus claves e ID.
- **4 idiomas nuevos**: Português (BR), Polski, 한국어 e Italiano (12 en total).
- **32 temas**, 8 de ellos nuevos: Cristal, Océano profundo, Galaxia, Atardecer, Lluvia en el cristal, Mármol y oro, Terminal, Estambul (Bósforo). Todos los temas se redibujaron y las animaciones son más fluidas y ligeras.

<p align="center">
  <img src="docs/img/hub_friends.png" alt="Pestaña de amigos" width="100%">
</p>

## 💖 Conoce a las Hundos

Las Hundos son las niñas que viven en los temas de HundoHunter. Parpadean, se balancean, mueven la cola y **saltan de alegría cada vez que desbloqueas un logro**. Cada una tiene su tarea favorita:

<table>
<tr>
<td width="200" align="center"><img src="docs/hundos/neko.svg" width="180" alt="Neko"><br><b>Neko</b></td>
<td>
<b>La rastreadora.</b> Neko olfatea tu <b>próximo logro</b> en cuanto empieza el juego, con su descripción y una pista de la guía. Sus orejas se mueven cuando algo está cerca (por ejemplo, logros con progreso <code>32/50</code>).
<br><br><i>"Nyaa~ ¡solo tres más y es tuyo!"</i>
</td>
</tr>
<tr>
<td width="200" align="center"><img src="docs/hundos/moon.svg" width="180" alt="Luz de Luna"><br><b>Luz de Luna</b></td>
<td>
<b>La guardiana tranquila.</b> Luz de Luna cuida tu <b>biblioteca</b>, tu <b>historial de 14 días</b> y los juegos <b>más cerca del 100%</b>, para que siempre sepas qué hundo tienes al alcance.
<br><br><i>"Stardew Valley está al 86%... ¿lo terminamos esta noche?"</i>
</td>
</tr>
<tr>
<td width="200" align="center"><img src="docs/hundos/idol.svg" width="180" alt="Ritmo Neón"><br><b>Ritmo Neón</b></td>
<td>
<b>La animadora.</b> Cuando salta un logro, ella es la primera en enterarse: <b>detección instantánea</b>, en el mismo segundo que la notificación de Steam. Sonido de trofeo, aviso, un salto y tu <b>puntuación Y</b> sube.
<br><br><i>"¡¡Trofeo de diamante!! ¡Menos del 1% de los jugadores lo tiene!"</i>
</td>
</tr>
<tr>
<td width="200" align="center"><img src="docs/hundos/goth.svg" width="180" alt="Princesa Gótica"><br><b>Princesa Gótica</b></td>
<td>
<b>La protectora.</b> Te avisa de los <b>logros que se pueden perder</b> antes de que sea tarde (detección con IA) y mantiene <b>borrosos los logros ocultos</b> para que nada se destripe.
<br><br><i>"Cuidado. Si sales de este capítulo, ese trofeo se pierde para siempre."</i>
</td>
</tr>
</table>

## ✨ Funciones

<table>
<tr>
<td width="50%" valign="top"><img src="docs/img/main_es.png" alt="Ventana en el juego" width="100%"></td>
<td valign="top">
<h3><img src="docs/hundos/neko_head.svg" height="30"> Guía dentro del juego</h3>
<ul>
<li>Detecta automáticamente el juego de Steam en ejecución</li>
<li><b>Próximo logro objetivo</b> con descripción, rareza y pista de la guía</li>
<li><b>Logros más cercanos</b> con barras de rareza</li>
<li>Sigue cualquier logro como objetivo y añade tus notas</li>
<li>Funciona encima de juegos en <b>ventana sin bordes / pantalla completa en ventana</b></li>
</ul>
<h3><img src="docs/hundos/idol_head.svg" height="30"> Desbloqueos al instante</h3>
<ul>
<li>Lee los registros locales del propio Steam: los logros aparecen <b>en el mismo segundo que en Steam</b></li>
<li>Funciona aunque tus <i>Detalles de juegos</i> sean privados</li>
<li>Caché sin conexión: funciona sin internet</li>
</ul>
</td>
</tr>
<tr>
<td valign="top">
<h3><img src="docs/hundos/goth_head.svg" height="30"> Sin sorpresas ni spoilers</h3>
<ul>
<li>Avisos de <b>logros perdibles</b> (con IA: Gemini u OpenAI)</li>
<li>Textos de guía <b>traducidos automáticamente</b> a tu idioma</li>
<li><b>Protección contra spoilers</b>: los logros ocultos siguen borrosos hasta que tú quieras</li>
</ul>
<h3><img src="docs/hundos/moon_head.svg" height="30"> Toda tu colección</h3>
<ul>
<li>Biblioteca con el progreso de cada juego y los <b>más cercanos al 100%</b></li>
<li>Gráfico de desbloqueos de 14 días</li>
<li><b>Comparación con amigos</b> y clasificación de amigos</li>
<li>Varias cuentas de Steam, cambia con un clic</li>
</ul>
</td>
<td valign="top"><img src="docs/img/toast.png" alt="Celebración de logro" width="100%"></td>
</tr>
</table>

<p align="center">
  <img src="docs/img/library.png" alt="Biblioteca" width="45%">&nbsp;&nbsp;
  <img src="docs/img/friends.png" alt="Clasificación de amigos (nombres difuminados)" width="45%">
</p>

## 🏆 Niveles de trofeo y puntuación Y

Cada logro recibe un nivel según cuántos jugadores lo han desbloqueado, y cada nivel tiene su propio sonido.

| | Nivel | Desbloqueado por | Puntos |
|:-:|---|---|--:|
| <img src="docs/img/bronze.png" width="32"> | **Bronce** | 50% o más | 5 |
| <img src="docs/img/silver.png" width="32"> | **Plata** | 20% – 50% | 15 |
| <img src="docs/img/gold.png" width="32"> | **Oro** | 5% – 20% | 40 |
| <img src="docs/img/sapphire.png" width="32"> | **Zafiro** | 1% – 5% | 100 |
| <img src="docs/img/diamond.png" width="32"> | **Diamante** | menos del 1% | 250 |

Termina un juego al 100% para un **bonus de +50**. Sube de rango: Novato → Cazador de bronce → Cazador de plata → Cazador de oro → Maestro zafiro → Maestro diamante → **Leyenda**.

## 🎨 32 temas (y algunos secretos)

La mayoría de los temas están animados. Las Hundos viven en **Neko**, **Luz de Luna**, **Ritmo Neón** y **Princesa Gótica**, y también tienen amigos mascota. Incluso puedes poner **tu propia imagen de fondo**, junto con un tema o sola.

<p align="center">
  <img src="docs/img/themes.png" alt="Galería de temas" width="820">
</p>

> 🤫 Algunos temas no aparecen en la lista. Dicen que las Hundos solo susurran las contraseñas a los verdaderos cazadores...

## 📥 Descarga e instalación

1. 🪟 **Windows:** Descarga **HundoHunter.zip** desde la [última versión](../../releases/latest) y descomprímelo donde quieras.
2. Ejecuta `HundoHunter.exe`. No hace falta instalar nada más: es un solo archivo con .NET incluido.<br>*Windows puede decir "Windows protegió su PC" porque la app no está firmada. Haz clic en **Más información → Ejecutar de todas formas**.*
   - 🐧 **Linux:** descarga `HundoHunter-4.1.0-linux-x64.tar.gz`, descomprímelo y ejecuta `./install.sh` (añade HundoHunter al menú de aplicaciones). Funciona mejor en una sesión X11; en Wayland, los atajos y el modo siempre visible dependen de tu escritorio.
   - 🍎 **macOS:** descarga el zip para tu Mac (`AppleSilicon` para M1–M4, `Intel` para Macs anteriores), descomprímelo y mueve `HundoHunter.app` a Aplicaciones. La app no está firmada: la primera vez, haz clic derecho y elige **Abrir**.
   - 🎮 **Steam Deck:** usa la versión de Linux. En el Modo Juego el HUD pequeño se dibuja encima del juego y se muestra u oculta con el mando. La ventana grande no está disponible en Steam Deck.
3. Consigue una **clave de Steam Web API** gratuita en <https://steamcommunity.com/dev/apikey> (sirve cualquier dominio, p. ej. `localhost`) y pégala en los ajustes.
4. Añade tu cuenta: pega el enlace de tu perfil de Steam, tu URL personalizada o tu Steam ID de 17 dígitos.
5. *(Opcional)* Añade una clave de **Google Gemini** (tiene nivel gratuito) u **OpenAI** para detectar logros perdibles y traducir guías.
6. Pulsa **Guardar e iniciar**, abre un juego desde Steam y saluda a tu Hundo.

> 💡 Para la biblioteca, el historial y los amigos, pon **Steam → Editar perfil → Privacidad → Detalles de juegos** en **Público**.

### Atajos de teclado

| Teclas | Acción |
|---|---|
| `Ctrl` + `H` | Mostrar / ocultar la ventana |
| `Ctrl` + `Shift` + `H` | Modo clic a través (los clics van al juego) |
| `Ctrl` + `Shift` + `A` | Abrir la ventana grande |
| `Ctrl` + `1` … `4` | Cambiar de pestaña en la ventana grande |

Todos los atajos se pueden cambiar en los ajustes. El modo compacto y la actualización no tienen tecla por defecto. También puedes mostrar u ocultar la ventana con un mando.

## 🔒 Privacidad

- Las claves API se cifran solo para tu cuenta (Windows DPAPI en Windows; en Linux y macOS, un archivo de clave privado que solo tú puedes leer).
- Los archivos locales de estadísticas de Steam solo se **leen**, nunca se modifican.
- Tu imagen de fondo se queda en tu ordenador; solo se guarda su ubicación.
- Sin telemetría. HundoHunter solo habla con Steam, el servicio de IA que elijas, el servicio de traducción y GitHub (para buscar actualizaciones).
- La página de overlay para streams solo se puede abrir desde tu propio ordenador (127.0.0.1).
- Las capturas y tarjetas se guardan en tu carpeta de Imágenes; no se sube nada.
- El estado en Discord es opcional y solo pasa por la aplicación de Discord de tu ordenador.
- El informe de errores abre una incidencia en GitHub que puedes leer antes de enviarla. Las claves API, los Steam ID, los correos y tu nombre de usuario se ocultan.

## ❓ Solución de problemas

| Problema | Prueba esto |
|---|---|
| No se ve encima del juego | Pon el juego en **ventana sin bordes / pantalla completa en ventana**. La pantalla completa exclusiva no puede mostrar otras ventanas. |
| No se pueden leer los logros | ¿Es correcta tu clave API? ¿Son públicos los *Detalles de juegos*? |
| Los logros aparecen tarde | ¿Steam está abierto y has iniciado el juego desde Steam? |
| Se detecta otro juego | Escribe el AppID del juego (el número de su enlace en la tienda) en *Elegir juego manualmente*. |
| La ventana desapareció | Pulsa `Ctrl` + `H` o haz clic en el icono de la bandeja. |

## 💝 Apoya HundoHunter

<p align="center"><img src="docs/hundos/idol_head.svg" height="56"></p>

HundoHunter es gratis y está hecho con cariño. Si te ayudó a completar un hundo, ¡puedes invitar a las Hundos a un dulce! Cada aporte trae nuevos temas, funciones y Hundos.

<p align="center">
  <a href="https://www.patreon.com/cw/HundoHunter"><img src="https://img.shields.io/badge/Patreon-%F0%9F%92%96-F96854?style=for-the-badge&logo=patreon&logoColor=white" alt="Patreon"></a>
  <a href="https://buymeacoffee.com/HundoHunter"><img src="https://img.shields.io/badge/Buy_Me_a_Coffee-%F0%9F%92%96-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=white" alt="Buy Me a Coffee"></a>
</p>

## 📜 Aviso legal y créditos

HundoHunter es un proyecto de fans independiente y **no está afiliado a Valve Corporation ni a Steam**. Steam y el logotipo de Steam son marcas comerciales de Valve Corporation. Los datos de juegos y logros vienen de la Steam Web API.

Las Hundos y todo el arte de los temas son dibujos vectoriales originales hechos para HundoHunter. Fuente "Press Start 2P" de CodeMan38, SIL Open Font License 1.1. Fuente "Mr Dafoe" de Alejandro Paul (Sudtipos), SIL Open Font License 1.1. Iconos de Material Design Icons de Pictogrammers, Apache License 2.0.

<p align="center">
  Hecho con 💖 por <b>Wavemint</b><br>
  <img src="docs/hundos/neko_head.svg" height="40"><img src="docs/hundos/moon_head.svg" height="40"><img src="docs/hundos/idol_head.svg" height="40"><img src="docs/hundos/goth_head.svg" height="40">
</p>
