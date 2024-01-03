# Hotel-Management-OOP-Project
This hotel management tool efficiently handles tasks like storing customer details, room bookings (of four types), food orders, unbooking rooms, and generating bills. It employs a menu-driven approach and runs continuously until the user exits. File handling is implemented to persist data (customer details, booked rooms, and food orders) in a file upon program termination, ensuring data persistence across program restarts. During restarts, the program reads the file to retrieve the prior hotel status. Notably, the file-writing operation occurs in a separate thread for parallel execution. To enhance robustness, user-defined exceptions are thrown, particularly when attempting to book an already allocated room. The program features comprehensive exception handling to manage unexpected situations effectively, ensuring a smooth and error-resilient hotel management experience.

Topics covered-

Classes and Objects, Inheritance, File Handling with Objects, ArrayList, Interface, User defined exception and Exception handling.


