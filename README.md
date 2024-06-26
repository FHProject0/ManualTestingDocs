# ManualTestingDocs

1. Functional Testing

Objective: To verify that the software functions according to the specified requirements.

Example:

	•	Test Case ID: FT-001
	•	Title: Verify login functionality with valid credentials.
	•	Preconditions: User is on the login page.
	•	Test Steps:
	1.	Enter valid username.
	2.	Enter valid password.
	3.	Click on the ‘Login’ button.
	•	Expected Result: User is successfully logged in and redirected to the homepage.

2. Integration Testing

Objective: To ensure that integrated components work together as expected.

Example:

	•	Test Case ID: IT-001
	•	Title: Verify data flow between the login module and the user profile module.
	•	Preconditions: User is on the login page.
	•	Test Steps:
	1.	Enter valid login credentials and log in.
	2.	Navigate to the ‘Profile’ page.
	•	Expected Result: User profile information is displayed correctly based on the login credentials.

3. System Testing

Objective: To validate the complete and fully integrated software product.

Example:

	•	Test Case ID: ST-001
	•	Title: Verify that the e-commerce application allows users to place an order successfully.
	•	Preconditions: User is logged in.
	•	Test Steps:
	1.	Add items to the cart.
	2.	Proceed to checkout.
	3.	Enter shipping details.
	4.	Select payment method.
	5.	Confirm the order.
	•	Expected Result: Order is placed successfully, and an order confirmation email is sent to the user.

4. Regression Testing

Objective: To ensure that recent code changes have not adversely affected existing functionalities.

Example:

	•	Test Case ID: RT-001
	•	Title: Verify that the login functionality works after recent updates to the authentication module.
	•	Preconditions: Recent updates have been deployed.
	•	Test Steps:
	1.	Enter valid username.
	2.	Enter valid password.
	3.	Click on the ‘Login’ button.
	•	Expected Result: User is successfully logged in and redirected to the homepage.

5. User Acceptance Testing (UAT)

Objective: To validate that the software meets user requirements and is ready for production.

Example:

	•	Test Case ID: UAT-001
	•	Title: Verify that users can successfully register for a new account.
	•	Preconditions: User is on the registration page.
	•	Test Steps:
	1.	Enter valid details in the registration form.
	2.	Submit the registration form.
	•	Expected Result: User receives a registration confirmation email and can log in with the new credentials.

6. Performance Testing

Objective: To assess the speed, responsiveness, and stability of the software under a particular workload.

Example:

	•	Test Case ID: PT-001
	•	Title: Verify the load time of the homepage under peak traffic conditions.
	•	Preconditions: The application server is running.
	•	Test Steps:
	1.	Simulate 1000 concurrent users accessing the homepage.
	•	Expected Result: The homepage loads within 3 seconds for all users.

7. Security Testing

Objective: To identify vulnerabilities and ensure that the software is protected against potential threats.

Example:

	•	Test Case ID: ST-002
	•	Title: Verify that the application is protected against SQL injection attacks.
	•	Preconditions: User is on the login page.
	•	Test Steps:
	1.	Enter "' OR '1'='1" in the username field.
	2.	Enter "' OR '1'='1" in the password field.
	3.	Click on the ‘Login’ button.
	•	Expected Result: Login attempt fails, and an error message is displayed.

8. Usability Testing

Objective: To evaluate the user interface and user experience aspects of the software.

Example:

	•	Test Case ID: UT-001
	•	Title: Verify the intuitiveness of the navigation menu.
	•	Preconditions: User is on the homepage.
	•	Test Steps:
	1.	Click on each menu item.
	•	Expected Result: User can navigate to different sections of the website easily without confusion.

9. Compatibility Testing

Objective: To ensure the software works across different devices, browsers, and operating systems.

Example:

	•	Test Case ID: CT-001
	•	Title: Verify the application’s functionality on different browsers.
	•	Preconditions: Application is deployed.
	•	Test Steps:
	1.	Open the application in Chrome.
	2.	Open the application in Firefox.
	3.	Open the application in Safari.
	4.	Open the application in Edge.
	•	Expected Result: The application functions correctly and displays consistently across all tested browsers.

10. Exploratory Testing

Objective: To discover defects and issues by exploring the software without predefined test cases.

Example:

	•	Test Case ID: ET-001
	•	Title: Explore the settings page for any anomalies.
	•	Preconditions: User is logged in.
	•	Test Steps:
	1.	Navigate to the settings page.
	2.	Interact with various settings options.
	3.	Note any unusual behavior or issues.
	•	Expected Result: All settings work correctly, and there are no unexpected behaviors.

These examples cover a range of manual testing scenarios to ensure thorough testing of a software application.
