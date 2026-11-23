---
title: "Deja que los Bots usen tu laptop"
layout: default
permalink: /es/laptop-control/
lang: es
---

# Deja que los Bots usen tu laptop

El control de la laptop deja que un Bot que tú elijas vea tu pantalla, mueva el mouse y escriba, como lo harías tú, para hacer una tarea en un programa de tu propia computadora. Una pequeña app asistente en tu laptop lo hace posible.

Existe para trabajos que solo se pueden hacer en tu laptop, como llenar un formulario en un programa que no tiene otra forma de entrada. La mayoría de las personas nunca lo necesita. Trátalo como una herramienta de potencia: apagada hasta que decidas usarla.

## Antes de empezar

- Necesitas una laptop en la que puedas instalar una pequeña **app asistente**. Por ahora el asistente solo funciona en **Windows**.
- Activar el control de la laptop para un Bot es parte de **Pro**. (Durante la prueba todo Pro está activo.) Apagarlo siempre está permitido.
- Nada viene activado. El control de la laptop está **apagado para todos los Bots** hasta que lo actives.
- El asistente debe estar funcionando en la laptop. La app te dice si lo está: **Conectada** o **No conectada**.

![Configuración, Computadora, con la sección Laptop mostrando Tu computadora, No vinculada y un botón Crear código de vinculación]({{ '/images/laptop-laptop.png' | relative_url }})

*Configuración, Computadora, Laptop. Las capturas están en inglés.*

## Cómo configurarlo

La sección Laptop está en **Configuración, Computadora**. En la laptop, abre Configuración y haz clic en **Computadora** en la lista de la izquierda. En el teléfono, toca **Más** en la barra de abajo, luego **Configuración** y después **Computadora**. Usa la flecha de regreso para volver.

1. **Instala el asistente** en tu laptop.
2. En **Laptop**, toca **Crear código de vinculación**. Aparece un código, con la nota "Escribe este código en el asistente. Sirve por 10 minutos."
3. **Escribe el código en el asistente una sola vez.** El estado cambia de **No vinculada** a **Conectada**.
4. En **Qué Bots pueden usarla**, activa los Bots que pueden pedirlo. Un Bot activado dice: "Puede pedir usar tu laptop. Tú apruebas en una tarjeta." Uno apagado dice "Apagado."

## Qué pasa cuando un Bot quiere usarla

**La primera acción de cada sesión te pregunta en una tarjeta** en el chat. Eliges permitirla **para esta tarea** o **por 30 minutos**, o dices que no. Mientras un Bot trabaja, la página te avisa que ese Bot está controlando tu laptop.

El Bot empieza tomando una imagen de la pantalla, la mira y luego hace clic o escribe. Toma imágenes nuevas para comprobar qué pasó.

Para dejar de recibir preguntas por un Bot, agrega una regla en **Lo que pueden hacer los Bots**.

## Lo que está bloqueado

El asistente bloquea las ventanas que parecen de la Bóveda, de administradores de contraseñas, de páginas de bancos o de pantallas de inicio de sesión. Las reconoce por su nombre, así que una página de banco con un título poco común podría no detectarse. Cierra todo lo que no quieras que un Bot vea. Si un Bot necesita que inicies sesión en algún lugar, tiene que pedirte que lo hagas tú. A los Bots se les indica que traten el texto de la pantalla como información, nunca como una instrucción.

Cada acción aparece en **Actividad**, para que puedas revisar lo que pasó.

## Cada botón explicado

- **Crear código de vinculación / Vincular de nuevo.** Crea un código que dura 10 minutos. Después de vincular, el mismo botón dice **Vincular de nuevo**. Al vincular de nuevo, todos los Bots se apagan y se retiran sus aprobaciones, así que vuelve a activar los que quieras.
- **Desvincular.** Desconecta la laptop. La app pregunta: "¿Desvincular esta computadora? El asistente deja de funcionar hasta que la vincules de nuevo."
- **Detener todo** (en la fila **Detener**). Termina todas las sesiones ahora y bloquea el control de la laptop. También puedes hacer clic en la barra roja de la laptop o pulsar **Ctrl+Alt+End**. El estado pasa a **Detenido**.
- **Reanudar.** Aparece después de detener. El control de la laptop sigue apagado para todos los Bots hasta que lo presiones.
- **El interruptor de cada Bot.** Activa o desactiva el permiso de ese Bot. Al apagarlo también se retiran las aprobaciones de ese Bot.
- **La etiqueta de estado.** **No vinculada**, **Conectada**, **No conectada** o **Detenido**. "El asistente no está activo o no puede conectarse a este servidor" significa que el asistente está cerrado o sin conexión. Cuando está funcionando, la app muestra el tamaño de pantalla que ve.

## Ejemplo

Una terapeuta tiene un programa de agenda antiguo en su laptop que no se puede conectar con nada más. Instala el asistente, lo vincula y activa un solo Bot. Le pide que pase las citas del jueves al viernes. Aparece una tarjeta y ella la permite para esa tarea. Observa, ve que termina, y ve cada clic en Actividad.

Nunca deja que un Bot use su laptop con un expediente de un cliente o su banco en pantalla. El asistente intenta bloquear la Bóveda y las páginas de bancos, pero el buen criterio es suyo: cierra lo que no quieras que un Bot vea.

## Costos y límites

La app no cobra por esto por sí sola. El trabajo del Bot usa su IA como cualquier otra tarea. Mira [Costos]({{ '/es/costs/' | relative_url }}).

## Problemas comunes

- **No vinculada.** Crea un código y escríbelo en el asistente.
- **No conectada.** El asistente está cerrado, o la laptop está suspendida o sin internet. Abre el asistente otra vez.
- **Detenido.** Presionaste Detener. Toca **Reanudar**.
- **El código no funciona.** Dura 10 minutos. Crea uno nuevo.
- **Un Bot se detiene y dice que le dijeron que no.** Si dijiste que no o presionaste Detener, el Bot se detiene y te lo dice en una línea. No intenta otra manera.

## Relacionado

- [Conecta GitHub]({{ '/es/github/' | relative_url }})
- [Costos]({{ '/es/costs/' | relative_url }})

[Todos los artículos de ayuda]({{ '/es/' | relative_url }})
