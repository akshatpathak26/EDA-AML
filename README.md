# Anti-Money Laundering (AML) Data Analysis (Hackathon Project)

This project focuses on performing Exploratory Data Analysis (EDA) on a financial transaction dataset to identify potential patterns and anomalies related to money laundering activities. The analysis aims to uncover suspicious patterns, visualize data, and provide insights that can aid in the detection and prevention of money laundering.

## Dataset

The dataset used in this project contains financial transaction records with the following features:

- `Timestamp`: The timestamp of the transaction
- `From Bank`: The sending bank account
- `To Account.1`: The receiving bank account
- `Amount Received`: The amount received in the transaction
- `Receiving Currency`: The currency of the received amount
- `Amount Paid`: The amount paid in the transaction
- `Payment Currency`: The currency of the paid amount
- `Payment Format`: The format of the payment (e.g., Reinvestment, Cheque)
- `Is Laundering`: A binary indicator for whether the transaction is classified as money laundering (0 or 1)

## Exploratory Data Analysis

The EDA process involved several steps, including:

1. **Data Understanding**: Familiarizing with the dataset and understanding the meaning of each feature.
2. **Data Cleaning**: Handling missing values, removing duplicates, addressing inconsistencies, and dealing with outliers.
3. **Exploratory Analysis**: Performing statistical analysis, visualizing data distributions, and identifying potential patterns and anomalies.
4. **Feature Engineering**: Deriving new features or transforming existing ones to better capture relevant information.

## Key Findings

During the EDA process, several insights and patterns were uncovered:

- Transactions carried out using ACH (Automated Clearing House) payment format were more prevalent among the identified money laundering cases.
- Late-night or odd-hour transactions (between 12 AM and 5 AM) exhibited higher rates of suspicious activity.
- Round number transactions (e.g., multiples of $10,000) were observed, which could indicate structuring schemes to avoid reporting thresholds.
- Certain days of the week, such as Saturdays, showed increased money laundering activity.
- Geographic and currency-based anomalies were explored to uncover potential high-risk locations or currencies associated with money laundering.

## Visualizations

The project includes various visualizations to aid in the analysis and presentation of findings, such as:

- Time-series plots to visualize the rapid movement of funds
- Histograms and bar charts to analyze the distribution of transaction amounts and payment formats
- Geographic maps to identify geographical anomalies (if location data is available)
- Network graphs to visualize relationships between accounts or parties involved in transactions

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/akshatpathak26/EDA-AML.git`
2. Download the dataset and place it in the `https://www.kaggle.com/datasets/ealtman2019/ibm-transactions-for-anti-money-laundering-aml` directory.
4. Run the Jupyter Notebook: `jupyter notebook` and navigate to the appropriate notebook file.


## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [Pandas](https://pandas.pydata.org/) for data manipulation and analysis
- [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) for data visualization


Feel free to modify and expand this README based on your specific project details, additional libraries used, and any other relevant information you would like to include.
