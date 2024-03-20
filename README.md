# algo2

```Python

class Student:  

    def __init__(self, name, avg_grade ):  
        self.name = name  
        self.avg_grade = avg_grade  
        self.course = '-' 



    def print_info(self):  
        print('Студент(-ка)', self.name)
        print('Имеет средний балл:', self.avg_grade)
        print('Посещает курс по выбору:', self.course)



    def set_course(self):  
        self.course = input("Введите название курса: ")  


# создаем экземпляр класса  
student = Student("Степанова Дарья", 4.8)  


# выводим информацию об объекте  
student.print_info()  



# устанавливаем курс по выбору  
student.set_course()  



# выводим обновленную информацию об объекте  
student.print_info()  





```
