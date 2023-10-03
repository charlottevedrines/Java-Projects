# Java-Project

## Project name: Polynomial local minimizer
This project finds the local minimum of a polynomial function of order n using steepest gradient descent using Java. 
<img width="627" alt="Screenshot 2023-07-14 at 15 01 48" src="https://github.com/charlottevedrines/Java-Projects/assets/97196465/69a70c25-15b0-4ed9-a34c-556495135403">


Steepest descent is a special case of gradient descent where the step length is chosen to minimize the objective function value. The step size chosen will significantly impact the perform of the algorithm. Therefore, this project will utilize three different methods to calculate the step size:
- Fixed step size
- Armijo line search
- Golden section search
  
Finally, each algorithm will be evaluated based on the three metrics: norm of the gradient, number of iterations needed and computation time needed to determine the best performer in each category and the overall best performer.

### Running the code
You can use this algorithm to minimize any polynomial function(s) you would like. Enter a grid of coefficients of the polynomial function(s) you would like minimized in a .txt file. The number of columns in your coefficient grid represent the order of your polynomial function, the rows the number of terms and of stars the number of functions. Use demo.txt in this repo as an example. 
Enter the option 'L' followed by the name of your .txt file to input your desired polynomial function(s).

# Citations 
This project was given as an assignment in Professor Aleman's class at the University of Toronto.

The image was taken from the website [calcworkshop](https://calcworkshop.com/partial-derivatives/extrema-multivariable-functions/)

