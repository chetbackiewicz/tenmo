# tenmo
Tenmo is venmo-style application which allows users to send and request money using a client side application, storing values in a postgres database.
The user registers, and is added to the database.  They start with 1000 dollars, and can view the available users.  After picking the user
by user id, they can send an amount of money less than their current amount, and it must be a positive amount.  
They can also send requests for money, which a user can see in the "pending requests".  The user with pending requests can do nothing with them, 
approve, in which case the money will be taken from their account and added to the requester's account, or the requests can be deleted, 
which removes it from their pending requests without doing anything to their account balance.
Java, Postgresql
