
### Answers to questions of part II.

# Part II:

2. The value of balance is now zero.

3. If too much money is inserted, the balance is returned to zero without 
   without giving the moey back. When too little is inserted, the ticket is 
   printed nontheless. If there is zero money in the balance, the ticket is 
   printed anyway.

5. The price printed on the ticket is different.

6. `public class LabClass` and `public class Student`

7. Yes, public is the visibility, class declares that it is a class. The class
   has red lines all over it. It says, "<identifier> expected", this explains
   what is wrong to someone who knows what should be there but to a beginner
   it is slightly unspecific.
   
10. public class TicketMachine
    public TicketMachine(int cost)
    price = cost;
    balance = 0;
    total = 0;
    public int getPrice()
    return price;
    public int getBalance()
    public void insertMoney(int amount)
    public void printTicket()
    
11. It does not have a class identifier and 
    it contains parameters`(int cost)`.
    
12. Int, String, String.

13. alive, tutor, game.

14. 2.12: Student and Server. 2.13: Person and Game.

15. Yes it does matter. Yes, it is either red, signaling an error or grey
    if it is okay.
    
16. Yes.

17. `private int status;`

18. Student.

19. Two, String and double.

20. Yes. Strings (words/sentences) and doubles (numbers with decimals).
    Their names are title and price respectively.
    
21. ```public Pet(String petsName)
    {
     name = petsName;   
    }```
    
22. `public Date (String month, int day, int year) { ... }`

23. When the get method is used, a different field is called. In the body,
    a different field is returned. 
    
24. "What is my current balance in the ticket machine?"

25. No it doesn't. It means that the name is only usefull as a description
    and doesnt actually change what the get method is doing.
    
27. "not a statement"

28. printTicket does not return a statement therefore its return statement
    is void.

29. No because they are setters not getters, they are called to set a value
    not to return one.
    
31. ```
    /**
    * Increase score by the given number of points.
    */
    public void increaseScore(int points)
    {
    score = score + points;
    }
    ```
    
32. Yes, it is a mutator. It could be demonstrated with a student object 
    by calling a getCredits method showing that the amount of credits has changed.

33. ```
    /**
    * Reduce price by the given amount.
    */
    public void discount(int amount)
    {
    price = price - amount;
    }
    ```
    
34. `public void currentAge(int age)`

35. `public void isAlive(boolean alive)`

36. The price is now zero even thought 25 was inputed.

37. My cat has green eyes.

39. #priceccents

40. # price cents

42. They have different outputs because their price is not the same.

43. Yes it prints the same thing. %d displays the price with a decimal and %n skips a line.

44. It now only asks for a name and not a price when a new object is created.

46. It does not need any parameters. It is a mutator.
