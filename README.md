To detect online payment fraud using machine learning, we must first train a model capable of classifying transactions as fraudulent or non-fraudulent. This necessitates the utilization of a dataset containing pertinent information regarding online payment fraud, enabling us to discern the characteristics indicative of fraudulent transactions. To accomplish this objective, I have obtained a dataset from Kaggle, comprising historical data on fraudulent transactions, which can be leveraged to identify fraud in online payments. Below is a summary of all the columns present in the dataset being utilized:

- **step:** Represents a unit of time, with each step equivalent to one hour.
- **type:** Denotes the type of online transaction.
- **amount:** Signifies the monetary value of the transaction.
- **nameOrig:** Identifies the customer initiating the transaction.
- **oldbalanceOrg:** Indicates the balance prior to the transaction for the originating customer.
- **newbalanceOrig:** Reflects the balance subsequent to the transaction for the originating customer.
- **nameDest:** Specifies the recipient of the transaction.
- **oldbalanceDest:** Denotes the initial balance of the recipient before the transaction.
- **newbalanceDest:** Represents the updated balance of the recipient after the transaction.
- **isFraud:** Binary indicator denoting whether the transaction is fraudulent or not.
