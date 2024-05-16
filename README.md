# IPRG-Ice-Task-3
IPRG Ice Task 3
Pseudocode:
BEGIN
    DISPLAY "Welcome to Sammy’s Seashore Supplies"
    PROMPT "Enter the number of minutes you rented the equipment: "
    READ rentalMinutes

    SET hours = rentalMinutes DIV 60
    SET additionalMinutes = rentalMinutes MOD 60
    SET totalCost = (hours * 400) + additionalMinutes

    DISPLAY "Sammy’s Seashore Supplies"
    DISPLAY "Hours Rented: ", hours
    DISPLAY "Additional Minutes: ", additionalMinutes
    DISPLAY "Total Price: R", totalCost
END
Flowchart:
Start.
Display “Welcome to Sammy’s Seashore Supplies”.
Prompt for the number of minutes rented.
Input the number of minutes.
Calculate hours as rentalMinutes DIV 60.
Calculate additional minutes as rentalMinutes MOD 60.
Calculate total cost as (hours * 400) + additionalMinutes.
Display “Sammy’s Seashore Supplies”.
Display “Hours Rented:” followed by the hours calculated.
Display “Additional Minutes:” followed by the additional minutes calculated.
Display “Total Price: R” followed by the total cost calculated.
End.
