# JavaScript Essential Assessment 2

## Project Instruction
A simple web page with appropriate styling, an embedded script, and a document containing test cases and a summary of two possible cyber security risks.

## The web page: 
- Create a simple webpage using HTML and CSS
- web page must contain the heading “Infected Presence Increase Calculation”.
- Include an area to receive the data output from the script 
- Must include script tags in the main body. Do not an external script.
- DO NOT use form fields in the HTML file to receive data form the user

## Required attributes
- You will need five global variable:
    - <b>infected</b> (int): user should be <b>prompted</b> to enter the number of <b>zombies</b> currently in the area. Value must be converted into a number.
    - <b>incoming</b> (int): user should be <b>prompted</b> to enter the number of <b>infected</b> that have appeared in the area in the last month.
    - <b>currentMonth</b>: initialise to a value of 1.
    - <b>totalMonths</b>: initialise to a value of 12.
    - <b>output</b>: this variable will store the HTML tag that will receive the output.

## The script:
- Create <b>one</b> while loop. The while loop:
    - Calculates an increase in the number of infected in a given area over a period of 12 months.
    - It assumes that the number of <b>infected</b> entering the area will remain the same for each month.
    - Receive the number of <b>infected</b> currently in the area and add the number of <b>incoming</b> infected.
    - Reassign the new value back to the <b>infected</b> variable
    - Display "There will be x infected in the area after y month(s)".
        - x being the value of infected.
        - y being the value of currentMonth.
    - There should be 12 lines of text.
    - Must test that the value of <strong>currentMonth</strong> does not exceed the value of <strong>totalMonths</strong>
