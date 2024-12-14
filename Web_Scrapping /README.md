**Amazon Product Scraper**

**Description**

The Amazon Product Scraper is a Python script that enables users to dynamically search for products on Amazon and retrieve key details such as product names, prices, and ratings. The scraped data is organized into a tabular format and saved as an Excel file. This script is designed to be robust, handling dynamic search queries and accounting for missing data.


**Features**:

Dynamic Search Query: Enter any product name to perform a search.

Data Scraping: Extracts:

Product Name

Price (in INR)

Product Ratings

Save to Excel: Automatically saves the extracted data to an Excel file with the search query as part of the filename.

Preview Data: Displays the first few rows of scraped data for quick verification.



**Techniques Used**:

The script uses Web Scraping to fetch and parse the content of Amazon's search results page. Key techniques include:

HTTP Requests: Sending requests to Amazon using the requests library to fetch the webpage content.

HTML Parsing: Using BeautifulSoup to navigate and extract specific elements from the HTML structure of the page.

Pattern Matching: Leveraging regular expressions (re module) to extract specific details like numeric ratings from text.

Data Organization: Using pandas to structure and save the extracted data in an Excel-friendly format.



**Libraries Used:**

The script employs the following Python libraries:

requests: To send HTTP requests and retrieve webpage content.

BeautifulSoup4 (bs4): For parsing and extracting data from HTML.

pandas: To create, manipulate, and export tabular data.

re: For regular expression operations, such as extracting numerical data from text.

openpyxl: Used implicitly by pandas for saving data to Excel files.



**Usage**:

Clone the repository and navigate to the script's directory.

Run the script

Enter the product name when prompted (e.g., "laptop").

The script will scrape the first page of Amazon search results for the given query.

The data will be saved in an Excel file named Amazon_<query>.xlsx in the current directory.



**Code Workflow**

Search Query Preparation: Converts user input into a URL-friendly format.

Request and Response: Sends a GET request to Amazon and checks the response status.

HTML Parsing: Extracts product names, prices, and ratings from the HTML content.

Data Storage: Saves the scraped data into a DataFrame and exports it to an Excel file.

Preview: Displays the first five rows of the data in the console for verification.


**Sample Input**:
Laptop
**Sample Output**
0  Lenovo Legion Pro 7 Intel Core i9-14900HX 16" ...    2,89,990    3.5

1  Lenovo [Smartchoice LOQ 12th Gen Intel Core i5...      68,990    3.9

2  Lenovo Legion 5 Intel Core i7-14650HX 16" (40....    1,29,690    3.4
