# **Expense Tracker CLI App**

An easy-to-use, command-line interface (CLI) application for tracking expenses. This tool is perfect for keeping a log of your daily expenses, organizing them by categories, and getting a quick summary of your spending habits.

---

## **Features**
- **Add Expenses**: Log your daily expenses with a description, amount, and category.
- **View Expenses**: Display all recorded expenses or filter by category.
- **Delete Expenses**: Remove an expense entry if needed.
- **Summarize Expenses**: Get a total of your spending across all categories.
- **Error Handling**: Robust error-handling mechanisms ensure smooth operation.

---

## **Technologies Used**
- **Language**: [Rust](https://www.rust-lang.org/)

---

## **Installation**
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/jennaose/Projects.git
   cd Projects/expense-tracker
   ```
2. Ensure you have Rust installed. If not, install it [here](https://www.rust-lang.org/tools/install).

3. Build and run the application:
   ```bash
   cargo build
   cargo run
   ```

---

## **How to Use**
1. Run the application using:
   ```bash
   cargo run
   ```
2. Choose an option from the menu:
   - **1**: Add an expense.
   - **2**: View all expenses.
   - **3**: Delete an expense.
   - **4**: Summarize expenses.
   - **5**: Exit the application.

3. Follow the prompts to input data, view summaries, or manage your expense records.

---

## **Project Structure**
```
expense-tracker/
├── src/
│   ├── main.rs          # Entry point for the app
│   ├── expense.rs       # Handles expense logic (e.g., add, delete, view)
│   ├── menu.rs          # CLI menu and user interaction
│   └── error.rs         # Custom error handling (if applicable)
├── Cargo.toml           # Dependencies and project metadata
└── README.md            # Project documentation
```

---

## **Future Enhancements**
- Add **persistent storage** for saving expenses (e.g., saving to a file or database).
- Implement **expense reports** with visual summaries.
- Support **multiple currencies** and exchange rate conversions.
- Create a **web version** or GUI for better accessibility.

---

## **Contributing**
Contributions are welcome! If you'd like to contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push the branch:
   ```bash
   git push origin feature-name
   ```
4. Open a pull request on GitHub.

---


## **Acknowledgements**
Special thanks to my mentor and the Rust community for guiding me through this project. 😊

Feel free to reach out with feedback or suggestions! 

---

### **Contact**
- Email: oseghalejennifer13@gmail.com
- Twitter: @jennaoseghale
