---
title: "Reportes de bloqueos"
layout: default
permalink: /es/freeze-reports/
lang: es
---

# Reportes de bloqueos

A veces una pantalla de la app deja de responder un momento. Tocas y no pasa nada, y luego despierta. Cuando eso dura 2 segundos o más, la app escribe en silencio una nota corta de lo que estaba haciendo. Eso es un **reporte de bloqueo**. Sirve para que, si la app va lenta o se atora, tú o quien te ayuda puedan ver por qué, en lugar de adivinar.

No tienes que hacer nada. La mayoría de las personas nunca abre esta página. Está para el día en que algo se sienta raro.

## Antes de empezar

- No hay nada que comprar ni que encender. Es gratis y siempre está funcionando.
- Los reportes se quedan en **tu servidor**. No se envían a ningún otro lado.
- Un reporte no es un mensaje de error ni significa que hiciste algo mal.

## Dónde encontrarlo

**En una laptop:** haz clic en el engrane de abajo a la izquierda para abrir **Configuración** y luego **Computadora**. Baja hasta la sección **Bloqueos de la app**.

**En un celular:** toca **Más** en la barra de abajo, luego **Configuración**, después **Computadora**, y baja hasta **Bloqueos de la app**. Usa la flecha de atrás, arriba, para volver a la lista.

Las capturas están en inglés.

![La sección Bloqueos de la app en la página Computadora, con "No hay bloqueos guardados"]({{ '/images/freezes-laptop.png' | relative_url }})

*Bloqueos de la app, en la página Computadora. Esta está vacía, que es la buena noticia.*

## Cómo usarlos, paso a paso

1. Abre **Configuración**, luego **Computadora** y baja hasta **Bloqueos de la app**.
2. Si ves "No hay bloqueos guardados", la app no se ha bloqueado. Listo.
3. Si ves filas, cada una dice algo como "Atorado por 6 segundos", con el día y la hora debajo.
4. Presiona **Detalles** en una fila para abrir la nota técnica. Presiónalo otra vez para cerrarla.
5. Para pedir ayuda, presiona **Copiar todo**. El botón cambia a "Copiado". Pega el texto en un mensaje para quien te da soporte.
6. Cuando el problema se resuelva, presiona **Borrar** para quitar los reportes.

## Cada opción explicada

**Una fila de reporte.** El título dice cuánto tiempo estuvo atorada la pantalla. Debajo ves cuándo pasó y una de dos líneas:
- "Se recuperó por sí sola." La pantalla volvió a responder.
- "No se había recuperado cuando se envió." La pantalla seguía atorada cuando se escribió el reporte.

**Detalles.** Abre un texto pequeño con la historia técnica: en qué pantalla estabas, qué seguía en proceso, tus últimos toques (qué tipo de toque y dónde, no las palabras que escribiste), partes lentas que midió el navegador y los últimos pasos. Está pensado para quien arregla el problema, no para que tú lo leas. El texto de este detalle aparece en inglés.

**Ver anteriores (N).** La página muestra los 20 reportes más nuevos. Este botón muestra 20 más cada vez.

**Copiar todo.** Pone todos los reportes en tu portapapeles como texto simple. Si tu navegador bloquea el copiado, el botón dice "No se pudo copiar".

**Borrar.** Pregunta "¿Borrar todos los bloqueos guardados?" y explica que borra los reportes, que sirven para encontrar por qué se bloqueó la app. Presiona **Borrar** para confirmar o **Cancelar** para conservarlos. No se puede deshacer.

## Cuándo se escribe un reporte y cuándo no

- Se escribe un reporte cuando una pantalla se atora 2 segundos o más.
- Si una pantalla sigue atorada, la app manda como máximo un reporte por minuto.
- Cambiar a otra app, bloquear el celular o dejar que la computadora se duerma no cuenta como bloqueo.
- La app guarda los últimos 200 reportes. Los más viejos se descartan.

## Ejemplos reales

- **Una coach en el celular** nota que el chat se atora cada vez que abre una conversación larga. Presiona **Copiar todo** y se lo manda a quien administra su instalación. Esa persona ve qué pantalla estaba ocupada.
- **Un terapeuta** revisa la página solo cuando la app se sintió lenta. "No hay bloqueos guardados" le dice que la lentitud fue de su internet, no de la app.
- **Una consultora** borra la lista después de un arreglo, para que cualquier reporte nuevo sea claramente nuevo.
- Confidencialidad: el reporte registra lo que la app estaba haciendo, no lo que escribiste en tus chats. Aun así, léelo antes de reenviarlo y mándalo solo a alguien en quien confíes para tu instalación.

## Costos y límites

- Gratis. No usa IA.
- Se conservan: los últimos 200 reportes en tu servidor.
- Umbral: 2 segundos.

## Problemas comunes y soluciones

- **"No se pudieron cargar los reportes."** La página no pudo llegar a tu servidor. Recarga e inténtalo de nuevo.
- **"No se pudo copiar".** Tu navegador bloqueó el copiado. Abre **Detalles** y selecciona el texto a mano.
- **Veo muchos reportes.** La app está batallando. Cópialos todos y pide ayuda, y considera liberar espacio en disco (mira [Archivos temporales]({{ '/es/temp-files/' | relative_url }})).
- **Dice "No hay bloqueos guardados" pero la app se siente lenta.** La causa puede ser tu conexión o tu proveedor de IA, y no la pantalla de la app.

## Funciones relacionadas

- [Archivos temporales]({{ '/es/temp-files/' | relative_url }}): un disco lleno puede volver todo más lento.
- [Control de la laptop]({{ '/es/laptop-control/' | relative_url }})
- [Costos]({{ '/es/costs/' | relative_url }})

[Todos los artículos de ayuda]({{ '/es/' | relative_url }})
