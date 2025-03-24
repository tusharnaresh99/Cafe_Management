# Cafe_Management
# Monk's Cafe Ordering and Booking System

Welcome to Monk's Cafe! This is a simple Python program that allows customers to either place an order from the cafe's menu or make a booking for a table.

## Features

1. **Order Placement**: Customers can choose items from the menu, specify quantities, and view the total cost of their order.
2. **Booking System**: Customers can provide their name, select a number of persons, and set a time for their table booking.
3. **Simple Menu**: The cafe offers a small menu with items like Maggie, Momos, Golgappe, and Pizza.

## Menu

- **Maggie**: 40
- **Momos**: 50
- **Golgappe**: 60
- **Pizza**: 120

## How to Use

1. **Run the script**:
    - The script will prompt you to either place an 'order' or make a 'booking'.
    
2. **Order**:
    - If you choose 'order', the menu will be displayed. Select items and specify quantities. Once you finish, the program will show a summary of your order along with the total bill.
    
3. **Booking**:
    - If you choose 'booking', you will be asked for your name, the number of persons, and the time for your table reservation. The system will confirm the booking with your details.

## Requirements

- Python 3.x

## Example Usage

```python
----Welcome To Monk's Cafe----
Would you like to place an 'order' or make a 'booking'?
```

### Example for placing an order:
```
Enter the item you'd like to order (or type 'done' to finish): Maggie
Enter quantity for Maggie: 2
Your current order: {'Maggie': 2}
...
Total bill: 80
```

### Example for making a booking:
```
Please enter your name: John Doe
For how many persons do you want to book a table? 4
Please enter the time (between 10:00-22:00) for your booking: 18:00
Thank you John Doe! Your table for 4 persons has been booked for 18:00.
```

## How to Run

1. Clone this repository to your local machine.
2. Open a terminal and navigate to the directory where the file is located.
3. Run the Python script by typing:

   ```bash
   python monk_cafe.py
   ```

## Contributing

If you want to contribute to this project, feel free to fork the repository, create a new branch, make your changes, and submit a pull request.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

Make sure to update the `monk_cafe.py` filename if needed. This README provides clear instructions for usage and how others can contribute.
