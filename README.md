# Android Studio Continued Lab

## Objective: 
In this lab, you will continue to explore and implement the capabilities of Android Studio and getting used to it as a work enviroment!  

By the end of this lab, you will have Signin & Signup pages with a Home page with the possibilty of logging out.  

## Instructions:

In this lab, we'll be making well designed pages with the possibilty to move between activities and implementing option menus!  

1. Designing the views of the **MainActivity**:
    - Give the `EditText` a **rounded border** around the input. (Google how!)
    - Give the `Buttons` **rounded corners** and **change their color**.

2. **SignUpActivity**:
    - Create a new Activity called `SignUpActivity` (Empty Activity), the Activity should contain:
        1. A `TextView` that says: "Sign Up".
        2. Three `EditTexts`: Name, Email & Password.
        3. A submit `Button`.
    - When the submit button in the MainActivity is clicked:
        - Go to the SignUpActivity.

3. **HomeActivity & Menu**:
      1. Create a new Activity called `HomeActivity` (Empty Activity), the Activity should contain:
        - A `TextView` that says: "Welcome to our App!".
      2. Create a menu directory, then a menu file:
        - Add an `Item` with the text: "SignOut".
      3. **Inflate** the menu to `HomeActivity`.
      4. **Implement** `onOptionItemSelected` function:
        - When SignOut is pressed, return to the `MainActivity`.


##### Call an Instructor/TA to check your completed tasks

### Bonus:

1. When you go to `HomeActivity`, send the email of the user as a **variable** and **display** it in `HomeActivity`.
 
###### make sure you commit and push your code.
