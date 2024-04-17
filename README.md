# Tax Calculator

This Tax Calculator is a web application designed to help users calculate their income tax based on specified criteria. It allows users to input their gross annual income, extra income, deductions, and age to determine their tax liability according to a predefined formula.
# Hosted link
https://tax-calculator-two-blue.vercel.app/
# References & Requirements
- The tax calculation works based on this formula -
    - Overall income (after deductions) under 8 (≤) Lakhs is not taxed.
        - Ex - if Gross Annual Income + Extra Income - Deductions =  6 Lakhs, no tax
        - if Gross Annual Income + Extra Income - Deductions =  9 Lakhs, tax
    - Income over 8 (>) Lakhs, the amount over 8 Lakhs is taxed at
        - 30% for people with age < 40
        - 40% for people with age ≥ 40 but < 60
        - 10% for people with age ≥ 60
        - Example
            - Age = 34, Income = 40 Lakhs, no deductions, tax = .3 * (40 - 8) = .3 * 32 = 9.6 Lakhs
- Do not restrict user from entering incorrect values like characters in the number fields
    - Highlight a error icon to the right of the input field (shown as an example in above image as a circle with `!`). Hovering over it should show the error in a tooltip
    - If no errors are present, dont show the error icon
    - This should be present in all the number fields
- The age dropdown field should have 3 values -
    - <40
    - ≥ 40 & < 60
    - ≥ 60
    - If user has not entered this value and clicks on submit, show a error icon hovering over which should show that input field is mandatory
- Error icons should not be visible in the form by default.
- Clicking on submit should show a modal which would show the final values based on above calculations.

 ![image](https://github.com/pravesh2892/tax-calculator/assets/112716122/df66ad03-598a-4d04-87ac-392142dc8df2)

 # Usage
- Input the gross income, extra income, age group, and total deductions.
-Click the submit button to calculate the overall income and display the result.
-If any input is invalid, error messages will be shown to guide the user on how to correct the inputs.



