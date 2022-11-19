# จับมือกันได้กี่ครั้ง

ผีน้อยได้เข้าร่วมงานสังสรรค์โดยผีน้อยอยากจะทำความรู้จักกับเพื่อนๆในงานจึงจะให้ผีน้อยทุกตัวในงานจับมือกันให้ครบทุกตน

งานสังสรรค์ครั้งนี้จะเกิดการจับมีเกิดขึ้นอย่างน้อยที่สุดกี่ครั้ง

จำนวนผีน้อยที่เข้าร่วมงาน มี1ตนขึ้นไป

### Example1
<pre class="output">
จำนวนคน : _1_
จำนวนจับมือ : 0
</pre>
### Example2
<pre class="output">
จำนวนคน : _3_
จำนวนจับมือ : 3
</pre>
### Example3
<pre class="output">
จำนวนคน : _4_
จำนวนจับมือ : 6
</pre>

::elab:begincode blank=True
a = int(input('จำนวนคน : '))
print(f'จำนวนจับมือ : {int((a*(a-1))/2)}')
::elab:endcode

::elab:begintest
1
::elab:endtest

::elab:begintest
3
::elab:endtest

::elab:begintest
4
::elab:endtest

::elab:begintest
10
::elab:endtest

::elab:begintest
10000
::elab:endtest

::elab:begintest
50
::elab:endtest
