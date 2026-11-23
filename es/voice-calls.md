---
title: "Llamadas de voz"
layout: default
permalink: /es/voice-calls/
lang: es
---

# Llamadas de voz

## Qué es y para qué sirve

Una llamada de voz te deja hablar en voz alta con un Bot, como una llamada telefónica, y oír su respuesta. Puedes interrumpirlo. Es práctico cuando tienes las manos ocupadas, cuando vas caminando o cuando piensas mejor hablando que escribiendo. Todo lo que se dice en la llamada queda también escrito en el chat del Bot al terminar, así que no se pierde nada.

## Antes de empezar

- **Una clave de Google AI.** El único proveedor que funciona hoy es **Gemini Live**, de Google. Usa tu propia clave de Google AI, así que le pagas directo a Google. Los otros dos de la lista, **xAI Voice** y **OpenAI Realtime**, aparecen en gris y todavía no se pueden elegir.
- **El servidor debe estar listo para guardar claves.** Si no, la página de Voz dice: "No se pueden agregar claves hasta que el servidor tenga su clave de cifrado."
- **Un micrófono** y un navegador con permiso para usarlo.
- **Costo:** alrededor de **1 centavo por minuto**, como indica la página de Voz: "Le pagas directo al proveedor, alrededor de 1 centavo por minuto." El costo de la llamada también aparece en [Costos]({{ '/es/costs/' | relative_url }}), bajo el Bot, y cuenta para tu [Límite mensual]({{ '/es/monthly-limit/' | relative_url }}).

## Cómo configurarla

- **Laptop:** abre **Configuración** y elige **Voz** en la lista de la izquierda.
- **Celular:** toca **Más** en la barra de abajo, luego **Configuración**, después **Voz**, y usa la flecha de regreso para volver.

Un puntito junto a Voz significa que todavía falta tu clave.

1. En **Proveedor de voz**, deja seleccionado **Gemini Live**.
2. En la fila **Tu clave**, pega tu clave de Google AI en el campo "Pega tu clave de Google AI".
3. Toca **Guardar clave**. El botón dice "Revisando…" un momento. Si Google la acepta, verás "Clave guardada." y la fila dirá **Clave guardada**, con "Se guarda cifrada en el servidor."
4. Si quieres, ajusta **Máximo por día**, **Llamada más larga** y la voz, como se explica abajo.

Las capturas están en inglés.

![Configuración, página de Voz con Gemini Live seleccionado, los límites y la lista de voces]({{ '/images/voice-laptop.png' | relative_url }})

*La página de Voz en Configuración.*

Para quitar una clave que guardaste en la app, toca **Quitar** en esa fila.

## Cómo hacer una llamada

1. Abre el chat de un solo Bot.
2. Toca el botón del **teléfono** en el chat. Su etiqueta es "Llamada con" y el nombre del Bot.
3. La primera vez, tu navegador te pide usar el micrófono. Permítelo.
4. Se abre la pantalla de llamada con la cara del Bot. Primero dice **Conectando**, luego **Escuchando…**.
5. Habla con normalidad. Haz una pausa cuando termines. Puedes interrumpirlo mientras habla.
6. Toca **Colgar** para terminar.

Durante la llamada, la pantalla muestra en qué está el Bot: conectando, escuchando, pensando, "En eso…" (cuando el Bot está haciendo el trabajo de verdad), hablando, "Micrófono apagado" cuando silencias, reconectando, y "Llamada terminada" al final.

## Los botones de la pantalla de llamada

- **Silenciar micrófono** apaga tu micrófono. Cambia a **Activar micrófono**.
- **Subtítulos** muestra u oculta en pantalla las últimas líneas de la conversación.
- **Colgar** termina la llamada.
- **Flecha de regreso** (arriba a la izquierda): "Volver al chat. La llamada sigue activa." Una barra pequeña mantiene la llamada a la mano.
- **Abrir en una ventana pequeña** (arriba a la derecha): en una computadora con pantalla ancha y un navegador que lo permita, la llamada pasa a una ventana pequeña que se queda encima de todo. No aparece en celulares.
- **Engrane:** "Voz y velocidad", el mismo selector que está en Configuración.
- Si un Bot necesita un toque tuyo, la pantalla avisa que hay una tarjeta esperando y te lleva al chat.

## Cada ajuste explicado

**Proveedor de voz.** La opción de selección. Solo Gemini Live funciona.

**Máximo por día.** En dólares. Empieza en **$2**. La nota dice "0 significa sin límite. Gastado hoy: …". El rango permitido es de $0 a $1000. Cuando el gasto de hoy lo alcanza, las llamadas ya no empiezan y ves: "Llegaste al límite de voz de hoy: $2.00. Auméntalo en Configuración, Voz, o llama de nuevo mañana."

**Llamada más larga.** En minutos. Empieza en **10** y puede llegar a **30**. La llamada termina sola con "La llamada llegó a su límite de N minutos."

**Voz y velocidad.**

- **Voz:** doce voces, cada una con una palabra que describe su carácter, en inglés: Kore (Firm), Puck (Upbeat), Charon (Informative), Zephyr (Bright), Aoede (Breezy), Sulafat (Warm), Achird (Friendly), Schedar (Even), Gacrux (Mature), Vindemiatrix (Gentle), Umbriel (Easy-going), Sadaltager (Knowledgeable). La predeterminada es Kore. Toca la flechita de reproducir junto a un nombre para oír una muestra corta antes de elegir.
- **Velocidad:** un control deslizante de 0.8x a 1.25x, que empieza en 1x. "La velocidad cambia un poco el tono. Una voz nueva empieza en tu próxima llamada."

## Cómo funciona una llamada

La voz que oyes es solo la voz del Bot. Cuando pides algo de verdad, como un archivo, un calendario o tus notas, la voz le pasa la petición al Bot real, dice que está en eso y te lee la respuesta con pocas palabras. Eso es el estado **En eso…**. Las llamadas son cortas y habladas, así que espera titulares, no listas largas.

**Seguridad.** Una petición dicha en una llamada nunca aprueba por sí sola nada riesgoso. Enviar, pagar, eliminar o instalar sigue necesitando tu toque en una tarjeta del chat, como siempre. La voz tampoco afirma por su cuenta datos sobre tu agenda, tus archivos o tu dinero. Primero le pregunta al Bot.

## Ejemplos reales

- **Una coach** camina entre sesiones y pregunta: "¿Qué tengo esta tarde y qué acordamos con el cliente del jueves?" El Bot responde en breve, y el texto completo queda en el chat.
- **Un consultor** dicta en voz alta el plan de un taller, y después lee la versión escrita en el chat.
- **Una terapeuta** debe tener cuidado. Una llamada va de tu dispositivo a Google, así que no menciones nombres de clientes ni datos de salud en una llamada.

## Costos y límites

- Alrededor de 1 centavo por minuto, a Google, con tu propia clave.
- Un límite diario (**$2** al inicio) y una llamada más larga (**10** minutos al inicio, **30** como máximo).
- El trabajo real que haga el Bot durante la llamada se cobra como cualquier otro trabajo de un Bot.
- Al terminar, la pantalla muestra la duración y el costo, y "Las palabras están en tu chat."

## Problemas comunes y soluciones

- **"Primero agrega tu clave de voz."** Todavía no tienes clave. La app abre Configuración, Voz.
- **"La llamada no se conectó. Revisa la clave en Configuración, Voz."** Puede que la clave esté mal. Pégala de nuevo.
- **"Google rechazó esa clave. Revísala e inténtalo de nuevo."** Consigue una clave nueva en tu cuenta de Google.
- **"El acceso al micrófono está bloqueado. Permítelo en la configuración del navegador."** Permite el micrófono para este sitio.
- **"Este navegador no puede usar el micrófono aquí. Abre la app desde su dirección segura."** Usa la dirección segura normal de la app.
- **"La voz no está disponible en este servidor."** El servidor no admite llamadas de voz.
- **"Se cortó la llamada."** Inténtalo de nuevo. Antes, la app intenta reconectar varias veces.
- **"Llegaste al límite de voz de hoy."** Sube **Máximo por día** o llama mañana.

## Funciones relacionadas

- [Dictado por voz]({{ '/es/voice-typing/' | relative_url }})
- [Costos]({{ '/es/costs/' | relative_url }})
- [Límite mensual]({{ '/es/monthly-limit/' | relative_url }})
- [Qué IA usa cada Bot]({{ '/es/which-ai/' | relative_url }})

[Todos los artículos de ayuda]({{ '/es/' | relative_url }})
