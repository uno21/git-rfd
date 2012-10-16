# Ruby Fun Day
## git y GitHub - primeros pasos
facilitado por [@luke_ar](http://www.twitter.com/luke_ar) / [@matitanio](http://www.twitter.com/matitanio)

### Consignas
¡Recordá hacer **commit** al finalizar cada punto!

Por si acaso, te dejamos a mano un [breve instructivo](http://marklodato.github.com/visual-git-guide/index-es.html) sobre el uso de git

0. Creá un **fork** (desde la interfaz web de GitHub) de este repositorio de GitHub en tu cuenta, y hacé un **clone** desde tu computadora.
1. Cambiá el título de la página por alguno que vos quieras.
2. Generá un **branch** nuevoContenido para hacer un cambio de contenido, y hacelo.
3. Volvé al **branch** master y cambiá el contenido por estas consignas.
4. Hacé un **merge** del branch nuevoContenido, y resolvé el conflicto
5. Borrá el **branch** nuevoContenido, ya que se ha vuelto un branch que ya no tiene sentido conservar.
6. Hacé varios cambios: color de fondo, subtítulo y agregá un footer. Agregá todo con [git add .].
Como verás, este commit que estás por hacer no es atómico (estas mezclando muchos cambios en un sólo commit). Hacé un **reset** y agregá y commiteá los cambios de a uno con el modo interactivo [git add -i]
7. Hacé un **push** al server de GitHub. Si no tenías cuenta anteriormente, o si no la tenés configurada en esta computadora, eguramente te pedirá que registres las claves ssh. Para eso, te acercamos [este instructivo](https://help.github.com/articles/generating-ssh-keys)