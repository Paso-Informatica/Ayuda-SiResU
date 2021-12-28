# Gestión de Superadmins

La gestión de super-admins es manual. Sólo el administrador de la base de datos puede hacerlo, ya que requiere tener
acceso directo a la propia base de datos. Esto se hace así para garantizar la seguridad e integridad, ya que puede ser
un permiso peligroso, y para evitar posibles elevaciones de permisos que no cumplan la jerarquía establecida.

Por lo general, el super-admin será el responsable del Paso. En caso de querer designar más super-admins, contactar con
el administrador de la base de datos.

## Administrador

Cada Paso tendrá su propio administrador. La plataforma fue creada por [Diego Barreiro](https://diego.barreiro.xyz),
por lo que posiblemente debas contactar con él ([diego@barreiro.xyz](mailto:diego@barreiro.xyz)).

## F.A.Q.

!!! question "¿Es posible asignar super-admin a otro usuario/administrador desde la interfaz web?"
    No, no es posible y no se contempla añadir tal funcionalidad en el futuro.

!!! question "¿Es posible quitarle super-admin a uno ya existente desde la interfaz web?"
    No, no es posible y no se contempla añadir tal funcionalidad en el futuro.

!!! question "¿Cómo puedo contactar con el administrador?"
    Si quieres añadir más permisos, deberás contactar con el administrador de la base de datos del Paso. Tienes más
    información arriba al respecto.

!!! question "¿Es posible saber quienes son los otros super-admins?"
    No es posible, pero es posible _intuirlo_. Cuando se eliminan todos los permisos de un administrador, si esa persona
    no desaparece de la lista de administradores es porque está protegido por ser super-admin.
