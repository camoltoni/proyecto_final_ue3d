<div align="center">
  
 ![image](https://user-images.githubusercontent.com/4754336/177018762-6e094370-c1bf-40d5-864c-9f858fe6fc65.png)
# UNIVERSIDAD NACIONAL DEL LITORAL<br>Facultad de Ingeniería y Ciencias Hídricas
### Tecnicatura en Diseño y Programación de Videojuegos
### Unreal 3D (2022)

</div>

#### Nombre del alumno/s
César Moltoni

#### Nombre del juego
No te derritas

#### Descripción de una línea
Sortear obstáculos y recoger items sin tocar el piso que es lava.

#### Historia
La central nuclear entró en fusión y hay que escapar antes que sea tarde. El personaje se encuentra en la sala de control de una central nuclear, en ella hay un taller de reparaciones, un elevador para depositar materiales en una plataforma y distintos módulos para propósitos generales. El pasillo de escape está delimitado por paredes vidriadas y una escalera que lleva a la azotea, en la que puede ser rescatado el personal.

#### Premisa
El jugador debe moverse entre plataformas saltando para evitar tocar el piso. Para pasar los distintos niveles tiene que recoger los distintos items y utilizarlos en el lugar indicado para poder escapar y ser evacuado.

#### Puntos clave
- Exploración y solución de problemas.
- Suelo de lava que no se puede pisar.
- Items que recoger y utilizar para poder escapar.

<div style="page-break-after: always;"></div>

#### Personaje
Se usará el personaje Iris que viene incluido en el proyecto de juego en tercera persona que viene con Unreal Engine.

#### Obstáculos
El piso es lava por lo cual no puede ser pisado. Si lo hace se reinicia el juego.

#### Gameplay

<style>
* {
  box-sizing: border-box;
}
p.clear {
  float: left;
  display: inline-block;
  width: auto;
}
img.clear {
  float: right;
  margin-left: 10px;
  display: inline-block;
  width: 60%;
  height: auto;
}
</style>

<p class="clear">
<image src="https://media.githubusercontent.com/media/camoltoni/proyecto_final_ue3d/new-level/Screenshots/LinuxEditor/ScreenShot00000.png" class="clear" />
El juego tiene un componente de exploración por lo que el jugador puede comenzar con distintos recorridos. Puede tomar por el pasillo de la izquierda que lleva a la escalera de emergencia hacia el techo.
</p>
<p class="clear">
<image src="https://media.githubusercontent.com/media/camoltoni/proyecto_final_ue3d/new-level/Screenshots/LinuxEditor/ScreenShot00001.png" class="clear" />
Luego llega a una escalera que no puede subir porque se derrumbó, puede ver también que hay un vidrio rajado y detrás unas cajas que puede empujar para salvar el hueco, pero necesita algo para poder romper el vidrio.
</p>
<p class="clear">
<image src="https://media.githubusercontent.com/media/camoltoni/proyecto_final_ue3d/new-level/Screenshots/LinuxEditor/ScreenShot00002.png"  class="clear"/><br>
Puede tomar hacia el frente y llegar al taller de reparaciones pero la puerta está cerrada y no puede entrar.
</p>
<div style="clear: both;page-break-after: always;"></div>
<p class="clear">
<image src="https://media.githubusercontent.com/media/camoltoni/proyecto_final_ue3d/new-level/Screenshots/LinuxEditor/ScreenShot00003.png"  class="clear"/><br>
Si rodea el taller de reparaciones llega al elevador, pero la palanca para accionarlo quedó lejos porque la lava disolvió una parte de la plataforma.
</p>
<p class="clear">
<image src="https://media.githubusercontent.com/media/camoltoni/proyecto_final_ue3d/new-level/Screenshots/LinuxEditor/ScreenShot00004.png" class="clear" />
Tiene que explorar un poco más en un rincón del edificio principal hay una escoba, la recoge y puede usarla para accionar la palanca del elevador.
</p>
<p class="clear">
<image src="https://media.githubusercontent.com/media/camoltoni/proyecto_final_ue3d/new-level/Screenshots/LinuxEditor/ScreenShot00005.png" class="clear" /><br>
Una vez en el techo del taller va a encontrar que está roto por una explosión por el agujero puede caer y buscar un martillo para poder romper el vidrio.
</p>
Toma el martillo y la puerta del taller se puede abrir de adentro así que sale, va hasta la plataforma de las cajas, rompe el vidrio con el martillo y empuja las cajas al hueco de la escalera, luego vuelve al inicio, toma el pasillo de escape, pasa las escaleras gracias a las cajas y llega al techo para ser evacuado.
