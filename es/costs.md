---
title: "Costos"
layout: default
permalink: /es/costs/
lang: es
---

# Costos

Costos es la página que muestra cuánto cuesta el trabajo de tus Bots. Te responde rápido: "¿cuánto he gastado hoy, esta semana y este mes?", y te enseña en qué se fue el dinero.

Existe porque el trabajo de IA se puede pagar de dos formas muy distintas y es fácil confundirlas. Esta página las mantiene separadas.

## Las dos formas de pagar el trabajo

- **Pago por uso, con una clave de API.** Cada trabajo tiene un precio. Este es el dinero que la página suma en dólares.
- **Con un plan.** Pagas una tarifa fija a una empresa, por ejemplo una suscripción a Claude o a ChatGPT. El trabajo con un plan **no se cobra por mensaje**. Un plan tiene una ventana de 5 horas y un límite semanal. Cada uno se reinicia solo a la hora que muestra la página.

Se muestra dinero del trabajo pagado con una clave de API. El trabajo con un plan se muestra como estimación, marcada con **≈**, y nunca se suma a tus dólares. La página lo dice claro: "≈ indica un monto estimado. Los planes tienen tarifa fija."

![La página de Costos con las cifras de Hoy, Esta semana y Este mes, la tarjeta Límites y la sección Planes]({{ '/images/limit-laptop.png' | relative_url }})

*La página de Costos en una laptop. Las capturas están en inglés.*

## Cómo abrirla

1. Abre **Más** y luego **Costos**.
2. En el teléfono, la línea de gasto arriba de la página Más también abre Costos.
3. En la laptop, cuando pasas del 80% de tu límite mensual aparece una línea de gasto en la columna izquierda. Haz clic en ella para abrir Costos.

## Qué ves, parte por parte

**Hoy, Esta semana, Este mes.** Tres cifras grandes. Cada una es el dinero pagado con claves de API. El trabajo con plan nunca se suma a estas cifras.

**La barra mensual.** Debajo de **Este mes** una barra muestra cuánto de tu límite mensual llevas usado, con "del límite de $X". La barra es ámbar desde el 80% y roja desde el 95%. **Cambiar límite** abre la tarjeta Límites. Mira [Límite mensual]({{ '/es/monthly-limit/' | relative_url }}). Si no hay límite, dice "Sin límite mensual".

**Tu plan.** Cuando un Bot funciona con un plan de Claude o de ChatGPT, un recuadro muestra la parte semanal usada, por ejemplo "Plan de Claude: 40% de esta semana usado, se reinicia lun 9:00". Una segunda línea puede mostrar la ventana de 5 horas. Cuando un plan se agota, el recuadro dice **Agotado** en lugar de un porcentaje. Los medidores están tan frescos como la última vez que el plan reportó; si la lectura es vieja, el recuadro dice hace cuánto se leyó. Si un plan no ha reportado nada, ves "sin medidor reportado". La app nunca inventa una cifra.

**Barras sólidas y rayadas.** Una barra sólida es dinero que pagas (claves de API). Una barra rayada es trabajo dentro de un plan.

**Planes.** Una lista corta con una línea por cada sesión de plan: cuántas tareas y cuántos tokens (un token es un pedacito de texto que la IA lee o escribe) usó este mes, y qué Bots lo usan. La etiqueta de la derecha dice "uso, no dólares".

**Por Bot.** Cuánto costó cada Bot hoy. Un Bot con tope mensual propio muestra una etiqueta de "tope", o "En pausa · tope" si lo alcanzó. **Ver gasto diario por Bot** abre esa misma vista.

**Últimos 30 días.** Una gráfica pequeña del gasto pagado por día, con el día de mayor gasto. El trabajo con planes aparece como una línea tenue punteada encima.

**Llamadas de voz.** Si hiciste llamadas de voz, aparecen con los minutos y el costo.

## Ejemplos

Una terapeuta usa sus Bots con una suscripción a Claude. Su página de Costos muestra $0.00 hoy, esta semana y este mes, y un recuadro de plan al 35% de la semana. Es normal: no se pagó dinero por uso. Solo necesita vigilar el porcentaje para no quedarse sin plan a mitad de semana.

Un consultor tiene un Bot con clave de API para informes largos. Costos muestra $4.20 este mes de un límite de $50. La lista Por Bot lo muestra como el único con gasto.

## Problemas comunes

- **"No cargó el gasto".** Toca **Intentar de nuevo**.
- **Todo aparece en $0.00.** O aún no se ha ejecutado nada, o tus Bots usan un plan. El trabajo con plan se muestra como uso y estimaciones ≈, no como dólares.
- **"Sin dato del límite del plan".** El plan todavía no le ha dado sus números a la app. Aparecen después de que un Bot trabaja.
- **La cifra de un plan parece vieja.** Solo está tan fresca como la última ejecución. Haz trabajar a un Bot y vuelve a mirar.

## Relacionado

- [Límite mensual]({{ '/es/monthly-limit/' | relative_url }})
- [Qué IA usa cada Bot]({{ '/es/which-ai/' | relative_url }})
- [Pensar de noche]({{ '/es/overnight-thinking/' | relative_url }}): tiene su propio límite diario de gasto.

Para ver cuánto llevas usado de cada plan, lee [Uso del plan]({{ '/es/plan-usage/' | relative_url }}).

[Todos los artículos de ayuda]({{ '/es/' | relative_url }})
