# Single-Number-II
from collections import Counter
nums = list(map(int,input("Enter numbers separated by space:").split()))
count = Counter(nums)
for i, c in count.items():
    if c == 1:
        print("Single number:", i)
        break
