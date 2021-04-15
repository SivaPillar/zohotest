# zohotest

str = input()
n = len(str)

estr = str[n//2:] + str[:n//2]
print(estr)

s = 2*n-2
for i in range(0, n):
	for j in range(0, s):
		print(end=" ")
	s = s-2
	for l in range(0, i+1):
		print(estr[l], end=" ")

	print("\r")
