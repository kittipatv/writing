# AlphaStar ชนะมืออาชีพได้อย่างไร

AlphaStarเป็นระบบปัญญาประดิษฐ์(AI, Artificial Intelligence)ที่ษริษัทDeepMindสร้างขึ้นมาเพื่อเล่นเกมStarCraft II
ระบบนี้ชนะMaNaผู้เล่นมืออาชีพระดับสูงไปแบบขาดลอย5-0ในการแข่งขันแบบตัวต่อตัว
ชัยชนะของAlphaStarถือว่าเป็นเรื่องที่สำคัญเป็นอย่างมาก
เพราะที่ผ่านมาไม่มีAIที่สามารถเอาชนะผู้เล่นมืออาชีพได้
และเมื่อวันที่24มกราคม2562
ทางDeepMindได้เขียนบลอกอธิบายการสร้างAlphaStarโดยย่อ
บทความนี้จะขยายความและพยายามอธิบายให้คนที่ไม่มีความรู้ด้านAIให้เข้าใจได้มากที่สุด

## AI ฉลาดกว่าคนหรือไม่

ก่อนที่จะลงรายละเอียดในวิธีการสร้างAlphaStar
ผู้เขียนขอตอบคำถามที่เป็นประเด็นถกเถียงในสื่อว่าAIจะฉลาดเกินคนหรือไม่
คำตอบในปัจจุบันและในอนาคตที่มองเห็นก็คือ"ไม่"
ถึงแมัว่าคุณอาจจะได้อ่านข่าวว่าAIสามารถทำงานบางอย่างได้ดีกว่ามนุษย์
นั่นก็ไม่ได้แปลว่าAIมีความนึกคิดเป็นของตัวเอง
ระบบการเรียนรู้ของเครื่องกล(Machine Learnining)ที่ใช้สำหรับสร้างAIในปัจจุบันทั้งหมดล้วนเป็นการแก้ปัญหาทางคณิตศาสต์ทั้งสิ้น
AIที่อยู่ในหลักการปัจจุบันไม่สามารถเปลี่ยนตัวเองให้ทำงานที่ไม่ได้ถูกสร้างมาให้ทำได้
ดังนั้นเราจึงไม่ถือว่าAIฉลาดกว่าคน
เปรียบเสมือนการที่เครื่องคิดเลขทำงานได้เร็วกว่าคนก็ไม่ได้ทำให้เครื่องคิดเลขฉลาดกว่าคน

## หลักการพื้นฐาน

AlphaStarเรียนการเล่นเกมด้วยหลักกการที่เรียกว่า Reinforcement Learning (TODO: ภาษาไทยเรียกว่าอะไร)
หัวใจสำคัญของหลักการนี้คือผู้ปฏิบัติ(agent)ต้องเรียนรู้วิธีการเลือกการกระทำที่ให้ผลตอบแทนสูงสุดด้วยตัวเอง

## Q-Learning

## Neural network

## Imitation learning

## Ciriculum learning