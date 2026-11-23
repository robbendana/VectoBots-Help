---
title: "Qué IA usa cada Bot"
layout: default
permalink: /es/which-ai/
lang: es
---

# Qué IA usa cada Bot

Cada uno de tus Bots piensa con una IA. Esta pantalla te deja elegir qué IA usa cada Bot y, si quieres, con qué modelo y cuánto esfuerzo.

Existe porque cada trabajo le queda mejor a una IA distinta. Un Bot que redacta informes largos y uno que ordena tu correo no necesitan la misma, y tampoco cuestan lo mismo.

## Antes de empezar

- Necesitas al menos una IA conectada a tu servidor: una suscripción, como Claude o ChatGPT, o una clave de API. Si una IA no aparece en la lista, todavía no está configurada.
- Cambiar la IA no cuesta nada. Lo que cuesta el trabajo después depende de la IA que elijas. Mira "Costos" más abajo.

![Configuración, Cuentas de IA, con la tarjeta Qué IA usa cada Bot: una fila por Bot con un menú para la IA y una sección Modelo y esfuerzo]({{ '/images/ai-laptop.png' | relative_url }})

*Configuración, Cuentas de IA. Las capturas están en inglés.*

## Cómo cambiarla

**En la laptop:**

1. Abre **Configuración**. A la izquierda hay una lista de páginas.
2. Haz clic en **Cuentas de IA**.
3. En la tarjeta **Qué IA usa cada Bot**, busca la fila del Bot.
4. Abre el menú de la derecha y elige una IA.

**En el teléfono:** toca **Más** en la barra de abajo, luego **Configuración** y después **Cuentas de IA**, y sigue los pasos 3 y 4. Usa la flecha de regreso para volver a la lista.

La app lo confirma con un aviso: el Bot usará esa IA y empieza una conversación nueva, pero lo que sabe se conserva. Por ahora, ese aviso puede salir en inglés.

## Cada opción explicada

**El menú de IA.** Muestra las IA que tu servidor puede usar. Las que la app conoce son: **Suscripción a Claude**, **Suscripción a ChatGPT**, **Clave de API de Anthropic**, **API de DeepSeek**, **API de OpenRouter**, un **Modelo local** (uno que corre en tu propia computadora o red) y **Pi (su propia configuración)**. Solo ves las que aplican a tu caso.

**Modelo y esfuerzo.** Una sección desplegable bajo cada Bot. Ábrela para elegir:

- **Modelo.** Lo predeterminado es **Modelo predeterminado**. La lista muestra los modelos que ofrece esa IA.
- **Esfuerzo.** Lo predeterminado es **Esfuerzo predeterminado**. Más esfuerzo significa que el Bot piensa más antes de responder; las opciones dependen del modelo. Si cambias a un modelo que no ofrece el esfuerzo que tenías, el esfuerzo vuelve al predeterminado.

Deja ambos en lo predeterminado, salvo que tengas un motivo. La mayoría de las personas nunca necesita tocarlos.

**La línea de costo bajo el nombre de cada Bot.** Dice cómo se paga el trabajo de ese Bot:

- **Usa tu plan de IA**: una suscripción de tarifa fija.
- **Se paga por uso con tu clave**: cada trabajo cuesta dinero.
- **Usa sus propios ajustes**: un Modelo local o Pi. El costo depende de cómo esté configurado.

## Qué pasa cuando lo cambias

Pasar un Bot a otra IA **empieza una conversación nueva**. Lo que sabe se queda: su memoria y sus notas se conservan. Solo el hilo de la conversación en curso empieza de cero.

Si cambias solo el modelo o el esfuerzo, ves un aviso corto, como "Anchor usará el modelo predeterminado." o "Anchor pensará con esfuerzo alto."

Si eliges un Modelo local, la app puede mostrar una advertencia. La app lo describe como un modelo sin factura de IA que suele ser más débil que Claude o GPT.

## Ejemplos

Una coach deja su Bot principal en su suscripción a Claude, porque ya paga una tarifa fija. Pasa un segundo Bot, que resume artículos largos, a un modelo más barato con clave de API. Ve el efecto en [Costos]({{ '/es/costs/' | relative_url }}).

Un consultor nota que un Bot con plan gasta mucho de su límite semanal. Pasa sus trabajos pesados a una clave de API y deja un límite mensual puesto para no llevarse sorpresas.

Ten presente que lo que un Bot lee se envía a la empresa detrás de la IA que elijas. Para material de clientes, elige una IA cuyas condiciones te den confianza.

## Costos

La app no fija los precios. Una **suscripción** es una tarifa fija que ya pagas. Una **clave de API** la cobra por uso esa empresa. La página de Costos muestra la diferencia. Conviene poner un [Límite mensual]({{ '/es/monthly-limit/' | relative_url }}) cuando los Bots trabajan con clave.

## Problemas comunes

- **Mi IA no está en la lista.** Todavía no está conectada en tu servidor.
- **"No se pudo cambiar."** El cambio no se guardó. Intenta de nuevo.
- **El Bot olvidó de qué hablábamos.** Después de cambiar de IA, la conversación empieza de nuevo por diseño. Sus notas y su memoria siguen ahí.
- **La lista dice "Aún no hay Bots".** Primero crea un Bot.

## Relacionado

- [Costos]({{ '/es/costs/' | relative_url }})
- [Límite mensual]({{ '/es/monthly-limit/' | relative_url }})
- [Pensar de noche]({{ '/es/overnight-thinking/' | relative_url }}): usa su propia IA, que aparece en su pantalla.

[Todos los artículos de ayuda]({{ '/es/' | relative_url }})
