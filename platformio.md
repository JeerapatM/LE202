# นายจีรพัฒน์ มูลตรีศรี 6310680035
## ขั้นตอนการติดตั้งโปรแกรม
1. download โปรแกรม git ผ่าน link ด้านล่าง  
=========================================================================================  
https://git-scm.com/download/win  

2. เปิด command prompt ในคอมพิวเตอร์(มีอยู่แล้ว) แล้วนำคำสั่งด้านล่างไปกรอกใน command prompt  
=========================================================================================  
git clone https://github.com/choompol-boonmee/iotset1.git    
3. รอสักครู่จนกว่าคอมพิวเตอร์จะ downlaod ครบ 100%    
4. กรอกคำสั่งด้านล่างเพื่อทำการ check ไฟล์ที่ download มา
=========================================================================================  
cd iotset1/examples  
=========================================================================================  
dir  
จะปรากฎให้เห็นไฟล์ทั้งหมด ดังภาพ  
![dir](https://user-images.githubusercontent.com/98943413/153716012-2b5cb6ae-b68e-48a3-93a5-1cfa516aebef.jpg)  
5. เป็นอันเสร็จสมบูรณ์ ซึ่งก็สามารถ run โปรแกรมที่โชว์อยู่ได้ทั้งหมดผ่านคำสั่งด้านล่าง  
-ยกตัวอย่าง run ex01  
=========================================================================================  
cd iotset1/examples/ex01
=========================================================================================  
pio run
