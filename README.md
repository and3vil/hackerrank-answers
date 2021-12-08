# hackerrank-answers
#The included code stub will read an integer, , from STDIN.

#Without using any string methods, try to print the following:


#Note that "" represents the consecutive values in between.

#Example

#Print the string .

#Input Format

#The first line contains an integer .

#Constraints

1<n>150
  from __future__ import print_function

if __name__ == '__main__':
    n = int(raw_input())
for i in range(n):
    print(i+1, end="")

