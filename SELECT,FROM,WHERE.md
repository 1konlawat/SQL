#  SELECT ดึงคอลั่ม
           SELECT name, ago
           FROM users;
แปลว่า: ดึง name ago  จากตาราง users

#  FROM   ระบุว่าข้อมูลอยู่ในตารางไหน
           SELECT *
           FROM products
แปลว่า: ดึงทุกคอลั่ม(*) จากตาราง products

#  WHERE  ใส่เงื่อนไขกรองข้อมูล
           SELECT name
           FROM employees
           WHERE deparment = 'Marketing';
แปลว่า: ดึงชื่อ จากพนักงาน ฝ่ายการตลาด 

__________________________________________________________________________________________________________________________________________________ #ตัวอย่างรวม SELECT +  FROM + WHERE

                           SELECT id , product_name , price
                           FROM products
                           WHERE price > 100;
