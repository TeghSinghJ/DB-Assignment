# Answers
1.Many-to-One Relationship
2.To ensure that each product in the "Product" table has a valid category assigned to it, we can use a foreign key constraint. The foreign key constraint will link the "category_id" column in the "Product" table to the "id" column in the "Product_Category" table. This ensures that every value in the "category_id" column of the "Product" table must exist in the "id" column of the "Product_Category" table.

