---
title: "Plantillas de Bots"
layout: default
permalink: /es/bot-templates/
lang: es
---

# Plantillas de Bots

## Qué es y para qué sirve

Una **plantilla de Bot** es un archivo pequeño que describe a un Bot: su nombre, su aspecto y sus instrucciones. Puedes **exportar** un Bot como plantilla para guardar una copia o compartirla, e **importar** una plantilla para agregar un Bot que hizo alguien más, o uno que guardaste antes.

Piensa en ella como una receta, no como el platillo terminado. Le dice a VectoBots cómo preparar el Bot. No lleva lo que ese Bot ha aprendido ni nada de tu información privada.

Las capturas están en inglés.

![Configuración en una laptop, página You: el cuadro Bot templates con Learn more y el botón Import a Bot template]({{ '/images/export-laptop.png' | relative_url }})

*El cuadro "Plantillas de Bots" (en la captura, "Bot templates") en la página Tú. Está debajo de "Tus datos".*

## Antes de empezar

- Es gratis y está disponible para ti, como dueño o dueña. Los Bots no pueden exportar ni importar plantillas.
- Para **importar** necesitas un archivo de plantilla. Termina en `.json`, y uno exportado se llama algo como `Nombre.vectobots-bot.json`.
- El Bot nuevo usa la **IA habitual** de este servidor, no la del archivo. Puedes cambiarla después en los ajustes del Bot nuevo.

## Qué lleva una plantilla

Una plantilla solo contiene texto descriptivo y unos cuantos ajustes de aspecto:

- **Nombre**, además de su color, su forma y su ajuste de carácter.
- **Título**, por ejemplo "Atención a clientes".
- **De qué se encarga**, **qué hace** y **qué no hace**.
- **A quién reporta** y sus **reglas** (las líneas que nunca cruza).
- **Sus instrucciones**, la descripción escrita de quién es el Bot.

## Qué nunca lleva una plantilla

- **Nada de memoria.** No carga lo que el Bot recuerda.
- **Ni claves ni inicios de sesión.**
- **Ni chats.**
- **Ni código.** Es solo texto y ajustes.

Por eso una plantilla es segura para guardar y compartir en lo que respecta a tus propios datos. Aun así, cuando viene de otra persona, **VectoBots no la revisa**. Mira "Cuidado con archivos de otras personas" más abajo.

## Cómo exportar un Bot como plantilla

**En una laptop**

1. Abre el chat del Bot.
2. Haz clic en el nombre del Bot, arriba del chat. Se abren sus detalles.
3. Haz clic en el botón **…** de arriba de los detalles. Su etiqueta es "Ocultar o eliminar".
4. Elige **Exportar como archivo de plantilla**.
5. Tu navegador guarda un archivo con el nombre del Bot, que termina en `.vectobots-bot.json`.

**En el celular**

1. Abre el chat del Bot desde **Bots**.
2. Toca el nombre del Bot, arriba, y luego el botón **…**.
3. Toca **Exportar como archivo de plantilla**.
4. Tu celular guarda el archivo en sus descargas.

Para exportar todo lo demás (memoria, chats, archivos) usa [Exporta tus datos]({{ '/es/export-your-data/' | relative_url }}), que también incluye tus Bots como plantillas.

## Cómo importar una plantilla

1. Abre **Configuración** y luego **Tú** (en laptop, el engrane de abajo a la izquierda; en el celular, **Más** en la barra de abajo y luego **Configuración**).
2. Baja hasta **Plantillas de Bots**.
3. Haz clic o toca **Importar una plantilla de Bot** y elige el archivo `.json`.
4. Se abre una ventana, **¿Agregar este Bot?**, con todo lo que contiene el archivo:
   **Nombre**, **Título**, **De qué se encarga**, **A quién reporta**, **Qué hace**, **Qué no hace**, **Reglas** y **Sus instrucciones**.
5. Léela. Si quieres ver el archivo tal cual, abre **Mostrar el archivo**.
6. Haz clic en **Agregar Bot** para crearlo, o en **Cancelar** para detenerte. No se crea nada hasta que pulses **Agregar Bot**.
7. Un aviso dice "Se agregó {Nombre}." El Bot nuevo abre con una nota: fue hecho desde un archivo de plantilla, VectoBots no lo revisó y te preguntará antes de hacer algo que necesite tu visto bueno.

Si ya existe un Bot con el mismo nombre, el nuevo recibe un número, por ejemplo "Anchor 2".

## Cuidado con archivos de otras personas

La ventana lo dice claro: **"No revisada por VectoBots. Léela antes."** VectoBots no revisa una plantilla por ti. Una plantilla escrita por un desconocido podría traer instrucciones que no quieres que siga tu Bot, que van contra ti o que tú no escribirías.

Por eso, siempre:

1. Lee cada campo de la ventana, sobre todo **Sus instrucciones** y **Reglas**.
2. Agrega solo plantillas de personas en las que confíes.
3. Deja activas tus reglas de aprobación. El Bot nuevo igual tiene que preguntarte antes de enviar, pagar, publicar o borrar.

## Ejemplos para un consultorio individual

- **Un respaldo de tu ayudante favorito.** Exporta tu Bot de "Preparación de sesiones" cuando ya afinaste sus instrucciones. Si algún día tienes que reconstruirlo, impórtalo.
- **Un Bot para un servicio nuevo.** Haz un Bot para preguntas de primer contacto, expórtalo, impórtalo y cámbiale el nombre para arrancar un segundo Bot con reglas parecidas.
- **Compartir con un colega.** Exporta un Bot "Planeador semanal" y envía el archivo a un colega de confianza. Recibe tu configuración, no tus clientes, notas ni claves.
- **Confidencialidad.** Una plantilla nunca debe contener nombres ni datos de clientes. Antes de exportar o compartir, lee el campo de instrucciones y quita lo personal, como el nombre de un cliente escrito ahí por error.

## Costos y límites

- Las plantillas son gratis.
- Un archivo de plantilla puede pesar hasta unos 100 KB. Las instrucciones pueden tener hasta 20,000 caracteres y cada uno de los otros campos unos 600. El texto más largo se corta.

## Problemas frecuentes

- **"Eso no es una plantilla de Bot."** El archivo no es una plantilla de Bot de VectoBots. Elige un archivo exportado desde VectoBots.
- **"That file is too big for a Bot template."** El archivo pasa el límite de tamaño.
- **"This template is from a newer version of VectoBots."** Actualiza tu VectoBots y vuelve a intentar.
- **"The template has no name."** Abre el archivo en un editor de texto y agrégale un nombre.
- **El Bot nuevo se comporta como con la IA habitual.** Es lo esperado. Una plantilla nunca lleva su IA. Cámbiala en los ajustes del Bot.
- **No encuentro Exportar como archivo de plantilla.** Abre el menú del Bot, no la página general de Configuración.

## Funciones relacionadas

- [Exporta tus datos]({{ '/es/export-your-data/' | relative_url }}): todo en un archivo.
- [Reglas generales]({{ '/es/house-rules/' | relative_url }}): reglas para todos los Bots a la vez.
- [Qué IA usa cada Bot]({{ '/es/which-ai/' | relative_url }}): elige la IA de cada Bot.

[Todos los artículos de ayuda]({{ '/es/' | relative_url }})
