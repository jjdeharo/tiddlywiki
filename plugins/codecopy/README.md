# codecopy-plugin

Plugin para **TiddlyWiki** que añade un botón de **copiar** en bloques de código (```) y en citas (<<< ... <<<).  
En el caso de las citas, el contenido copiado **excluye el propio botón**.

## características

- Botón 📋 para copiar el contenido de bloques de código.
- Botón 📋 para copiar el contenido de citas.
- Manejo automático de eventos para evitar añadir botones duplicados.
- Notificación visual breve cuando el texto se copia correctamente.

## instalación

1. Descarga el archivo [`codecopy-plugin.tid`](./codecopy-plugin.tid).
2. Ábrelo en tu TiddlyWiki y arrástralo dentro del wiki o impórtalo desde el menú **Import**.
3. Guarda el wiki para que el plugin quede instalado.

## uso

Una vez instalado:
- En cualquier bloque de código (```), aparecerá un botón 📋 en la parte superior derecha.
- En las citas (<<< ... <<<) también aparecerá un botón 📋 que copiará solo el contenido.
- Haz clic en el botón para copiar el texto al portapapeles.

## requisitos

- **TiddlyWiki 5.2.0** o superior (probado en versiones recientes).
- Navegador con soporte para `navigator.clipboard.writeText()`.

## licencia

Este plugin es de uso libre según la licencia de tu preferencia (añade aquí la licencia que corresponda).
