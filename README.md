# day-1
list=[3,5,7,8,0,1,6,29,65,90,36,78,67,44,35,88,12,35,79,45,100,102,333,678,876,33,71,27,28,30]
print(list)
list.append(2)#value is added at end of list
list.insert(0,1)#inserted at specified position
print(list)
del list[3]#element is deleted at specified index
list.pop()#last element in the list will be deleted
list.pop(9)#element at specified index will be deleted
list.remove(3)#deletes the element specified
list.sort()#sorts the elements in the list
list.sort(reverse=True)#sorts elements in reverse order
list.reverse()#to reverse elements in the list
print(len(list))#to print no of elements in the list
