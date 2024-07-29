NAME:: KOLACHANA VENKATA NAGA AKKSHAY SRINIDHI

COMPANY:: CODTECH IT SOLUTIONS

ID:: CT08DS4836

DOMAIN:: CYBER SECURITY AND ETHICAL HACKING

DURATION:: JULY TO AUGUST 2024

MENTOR:: MUZAMMIL AHMED 

OVERVIEW OF THE PROJECT

PROJECT:: PASSWORD STRENGTH CHECKER

OBJECTIVE:: Develop a tool to acess the strength of passwords entered by the user. Implement algorithms to analyse factors such a length,complexity,and uniqueness to provide feedback on password strength

KEY ACTIVITIES:: TO CHECK THE STRENGTH OF THE PASSWORD 
1) USING LENGTH
2) COMPLEXITY
3) UNIQUENESS
   
TECHNOLOGY USED AND CODE EXPLANATION::
1) HTML:: The HTML structure includes a <title> for the page, a <style> section for CSS, and a <script> section for the JavaScript code.
The body contains an  heading, an input field for the user to enter the password, and two div elements: one for the password strength bar and one for the password strength text.

3) CSS:The CSS styles the layout and appearance of the page, including the font, text alignment, input field, password strength bar, and password strength text.
The password strength bar is given a height of 20px and a width that will be dynamically updated by the JavaScript code.
The password strength text is given a margin-top of 10px and a bold font weight.

5) JavaScript:The calculatePasswordStrength function takes a password as input and calculates a score based on the length and complexity of the password.
The function checks the length of the password and assigns a score of 1 or 2 based on whether the password is at least 8 characters or 12 characters long, respectively.
The function then checks the complexity of the password by looking for the presence of uppercase letters, lowercase letters, numbers, and symbols. The score is assigned based on the number of these character types present.
The function does not include the uniqueness check.
The input event listener is attached to the password input field. Whenever the user types or changes the password, the calculatePasswordStrength function is called, and the password strength bar and text are updated accordingly.
The password strength bar's width is set to the percentage of the maximum score that the current password score represents.
The password strength text is updated to display "Weak password", "Medium password", or "Strong password" based on the calculated score.
