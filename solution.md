Solution of the problem

There is an issue in the switch method 
we can change the mode based on the switch movement method
one mthod of not working connection were proper I have checked 

spriteMovement_M2()  this method was working fine
there was an issue with  spriteMovement()

apporach how I solved
I have not worked with qGraphics so i have checked the documentation of qt using help
after getting some basic idea I started to put debug statement and the values where it is moving
I come to conclusion that there is some error in the spriteMovement while calculating the angel

I have tried to change the angle manually but due to logical error it was nt solveable
so I added some more debug statement and finally commented the calcDeltaMovement() and decided to give value based on the keypress event i am moving in right angle

bool poofTheEnemy (QGraphicsItem *potentialEnemy);
void addEnemies ();
UpDownLeftRightIum
all these I have checked using debugging but there was not problem


now you can see aThingyToMove is moving in the correct direction such as upwards and so on for other directions as expected in this mode


Ref:
https://doc.qt.io/qt-6/qgraphicsitem.html
https://doc.qt.io/qt-5/qpoint.html



