# ORDER BY  เรียงลำดับข้อมูล
        ASC  เรียงจากน้อยไปมาก
        DESC เรียงจากมากไปน้อย


        
    EX        SELECT first_name , last_name , age
              FROM users
              ORDER BY last_name ASC , age DESC
        เรียงตามนามสกุลก่อน แล้ว อายุมากไปน้อย

        trip: ถ้าไม่ใส่ มันจะอัตโนมัติ ให้เป็น ASC ให้อัตโนมัติ
              ORDER BT อยู่ท้าย SQL Query แปลว่าอยู่ท้ายสุด
              ใช้กับ SELECT , JOIN , หรือพวก GROUP BY
