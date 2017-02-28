#This program removes the exclamation marks from a sentence except from those at the end of it.







x= str(raw_input("Please input a sentence: "))
n=int(len(x))- 1
fn=n
counter=0
flag=True
while n>=0 and flag==True:
	if x[n] != "!":
		flag=False
	else:
		counter=counter + 1
		n=n - 1
	
length= fn - counter
i=0
y=[]
while i<=fn:
	if x[i]!= "!":
			y.append(x[i])
	i=i + 1

y.append(counter*"!")
z= "".join(y)
print(z)
