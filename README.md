# salon-booking-system
A system design architecture study for a booking system for Salons


Base Idea:
add the requirements for the Salon Booking system, add what database relations we want in mySQL ,  generate DBML for database diagram (https://dbdiagram.io/d) 
Doc for DBML: https://dbml.dbdiagram.io/home
use excalidraw for diagramming (mermaid chart is fine for the system architecture)

Booking system demo: https://youtu.be/m67Mjbx6DMY?si=5Acu2oK7ehfNdMlj

Salon owners would also have a choice to choose weather it's a strictly male or female salone, in which case there would be no options for customers to choose male or female while resereving(which would be enabled by default) since they'd already be choosing male/female salons

There would be generally two parts
1. Admin (Salon Owners)
2. User (Salon Customers)

Admin would handle adding new Salon to the database & associated info of the salon
Salon will contain the following fields
How Many Seats are at the Salon (Seat number)
Which days are they open
What services they provide(check below for service ceategories)
Weather they have waiting room , snacks options

Users flow:
User check the list of Salons
User choose a salon via list of search 
User choose a service to see weather the salon provides the service or not
optionally they can select snacks (tea or coffee) for when they have to sit at the waiting room 
Finally comes Reservation:
Users can pick a date for reservation, or the calender could show which days at the salon are available for reservation of seat
they the user will pick a seat 
submit reservation to the cart
go to the cart & proceed to payment
the reservation receipt will be auto generated with QR code for the user & will remain under the salon's database 


Male & Female Categories
Males:
Beard Sculpting
Hair Color (Options: Multiple color options like red,blue,brown etc)
Hair Style
Hair Style with Half Body Massage
Hair Style with Full Body Massage
Scalp Massage & Conditioning Treatment

Female:
Facial
Special Make Up (options: engagement, bridal, party)
Pedicure (options: Nail, Feet)
Hair Color (Options: Multiple color options like red,blue,brown etc)
Eyebrow Trim
Scalp Massage & Conditioning Treatment

# Database

DB Relations: https://dbdocs.io/shatil1921046/Salon-DB?view=relationships  
DB Diagram:

<img width="1935" height="698" alt="SalonDB" src="https://github.com/user-attachments/assets/819e3cdc-f2ea-4b92-8a2c-e8136f56807e" />

# Architecture
<img width="4779" height="2165" alt="sysdesign-salon" src="https://github.com/user-attachments/assets/f83bf1d8-a4c2-4dcf-9971-36238e76ea59" />




