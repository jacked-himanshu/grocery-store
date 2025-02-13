# grocery-store
item=input("Enter products")
a=item.lower()
quant=int(input("Enter quantity"))
x=quant
total =0
if(a=="milk"):
 total += x * 80
elif(a=="namkeen"):
 total += x* 200
elif (a=="biscuit"):
  total=x*100
elif(a=="curd"):
  total += x* 68
elif(a=="chocolate"):
  total +=x*800
elif(a=="chips"):
  total += x*50
print(total)
