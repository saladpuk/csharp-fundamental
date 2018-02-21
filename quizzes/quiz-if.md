## 1.เครื่องขายผลไม้อัตโนมัติ
เครื่องขายผลไม้อัตโนมัติมีผลไม้ขายดังนี้
|ชนิดของผลไม้|ราคา|
|---|---|
|ส้ม|15|
|มะนาว|25|
ก่อนจะซื้อผลไม้เครื่องจะถามว่าเรามีเงินเท่าไหร่ แล้วผู้ใช้ถึงจะได้เลือกผลพร้อมกับกำหนดจำนวนที่จะซื้อ และเมื่อซื้อเสร็จโปรแกรมจะทอนเงินคืน

ตัวอย่าง

```
How many money do you have?
500
Which one do you want to buy Orange or Lemon?
Orange
How much?
20
Here your change 200
```
---
## 2.เครื่องขายผลไม้อัตโนมัติ เวอร์ชัน 2
จากโจทย์ข้อ 1 ถ้าเรามีเงินไม่พอซื้อ โปรแกรมจะต้องทำการแจ้งเตือนแล้วทอนเงินคืน

ตัวอย่าง

```
How many money do you have?
100
Which one do you want to buy Orange or Lemon?
Orange
How much?
20
You have not enough money!
Here your change 100
```
---
## 3.โปรแกรมทำนายความรัก
โปรแกรมจะทำนายให้ว่าคนที่คุณแอบชอบจะมีใจให้หรือไม่ โดยโปรแกรมจะถามว่าคุณเคยให้อะไรเขาไปบ้าง ซึ่งรายการที่จะถามมีดังนี้
 1. กุหลาบ
 1. ตุ๊กตา

หลังจากที่ได้บอกว่าเคยให้อะไรไปบ้างโปรแกรมจะบอกผลลัพท์ โดยเทียบจากตารางด้านล่างนี้

|เคยให้กุหลาบ|เคยให้ตุ๊กตา|ผลการทำนาย|
|---|---|---|
|/||He/She like you|
||/|He/She interested in you|
|/|/|He/She love you :)|
|||He/She don't care about you|

ตัวอย่าง
```
Did you ever give him/her a rose?
yes
Did you ever give him/her a doll?
yes
He/She love you :)
```
---
## 4.ผู้กล้าปราบจอมมาร
ผู้กล้ากำลังจะเข้าไปสู้กับจอมมาร ซึ่งผลลัพท์ในการต่อสู้ครั้งนี้ขึ้นอยู่กับสิ่งที่ผู้กล้านำติดตัวไปด้วย 3 อย่าง ซึ่งจะส่งผลดังนี้

|น้ำมนต์ศักศิทธิ์|โล่ห์วิเศษ|ดาบศักดิ์สิทธิ์|ผลลัพท์ในการต่อสู้|
|---|---|---|---|
|/|/|/|The devil die|
|/|/|x|Hero bleeding|
|/|x|/|Hero die, The devil bleeding|
|/|x|x|Hero die|
|x|/|/|Hero turn to be a werewolf|
|x|/|x|Hero turn to be a zombie|
|x|x|/|Hero turn to be a bat|
|x|x|x|Hero turn to be a worm|

ให้เขียนโปรแกรมคำนวณผลลัพท์การต่อสู้ในครั้งนี้ โดยโปรแกรมจะถามถึงของที่ผู้กล้านำติดตัวไปด้วย

ตัวอย่าง
```
Do you have a holy water?
yes
Do you have a holy shield?
no
Do you have a holy sword?
no
The battle result is
Hero die
```
---