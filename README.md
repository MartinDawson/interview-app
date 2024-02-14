# 1
The app logo is messed up and not in the flow of the DOM, fix the position of the <img /> logo so that it is centered in the middle and apart of the flow of the DOM.

# 2
There's an input and a button in App.tsx, make it so that:

- The input is a controlled input which sets the value on change
- The button on click outputs a message to the user that says 'Clicked', the message should be
above the button.

# 3
Add validations on click of the button that verifies the following:

- The input value is less than 10 characters
- The input value is not empty
- The input value does not have any special characters, you can use this regex to do that: /[^\w\s]/;

# 4 
Write a test case for this new validation