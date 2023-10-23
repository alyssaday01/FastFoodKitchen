# Fast Food Kitchen
## Intro to Computer Science II: Project 3
## Coding Language: Java

This project was completed in an intro to computer science course in 2022.

The Fast Food Kitchen Order Management System is a coding project designed to efficiently manage a fast-food kitchen's burger and soda orders. It involves the creation of order objects that represent different types of burgers (hamburgers, cheeseburgers, veggie burgers) and sodas. The system keeps track of whether the order is for dine-in or takeout and assigns a unique order number to each order. Additionally, it maintains a list of pending orders, allowing users to interact with the system by choosing from a set of options.

## Key Components:

- Burger Order Class: The Order class represents an individual order and includes attributes like order type (hamburger, cheeseburger, veggie burger, soda), quantity, order number, and dine-in or takeout flag.

- Fast Food Kitchen Class: The FastFoodKitchen class is responsible for managing the orders and includes an ArrayList to store all pending orders.
It provides methods for adding new orders, canceling the last order, showing pending orders, completing orders (checkout), checking the status of a specific order, and canceling a specific order. The order numbers increase with each new order, ensuring uniqueness.

- Fast Food Driver(Driver Class): The FastFoodKithcen class presents a menu of options for the user to interact with the system. The user can choose from the following options:
  - Order Food: Create a new order for a burger or soda, specifying the type and quantity.
  - Cancel Last Order: Remove the most recent order from the pending orders list.
  - Show Pending Orders: Display a list of all pending orders with their order numbers.
  - Complete Order (Checkout): Mark an order as completed and remove it from the pending orders list.
  - Check on Status of Order: Provide information about a specific order, including its type, quantity, and status.
  - Cancel Specific Order: Remove a specific order from the pending orders list using its order number.
  - Exit: Exit the program.
