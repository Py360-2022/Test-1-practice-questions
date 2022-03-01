# Instructions  

  ** these are practice questions for test 1 **

  _ note that any previous exercises would also be practice too _

  ## Note
  * Lists will not be on the test
  * You will be using repl.it for the exam, (not moodle as previously stated)
  *   Some of the questions below are longer than the test will be! The difficulty of questions should give you an idea of what to expect, but the test will not be this long.
  ## Steps
  1.  In creating an application for a bank, we want to create a login system. This system should ask for a username and password. If the user enters the password 'P@55w0rD', you should print the message 'Access granted', and welcome the user by the name they entered. 
    * If the user enters anything else, you should simply print access denied.
    * Do this in a function called `login` that takes no parameters returns true if the login is successful, false otherwise.
      
  3. Write a piece of code that will evaluate a service charge for cashing a cheque, where the service charge depends on the amount of the cheque. 
    *	if the cheque value < 10, charge $1
    *	if greater than or equal to 10 but less than 100, charge 10% of the cheque value
    *	if greater than or equal to 100 but less than 1000, charge $5 plus 5% of the cheque value
    *	if over 1000, charge 40 plus 1%

  NOTE: Use else-if statements efficiently!!!

  Do this in a function called `cash_cheque` which takes as a parameter the amount of the cheque, and returns that total service charge for cashing the cheque.  Service charge does not include the cheque amount.

  3. To allow multiple login attempts, create a function called `multiple_login`. This function should call login 5 times using a loop. If any of the 5 logins are successful, this function should return true. If all 5 logins fail, this function should return false.
5. Write a piece of code that will determine the number of times the substring _bank_ occurs in a string.
  
  Hint: use your own index (0 to ...) & a counter
  
  Do this in a  function called `find_bank` take a string as a parameter and returns the count of occurrences 

  4. To allow cashing multiple cheques, create a function called `multiple_cheque`. This function should ask the user how many cheques they would like to deposit. Then, using a loop, you should repeatedly ask the user the value of each of these cheques, call the `cash_cheque` function, and then accumulate (add up) the service charges. Finally, print out the total service charges at the end.