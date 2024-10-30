---
layout: post
title: "Aprendiendo Arquitectura de Software"
description: "Trade-offs una de las primeras cosas a aprender a identificar"
date: 2023-02-11 22:40:00 +0300
image: '/images/05-1.jpg'
tags: [architecture, learning]
categories: General
---

Hace algún tiempo en mi empresa tomé el cargo de Arquitecto de Software, es primera que vez tomo este cargo formalmente, previamente este rol ha estado dentro de un rol de Desarrollador Full Stack. Ahora es más formal, es un proyecto más grande y complejo. Dicho esto quiero compartir algunas reflexiones de lo que estudiado acerca de Arquitectura de Software y cosas que creo que me ayudan a complementar mi rol.

Para este cargo, algo que me propuse es leer un libro referente al tema, investigue algunos libros asociados al tema, el elegido fue [Fundamentals of Software Architecture](https://www.oreilly.com/library/view/fundamentals-of-software/9781492043447/) el cual he ido estudiando capítulo a capítulo y uno de los primeros conceptos importantes a aprender en este ámbito son los **Trade-offs**. Si sabes ingles puedes deducir que se trata.

# Trade-offs

Cuando uno tiene elegir algún tipo de herramienta, software, patrón de diseño, framework o incluso como codeas el flujo de código, estas eligiendo un forma de estructura sobre todas las otras posibles y si solo estás encargado de desarrollar es posible que estés pensando en todos los beneficios de elegir una opción sobre la otra. Desarrollar una API en Python con Fast API puede ser muy parecido a hacerlo en Flask, pero a la vez algo más distinto que hacerlo en Django (aunque sigan siendo Python), pero completamente distinto a utilizar Java con el framework Spring. Acá es donde el desarrollador conoce y le importan los beneficios de desarrollar en un entorno específico, pero es tarea del Arquitecto de Software discriminar qué beneficios y pérdidas de elegir cierta opción.

Para construir un microservicio, FastAPI y Flask pueden ser adecuados, en cambio Django a pesar de ofrecer muchas herramientas para múltiples objetivos puede quedar muy grande para un microservicio, al igual que Java Spring (ya que necesita más desarrollo y recursos entre otras cosas). Ahora, si necesito construir un sistema más robusto, donde debo separar distintas capas de abstracción, elegir entre Django y Spring puede depender desde aspectos de facilidad de desarrollo, de seguridad o incluso burocráticos.

Un Arquitecto de software debe aprender a realizar este tipo de decisiones, tiene que sopesar qué solución se ajusta a los requerimientos dados. Desde elegir si vamos a crear una aplicación monolítica o usar micro servicios o qué servicio de protocolo de Publicación/Subscripción (Pub/Sub) elegir, ¿Amazon SQS o Rabbit MQ?, o quizás base de datos ¿MySQL, Postgres o Oracle?, ¿Servidores dedicados o una arquitectura Serverless?.

Lo más importante a entender es que no se trata de elegir el mejor, si no reconocer las diferencias de cada un de las alternativas sobre las otras, preguntarse cómo la elección de una limita los objetivos, ya sea en el resultados a corto plazo o cómo influye el desarrollo futuro, de que se gana (o pierde) a cambio (Trade-off) de elegir una solución con respecto a otra.

# Ademas...

Ok, este fue mi primer post real, me hubiera gustado ahondar un poco más, pero quizás me pueda dar para hacer una continuación. Por ahora me enfocaré en hacer lo mejor que pueda, sin poner mucha carga al escribir estos posts, los haré en español y no en inglés como lo pensaba originalmente.

Bye.
