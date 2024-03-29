### บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3
![image](https://github.com/Chaiyapa/03376836-OOP-2566-Lab-11/assets/144195729/120f860c-e98d-4d08-9c65-8aad20a884cd)

build ได้ เพราะ สร้างคลาส Animal และคลาสลูกของมันอย่าง Dog, Fish, และ Bird ซึ่งแต่ละคลาสลูกมีเมทอด Move ที่ได้รับการโอเวอร์ไรด์ (override) จากคลาส Animal โดยแต่ละเมทอด Move ของคลาสลูกจะแสดงข้อความที่บอกถึงวิธีการเคลื่อนที่ของสัตว์แต่ละชนิด และเรียกใช้เมทอด Move ของคลาสแม่ด้วยคำสั่ง base.Move()
### บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5
![image](https://github.com/Chaiyapa/03376836-OOP-2566-Lab-11/assets/144195729/bb58f5ef-c1a3-4f06-b330-2bc17b211fcb)

Run ได้ เพราะ ใช้เมทอดของคลาสเดียวกันในลักษณะที่แตกต่างกันขึ้นอยู่กับประเภทของวัตถุที่เรียกใช้เมทอดนั้น ๆ ซึ่งเป็นเหตุผลในการทำให้เราสามารถเรียกใช้เมทอด Move() ของคลาส Animal
### อธิบายสิ่งที่พบในการทดลอง
โปรแกรมจะแสดงผล

Dog: Running on the ground.

Move successfully.

Fish: Swimming in the water.

Move successfully.

Bird: Flying in the air.

Move successfully.
