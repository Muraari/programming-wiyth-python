# programming-wiyth-python

**Note: Before executing the code,create a even_odd.txt and enter a n numbers in it**

file = open("even_odd.txt","rt") 
for i in file: 
    if i.strip: 
        num = int(i) 
        if (num % 2 == 0): 
            even = open("even.txt","a") 
            even.write(str(num)) 
            even.write("\n") 
        else: 
            odd = open("odd.txt","a") 
            odd.write(str(num)) 
            odd.write("\n")*
             
*Output:*
      *Two new .txt files are created ie,even.txt and odd.txt*
In even.txt file:
0
2
4
6

In odd.txt file:
1
3
5
7


Separating even and odd Numbers
1 Open the input.txt file in write mode.
2 Write the numbers 1 through 10 to the file.
3 Close the file.
4 Open the input.txt file in read mode.
5 Read the contents of the file.
6 Print the contents of the file.
7 Open the even.txt file in append mode.
8 Open the odd.txt file in append mode.
9 Loop through the input.txt file.
10 Check if the number is even or odd.
11 If the number is even, write it to the even.txt file.
12 If the number is odd, write it to the odd.txt file.
13 Close the files.
