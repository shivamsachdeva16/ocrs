# ocrs
Online Car Rental System built on django framework and mysql as database.

## the structure of project 

  there are two modules (apps) one for customers, one for the home page. Each app handles usual django things like models, urls and views.
  
## the system

  This is how the system works, a user signs up and uploads cars that he thinks are available for renting. Customer logs in to the customer_portal, enters the area at which he wants the car and the system scans through all the available cars at that perticular area and shows the results to the customer. If the car is already rented by someone else it wont show up in the search results. 
  

## database 

  I have used the local mysql database and the python classes in models.py helps managing/updating database. the database configuration can be accessed in ocrs/ocrs/settings.py and in that file under the DATABASE section you can add your own database, username password etc.
