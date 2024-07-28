This GitHub repository has everything you need to fully understand the Java project it contains.

Here's what you'll find inside:

A zip file with all the Java source files for detailed code review and changes
Another zip file with the generated Javadoc documentation, explaining the project's classes, methods, and overall structure
A JPEG image showing the Dia diagram of the project's design to help visualize its structure
With these resources, you'll have all the tools necessary to comprehend and work on the Java project.

Project Description:
This project simulates a Hotel Reservation System.
  The features of the project contains:
    (1). Create/Register a new hotel in the System 
           - You can create a Hotel object in the system and specify many room it has.
           - It can only have 50 rooms maximum but has one minimum.
    (2). Remove a registered hotel in the System
           - You can remove a Hotel object in the system. 
           - Remove feature is not available when there are no existing hotels.
           - NOTE: You cannot remove a Hotel with existing reservation.
    (3). View a registered hotel in the System
           -You can view a Hotel object details in the system.
           -You can see the name, type, and the price of the Room.
           -You can also see the Reservations existing in the Room.
           -You can change the type of the Room. (Details are shown below).
           -NOTE: View feature is not enabled when there are no exisisting Hotels.
    (4). Change Price of a Hotel
          -You can change the cost per night of a Hotel
          -NOTE: The price change must atleast be 100.00
    (5). Change the Rate of a Day of a Hotel
          -You can change the rate of a Day of a Hotel
          Explanation:
            Hypothetically the price of a Regular Room in the Hotel is 100.00 and hypothetically you change the rate of the 1st day to be 0.9.
            If you booked a Regular Room in the Hotel and check-in and out at the 1st day, the price of the reservation should be 90.00.
          -NOTE: You cannot change the rate of a Hotel when there is an existing Reservation.
    (6). Simulate a Booking on a Hotel
          -You can create a Reservation on a Hotel
          -You need to input the guest name, Hotel number, Room number, check in and check out dates and a code if there is.
          -(Codes will be explained below)
          -NOTE: You cannot create a Reservation on a Hotel if there are existing Reservation on the check in and check out inputs.


    More Details:
    -There are 3 different types of Rooms
      Regular Room - it contains the regular price of the hotel
      Deluxe Room - it will cost 20% more than the regular price
      Executive Room - it will cost 35% more than the regular price
    -Codes you can use to simulate a booking
      "I_WORK_HERE" - 10% discount
      "PAYDAY" - 7% discount when the date 15 and 30 is in between the booking
      "STAY4_GET1" - if the booking details contains more than 5 days, the price of the booking will be less than 1
      NOTE: You can only use 1 code per reservation.

