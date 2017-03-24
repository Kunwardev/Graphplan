In the file hanoi_facts1.txt and hanoi_facts2.txt, All the constants are defined
with the class Object. In the preconds the initial state is represented, but an
additional condition is also added, that will ensure that the peg A, B, C do not
move and the bigger disk does not rest on the top of the smaller disk.
A smaller instance is initialized which is smaller(disk1 C) which is read as
C is smaller than disk1.
In the file hanoi_ops.txt, move operator is initialized that takes 3 arguments
that verifies the precondition that the disk to be moved is smaller than 
the disk on which it is going, and then remove the disk from the previous peg.
