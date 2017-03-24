In the file 7puzzle_facts1.txt and 7puzzle_facts2.txt, the tiles are defined
and the locations are defined. The initial state are defined in the preconds,
along with the additional instances that verify that the correct tile is passed
and the location passed is also valid. The tileAt instance tells that which tile
is at the specified location.
In the file 7puzzle_ops.txt, we applied four functions that are moveleft, moveright,
moveup and movedown. I have assumed the grid to be in a straight line, and for left,
right I incremented and decremented according to the empty space, and for up, down 
I incremented and decremented by a factor of 3 according to the empty space.
The Visual description is 
			1 2 3
			4 5 6   -----> 1 2 3 4 5 6 7 X X 
			7 X X

			Move Up
			1 2 3 
			4 5 X   -----> 1 2 3 4 5 X 7 X 6  (6's position incremented by 3)
			7 X 6
			
			Move Left
			1 2 3
			4 X 5   -----> 1 2 3 4 X 5 7 X 6  (5's position incremented by 1)
			7 X 6