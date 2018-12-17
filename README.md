# Vocab-Game เกมส์ทายความหมายศัพท์ภาษาอังกฤษ

## ![](/img/house.png)คำอธิบายโปรเจค
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ปัจจุบันภาษาอังกฤษมีความสำคัญเป็นอย่างมาก เพราะเป็นภาษาสากลที่ทั่วทั้งโลกใช้ในการติดต่อสื่อสารกันในหลาย ๆ ด้าน โดยภาษาอังกฤษประกอบไปด้วยหลายทักษะ เช่น การฟัง การอ่าน การพูด และการเขียน ซึ่งสามารถฝึกฝนได้ผ่านสื่อที่หลากหลาย นอกจากนี้กุญแจสำคัญที่ทำให้ภาษาอังกฤษสามารถเรียนรู้ได้ง่ายขึ้นนั่นคือ “คำศัพท์” หากเรารู้คำศัพท์มาก เราจะสามารถตีความ หรือรู้ความหมายได้ง่ายขึ้น ซึ่งส่งผลต่อทักษะด้านต่าง ๆ ของภาษาอังกฤษ หากเรามีการฝึกฝนทางด้านคำศัพท์มาตั้งแต่เด็กก็จะเป็นการปูพื้นฐานภาษาอังกฤษที่ดี ดังนั้นความรู้เรื่องคำศัพท์จึงเป็นเรื่องสำคัญในการเรียนรู้ภาษา โดยพวกเราได้จัดทำเกมทายคำศัพท์ภาษาอังกฤษขึ้นมา เพื่อเป็นสื่อเรียนรู้ในการฝึกฝนด้านคำศัพท์ภาษาอังกฤษ และให้ผู้ที่กำลังฝึกฝนทางด้านภาษาอังกฤษเกิดความสนุก และไม่เครียดกับการฝึกฝนด้วยตนเอง นอกจากนี้ผู้เล่นจะสามารถจดจำคำศัพท์ภาษาอังกฤษได้มากขึ้น

## วัตถุประสงค์ และเป้าหมาย
1.	เพื่อให้ผู้เล่นเกมสามารถจดจำคำศัพท์ภาษาอังกฤษได้มากขึ้น
2.	เพื่อให้ผู้เล่นได้รับความสนุกสนาน และเพลิดเพลินขณะเล่นเกมส์
3.	เพื่อให้ผู้เล่นทราบถึงคำศัพท์ระดับพื้นที่ควรรู้ในภาษาอังกฤษ
4.	เพื่อให้ผู้เล่นได้ฝึกกระบวนการความคิด และสมอง

## ประโยชน์ที่คาดว่าจะได้รับ และการนำไปใช้
1.	สามารถนำเกมส์ไปเป็นสื่อการในการเรียนรู้ทางด้านภาษาอังกฤษได้
2.	ผู้เล่นรู้สึกสนุกกับเกมส์ และไม่รู้สึกเบื่อหน่ายขณะเรียนรู้ภาษาอังกฤษ
3.	ผู้เล่นกระตือรือร้นในการเรียนรู้ทางด้านภาษาอังกฤษ

## ขอบเขต และข้อจำกัดของโปรแกรมที่จะพัฒนา
1.	ผู้เล่นสามารถเลือกได้ว่าจะตอบผิดกี่ครั้ง โดยมีให้เลือกไม่เกิน 1 - 5 ครั้ง ก่อนจะบังคับจบเกมส์
2.	สามารถนำไปใช้เป็นสื่อการสอนในระดับมัธยมศึกษาได้
3.	สามารถเล่นได้ 1 คน ต่อเกม
4.	ผู้เล่นสามารถเลือกตอบได้จากตัวเลือกทั้ง 4 ตัวเลือก
5.	ผู้เล่นสามารถเลือกเวลาได้โดยมีให้เลือกได้10-30วินาทีต่อหนึ่งข้อ
6.	คำถามอ้างอิงตาม Database เราสามารถ Randomได้
7.	ใน 1 เกม จะมีคำถามให้เลือกได้ว่าจะทำกี่ข้อโดยมีให้เลือก10-40ข้อ
8.	เสียงคำอ่านของศัพท์นั้น ๆ ในบางคำอาจฟังไม่รู้เรื่อง หรือเป็นสำเนียงที่ไม่ใช่สำเนียงของศัพท์นั้น ๆ
9.	สามารถเลือกได้ว่าจะดูเฉลยได้เลยหรือจะเลือกที่จะปิดเฉลยไว้แล้วไปค้นหาเองได้
10.	สามารถเลือกได้ว่าจะเปิดเพลงประกอบตอนเล่นได้

## Storyboard
ขั้นตอนการเปิดเกมส์มีดังนี้
- กด Import หลังจาก Clone จาก Git เสร็จ<br> 
 <a href=""><img src="img/4.PNG" width="500px"></a>
- กดเลือก Existing Gradle Project ตามด้วยปุ่ม Next<br>
 <a href=""><img src="img/5.PNG" width="500px"></a>
 <a href=""><img src="img/6.PNG" width="500px"></a>
- วิธี How to run and add library กดที่โฟลเดอร์ของเกมส์ แล้วเลือก DesktopLauncher.java คลิกขวาแล้วเลือก Run As เสร็จแล้วก็เลือก Run Configurations<br>
<a href=""><img src="img/7.PNG" width="500px"></a>
- ทำตามขั้นตอนที่ชี้ตามลูกศร คือ 1. กดเลือกที่ Arguments   2. กดเลือก Workspace    3. เลือก Assets และ 4. กด OK <br>
<a href=""><img src="img/8.PNG" width="500px"></a>
- จากนั้นกดเลือก Properties <br>
<a href=""><img src="img/9.PNG" width="500px"></a>
- จะได้หน้าต่างดังรูปแล้วคลิกที่ Java Build Path เสร็จแล้วเลือก Add External JARs จากนั้นกด Apply and Close <br>
<a href=""><img src="img/10.PNG" width="500px"></a>
- จะขึ้นหน้าต่างดังรูปจากนั้นให้เรากด Open ไฟล์ทั้งหมดในโฟล์เดอร์ <br>
<a href=""><img src="img/11.PNG" width="500px"></a>
- ทำตามขั้นตอนเดิมที่โฟลเดอร์ Vocab-Game-desktop เพื่อเล่นเกมส์ <br>
<a href=""><img src="img/12.PNG" width="500px"></a>
- เมื่อกด Java Application แล้วจะปรากฏหน้าต่างเกมส์ขึ้นมาดังรูป จากนั้นคลิกที่ปุ่ม Start เพื่อเริ่มเกมส์หรือปุ่ม Exit เพื่อออกจากเกมส์ <br>
<a href=""><img src="img/13.PNG" width="300px"></a>
- หลังจากกด Start มาแล้วจะมีหมวดหมู่คำศัพท์ให้เราเลือกเล่น ให้เราเลือกหมวดใดหมวดหนึ่งเพื่อเล่นเกมส์ <br>
<a href=""><img src="img/14.PNG" width="300px"></a>
- เมื่อเลือกหมวดคำศัพท์ที่จะเล่นแล้ว จะปรากฏหน้าต่างดังรูป ให้เรากดเลือกคำศัพท์ที่ถูกต้องได้เลย <br>
<a href=""><img src="img/15.PNG" width="500px"></a>
- ถ้าตอบถูกจะขึ้นหน้าต่างแสดงว่า Correct ให้เรากด OK เพื่อไปข้อต่อไป <br>
<a href=""><img src="img/16.PNG" width="300px"></a>
- ถ้าตอบผิดจะขึ้น Wrong ให้กด OK เพื่อเล่นข้อถัดไป <br>
<a href=""><img src="img/17.PNG" width="300px"></a>
- ถ้าเราตอบผิดเกิน 5 ข้อเกมส์จะจบทันที พร้อมเฉลยข้อที่เราทายผิดเราสามมารถเลือกกดเกมส์เพื่อเล่นอีกครั้งหรือกดออกจากเกมส์เมื่อเลิกเล่นแล้ว <br>
<a href=""><img src="img/18.PNG" width="300px"></a>
- ได้มีการเพิ่ม score สามารถดูได้ว่าเราได้คะแนนเท่าไหร่แล้ว แล้ว Best score คือเท่าไหร่ถ้าตอบผิดไม่เกินที่เรากำหนดไว้ก็จะขึ้นว่า Win<br>
<a href=""><img src="img/19.PNG" width="500px"></a>
- สามารถเลือกได้ว่าจะทายคำศัพท์กี่ข้อในแต่ละหมวด โดยมีให้เลือกตั้งแต่10ถึง40ข้อ<br>
<a href=""><img src="img/20.PNG" width="500px"></a>
- สามารถเลือกเวลาที่จะทายคำศัพท์ในแต่ละข้อได้ โดยมีให้เลือกตั้งแต่10-30วินาที <br>
<a href=""><img src="img/21.PNG" width="500px"></a>
- สามารถเลือกได้ว่าจะทายผิดได้ไม่เกินกี่ข้อในแต่ละหมวด โดยสามารถเลือกได้ตั้งแต่1ถึง5ข้อ <br>
<a href=""><img src="img/22.PNG" width="500px"></a>
- สามารถเลือกได้ว่าเราจะดูเฉลยได้เลยหรือเลือกที่จะปิดเฉลยเพื่อหาคำตอบเองก่อนได้ <br>
<a href=""><img src="img/23.PNG" width="500px"></a>
- สามารถเลือกได้ว่าจะเปิดเสียงดนตรีขณะเล่นเกมส์หรือไม่ โดยเลือกกดเปิดและปิดจากตัวม้าได้เลย <br>
<a href=""><img src="img/24.PNG" width="500px"></a>
- หลังจากตั้งค่าการเล่นเกมส์ทายคำศัพท์ตามที่เราต้องการแล้วให้กด APPLY เพื่อให้มันบันทึกการตั้งค่าของเรา
จากนั้นจะขึ้นหน้าต่างบอกว่าบันทึกการตั้งค่าสำเร็จดังรูป
 <br>
<a href=""><img src="img/25.PNG" width="500px"></a>
- เราสามารถกด Reset เพื่อกลับไปยังค่าเริ่มต้นของการตั้งค่าตอนติดตั้งเกมส์ได้ <br>
<a href=""><img src="img/26.PNG" width="500px"></a>

## ![](/img/collaboration.png)Team Members
| | รหัสนักศึกษา        | ชื่อ | นามสกุล | githup |
|:-:| :-------------: |:----------:|:--------:|:--------:|
| <a href=""><img src="img/1.jpg" width="200px"></a> | 60070018    | นายฐิติกร  | ผดุงเวทสวัสดิ์  | https://github.com/maxlunla  |
| <a href=""><img src="img/2.jpg" width="200px"></a> | 60070024     | นางสาวณัฐปภัสร์  | อยู่ยง  | https://github.com/Nutpapat  |
| <a href=""><img src="img/3.jpg" width="200px"></a> | 60070025    | นายณัฐวุฒิ  | เตชะศรีบูรพา  | https://github.com/Frong-nt  |

## ![](/img/administrator.png)Assistant Teacher
- Instructor : ผศ.ดร.ธนิศา นุ่มนนท์
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;โครงการนี้เป็นส่วนหนึ่งของวิชาการสร้างโปรแกรมเชิงอ็อบเจกต์ 
ภาคเรียนที่ 1 ปีการศึกษา 2561<br>สถาบันเทคโนโลยีพระจอมเกล้าเจ้าคุณทหารลาดกระบัง

