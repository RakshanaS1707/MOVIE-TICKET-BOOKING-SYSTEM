# MOVIE-TICKET-BOOKING-SYSTEM
Java
The main objective of the online movie ticket booking system is to manage the booking and cancelling tickets, displaying a particular ticket detail, exchanging seats in theatre, add a movie and displaying all movies. The purpose of the project is to build an application program to reduce the manual work. This application is developed in Java using OOPS and inheritance concept.

FUNCTIONAL REQUIREMENTS:

* Book a ticket
* Cancel a ticket
* Display particular ticket details
* Entering into the movie
* Exchange seats
* Add a movie
* Displaying all movies
* Exit

CLASSES IDENTIFIED:

* Movie
* Customer
* Booking
* Payment
* Seats
* Shows

CLASS ATTRIBUTES:

Movie Attributes: movie_id, movie_name, movie_language, movie_type, movie_hour, movie_description

Customer Attributes: customer_id, customer_name, customer_mobile, customer_email, customer_username, customer_password, customer_address

Booking Attributes: booking_id, booking_title, booking_type, booking_ticket, booking_date, booking_description

Payment Attributes: payment_id, payment_customer_id, payment_date, payment_amount, payment_description

Seats Attributes: seat_id, seat_movie_id, seat_customer_id, seat_number, seat_type, seat_description

Shows Attributes: show_id, show_name, show_type, show_time, show_date, show_description

CLASSES AND THEIR METHODS:

Movie Methods: addMovie(), editMovie()delete Movie(), update Movie(), saveMovie(), search Movie()

Customer Methods: addCustomer(), editCustomer(), delete Customer(), updateCustomer(), saveCustomer(), searchCustomer()

Booking Methods: addBooking(), editBooking(), deleteBooking(), updateBooking()saveBooking(), searchBooking()

Payment Methods: addPayment(), editPayment()deletePayment(), updatePayment(), savePayment(), searchPayment()

Seats Methods: addSeats()editSeats()delete Seats(), updateSeats(), save Seats(), search Seats()

Shows Methods: addShows(), editShows(), delete Shows(), updateShows(), saveShows(), searchShows() .
