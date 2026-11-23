---
title: "Reglas integradas"
layout: default
permalink: /es/built-in-rules/
lang: es
---

# Reglas integradas

## Qué son y para qué sirven

Dos conjuntos de reglas definen cómo se comportan tus Bots, y la app los muestra juntos en una sola página, **Lo que pueden hacer los Bots**:

1. Las **reglas integradas** definen cómo **te escribe** cada Bot: primero la respuesta, con palabras cortas y claras, una pregunta a la vez.
2. Las **reglas de aprobación** definen qué **pueden hacer los Bots sin preguntarte**: enviar, publicar, pagar, borrar y más.

Juntas hacen que tus Bots hablen como un asistente tranquilo y que nunca den un paso importante a tus espaldas. Este artículo explica ambos conjuntos.

## Antes de empezar

- Los dos conjuntos están activos para todos y no cuestan nada.
- Solo tú, como dueño o dueña, puedes ver estas páginas y cambiar las reglas de aprobación. Los Bots siguen ambos conjuntos, pero no pueden cambiarlos.
- Las reglas integradas son solo de lectura. No se pueden editar. Para cambiar cómo escriben los Bots, agrega tus propias [reglas generales]({{ '/es/house-rules/' | relative_url }}). **Tus propias reglas van primero**: si dicen algo distinto, mandan las tuyas.

## Parte 1: Las reglas integradas de escritura

**Cómo leerlas**

*Laptop:* haz clic en el engrane de abajo a la izquierda para abrir **Configuración**, haz clic en **Lo que pueden hacer los Bots**, baja hasta el final y haz clic en **Ver las reglas integradas**. Haz clic en **Ocultar las reglas integradas** para cerrarlas.

*Celular:* toca **Más** en la barra de abajo, luego **Configuración** y después **Lo que pueden hacer los Bots**, baja y toca **Ver las reglas integradas**. Usa la flecha de regreso para volver a la lista.

**Qué dicen, en palabras simples**

- Empezar por el resultado o la respuesta. Después, solo lo que necesitas para decidir o hacer lo siguiente.
- Ser breve: unas cuantas frases o hasta cinco viñetas sencillas. Negritas solo para lo único que no debes perderte.
- Responder en el idioma en que tú escribes, con frases sencillas.
- Usar palabras simples. Sin rutas de archivos, nombres de carpetas, comandos, códigos ni nombres de herramientas en las respuestas normales.
- No listar cada paso. Decir lo que se hizo en una línea. El detalle está en Actividad.
- Cuando un archivo esté listo, entregarlo por la app para que lo abras, en lugar de decir dónde está guardado.
- Dar nombre a cada enlace web en vez de pegar una dirección suelta.
- Si algo falla, decir qué pasó y qué se necesita de ti, sin códigos de error ni registros.
- Hacer una pregunta a la vez y decir cuál opción recomienda.
- Solo cuando trabajas con código, o pides el detalle técnico, un Bot puede usar palabras de desarrollador.

## Parte 2: Las reglas de aprobación

Una regla de aprobación responde una pregunta: **¿puede este Bot hacer esto, aquí, sin preguntarme?** La app arma cada regla como una frase que puedes leer, por ejemplo, en inglés: "Let every Bot post in public on sites matching *.example.com, but always ask first." Por ahora, en español partes de esta frase pueden salir en inglés.

La página tiene estas secciones, de arriba abajo:

- **Les enseñaste.** Reglas que nacieron cuando respondiste una tarjeta con "Sí, dejar de preguntar". Cada una muestra cuántas veces se usó. **Deshacer** la quita y el Bot vuelve a preguntar. Si una regla enseñada está apagada, **Activar** la regresa.
- **Siempre te pregunta primero.** Un cuadro fijo con cosas que ninguna regla puede desactivar. Míralo más abajo.
- **Tus propias reglas.** Reglas que escribes tú con **Nueva regla**.
- **Aprobado por un tiempo.** Aprobaciones temporales que diste en una tarjeta ("Aprobar todo lo parecido para esta tarea" o "por 30 min"), con el tiempo que queda. Terminan solas.

## Cómo crear una regla nueva

1. En la página **Lo que pueden hacer los Bots**, haz clic o toca **Nueva regla**.
2. Llena el formulario:
   - **Quién.** **Todos los Bots**, o un Bot en particular.
   - **Qué.** El tipo de acción, por ejemplo enviar mensajes, publicar en público, borrar cosas, pagar cosas, publicar versiones de prueba o controlar tu laptop. Por ahora estas opciones aparecen en inglés.
   - **Dónde (opcional).** Un patrón para el destino. Usa \* para cualquier texto, por ejemplo \*@ejemplo.com. Déjalo vacío para cubrir todo de este tipo.
   - **Decisión.** **Permitir sin preguntar**, **Preguntar siempre** o **Nunca permitir**.
   - **Nota (opcional).** Por qué hiciste la regla. Hasta 200 caracteres.
3. Lee la línea **Esta regla dice**. Se actualiza mientras cambias el formulario. Si no es lo que quieres decir, corrígela.
4. Haz clic en **Guardar regla**. Verás "Regla guardada."

En cada regla puedes usar el interruptor para apagarla y encenderla, **Editar** para cambiarla o **Eliminar** (la app pregunta "¿Eliminar esta regla?" y eliges **Eliminar** o **Conservar**). Una regla apagada sigue en la lista pero no hace nada. Cada regla también muestra cuántas veces se ha usado.

Cuando dos reglas se traslapan, gana la más específica. Puedes tener hasta 200 reglas. El destino puede tener hasta 120 caracteres.

## Lo que ninguna regla puede cambiar

El cuadro **Siempre te pregunta primero** las enumera. Una regla solo puede hacer que pregunten o que se bloqueen, nunca permitirlas:

- Enviar correos y mensajes.
- Publicar en público.
- Pagar cualquier cosa.
- Publicar en vivo (despliegues a producción y publicación de paquetes).
- Guardar o cambiar una habilidad.
- Subir cambios a la rama principal (main) está bloqueado. Una regla puede convertirlo en una pregunta.
- Todo lo que rechazaste antes en la misma tarea.
- Todo lo que toque contraseñas guardadas o los ajustes de seguridad de los propios Bots, que siempre está bloqueado.

Si intentas permitir una de estas, la app avisa que una regla no puede dejar que un Bot lo haga sin preguntar. Aun así puedes crear una regla que pregunte o bloquee. En el formulario, **Permitir sin preguntar** aparece en gris como "(no es posible aquí)" para estos tipos.

## Ejemplos para un consultorio individual

- **Una coach con una app de calendario:** una regla que, para las herramientas conectadas que cambian cosas en el calendario, diga "preguntar siempre". Ves cada cambio antes de que ocurra.
- **Bloquear una acción por completo:** una regla **Nunca permitir** para borrar cosas, con **Todos los Bots**. Útil mientras te acostumbras a los Bots.
- **Un terapeuta:** crea una regla que bloquee publicar en público para todos los Bots. Es una segunda capa que protege la privacidad de tus clientes. No sustituye tu cuidado con la información confidencial.
- **Menos interrupciones:** cuando una tarjeta insiste en preguntar algo inofensivo que sí quieres permitir, responde **Sí, dejar de preguntar**. Aparece en **Les enseñaste** y puedes deshacerla cuando quieras.

## Problemas frecuentes

- **"Las reglas no se cargaron".** Pulsa **Intentar de nuevo**.
- **"Cargando reglas..." no se quita.** Revisa tu conexión y vuelve a abrir la página.
- **"Elige a qué tipo de acción se refiere esta regla."** Elige una opción en **Qué**.
- **"Es demasiado largo..."** El destino admite hasta 120 caracteres y la nota hasta 200. Acórtalos.
- **Un Bot sigue preguntando aunque lo permití.** Quizá tu regla no coincide con el lugar exacto. Haz **Dónde** más amplio o déjalo vacío. O la acción está en la lista que siempre pregunta.
- **Quiero quitar una regla enseñada.** Haz clic en **Deshacer**. "Se deshizo. Volverá a preguntar."

## Funciones relacionadas

- [Reglas generales]({{ '/es/house-rules/' | relative_url }}): tus propias instrucciones para todos los Bots.
- [Control de la laptop]({{ '/es/laptop-control/' | relative_url }}): las acciones de los Bots en tu computadora.
- [Integrantes del equipo]({{ '/es/team/' | relative_url }}): las aprobaciones siempre te llegan a ti.
- [Límite mensual]({{ '/es/monthly-limit/' | relative_url }}): un tope de gasto.

*Las capturas están en inglés.*

![La página Lo que pueden hacer los Bots: reglas que les enseñaste, la lista que siempre te pregunta, tus reglas y el enlace a las reglas integradas.]({{ '/images/rules-laptop.png' | relative_url }})
*La página Lo que pueden hacer los Bots.*

[Todos los artículos de ayuda]({{ '/es/' | relative_url }})
