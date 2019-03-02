 # Java Developer resume
 
#### Troshka Marharyta 
#### *(29)8262130* or _margarita1980rb@gmail.com_
## Summary
* Computer programmers can work in a challenging and dynamic environment.
* Computer programmers need to understand, manipulate, and repair complex computer code.
* Computer programmers may need help from another department or colleague to fix a software issue. It is important they have a collaborative mindset.
#### I have to work my hardest in order to achieve progress in this field, and I do. About me:
> Analyzing processes and selecting the simplest way to accomplish a task
> Setting daily, weekly and monthly goals
> Assertiveness to say no to inappropriate demands that distract from central duties
## Skills
### * Knowledge of object oriented programming and design
### * Knowledge of HTTP and Web
### * Git
### * Java 8, Spring Framework
### * HTML, CSS, JavaScript
## Code
```java
public void withdraw(double amount) throws OverdraftException {
        if ( balance < amount ) {            
            double overdraftNeeded = amount - balance;
            if ( overdraftAmount < overdraftNeeded ) {                
                throw new OverdraftException("Insufficient funds for overdraft protection",
                        overdraftNeeded);                
            } else {                
                balance = 0.0;
                overdraftAmount -= overdraftNeeded;
            }            
        } else {            
            balance = balance - amount;
        }
    }
  ```
## Experience
#### course project
```java
public class Customer {

  private String firstName;
  private String lastName;

  private List<Account> accounts;

  public Customer(String f, String l) {
    firstName = f;
    lastName = l;
    accounts = new ArrayList<Account>(10);
  }

  public String getFirstName() {
    return firstName;
  }

  public String getLastName() {
    return lastName;
  }

  public void addAccount(Account acct) {
    accounts.add(acct);
  }

  public int getNumOfAccounts() {
    return accounts.size();
  }

  public Account getAccount(int account_index) {
    return accounts.get(account_index);
  }
}
```
## Education
> BSU, MMF, Mathematics, 2017-2021
> Courses in programming for the Java SE, 2018 
> Online: Codeacademy, JavaRush, 2017-2018
## Knowledge of english
> I can understand the main points of clear texts in standard language if they are about topics with which they are familiar, whether in work, study or leisure contexts.





