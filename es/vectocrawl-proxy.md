---
title: "Proxy de IPRoyal"
layout: default
permalink: /es/vectocrawl-proxy/
lang: es
---

# Proxy de IPRoyal

## Qué es y para qué sirve

Algunos sitios web se niegan a atender las rutas gratuitas de búsqueda y lectura de páginas, normalmente porque tratan ese tráfico como si fuera un robot. Un **proxy** es un intermediario que hace la solicitud en nombre del Bot, de modo que el sitio ve una conexión común. IPRoyal es una empresa que vende este servicio. La app lo recomienda y tiene un campo para su dirección, en la tarjeta **Mejores resultados (claves opcionales)**, en la fila **Recomendado: proxy de IPRoyal**.

La fila muestra el precio: unos $6 a $7 por GB, que le pagas a IPRoyal.

## Antes de empezar

- **Necesitas una cuenta en IPRoyal.** La creas tú. VectoBots no la vende y no ve tu pago.
- **Le pagas directo a IPRoyal,** unos $6 a $7 por GB, como muestra la app. Ese es el único precio que la app indica. Revisa el sitio de IPRoyal para ver sus planes actuales antes de comprar.
- **Al registrarte, IPRoyal te da una dirección de conexión.** Se ve así: `http://usuario:contraseña@servidor:puerto`, con tus propios datos en lugar de las palabras. Esa es la dirección que pegas en la app.
- **El servidor debe estar listo para guardar claves.** Si la tarjeta dice "Todavía no se pueden guardar claves en este servidor", el campo aparece atenuado. Es un paso de configuración del servidor: primero pide ayuda a tu Bot principal o a quien instaló VectoBots para ti.

La mayoría de las personas no necesita esto. Empieza con la búsqueda gratis y agrega un proxy solo si tus Bots avisan seguido que los sitios los rechazan.

## Cómo agregarlo

- **Laptop:** abre **Configuración**, elige **Cuentas de IA** a la izquierda, baja hasta **Mejores resultados (claves opcionales)** y busca **Recomendado: proxy de IPRoyal**.
- **Celular:** toca **Más** en la barra de abajo, luego **Configuración**, después **Cuentas de IA**, y baja hasta esa misma fila. La flecha de regreso te devuelve a la lista.

1. Haz clic en el campo. Su texto de ejemplo es `http://usuario:contraseña@servidor:puerto`.
2. Pega la dirección completa que te dio IPRoyal.
3. Toca **Guardar**. Verás "Guardada", y la fila mostrará **Agregada**.

La dirección contiene una contraseña, y la app la trata como una clave: se guarda de forma segura y **nunca se vuelve a mostrar**. Conserva tu propia copia.

Para quitarla, toca **Quitar**.

Las capturas están en inglés.

![Configuración, página de Cuentas de IA con la tarjeta VectoCrawl; la fila del proxy está más abajo, en la tarjeta de claves]({{ '/images/search-laptop.png' | relative_url }})

*La fila del proxy está en la tarjeta de claves, debajo de esta vista.*

## Cómo se usa

- **Solo después de que un sitio dice que no.** Un Bot siempre prueba primero la ruta gratis. Solo cuando una página la rechaza, la app lo intenta una vez más con tu proxy.
- **Cada uso cuenta para el límite diario.** El mismo **Límite diario para claves de pago** que cubre a Brave, Tavily y los demás cubre también el proxy. Empieza en 100. Al alcanzarlo, el proxy se detiene por el día y al Bot se le avisa que se alcanzó el límite diario.
- **Sirve para leer páginas.** No cambia la forma en que los Bots buscan.

El proxy no quita otras protecciones. Los Bots siguen sin poder dirigirse a direcciones de redes privadas.

## Ejemplos reales

- **Una coach** quiere que un Bot lea la página pública del programa de una conferencia, pero el sitio rechaza la ruta gratis. Con el proxy agregado, la página abre.
- **Un consultor** recibe una y otra vez "no se pudo leer esa página" en la página de precios de un competidor. El proxy la supera y llega el resumen del Bot.
- **Una terapeuta** que solo consulta temas generales en sitios grandes y abiertos no agrega proxy y no pierde nada.

## Costos y límites

- Precio: lo fija IPRoyal. La app indica unos $6 a $7 por GB, que se pagan a IPRoyal.
- Cada solicitud por proxy cuenta para el límite diario de claves de pago.
- El proxy solo se usa cuando la ruta gratis fue rechazada, así que el gasto suele ser pequeño.
- VectoBots no cobra nada.

## Problemas comunes y soluciones

- **"That doesn't look like a proxy address. It should look like http://user:password@host:port".** Este mensaje puede salir en inglés. Quiere decir que la dirección no tenía esa forma. Copia otra vez la dirección de conexión completa desde tu cuenta de IPRoyal, con el `http://` del inicio.
- **El campo está atenuado.** El almacén de claves todavía no está configurado en tu servidor. Pide ayuda a tu Bot principal o a quien instaló VectoBots para ti.
- **Una página sigue sin abrir.** No todos los sitios se pueden alcanzar. Para páginas que piden inicio de sesión o clics, mira [El navegador del Bot]({{ '/es/vectocrawl-browser/' | relative_url }}).
- **El Bot dice que se alcanzó el límite diario de claves de pago.** Sube el límite diario en la misma tarjeta, o espera. Cuenta las últimas 24 horas.
- **Pegaste la dirección equivocada.** Toca **Quitar** y agrégala de nuevo.

## Funciones relacionadas

- [VectoCrawl]({{ '/es/vectocrawl/' | relative_url }})
- [Mejores resultados con claves]({{ '/es/vectocrawl-keys/' | relative_url }})
- [El navegador del Bot]({{ '/es/vectocrawl-browser/' | relative_url }})
- [Costos]({{ '/es/costs/' | relative_url }})

[Todos los artículos de ayuda]({{ '/es/' | relative_url }})
