# Proyecto Final - Backend de una Aplicación Ecommerce

## LEIBLICH Ezequiel Gaston

## Comisión 43345 - Programación Backend


##Backend de una Aplicación Ecommerce
¡Bienvenido a mi proyecto final de backend para una aplicación de ecommerce! He realizado una serie de mejoras y ajustes clave en el backend de la aplicación para brindar una experiencia de compra completa y cerrar detalles administrativos con los roles de usuario.

## Rutas de Usuarios

He creado tres nuevas rutas en el router /api/users para gestionar los usuarios de manera eficiente:

GET /: Esta ruta obtiene todos los usuarios y devuelve sus datos principales, incluyendo nombre, correo y tipo de cuenta (rol).

DELETE /: Limpia a todos los usuarios que no han tenido una conexión en los últimos 2 días. Además, se envía un correo electrónico a los usuarios cuyas cuentas se han eliminado por inactividad.

Vista Administrativa: He creado una vista administrativa que permite visualizar, modificar el rol y eliminar a los usuarios. Esta vista solo es accesible para el administrador del ecommerce.

## Eliminación de Productos
He modificado el endpoint que elimina productos para que, en caso de que el producto pertenezca a un usuario premium, se le envíe un correo electrónico informando que el producto ha sido eliminado. Esto mejora la comunicación con los usuarios premium y les proporciona una notificación relevante.

## Vistas para el Proceso de Compra
He finalizado las vistas necesarias para llevar a cabo un flujo completo de compra en la aplicación. Aunque no he especificado una estructura específica de vistas, he creado las que consideramos esenciales para la realización de todo el proceso de compra.

## Despliegue
He desplegado la aplicación en la plataforma Railway.app y he comprobado que se puede llevar a cabo un proceso de compra completo. Railway.app fue mi elección para el despliegue, como se sugirió en el curso.


## Objetivos Cumplidos:

Con este conjunto de mejoras, he alcanzado los siguientes objetivos:

Ofrecer una experiencia de compra completa a los usuarios.
Cerrar detalles administrativos relacionados con los roles de usuario.


# Agradecimiento
¡Gracias por revisar mi proyecto final! Si tienes alguna pregunta o necesitas asistencia adicional, no dudes en ponerte en contacto conmigo.
