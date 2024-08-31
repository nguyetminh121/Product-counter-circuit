# Product-counter-circuit
GIỚI THIỆU
"Mạch đếm lên sản phẩm" là mạch điện tử để đếm số lượng sản phẩm trong quá trình sản xuất. 
Mục tiêu của đề tài là thiết kế một hệ thống đếm chính xác, hiệu quả nhằm cải thiện quy trình sản xuất và kiểm tra hàng hóa.

MÔ TẢ

YÊU CẦU PHẦN CỨNG
+ IC LM358
+ IC NE555
+ IC 74LS90
+ IC 74LS47
+ Led 7 đoạn (anode chung)
+ điện trở
+ button
+ Led đơn
SCHEMATIC
![image](https://github.com/user-attachments/assets/60112aaf-e7df-47b6-acbf-34f3db558013)

![image](https://github.com/user-attachments/assets/cc42bf97-4ef9-4235-a1a2-a3db96cb8033)

#Using an LM358 can build a sensor unit with an infrared LED and a
photodiode. At the same time, the IC NE555 is used to generate
pulses, which are then fed into the 74LS90 counter to count the
pulses and trigger the 74LS47 to convert BCD to a 7-segment LED
display to show the results.
