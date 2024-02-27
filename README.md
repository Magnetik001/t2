import random
 
names = ['Аня','Ваня','Юля','Дима','Саша','Глаша','Егор','Денис','Вася','Миша']
nums = [1,2,3,4,5,6,7,8,9,10]
print(names)
print(nums)
print()
lst = []
use_names = []
use_nums = []
dct = {}
lst2 = []

n = 0
while n < 20:
    name = random.choice(names)
    num = random.randint(1,10)
    if name not in lst:
        lst.append(name)
        use_names.append(name)
        n += 1
    if num not in lst:
        lst.append(num)
        use_nums.append(num)
        n += 1

print(use_names)
print(use_nums)
