---
title: "Elige un servidor"
layout: default
permalink: /es/choose-a-server/
lang: es
---

# Elige un servidor

VectoBots corre en una computadora pequeña dentro de un centro de datos que **tú rentas**, llamada servidor (también "VPS"). Tus Bots, chats y archivos viven ahí, y sigue encendido aunque cierres tu laptop. Esta guía te ayuda a elegir uno y te muestra cada paso para pedir nuestra mejor opción.

*Los precios de OVHcloud se revisaron en su página de pedido el **23 de noviembre de 2026**. Los demás precios vienen de sitios que comparan precios, el mismo día. Los precios de servidores subieron en 2026, así que confirma el precio en la página del proveedor antes de pagar.*

## ¿Qué tamaño necesitas?

Lo que importa es **cuántos Bots trabajan al mismo tiempo**, no solo cuántas personas son. Un Bot que navega por internet es el que más memoria usa.

| Quién | Tamaño sugerido | Por qué |
|---|---|---|
| Solo tú | **4 CPU y 8 GB de memoria** | Espacio para varios Bots trabajando a la vez, más la transcripción de voz. |
| Tú y 2 o 3 personas | **4 a 6 CPU y 8 a 12 GB** | Con más personas, hay más Bots trabajando al mismo tiempo. |
| Un equipo de hasta 6 | **6 CPU y 12 GB de memoria** | Nuestra elección para un equipo pequeño. |

Estos tamaños son **estimaciones** nuestras, basadas en lo que necesitan los Bots. Todavía no hemos probado un equipo completo de 6 trabajando a la vez, así que no lo prometemos. Si tu servidor se siente lento, puedes pasar a un plan más grande desde tu cuenta de OVHcloud, a un precio más alto.

También conviene saber:

- Disco: **100 GB o más** es cómodo.
- Elige **Ubuntu 24.04** (una versión de Linux).
- Elige un lugar cercano. Para la Ciudad de México, las ubicaciones de EE. UU. que aparecen abajo deberían funcionar bien.
- Cada persona sigue usando **su propio plan de Claude**. El servidor no cambia los límites del plan.
- Compartir con un equipo tiene algunos límites hoy. Lee primero [Integrantes del equipo]({{ '/es/team/' | relative_url }}).

## Nuestra mejor opción: OVHcloud VPS-3 (unos US$14.50 al mes, antes de impuestos)

- 6 CPU, 12 GB de memoria, 100 GB de disco rápido.
- **Mes a mes**: cancelas cuando quieras.
- Ubicaciones en EE. UU.: Virginia (este) y Oregón (oeste).
- Más barato si te comprometes: unos **US$13.77** al mes por 6 meses, o unos **US$12.32** por 12 meses.
- El tamaño que sugerimos para un equipo de hasta 6 (es una estimación, ver arriba).

## Otras buenas opciones

| Servidor | Tamaño | Precio | Condiciones | Dónde |
|---|---|---|---|---|
| **OVHcloud VPS-2** | 4 CPU, 8 GB, 75 GB | desde US$8.50 al mes (precio a 12 meses, antes de impuestos) | Unos US$10 al mes sin compromiso | EE. UU. y el mundo |
| **netcup VPS 1000** | 4 CPU, 8 GB, 128 GB | unos €12 al mes (12 meses), unos €14 mes a mes | Disponible mes a mes | Europa, o una ubicación en EE. UU. por unos €1.50 más al mes |
| **Contabo Cloud VPS 4** | 4 CPU, 8 GB, 100 GB | unos €5.50 mes a mes | Mes a mes disponible | EE. UU. y Europa |
| **Hostinger KVM 2** | 2 CPU, 8 GB | unos US$9 al mes, solo si pagas 24 meses por adelantado (unos US$216) | Se renueva en unos US$15 al mes | Revisa la página del proveedor |

Notas honestas:

- **Contabo** es la más barata de esta lista. Su conexión anunciada es de 200 Mbit/s, menos de lo que nos gustaría para un equipo con mucho uso. Sirve para una persona; para un equipo preferimos OVHcloud.
- **Hostinger** es barata solo si pagas 2 años de golpe. Además tiene solo 2 CPU, menos de lo que sugerimos. No la sugerimos si no estás seguro.
- **Hetzner**, por mucho tiempo una opción popular, **subió sus precios dos veces en 2026** y desde junio de 2026 limita los pedidos de muchos clientes nuevos. Por ahora no la sugerimos.
- **DigitalOcean, Vultr y Akamai (Linode)** son excelentes y confiables, pero un servidor de 8 GB cuesta de **US$40 a US$48** al mes. Elígelas solo si quieres un nombre muy conocido.
- **México:** todavía no encontramos una opción con servidores en México que podamos confirmar y recomendar. Un servidor en EE. UU. funciona bien desde la Ciudad de México.

## ¿Cambiarán los precios en 2027?

Nadie puede prometerlo, pero esto es lo que vemos hoy:

- Los chips de memoria costaron mucho más en 2026 y eso empuja hacia arriba el precio de los servidores. Hetzner y netcup subieron precios en 2026, y los planes VPS más nuevos de OVHcloud (junio de 2026) cuestan más que los anteriores del mismo tamaño.
- OVHcloud dice que limita los aumentos en sus servicios más nuevos, y ha permitido a clientes actuales conservar su precio por un plazo si renuevan antes de una fecha límite. Revisa las condiciones vigentes en el sitio de OVHcloud.
- Al 23 de noviembre de 2026, no encontramos ningún proveedor que haya anunciado un aumento para 2027, pero estamos pendientes.
- **Hasta el 1 de diciembre de 2026**, OVHcloud ofrece hasta 3 meses gratis de su respaldo mejorado (Premium). No es un descuento en el servidor y puede costar dinero después del periodo gratis, así que revísalo antes de agregarlo. netcup podría tener ofertas en diciembre; no hemos confirmado ninguna.
- Si estás seguro de que conservarás tu servidor un año, un compromiso de **12 meses** suele ser más barato y mantiene tu precio fijo durante esos 12 meses.

## Pide el OVHcloud VPS-3, paso a paso

Necesitas: un correo, una tarjeta de crédito o débito y unos 15 minutos. No deberían cobrarte hasta que confirmes el pedido al final. Seguimos la página de pedido de OVHcloud hasta el resumen (paso 8) el 23 de noviembre de 2026; las pantallas de registro y pago pueden ser distintas. Si algo se ve diferente, detente y pregúntale a tu Bot. OVHcloud también puede enviarte a otro sitio de OVHcloud según tu país; revisa que el precio del VPS-3 ahí coincida con esta guía.

1. **Abre la página de planes.** Ve a **us.ovhcloud.com/vps**. Verás una fila de tarjetas de planes, entre ellas VPS-3.
2. **Elige VPS-3.** Su tarjeta dice **6 vCores, 12 GB RAM, 100 GB SSD NVMe**. Haz clic (o toca) **Configure**.
3. **Periodo de compromiso (Commitment period).** Verás tres opciones: **No commitment**, **6 months (save 5%)** y **12 months (save 15%)**. **Ya viene seleccionada la de 12 meses.** Si quieres poder cancelar en cualquier momento, haz clic en **No commitment**. El precio "desde" de la tarjeta es el de 12 meses. Con 6 o 12 meses aceptas pagar el periodo completo aunque lo dejes antes. Todos los planes se renuevan y se cobran de nuevo hasta que canceles.
4. **Número de VPS (Number of VPS).** Déjalo en **1**.
5. **Ubicación (Location).** Abre la pestaña **North America** y elige **Virginia** (más cerca de la Ciudad de México) u **Oregón**.
6. **Imagen (Image).** Abre **Distribution only**, haz clic en **Ubuntu** y elige la versión **24.04**. Es gratis.
7. **Opciones (Options).** Puedes dejar los extras sin seleccionar. El resumen muestra un respaldo automático estándar en $0.00.
8. **Revisa el resumen a la derecha.** Muestra el plan, el compromiso y la imagen. Los precios ahí son **antes de impuestos**. Asegúrate de que el total sea el que esperas.
9. **Continúa y crea tu cuenta.** Escribe tu nombre, correo y una contraseña segura, y confirma el correo que te manda OVHcloud.
10. **Agrega tu dirección y tarjeta, y paga.** Haz clic en el botón final solo cuando el total sea correcto.
11. **Espera el correo.** Normalmente en minutos. OVHcloud puede pedirte primero que confirmes tu identidad, lo cual puede tardar más. Te envía la **dirección** de tu servidor y una **contraseña** temporal. Guárdalas en privado. Escribe la contraseña solo donde te la pida la página de instalación de VectoBots; nunca la mandes por correo, chat o mensaje, ni siquiera a nosotros.
12. **Conéctalo a VectoBots.** Abre la página de instalación de VectoBots. Te pide la dirección del servidor y te guía en lo demás.

## Buenos hábitos

- Activa la **verificación en dos pasos** en tu cuenta del proveedor.
- Si tu proveedor incluye respaldos, déjalos encendidos.
- Anota la fecha en que se renueva tu servidor y pon un recordatorio una semana antes.
- Si algún día dejas de usarlo, cancela en el panel del proveedor, porque borrar VectoBots no cancela el servidor.

## Preguntas

**¿Puedo cambiar de tamaño después?** Sí. En OVHcloud puedes pasar a un plan más grande desde tu cuenta; tu precio sube. Para pasar a uno más pequeño hay que pedir un servidor nuevo.

**¿El servidor viene incluido con VectoBots?** No. Lo rentas al proveedor y le pagas directamente.

**¿Ganan dinero si lo pido?** No. Ningún proveedor de esta página nos paga y no usamos enlaces de referidos. Si eso cambia, lo diremos aquí.

[Todos los artículos de ayuda]({{ '/es/' | relative_url }})
