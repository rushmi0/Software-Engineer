# Software Process

กิจกรรมที่นำไปสู่การผลิตซอฟต์แวร์ อาจเกี่ยวข้องกับการพัฒนาซอฟต์แวร์โดยใช้ภาษาโปรแกรมมาตรฐานเช่น Java
ในปัจจุบันไม่จำเป็นต้องพัฒนาด้วยวิธีนี้เสมอไป ซอฟต์แวร์ประยุกต์สมัยใหม่ได้รับการพัฒนาโดยการขยายและแก้ไขระบบ
โดยการกำหนดค่า (Configuration) การรวมซอฟต์แวร์ (Integration) หรือส่วนประกอบระบบที่อยู่ในซอฟต์แวร์ต่างๆ


### Software Process มีกิจกรรมพื้นฐาน 4อย่างคือ
1. #### Software Specification
   - การกำหนดว่าซอฟต์แวร์ควรจะทำอะไรได้บ้าง

2. #### Software Design and Implementation
   - การวิเคราะห์และออกแบบระบบรวมทั้งการดำเนินงาน ให้ตรงกับข้อกำหนดที่ระบุไว้

3. #### Software Validation
   - การตรวจสอบระบบว่าถูกต้องทำความต้องการหรือไม่

4. #### Software Evolution
   - การปรับเปลี่ยนระบบ หรืออัพเดทเพื่อให้ตรงตามความต้องการของลูกค้าเสมอ

<br>


### In House Software Development

กระบวนการพัฒนาซอฟต์แวร์มีความซับซ้อน อาจจะไม่ใช่ระบบในอุดมคติ องค์กรส่วนใหญ่จึงมีการพัฒนากระบวนการพัฒนาซอฟต์แวร์ของตัวเองขึ้นมาเพื่อรองรับลักษณะเฉพาะของระบบที่กำลังพัฒนา



### Plan Based Approach
การขับเคลื่อนด้วยแผน กิจกรรมทั้งหมดเป็นการวางแผนล่วงหน้า ความคืบหน้าจะถูกประเมินกับแผนนี้ หรืออาจจะใช้รูปแบบอไจล์
ซึ้งมีความคล่องตัว และรองรับการเปลี่ยนแปลงได้อย่างดี รูปแบบการปรับปรุงซอฟต์แวร์ที่หลากหาย ต้องคำนึงถึงเทคนิคที่ล้าสมัย หรืออาจไม่ใช้ประโยชน์


# Software Process Models


## Walter Fall Model

ระบบที่จะพัฒนานั้นอาจเริ่มด้วยการพัฒนาระบบใหม่ หรือนำระบบเดิมที่มีอยู่แล้วมาปรับเปลี่ยนให้ดียิ่งขึ้น 
ในวงจรการพัฒนาระบบช่วยให้ดำเนินการได้อย่างมีแนวทางและขั้นตอน ทำให้สามารถควบคุมเวลา 
และงบประมาณการดำเนินงานได้

![water-fall](https://github.com/rushmi0/Software-Engineer/assets/120770468/1ba5af49-2cc8-498b-8b5c-56feefe9f36a)

### 1. Project Planning

เป็นการวางแผนการพัฒนาโดยการระบุปัญหา โอกาศ และจุดมุ่งหมาย ซึ่งเป็นการกำหนดทิศทางในการพัฒนาให้ชัดเจน
เช่น การระบุปัญหาจะได้รับมาจากพนักงานที่ทำงานแล้วพบว่ามีปัญหา หรือไม่พอใจกับระบบที่มีอยู่เดิม

### 2. Analysis

รวบรวมข้อมูลจากความต้องการของผู้ใช้โดยการ สัมภาษณ์ ออกแบบสอบถาม สังเกตพฤติกรรมของผู้ใช้และสิ่งแวดล้อม 
ให้ความสำคัญความต้องการของผู้ใช้เป็นหลักและวิเคราะห์ออกมาในรูปแบบของแผนภาพ

### 3. Design

เป็นการออกแบบเชิงตรรกะ (Logical Design) และการออกแบบเชิงกายภาพ (Physical Design)
การออกแบบเชิงตรรกะ เป็นการออกแบบโดยตามความต้องการของผู้ใช้ ควรมีลักษณะการทำงานแสดงผลออกมาอย่างไร
หรือเก็บข้อมูลอะไรบ้าง .. เชิงกายภาพ เป็นการออกแบบให้ระบบนั้นสามารถทำงานได้จริง

### 4. Implementation

ในขั้นตอนนี้ต้องมีเอกสารควบคู่ไปกับการเขียนโปรแกรมให้ตรงกับที่วิเคราะห์ออกแบบไว้ และต้องมีการทดสอบโปรแกรม
ที่ได้พัฒนาขึ้น ก่อนนำระบบใหม่มาใช้แทนระบบเดิม จากนั้นต้องมีการจัดอมรมใช้ระบบ ควรคำนึงถึงผลกระทบต่อผู้ใช้ระบบและองค์กร
ต้องมีกาารประเมินผลความพึงพอใจของผู้ใช้ เพื่อนำกลับไปพัฒนาใหม่อีกครั้ง

### 5. Maintenance

เป็นการดูแลให้ระบบทำงานได้อย่างมีประสิทธิภาพ เช่น การสำรองข้อมูล ปรับแต่งฐานข้อมูล ... หากมีการเปลี่ยนแปลงความต้องการ
จำเป็นต้องมีการแก้ไข ปรับปรุงมากเกินกว่าที่จะแก้ไขได้ ต้องกลับไปที่ขั้นตอนที่ 1 ใหม่ ทำแต่ละขั้นตอนตามลำดับ

## ข้อจำกัดของ Walter Fall Model

 - ไม่สามารถปรับเปลี่ยนความต้องการในรหว่างที่มีการพัฒนาได้ เพราะจะกระทบต่องานทั้งหมด
 - ผู้ใช้มีส่วนร่วมน้อยมาก การทำงานทั้งหมดขึ้นอยู่กับผู้พัฒนาเป็นหลัก ผู้ใช้เป็นเพียงผู้ให้ความต้องการเท่านั้น
 - วิธีนี้ให้ความสำคัญกับแผนงาน และมีเวลาตายตัว ถ้าขั้นตอนใดมีปัญหาล่าช้า จะกระทบต่อโครงการทั้งหมด

<br>

## Joint Application Development (JAD)

เทคนิคการทำงานเป็นทีมโดยให้ผู้ใช้มีส่วนร่วมในการพัฒนาระบบ เพื่อวิเคราะห์ระบบ แก้ปัญหา  รับความต้องการระบบใหม่
ผลที่ได้คือ รูปแบบความต้องการของผู้ใช้ ทำให้มีความถูกต้องแม่นยำสูง แต่มีข้อเสียคือ มีค่าใช้จ่ายสูงเพราะต้องมีการจัด Workshop


## Rapid Application Development (RAD)

ออกแบบมาเพื่อผลิตซอฟต์แวร์อย่างรวดเร็ว โดยกำหนดว่าซอฟต์แวร ไม่ได้เป็นหน่วยเดียว แต่เป็นส่วนๆ
โดยแต่ละส่วนที่เพิ่มขึ้น ไม่ว่าจะเพิ่มฟีเจอร์หรือฟังก์ชันใหม่ นำเข้าไปรวมกันเป็นระบบใหม่ หลักการนี้เรียกว่า `Incremental Development`

_**การพัฒนาซอฟต์แวร์อย่างรวดเร็วอย่าง Agile และ Extreme Programing ต่างมีหลักพื้นฐานบางอย่างที่เหมือนกันคือ**_

### 1. Requirement

 + ความต้องการของผู้ใช้ รายละเอียดของระบบหรือข้อกำหนด

### 2. Version

 + ผู้ใช้และผู้มีส่วนได้ส่วนเสีย มีส่วนร่วมในการระบุความต้องการและประเมินผลแต่ละรุ่น อาจมีการเสนอการเปลี่ยนแปลง
และข้อกำหนดใหม่ในระบบที่เป็นรุ่นใหม่กว่า

### 3. User Interface

 + ถูกออกแบบมาโดย `UI Designer` ช่วยให้การออกแบบ สร้าง UI เสร็จได้อย่างรวดเร็ว

<br>

_**โดยทั้ง JAD และ RAD มุ่งเน้นให้การพัฒนาซอฟต์แวร์เสร็จสิ้นในเวลาที่สั้น ซึ่งเป็นประโยชน์ในสถานการณ์ที่
ต้องการผลิตซอฟต์แวร์ที่สามารถใช้งานได้เร็ว หรือในการสร้างโปรโตไทป์ของซอฟต์แวร์ในเวลาเร่งด่วน
อย่างไรก็ตาม JAD และ RAD มีความแตกต่างกันในเชิงมุมมองและกระบวนการที่ใช้ในการพัฒนาซอฟต์แวร์ ดังนี้**_

<br>

### 1. Joint Application Development (JAD)
 + JAD ใช้ในการวางแผนและพัฒนาซอฟต์แวร์ โดยควบคู่กับความร่วมมือกันของผู้เกี่ยวข้องทั้งหมด ทั้งนี้เพื่อให้ความคิดและความต้องการของผู้ใช้หรือลูกค้าถูกนำเสนอและนำไปใช้ในกระบวนการพัฒนา

 + การประชุมและการสัมภาษณ์เป็นเครื่องมือหลักในกระบวนการ JAD เพื่อเสนอแนวคิด รวบรวมข้อมูลความต้องการ และทำความเข้าใจเรื่องราวธุรกิจและกระบวนการที่ผู้เกี่ยวข้องต้องการให้ระบบรองรับ

<br>

### 2. Rapid Application Development (RAD)
 + กระบวนการ RAD มุ่งเน้นให้การพัฒนาซอฟต์แวร์เป็นไปอย่างรวดเร็ว โดยให้มีการสร้างโปรโตไทป์ของระบบที่มีความสมบูรณ์ในส่วนหนึ่งเพื่อให้ลูกค้าและผู้ใช้สามารถให้ความคิดเห็นและติดตามการพัฒนาได้

 + การทดสอบและการให้ความคิดเห็นของผู้ใช้เป็นส่วนหนึ่งในกระบวนการ RAD เพื่อปรับปรุงและปรับเปลี่ยนโปรโตไทป์ให้เข้ากับความต้องการของผู้ใช้

<br>

สรุป, ทั้ง JAD และ RAD เป็นกระบวนการที่ให้ความสำคัญในความรวดเร็วในการพัฒนาซอฟต์แวร์ แต่วิธีและความเน้นในกระบวนการนั้นมีความแตกต่างกันไป .. การเลือกใช้กระบวนการแบบใดอยู่ที่ความต้องการและสภาพแวดล้อมของโครงการพัฒนาซอฟต์แวร์นั้นๆ


## incremental 
กระบวนการในการพัฒนาซอฟต์แวร์ที่เน้นการสร้างส่วนของระบบที่สำคัญและสามารถใช้งานได้ ส่วนนี้จะถูกสร้างขึ้นและทดสอบให้เสร็จสมบูรณ์ก่อนที่จะไปสู่การสร้างส่วนถัดไป ซึ่งเป็นการพัฒนาแบบเป็นขั้นลำดับ

### สรุปในลักษณะง่าย ๆ ดังนี้

 + การทำงานแบบ incremental เป็นการพัฒนาแบบสร้างขึ้นทีละส่วนซึ่งส่วนแต่ละส่วนมีความสำคัญและสามารถใช้งานได้

 + ทำให้สามารถทดสอบและเปรียบเทียบความสามารถของระบบในแต่ละขั้นตอนได้

 + ส่วนที่สร้างและทดสอบเสร็จสมบูรณ์แล้วจะถูกนำมาใช้ในการพัฒนาส่วนถัดไป และจะค่อยๆ เพิ่มส่วนใหม่เข้าไปจนกระทั่งระบบเสร็จสมบูรณ์

## iterative 

การทำงานแบบ iterative จะทำซ้ำไปเรื่อย ๆ จนกว่าฟีเจอร์หรือส่วนการทำงานทั้งหมดในโครงการจะเสร็จสิ้น และช่วยให้ทีมพัฒนาสามารถปรับปรุงและปรับแก้ไขระหว่างกระบวนการพัฒนาได้อย่างรวดเร็วและตอบสนองต่อความต้องการของลูกค้าหรือผู้ใช้ได้มีประสิทธิภาพมากยิ่งขึ้น

โดยประกอบด้วยขั้นตอนดังนี้

### 1. วางแผนและการกำหนดความต้องการ
 + กำหนดขอบเขตและกลุ่มฟีเจอร์ที่ต้องการพัฒนาในรอบการทำงานนั้น ๆ

### 2. การพัฒนาและทดสอบ
 + พัฒนาฟีเจอร์หรือส่วนการทำงานที่กำหนด พร้อมทั้งทำการทดสอบความสามารถและประสิทธิภาพ

### 3. ส่งมอบและขอความคิดเห็น
 + ส่งมอบฟีเจอร์หรือส่วนการทำงานที่เสร็จสมบูรณ์ และขอความคิดเห็นหรือข้อเสนอแนะจากลูกค้าหรือผู้ใช้

### 4. ปรับปรุงและวางแผนในรอบการทำงานถัดไป
 +  นำความรู้หรือข้อเสนอแนะมาปรับปรุงและวางแผนในรอบการทำงานถัดไป

