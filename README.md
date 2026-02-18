numbers=list(map(int,input("Enter numbers: ").split()))
x=int(input("Enter value: "))
pos=int(input("Enter position: "))
numbers.insert(pos,x)
print(numbers)

OUTPUT:
Enter numbers: 10 20 30 40
Enter value: 25
Enter position: 2
[10, 20, 25, 30, 40]

