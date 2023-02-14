# Book_Shop_Bot
## In this project, we perform the following tasks

- read **Config.xlsx** file
- build **BooksDT** 
- loop through each file in **Monthly_Data** folder
- fetch BookRecords
- loop through each **BookRecord**
- assign BookRecord data to **BookName**, **ShopName**, **Sales**, **Month** variables
- add datarow (BookName, ShopName, Sales, Month variables) to **BooksDT**
- split BooksDT into **list_BooksDT** using **LINQ** query
- loop thorugh each **BookDT**
- fetch **SheetName** from **BookDT**
- remove **BookName** data column from **BookDT** 
- write **BookDT** to **output.xlsx**
- open browser 
- upload output.xlsx
- click on submit
- click ok
- close browser

### Key takeaways
- use of RegEx 
- **split** **datatable** into multiple datatables using LINQ queries
- string manipulations

