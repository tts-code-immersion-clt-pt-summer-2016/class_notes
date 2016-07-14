# Create a Tip Calculator
-

----
### Step 1 - tip_amount method
- - - - 
- create a bill_amount variable that stores the amount of the check (w/o gratutity) 
	

- create a method named tip_amount
	- insure that it takes the bill_amount variable as an argument
	- returns 20% of the total bill

- Run the script to insure that the tip_amount is doing what you expect (I recommend using whole numbers like 100 while testing)


	*hint: you'll need to multiply using a float, and don't forget to convert your answer into the proper data-type!*





----
### Step 2 - total\_with_grat method
- - - -
- Create a method that SUMS the bill_amount + the tip\_amount

- print the total bill to the screen

	*hint: you'll need to pass the bill_amount variable into the method as an argument*

----
### Step 3 - Refactor!

----

- This looks good, but you'll notice that we are running the same method several times. 

- Because we are writing clean, DRY code... 
	- we can actually call the total\_with_grat() method one time 
	- this will take care of all the calculations for us
- Give it a try! 

----

### Extra Credit!

----

- Now, 1 more thing... we need to fix that float to reflect two decimal points... 

- The easiest way to do this, is to use the [sprintf method](http://ruby-doc.org/core-2.2.0/Kernel.html#method-i-sprintf)
	- Go read up on the documentation and try to apply the correct formatting using sprintf()
