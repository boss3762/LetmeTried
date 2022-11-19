# Area and perimeter

ในคืนพระจันทร์เต็มดวงมีผีน้อยตนหนึ่งอยู่บนเรือที่กำลังเคลื่อนที่(ไปทางดวงจันทร์)มองไปที่ดวงจันทร์แล้วเกิดสงสัยขึ้นว่าทรงกลมที่เขามองเห็นมันมีพื้นที่และเส้นรอบรูปเท่าไหร่
ในระหว่างนั้นเรือก็เคลื่อนที่เข้าใกล้ดวงจันทร์ขึ้นเรื่อยๆ

โดยผีน้อยมีความสามารถในการรู้รัศมีของดวงจันทร์ พี่อยากให้น้องๆช่วยคำนวณพื้นที่และเส้นรอบรูปให้ผีน้อยหน่อย

โดยรัศมีของดวงจันทร์ มากกว่า0เสมอ

ผลลัพธ์ที่ออกมาต้องมีทศนิยมสองตำแหน่ง

### Example1
<pre class="output">
Radius : _1_
Area : 3.14
Perimeter : 6.28
</pre>
### Example2
<pre class="output">
Radius : _5_
Area : 78.5
Perimeter : 31.42
</pre>
### Example3
<pre class="output">
Radius : _25.5_
Area : 2042.82
Perimeter : 160.22
</pre>

::elab:begincode blank=True
import math
a = int(input('Radius : '))
print(f'Area : {math.pi*a**2:.2f}')
print(f'Perimeter : {2*math.pi*a:.2f}')

::elab:begintest
1
::elab:endtest

::elab:begintest
5
::elab:endtest

::elab:begintest
25.5
::elab:endtest

::elab:begintest
0.05
::elab:endtest

::elab:begintest
0.15909091
::elab:endtest

::elab:begintest
100000000
::elab:endtest
