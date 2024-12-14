Python CRUD operations on Sales dataset

**Overview**
This repository demonstrates Python-based CRUD (Create, Read, Update, Delete) operations on a sales dataset. The dataset consists of transactional sales data and uses Pandas for data manipulation, along with Warnings for managing runtime alerts.

**Dataset Description**
The sales dataset contains the following fields:
Order ID: Unique identifier for each order.
Product: Name of the product purchased.
Quantity Ordered: Number of units ordered.
Price Each: Price per unit of the product.
Order Date: Date when the order was placed.
Purchase Address: Address where the order was delivered.

**Imported Libraries**
Pandas: Used for efficient data manipulation and analysis.
Warnings: Used to handle runtime warnings and ensure smooth execution.

**CRUD Operations**
1. Create: Insert a New Record
This function accepts parameters and appends a new record to the dataset. It performs the following steps:
Accepts parameters for the fields (Order ID, Product, Quantity Ordered, Price Each, Order Date, Purchase Address).
Checks if the dataset is available.
If the dataset is found, it appends the new record and prints a success message.
If the dataset is not found, it prints an unsuccessful message.

2. Read: Fetch a Record by Order ID
This function retrieves a record based on the given Order ID. It follows these steps:
Accepts the Order ID as a parameter.
Checks if the dataset is available.
If the dataset is found, it reads the ID and checks if the record exists.
If the record exists, it returns the associated data.
If no record is found, it prints "Not Found".
If the dataset is unavailable, it prints an unsuccessful message.

3. Update: Modify an Existing Record
This function updates the details of an existing record. The steps include:
Accepts parameters for the update.
Checks if the dataset is available.
If the dataset is found, it reads the ID to verify if the record exists.
If the record exists, it updates the relevant fields and prints a success message.
If the record does not exist, it prints an unsuccessful message.
If the dataset is unavailable, it prints an unsuccessful message.

4. Delete: Remove a Record by Order ID
This function deletes a record associated with a given Order ID. It performs the following steps:
Checks if the dataset is available.
If the dataset is found, it verifies the existence of the given ID.
If the ID exists, it removes the corresponding record and prints a success message.
If the ID does not exist, it prints an unsuccessful message.
If the dataset is unavailable, it prints an unsuccessful message.



**How to Use**
Clone the repository.
Ensure the required libraries (Pandas and Warnings) are installed.
Run the Python script and interact with the CRUD functions by passing the necessary parameters.
