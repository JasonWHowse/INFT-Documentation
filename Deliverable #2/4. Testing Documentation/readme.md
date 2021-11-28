4. Testing Documentation
You need to have a plan for thoroughly testing your software that should include a combination of black-box and white-box tests. Beta testing is not required, although if you have the time and resources, it would probably be a good idea. Your test plan and your test cases should be documented thoroughly. It is vital to maintain a detailed record of every test (inputs, expected outputs, rationale) you perform, since you will need to be able to rerun these tests when you make changes to the software (regression testing). Testing will probably be the least glamorous and most tedious part of the entire project, but it is absolutely vital to ensure the software you build is meets its specification (i.e., it is verified), and is valid (i.e., it meets the customer’s expectations).
You should indicate traceability of requirements (for black-box testing) and of source code (for white-box testing) for each test case. An example test case is shown below:
Test Case #
Requirement Tested
Rationale
Input(s)
Expected Output
Pass/Fail
105
2.1.0
User should be allowed to play 5 card draw poker
User selects “5 card draw” when prompted for game variant to play
5 card draw layout is displayed
PASS
Note that you can design many of your black-box test cases concurrently as you flesh out the requirements. For example, if one of your requirements states that the software must be able to open a Microsoft Word document, you can design black-box test cases using a series of different Word documents as input. Obviously, white-box test cases cannot be designed until there is code to test, but you can design white-box test cases as the code becomes available.