# AI-Powered Personal Finance Tracker

This is an **AI-Powered Personal Finance Tracker** built with Streamlit. The application allows users to track their financial transactions, categorize them, and visualize their spending habits. It provides a user-friendly interface to add transactions, display a transaction history, and generate various financial charts to analyze income and expenses.

## Features

- **Add Transactions**: Enter transaction details including date, amount, category, and description.
- **Transaction History**: View a detailed list of all added transactions.
- **Expense Breakdown**: Visualize your expenses using a pie chart for categories like Food, Rent, Transport, etc.
- **Income vs Expense Bar Chart**: Compare your total income, expenses, and savings with a bar chart.

## Technologies Used

- **Streamlit**: For creating the web application.
- **Pandas**: For data management and processing.
- **Matplotlib**: For generating visualizations.
- **Python 3.x**: The programming language used for development.

## Installation

To run this application locally, follow the steps below:

### Prerequisites

Make sure you have Python 3.7 or higher installed on your machine.

### Clone the Repository

```bash
git clone https://github.com/your-username/finance-tracker.git
cd finance-tracker
```

### Install Required Packages

Use `pip` to install the necessary dependencies:

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available, manually install these dependencies:

```bash
pip install streamlit pandas matplotlib
```

### Run the Application

To launch the application, run the following command:

```bash
streamlit run app.py
```

This will start a local server, and you can view the app in your browser at `http://localhost:8501`.

## Customization

- You can add your own logo to the app by placing an image file (e.g., `logo.png`) in the same directory as the app and modifying the `st.image()` call in the `app.py` file.
- The categories of transactions can be customized based on your needs by modifying the `category` list.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Streamlit](https://streamlit.io/) for the excellent framework that powers this app.
- [Matplotlib](https://matplotlib.org/) for the visualization library.
- [Pandas](https://pandas.pydata.org/) for the data manipulation capabilities.

