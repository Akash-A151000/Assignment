## Answers

#### Question 1

In The provided image the relationship between the "Product" and "Product Category" tables is:

- There is a field called category_id which represents foreign key that holds the reference to the primary key (id) of the "Product_Category" Table. It establishes the association between a product and its category.

#### Question 2

To ensure that each product in the "Product" table has a valid category assigned to it, you would typically use a foreign key constraint. A foreign key is a field in a database table that is used to establish a link between the data in two tables.

- In the Picture, the category_id column in the "Product" table is a foreign key that references the category_id primary key in the "Category" table.

By using foreign key constraints, you ensure that each product in the "Product" table must have a valid category assigned to it.

#### Question 3

I have attached a schema.prisma file written using Prisma, an ORM.
