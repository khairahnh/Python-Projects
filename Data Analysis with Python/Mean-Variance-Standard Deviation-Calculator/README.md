## Mini Project 1: Mean-Variance-Standard Deviation Calculator

### 1.0 Assignment
Create a function named `calculate()` in `mean_var_std.py` that uses Numpy to output the mean, variance, standard deviation, max, min, and sum of the rows, columns, and elements in a 3 x 3 matrix.

The input of the function should be a list containing 9 digits. The function should convert the list into a 3 x 3 Numpy array, and then return a dictionary containing the mean, variance, standard deviation, max, min, and sum along both axes and for the flattened matrix.

The returned dictionary should follow this format:

![Screenshot 2022-09-30 at 9 08 53 PM](https://user-images.githubusercontent.com/100784629/193321497-d04c990d-62bd-45f3-9fe3-3cea1b9c65c5.png)

If a list containing less than 9 elements is passed into the function, it should raise a ValueError exception with the message: "List must contain nine numbers." The values in the returned dictionary should be lists and not Numpy arrays.

For example, `calculate([0,1,2,3,4,5,6,7,8])` should return:

![Screenshot 2022-10-01 at 1 12 37 AM](https://user-images.githubusercontent.com/100784629/193321568-42f7ba2c-7a16-403c-b374-d6041c0b44a8.png)

The unit tests for this project are in `test_module.py`.

### 1.1 Development
For development, you can use main.py to test your calculate() function. Click the "run" button and main.py will run.

### 1.2 Testing
We imported the tests from test_module.py to main.py for your convenience. The tests will run automatically whenever you hit the "run" button.

### 1.3 My thoughts
Since this is the first mini project from FreeCodeCamp, I found it hard to really understand the assignment and came out with the codes. You can see my codes. It's messy but readable. 😵
Definitely need to do more projects so that I get to familiar with Numpy. 
