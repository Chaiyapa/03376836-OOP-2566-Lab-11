### บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3
แก้ไขแล้ว

![image](https://github.com/Chaiyapa/03376836-OOP-2566-Lab-11/assets/144195729/ba9572fc-962f-4352-adea-b4bb0afcdade)

ไม่สามารถ Build ได้ เพราะ Derived_2.A พยายามจะสืบทอดจาก Derived_1 แต่ถูกปิดกั้นด้วยคำสั่ง sealed แก้โดยลบส่วนการทำงานของclass Derived_2 : Derived_1 ออก
### บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5
แก้ไขแล้ว

![image](https://github.com/Chaiyapa/03376836-OOP-2566-Lab-11/assets/144195729/b7b0955c-f6c8-477f-85c6-c91e37a52a1f)

ไม่สามารถ Run ได้ เพราะ Derived_2.A พยายามจะสืบทอดจาก Derived_1 แต่ถูกปิดกั้นด้วยคำสั่ง sealed แก้โดยลบส่วนการทำงานของclass Derived_2 : Derived_1 ออก
### อธิบายสิ่งที่พบในการทดลอง
โปรแกรมจะแสดงผล

Derived_1.A()

Derived_1.A()

Derived_1.A()

code

![image](https://github.com/Chaiyapa/03376836-OOP-2566-Lab-11/assets/144195729/937f1606-cf6d-4294-8fce-fc1ca77f8c76)
