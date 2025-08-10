# codecopy-plugin-ai

Plugin para **TiddlyWiki** que añade un botón de **copiar** y un menú desplegable para enviar el contenido de un bloque directamente a diferentes chatbots de inteligencia artificial.

## características

- Botón 📋 para copiar al portapapeles el contenido de:
  - Bloques de código (` ``` `)
  - Citas (`<<< ... <<<`)
- Menú desplegable **Enviar a…** que abre una nueva pestaña con el servicio seleccionado y el contenido del bloque.
- Aviso visual breve cuando se copia el texto.
- Estética unificada para botones y desplegable.
- En las citas, la barra de herramientas se muestra separada del texto para mantener la legibilidad.

## servicios disponibles

- **Bloques de código**: ChatGPT, Grok, Perplexity, Claude  
- **Citas**: ChatGPT, Grok, Microsoft Copilot, Perplexity, Claude

## instalación

1. Descarga el archivo [`codecopy-plugin-ai.tid`](./codecopy-plugin-ai.tid).
2. Abre tu TiddlyWiki y arrástralo dentro o impórtalo desde el menú **Import**.
3. Guarda el wiki para que el plugin quede instalado.

## uso

- **📋 Copiar**: copia el contenido del bloque al portapapeles.
- **Enviar a…**: selecciona un servicio y el contenido se abrirá automáticamente en una nueva pestaña con la URL correspondiente.

## desinstalación

1. Abre **Más → Complementos** en TiddlyWiki.
2. Localiza `codecopy-plugin-ai` y haz clic en **Desinstalar**.
3. Guarda el wiki.

## compatibilidad

- Requiere **TiddlyWiki 5.2.0** o superior.
- Navegador con soporte para `navigator.clipboard.writeText()`.

## licencia

Indicar aquí la licencia que corresponda.
