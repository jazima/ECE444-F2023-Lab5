# Flaskr TDD

# Unit tests for team project
Please see unit tests implemented at the following link:
https://github.com/ECE444-2023Fall/project-1-web-application-design-group2-t3/blob/tests/flask-api/app_test.py/#L36-L44

# Pros and Cons of TDD
Test-driven development (TDD) is a software development process in which the developer first write the tests for for some function, and then works on writing the code for that function in order to pass the defined test. The idea is that in writing the test, the developer lays out the requirements for the function and in doing so is better able to understand what the function needs to do. It also ensures that the code written is verified based on the requirements of the test.

One of the pros of TDD is that it helps to define the requirements of software before it is written. Having clear and well-defined requirements helps in writing high quality and bug free code. In writing the test, the developer would consider several cases for its functionality and then in development can properly handle all of the considered cases. Another pro of TDD is that It leads to modular and maintainable code. Since all code is written in testable blocks, it helps define the scope of that set of code, helping it be more modular. The expandability of the test code also helps in maintenance in case of errors in th future. A third pro of TDD is that it helps with collaboration. The tests for the new changes are a good way for a collaborator to understand the goal and scope of that code. This helps with understandability of the requirements that the test writer had in mind for that code. Overall TDD ensures that any code written passes its predefined test, catching bugs earlier it the development process and acting as a sanity check for the developer.

Every development practice tends to come with both pros and cons and TDD is no different. Writing tests for every component of the software can be very time consuming, especially in the beginning when the developer has to write the tests without having any code for reference. Often, one gets a better understanding of what functionality the code or function should have as its being written. This means that the developer would have to go back and update the test code throughout the development of the code, adding a lot of extra work. Additionally, it can lead to an over reliance on the tests in verifying the functionality of the code. Sometimes, the tests do not, and cannot, cover all the test cases. When this is the case, the written tests are not comprehensive and do not properly verify the functionality of the code, but if the written code passes its corresponding test, this may lead to a false sense of verification. Finally, TDD is not suitable for many types of software. For example, it is not feasible to completely test the usability of a web frontend with written tests. This would require dedicated user testing for qualitative assessments.
