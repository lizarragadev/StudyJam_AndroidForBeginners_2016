Proyecto Final - Study Jam II 2016
===

Repositorio Proyecto Final del Study Jam Android Development for Beginners II 2016, llevado a cabo en la ciudad de La Paz, Bolivia a cargo del [GDG Android Bolivia](http://www.gdg.androidbolivia.com).

Nombre Aplicacion.
---
El nombre de la aplicacion es: SantaApp

Objetivo
---
Listar y detallar todos los lugares que Papa Noel debe visitar.

Caracteristicas
---
* Musica de fondo (Con opcion activar/desactivar).
* Visualizar en Google Maps la ubicacion exacta del lugar.
* Vibracion cuando encuentre un lugar donde deba dejar regalos.

Compatibilidad
---
Esta aplicacion es compatible con versiones de Android 4.2 o superior.

Uso
---------
Para probar este ejemplo clona este repositorio de la siguiente forma:
>
>     $ git clone https://github.com/Gusn8/ProyectoFinal_StudyJam.git

Dentro de Android Studio:

* File --> New --> Import Project 
* Seleccionas la ruta donde hiciste el `clone` del proyecto.
* Build --> Rebuild Project
* Run 

Captura y corrida
---
<div align="center">
    <center>
        <table border="0">
            <tr>
                <td><img src="/img/corrida_01.gif" width="250"></td>
                <td><img src="/img/corrida_02.gif" width="250"></td>
                <td><img src="/img/corrida_03.gif" width="250"></td>
            </tr>
        </table>
    </center>
</div>
<br>

Descripcion tecnica
---
En este proyecto de utilizaron los siguiente componentes tanto en la vista como en la funcionalidad:
Vista:
* LinearLayout (Horizontal) para la alineacion de las vistas principales.
* RelativeLayout, para el acomodamiento de la segunda pantalla: SegundaActivity.
* ToggleButtons, para activar y/o desactivar el sonido en la aplicacion.
* EditTexts, para recabar informacion acerca de los nombres de las personas.
.
.
.

Funcionalidad:
* MediaPlayer, para reproducir la cancion de fondo de la app.
* Vibrator, para asignar una vibracion en ciertas partes de la app.
* Ciclo de vida de una Activity, para detectar cuando se coloca en Pausado asi pueda seguir ejecutandose una tarea.
.
.
.

Autor(a)
---
Gustavo Josue Lizarraga

Contactos
---
[Facebook](https://www.facebook.com/Gusn8)
[Twitter](https://www.twitter.com/Gusn8_)
[Google Plus](https://www.plus.google.com/GustavoLizarraga)
[Github](https://www.github.com/Gusn8)
[Sitio Web](http://www.miramicodigo.com/)
