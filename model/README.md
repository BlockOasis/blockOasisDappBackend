# Project Documentation

This directory contains the core modules of our financial and claims management system. Below is an overview of each file and its role in the project.

## Files Overview

### 1. `bank_db.py`
This module contains the `BankDatabase` class, which is responsible for managing all banking-related operations. It includes functionalities such as depositing, withdrawing, transferring funds, and querying balances for different wallet addresses.

### 2. `claims_db.py`
This file defines the `ClaimsDatabase` class. This class handles the storage, creation, and management of claims. It includes methods for creating new claims, disputing claims, finalizing claim statuses, and retrieving claim information based on different criteria.

### 3. `model.py`
The `model.py` file is central to the system, defining the data models used across the application. It includes classes like `User`, `Claim`, `IoTDevice`, `WaterUsageRecord`, `Dispute`, `ValidatorNode`, and `AggregatorNode`. Each class is equipped with attributes and methods specific to its functionality.

### 4. `user_db.py`
In `user_db.py`, the `UsersDatabase` class is defined. This class focuses on user management, including creating and updating user information, managing user claims and disputes, and retrieving user data.

## Development and Usage

Each module is designed to be standalone, interacting with others through well-defined interfaces. They can be imported and utilized in other parts of the application as needed.

### Setting Up
- Ensure Python 3.8 or higher is installed.
- Install required packages: `pydantic` for data validation and `typing` for type annotations.

### Integration
- Import these modules into your main application file or other modules as required.
- Use the classes and methods provided to manage bank transactions, user data, and claims.

## Contributing
Contributions to enhance these modules are welcome. Please follow the standard pull request process and ensure that your code adheres to the project's coding standards.

## Support
For any queries or issues, please open an issue in the project repository or contact the project maintainers.
