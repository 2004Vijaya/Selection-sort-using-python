# Selection-sort-using-python

#selection sort
1.select lowest value
2.swap with minimal index value
3.check next lowest value swap with i[0]+1

example:
--17 14 15 19 18 12 1
--1 14 15 19 18 12 17
--1 12 15 19 18 14 17
--1 12 14 19 18 15 17
--1 12 14 15 18 19 17
--1 12 14 15 17 19 18
--1 12 14 15 17 18 19

*****Algorithm*****
1.start from first element in the list/arry
2.arr[0]=min 
3.compare with all the remaining elements to find the real lowest element
4.perform swapping with current position
5.repeat the same with adding positional values(index values) for each minimum check

# pseudocode
for 0 to n-1:
    min=i
    for j i+1 to n:
        if arr[j]<arr[min]
            swap
min=i+1
best_case=o(n^2)
'''
