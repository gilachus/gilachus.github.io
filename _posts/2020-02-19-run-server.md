---
layout: post
title: servidor de desarrollo
categories:
 - django
---

Para el ejecutar el servidor de desarrollo de Django te ubicas en tu proyecto, donde se encuentro el archivo manage.py.

`python manage.py runserver`

Puedes especificar un puerto.

`python manage.py runserver 7000`

O ponerlo visible para todos los dispositivos de tu red (configura ALLOWED_HOSTS en settings.py).

`python manage.py runserver 0.0.0.0:8000` 

<small>
[The development server](https://docs.djangoproject.com/en/3.1/intro/tutorial01/)
</small>