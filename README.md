1. (SELECT first_name FROM actor)
   UNION
   (SELECT first_name FROM customer);

   ![](./images/1.png)

2. (SELECT first_name FROM actor)
   INTERSECT
   (SELECT first_name FROM customer);

   ![](./images/2.png)

3. (SELECT first_name FROM actor)
   EXCEPT
   (SELECT first_name FROM customer);

   ![](./images/3.png)

4. - (SELECT first_name FROM actor)
     UNION ALL
     (SELECT first_name FROM customer);

     ![](./images/4.png)

   - (SELECT first_name FROM actor)
     INTERSECT ALL
     (SELECT first_name FROM customer);

     ![](./images/5.png)

   - (SELECT first_name FROM actor)
     EXCEPT ALL
     (SELECT first_name FROM customer);

     ![](./images/6.png)
