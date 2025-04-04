# OGame - Enviar recursos al planeta principal

Este script de Tampermonkey permite enviar automáticamente recursos desde tus colonias al planeta principal en OGame.

## Instalación

### Método 1: Instalación por URL (Recomendado)
1. Instala la extensión Tampermonkey en tu navegador:
   - [Chrome Web Store](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   - [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
   - [Microsoft Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)

2. Abre el Dashboard de Tampermonkey
3. Ve a la pestaña "Utilidades"
4. En el cuadro "Import from URL", pega la siguiente URL:
   ```
   https://raw.githubusercontent.com/Sri7ach1/OGame-Enviar-recursos-al-planeta-principal/refs/heads/main/ogame_send_to_principal.js
   ```
5. Haz clic en "Importar"

### Método 2: Instalación manual
1. Instala la extensión Tampermonkey en tu navegador
2. Haz clic en el icono de la extensión y selecciona "Crear un nuevo script..."
3. Copia todo el contenido del archivo `ogame_send_to_principal.js` y pégalo en el editor de Tampermonkey
4. Guarda el script presionando `Ctrl + S` o haciendo clic en el icono de guardar

## Uso

1. Inicia sesión en tu cuenta de OGame.
2. Verás un nuevo botón en la esquina superior derecha de la pantalla.
3. Selecciona tu planeta principal del menú desplegable.
4. Especifica el número de naves de carga grandes que deseas usar para el transporte.
5. Haz clic en "📦 Enviar a Principal" para iniciar el proceso.

## Características

- Envía recursos automáticamente desde todas tus colonias al planeta principal
- Permite seleccionar el planeta principal
- Configurable número de naves de carga grandes
- Interfaz intuitiva y fácil de usar

## Notas

- Asegúrate de tener suficientes naves de carga grandes en cada colonia
- El script respeta los tiempos de carga de la página para evitar errores
- Los datos de configuración se guardan en el almacenamiento local del navegador

## Soporte

Si encuentras algún problema o tienes sugerencias, por favor abre un issue en el repositorio. 