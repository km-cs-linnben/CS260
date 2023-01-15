# CS260
Assignment #1
Bag of Marbles

1.) Some way of representing marbles (what makes up a marble in this program?)
I am thinking in amatuer Python for all of these questions. First I would create a class called Marble.
I would initialize various properties such as diameter, color, weight, etc. Perhaps a menu to let users select these attributes.

2.) A way to add new marbles into the bag (how do we interact with marbles and add them into the bag?
I would create a list called bag_O_Marbles. Maybe another list called free_Marbles. I would have a menu/function that lets users create various marbles using the Marble class and assigning each created Marble a different variable name (ex: red_1inch_marble, blue_halfinch_marble).

3.) A way to remove a marble out of the bag (perhaps a random marble taken out of the bag?
I would have another function to add the created marble to the list bag_O_Marbles, and another to delete them from the list. Once deleted they would be added to the list free_marbles. I could import the random module and use that in a seperate function that would choose a random index in the bag_O_marbles list to be deleted.

4.) A few ways that we could use to show that our implementation should be working correctly (tests)

