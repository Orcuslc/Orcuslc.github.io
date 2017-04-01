---
title: Solutions to POJ
category: solutions
tag: [algorithm]
---

See:
https://github.com/Orcuslc/Learning/tree/master/POJ  

The following are some summaries to each problem.  

-  1000: trivial  
-  1001: Not submitted yet  
-  1002: Used a large array; Going to replace with a hash table  
-  1003: Math problem, with a binary search  
-  1004: Math problem with formatted output  
-  1005: Simple math problem  
-  1006: A number theory problem  
-  1007: Merge sort to count reversed pairs; insertion sort for output  
-  1008: Math Problem; used <map> to create hash tables;(Checked discussion to correct the wrong answer)
-  1009: Checked http://leons.im/posts/poj-1009-edge-detection-report/. We can know that, changing points in the output image are all located in the neighbourhood of changing points in the input image; use STL map and vector.
-  1011: DFS; Used a jumping skill to shorten the search time.
-  1010: DFS; (注意! 题目里说邮票种数不超过25, 但是judge时是会超过25的! 我说怎么总是WA....)
-  1013: 1. If one line is even, then all coins in this line is TRUE.
		2. Scan through the three lines, jump over the TRUE coins;
		2'. for those in the up side, their count --; for the down side, count++. (To distinguish between the up and down cases)
		3. The coin with the largest count(under abs) is the fake one.
		4. Notes: when using {switch, case}, remember to add BREAK!;
-  1014: DFS;