# OOP-58003
class Student:
    student_id = '202112237'
    student_name = 'Divinagracia Christian Joseph R.'
    student_age = '20'
    student_school = 'Adamson University'
    student_course = 'BS CpE'
    def display():
        print(f'Student id: {Student.student_id}\nStudent Name: {Student.student_name}\nStudent Age: {Student.student_age}\nStudent School: {Student.student_school}
        \nStudent Course: {Student.student_course}')
print("Original attributes and their values of the Student class:")
Student.display()
