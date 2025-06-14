# Laboratorio2_Robotica

En este repositorio se informa el proceso que se realizó para el uso de un manipulador industrial IRB 140 con el objetivo de lograr el dibujo en una "torta" de los nombres de los integrantes del grupo.
Con ayuda del software RobotStudio se realizó la programación y simulación de las rutinas requeridas para lograr el objetivo. 
Esta simulación se observa en 
![Simulación](https://github.com/Juanfe710/Laboratorio2_Robotica/blob/main/Simulacion/Video.md)
Para conseguir el objetivo se tuvo que primero modelar e importar la herramienta dentro de la interfaz de RobotStudio.
Para esto se realizó el modelado en Inventor y posteriormente se importé al software a trabajar. Aquí se realizó la debida calibración de herramienta y se instaló en el robot para que fuera el efector final.
![Herramienta](https://github.com/Juanfe710/Laboratorio2_Robotica/blob/main/Dise%C3%B1o%20de%20Herramienta/Dise%C3%B1o%20de%20Herramienda.md)
Luego de conseguirlo se realizó el modelo en 3D, también usando Inventor, del "pastel" que en este caso sería una caja de (25.6x14.6x13.8) cm, y se importó en RobotStudio y se ajustó el workobject en la superficie de este. Con esto se establecen los puntos por los que pasará el marcador para marcar la S, que es la primera letra para escribir "Santi y Juan".

Con los puntos definidos se determina la trayectoria que seguirá el robot, y al final de esta se desplaza el manipulador a un punto encima de la superficie para alistarse para moverse a la siguiente ubicación para realizar la siguiente letra. Este proceso se repite con cada una de las letras a inscribir en el pastel. Además se realizan las trayectorias circulares de los dibujos adicionales, que en este caso será un Pacman y un fantasma.

