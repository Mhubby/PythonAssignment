# PythonAssignment
WordString = input('Enter Number here: ' )
length = len(WordString)
print(length)

for i in range(11):
    print (WordString)

print(WordString[0])
print(WordString[0:3])
print(WordString[length-3:length])
print(WordString[::-1])

if length>=7:
    print(WordString[6])
else:
    print('none')
print(WordString[1:length-1])
print(WordString.upper()) 


