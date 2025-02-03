# README.md

# Bash DBMS

A simple database management system implemented in Bash. This project provides functionalities to create, manage, and manipulate databases and tables through a command-line interface.

## Project Structure

```
Project-bash
├── src
│   ├── main.sh          # Entry point of the application
│   ├── config.sh        # Configuration variables
│   ├── utils            # Utility scripts
│   │   ├── menu.sh      # Menu display functions
│   │   └── validators.sh # Input validation functions
│   └── operations       # Database operations
│       ├── database.sh  # Database management functions
│       ├── table.sh     # Table management functions
│       └── record.sh    # Record management functions
├── data
│   └── databases        # Directory for database files
├── install.sh           # Setup script
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
   ./install.sh
   ```

## Usage

To start the application, run:

```bash
./src/main.sh
```

Follow the on-screen instructions to navigate through the database management system.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.
