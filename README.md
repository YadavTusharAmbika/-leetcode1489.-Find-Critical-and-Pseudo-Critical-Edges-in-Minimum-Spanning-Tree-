this proejct is made in C++ with a complex algo 

to find critical 
to find pseudo 
find mst 


eg :-
Input: n = 5, edges = [[0,1,1],[1,2,1],[2,3,2],[0,3,2],[0,4,3],[3,4,3],[1,4,6]] and theier index are like 0,1,2,3,4,,5,6

MST  aissa grap jiska wght minimun ho 
mst meansare vertex hone chaiye aur edges 4 cause n-1 
like asumme the graph 

0->1->2->3->4
1   1  2  3 this the edges value afteer combing all mst is = 7

4->0->1->2->3 
 3  1  1  2  4 vertex like v-1 =4 total wght is =7 
 
 2->1->0->3->4
  1  1  2  3  total is = 7 mst wgt 

  2->1->0->3
  1  1 | 2
      3\/               total is 7 mst wgt 
       4


       ab critical edge nikalo 
       phir pseudo critical bhi 
       
