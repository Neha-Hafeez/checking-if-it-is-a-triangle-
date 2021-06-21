# checking-if-it-is-a-triangle-
print('***triangle or not ***')
a1 = int(input('enter first angle'))
a2 = int(input('enter second angle'))
a3 = int(input('enter third angle'))
a4 = a1+a2+a3
if a4 == 180:
	print('it is a triangle ')
else:
	print('it is not a triangle')
