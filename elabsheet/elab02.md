# แปลงเวลา

   เขาว่ากันว่าการนอนนับแกะจะทำให้นอนหลับง่ายขึ้น ผีน้อยตนหนึ่งจึงนับแกะไปเรื่อยๆจนหลับโดยผีน้อยตัวนี้จะนับจำนวนแกะเพิ่มขึ้น1 ทุกๆ1วินาที
   
   พี่อยากทราบเวลาในแต่ละคืนก่อนที่ผีน้อยตนนี้จะนอนหลับ
    
### Example1
<pre class="output">
Sheep : _60_
Time : 0 hr(s) 1 minute(s) 0 second(s)
</pre>
### Example2
<pre class="output">
Sheep : _1000_
Time : 0 hr(s) 16 minute(s) 40 second(s)
</pre>
### Example3
<pre class="output">
Sheep : _25000_
Time : 6 hr(s) 56 minute(s) 40 second(s)
</pre>

::elab:begincode blank=True
a = int(input('Sheep : '))
print(f'Time : {a//3600} hr(s) {a%3600//60} minute(s) {a%60} second(s)')
::elab:endcode

::elab:begintest
60
::elab:endtest

::elab:begintest
1000
::elab:endtest

::elab:begintest
25000
::elab:endtest

::elab:begintest
0
::elab:endtest

::elab:begintest
23
::elab:endtest

::elab:begintest
3600
::elab:endtest
