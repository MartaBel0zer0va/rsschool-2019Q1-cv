 # Java Developer resume
 
#### Troshka Marharyta 
#### *(29)8262130* or _margarita1980rb@gmail.com_
## Summary
### I can work in a challenging and dynamic environment.
## Skills
### * Knowledge of object oriented programming and design.
### * Knowledge of HTTP and Web
### * Git
### * Java 8, Spring Framework
### * HTML, CSS, JavaScript
## Code
```java
public void withdraw(double amount) throws OverdraftException {
        if ( balance < amount ) {            
            // Not enough balance to cover the amount requested to withdraw
            // Check if there is enough in the overdraft protection (if any)
            double overdraftNeeded = amount - balance;
            if ( overdraftAmount < overdraftNeeded ) {                
                // No overdraft protection or not enough to cover the amount needed
                throw new OverdraftException("Insufficient funds for overdraft protection",
                        overdraftNeeded);                
            } else {                
                // Yes, there is overdraft protection and enough to cover the amount
                balance = 0.0;
                overdraftAmount -= overdraftNeeded;
            }            
        } else {            
            // Yes, there is enough balance to cover the amount
            // Proceed as usual
            balance = balance - amount;
        }
    }
  
## Experience

## Education
> BSU, MMF, Mathematics, 2017-2021
> Courses in programming for the Java SE, 2018 
> Online: Codeacademy, JavaRush, 2017-2018
## Knowledge of english
> I can understand the main points of clear texts in standard language if they are about topics with which they are familiar, whether in work, study or leisure contexts.





