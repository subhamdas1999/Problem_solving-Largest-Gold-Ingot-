
Problem Name – Largest Gold Ingot

Problem - Ramesh is a goldsmith, who brought a large number of gold ingot each of different length(L) but equal breadth(B) and height(H). He wanted to wield the ingots of same length with each other.


Problem Description - Ramesh is a goldsmith, who brought a large number of gold ingot each of different length(L) but equal breadth(B) and height(H). He wants to weld the ingots of same length with each other. He tasks his new employee, Akash, to weld the ingots of same length with each other. But Akash forgot that he had to weld the ingots of same length, instead he welded the ingots in a random manner.
Later Ramesh found out what he had done. He then ordered Akash to cut the welded ingot such that a cuboid with the largest volume from the welded gold ingot is obtained.
Find the volume of summation of gold ingots minus volume of the largest cuboid.
Constraints
0 < G < 10^5
Input
First Line contains one integer G, denoting number of gold ingots
Second line contains two space separated integers B and H, where B denotes the breadth and H denotes the height of individual ingot
Third line contains G space separated integers, denoting the length of the individual gold ingots that are welded together in adjacent manner
Output
An integer corresponding to the volume of summation of gold ingots minus volume of the largest cuboid, mod 10^9+7.
Time Limit
1
Examples
Example 1
Input
7
1 1
6 7 3 4 5 1 3
Output
14
Explanation
 
Total volume of shaded region is 15 and the total volume is 29. So the volume of summation of gold ingots minus largest cuboid obtained is 14, since the height is 1 and breadth is 1.
