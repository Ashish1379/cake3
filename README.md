
# Function to check if it is possible to cut the cake in diferent way
def cutcake(n):



	#Case 1
	if(360 % n == 0):
		print("Yes,it is possible to cut cake in",n,"euqal pieces")
	else:
		print("No,it can't be cut cake into",n,"equal pieces.")
        

	# Case 2
	if(n <= 360):
		print("Yes,it can be cut into",n,"pieces of any size.")
	else:
		print("No,it can't be cut into",n,"pieces of any size.")

	# Case 3
	if(((n * (n + 1)) / 2) <= 360):
		print("Yes,it can be cut into different size having no piece equal")
	else:
		print("No,it can't be cut into different size having no piece equal")

n=int(input("Number of pieces: "))
cutcake(n)

