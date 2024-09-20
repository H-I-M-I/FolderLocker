# Folder Locker Software

This repository contains the **Folder Locker Software**, a desktop application written in Java that allows users to lock and secure folders on their PC. The software ensures that your sensitive data remains protected by restricting access to selected folders. 

## Features
- **Folder Locking and Unlocking**: Password-protect any folder on your system to prevent unauthorized access.
- **System Tray Integration**: Minimize the application to the system tray for convenient access and control.
- **Security Handling**: Ensures password protection and handles encryption for secure access.

## Code Structure

The project consists of three main components:

1. **Main.java**  
   - The entry point for the application. It initializes the GUI and manages the overall functionality, such as folder selection, locking, and unlocking actions.

2. **FolderLockerSecurityHandler.java**  
   - This file contains the core logic for securing folders. It handles password protection, encryption, and validation to ensure that only authorized users can unlock and access the folder.

3. **Tray.java**  
   - Implements the system tray functionality, allowing users to minimize the app to the system tray for quick access. This feature enhances usability by providing options to lock/unlock folders directly from the tray.

## How to Use

1. **Clone the repository**  
   ```bash
   git clone <repository-link>
   ```

2. **Compile and run the program**  
   You can compile and run the software using any Java IDE (e.g., IntelliJ IDEA, Eclipse) or using the command line:
   ```bash
   javac Main.java
   java Main
   ```

3. **Locking a Folder**  
   - Select a folder from the user interface.
   - Set a password for the folder.
   - The folder will be locked and access will be restricted.

4. **Unlocking a Folder**  
   - Select the locked folder.
   - Enter the password to unlock it.
   - Once unlocked, you can access the folder normally.

## Future Enhancements
- Adding multi-user support.
- Password recovery options.
- Support for locking multiple folders simultaneously.

