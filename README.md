# Expense Tracker
This project is designed to help users track their expenses easily and effectively. It allows users to add, categorize, and visualize their expenses over time. With an intuitive interface built using Streamlit, users can quickly input their expenses and see summaries and visualizations of their spending patterns. This project is awesome and helps in managing personal finances efficiently.
screenshot :
![expenses tracker ](https://github.com/user-attachments/assets/2ef2ec46-2bf6-42dd-a0fd-afa1492816cd)

Tech Stack: Streamlit, Pandas

Features: Input expenses, visualize data, and receive immediate feedback.

Why Use It: Simple and intuitive interface for quick expense tracking.

Enhancement Ideas: Implement data persistence, add advanced filtering options, or integrate with financial APIs.

## How it Works ?
The Expense Tracker application is built using Streamlit, a powerful and easy-to-use Python framework for building web applications. Here's a step-by-step explanation of how the project works:

1. **User Input**: Users can input their expense details, including description, amount, category, and date.
2. **Data Storage**: Expenses are temporarily stored in the session state during the user's session. For persistence, an SQLite database can be integrated.
3. **Visualization**: The app provides a summary of total expenses and displays expenses by category in a bar chart.
4. **Feedback**: Users receive immediate feedback upon adding an expense, and the app updates the visualization dynamically.

## Libraries used
- **Streamlit - Version 1.10.0**: For creating the web application.
- **Pandas - Version 1.4.2**: For data manipulation and analysis.
## How to configure
1. **Clone the Repository**:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```
2. **Create a Virtual Environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
3. **Install Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```
## How to Run
1. **Run the Streamlit Application**:
    ```sh
    streamlit run expense_tracker.py
    ```
2. **Access the Application**:
    - Open your web browser and navigate to `http://localhost:8501`.
3. **Use the Application**:
    - Input your expenses and visualize the data.
  
   
