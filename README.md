Proyecto Final - Study Jam II 2016
===
<div align="center">
    <center>
        <img src="http://developerstudyjams.com/images/masthead.png" width="400px"/>
    </center>
</div>

Repositorio Proyecto Final del Study Jam Android Development for Beginners II 2016, llevado a cabo en la ciudad de La Paz, Bolivia a cargo del <a target="_blank" href="http://www.gdg.androidbolivia.com">GDG Android Bolivia</a> .

Nombre Aplicación.
---
El nombre de la aplicación es: SantaApp

Objetivo
---
Listar y detallar todos los lugares que Papa Noel debe visitar.

Caracteristicas
---
* Música de fondo (Con opción activar/desactivar).
* Visualizar en Google Maps la ubicación exacta del lugar.
* Vibración cuando encuentre un lugar donde deba dejar regalos.

Compatibilidad
---
Esta aplicación es compatible con versiones de Android 4.2 o superior.

Uso
---------
Para probar este ejemplo clona este repositorio de la siguiente forma:
>
>     $ git clone https://github.com/Gusn8/ProyectoFinal_StudyJam.git

Luego de ello dentro de Android Studio:

* File --> New --> Import Project 
* Seleccionas la ruta donde hiciste el `clone` del proyecto.
* Build --> Rebuild Project
* Run 

Corrida previa
---
Aca te muestro cual es el funcionamiento de mi aplicación a grandes rasgos.
<div align="center">
    <center>
        <table border="0">
            <tr>
                <td><img src="https://github.com/Gusn8/StudyJam_II_CustomListViews/blob/master/img/captura.gif" width="250"></td>
                <td><img src="https://github.com/Gusn8/StudyJam_II_Animations/raw/master/img/corrida_02.gif" width="250"></td>
                <td><img src="https://github.com/Gusn8/StudyJam_II_Intents/raw/master/img/corrida_02.gif" width="250"></td>
            </tr>
        </table>
    </center>
</div>
<br>

Descripción técnica
---
En este proyecto de utilizáron los siguientes componentes tanto en el `diseño` como en la `funcionalidad`:

**`Vista:`**
* LinearLayout (Horizontal) para la alineación de las vistas principales.
* RelativeLayout, para el acomodamiento de la segunda pantalla: SegundaActivity.
* ToggleButtons, para activar y/o desactivar el sonido en la aplicación.
* EditTexts, para recabar información acerca de los nombres de las personas.
.
.
.

**`Funcionalidad:`**
* MediaPlayer, para reproducir la canción de fondo de la app.
* Vibrator, para asignar una vibración en ciertas partes de la app.
* Ciclo de vida de una Activity, para detectar cuando se coloca en Pausado asi pueda seguir ejecutandose una tarea.
.
.
.

Autor(a)
---
Gustavo Josue Lizarraga

Contactos
---
lizarraga.gux@gmail.com

[Facebook](https://www.facebook.com/Gusn8) <br>
[Twitter](https://www.twitter.com/Gusn8_)<br>
[Google Plus](https://www.plus.google.com/GustavoLizarraga)<br>
[Github](https://www.github.com/Gusn8)<br>
[Sitio Web](http://www.miramicodigo.com/)<br>
