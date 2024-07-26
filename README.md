# Online Payment Fraud Detection using Machine Learning

With the evolution of technology, the vast trend of online payment is tremendous. Despite online payment being advantageous and beneficial to buyers and sellers due to its ability to save time and cost, it is associated with fraudulent risks/activities. This is the reason why Online Payment Fraud Detection is very important. To do this, we will use classification algorithms to train a machine learning model to identify fraudulent and non-fraudulent payments.

## Dataset

The dataset to be used has the following columns:

- **Step**: A unit of time where 1 step equals 1 hour
- **type**: Type of transaction done
- **amount**: Total amount of the transaction
- **nameOrig**: Account that starts the transaction
- **oldbalanceOrig**: Balance of the account of the sender before the transaction
- **newbalanceOrig**: Balance of the account of the sender after the transaction
- **nameDest**: Account that receives the transaction
- **oldbalanceDest**: Balance of the account of the receiver before the transaction
- **newbalanceDest**: Balance of the account of the receiver after the transaction
- **isFraud**: The target, whether fraud or not

## Project Overview

The goal of this project is to develop a machine learning model that can accurately identify fraudulent transactions from non-fraudulent ones. The classification algorithms will be trained on the dataset provided above.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, sklearn, matplotlib, seaborn

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/online-payment-fraud-detection.git
