---
title: "Conecta GitHub"
layout: default
permalink: /es/github/
lang: es
---

# Conecta GitHub

GitHub es un sitio web donde se guardan los archivos de un proyecto, casi siempre software o un sitio web, con el historial completo de cada cambio. Al conectarlo, tus Bots pueden trabajar en esos proyectos por ti, en el área VectoCode de la app.

Si no usas GitHub, puedes saltarte esta función. Es solo para quienes ya tienen proyectos ahí, o para quienes un desarrollador o un Bot les construye un sitio web o una app.

## Antes de empezar

- Necesitas una **cuenta de GitHub** y al menos un proyecto (GitHub lo llama repositorio) en ella.
- **No** le das a VectoBots tu contraseña de GitHub. Se abre una página de GitHub y tu contraseña se queda con GitHub.
- Tú eliges qué proyectos pueden ver los Bots.
- Conectar no cuesta. El trabajo de IA que tus Bots hagan después se paga como cualquier otro. Mira [Costos]({{ '/es/costs/' | relative_url }}).

## Tres cosas que debes saber

- Los Bots solo ven lo que permites. Puedes cambiarlo en GitHub cuando quieras.
- Al iniciar un proyecto, tus Bots obtienen **su propia copia de trabajo**. No editan tu original directamente.
- Tu trabajo se guarda en GitHub **solo cuando tú lo indicas**.

## Cómo conectar

La sección de GitHub está en **Apps**. En la laptop, haz clic en el ícono de Apps al fondo de la columna izquierda. En el teléfono, toca **Más** en la barra de abajo y luego **Apps**.

1. Abre **Apps** y busca **GitHub**. Verás el título **Conectar GitHub** y "Para que tus Bots trabajen en tus proyectos."
2. Toca **Iniciar sesión con GitHub**. Se abre una página de GitHub.
3. **Solo la primera vez**, GitHub muestra **un solo botón Crear** para la App de VectoBots. Apruébalo una vez. GitHub te pide aprobar una vez y después eliges qué proyectos pueden ver los Bots: **todos**, o solo los que elijas.
4. GitHub te regresa a la app. Ves "GitHub está conectado" y la pantalla **Elige un proyecto**.

La pantalla lista los tres pasos así: Iniciar sesión con GitHub, Elige qué pueden ver los Bots, Regresa y elige un proyecto.

## Cómo iniciar un proyecto

1. En **Elige un proyecto**, busca el que quieres. Usa **Buscar un proyecto** para filtrar. Cada fila dice Privado o Público y cuándo se actualizó por última vez.
2. Toca **Iniciar** junto a él.
3. La app pregunta "¿Iniciar un proyecto desde [nombre]?". Toca **Iniciar proyecto**, o **Cancelar**.
4. La fila muestra "Preparando…" y luego "Proyecto listo."

## Cada botón y línea explicados

- **Actualizar.** Vuelve a cargar la lista. Úsalo después de agregar un proyecto nuevo en GitHub. La app dice "Al día."
- **Buscar un proyecto.** Filtra la lista mientras escribes. "Sin coincidencias" significa que nada coincide; "Aún no hay proyectos" significa que todavía no elegiste ninguno en GitHub.
- **Elegir más en GitHub.** El enlace debajo de la lista. Abre GitHub para que permitas más proyectos. Regresa y toca **Actualizar**.
- **Intentar de nuevo / Quitar.** Aparecen en un proyecto que falló al copiarse. La fila dice "No se pudo copiar:" con el motivo. **Intentar de nuevo** repite la copia. **Quitar** lo saca de la lista ("Quitado").
- **Cerrar sesión de GitHub.** Desconecta la app de tu cuenta de GitHub. La app dice "Sesión de GitHub cerrada."

## Ejemplos

Una consultora tiene un sitio web pequeño en GitHub. Conecta, permite solo ese proyecto y toca **Iniciar**. En VectoCode le pide a un Bot que corrija una errata y agregue una página. El Bot trabaja en su propia copia. Cuando ella queda conforme, le dice que guarde el trabajo en GitHub.

Una coach tiene varios proyectos, entre ellos uno privado con formularios de clientes. Cuando GitHub pregunta qué proyectos pueden ver los Bots, elige solo el del sitio web público. El privado queda invisible para sus Bots.

## Problemas comunes

- **"Aún no está listo", con un motivo debajo, o "Necesita la clave de la Bóveda".** La app no puede guardar tu conexión de GitHub de forma segura hasta que la clave de la Bóveda esté configurada. El motivo de abajo dice qué falta.
- **"GitHub no terminó. Intenta de nuevo."** Saliste de GitHub antes de terminar, o falló. Toca **Iniciar sesión con GitHub** otra vez.
- **No veo mi proyecto.** Todavía no lo permitiste. Toca **Elegir más en GitHub**, permítelo y luego **Actualizar**.
- **"No se pudo copiar".** Toca **Intentar de nuevo**. Si sigue fallando, toca **Quitar** y vuelve a iniciarlo.

## Relacionado

- [Deja que los Bots usen tu laptop]({{ '/es/laptop-control/' | relative_url }})
- [Costos]({{ '/es/costs/' | relative_url }})

[Todos los artículos de ayuda]({{ '/es/' | relative_url }})
