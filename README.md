# simple-REST-python-mongo

Start your mongodb server, create a new database called hotel1 and then run this python script in a python server using the command: python simple_rest_hotel.py from the directory where you have saved a copy of the py file, then using Postman you can POST new Hotels to the hotel1 database using json such as:

{
"name" : "Paris No 1 Hotel", 
"address" : "Paris, Le something rather"
}

with the url: http://127.0.0.1:5000/room

Then view your hotels by playing around with the two GET HTTP functions in the script via Postman, using urls:

http://127.0.0.1:5000/room
http://127.0.0.1:5000/room/name_of_hotel

