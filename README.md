# reservation-api
Little lemon Reservation api


==maysql/maria== 
dbuser: root, password=root

==End Points==
/api/bookings/
/api/registration/


==API==

Payload For Testing

{
    "customer_name": "moses",
    "customer_email": "moses@example.com",
    "date": "2024-08-16",
    "time": "20:00:00",
    "party_size": 5
}


api

http://127.0.0.1:8000/api/bookings/
Posting end point.

http://127.0.0.1:8000/api/bookings/{id}/
http://127.0.0.1:8000/api/bookings/{id}/
http://127.0.0.1:8000/api/bookings/

all these are GET method
