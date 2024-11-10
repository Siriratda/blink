# cool book
# โปรเจค Blink
โปรเจคนี้จะเป็นการทำให้ LED ในบอร์ด ESP32 ติด/ดับ
#ขั้นตอนการทำงาน
กดเข้าไปที่ Show Exaple เลือกหา blink แล้วกด Create Project ตามขั้นตอนดังรูป

![cl2](https://github.com/user-attachments/assets/994d2ee9-d728-4474-8b74-d7ba9c834c37)

# การต่อวงจร
ต่อขา GPIO5 เข้ากับ LED1
![image](https://github.com/user-attachments/assets/8c833d64-f596-4022-ae9b-d129a5651a31)

# การ Build
ทำการอัพโหลดโค้ดลงบอร์ดและ Build จะได้ผลดังรูป

![image](https://github.com/user-attachments/assets/f4ea538e-f4fd-4654-a1d3-8d584961e3b0)

# ส่วนที่ต้องปรับปรุงแก้ไข
บรรทัดที่ 102 ส่วนของ vTaskDelay ให้แก้ไข Delay จะเป็นการกำหนดให้ LED ติด/ดับ เร็วขึ้น 

![image](https://github.com/user-attachments/assets/ff44ee1b-8eac-47b7-8950-3537f2a87363)

