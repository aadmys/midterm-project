# midterm-project
Aadhya Mysore midterm project 
numbers = open('numbers.txt', 'r')
listitems = numbers.read().splitlines()
nums = {}
for number in listitems:
    if number in nums:
        nums[number] += 1 
    else:
        nums[number] = 1 
print(nums)
