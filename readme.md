The test case is a set of conditions that determines if the application or one of its modules is behaving as expected. You can write multiple test cases in a single module. Test cases are executed in alphabetically ascending order of test case names.



Actions
These are the actions we use to write our test cases. The following are the definitions and a few examples of when each action would be used.

Wait For
• This action is for Android, iOS, and Web.
• This action will delay the test case for a specified amount of time (in seconds) or until a certain condition is met before continuing to the next step.

Tap on
• This action is for Android, iOS, and Web.
• This action is used to Click on any element. We can also specify the number of taps and the number of touches to perform.

Check
• This action is for Android, iOS, and Web.
• We can specify assertions using the Check action. It can “Check” if a specified condition is true. The check action will also “Check” the value of any element.

Start If, Start Else, End If
• This action is for Android, iOS, and Web.
• This action works as a conditional IF and Else statement like in any other programming language. We can check if the element is visible before we perform the “tap on” action on it.

Scroll to
• This action is for Android, iOS, and Web.
• This action is used to scroll the screen until the element is at the top of the screen.

Swipe
• This action is for Android, iOS, and Web.
• This action is used to perform a directional swipe gesture. We can specify any of the four directions, and the swipe will happen in the middle of the screen.  We can also specify the container that we wish to swipe in.

Type In
• This action is for Android, iOS, and Web.
• This action is used to type text in the text fields. The auto-hide keyboard feature can be set to true or false.

Type Encrypted
• This action is only for Mobile.
• This action is used to type text in the text fields with encrypted format. The auto-hide keyboard feature can be set to true or false.
 
Variable
• This action is for Android, iOS, and Web.
• This Action is used to declare a variable. We can also specify its datatype (String, integer or JSON)

Save to Variable
• This action is for Android, iOS, and Web.
• This action is used to assign value to the already declared variable.

Repeat If,  End Repeat
• This action is for Android, iOS, and Web.
• This action performs a repetitive action based on the condition set by the user.

Comment
• This action is for Android, iOS, and Web.
• This action has no effect on the test case running. Commenting is used as a way to make notes for the user.

Call Test Functions
• This action is for Android, iOS, and Web.
• This action calls a declared test function.

Call Network Assert
• This action is for Android, iOS, and Web.
• This action calls the network assert test case inside the UI test case.
  
Clear Network Log
• This action is for Android, iOS, and Web.
• This action ignores the network calls that were made prior to this step in the network assert test case.

Print Log
• This action is for Android, iOS, and Web.
• This action will print the parameter you give it in the detailed log (ie: Typing “Hello World” will print “Hello World” in the detailed logs)

Increase
• This action is for Android, iOS, and Web.
• This action increases the value of an integer variable.

Select
• This action is for Android, iOS, and Web.
• This action is used to select text from a single element or multiple element list with text and index.

Hover
• This action is only for Web.
• This action is used to hover an element.

Write to CSV File
• This action is only for Web.
• This action is used to write text in CSV. You can use select action or element or the text.

Declare
• This action is for Android, iOS, and Web.
• This action is used to declare elements while writing test cases.

Take Full Screenshot
• This action is only for Web.
• This action allows you to take a full screenshot.

Press Key
• This action is only for Web.
• This action allows you to use the keyboard keys to press.

Pull Down To Refresh 
• This action is for Android, iOS.
• This action can do a pull to refresh by swiping down from mid of screen to bottom of the screen with using specific element.

Check Ad with Id 
• This action is for Android, iOS.
• This action can do check any ad with ID using element.
 
 
 
Test Functions
• Test Function is a set of commands that performs a specific action. You can create a Test Function of any repetitive actions.
• Click on “Add Test Function” button
• If you have the same scenario in many test cases then you can create one function for that and use it in every test case.
• Add a Test Function Name and Description.
• Add steps.
• Click on Update button.


Use Test Function In TestCase
• Open your test case.
• Select the Call Test Function.
• Now, you can see your test functions in the right field and select the function from the drop-down list.
