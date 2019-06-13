   


#Logic:

The parking calculator lets you know how much you need to pay for parking depending on the lot you choose. The math seems to break when you input a number >24 for entry or leaving time, and when you input a number for entry date less than the leaving date. Also, the lot switches back to “short-term parking” everytime you display the results.

The math logic works properly for each lot when the time and date are entered correctly in every scenario.

There should be some input format restrictions to avoid the user from entering a non-realistic time or date.

#Bugs/Need to fix:

- label: it should be “choose entry time and date”, it makes more sense since that's the visual order.


- entry/leaving time box: this input seems to take all numbers but it should take time format only, or only accept numbers <12 (<24 might be redundant since we have “am or pm” to choose as well). Same thing applies to the “leaving time box”. 

- entry/leaving date box:: though the user can select a date from the popup and display it in a date format, the logic will work as long as the “entry date” is less (<) than the “leaving date”, maybe another “time input format restriction” could work too.

- results page: every time you hit calculate, the results page will do the math according to the lot you chose, but will always display “short-term parking” when page reloads with the result.


- entry and leaving dates: these do not seem to matter for the math to work or not on any scenario as long as the input of “entry date” is less than the input “leaving date”.



