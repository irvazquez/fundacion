Microservicios
==============

.. toctree::
   :maxdepth: 2
   
   pagina-estatica
   autenticacion
   pagos
   e-commerce
   reportes
   eventos

.. _introduccion-modulos:

Introducción
------------

Una de las mejores formas de poder crear una aplicación web que pueda ser escalable y de facil mantenimiento es usando módulos independientes que se comuniquen entre sí, de esta manera cada módulo solo tiene una obligación principal y no requiere guardar la información que no le compete. Esto hace que este tipo de aplicaciones sean mas seguras.

Para este desarrollo optamos esta forma por las ventajas que presenta, aunque cabe decir que, como cualquier otra forma de desarrollo, también tiene sus desventajas.

.. _ventajas-servicios:

Ventajas
--------

* Cada servicio puede ser desarrollado con la tecnología con la que el desarrollador se sienta comodo, ó sea la mejor para desarrollar la responsabilidad que tendrá.
* El backend y frontend serán independientes (Esto para cada servicio).
* El agregar una nueva función a un servicio será más sencillo y con menos probabilidades de que falle toda la aplicación al momento de hacer la integración.
* La comunicación entre servicios es estandatrizada. (A traves de `JSON's <https://www.json.org/json-es.html>`_)
* Cada servicio contará con su propia base de datos.

.. _desventajas-servicios:

Desvantajas
-----------

* El mantenimiento se puede volver problematico (del Frontend y del Backend), si el número de tecnologias usadas es alto, debido a que se requeriría contar con al menos un desarrollador para cada tecnología usada. (Un desarrollador podría dominar 2 ó más tecnologías)

.. _algo-mas-servicios:

Algo a tener en cuenta
----------------------

Todo el desarrollo contará con documentación del estilo de este documento, con anotaciones especificas para los desarrolladores. El tiempo de crear una documentación es muy similar al tiempo de el desarrollo de la aplicación web.
Además de que se integraran test automatizados para que si en un futuro es requerido hacer sun refactor, este sea más sencillo de hacer.