# python
class student: #creating a class ,class classname
    rno=23      #which are declared inside the class and outside function called instance variable
    name="ganga"
    branch="cs"
    def write(self):#function this can declared with keyword def this should take self argument 
     #this a local variable
     print(self.name)#we can access the instance variable using self variable
     print("writing ")
    def read(self):
      print("reading")
s=student()#creating object
print("roll numnber of student: ",s.rno)#through object accessing the insatnce variable 
print("Name of the Sthtudent: ",s.name)
print("Branch of the Student: ",s.branch)
print(s.write())#through object we can access
print(s.read())

OUTPUT
--------------------------------
roll numnber of student: 23
Name of the Sthtudent: ganga
Branch of the Student: cs
ganga
writing 
reading
