# py-17
printing plus pattern usin python
n=5
for i in range(n):
	for j in range(n):
		if(i==n-(n//1.5)) or (j==n-(n//1.5)):
		   print("*",end=" ")
		else:
			print(" ",end=" ")
	print()
