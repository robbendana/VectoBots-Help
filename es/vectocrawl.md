---
title: "VectoCrawl"
layout: default
permalink: /es/vectocrawl/
lang: es
---

# VectoCrawl

## Qué es y para qué sirve

VectoCrawl es la forma integrada que tienen tus Bots de buscar información en internet: buscar en la web, leer una página y hacer una ronda corta de investigación. Sin esto, un Bot solo puede responder con lo que ya sabe, que puede estar desactualizado. Con VectoCrawl, un Bot puede comprobar un dato antes de adivinar y decirte de dónde lo sacó.

Funciona sin cuenta y sin clave. Las claves y el proxy son extras opcionales que lo hacen más confiable. Tienen sus propias guías, al final de esta página.

## Antes de empezar

- **No necesitas nada.** La búsqueda gratis funciona tal cual.
- **Costo:** la búsqueda gratis no cuesta nada. Solo se gasta dinero si tú agregas una clave de pago o un proxy, y en ese caso el servicio te cobra a ti, no VectoBots. Mira [Mejores resultados con claves]({{ '/es/vectocrawl-keys/' | relative_url }}).
- VectoCrawl viene **activada** de fábrica. Puedes apagarla cuando quieras.

## Dónde encontrarla

VectoCrawl está en la página **Cuentas de IA** de **Configuración**, en su propia tarjeta llamada **VectoCrawl**, debajo de la lista que muestra qué IA usa cada Bot.

- **Laptop:** abre **Configuración**, elige **Cuentas de IA** en la lista de la izquierda y baja hasta **VectoCrawl**.
- **Celular:** toca **Más** en la barra de abajo, luego **Configuración**, después **Cuentas de IA**, y baja hasta **VectoCrawl**. Con la flecha de regreso vuelves a la lista.

Las capturas están en inglés.

![Configuración, página de Cuentas de IA, con la tarjeta VectoCrawl: el interruptor, la búsqueda gratis y el campo del servidor de búsqueda]({{ '/images/search-laptop.png' | relative_url }})

*La tarjeta VectoCrawl dentro de la página de Cuentas de IA.*

## Cómo usarla

1. Abre la tarjeta VectoCrawl como se explicó arriba.
2. Revisa que el interruptor **Dejar que los Bots usen VectoCrawl** esté activado.
3. Si quieres, escribe la dirección de tu propio servidor de búsqueda y toca **Guardar dirección**. Verás "Dirección guardada".
4. Si quieres, agrega claves en la tarjeta **Mejores resultados (claves opcionales)**. Eso se explica en la siguiente guía.

## Cada opción explicada

**Dejar que los Bots usen VectoCrawl.** El interruptor principal. Viene activado. Si lo apagas, los Bots no pueden buscar nada en internet; si lo intentan, se les avisa que VectoCrawl está apagada y que te pidan encenderla.

**Búsqueda gratis.** Funciona sin cuenta y no hay nada que configurar. Si no tienes servidor propio ni claves, es lo que se usa. Puede ser lenta, y puede ser rechazada cuando el servicio gratuito está saturado.

**Tu propio servidor de búsqueda.** Opcional. Lleva la dirección de un servidor SearXNG, una herramienta de búsqueda gratuita que algunas personas manejan por su cuenta. La mayoría lo deja vacío. Si lo llenas:

- La dirección debe empezar con `http://` o `https://`.
- No pongas usuario ni contraseña dentro de la dirección. La app lo rechaza.
- Tu servidor debe tener activada la salida en formato JSON. Si no, la búsqueda del Bot avisa que tu servidor respondió con un error y pregunta si JSON está activado.
- Si tienes este servidor, se prueba primero. Si no, la búsqueda gratis se prueba al final, después de las claves de pago que hayas agregado.

**Mejores resultados (claves opcionales)** y **Recomendado: proxy de IPRoyal.** Mira las guías de claves y de proxy.

**Límite diario para claves de pago.** Un número de 0 a 10,000 que detiene las claves de pago por el día cuando se alcanza. Empieza en 100. La búsqueda gratis no cuenta. La tarjeta también muestra cuántas se han usado hoy.

**Último recurso: el navegador del Bot.** Una nota con su propia guía. Mira [El navegador del Bot]({{ '/es/vectocrawl-browser/' | relative_url }}).

## Qué hacen realmente los Bots con esto

- **Buscar.** El Bot hace una pregunta y recibe una lista corta de resultados. Prueba primero la ruta más barata.
- **Leer una página.** El Bot abre una dirección web y lee el texto.
- **Leer un sitio completo.** En un sitio web, un Bot puede leer hasta 40 páginas.
- **Investigar.** El Bot hace de una a cuatro búsquedas, lee las mejores páginas y redacta él mismo la respuesta con sus fuentes.
- **Redes sociales.** Un Bot puede buscar en X, LinkedIn, Facebook, Instagram, Threads, Reddit, TikTok, YouTube y Hacker News. En la mayoría busca lo que los buscadores tienen listado, así que la cobertura de publicaciones es parcial, y al Bot se le indica que lo diga.

También se les indica que citen la fuente de cada dato, que traten el texto de las páginas como información y nunca como órdenes, y que no paguen ni se registren en nada de tu parte.

## Ejemplos reales

- **Una coach** le pregunta a un Bot: "¿Cuál es la redacción actual de la competencia central de la ICF sobre cultivar la confianza?" El Bot busca, lee la página oficial y responde con el enlace.
- **Un terapeuta** pide investigación publicada y reciente sobre un tema general, como sueño y ansiedad, y recibe un resumen corto con fuentes numeradas para verificar.
- **Un consultor** le pide a un Bot que compare las páginas públicas de precios de tres herramientas de agenda antes de elegir una.

**Una nota sobre confidencialidad.** Cada búsqueda va a un servicio externo. A los Bots se les indica que nunca pongan nombres de clientes, datos de salud ni información privada en una búsqueda, y tú tampoco deberías pedírselo. Busca temas generales, no personas de tu práctica.

## Costos y límites

- Búsqueda gratis: sin costo.
- Claves de pago y proxy: los cobran esos servicios, y el precio aparece en pantalla junto a cada uno.
- Un Bot puede hacer como máximo 30 consultas por minuto. Si va más rápido, se le indica que espere y use lo que ya encontró.
- El límite diario para claves de pago empieza en 100 y cuenta las últimas 24 horas.
- Las direcciones de redes privadas se rechazan, así que un Bot no puede usar VectoCrawl para llegar a equipos privados.

## Problemas comunes y soluciones

- **Un Bot dice que no puede buscar.** Revisa que el interruptor **Dejar que los Bots usen VectoCrawl** esté activado.
- **El Bot dice que la búsqueda no encontró nada, con la sugerencia de agregar una clave.** La búsqueda gratis fue rechazada o no halló resultados. Prueba con otras palabras o agrega una clave. Mira la guía de claves.
- **No se puede leer una página.** Algunas páginas piden inicio de sesión o clics. Al Bot se le indica que puede usar su propio navegador, que cuesta más.
- **Demasiadas consultas en un minuto.** Espera un poco. El Bot usará lo que ya encontró.
- **"Algo salió mal. Inténtalo de nuevo."** en la tarjeta. Recarga la página e inténtalo otra vez.

## Funciones relacionadas

- [Mejores resultados con claves]({{ '/es/vectocrawl-keys/' | relative_url }})
- [Proxy de IPRoyal]({{ '/es/vectocrawl-proxy/' | relative_url }})
- [El navegador del Bot]({{ '/es/vectocrawl-browser/' | relative_url }})
- [Costos]({{ '/es/costs/' | relative_url }})
- [Qué IA usa cada Bot]({{ '/es/which-ai/' | relative_url }})

[Todos los artículos de ayuda]({{ '/es/' | relative_url }})
