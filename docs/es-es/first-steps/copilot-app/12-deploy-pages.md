---
title: "Lección 12 - Publica el sitio con GitHub Pages"
description: "Utiliza la aplicación GitHub Copilot para configurar un flujo de trabajo de Pages, revisar su solicitud de incorporación de cambios y comprobar el Space Quiz publicado."
authors:
  - jamesmontemagno
lastUpdated: 2026-10-12
---

Publica el Space Quiz en GitHub Pages para que cualquiera pueda acceder a él. Copilot puede preparar el flujo de trabajo y guiarte durante el despliegue, pero eres responsable de revisar los cambios y confirmar que el sitio está publicado.

En esta lección:

- pedirás a Copilot que configure un despliegue en GitHub Pages.
- revisarás el flujo de trabajo y la solicitud de incorporación de cambios antes de combinarlos.
- seguirás el despliegue y comprobarás el sitio publicado.

## Escenario

El Space Quiz ya está en un repositorio de GitHub, pero quienes quieran probarlo necesitan una forma sencilla de hacerlo. Al publicar el sitio de un solo archivo con GitHub Pages, estará disponible en un localizador uniforme de recursos (URL) público sin añadir un servidor ni dependencias de ejecución.

## Pide a Copilot que despliegue el sitio

En la sesión de la aplicación Copilot para `space-quiz`, envía este prompt:

```plaintext
Habilita GitHub Pages en este repositorio. Crea un flujo de trabajo de GitHub Actions que compile el sitio web si es necesario y lo despliegue en GitHub Pages. Añade un README que describa la aplicación y cómo ejecutarla en local si aún no existe. Crea una solicitud de incorporación de cambios con estos cambios y combínala cuando se superen las comprobaciones obligatorias. Supervisa el despliegue hasta que termine correctamente y, después, indica el localizador uniforme de recursos (URL) final del sitio web publicado. Si no tienes permiso para habilitar Pages o combinar la solicitud, dime exactamente qué tengo que aprobar o hacer; no indiques que se ha completado hasta que el sitio esté publicado.
```

![Diagrama de tres fases: una solicitud de incorporación de cambios de space-quiz combinada; una ejecución correcta de Deploy website en GitHub Actions con los pasos Build website, Upload artifact y Deploy to Pages; y el Space Quiz publicado en yourname.github.io/space-quiz/.](../../../_images/first-steps-app-pages-deploy.svg)

> [!WARNING]
> Este prompt pide al agente que cree y combine una solicitud de incorporación de cambios y cambie la configuración de Pages del repositorio. Antes de continuar, revisa el diff, los permisos de despliegue y cualquier solicitud de aprobación de GitHub.

## Revisa el flujo de trabajo y comprueba el despliegue

Revisa cada etapa para confirmar que los cambios son correctos y que el sitio se ha publicado antes de dar la tarea por terminada.

1. Confirma que el README solo se añade si el repositorio aún no tiene uno.
2. Revisa los cambios de la solicitud de incorporación de cambios, incluidos los pasos de compilación y despliegue del flujo de trabajo.
3. Combina los cambios únicamente después de que se superen las comprobaciones obligatorias de la solicitud.
4. Sigue la ejecución de despliegue de GitHub Actions hasta que termine correctamente.
5. Abre la URL indicada y confirma que se carga el Space Quiz.

Si el agente no puede habilitar Pages o combinar la solicitud de incorporación de cambios, sigue las instrucciones concretas que te proporcione. No des la tarea por completada hasta que el despliegue termine correctamente y se cargue el sitio publicado.

## Resumen y siguientes pasos

Tu Space Quiz ya está disponible como sitio publicado y has comprobado el despliegue en lugar de confiar únicamente en el informe del agente. Continúa con [Lección 13: Repaso y siguientes pasos][next-lesson].

[next-lesson]: ../13-review/
