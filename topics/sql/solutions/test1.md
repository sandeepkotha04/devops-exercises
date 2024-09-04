**1. INSERT**
```sql

INSERT INTO students (student_id, name, email, enrollment_date) VALUES (1, 'John Doe', 'john.doe@example.com', '2024-09-01');


INSERT INTO products (product_id, product_name, price) VALUES (101, 'Laptop', 799.99);
INSERT INTO products (product_id, product_name, price) VALUES (102, 'Smartphone', 499.99);
INSERT INTO products (product_id, product_name, price) VALUES (103, 'Tablet', 299.99);
**2. UPDATE**

UPDATE employees SET email = 'new.email@example.com' WHERE employee_id = 5;
UPDATE products SET price = 450.00 WHERE product_id = 102;
**3. DELETE**

DELETE FROM orders WHERE order_id = 10;
DELETE FROM customers WHERE status = 'inactive';
**4. ALTER**

ALTER TABLE users ADD COLUMN birthdate DATE;
ALTER TABLE contacts RENAME COLUMN address TO home_address;
**5. RENAME**

ALTER TABLE old_employees RENAME TO new_employees;
ALTER TABLE inventory RENAME TO stock;
