# Item-in-common

We'll see the most efficient way to find an item in common, 
since we need two lists to compare : list1 and list2

Approach1 :

  In this approach we'll use two nested For loops, one to iterate through the list1 and another for list2
  as we implement nested loops the Big(o) of this code turns out to be O(n^2)
  
Approach2 :

  In this approach we'll create a dictionary "mydict" to insert all the items in list1 using a For loop,
  Now we'll use another For loop to check whether the items in list2 matches with the items in "mydict" using a if statement.
  As we've used two For loops, but not nested the Big(o) turns out to be O(2n) 
  since we drop constants out it is O(n)

both the codes will work fine, 
but O(n) is way more efficient than O(n^2),
Approach2 is better than approach1
