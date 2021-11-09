# ![4Geeks Logo](http://assets.breatheco.de/apis/img/images.php?blob&random&cat=icon&tags=4geeks,16) Sitio Web colaborativo (Git collaboration)

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io#https://github.com/4GeeksAcademy/html-hello.git)

El objetivo de este proyecto es poner en práctica las habilidades en GIT a la vez que desarrollamos un sitio web, en concreto una página que trata sobre la festividad
de la Feria de Málaga. La idea es que cada alumno trabaje en un archivo diferente para cada parte del sitio web, y finalmente se realice una integración así como un despliegue. 

Alumno 1: Marina Roz <br>
Alumno 2: Jesús Cano

### Instrucciones 

1. El líder del equipo debe hacerle fork al repositorio del proyecto en GitHub e invitar a otros colaboradores a participar en este repositorio.
2. Iniciad la creación del proyecto creando la que será la rama master con el archivo index.html (esta rama no debe ser modificada hasta el final).
3. Posteriormente, crear una rama auxiliar (ej: rama-dev) que servirá para que cada colaborador haga push de sus respectivas modificaciones. 
4. Y para terminar, cada colaborador deberá tener una rama propia (rama1, rama2...) donde trabajar y guardar su progreso, y desde la cual hará 
las modificaciones necesarias antes de enviar los archivos a la rama auxiliar. 

Un ejemplo de correcto flujo de desarrollo sería el de la siguiente imagen: 

<p align="center">
  <img width="600" src="https://miro.medium.com/max/823/1*uUpzVOpdFw5V-tJ_YvgFmA.png" alt="Git Flow Scheme">
</p>

- La rama azul (master), debe ser única y no ser modificada hasta el momento de la integración/despliegue. 
- La rama lila (develop), hace referencia a la rama auxiliar, donde se enviará el progreso de los diferentes colaboradores.
- Las ramas verde (feature), corresponden a los progresos de cada colaborador.  

RECUERDA: Una vez que cada colaborador del equipo termina con su progreso, debe hacer commit y push a su rama así como a la rama auxiliar, mediante el siguiente
comando: 

```sh
$ git add . 
$ git commit -m "Mensaje"
$ git push origin rama-colaborador --> rama1, rama2...
$ git push origin rama-colaborador:rama-auxiliar
```