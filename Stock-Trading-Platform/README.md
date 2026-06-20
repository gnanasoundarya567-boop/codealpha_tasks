### Stock Trading Platform

A console-based Java application that simulates a basic stock market trading environment. Users can track a specific stock, manage a virtual cash balance, buy and sell shares, and view their real-time investment portfolio.

### 🚀 Features

*   **Real-time Metrics**: Displays current stock name, stock price, and available cash balance.
*   **Buy/Sell Orders**: Validates cash balance or available shares before executing trades.
*   **Portfolio Tracker**: Summarizes owned shares, total portfolio value, and remaining liquid cash.
*   **Interactive CLI**: Menu-driven interface using standard command-line inputs.

### 📋 Prerequisites

Before running this project, ensure you have the following installed:

*   **Java Development Kit (JDK)**: Version 8 or higher.
*   A command line interface (Terminal or Command Prompt) or an IDE like IntelliJ IDEA, Eclipse, or VS Code.

### ⚙️ How to Run

1.  **Save the File**  
    Save the code locally in a file named exactly `StockTradingPlatform.java`.
2.  **Compile the Source Code**  
    Open your terminal, navigate to the folder where you saved the file, and execute:
    
    bash
    
        javac StockTradingPlatform.java
        
    
    Use code with caution.
    
3.  **Run the Program**  
    Launch the application using:
    
    bash
    
        java StockTradingPlatform
        
    
    Use code with caution.
    

### 💡 Example Usage

text

    ===== STOCK TRADING PLATFORM =====
    Stock: TCS
    Price: Rs.3500.0
    Balance: Rs.100000.0
    1. Buy Shares
    2. Sell Shares
    3. View Portfolio
    4. Exit
    Enter Choice: 1
    Enter shares to buy: 10
    Purchase Successful
    
    ===== STOCK TRADING PLATFORM =====
    Stock: TCS
    Price: Rs.3500.0
    Balance: Rs.65000.0
    1. Buy Shares
    2. Sell Shares
    3. View Portfolio
    4. Exit
    Enter Choice: 3
    
    ===== PORTFOLIO =====
    Stock Name: TCS
    Shares Owned: 10
    Portfolio Value: Rs.35000.0
    Balance: Rs.65000.0
    

Use code with caution.

### 🛠️ Built With

*   **Java** - Core object-oriented logic.
*   **java.util.Scanner** - Handles live menu selection and numeric user inputs.
