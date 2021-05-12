# Grocery-Store-Management-System
Grocery Store Management System

GSMS Documentation (read me)

Login Class
Name : Login
Methods: 4

  Login class allows user to login as Owner or Employee. 
  It has following methods:
    1.	owner_ids():
    2.	owner_ids():
    3.	employee_ids():
    4.	employee_login():

Owner Class
Name : Owner
Methods: 10

  Owner class allows owner to view stock, add stock, refill stock, can see costumers list/details, 
  can see purchased quantities and see complete bills till the time.

    It has following methods:
    1.	get_ownerids()
    2.	owner_password_check()
    3.	coustmers()
    4.	print_details()
    5.	sales_record()
    6.	stock_ids()
    7.	stock_products()
    8.	stock()
    9.	stock_lookup()
    10.	add_stock()


Employee Class
Name : Employee
Methods: 9
  Employee class allows employees to view stock, refill stock, Collect customer Details add and remove products 
  to current customer purchase list, print out complete bill, Collect and return Cash.

    It has following methods:
    1.	get_ids ()
    2.	password_check()
    3.	view_stock ()
    4.	customer()
    5.	add_product()
    6.	get_Receipt()
    7.	e_pay()
    8.	remove_product()
    9.	printing()

Customer Class
Name : Customer
Methods: 2

  It returns customer a mini receipt with total quantity bought and amount to pay. 
  Also aid in collecting and returning cash. 

    It has following methods:
    1.	getReceipt ()
    2.	pay ()

Stock Class
Name : Product_stock
Methods: 2

  It allows employ to refill exciting stock and view remaining stock items
  
    It has following methods:
    1.	product_store ()
    2.	update_product ()
