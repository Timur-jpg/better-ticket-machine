Project: better-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate conditional statements.
How to start this project: Create one or more TicketMachine objects.


Question 47: Unlike the previous machine the balance doesn't go back to 0 if I don't insert the right amount of money it keeps the money I putted in.
             I think the tickets will be free if I  enter the value zero as the parameter.
             
Question 48: I think the method will accept zero or any positive amount as valid input.
             Changing to amount "if(amount >= 0)" lets zero be accepted without error, but it doesn’t increase the balance.
             
Question 50: The boolean field controlled whether the circle was filled or not.
             Yes because it has only two states.

Question 51: The better-ticket-machine’s printTicket manages total and balance updates better than the naive version.

Question 52: Yes, I can remove it.
             It says "use a positive amount rather than: 0"
             
Question 53: No, the balance should never become negative because the method only prints tickets when the balance is at least the price.

Question 54: saving = price * discount;

Question 55: mean = total / count;

Question 58: String concatenation is easier

Question 59: Because this version resets balance before returning, so it always returns 0 instead of the original balance amount.

Question 60: The code does not compile
             A return statement stops the method, so code after it won't run and causes an error.
             
Question 61: The difference between the version are that the type in is added infront of the price and the value changed from 0 to cost.
             Yes, this version does compile.
             Yes, the price field remains 0
             I think it’s because the constructor makes a new price variable just inside itself, so maybe it doesn’t actually change the main price that the rest of the class uses. So the original price stays at 0.
 
Question 64: Add fields to hold discount info and a method to activate it to allow this kind of functionality.             
             

