The naming of the file is incorrect, such things can be changed on github itself. Also, you seem to have changed the structure of the code itself by taking w as a class variable. 
I'll be giving comments on the basis of the updated structure, but in the future try to stick to the structure of the code given since some of the testing makes sense only for that structure.

In the class Tester, there are following issues in the functions: 

1. def iterative_mult(w) :
* M needs to be accessed using self.M, similarly w needs to be accessed using sel

2. def matrix_mult(w) :
* Looks good

3. def comparison(w) :
* Looks good

4. Plotting
* Looks good

As a sidenote, it's a good practice to write comments wherever required.
