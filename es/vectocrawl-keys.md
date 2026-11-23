---
title: "Mejores resultados con claves"
layout: default
permalink: /es/vectocrawl-keys/
lang: es
---

# Mejores resultados con claves

## Qué es y para qué sirve

[VectoCrawl]({{ '/es/vectocrawl/' | relative_url }}) funciona gratis. Una búsqueda gratis puede ser lenta, puede ser rechazada cuando el servicio gratuito está saturado y no puede leer todas las páginas. Una **clave** es un código privado de un servicio de búsqueda al que tú te registras. Cuando la pegas, tus Bots usan también ese servicio, y los resultados mejoran y son más confiables.

Las claves son totalmente opcionales. Si no sabes si necesitas una, no la necesitas.

## Antes de empezar

- **Una clave la consigues en el sitio del propio servicio.** Creas ahí una cuenta y te dan un código largo. Ese código es el que pegas en VectoBots.
- **El servicio te cobra a ti, no VectoBots.** Los precios de abajo vienen de la app. Revisa el sitio del servicio antes de registrarte, porque los precios son suyos y pueden cambiar.
- **El servidor debe estar listo para guardar claves.** Si no lo está, la tarjeta dice "Todavía no se pueden guardar claves en este servidor." Los campos aparecen atenuados. Es un paso de configuración del servidor, no algo que se arregle en esta página: pide ayuda a tu Bot principal o a quien instaló VectoBots para ti.
- Una clave se guarda de forma segura y **nunca se vuelve a mostrar** después de guardarla. Conserva tu propia copia en un lugar seguro, como tu administrador de contraseñas.

## Cómo agregar una clave

- **Laptop:** abre **Configuración**, elige **Cuentas de IA** a la izquierda y baja hasta la tarjeta **Mejores resultados (claves opcionales)**.
- **Celular:** toca **Más** en la barra de abajo, luego **Configuración**, después **Cuentas de IA**, y baja hasta **Mejores resultados (claves opcionales)**. La flecha de regreso te devuelve a la lista.

1. Busca en la lista el servicio que quieres.
2. Haz clic en su campo, que dice "Pega la clave", y pega tu código.
3. Toca **Guardar**. Verás "Guardada", y la fila mostrará **Agregada**.

Las capturas están en inglés.

![Configuración, página de Cuentas de IA, con la tarjeta VectoCrawl y el inicio de la lista de claves opcionales]({{ '/images/search-laptop.png' | relative_url }})

*La tarjeta de claves opcionales está debajo de la tarjeta principal de VectoCrawl.*

Para quitar una clave, toca **Quitar** en su fila. La fila vuelve a **Sin agregar**.

## Los servicios, uno por uno

Cada fila muestra una etiqueta: **Sin agregar**, **Agregada** o **Configurada en el servidor**. Algunas filas también muestran un precio. Una clave configurada en el servidor no tiene botón Quitar, porque se puso fuera de la app.

- **Brave Search.** Unos $5 por 1,000 búsquedas. Una buena primera opción si solo vas a agregar una.
- **Tavily.** Hecho para IA, con 1,000 búsquedas gratis al mes.
- **Exa.** Encuentra páginas por significado, con un pequeño crédito gratis al mes. Sirve cuando sabes qué quieres decir pero no las palabras exactas.
- **Firecrawl.** Lee páginas difíciles. Plan de pago desde unos $16 al mes. Se prueba cuando una página no se puede leer de la forma normal.
- **Clave de Jina Reader.** Sube el límite gratis de lectura de páginas. La lectura de páginas con Jina ya funciona sin clave, a un ritmo bajo. La clave sube ese ritmo.
- **Recomendado: proxy de IPRoyal.** Para sitios que bloquean la búsqueda gratis. Tiene su propia guía: [Proxy de IPRoyal]({{ '/es/vectocrawl-proxy/' | relative_url }}).

## En qué orden se prueban

No tienes que manejarlo, pero conviene saberlo:

1. Tu propio servidor de búsqueda, si agregaste uno.
2. Brave, luego Tavily, luego Exa, los que hayas agregado.
3. La búsqueda gratis, como último recurso.

Gana el primero que devuelve resultados. Para leer una página, primero se prueba la ruta gratis, luego Firecrawl si lo agregaste y luego Jina Reader.

## Límite diario para claves de pago

Debajo de las claves hay un campo numérico llamado **Límite diario para claves de pago**. Las claves de pago se detienen por el día al llegar a este número. La búsqueda gratis no cuenta. Debajo del nombre ves cuántas se usaron hoy, como "Hoy: N usadas."

- Empieza en **100**. Puedes poner cualquier número entero de 0 a 10,000.
- Cuenta cada llamada de pago durante las últimas 24 horas.
- Al alcanzar el límite, los Bots siguen trabajando solo con búsqueda gratis. Al Bot se le avisa que se alcanzó el límite diario.
- Con **0**, las claves de pago no se usan para nada.

Ponlo bajo mientras pruebas. Es tu red de seguridad contra una cuenta sorpresa.

## Ejemplos reales

- **Una coach independiente** agrega una clave de Brave y deja el límite en 100. Su Bot ahora encuentra artículos recientes de forma confiable al preparar un taller, y el cobro mensual se mantiene bajo.
- **Un consultor** que investiga mucho agrega Tavily por sus 1,000 búsquedas gratis al mes y fija el límite diario en 30 para quedarse bien dentro de eso.
- **Una terapeuta** no agrega ninguna clave. Las preguntas generales ocasionales funcionan bien con la búsqueda gratis y no gasta nada.

## Confidencialidad

Cada búsqueda va a un servicio externo, y un servicio de pago también ve tus preguntas. Nunca le pidas a un Bot que busque el nombre de un cliente, datos de salud ni nada que identifique a alguien de tu práctica.

## Costos y límites

- VectoBots no cobra nada por ninguna clave. El servicio te cobra directo a ti.
- Los únicos precios son los que aparecen en pantalla. Para cualquier otro, consulta con el servicio.
- La búsqueda gratis nunca cuenta para el límite diario.

## Problemas comunes y soluciones

- **El botón Guardar y los campos están atenuados.** La tarjeta dice "Todavía no se pueden guardar claves en este servidor." Es un paso de configuración del servidor. Pide ayuda a tu Bot principal o a quien instaló VectoBots para ti.
- **"Algo salió mal. Inténtalo de nuevo."** Revisa que pegaste la clave sola, sin espacios ni palabras de más, e inténtalo otra vez.
- **Guardaste una clave pero los resultados no cambiaron.** Revisa el límite diario. Si el conteo de hoy ya lo alcanzó, las claves de pago esperan hasta que baje.
- **Pegaste la clave equivocada y no puedes verla.** Las claves nunca se vuelven a mostrar. Toca **Quitar** y agrega la correcta.

## Funciones relacionadas

- [VectoCrawl]({{ '/es/vectocrawl/' | relative_url }})
- [Proxy de IPRoyal]({{ '/es/vectocrawl-proxy/' | relative_url }})
- [El navegador del Bot]({{ '/es/vectocrawl-browser/' | relative_url }})
- [Costos]({{ '/es/costs/' | relative_url }})
- [Límite mensual]({{ '/es/monthly-limit/' | relative_url }})

[Todos los artículos de ayuda]({{ '/es/' | relative_url }})
