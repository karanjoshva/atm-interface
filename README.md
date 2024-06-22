# atm-interface
java program for atm interface
## ATM Simulator: A Java Application

This project simulates a simple ATM (Automated Teller Machine) application written in Java. It allows users to check their balance, deposit funds, and withdraw cash.

### Getting Started

1. **Prerequisites:** You will need Java installed on your system. You can check if you have Java by running `java -version` in your terminal. If you don't have it, download and install it from the official Java website: [https://www.oracle.com/java/technologies/downloads/](https://www.oracle.com/java/technologies/downloads/)
2. **Running the Program:** 
    * Save the provided code as three separate files: `BankAccount.java`, `ATM.java`, and `ATM_Interface.java`.
    * Compile the program using the following command in your terminal:
        ```
        javac BankAccount.java ATM.java ATM_Interface.java
        ```
    * Run the program using the following command:
        ```
        java ATM_Interface
        ```

### How to Use the ATM

1. The program will welcome you and prompt you to enter your four-digit PIN (currently set to a placeholder value). 
2. Once you enter the PIN, you will be presented with a menu offering the following options:
    * Check Balance (Option 1)
    * Deposit (Option 2)
    * Withdraw (Option 3)
    * Exit (Option 4)
3. Select the desired option by entering the corresponding number (1-4) and pressing Enter.
4. Follow the on-screen instructions for each option (e.g., entering the amount for deposit or withdrawal).
5. You can continue using the ATM until you choose to exit (Option 4).

### Additional Notes

* This is a basic ATM simulation for educational purposes. It does not implement security features like real-world ATMs.
* The initial balance in the `BankAccount` class is set to a placeholder value of 10000.0. You can modify this value to simulate a different starting balance.
* The program currently uses a hardcoded PIN for simplicity. In a real ATM, PINs would be stored securely and verified against user credentials.
