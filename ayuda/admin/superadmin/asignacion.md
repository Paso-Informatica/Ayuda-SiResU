# Asignación de Permisos

La asignación y eliminación de permisos de otros administradores es un proceso muy sencillo. En un panel de control
se puede ver una tabla con todos los permisos disponibles y quien tiene cada permiso.

## Dar permiso a un usuario

Para dar un permiso a un usuario, si este usuario ya era un administrador de antemano, tan sólo es necesario activar
el deslizador del permiso correspondiente.

En caso de ser un nuevo administrador, habrá que clicar en `Añadir Admin` e introducir su DNI para buscarlo y añadirlo:

<figure markdown>
  ![superadmin.png](../assets/img/admin/superadmin/asignacion1.png)
  <figcaption>Buscar Usuarios</figcaption>
</figure>

A continuación aparecerá en la tabla y ya se le podrá dar el permiso deseado.

## Eliminar un permiso a un usuario

Para quitarle un permiso a un administrador, basta con desactivar el deslizador del permiso correspondiente:

<figure markdown>
  ![superadmin.png](../assets/img/admin/superadmin/asignacion2.png)
  <figcaption>Buscar Usuarios</figcaption>
</figure>

Por lo general, un administrador sin permisos desaparecerá de la tabla. Si tras quitar el último permiso no desaparece
de la tabla, es probable que el administrador sea un super-admin.

## F.A.Q.

!!! question "No me aparecen las pestañas de los nuevos permisos"
    Si te acabas de asignar o eliminar un nuevo permiso a ti, será necesario que actualices dos veces la página para
    ver los cambios reflejados (la primera para actualizar la sesión, y la segunda para actualizar la interfaz). Esto
    sólo es necesario si tenías una sesión abierta.

!!! question "¿Los cambios son inmediatos?"
    **Sí.** Aunque se tarden en reflejar en la interfaz, el administrador al que se le quiten permisos no podrá ejecutar
    ninguna acción relacionada con ese permiso a partir de ese mismo momento (se le mostrarán errores).
