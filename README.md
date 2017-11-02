# RodRego
Code for RodRego Register Machine

Simulater available here: [http://proto.atech.tufts.edu/RodRego/](http://proto.atech.tufts.edu/RodRego/)
Details here:[https://sites.tufts.edu/rodrego/](https://sites.tufts.edu/rodrego/)

Basically this machine has three commands which can be combined to perform computations.

> N END

Ends the program if line N is run

> N INC R X

Increments the contents of register R, then calls line X. This is called when another line calls line N.

> N DEB R X Y

Decrements the contents of register R, then calls line X. If R is empty, it calls line Y.

DEB can be used to create a while loop. 
