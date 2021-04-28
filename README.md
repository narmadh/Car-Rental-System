# Car-Rental-System 
A full fledged car rental system implemented in Python using object oriented programming.

## Customers can 

* See available cars on the shop
* Rent cars on hourly basis $5 per hour.
* Rent cars on daily basis $20 per day.
* Rent cars on weekly basis $60 per week.
* Family Rental, a promotion that can include from 3 to 5 Rentals (of any type) with a discount of 30% of the total price

## The rental shops can

* issue a bill when customer decides to return the car.
* display available inventory
* take requests on hourly, daily and weekly basis by cross verifying stock
  
Since classes are used various customers and car rental shops can be instantiated as needed.

For simplicity we assume that any customer requests rentals of only one type i.e hourly, monthly or weekly but is free to chose the number of cars he/she wants. However requested cars should be less than available stock.




## How to run?
This code is written in python3.6.

Simply run
``` 
python main.py

# or depending upon your config

python3 main.py
```
