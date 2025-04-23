my_list = []
# my_list -> []
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
# my_list -> [10, 20, 30, 40]
my_list.insert(1, 15)
# my_list -> [10, 15, 20, 30, 40]
my_list.extend([50, 60, 70])
# my_list -> [10, 15, 20, 30, 40, 50, 60, 70]
my_list.pop()
# my_list -> [10, 15, 20, 30, 40, 50, 60]
my_list.sort()
# my_list -> [10, 15, 20, 30, 40, 50, 60]
index_30 = my_list.index(30)
print("Index of 30:", index_30)
# Output: Index of 30: 3
print("Final List:", my_list)
# Output: Final List: [10, 15, 20, 30, 40, 50, 60]

