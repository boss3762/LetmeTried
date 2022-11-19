# Vat
  วันหนึ่งมีผีน้อยที่หิวโซไปกินข้าวที่ร้านอาหารแห่งหนึ่ง เมื่อผีน้อยรับประทานอาหารเสร็จจึงไปคิดเงิน โดยปกติเราจะต้องจ่ายภาษีเพิ่มขึ้นจากอาหาร 7%
  ผีน้อยจึงสงสัยว่าเงินสุทธิที่เขาต้องจ่ายถูกหรือไม่
  
เนื่องจากน้องๆเขียนโปรแกรมกันเก่ง พี่จึ่งอยากให้เขีียนโปรแกรมรับเงินสุทธิ

นำมาคำนวณว่าในจำนวนเงินนั้นเป็นค่าอาหารจริงกี่บาท และภาษีกี่บาท

ให้หาค่าภาษีจาก ภาษี = ราคารวมภาษี - ราคาไม่รวมภาษี

เนื่องจากโจทย์ไม่สามารถ format float ได้ ขอให้น้องหาค่า ราคาไม่รวมภาษี จาก ราคา = ราคารวมภาษี /107 *100

### Example1
<pre class="output">
summary price : _107_
food : 100.0
vat : 7.0
</pre>

### Example2
<pre class="output">
summary price : 3265
food : 3051.4018691588785
vat : 213.59813084112147
</pre>

### Example3
<pre class="output">
summary price : 152.9
food : 142.89719626168224
vat : 10.002803738317766
</pre>

::elab:begincode blank=True
sum = float(input("summary price : "))
food = (sum/107)*100
vat = sum - food
print(f"food : {food}")
print(f"vat : {vat}")

::elab:begintest
107 
::elab:endtest

::elab:begintest
3265
::elab:endtest

::elab:begintest
152.9 
::elab:endtest

::elab:begintest
500.0001 
::elab:endtest

::elab:begintest
1000.0015
::elab:endtest

::elab:begintest
100000000
::elab:endtest

::elab:begintest
1
::elab:endtest
