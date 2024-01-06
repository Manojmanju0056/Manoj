# Train Ticket Booking

This Solidity smart contract implements a Train Ticket Booking System on the Ethereum blockchain. The contract enables users to book even-numbered seats within the range of 1 to 50, associating each seat with the Ethereum address of the booking passenger.

## Features

###  Ticket Booking

- Users can book train tickets by interacting with the contract.
- Only even-numbered seats (within the range of 1 to 50) are available for booking.

###  Seat Validation

- The contract validates seat numbers to ensure they fall within the acceptable range.
- It restricts booking to even-numbered seats.

###  Prevention of Double Booking

- The contract prevents double booking of seats. If a seat is already booked, the transaction reverts with an appropriate message.

## Usage

1. Deploy the contract on an Ethereum-compatible blockchain.
2. Users can interact with the contract by calling the `bookTicket` function and specifying the desired seat number.



## License

This contract is released under the MIT License. See the (LICENSE) file for the terms and conditions.


## Author

Manoj

manjumanoj0056@gmail.com


