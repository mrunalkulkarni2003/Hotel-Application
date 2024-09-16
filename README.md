#Hotel-Management-Application

This Hotel Management Application is a comprehensive web-based solution designed for booking hotels. Built with a focus on user experience and security, the app allows users to search for hotels, view detailed information, and complete bookings. The application is integrated with MongoDB for fetching hotel data via APIs, providing real-time updates based on search inputs like destination, date range, price range, and guest options.

Key Features - 
Hotel Search and Booking: Users can search for hotels by selecting a destination, date range, and guest options. Upon searching, related hotels are fetched and displayed, with the ability to adjust the search inputs or price range for real-time updates. Detailed hotel information is shown upon selecting a hotel, and the user can proceed to book after logging in.
Admin Panel: The app includes an admin panel with options to manage users and hotels. Admins can add new rooms, delete users, and add new hotels to the system.
Authentication & Security: The app uses JWT (JSON Web Token) for secure authentication. API requests are protected and made using cookies.
Conditional Authentication: Separate login functionality for property hosts and regular users.
Booking Process: The booking page allows users to select the number of rooms and finalize the reservation process after login.

Technologies Used - 
MongoDB for the database
REST APIs for data fetching and management
JWT for secure authentication
Cookies for making API requests and managing sessions

How to Use - 
Clone the repository. Install the dependencies using command 'npm install'. Start the server using the command 'npm start' and open the app in your browser.

How to Interact - 
Search for Hotels: Choose a destination, date range, and number of guests to view available hotels.
View Hotel Details: Click on any hotel to see pictures, pricing, and other relevant details.
Booking: Log in and select room options to complete the booking.
Admin Panel: Admins can log in to manage users, hotels, and room availability.
