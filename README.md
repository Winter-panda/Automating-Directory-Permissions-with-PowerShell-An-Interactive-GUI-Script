# Automating Directory Permissions with PowerShell: An Interactive GUI Script

This PowerShell script provides an intuitive graphical user interface (GUI) to automate the process of managing directory permissions. The script verifies directory paths, checks security groups, and ensures proper inheritance settings, making it an invaluable tool for IT administrators and system managers.

## Features

- **Interactive GUI**: User-friendly interface created with Windows Forms to streamline permission management.
- **Path Validation**: Ensures the provided directory path is valid before proceeding.
- **Group Security Management**: Lists security groups with read-only and read-write access.
- **User Permission Assignment**: Allows selecting a group and assigning permissions to a specified user.
- **Inheritance Check**: Verifies if permissions inheritance is enabled; if not, checks for necessary explicit permissions.

## How to Use

1. **Enter the Directory Path**: Provide the path of the directory you want to manage.
2. **Validate the Path**: Click the "Validate Path" button to ensure the path is correct.
3. **Select Security Groups**: The script lists the security groups with read-only and read-write permissions.
4. **Specify the User**: Enter the user to whom the permissions will be assigned.
5. **Assign Permissions**: Click the "Add Rights" button to apply the permissions to the user.

## Prerequisites

- PowerShell 5.1 or later
- Active Directory module for PowerShell
- Windows Forms assembly

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/yourrepository.git
    ```
2. Run the script:
    ```bash
    cd yourrepository
    ./yourpowershellscript.ps1
    ```

