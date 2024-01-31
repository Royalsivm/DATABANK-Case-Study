# SQL Case Study  [ Data Bank]
 
# INTRODUCTION:
Neo-Banks are a recent development in the financial sector; they are new banks that solely operate online.
I believed that there should be some kind of connection between the digital world, these new age institutions, and cryptocurrencies.
So I made the decision to start a new project called Data Bank! 
Customers of Data Bank receive cloud data storage allotments that are directly related to the balances in their accounts. The Data Bank team needs your assistance since this business model comes with some intriguing drawbacks.
This case study focuses on metrics calculations, business growth, and smart data analysis to assist the company more accurately estimate and plan for the future.


# SCHEMA USED

## regions
region_id	int,
region_name	varchar

## customer_transactions
customer_id	int,
txn_date	date,
txn_type	varchar,
txn_amount	int

## customer_nodes
customer_id	int,
region_id	int,
node_id	int,
start_date	date,
end_date	date

![image](https://github.com/Royalsivm/DATABANK-Case-Study/assets/153700930/5784cf45-c918-4537-b8e2-1ff6fa61ddb5)


## CASE STUDY QUESTIONS

1.	How many different nodes make up the Data Bank network?
2.	How many nodes are there in each region?
3.	How many customers are divided among the regions?
4.	Determine the total amount of transactions for each region name.
5.	How long does it take on an average to move clients to a new node?
6.	What is the unique count and total amount for each transaction type?
7.	What is the average number and size of past deposits across all customers?
8.	For each month - how many Data Bank customers make more than 1 deposit and at least either 1 purchase or 1 withdrawal in a single month?

 


 

