# my_first_redux_with_react
This is my first attempt to use redux for React.
I am following along the tutorial by Stephen Grider and using his Redux starter code 'ReduxSimpleStarter'.

18 May 2016 - I get this error in the browser console:
bundle.js:21412 Uncaught Error: Cannot find module "../containers/book-list"
Solved the issue.  It was just typo in book-list.js file.

18 May 2016 - I get another similar error in my browser console:
bundle.js:21654 Uncaught Error: Cannot find module "./reducer_active_book"
I cannot find typo..
18 May 2016 - The problem solved, it was just another typo. corrected stwich to switch.  Also, activeBook, ActiveBook letter case was corrected. It works now.