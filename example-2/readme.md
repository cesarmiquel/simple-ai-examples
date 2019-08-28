# Examples

In this example each "experiment" consists of 20 numbers which are either always increasing from left to right, or not. In the case that the numbers are always increasing we say that the row correspond to a "positive" row and we put a "1" as a last digit in the column 21st.  On the contrary, if at any column there is a number smaller or equal on the right of a given number, then we say that the row is non-positive, and we put a "0" in the column 21st.

The LearnCard has therefore 21 columns, whereas the InCard has only 20 columns.  The last column of the InCard is the one that the Neural Network should say if it is either a "1" or a "0" according to how well it learns to recognize the aforementioned patterns.
