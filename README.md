# ATM-System
# ATM Project in C#

Welcome to the ATM Project repository! This repository contains the source code and documentation for our ATM (Automated Teller Machine) system, written in C#. Our goal was to develop a user-friendly and secure ATM system with various functionalities to provide a seamless banking experience.

## Features

Our ATM system offers the following key features:

1. Deposit: Users can deposit funds into their bank accounts using the deposit button. The system securely processes the transaction and updates the account balance accordingly.

2. Withdraw: Users can withdraw cash from their bank accounts by selecting the withdraw button. They can enter the desired amount, and the system will dispense the appropriate denomination of currency while maintaining the account balance.

3. Fast Cash: The fast cash feature allows users to quickly withdraw predefined amounts of cash, such as $20, $50, or $100, by selecting the corresponding buttons. This provides a convenient option for immediate cash needs.

4. Mini Statement: Users can request a mini statement that displays their recent transactions. By clicking the mini statement button, the system retrieves and presents a concise summary of the user's transaction history.

5. Change PIN: To enhance security, users have the option to change their PIN (Personal Identification Number) using the change PIN button. This feature ensures that users can maintain control over their account access.

6. Balance: Users can check their account balance by clicking the balance button. The system retrieves the account information from the database and displays the current available balance.

## System Design

Our ATM system is designed with multi-level hierarchies to ensure modularity and maintainability. The system follows an object-oriented approach, leveraging the power of classes, inheritance, and encapsulation.

The graphical user interface (GUI) provides an intuitive and user-friendly experience, guiding users through each step of the ATM transaction process. The GUI elements are designed to be responsive and provide clear feedback to users regarding the status of their transactions.

The system also incorporates a database to store and retrieve user account information securely. The database maintains the account balances, transaction history, and other relevant data. We have implemented proper data validation and encryption techniques to ensure the confidentiality and integrity of user information.

## Repository Structure

The repository is structured as follows:

- `src/`: This directory contains the source code for the ATM project, including the C# files, classes, and any necessary libraries.

- `docs/`: Here, you can find the documentation related to the project, including system design diagrams, GUI wireframes, and instructions for running the application.

- `database/`: This directory contains the necessary files and scripts for setting up and configuring the database used by the ATM system.

- `LICENSE`: The license file specifying the terms and conditions for using our project.

- `README.md`: The file you are currently reading, providing an overview of the project, its features, and instructions for getting started.

## Getting Started

To get started with the ATM project, please refer to the documentation in the `docs/` directory. It contains step-by-step instructions on setting up the database, compiling and running the application, and a comprehensive user guide to understand and utilize the ATM system effectively.

## Contributing

We welcome contributions to our ATM project! If you have any ideas, bug fixes, or enhancements, please feel free to open an issue or submit a pull request. We appreciate your interest in improving our project.

We hope you find our ATM system helpful and reliable for your banking needs!
