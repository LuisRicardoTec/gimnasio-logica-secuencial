# Gimnasio Mental de Lógica Secuencial — TC1004B

Versión 2.1. Sitio web estático e independiente para GitHub Pages.

## Contenido

1. **Contador BCD decremental síncrono**. 9→8→…→0→9; cuatro flip-flops D; RESET síncrono; recuperación de estados inválidos.
2. **Contador de secuencia personalizada**. 0→3→5→6→1→4→0; tres flip-flops D; EN y RESET síncronos; recuperación de estados inválidos.
3. **Moore: cadena de frío**. Alarma retenida después de dos lecturas anómalas consecutivas.
4. **Mealy: gabinete IoT**. Detección de apertura no autorizada con autorización de un ciclo.

Cada estación incluye cinco preguntas autocorregibles (mínimo 4/5), reflexión individual y enlace a una simulación de CircuitVerse. Al finalizar, el estudiante descarga un **comprobante HTML** con datos, respuestas, reflexiones y enlaces para entregar en Canvas.

## Publicación o actualización en GitHub Pages

1. En el repositorio GitHub existente, sustituye el archivo **`index.html`** por el de este paquete.
2. Opcionalmente sustituye también `README.md`.
3. Confirma los cambios mediante **Commit changes**.
4. Si GitHub Pages ya estaba configurado en **Settings → Pages → Deploy from a branch → main / (root)**, no hay que configurarlo otra vez.
5. Espera a que termine el despliegue y actualiza la página. Si ves la versión anterior, prueba una recarga forzada (Ctrl+Shift+R o Cmd+Shift+R).

## Nota para el docente

- La versión 2.1 utiliza una clave de almacenamiento local nueva porque cambió el orden de las estaciones; no mezcla respuestas anteriores.
- Las preguntas se califican automáticamente (20 puntos en total); las reflexiones y los circuitos requieren revisión docente.
- Los enlaces se validan por dominio `circuitverse.org`, pero la página no verifica la funcionalidad del circuito ni la autoría.
- El comprobante se genera localmente, no es una certificación inviolable.
- Los estudiantes deben entregar el archivo HTML descargado en Canvas, no el código fuente del sitio.
- Para contador BCD, el RESET es **síncrono** y carga 1001; para el contador personalizado, RESET es **síncrono** y carga 000.
- No se utilizan servicios externos, bibliotecas CDN ni backend; los datos permanecen en el navegador salvo los enlaces que los estudiantes decidan compartir.
