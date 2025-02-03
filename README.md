# README.md

# Bash DBMS

A simple database management system implemented in Bash. This project provides functionalities to create, manage, and manipulate databases and tables through a command-line interface.

## Project Structure

```
Project-bash
├── src
│   ├── main          # Entry point of the application
│   ├── config        # Configuration variables
│   ├── utils            # Utility scripts
│   │   ├── menu      # Menu display functions
│   │   └── validators # Input validation functions
│   └── operations       # Database operations
│       ├── database  # Database management functions
│       ├── table     # Table management functions
│       └── record    # Record management functions
├── data
│   └── databases        # Directory for database files
├── install           # Setup script
├── .gitignore           # Git ignore file
└── README.md            # Project documentation
```

## Features

- Create, delete, and manage databases.
- Create, update, and delete tables within databases.
- Add, update, and delete records in tables.
- Input validation to ensure data integrity.

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd Project-bash
   ```

2. Run the installation script:
   ```bash
   ./install
   ```

## Usage

To start the application, run:

```bash
./src/main
```

Follow the on-screen instructions to navigate through the database management system.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.
