Attributes:

User:

user_id (INT)
username (VARCHAR)
password (VARCHAR)
full_name (VARCHAR)
email (VARCHAR)
phone_number (VARCHAR)
Account:

account_id (INT)
user_id (INT)
account_number (VARCHAR)
balance (DECIMAL)
account_type (VARCHAR)
Transaction:

transaction_id (INT)
account_id (INT)
transaction_date (DATE)
amount (DECIMAL)
transaction_type (VARCHAR)
Loan:

loan_id (INT)
account_id (INT)
loan_amount (DECIMAL)
interest_rate (DECIMAL)
Bill:

bill_id (INT)
account_id (INT)
bill_amount (DECIMAL)
bill_type (VARCHAR)
Payment:

payment_id (INT)
bill_id (INT)
payment_date (DATE)
amount (DECIMAL)
Transfer:

transfer_id (INT)
sender_account_id (INT)
receiver_account_id (INT)
transfer_date (DATE)
amount (DECIMAL)
Statement:

statement_id (INT)
account_id (INT)
statement_date (DATE)
statement_details (VARCHAR)
Alert:

alert_id (INT)
account_id (INT)
alert_type (VARCHAR)
alert_date (DATE)
alert_details (VARCHAR)
Branch:

branch_id (INT)
branch_name (VARCHAR)
location (VARCHAR)
Customer Service:

service_id (INT)
branch_id (INT)
employee_name (VARCHAR)
Security Question:

question_id (INT)
question_text (VARCHAR)
Card:

card_id (INT)
account_id (INT)
card_number (VARCHAR)
expiration_date (DATE)
cvv (VARCHAR)
Interest Rate:

rate_id (INT)
account_type (VARCHAR)
interest_rate (DECIMAL)
Exchange Rate:

exchange_id (INT)
base_currency (VARCHAR)
target_currency (VARCHAR)
rate (DECIMAL)
Account Type:

type_id (INT)
account_type (VARCHAR)
