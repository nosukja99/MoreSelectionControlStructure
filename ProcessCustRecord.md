A program is required to read a customer’s name, a purchase amount and a tax code. 
The tax code has been validated and will be one of the following:
    0  tax exempt (0%)
    1  state sales tax only (3%)
    2  federal and state sales tax (5%)
    3  special sales tax (7%)
The program must then compute the sales tax and the total amount due,and print the customer’s name, 
purchase amount, sales tax and total amount due.

    ALGORITHM : compute the tax and total amount due and display 
	
	===================================
	INPUT : String name, purchase, taxCode

	PROCESSING STEPS : According to the input tax code, compute each tax 
	and add it to the purchase to get totla amount

	OUTPUTS : name, purchase, sales tax and total amount

	=================================
	PSEUDOCODE : Initialize String name to null
	             Initialize double purchase to zero
				 Initialize String taxCode to null
				 Initialize double salesTax to zero
				 Initialize double totlaAmount to zero
	             Prompt user input name, purchase, and taxCode
				 Get name, purchase, taxCode
				 CASE OF taxCode
				    0: salesTax =purchase totlaAmount=purchase
					1: salesTax =purchase*0.03 totlaAmount=purchase+salesTax
					2: salesTax =purchase*0.05 totalAmount=purchase+salesTax
					3: salesTax =purchase*0.07 totalAmount=purchase+salesTax
				 Diaplay name, purchase, salesTax, and totalAmount