---
title: "Uso del plan"
layout: default
permalink: /es/plan-usage/
lang: es
---

# Uso del plan

Tu plan de Claude y tu plan de ChatGPT limitan cuánto puedes usar en cada periodo. La app muestra cuánto de cada límite llevas usado, para que un límite no te sorprenda a media tarea. Lo ves en la página **Más** y en **Costos**, y también se les avisa a todos tus Bots, para que guarden el trabajo más pesado para cuando haya espacio.

## Los dos tipos de límite

- **La ventana de 5 horas.** Una cuota corta que se reinicia sola unas horas después de empezar a trabajar. En los planes de Claude empieza con tu primer mensaje y se reinicia cinco horas después.
- **La ventana semanal.** Una cuota mayor que se reinicia una vez por semana, a una hora fija de tu cuenta.

Qué límites tienes depende de tu plan, y las empresas los cambian. Esto es lo que dicen hoy:

- **Claude (Pro, Max).** Ventana de 5 horas y límite semanal. Algunas cuentas no tienen ventana de 5 horas. El centro de ayuda de Claude lo explica, y tu propia página en claude.ai, en Configuración y luego Uso, muestra las cifras exactas.
- **ChatGPT (Plus, Business).** Una cuota de 5 horas, y puede aplicar además un límite semanal.
- **ChatGPT Pro.** OpenAI dice que los planes Pro por ahora no tienen límite de 5 horas, y que pueden aplicar límites semanales. Si tu plan no envía ventana de 5 horas, la app dice "este plan no reporta límite de 5 horas" y muestra solo la semana. Nunca inventa una cifra.

Si dudas de tu plan, revisa la página de la empresa. La app muestra lo que tu plan reporta. No lo supone.

## Qué tan al día están los números

La app vuelve a revisar cada 5 minutos, más o menos.

- **ChatGPT.** Lee el uso que la propia herramienta de ChatGPT guarda en tu computadora cada vez que trabaja. No cuesta nada.
- **Claude.** Cada ejecución de un Bot lo actualiza. Si ninguna ejecución lo ha actualizado en 5 minutos, la app envía un mensaje muy corto al modelo más pequeño de Claude, solo para recibir el reporte de uso. Gasta una parte mínima de tu plan nunca se hace mientras un Bot de Claude está trabajando, y baja a una vez por hora cuando tu plan está inactivo desde que terminó su ventana de 5 horas. Se detiene de inmediato si Claude Code tiene una sesión con clave en lugar de tu plan. Puedes apagarlo en Configuración, en Uso.

Entre lecturas, la app te dice qué tan vieja es la lectura. Una ventana que ya se reinició se marca como **estimado** hasta la siguiente lectura, porque la app todavía no conoce la cifra nueva.

## Medido y estimado

- **Medido:** el porcentaje usado y la hora de reinicio, tal como los reportó el plan, con la hora de la lectura.
- **Estimado:** lo que se muestra después de un reinicio y cualquier hueco entre lecturas. Si también usas Claude o ChatGPT en otro dispositivo, ese uso aparece en la siguiente lectura, no al instante.

## Qué hacer con esto

- Arriba de 85%, el recuadro se pone ámbar. Haz primero el trabajo más importante.
- Si un Bot llega a un límite, su trabajo espera con calma hasta la hora de reinicio y una tarjeta en Hoy te avisa.
- Con un plan de $20, revisa la ventana de 5 horas antes de empezar una tarea larga. Una tarea larga puede gastar casi toda una ventana ella sola.

## Avisos de tu Bot

La app también vigila qué tan rápido se está llenando una ventana. Si a ese ritmo una ventana se agotaría antes de reiniciarse, tu Bot líder te avisa en palabras sencillas, por ejemplo: "A este ritmo, tu límite de 5 horas de Claude se agota alrededor de las 3:40 PM, antes de reiniciarse a las 5:10 PM. Haré primero el trabajo más importante." También te avisa una vez cuando una ventana pasa de 85% usado.

- Es un estimado. El uso llega a ráfagas, así que la hora puede moverse. Necesita que la ventana lleve al menos 20% usado y un poco de historial antes de decir algo.
- Recibes como máximo un aviso por ventana por cada uno de los dos motivos, nunca repetido.
- Sigue el ajuste **Por su cuenta** de tu Bot. Por debajo de **Avisar**, el Bot no inicia el mensaje. Aun así lo sabe y te lo dice cuando preguntas o cuando te responde. También aplican las horas de silencio y el límite diario.

## Problemas comunes

- **"Límite aún sin reportar".** El plan todavía no ha enviado cifras. Aparecen a los pocos minutos de la primera ejecución o revisión.
- **El plan de ChatGPT muestra solo la semana.** Tu plan no tiene ventana de 5 horas por ahora. Eso es lo que el plan reporta.
- **Una cifra se ve vieja.** La línea dice hace cuánto se leyó. Si sigue vieja, puede que la sesión haya expirado. Vuelve a iniciar sesión en Configuración.

## Relacionado

- [Costos]({{ '/es/costs/' | relative_url }})
- [Límite mensual]({{ '/es/monthly-limit/' | relative_url }})
- [Qué IA usa cada Bot]({{ '/es/which-ai/' | relative_url }})

[Todos los artículos de ayuda]({{ '/es/' | relative_url }})
