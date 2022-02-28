class OOP_58003:
  def __init__(self, name, studentnumber, age, 
    self.name = name
    self.sdentNumber = 202112237
    self.age = 20
    self.school = Adamson University
    self.course = BS Computer Engineering
  def description(self):
    return self.name, self.studentnumber, self.age, self.school, self.course
  
  def display(self):
    print("Name:", self.name,",",self.studentnumber,",",self.age,",",self.school,",",self.course)
    
name1 = OOP_58003("Divinagracia","CJ")
print(name1.display())
