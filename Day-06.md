### Record of learning Java with English tutorial

Day  6/Infinity（coding）June 7, 2022

### Java

1. Cannot use comparison operators between reference types, because the these operators will compare the address or string objects, not the value.

2. break statement - break is used to jump out the loop

3. final byte/int means can't change the value after. Should use all capital letters for the variable name.

4. how to create method

   - void: not return message
   - String: return message

5. The **getCurrencyInstance()** method is a built-in method of the **[java.text.NumberFormat](https://www.geeksforgeeks.org/numberformat-class-java/)** returns a currency format for the current default FORMAT locale.

   **Program1**:

   ```java
   import java.text.NumberFormat;
   import java.util.Locale;
   import java.util.Currency;
   
   public class Main {
       public static void main(String[] args)
           throw Exception
       {
           // Get the currency instace
           NumberFormat nF
               = NumberFormat.getCurrencyInstance();
           
           // Sets the currency to Canadian Dollar
           nF.setCurrency(
   	        Currency.getInstance(Local.CANNDA));
       }
   }

6. assign statement must in the block 

   

7. ```java
   while (ture) {
       int a = 10; // If not in curl braces, compiler will express an error.
   }

FOR EACH statement - has limited, one is forward only. If don't need index, for each statement is good.

```java
for (String fruit : fruits)
    System.out.println(fruit);
```

Unfamiliar words & terms:

1. parenthesis

2. consumption

3. characteristic `noun`

   1. a feature or

4. generic `adj.` 

   1. characteristic of or relating to a class or group of things; not specific
   2. Biology of or relating to a genus

5. prompt `n.` 

   1. a word or words said to an actor, to remind them what to say next when they have forgotten
   2. `(computing)` a sign on a computer screen that shows that the computer has finished doing sth and is ready for more instructions
      - You can also call any command or function at the prompt.

6. overextend  `v.`

   - make too long    

   - impose on (someone) an excessive burden of work or commitments   
     1. Do not overextend yourself; learn to say no.
     2. Any users of credit may overextend themselves.

7. recap`v.` `n.` - ~ (on sth) | ~ sth

   - Let me just recap on what we've decided so far.
   - Can you recap the points included in the proposal?
   - To recap briefly, the agreement was rejected 10 days ago.

8. trade off

9. implement this scenario 

10. scenario `n.` `pl. os` - a description of how things might happen in the future

   ​                                   - a written outline of what happen in a film/movie or play

      - Let me suggest a possible scenario.
      - The worst-case scenario(= the worst possible thing that could happen) would be for the factory to be closed down.
      - a nightmare scenario

11. envelope `n.` -- a flat paper container used for sending letters in

    ​					  -- a flat container made of plastic for keeping papers in	 

12. enclose `VN` 

    1. to  put sth in the same envelope, package, etc. as sth else

    - Please return the completed form, enclosing a recent photograph.

    