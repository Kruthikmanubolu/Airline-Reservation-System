# Airline-Reservation-System

  Airline Reservation System developed using HTML , CSS , JavaScript , NodeJS , ExpressAPI and FirebaseAPI.
  
• **Manage the header functions**

o Login Management

o Booking Management

o Profile Management

• **Login**

o open the login/register page

o enable logging-in

o upon successful login, redirect to the page intended

o upon failure, redirect to exception processing (retry, forgot password or register)


• **Booking Management**

o display the list of bookings where travel is not yet completed - (Time and date constraints are still in progress)

o select the booking

o if the booking is not listed, allow the user to enter the PNR and last name for pulling up the booking

and linking it to the login id

• **Check-IN**

o Show the layout of the seating arrangement in the plane

▪ enable only the seats for the class the booking has been made

▪ cross the seats that have already been selected by others

▪ upon confirming the seats, generate a PNR Number for future reference


• **Profile Management**

o Show the personal information collect and allow options for editing (name, address, DoB, current

password, preferences)

o Upon saving show the updated details

After the check-in is complete, issue a PNR Number which can be used to generate a scannable code that can be scanned by

the agent's application and board the passenger


• **Boarding**

o Select the flight for which boarding is being done in the desktop application

o Pull up the list of customers that need to be boarded

o Upload the bar code/QR Code in the boarding pass and transfer the details to the main application running on the desktop

o Upon receiving the bar code details, call a function to decode and validate the bar-code and board

the customer

▪ Update the database that the customer can be successfully boarded

o Display the details of the scan so that

▪ a check can be done to verify if all the customers have been boarded

▪ remove the customers from the list as they are successfully boarded

▪ a list of the customers yet to be boarded is left showing, for making the announcements
