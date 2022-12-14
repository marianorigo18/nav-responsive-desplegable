# nav-responsive-desplegable
Este es un muy lindo menu de navegacion responsivo creado con html css and javascript

La clave de un menu responsivo son las clases de css y el dinamismo que le asignemos con javascript.

La clase .nav_navbar tiene una position absoluta y un right del 100% osea que el menu con dicho right esta oculto,
lo que hacemos con javascript es asignarle un evento click a un boton que se encuentre accesible y visible para el 
usuario, le asignamos un evento click que cuando esto suceda cambie la clase a .menu_visivility que dicha clase tiene 
como propiedad un right de 0 haciendo asi que cuando le demos click a un boton el menu se pueda ver, y con la p´ropiedad
toggle si le damos click otra vez a boton se eliminara la clase agregada, haciendo asi que se vuelva a ocultar el menu responsivo.
