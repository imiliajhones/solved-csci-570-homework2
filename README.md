Download Link: https://assignmentchef.com/product/solved-csci-570-homework2
<br>
<h1>1.       Minimum – Maximum</h1>

You are given a weighted graph G and two designated vertices s and t. Your goal is to find a path from s to t in which the minimum edge weight is maximized, i.e. if there are two paths with weights 10−&gt;1−&gt;5 and 2−&gt;7−&gt;3, then the second path is considered better since the minimum weight (2) is greater than the minimum weight of the first (1). Describe an efficient greedy algorithm to solve this problem and show its complexity. Prove its correctness. (Note: This problem is exactly the same problem to Pr. 8 in HW1.)

1.       Unique MST

Suppose you are given a connected graph G, with edge costs that are all distinct. Prove that G has a unique minimum spanning tree.

<strong> </strong> Near-Tree

Let us say that a graph G = (V,E) is a near-tree if it is connected and has at most n + 8 edges,  where n = |V |. Give an algorithm with running time O(n) that takes a near-tree G with costs on its edges, and returns a minimum spanning tree of G. You may assume that all the edge costs are distinct.

Subsequence

You are trying to find whether a sequence of characters is a subsequence of another sequence. A subsequence of a string is obtained by deleting zero or more symbols of that string. For example,

RACECAR is a subsequence of QRAECCETCAURP. Give a linear algorithm that takes two sequences S ′  of length m and S of length n and decides whether S ′  is a subsequence of S. Prove its correctness.<sub>​</sub>

Winter in Canada

Your friends are planning an expedition to a small town deep in the Canadian north next winter break. They’ve researched all the travel options and have drawn up a directed graph whose nodes represent intermediate destinations and edges represent the roads between them.

In the course of this, they’ve also learned that extreme weather causes roads in this part of the world to become quite slow in the winter and may cause large travel delays. They’ve found an excellent travel Web site that can accurately predict how fast they’ll be able to travel along the roads; however, the speed of travel depends on the time of year. More precisely, the Web site answers queries of the following form: given an edge e = (v,w) connecting two sites v and w, and given a proposed starting time t from location v, the site will return a value fe​ (<sub>​ </sub>t), the predicted arrival time at w. The Web site guarantees that fe​ (<sub>​ </sub>t) ≥ t for all edges e and all times t (you can’t travel backward in time), and that fe​ (<sub>​ </sub>t) is a monotone increasing function of t (that is, you do not arrive earlier by starting later). Other than that, the functions fe​ (<sub>​ </sub>t) may be arbitrary. For example, in areas where the travel time does not vary with the season, we would have fe​ (<sub>​ </sub>t) = t + <em>l<sub>e </sub></em>, where <em>l<sub>e</sub></em>  ​is the time needed to travel from the beginning to the end of edge e.<sub>​           </sub>

Your friends want to use the Web site to determine the fastest way to travel through the directed graph from their starting point to their intended destination. (You should assume that they start at time 0, and that all predictions made by the Web site are completely correct.) Give a polynomial-time algorithm to do this, where we treat a single query to the Web site (based on a specific edge e and a time t) as taking a single computational step.

Shortest Path

Given a directed graph G = (V,E) with nonnegative edge weights and the shortest path distances d(s,u) from a source vertex s to all other vertices in G. However, you are not given the shortest path tree. Devise a

linear time algorithm, to find a shortest path from s to a given vertex t.

Worst Gas Mileage in the World

Suppose you were to drive from USC to Santa Monica along I-10. Your gas tank, when full, holds enough gas to go p miles, and you have a map that contains the information on the distances between gas stations along the route. Let d1​ &lt;<sub>​</sub> d2​ &lt;<sub>​</sub> … &lt; dn ​ be the locations of all the gas stations along the route where d<sub>​                   </sub>i ​ is the<sub>​</sub>

distance from USC to the gas station. We assume that the distance between neighboring gas stations is at most p miles. Your goal is to make as few gas stops as possible along the way. Design a greedy algorithm to determine at which gas stations you should stop and prove that your strategy yields an optimal solution.Prove its correctness.

MST

You are given a minimum spanning tree T in a graph G = (V, E). Suppose we remove an edge from G creating a new graph <em>G</em><sub>1 </sub>. Assuming <em>G</em><sub>1 </sub>that  ​is still connected, devise a linear time algorithm to find a<sub>​     </sub> MST in <em>G</em><sub>1 </sub>.

Recurrences

Solve the following recurrences by the master theorem.

<ol>

 <li><em>T</em>(<em>n</em>) = 9<em>T</em>(<em>n</em>/3) + <em>n </em>+ <em>logn</em></li>

 <li></li>

 <li>More on Recurrences</li>

</ol>

The recurrence T(n) = 7T(n/2) + <em>n</em><sup>2</sup> describes the running time of an algorithm ALG. A competing<sub>​      </sub> algorithm ALG ′  has a running time of T (n) = aT (n/4) + <em>n</em><sup>2</sup><em>log</em> <em>n</em>. What is the largest value of a such that ALG ′ is asymptotically faster than ALG?<strong>  </strong>