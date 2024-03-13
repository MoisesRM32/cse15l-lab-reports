#*Edstem Post
![Image](symptoms1.png)
![Image](s.png)
![Image](symptoms3.png)
My code is not working for both my multiply and addition functions. In the addition test, it tests the addition of the numbers `[2]` and `[3]` expecting `[5]` but instead got `[6]`. As for my multiplication test I tested numbers `[2]` and `[3]` expecting `[6]` but instead got `[5]`. My guess for these tests failing is because of bad implementation of my calculator methods for addition and multiplication. I am confused please help me.


#Response from TA "Jonsey Fortnite"
You should review your addition method and multiply methods as there may be some confusion on how you implemented your methods, also check if tester methods are missing an arguement in your assertions. Because you are working with doubles your testers. Search up what a delta delta is for floating point numbers.

![Image](float.png)


This is when I fixed the issue in both methods add and multiplication and ran it only to fail to the floating point error.


![Image](passedtests.png)


This is after I added a delta to both tests passing the tests. So to fix the bugs in my code was changed the method titles of add and multiply in `SimpleCalculator.java`. Then in `SimpleCalculatorTester.java` I added deltas to the asserts in my tests.

#Structure
![Image](1.png)

#The code before the changes
![Image](2.png)
![Image](2pt.png)

#Command line to run the bug
![Image](3.png)

#How to change the bug 
You have to switch the addition and multiplication in `SimpleCalculator.java` and then you have to add deltas to the asserts in `SimpleCalculatorTester.java`.


Learning about scripting was very interesting to learn about as I could be able to use it to rapidly test my code without having to manually retype it in the terminal. Also allowing me to create and delete new files from the script able to automate my code to run and test itself which could prove to be very helpful. Something cool that I learned was learning vim, although it may prove difficult to use sometimes, maybe I will become better at vim over time. :)



