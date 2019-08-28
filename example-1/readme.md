# Islands example

In this example each "experiment" consists of 20 numbers which are either 0 or 1. If in these 20 numbers the 1's are altogether forming "islands", with no zeros in between, and there is only one "island" of 1's, then we say that the experiment is "positive". Therefore, in the `Learn_card`, the column 21st has a "1" when it is a positive row, and a "0" when it is a non-positive row.  

Observe that this last digit ("1" or "0") is only to say if the row is positive or not, and has nothing to do with the "islands" of 1's.

The LearnCard has therefore 21 columns, whereas the InCard has only 20 columns.  The last column of the InCard is the one that the Neural Network should say if it is either a "1" or a "0" according to how well it learns to recognize the aforementioned patterns.
