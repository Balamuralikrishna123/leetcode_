# leetcode_
my agenda is not solving many problems its solving one poblem in many ways 
solving leetcode  and maintainign track 150 problems by december 
# LeetCode Solutions
fitst problem is two sum 
1 ) brute force approach 
two for loops big o of n sqaure worst dolution 
one for loop for itrating thorugh entire array and anothr for loop to iterate from next element 
for i  in range(len(array):
for j in range (i+1, len(array)
if arrray[i]+array[j] == targert
returning[i, j] 
NOW lEts use the DICTIONARY
SEEN  = {}

we save every element in dictionary what we have seen so that we need not to iterate all the time
we go to element one reminder  == target -arr[i] we see if the reminder is in the dictionary if not we go to another elemnet AND WE SAVE this  element 
by see[nums[i]= i
the code is:
seen = {}
for i in range(len(arr));
     remider  = tarhet-nums[i]
     if remider in seen:
        return [seen[reminder], i]
     seen [nums[i]=i
     
  





<!---LeetCode Topics Start-->
# LeetCode Topics
## Linked List
|  |
| ------- |
| [0002-add-two-numbers](https://github.com/Balamuralikrishna123/leetcode_/tree/master/0002-add-two-numbers) |
## Math
|  |
| ------- |
| [0002-add-two-numbers](https://github.com/Balamuralikrishna123/leetcode_/tree/master/0002-add-two-numbers) |
## Recursion
|  |
| ------- |
| [0002-add-two-numbers](https://github.com/Balamuralikrishna123/leetcode_/tree/master/0002-add-two-numbers) |
<!---LeetCode Topics End-->