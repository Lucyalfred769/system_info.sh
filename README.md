# Automated System Information Report Script

## Overview

This Bash script generates a detailed system information report. It allows you to choose from several types of system data to include in the report, such as CPU information, memory usage, disk usage, network configuration, and running processes. The report is formatted into a structured table and saved to a log file.

## Features

- **Customizable Reporting**: Choose specific types of system information to include.
- **Formatted Output**: Results are neatly formatted into tables for clarity.
- **Real-Time Data Collection**: Provides up-to-date information about your system.

## Prerequisites

- Bash Shell
- Common Linux utilities: `lscpu`, `free`, `df`, `ip`, `ifconfig`, `ipconfig`, `ps`

## Usage

1. **Save the Script**: Copy the script into a file, for example, `systeminfo.sh`.

2. **Make the Script Executable**:
    ```bash
    chmod +x systeminfo.sh
    ```

3. **Run the Script**:
    ```bash
    ./systeminfo.sh
    ```

4. **Follow Prompts**: The script will prompt you to choose which information to include in the report.

5. **View the Report**: The generated report will be saved to `system_report.txt`.

## Script Breakdown

1. **Log File Creation**: Sets up the log file and initializes basic information.
2. **Table Functions**: Defines functions to format the output as tables.
3. **User Input Handling**: Prompts the user to select the types of information to include.
4. **Data Collection**: Collects and formats system data based on user input.
5. **Error Handling**: Displays an error message for invalid choices.

## Troubleshooting

If you encounter issues running the script:

- **Ensure you are using a compatible Command-Line Interface (CLI)**. On Linux, use terminal emulators like GNOME Terminal or Konsole. On Windows, use Git Bash or Windows Terminal for a Unix-like experience.

- **Verify that you have the correct shell environment**. The script is designed for Bash, so running it in other shells like Command Prompt may lead to unexpected results.

- **Check for any syntax or command compatibility issues**. Different CLIs or shells may handle commands slightly differently.


## Contribution

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.


---

**Note**: Replace the placeholders and adjust the content according to your project's specific details and needs.
