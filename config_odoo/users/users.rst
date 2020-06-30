*********
Usuarios
*********

En Odoo se define un **Usuario** como alguien que tiene acceso a la base de datos y puede realizar diferentes tareas dentro de Odoo.

Se pueden añadir tantos usuarios como el administrador desee, de igual manera el administrador podrá administrar los permisos de acceso a las diferentes aplicaciones dentro de Odoo para cada usuario individualmente.

.. figure:: /users/pics/00.png

    ¿Cúantos usuarios necesitamos?

Añadir nuevos Usuarios
========================

Desde Ajustes
--------------

Esta forma de añadir un nuevo usuario es recomendada si el usuario no está añadido en el aplicación Odoo de **Empleados** aún.

Para empezar vayamos a **Ajustes** desde el menú principal.

.. figure:: /users/pics/01.png

    **Settings** si tenemos nuestro Odoo en inglés

Y a continuación al menú **Administrar permisos de acceso**

.. figure:: /users/pics/02.png


Hacemos click en **Crear** y ingresamos los datos, permisos y preferencias del usuario.
Tanto los permisos como las preferencias se podrán modificar en el futuro.


.. figure:: /users/pics/03.png

    Los campos sombreados en azul son obligatorios

Nota
    La posibilidad de elegir el tipo de usuario entre *Usuario Interno*, *Portal* o *Público* será unicamente posible si tenemos el modo desarrollador activado.

Una vez hagamos click en **Guardar** el usuario será creado. El administrador podrá mandarle un correo de invitación a la plataforma además de la posibilidad de resetear la contraseña del usuario en todo momento desde el mismo menú


Desde Contactos
----------------

Un usuario creado de esta forma por defecto solo tiene acceso de lectura. No podrá editar ningún documento en el sistema.

En el menú principal, seleccione **Contactos**. Si el Contacto no está creado todavía en el sistema, haga click en el botón **Crear** para crear un nuevo contacto. Ingrese los detalles y haga click en **Guardar**.

Si por el contrario el **Contacto** ya existe en el sistema o ya lo acaba de crear, seleccione el contacto deseado y haga click en el menú **Acción** en el centro superior del interfaz y seleccione **Otorgar Acesso al Portal** en el menú emergente.

.. figure:: /users/pics/04.png

    Todos sus datos son ficticios.

Una nueva ventana aparecerá, el **correo electrónico** será el login del usuario, aparecerá por defecto si el contacto ya lo tenía añadido,
seleccione la casilla **En el Portal** y además podemos agregar un texto para ser incluido en el correo electrónico de invitación.

.. figure:: /users/pics/05.png

    Importante seleccionar la casilla **En el Portal**.

Haga click en **Aplicar** cuando haya terminado. Odoo enviará un e-mail con las instruciones para acceder al portal.


Vía invitación
----------------

Desde el menú **Ajustes** puede invitar a tantos usuarios como usted necesite añadiendo únicamente su dirección de correo electrónico y haciendo click en **Invitar**.

.. figure:: /users/pics/07.png

    Invitaciones a golpe de click.

Desde Empleados
-----------------

Ver en módulo **Empleados**.