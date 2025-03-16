# goit-rdb-hw-03

## p1-1
SELECT * FROM products;
![image](https://github.com/user-attachments/assets/ff96e69a-53b4-4c2e-bb2a-6cb7a47da4f3)

## p1-2
SELECT name, phone FROM shippers;
![image](https://github.com/user-attachments/assets/b721a517-2814-49e1-8ff8-30121040de2a)

## p2
SELECT 
    AVG(price) AS average_price, 
    MAX(price) AS max_price, 
    MIN(price) AS min_price 
FROM products;
![image](https://github.com/user-attachments/assets/659c0b85-fec7-4865-a09b-5bc76508eca4)

## p3
SELECT DISTINCT category_id, price 
FROM products 
ORDER BY price DESC 
LIMIT 10;
![image](https://github.com/user-attachments/assets/5ad8d744-15f1-4725-8d2c-e269a8540e15)

## p4
SELECT COUNT(*) AS product_count 
FROM products 
WHERE price BETWEEN 20 AND 100;
![image](https://github.com/user-attachments/assets/fee768af-f680-4532-a4fb-e5f1fc85143c)

## p5
SELECT 
    supplier_id, 
    COUNT(*) AS product_count, 
    AVG(price) AS average_price 
FROM products 
GROUP BY supplier_id;
![image](https://github.com/user-attachments/assets/2f4ed522-b6f9-4625-9a9b-35876180bd95)
