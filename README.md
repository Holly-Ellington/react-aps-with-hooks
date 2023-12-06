# react-APIs-with-hooks

Thinkful bootcamp assigment 7.4 React and APIs with Hooks
React album app
Requirements
Your task is to build a React app to view the albums owned by users.

It should contain a list of users on the left.
On the right it should have a list of albums owned by the selected user.
As you click through the users, the list of albums should change.
Here is an example of what it might look like with no user selected.

When a user is selected, display the albums for that user:

Specific instructions
Load users from https://jsonplaceholder.typicode.com/users.
Load albums from https://jsonplaceholder.typicode.com/albums?userId=${user.id}.
Create additional components that are then used by the App component.
Style the components using inline styling and/or CSS files. It does not need to match the appearance of the example image, but should have a reasonable layout.
The document title should be "Awesome Album App" and should reset to the original document title when the component is cleaned up. You can get the original title by accessing document.title and storing that value.
Pending API calls should be canceled when the user changes.
State should be "lifted up" whenever possible.
Do not make any assumptions about the number of users or number of albums owned by the user.
If no user is selected, the right side should display "Please click on a user name to the left"
List of albums should include the album ID and the album title
Note: When running the tests, you might see messages like Warning: An update to %s inside a test was not wrapped in act(...). These can be ignored and will go away once the test is passing.

Success criteria
Functionality:
Document title is set to "Awesome Album App"
Document title is reset to original title on cleanup
List of user names is displayed
Clicking the user name displays a list of albums owned by the user
Pending API calls are canceled when a new user is selected. Make use of the AbortController and handle abort errors accordingly.
Hints for AlbumList.js
We suggest that you only try using the hints to compare your work. Try working on your solution and use the hints to compare it with your work. Only use the hints if you feel stuck.

First of all, make sure you import useEffect and useState.
