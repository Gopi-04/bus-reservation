# Bus Reservation using Java

A simple Java-based Bus Reservation System that allows users to book and cancel seats on a bus using IntelliJ Idea. This project simulates a basic reservation system with a text-based interface.

# Features
**Book a Seat:** Users can select a seat from the available options and book it by entering their name.

**Cancel a Reservation:** Users can cancel a previously booked seat by entering the seat number and their name.

**View Seat Availability:** The system displays the current seat availability, showing which seats are booked and which are available.

**Payment Simulation:** Simulates a payment process for booking seats.
# Prerequisites
Java Development Kit (JDK) 8 or higher
An IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans) or a simple text editor with a command-line interface.
# Installation
**Clone the Repository:**
```bash
git clone https://github.com/Gopi-04/bus-reservation/blob/main/busReservation.java
```

**Navigate to the Project Directory:**

```bash
cd busReservation
```

**Open the Project:**

If using an IDE, open the project directory.
If using a text editor, open the **busReservation.java** file.
# How to Run
**Compile the Java File:**

**Open a terminal in the project directory and run:**

Copy code
```bash
javac busReservation.java
```

**Run the Program:**

**After compilation, run the program using:**
```bash
java busReservation
```
# Interact with the System:

You will be prompted to select a seat number to book or cancel.
Follow the on-screen instructions to book a seat, cancel a reservation, or exit the system.
Code Structure
Reservation.java: The main file containing the logic for booking and canceling seats, payment simulation, and user interaction.
# Usage
**Booking a Seat:**

When prompted, enter a seat number (1-9) to book.
Provide the passenger's name when requested.
Complete the payment simulation to confirm the booking.

**Canceling a Reservation:**

When prompted, enter a seat number (1-9) to cancel.
Provide the name associated with the booking for validation.
The system will confirm the cancellation and refund.
# Example Output

---------------   SELECT THE SEAT NUMBER YOU WANT   ---------------

---------------   STARRED '*' SEATS ARE BOOKED SEATS   ------------

---------------   SELECT OTHER AVAILABLE SEATS   ------------------

[1]  [2]  [*]  

[4]  [*]  [6]  

[*]  [8]  [9]  

**ENTER THE SEAT NUMBER TO BOOK : 1**

**ENTER THE PASSENGER NAME : Gopi**

---------------- Your Seat Has Been Locked ----------------

---------------- Pay 500 INR to Book/Confirm Your Seat ----------------

**Enter Card Number : 1234567890123456**
**Enter CVV : 123**

----------  Payment Successful  ----------

**Ticket booked for : Gopi**

**Seat Number       : 1**

**Start Place       : CHENNAI at 11:00pm**

**End Place         : SALEM at 6:00am**

# Contact

For any questions or feedback, please contact me at [pvgopi04@gmail.com](mailto:pvgopi04@gmail.com).
