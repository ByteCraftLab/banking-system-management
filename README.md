# C++ Banking System

A simple console-based banking system written in C++. This project allows you to manage bank user accounts, including viewing account details, adding new users, and storing user data such as account name, account number, and balance.

## Features

- **Add New Users**: Create and store new bank accounts with unique account numbers.
- **View Accounts**: Display details of user accounts (account name, number, and balance).
- **Data Storage**: Stores user account information in memory (extendable to file/database).
- **Basic Transactions**: (Extendable) Deposit and withdraw operations.

## Getting Started

### Prerequisites

- C++ compiler (e.g., g++, Visual Studio, clang)
- Make or CMake (optional, for building)

### Building

1. Clone the repository:
   ```bash
   git clone https://github.com/ByteCraftLab/cpp-banking-system.git
   cd cpp-banking-system
   ```
2. Compile the project:
   ```bash
   g++ -o banking main.cpp
   ```
3. Run the application:
   ```bash
   ./banking
   ```

### Usage

- Follow the on-screen menu to add users, view accounts, and perform operations.

## Project Structure

```
cpp-banking-system/
│
├── main.cpp        # Main application source code
├── README.md       # Project overview and instructions
├── LICENSE         # License information
└── ...             # Other files (headers, modules, etc.)
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

See [LICENSE](LICENSE) for details.

## Author

ByteCraftLab
