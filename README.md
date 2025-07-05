# Ex-6-python-largest-number-
nums=input("the list of numbers: ")
num_list=nums.split()
count =0
for num in num_list:
    count+=1
print("count=",count)
for i in range(count):
    num_list[i]=int(num_list[i])
print("the obtained list:",num_list)
max_num=num_list[0]
for num in num_list:
    if num>max_num:
        max_num=num
print("the maximum number is:",max_num)
