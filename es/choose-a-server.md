---
title: "Elige un servidor"
layout: default
permalink: /es/choose-a-server/
lang: es
---

# Elige un servidor

VectoBots corre en una computadora pequeña dentro de un centro de datos que **tú rentas**, llamada servidor (también "VPS"). Tus Bots, chats y archivos viven ahí, y sigue encendido aunque cierres tu laptop. Esta guía te ayuda a elegir uno y te muestra cada paso para pedir nuestra mejor opción.

*Precios revisados el **23 de noviembre de 2026**. Los precios de servidores están subiendo este año, así que confirma el precio en la página del proveedor antes de pagar. Esta lista se actualiza cada mes.*

## ¿Qué tamaño necesitas?

Lo que importa es **cuántos Bots trabajan al mismo tiempo**, no solo cuántas personas son. Un Bot que navega por internet es el que más memoria usa.

| Quién | Tamaño sugerido | Por qué |
|---|---|---|
| Solo tú | **4 CPU y 8 GB de memoria** | Espacio para varios Bots trabajando a la vez, más los extras. |
| Tú y 2 o 3 personas | **4 a 6 CPU y 8 a 12 GB** | Más personas significa más Bots trabajando al mismo tiempo. |
| Un equipo de hasta 6 | **6 CPU y 12 GB de memoria** | Nuestra elección para un equipo pequeño. |

Estos tamaños son **estimaciones** nuestras, basadas en lo que necesitan los Bots. Todavía no hemos probado un equipo completo de 6 trabajando a la vez, así que no lo prometemos. Si tu servidor se siente lento, en la mayoría de los proveedores puedes subir un tamaño con un clic.

También conviene saber:

- Disco: **100 GB o más** es cómodo.
- Elige **Linux**, **Ubuntu 24.04** o más nuevo.
- Elige un lugar cercano. Para la Ciudad de México funcionan bien las ubicaciones de EE. UU. de abajo.
- Cada persona sigue usando **su propio plan de Claude**. El servidor no cambia los límites del plan.

## Nuestra mejor opción: OVHcloud VPS-3 (unos $14.50 USD al mes, antes de impuestos)

- 6 CPU, 12 GB de memoria, 100 GB de disco rápido.
- **Mes a mes**: cancelas cuando quieras.
- Ubicaciones en EE. UU.: Virginia (este) y Oregón (oeste).
- Más barato si te comprometes: unos **$13.77** al mes por 6 meses, o unos **$12.32** por 12 meses.
- La mejor opción para un equipo de hasta 6.

## Otras buenas opciones

| Servidor | Tamaño | Precio | Condiciones | Dónde |
|---|---|---|---|---|
| **OVHcloud VPS-2** | 4 CPU, 8 GB, 75 GB | desde $8.50 (precio a 12 meses, antes de impuestos) | Mes a mes cuesta cerca de 18 % más | EE. UU. y el mundo |
| **netcup VPS 1000** | 4 CPU, 8 GB, 128 GB | unos €12 al mes (12 meses), unos €14 mes a mes | Mes a mes disponible | Europa, y Virginia (EE. UU.) con un pequeño cargo extra |
| **Contabo Cloud VPS 4** | 4 CPU, 8 GB, 100 GB | unos €5.50 mes a mes | Mes a mes disponible | EE. UU. y Europa |
| **Hostinger KVM 2** | 2 CPU, 8 GB, 100 GB | unos $9 al mes | Exige pagar **24 meses** por adelantado, y luego sube el precio | Varias, incluida EE. UU. |

Notas honestas:

- **Contabo** es la más barata, pero comparte más la máquina entre clientes y tiene una conexión más lenta (200 Mbit/s). Sirve para una persona, es arriesgada para un equipo.
- **Hostinger** es barata solo si pagas 2 años de golpe. No la sugerimos si no estás seguro.
- **Hetzner**, la favorita de antes, **subió sus precios dos veces en 2026** y tiene inventario limitado para clientes nuevos. Por ahora no la sugerimos.
- **DigitalOcean, Vultr y Akamai (Linode)** son excelentes y confiables, pero un servidor de 8 GB cuesta de **$40 a $48** al mes. Elígelas solo si quieres un nombre muy conocido.
- **México:** todavía no encontramos una opción con servidores en México que podamos confirmar y recomendar. Un servidor en EE. UU. funciona bien desde la Ciudad de México.

## ¿Cambiarán los precios en 2027?

Nadie puede prometerlo, pero esto es lo que vemos hoy:

- Los chips de memoria están mucho más caros este año, y eso empuja hacia arriba el precio de los servidores. Hetzner y netcup subieron precios en 2026.
- OVHcloud dice que limita sus aumentos en los servidores más nuevos, y que a los clientes actuales les permite conservar su precio por el compromiso que elijan al renovar.
- Hasta donde encontramos, ningún proveedor ha anunciado un aumento para 2027, pero estamos pendientes.
- **Las ofertas del Buen Fin / Black Friday y de fin de año están activas.** La oferta actual de OVHcloud es respaldo gratis hasta por 3 meses (hasta el 1 de diciembre). netcup suele tener ofertas en la semana de Black Friday y en diciembre.
- Si estás seguro de que conservarás tu servidor un año, pagar **12 meses** suele ser más barato y te protege de una subida de precio.

## Pide el OVHcloud VPS-3, paso a paso

Necesitas: un correo, una tarjeta de pago y unos 15 minutos. **No se cobra nada hasta que confirmes al final.** Revisamos la página de pedido el 23 de noviembre de 2026 para escribir estos pasos. Si tu pantalla se ve distinta, detente y pregunta.

1. **Abre la página de planes.** Ve a **us.ovhcloud.com/vps**. Verás cuatro tarjetas: VPS-1, VPS-2, VPS-3 y VPS-4.
2. **Elige VPS-3.** Su tarjeta dice **6 vCores, 12 GB RAM, 100 GB SSD NVMe**. Toca **Configure**.
3. **Periodo de compromiso (Commitment period).** Verás tres cajas: **No commitment**, **6 months (save 5%)** y **12 months (save 15%)**. **Ya viene seleccionada la de 12 meses.** Si quieres cancelar cuando quieras, toca **No commitment**. El precio "desde" de la tarjeta es el de 12 meses. Un compromiso se renueva solo, a menos que lo desactives en tu cuenta.
4. **Número de VPS.** Déjalo en **1**.
5. **Ubicación.** Abre la pestaña **North America** y elige **Virginia** (más cerca de la Ciudad de México) u **Oregón**.
6. **Imagen.** Abre **Distribution only**, toca **Ubuntu** y elige la versión **24.04** (una más nueva también sirve). Es gratis.
7. **Opciones.** Puedes dejar los extras apagados. Los respaldos diarios ya vienen incluidos sin costo.
8. **Revisa el resumen a la derecha.** Muestra el plan, el compromiso y la imagen. Los precios ahí son **antes de impuestos**. Asegúrate de que el total sea el que esperas.
9. **Continúa y crea tu cuenta.** Escribe tu nombre, correo y una contraseña segura, y confirma el correo que te manda OVHcloud.
10. **Agrega tu dirección y tarjeta, y paga.** Toca el botón final solo cuando el total sea correcto.
11. **Espera el correo.** En minutos OVHcloud te envía la **dirección** de tu servidor y una **contraseña** temporal. Guárdalas en privado y nunca las pegues en un chat.
12. **Conéctalo a VectoBots.** Abre la página de instalación de VectoBots. Te pide la dirección del servidor y te guía en lo demás.

## Buenos hábitos

- Activa la **verificación en dos pasos** en tu cuenta del proveedor.
- Deja encendido el **respaldo diario** que incluye OVHcloud.
- Anota la fecha en que se renueva tu servidor y pon un recordatorio una semana antes.
- Si algún día dejas de usarlo, cancela en el panel del proveedor, porque borrar VectoBots no cancela el servidor.

## Preguntas

**¿Puedo cambiar de tamaño después?** Sí. En OVHcloud puedes subir con un clic. Para bajar hay que pedir un servidor nuevo.

**¿El servidor viene incluido con VectoBots?** No. Lo rentas al proveedor y le pagas directamente.

**¿Ganan dinero si lo pido?** No. Son enlaces normales, no de pago.

[Todos los artículos de ayuda]({{ '/es/' | relative_url }})
