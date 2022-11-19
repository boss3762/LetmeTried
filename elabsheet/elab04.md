# ยาวเท่าไหร่นะ

วันหนึ่งผีน้อยได้เห็นชายสองคนลักลอบค้าขายสิ่งผิดกฏหมายในสถานที่ลึกลับ ผีน้อยจึงเข้าไปใกล้ๆเพื่อแอบฟังข้อมูลเกี่ยวกับการค้าขายในครั้งนี้

ในขณะที่ผีน้อยแอบฟังอยู่นั้นผีน้อยก็สงสัยขึ้นมาว่าประโยคที่ชายสองคนนั้นใครพูดยาวกว่ากัน

พี่จึงอยากให้น้องๆเขียนโปรแกรมแสดงความยาวของประโยคนั้นๆ

โดยชายคนแรกสมมุติเป็น A ชายคนที่สองสมมุติเป็น B

ช่องว่างระหว่างคำ,จุดFull Stop และตัวอักษรพิเศษให้นับเป็นหนึ่งตัวอักษร ให้นับเป็นหนึ่งตัวอักษร

### Example1
<pre class="output">
A : _Hello!_
B : _How are you?_
A : 6
B : 12
</pre>
### Example2
<pre class="output">
A : _Nice to meet you!_
B : _Nice to meet you too!_
A : 17
B : 21
</pre>

::elab:begincode blank=True
a = input('A : ')
b = input('B : ')
print(f'A : {len(a)}')
print(f'B : {len(b)}')

::elab:begintest
Hello!
How are you?
::elab:endtest

::elab:begintest
Nice to meet you!
Nice to meet you too!
::elab:endtest

::elab:begintest
' '
''
::elab:endtest

::elab:begintest
''
''
::elab:endtest

::elab:begintest
' '
' '
::elab:endtest

::elab:begintest
abcd aswd.
qwert.
::elab:endtest

::elab:begintest
....
...
::elab:endtest
