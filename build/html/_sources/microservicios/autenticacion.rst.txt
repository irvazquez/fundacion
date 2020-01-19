Servicio de Autenticación
=========================

.. toctree::
   :maxdepth: 2

.. _introduccion-autenticacion:

Introducción
-------------

Esté es uno de los servicios, sino el que más importa, debido a la responsabilidad que tiene. Este servicio es el encargado se permitir a un usuario ingresar a una sección de la aplicación, ó denegarselo. Practicamente a este servicio, sotod los demás tendran que conectarse para verificar la información del usuario y así permitirle o denegarle el acces

Para este servicio se tiene pensado implementar `JWT <https://jwt.io/>`_, el cual sirve para `tokenizar` (encriptar), la información del usuario, guardar la información encriptada del usuario en una variable de sesión, y mandarla en cada petición que el usuario haga a la aplicación. Solo el servicio que hizo la encriptación puede decencriptarlo, y de esta forma, válidar al usuario en todo momento con el mismo servicio.