class OOP_58003:
  def __init__(self, name, age, studentnumber, school, course):
    self.name = name
    self.age = age
    self.studentnumber = studentnumber
    self.school = school
    self.course = course
  def description(self):
    return self.name, self.age,self.studentnumber,self.school,self.course
  
  def display(self):
    print("Name:", self.name)
    print("age:",self.age)
    print("studentnumber:",self.studentnumber)
    print("school:",self.school)
    print("course:",self.course)
    
name1 = OOP_58003("Divinagracia Christian Joseph R.", "20","202112237","Adamson University","BS Cpe")
print(name1.display())
