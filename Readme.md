# 👋 Welcome to Vision CSE  

This repository is for the **15 Days of Code Challenge** organized by **Vision CSE** 🚀  

## 📌 About the Challenge
- Duration: **15 Days**
- Goal: Code every day and build consistency  
- Task: Fork this repository, and update your progress here!  

## ✅ How to Participate
1. **Fork** this repository.  
2. **Edit this README** file in your fork.  
3. Document your progress daily:  
   - Add a short note on what you did  
   - Attach screenshots or  
   - Add links to your code submissions/projects  

4. Keep pushing your changes every day!

  # DAY 1 (13/10/2025)
  --> QUESTION 1. Aggressive Cows PROBLEM(BINARY SEARCH) SOLVED IN TUF SHEET/gfg
   problem link: https://www.geeksforgeeks.org/problems/aggressive-cows/1
   NOTE : I solved it using biary search on answers. First, I sorted the stall positions and then used binary search to find the largest minimum distance possible between any two cows. For each middle distance,     I checked if all cows could be placed keeping at least that much gap. If yes, I tried a larger distance; otherwise I reduced it.
  --> QUESTION 2. BOOK ALLOCATION PROBLEM (solved in gfg)
   problem link: https://www.geeksforgeeks.org/problems/allocate-minimum-number-of-pages0937/1
   NOTE: I solved it using binary search on answers. I searched for the minimum possible maximum pages a student can read by checking each middle value. For each mid, I counted how many students would be needed     if no one reads more than that many pages. If it was possible within k students, I tried a smaller maximum; otherwise, I increased it.
   --> QUESTION 3. Split array - Largest Sum(solved in leetcode)
   solution link: https://leetcode.com/submissions/detail/1800459934/
   NOTE: I solved it using binary search on answers. I searched for the minimum possible largest sum among subarrays by checking each middle value. For each mid, I calculated how many subarrays would be needed      if no subarray sum exceeded that value. If it was possible within k subarrays, I tried a smaller maximum; otherwise I increased it.
   -->QUESTION 4. Painter's partition(SOLVED IN GFG)
   solution link: https://www.geeksforgeeks.org/problems/the-painters-partition-problem1535/1
   NOTE: I solved it using binary search on answers. I searched for the minimum time required by checking each middle value as a possible limit. For each mid, I calculated how many workers would be needed if no     one exceeded that time. If it was possible within k workers, I tried a smaller limit; otherwise I increased it.

#Day 2(14/10/2025)
-->QUESTION 1. Minimize max distance to gas stations(gfg)
Soulution link:https://www.geeksforgeeks.org/problems/minimize-max-distance-to-gas-station/1
Note: i solved it by first calculating  the gaps between consecutive stations and stores them in a max-heap It then repeatedly takes the largest gap, adds a new station to split it, updates the gap’s new distance, and pushes it back into the heap. After placing all K stations, the largest value remaining in the heap represents the minimized maximum distance between any two stations.
-->Question 2. Median of two sorted arrays(gfg)
Solution link:https://www.geeksforgeeks.org/problems/median-of-2-sorted-arrays-of-different-sizes/1
Note: What I have thought is that the code iterates through both arrays simultaneously, counting elements as if merging them, keeps track of the middle one or two elements needed for the median, and finally returns either the middle element (if total length is odd) or the average of the two middle elements (if even).
-->Question 3.Kth element of two sorted arrays
Solution link:https://www.geeksforgeeks.org/problems/k-th-element-of-two-sorted-array1317/1
Note: What I have thought is that the code iterates through both sorted arrays like a merge process, counts elements one by one, and returns the kᵗʰ element when the count reaches k, handling leftover elements from either array if one is exhausted.
-->Question 4. row with maximum number of 1's(gfg)
Solution link:https://www.geeksforgeeks.org/problems/row-with-minimum-number-of-1s5430/1
Note:What I have thought is that the code counts the number of 1’s in each row of the matrix, keeps track of the row with the minimum count, and finally returns the index (1-based) of the row that contains the fewest 1’s.

#Day 3(15/10/2025)
-->Question 1. Remove outermost parentheses(strings)
solution link: https://leetcode.com/submissions/detail/1802632489/
-->Question 2. Reverese word in a string 
solution link: https://leetcode.com/submissions/detail/1802669632/
-->Question 3.Largest odd number in a string
solution link:https://leetcode.com/submissions/detail/1802695930/
-->question4. Longest Common Prefix 
Solution Link:https://leetcode.com/submissions/detail/1802731474/
-->Question5. Isomorphic strings
solution link :https://leetcode.com/submissions/detail/1802788148/

#day 4(17/10/2025)
-->Question 1 Check whether one string is rotation of another
solution link: https://www.geeksforgeeks.org/problems/check-if-strings-are-rotations-of-each-other-or-not-1587115620/1
-->Question2 Count substrings
solution link:https://www.geeksforgeeks.org/problems/count-substring/1
-->Question3 Valid Anagram
solution link:https://leetcode.com/submissions/detail/1803942828/
-->question 4 Sort characters by frequency
solution link: https://leetcode.com/submissions/detail/1804007343/
-->question 5 Maximum nesting depth of the parentheses
Solution link: https://leetcode.com/submissions/detail/1804201454/
-->Question 6 Roman to integer
solution link :https://leetcode.com/submissions/detail/1804239029/
-->Question 7 String to integer
solution link : https://leetcode.com/submissions/detail/1804359591/

#day 5(18/10/2025)
Question 1 Middle of the linked list
Solution link :https://leetcode.com/submissions/detail/1804695026/
Question 2 Reverse Linked list 
solution link :https://leetcode.com/submissions/detail/1804753108/
Question 3 Linked list cycle 
solution link :https://leetcode.com/submissions/detail/1804767745/
Question 4 Linked list cycle II
solution link :https://leetcode.com/submissions/detail/1804774753/'
Question 5 Palindrome linked list 
solution link :https://leetcode.com/submissions/detail/1805152370/

#day 6(19/10/2025)
Question1 Odd even linked list 
solution link :https://leetcode.com/submissions/detail/1805278361/
Question 2 Remove nth node from end of linked list 
soltuion  link : https://leetcode.com/submissions/detail/1805287072/
Question 3 Smallest missing multiple of k 
solution link :https://leetcode.com/contest/weekly-contest-472/submissions/detail/1805515194/
Question 4 Longest balanced subarray I
solution link :https://leetcode.com/contest/weekly-contest-472/submissions/detail/1805541820/
Question 5 delete the middle node of linked list
solution link: https://leetcode.com/submissions/detail/1805595079/
Question 6 sort list
solution link :https://leetcode.com/submissions/detail/1805667570/

#day7(21/10/2025)
question 1 Sort a ll of 0's , 1's and 2's
solution link : https://www.geeksforgeeks.org/problems/given-a-linked-list-of-0s-1s-and-2s-sort-it/1
question 2 find intersection point of y ll
solution link :https://leetcode.com/submissions/detail/1807436675/
question 3 add 1 to a number represented by ll
solution link :https://leetcode.com/submissions/detail/1807581451/
question 4 delete all occurances of key in dll
soltuion link: https://www.geeksforgeeks.org/problems/delete-all-occurrences-of-a-given-key-in-a-doubly-linked-list/1
question 5 find pairs of given sum 
solution link : https://www.geeksforgeeks.org/problems/find-pairs-with-given-sum-in-doubly-linked-list/1
question 6 Remove duplicates from sorted doubly ll 
solution link: https://www.geeksforgeeks.org/problems/remove-duplicates-from-a-sorted-doubly-linked-list/1

#day8(22/10/2025)
question 1 Reverse LL in group of given size k
solution link: https://leetcode.com/submissions/detail/1807906201/
question 2 Rotate a ll
solution link :https://leetcode.com/submissions/detail/1808279126/
question 3 Flattening a LL
solution link : https://www.geeksforgeeks.org/problems/flattening-a-linked-list/1
question 4 Copy list with random pointer
solution link : https://leetcode.com/submissions/detail/1808738523/
question 5 pow(x,n)
solution link : https://leetcode.com/submissions/detail/1808773583/
question 6 Count good numbers
solution link : https://leetcode.com/submissions/detail/1808809050/
   



    
