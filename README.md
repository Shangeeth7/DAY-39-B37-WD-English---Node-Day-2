# Nodejs hall booking api task

:--> Hall_Bookking_api :

GET : // To get all Room Data

https://roombooking-api.herokuapp.com/

GET : //To get booked customer details

https://roombooking-api.herokuapp.com/booked-customer-details

GET : //To get booked room details

https://roombooking-api.herokuapp.com/booked-room-details

POST : // To creaate a room

https://roombooking-api.herokuapp.com/create-room

Bodyraw (json)
json :

{
"name": "Medium",
"seats": 30,
" roomId": "006",
"amenities": [
"food",
"air conditioner",
"tv"
],
"price": 550,
"BookingStatus": "Occupied",
"customerDetails": {
"cutstomerName": "Sanjay",
"date": "2022-10-05",
"start": "17:00",
"end": "23:00",
"roomId": "006",
"status": "Booked"
}
}

POST : //To book a room

https://roombooking-api.herokuapp.com/room-booking

Bodyraw (json)
json :

{
"customerName" : "Shangeeth",
"date" : "2022-10-05",
"start" : "12:30",
"end" : "20:00",
"roomId" : "012"

}
