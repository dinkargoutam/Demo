* Create the following structure
* __Person__ has name and a array of cities visited
* __City__ has a name, and a country
* Every City belongs to a __Country__
* __Country__ has a name and capital and population

* __Person__ has another Person as a friend
* Define the classes each in a __separate file__.

* Create __Lab03.java__ with a main method. Create the objects with the following data using the classes you have defined.



```
Sam
Pune, India - New Delhi, 1.4 billion
New York City, USA - Washington DC, 400 million
Sam's friend is Ram

Ram has not visited any city yet
Ram's friend is Sam
```

------------------------------------------------------------
* Create a class called __Account__ that does the following. 

### Part I

* It has a balance that needs to be initialized with a value greater than 10000
* Methods to __deposit, withdraw__. If there isn't sufficient balance don't allow withdraw.
* You can withdraw only 3 times. After that you will be charged 0.5% of the amount as Fees.

* Create an object of __Account(20000)__ from main() in __AccountUser.java__ and call deposit twice and withdraw 5-6 times. Print the Balance

* Implement a method __printStatement__ that prints the list of transactions performed. 
* This method will display the __account number, amount, type of transaction(Credit or Debit)__ and the __time__.
* Instead of using arrays, you can create an instance of __java.util.ArrayList__ and use methods like __size(), get()__ for storing the transactions. Sample code is here

``` java
//If you want to store a collection of strings
ArrayList<String> transactions = new ArrayList<>();
	
//If you want to store a collection of Transaction class objects
ArrayList<Transaction> transactions = new ArrayList<>();
	
transactions.add(...);
transactions.add(...);
transactions.add(...);

```

* Follow the basic design constructs in Java language in this lab.

### Part II

* Reuse the Account.java 
* Create __CurrentAccount__ class
* CurrentAccount allows __10 withdrawals__
* Limit of withdraw amount at any point of time is 1 Lakh only
* Create a Premium Current account that __allows 100 withdrawals__ and withdraw limit is 10L
* Create some Current Account and Premium Current Account objects and use the deposit and withdraw methods. Print statement to check the transactions and display the balance


* __You can make Account and CurrentAccount be related to each other using an interface or abstract class__
