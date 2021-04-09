# interviews

## SQL Exercise

We have an online grovery store. Customers can order grocery items and they receive a bill for their order that looks like this:

![Image of SO](./diagrams/SO_Example.png)

The data is contained in a SQLITE database. 

![ERD](./diagrams/ERD.png)

You can access the database [here](https://sqliteonline.com/#fiddle=333b56f2bab06278f24056be2125d86ea1711e66047caa6d0921ac868f0e320c).

1) Write a sql statement to show 
    - all service order headers

        ![ERD](./diagrams/so_headers.png)

    - all service order numbers with the customer name

        ![ERD](./diagrams/so_headers.png)

    - service order 1234 details 
        - service order number
        - customer name
        - product name
        - qty 
        - price
        - total for the line

        ![ERD](./diagrams/SO_1234_details.png)
    - the total invoice price for each service order

        ![ERD](./diagrams/SO_1234_details.png)

    - the max price paid for an Apple

        ![ERD](./diagrams/SO_1234_details.png)

2) Look at the details for so_nnumber = 1237. Notice there is only one line item, but it has been updated. Write a statement to show
    - the most recent version of this line item

        ![ERD](./diagrams/most_recent_line.png)
