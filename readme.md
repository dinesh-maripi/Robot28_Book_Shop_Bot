# Book Shop Bot
> Please go through [usecase description](https://www.youtube.com/watch?v=5mwh-SLR5H0&feature=youtu.be)
---
[Book Shop Website](https://botsdna.com/BookShop/)

## In this project, we perfrom the following tasks.

1. build **DataTable** - *BooksDT*
1. loop through each file in **Monthly Data** Folder
    1. read text file and assign output to **FileText** variable
    1. perfrom **string manipulations** on **FileText** to fetch **BookRecords**
    1. loop through each **BookRecord**
        1. assign data to **BookName** **ShopName** **SalesCount** **Month** variables
        1. add data to **BooksDT** DataTable
1. Split **BooksDT** into **list_BooksDT** group by **Book Name** column using Linq query
1. loop through **BookDT**
    1. Get book name and assign it to **SheetName** variable
    1. Remove **Book Name** column from **BookDT** DataTable
    1. write data to **output.xlsx** file
1. open browser & upload **output.xlsx** file
1. close browser
1. done

### Key takeaways
- **string manipulation**
- **file uploading**
- working with Dates
- **splitting DataTable** into multiple **DataTables** using **LINQ** query
