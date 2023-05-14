# flask-wtf-coffee-wifi

Goal of today is to ensure that I'm fully comfortable with Flask-WTF, Flask-Bootstrap, Bootstrap classes and do a bit of revision on csv manipulation.

![image](https://github.com/pradomska/flask-wtf-coffee-wifi/assets/113101087/954e35e4-ceec-4cbe-b439-32f8634fe3b8)

The "/cafes" route is rendering the cafes.html file. This file contains a Bootstrap table which displays all the data from the cafe-data.csv.

![image](https://github.com/pradomska/flask-wtf-coffee-wifi/assets/113101087/ce9f3694-1475-4b0b-9d75-3286e6471351)

There is also a secret route "/add" which doesn't have a button, but those in the know is able to access it, where using "quick_form" contains all the fields.
When the user successfully submits the form on add.html, the data gets added to the cafe-data.csv. It needs to be appended to the end of the csv file. The data from each field need to be comma-separated like all the other lines of data in cafe-data.csv

![image](https://github.com/pradomska/flask-wtf-coffee-wifi/assets/113101087/062f2f67-7ea8-4047-96b8-7676a09a8795)
