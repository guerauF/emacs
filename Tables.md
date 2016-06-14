Learning the functionality of emacs always starts with a problem, and how to deal with it using emacs. 

Here are some examples:

# Column paste next to another

1. Set the mark. You have to imagine you are delimiting a rectangle. So if the last word of the column you want to paste
is shorter than another word from the same column, add spaces to limit the area. If you do not do so, longer words will be cut.

2. Ctrl x r k # kill the rectangle

3. Go where you want to place the new column and Ctrl x r y # paste the killed rectangle

# Sort column

Ctrl c ^

A menu pops up, where you have to specify if alphabetic, numeric or time.
Uppercase letters specify in reverse order.

# Multiple cursors

# Columns with specific decimal positions
