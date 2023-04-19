# Lab-8_202001085

# Unit Testing with JUnit

#Lab Exercises :

1. Created a new Eclipse project name Lab8, the Package name Junit and class name Boa .


2. Create a class for a Boa. Here’s the code you can use (you may copy/paste):

![image](https://user-images.githubusercontent.com/107172109/233026943-b3c686fc-5c1f-4467-91ee-f2335e2779ed.png)

3. Follow the instructions in the JUnit tutorial in the section “Creating a JUnit Test Case in
Eclipse”. You’ll be creating a test case for the class Boa. When you’re asked to select
test method stubs, select both isHealthy() and fitsInCage(int).

4. Now it’s time to write some unit tests. Notice that the BoaTest class that JUnit created
for you contains stubs for several methods. The first stub (for the method setUp()) is
annotated with @Before. The @Before annotation denotes that the method setUp()
will be run prior to the execution of each test method. setUp() is typically used to
initialize data needed by each test. Modify the setUp() method so that it creates a
couple of Boa objects, as follows:

add UnitTest cases : 

![image](https://user-images.githubusercontent.com/107172109/233033361-e3e2f24a-4742-4cf3-8d9c-98a3eb799c9d.png)

5.JUnit also provided stubs for two test methods, each annotated with @Test. Work on
the testIsHealthy() method first. The purpose of this method is to check that the
isHealthy() method in the Boa class behaves the way it’s supposed to. In the JUnit
tutorial, read the section on “Writing Tests”. Modify the testIsHealthy() method so that
it checks the results of activating the isHealthy() method on the two Boa objects you
created in setup().

Likewise, modify the testFitsInCage() method to test the results of that method. Make
sure your test is robust; it should check the results when the cage length is less than the
length of the boa, when the cage length is equal to the length of the boa, and when the
cage length is greater than the length of the boa. Should you write tests for both jen
and ken?

added private field jen and ken.

![image](https://user-images.githubusercontent.com/107172109/233043166-275949f9-0d18-4ce3-8348-bb1cc5a49a86.png)


6. Now you can run your tests. Read the section “Running Your Test Case” in the tutorial.
Did you get a green bar in the JUnit pane? If you got a red bar, use the output in the
JUnit pane to determine which test(s) failed. Fix your tests, and try running the test
case again.

It’s important to note that a red bar doesn’t necessarily mean that the test case is
written incorrectly; it could be that the method that’s being tested isn’t correct. In fact,
that’s what unit testing is supposed to do – help us find errors in our code. When a test
fails, you need to determine if the error is in the test case itself or in the code it’s
testing.

adding test cases

![image](https://user-images.githubusercontent.com/107172109/233034754-fb27289f-dcb1-4a91-9d2e-2e46cef042bf.png)

7.Running the test cases

![image](https://user-images.githubusercontent.com/107172109/233047663-d56d9c6e-ef27-4d27-a2f7-2cd39e2d09f6.png)


8. Adding new method to the Boa class, with this purpose and signature:

![image](https://user-images.githubusercontent.com/107172109/233040010-a0e0f591-ee05-4f30-81e8-1db9fcb30195.png)

9.Adding the new test cases for the new method -

![image](https://user-images.githubusercontent.com/107172109/233048125-a5dfdef6-37b6-49a5-9fc6-f23bb20b2295.png)

10.After running all the test cases after adding the new method -

![image](https://user-images.githubusercontent.com/107172109/233048049-61a9dddc-26f9-4ced-b40f-fa27f970ac65.png)




