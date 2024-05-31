# Repositorio Android para el Minimo 2 de DSA.

Funcionalidad que permita realizar una denuncia de un abuso con la siguiente información: fecha, nombre, comentario.

T2: En la APP Android, añadir una opción en el "dashboard" para denunciar un
abuso. La nueva actividad preguntará por el nombre y una descripción y enviará a la
API dicha información. --> COMPLETADA

- Se ha creado una actividad llamada denuncia_activity con los campos de entrada Fecha Titulo y Mensaje.
- Se ha creado la clase de esta actividad con su funcionalidad hecha para enviar a la API los campos correspondientes.
- Se ha creado la clase Denuncia con sus respectivos campos.
- En UsuarioService se ha hecho la llamada a la API.
