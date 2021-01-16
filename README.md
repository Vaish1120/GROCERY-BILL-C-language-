# GROCERY-BILL-C-language-
As we go shopping, We see the cashier generates a bill after he scans or enters a code for each item we purchase. We pay the bill and take the receipt home. Basically, there is 
a file which contains the code and the price for all items in the store. For each day, we can know how many items of the same category were sold to different customers.
We can also know the total amount earned at the end of the day after selling a particular item to many different customers. The code "main.c"
can  carry out the job described above, in general terms. The details of this task are stated in the following paragraphs.
Note that several examples are provided on following pages in order to explain and guide you in understanding your task and how to approach it. This problem is designed to 
examine your understanding of file processing, and dynamic memory allocation and linked list concepts and techniques, in addition to other programming techniques. 
Details: A grocery store needs a computer program to help keep track of inventory and price data. The program must work by processing all the customer transactions
gathered during each day. At the beginning of the day the program logic is started and all initialization steps are carried out before processing any customers.
The initialization steps require inputting data from two files that provide numbers and name strings for various categories of goods that are sold by the grocery store.
This data is referenced throughout the program. You should review the example data and notes in Use-Case 1 (Input File Name: CategoryName.dat) and Use-Case 2
(Input File Name: CodeNamePrice.dat). For each customer, the cashier processes items in the order received – you might recall how each item is scanned for a barcode 
and the number of items of the same kind is entered. After the last item is processed for a given customer, the cashier triggers generation of a transaction receipt. 
This receipt is sorted by an item code, and states the name, price/item, number of items and total cost for that item (or group of items if more than one) and which,
in summary, then lists the total number of items of all types (or codes) purchased and the total purchase price for the complete transaction.
Usually this would be done using a cash register, but for this problem we simulate data entry through an input file and output using standard output. 
You should review the example data and notes in Use-Case 3 (Input File Name: DailyTransactions.dat). Note that the order of items processed is not sorted; 
as it is inputted, it must be sorted by the item code, preparing for the next step. After the final record of items input, a Code value of 000 indicates 
the end of the transaction listing. For every customer, the transaction receipt generated looks like the output shown in Use-Case 4. Each line consists of 
various fields, each of fixed size, following a fixed format spacing shown in Use-Case 4. Each line consists of a Code (3 digit number from 100 to 888),
Item Name string (16 characters, including blanks), Price per item, number of items sold, and the total item cost (Price x number of items sold). 
This output is just sent to the standard device.
