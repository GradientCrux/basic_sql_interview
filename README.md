# Interview

## Setup 



The data for this exercise is contained in a SQLITE database that you will need to load. You can do so by:
1. Cloning this repository to your local environment (HTTPS is easiset). 
2. Navigating to [sqliteonline.com](https://sqliteonline.com/)
3. Clicking File > Open DB and uploading the file from this repository "basic_sql_interview/sqlite/interview_exercise.db"
![Image of Load](./diagrams/upload_db_image.png)


## SQL Exercise
We have an online grocery store. Customers can order grocery items and they receive a bill for their order that looks like this:

![Image of SO](./diagrams/SO_Example.png)

Below is a diagram of the relationships of between the tables. 

![ERD](./diagrams/ERD.png)



1) Write a sql statement to show the **exact** table output as shown below
    -All service order headers 

        ![ERD](./diagrams/so_headers.png)

    - All service order numbers with the customer name 

        ![ERD](./diagrams/so_number_customer.png)

    - Service order 1234 details 
        - service order number
        - customer name
        - product name
        - qty 
        - price
        - total for the line

        ![ERD](./diagrams/SO_1234_details.png)
    - The total amount paid for each service order 

        ![ERD](./diagrams/order_totals.png)

    - The max price paid for an Apple

        ![ERD](./diagrams/max_apple_price.png)

2) Look at the details for so_number = 1237. Notice there is only one line item, but it has been updated. 

    ![ERD](./diagrams/duplicated_lines.png)

Write a statement to show

- The most recent version of this line item

    ![ERD](./diagrams/most_recent_line.png)
