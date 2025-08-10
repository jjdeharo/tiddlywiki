# codecopy-plugin-ai

Plugin para **TiddlyWiki** que añade un botón de **copiar** y un menú desplegable para enviar el contenido de un bloque directamente a diferentes chatbots de inteligencia artificial.

## Características

- Botón 📋 para copiar al portapapeles el contenido de:
  - Bloques de código (` ``` `)
  - Citas (`<<< ... <<<`)
- Menú desplegable **Enviar a…** que abre una nueva pestaña con el servicio seleccionado y el contenido del bloque.
- Aviso visual breve cuando se copia el texto.
- Estética unificada para botones y desplegable.
- En las citas, la barra de herramientas se muestra flotando a la derecha sin añadir margen extra al resto del texto.

## Servicios disponibles

- **Bloques de código**: ChatGPT, Grok, Perplexity, Claude  
- **Citas**: ChatGPT, Grok, Microsoft Copilot, Perplexity, Claude

## Instalación

1. Descarga el archivo [`codecopy-plugin-ai.tid`](./codecopy-plugin-ai.tid).
2. Abre tu TiddlyWiki y arrástralo dentro o impórtalo desde el menú **Import**.
3. Guarda el wiki para que el plugin quede instalado.

## Uso

- **📋 Copiar**: copia el contenido del bloque al portapapeles.
- **Enviar a…**: selecciona un servicio y el contenido se abrirá automáticamente en una nueva pestaña con la URL correspondiente.

## Desinstalación

1. Ve a **Panel de control → Plugins**.
2. Abre el plugin **codecopy-plugin-ai**.
3. En el menú del tiddler, selecciona **Eliminar** (borrar).
4. Guarda el wiki.

## Compatibilidad

- Requiere **TiddlyWiki 5.2.0** o superior.
- Navegador con soporte para `navigator.clipboard.writeText()`.

## Licencia

Este plugin está bajo licencia **[Creative Commons Attribution-ShareAlike (CC BY-SA)](https://creativecommons.org/licenses/by-sa/4.0/deed.es)**.
