# Multiplication Table Generator

A Bash script that generates customizable multiplication tables based on user input. This interactive script allows users to create both full and partial multiplication tables with various display options.

## Features

- Generate multiplication tables for any number
- Option to display full (1-10) or partial range tables
- Input validation and error handling
- User-friendly interface
- Multiple display format options
- Supports both ascending and descending order
- Implements both list-form and C-style loop demonstrations

## Requirements

- Bash shell (version 3.0 or higher)
- Unix-like operating system (Linux, macOS, etc.)

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/multiplication-table-generator.git
```

2. Navigate to the project directory:
```bash
cd multiplication-table-generator
```

3. Make the script executable:
```bash
chmod +x multiplication_table.sh
```

## Usage

Run the script:
```bash
./multiplication_table.sh
```

Follow the interactive prompts:
1. Enter the number for which you want to generate a multiplication table
2. Choose between full table (1-10) or partial table
3. If partial table is selected, specify the range
4. Choose display format (optional)
5. Select ascending or descending order (optional)


## Project Structure

- `multiplication_table.sh`: Main script file
- `README.md`: Documentation
- `LICENSE`: Project license file

## Technical Details

The script demonstrates two different loop implementation approaches:
1. List Form Loop: Uses Bash's native list-based iteration
2. C-style Loop: Implements traditional for-loop syntax

Both implementations showcase different ways to achieve the same result while maintaining code readability and efficiency.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Learning Objectives

This project helps users understand:
- Variable usage in Bash scripting
- Loop syntax and implementation differences
- User input handling and validation
- Conditional logic implementation
- Script formatting and documentation
- Interactive user interface design

## Acknowledgments

- Project created as a practical application of Bash scripting fundamentals
- Designed for educational purposes to demonstrate loop implementations and user interaction
- Inspired by the need for practical scripting exercises in learning environments
