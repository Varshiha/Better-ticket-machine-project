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

LETS START:
47.The balance does not change. For instance I had 450 in my blance  and I added -45, the error message popped up but the balance stayed 450. An error message will pop up which is what happened because the amount has to be more than 0 if not an error message will pop up.
48. The difference is that an error message does not pop up when I put 0 but it still does pop up if it is a negative number.
50. The feature was boolean isVisible so there are only two possible values(Visible or Not visible) which works for a type boolean since we can only do true or false.
51. The differences are that when we insert 40 cents but the price of the ticket is 30 cents, in the better ticket machine the balance would show 10 instead of 0 like in the naive one because it substracts the price from the balance. Also, in the naive ticket would still print the ticket even if there wasn't that much money. However, for the bettter ticket machine it will tell you how much money you are missing to be able to pay the ticket. 
52. The code does still compile but when I try to print the ticket without inserting money, the terminal does not even show up. 
53. It doesn't because of the body in the else. The balance stays and when you try to print a ticket it will tell you how many more cents you need. 
54. There is multiplication (*), division (/) and modulus (%).
55. int saving = price * discount;
56. int mean = total / count;
59. The difference is that when I click on refundBalance in the original version, the money I inserted which was 50 which was also my Balance showed 50 in the refundBalance. However, in the other version it showed 0 on my refundBalance. I am pretty sure it does not give the same results because in the code it is written so that when we click on refundBalance it will automatically change the balance to 0 and then return the balance whihc will be 0 too. 
60. It does not compile because the balance = 0 will be unreachable since the return statement is before. That is the return statement is always last because after that it will exit the method.
61. The difference is that by writing int price = cost we are declaring a new variable so it will keep its default value of 0 and not the one of cost since that is with other price variable. It did  compile. The price showed 0 and not 300 because the local variable (int price) does not affect the instance variable. 
64. I added a boolean field discountOn so that I would be able to put true or false. I created a method called activateDiscount so that we can click on it. I only changed the print ticket one so that I could the price of the discounted price by doing originalPrice / 2.




