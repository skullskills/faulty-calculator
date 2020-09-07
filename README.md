# faulty-calculator
#this is a faulty calculator which will correctly solve all the problems except following few
var1 = input("operator")
var2 = input("first number")
var3 = input("second number")
new_var = var1 + var2 + var3
if new_var == "45*3":
    print ("555")
if new_var == "56+9":
    print ("77")
if new_var == "56/6":
    print ("4") 
 if var1 == "*":
     print (int(var2)*int(var3))
 if var1 == "+":
     print (int(var2)+int(var3))    
 if var1 == "-":
     print (int(var2)-int(var3))   
if var1 == "/":
     print (int(var2)/int(var3)) 
else:      
  print ("OUT OF RANGE")  
    
