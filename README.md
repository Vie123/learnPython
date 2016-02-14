

def bubbleSort(numbers):
	for i in range(len(numbers)-1,-1,-1):
		for j in range(i):
			if numbers[j] < numbers[j+1]:
				numbers[j] , numbers[j+1] = numbers[j+1] , numbers[j]
	print numbers

numbers = []
for i in range(5):
	num = raw_input()
	numbers.append(int(num))


bubbleSort(numbers) 
