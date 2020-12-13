# ตัวอย่างโปรแกรมสำหรับการเรียน     OOP

### วิธีติดตั้ง

เปิด CMD / Terminal

```python
pip install navapol
```

### วิธีเช้

```python
>>> from navapol import Student, SpecialStudent
```

student0 = SpecialStudent('Mark','Bill Gates')

student0.Hello()
student0.AskExp()
student0.ShowExp()

student1 = Student('navapol')

student1.Hello()
student1.AddExp(10)

student2 = Student('Steve')

student2.Hello()
student2.Coding()

student1.name = 'Albert Einstain'

for i in range(5):
	student2.Coding()

student1.ShowExp()
student2.ShowExp()