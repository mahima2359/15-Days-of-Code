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


   



    
