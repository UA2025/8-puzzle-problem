Start State:
1 0 2
3 4 5
6 7 8
End State:
3 1 2
0 4 5
6 7 8
For the given values of start and end state our algorithms gave the following results:
BFS
{'nodes visited': 5, 'path cost': [2], 'time': 0.00020694732666015625}
memory: 11324
DFS
'nodes visited': 3, 'path cost': [2], 'time': 0.00010848045349121094}
memory: 13560
UCS
{'nodes visited': 8, 'path cost': 2, 'time': 0.00019860267639160156}
memory: 17211
IDS
{'nodes visited': 16, 'path cost': [2], 'time': 8.726119995117188e-05}
memory: 15754
Dfs explored the least number of nodes and IDS gave the best time complexity. Ids iterated through most
nodes as dfs was repeatedly called from root.
