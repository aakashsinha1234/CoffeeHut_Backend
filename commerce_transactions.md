# Commerce Transactions

The `commerce_transactions.md` file tracks every transaction made by customers on the CoffeeHut website. It logs successful and failed transactions, payment method used, user ID, and other relevant information.

## Transaction Log Structure

Each entry in this file represents a unique transaction and includes the following details:

- **Order ID**: Unique identifier for each order (e.g., ORD12345).
- **User ID**: Unique identifier for the customer making the transaction.
- **Product IDs**: List of product IDs for items purchased.
- **Total Amount**: The total value of the transaction (including any discounts).
- **Payment Method**: The payment option used by the customer (e.g., Credit Card, CoffeeHut Wallet).
- **Transaction Status**: Whether the transaction was successful, failed, or pending.

---

## Example Transactions

### Transaction 1
- **Order ID**: ORD12345
- **User ID**: U123
- **Products**: Espresso Coffee Machine, Organic Coffee Beans
- **Total Amount**: $199.99
- **Payment Method**: Credit Card
- **Status**: Success

### Transaction 2
- **Order ID**: ORD12346
- **User ID**: U124
- **Products**: Latte Coffee Mug, Coffee Grinder
- **Total Amount**: $49.98
- **Payment Method**: CoffeeHut Wallet
- **Status**: Success

### Transaction 3
- **Order ID**: ORD12347
- **User ID**: U125
- **Products**: Espresso Coffee Machine
- **Total Amount**: $179.99
- **Payment Method**: Net Banking
- **Status**: Failed (Payment gateway error)

---

### Additional Notes:
- Each transaction entry is timestamped for accurate reporting.
- Failed transactions are flagged for review and investigation.
- The transaction data is used for financial auditing and reporting purposes.
