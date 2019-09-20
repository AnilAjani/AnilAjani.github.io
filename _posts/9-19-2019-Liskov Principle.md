The way I understand what the Liskov principle is that parent and child class cannot have conflicting methods, for example:

Using rectangle/square - if the parent class (rectangle) has a set height and width not equal to eachother.

The child class (square) will also have set height and width not equal to eachother.

But if square were to make its height and width equal, as it should be for a square, it will conflict with the set height and width in the parent class.

Therefore, expecting a rectangle but getting a square.
