#Assigning the values to list
list1=[10,20,90,80]
#printing the maximum value of the list
print(max(list1))

Task2

#Assigning the values to the list
list2=[90,100,120,80,60,75]
#sorting the list in ascending order
list2.sort()
#using the negative indexing,getting the second largest values
print(list2[-2])

Task3
#assigning the values to the lists
list1=["Anaconda","Jupyter","Notebook","Pycharm"]
list2=["salary","office","cabs"]
#Merging the two lists using the +operator and assiging the result to the variable
Output=list1+list2
#printing the reslut
print(Output)

Task4
#Defining a function for swaping the list
def listswap(list1):
#swaping the first and last items in a list uisng array indexes   
    list1[0],list1[-1]=list1[-1],list1[0]
    return(list1)
#Assigning the values to the list
list1=[90,50,68,75,20,43,91]
#printing the function
print(listswap(list1))
