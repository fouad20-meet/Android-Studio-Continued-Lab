# Android Studio Continued Lab

## Objective: 
In this lab, you will learn to implement the essentials of Android Studio and working with Java & XML!  

By the end of this lab, you will have a template of a signin page.  

## Instructions:

In this lab, we'll be creating a sign in page using TextView, EditText & Button!  

1. Create and set up a new `Android Studio` project:
    - Go to new -> new project -> Empty Activity.
    - Make sure your code is in **Java**.

2. In your XML file:
    1. Change the layout to `LinearLayout`.
          - Don't forget the LinearLayout attributes.
          - Center all the objects within the layout.
    2. Add:
          - A `TextView` that says SignIn.
          - Two `EditTexts` for email & password, **hint:** Don't forget the difference between hint and text.
          - Two `Buttons` one says signin and the other signup.
              - Organize the buttons to be next to each, **hint: LinearLayout & weight**.
          - **Don't forget to add ids**
    3. Use margins to improve the appearance of the page. 

3. In your Java file:
      1. Connect the views from the `XML file` to the `Java file`.
      2. Set an `onclick listener` for both button:
        - When the signin `Button` is clicked:
            - Set the text of the EditTexts to be the email of the user.
        - When the signup `Button` is clicked:
            - Using Toast, display "Signup is under construction" as a message.


##### Call an Instructor/TA to check your completed tasks

### Bonus:

1. Perform the function of the signin button only if:
    - The email contains "@" & ".com"
    - The password is 6 characters long.
 
###### make sure you commit and push your code.
