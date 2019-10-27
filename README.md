# ¿Qué es una botonera?
“Una botonera” es un conjunto de botones que redireccionan cada uno a su canal.
Como bien dicen, una imagen vale más que mil palabras, por ello aquí tienes un ejemplo gráfico:

![La Botonera](/media/botonera.png)

# ¿Qué es "La Botonera"?
La Botonera es un grupo que realiza botoneras de forma automática. Esto es, la botonera se publicará y se eliminará automáticamente de los canales que estén correctamente asociados y con la participación activa.
"La Botonera" cuenta con características que ningún otro grupo que realice botoneras tiene, entre las cuales se pueden destacar:

1. Gestión propia de tu botón en la botonera.
1. Gestión propia de tu participación.
1. Capacidad de protección de tu canal frente a usuarios no deseados, como copiadores de contenidos o userbots
1. Publicación y eliminación automática
1. Informe de crecimiento al finalizar la botonera.
1. Los canales se ordenan automáticamente para la siguiente botonera en función de las vistas realizadas.
1. Si un usuario elimina la botonera de su canal, su botón desaparece casi en tiempo real del resto de canales.
1. Cuenta atrás en el mensaje de la botonera, de tal forma que se sabe cuanto tiempo resta para la eliminación automática


# ¿Cuando se hace?

El día establecido de publicación de **La Botonera** se define en el grupo que lo realiza. Estas dudas deben ser consultadas con los administradores.

# ¿Cómo funciona?

Los canales asociados y registrados se agrupan en "Botoneras", en función de las vistas que se realizan en la botonera anteriormente realizada. Un canal nuevo, por tanto, aparecerá en la botonera de menos visualizaciones.

Los botones de las botoneras se ordenand en función de las vistas realizadas en la ultima participación que hizo en ese mismo día, y se agrupan los canales en bloques de entre 9 y 11 canales normalmente.

Las botoneras se publicarán a la vez, cada una en su grupo de canales correspondiente. Si un usuario consigue sobrepasar 
las visualizaciones requeridas pasará a la botonera número 1, en caso de perderlas pasará a la botonera 2. El cambio de 
botonera se aplicará en la siguiente semana hábil en la cual se publique La Botonera.

La franja horaria en la que estará publicada la botonera queda reflejado en el grupo que realiza la botonera. Suele ser en horario nocturno, tomando como referencia desde 22.00h (10:00 PM) hasta las 09:00h (9:00 AM) hora Española (GMT+1).


# Requisitos para unirse a la botonera

1. No se permite la participación de grupos, solo de canales.
1. El canal debe tener al menos **100 suscriptores**, aunque podría variar en el tiempo y según que botonera. Otros requisitos especiales pueden ser solicitados en cada grupo que organiza la botonera.



# ¿COMO UNO MI CANAL A LA BOTONERA?

1. Debemos añadir el bot @labotonera_bot como administrador del canal y dale los siguientes permisos: **Publicar mensajes, Añadir usuarios** y **Eliminar mensajes de otros** (Este último es opcional, pero en caso de bloqueo por publicación, el canal no será desbloqueado)
    
    ![Permisos necesarios](/media/permisos_labotonera_bot.png)

2. Reenviar un mensaje que solo contenga **solo texto** preferentemente al grupo [**La botonera**](https://t.me/LaBotonera) https://t.me/LaBotonera. Este mensaje no debe proceder de otro reenvío, debe ser un mensaje publicado directamente en el canal que se pretende registrar. Realizando esto, nuestro canal quedará asociado.


# ¿Cómo creo o modifico mi botón?

La creación o modificación y el registro del botón se realiza con la misma orden, la cual se debe enviar al grupo que organiza la botonera:
 ```
 /registrar_boton@labotonera_bot @alias_del_canal texto_del_boton
 ```

* alias_del_canal: Alias de nuestro canal. Respeta las mayúsculas y minúsculas del alias de tu canal. (CASE SENSITIVE). 
* texto_del_boton: Texto que aparecerá dentro del botón cuando se publique.

Si el canal no es público, no tendrá alias, en ese caso hay que usar un pseudo-alias. Para consultar el pseudo-alias asignado, puedes ejecutar la siguiente orden en el grupo:
```
/mis_canales
```

# ¿Cómo activo o desactivo mi botón?

Una vez registrado tu canal, y con tu botón creado, solo te queda activarlo. Para ello debes usar el siguiente comando el grupo que organiza la botonera:

```
/mis_canales
```


Una vez que se activado o desactivado el canal es **efectivo para las siguientes botoneras** hasta que sea nuevamente cambiado este estado.

# ¿Que otros comandos existen?

Por ahora se han implementado los siguientes comandos:

## Comandos para usuarios
```
    /mis_canales
    /registrar_boton @alias_del_canal Texto boton 
    /ayuda (/help, alias de /ayuda)
    /enlace_privado alias_del_canal
    /mis_canales
    /protección
```

## Comandos para administradores
```
    /publish
    /delete
    /muestra_botoneras
    /informe_vistas
    /update_vistas
    /chan_stats
```


# Normas Generales y penalizaciones

1. No está permitida la publicación de ningún mensaje en el canal mientras dure visible **La Botonera**. En caso de producirse y detectarse se penalizará con un warn. Tres warn significarán la **expulsión definitiva** de **La Botonera**.
1. No se puede eliminar la botonera de forma manual. Se asume que esta acción ha sido intencionada con el único objetivo de beneficiarse del resto de usuarios. Esta acción conlleva la **expulsión definitiva**.
1. El administrador que registra el canal es responsable de coordinarse con el resto de admins.
1. No se permite **COMPARTIR** el mensaje de la botonera en ningún canal o grupo. Si se detecta, **podría ser expulsado permanentemente**, al igual que no se permite hacer publicidad en grupos de SPAM o canales desde **dos horas** antes del comienzo hasta la finalización de la misma.
1. Si has recibido un warn, deberás publicar la botonera de tu grupo durante una noche de un día que no sea la botonera. En caso contrario, no podrías participar en la siguiente botonera.
1. El texto de los botones no debe hacer apología a la pornografía, ni contenido para adultos.
1. El texto de los botones no debe ser engañoso, y debe reflejar el contenido del canal.
1. No se podrán registrar canales en los que al menos uno de los administradores esté en la lista de baneo completo
1. Los grupos de la botonera no es un medio para contactar a otros miembros para puentes/botoneras o enviarle SPAM. Esta acción será penalizada

# F.A.Q (Preguntas y respuestas frecuentes)
<b>Mi canal no aparece en la lista de botones. ¡Estoy haciendo publicidad gratis!</b>
No, no estas haciendo publicidad gratis, lo que ocurre es que tu botón se elimina de tu canal para optimizar la botonera, ya que tu botón dirige a tu canal

<b>Tengo la participación activa, cuando pido /mis_canales, tengo el canal con el tick en verde, pero no se ha publicado</b>
Una de las mejoras que tiene la botonera, es que si un canal no está activo en los últimos días, no particpará en la botonera, esto es para evitar la participación de canales que no tienen actividad.


