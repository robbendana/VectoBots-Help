---
title: "El navegador del Bot"
layout: default
permalink: /es/vectocrawl-browser/
lang: es
---

# El navegador del Bot

## Qué es y para qué sirve

La búsqueda y la lectura de páginas cubren casi todo lo que un Bot necesita consultar. Hay pocas cosas que no pueden hacer: páginas que piden que inicies sesión y páginas que solo muestran su contenido después de un clic, un desplazamiento o un formulario. Para eso, un Bot puede usar su propio navegador web, haciendo clic y escribiendo como lo haría una persona.

Por eso la tarjeta de Configuración lo llama **Último recurso: el navegador del Bot**. Sirve para inicios de sesión y páginas que necesitan clics, y cuesta mucho más.

## Antes de empezar

- **Aquí no hay nada que encender.** La tarjeta es una nota, con un enlace **Conoce más** a esta página. No tiene interruptor ni campo.
- **Cuesta mucho más.** Trabajar una página clic por clic requiere muchos más pasos que leer texto, y cada paso es trabajo de IA que pagas con tu plan o clave de siempre. Por eso es el último recurso.
- **Es el navegador del Bot, no el tuyo.** Cada Bot tiene su propia pantalla con un navegador. No es el navegador de tu laptop. Dejar que un Bot use tu propia laptop es otra función: mira [Deja que los Bots usen tu laptop]({{ '/es/laptop-control/' | relative_url }}).
- **Puedes verlo.** Abre los detalles del Bot (toca su nombre arriba del chat) y toca **Computadora** para ver su pantalla. Ver y tomar el control de la pantalla de un Bot es parte de Pro.

## Dónde lo ves

- **Laptop:** abre **Configuración**, elige **Cuentas de IA** a la izquierda y baja hasta el final del área de VectoCrawl. La última tarjeta es **Último recurso: el navegador del Bot**.
- **Celular:** toca **Más** en la barra de abajo, luego **Configuración**, después **Cuentas de IA**, y baja hasta la misma tarjeta. Con la flecha de regreso vuelves a la lista.

## Cómo decide el Bot

Tú no eliges el orden. A los Bots se les indica ir de lo más barato a lo más caro:

1. **Buscar.** Hacerle una pregunta a la web.
2. **Leer la página.** Abrir una dirección web y leer su texto. Si la ruta gratis es rechazada, puede probarse un proxy opcional. Mira [Proxy de IPRoyal]({{ '/es/vectocrawl-proxy/' | relative_url }}).
3. **El navegador.** Solo cuando los dos primeros no pueden mostrar la página.

Cuando una página no se puede leer, el Bot recibe un mensaje que dice que no pudo leerla, con el motivo, y una pista: si necesita inicio de sesión o clics, puede usar su navegador, que cuesta más. Una página con casi nada de texto, por ejemplo una que se dibuja por completo con scripts, recibe la misma pista.

## Para qué sirve

- Una página detrás de un inicio de sesión, como un área de miembros a la que ya perteneces.
- Una página que solo carga su contenido después de un clic.
- Trabajo que necesita varios pasos en un mismo sitio.

## Lo que los Bots no harán

- A los Bots se les indica que no paguen ni se registren en nada de tu parte.
- Si un sitio pide iniciar sesión, el Bot te pide el acceso en una tarjeta del chat. Escribes el usuario y la contraseña en esa tarjeta y tocas **Guardar acceso**. Luego la tarjeta dice "Guardado en la bóveda. El Bot puede iniciar sesión, pero nunca ve la contraseña." Nunca escribas una contraseña en un mensaje del chat.
- Todo lo riesgoso, como enviar, pagar o eliminar, sigue esperando tu toque en una tarjeta.

## Ejemplos reales

- **Una coach** le pide a un Bot revisar, en un sistema de reservas que ya usa, qué sesiones están libres la próxima semana. La página pide inicio de sesión, así que el Bot te pide el acceso en una tarjeta y luego entra con su navegador.
- **Un consultor** necesita cifras de un directorio de la industria que solo muestra su tabla después de un clic en "Mostrar todo". La búsqueda y la lectura de páginas regresan vacías, así que el Bot abre el navegador.
- **Una terapeuta** no debería usar esto con nada que muestre información de clientes. Mantén los expedientes fuera de cualquier página que un Bot abra por ti, y usa el navegador solo para páginas públicas o administrativas.

## Costos y límites

- La app no muestra un precio fijo. La respuesta honesta es "mucho más que una búsqueda o la lectura de una página".
- El costo es el trabajo de IA que el Bot gasta haciendo clics, y aparece en [Costos]({{ '/es/costs/' | relative_url }}) como cualquier otro trabajo de un Bot.
- Si fijaste un [Límite mensual]({{ '/es/monthly-limit/' | relative_url }}), también aplica.
- Si la información es texto público, pídele al Bot que busque o lea la página. Es mucho más barato.

## Problemas comunes y soluciones

- **Un Bot dice que no puede leer una página y menciona el navegador.** Es la pista de último recurso. Decide si la página vale el costo extra y luego pídele al Bot que continúe.
- **Un Bot usa el navegador para cosas fáciles.** Dile en el chat: "Primero busca, luego lee la página, y usa el navegador solo si eso falla."
- **El navegador necesita un acceso.** El Bot te lo pide en una tarjeta del chat. Llénalo en la tarjeta, no en un mensaje, para que el Bot pueda iniciar sesión sin ver nunca la contraseña.
- **No pasa nada.** Abre **Configuración**, **Computadora**, y revisa **Las pantallas de los Bots**. Ahí puedes reiniciar la pantalla de un Bot con **Reiniciar pantalla**.

## Funciones relacionadas

- [VectoCrawl]({{ '/es/vectocrawl/' | relative_url }})
- [Mejores resultados con claves]({{ '/es/vectocrawl-keys/' | relative_url }})
- [Proxy de IPRoyal]({{ '/es/vectocrawl-proxy/' | relative_url }})
- [Deja que los Bots usen tu laptop]({{ '/es/laptop-control/' | relative_url }})
- [Costos]({{ '/es/costs/' | relative_url }})

[Todos los artículos de ayuda]({{ '/es/' | relative_url }})
