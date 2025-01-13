run:
path: C:\Users\USER_NAME\Desktop\path.txt
A,B,C,D,E,F,G
A,B,4
A,C,2
A,D,3
B,E,5
B,C,3
C,E,6
C,D,2
D,F,7
E,G,1
G,C,1
A,G,10
A,D,2
A,D,1
A,C,1
C,D,5
D,E,5



===============Shortest Path Navigator System===============

========= Menu =========
1. View All Vertices
2. Find Path (All Possible Paths and Shortest Path)
3. Add Vertex
4. Remove Path
5. View All Path
6. Exit
Enter your choice: 1

===== All Vertices =====
A
B
C
D
E
F
G

========= Menu =========
1. View All Vertices
2. Find Path (All Possible Paths and Shortest Path)
3. Add Vertex
4. Remove Path
5. View All Path
6. Exit
Enter your choice: 2
Enter the start vertex: A
Enter the end vertex: D

======================= All Possible Paths =======================
1. A -> B -> E -> G -> C -> D = Total Weight: 13
2. A -> B -> E -> G -> C -> D = Total Weight: 13
3. A -> B -> C -> D = Total Weight: 9
4. A -> B -> C -> D = Total Weight: 9
5. A -> C -> D = Total Weight: 4
6. A -> C -> D = Total Weight: 4
7. A -> D = Total Weight: 3
8. A -> G -> C -> D = Total Weight: 13
9. A -> G -> C -> D = Total Weight: 13
10. A -> D = Total Weight: 3
11. A -> D = Total Weight: 3
12. A -> C -> D = Total Weight: 4
13. A -> C -> D = Total Weight: 4

==================== Shortest Path ====================
Shortest Path: A(3) -> D = Total Weight: 1

========= Menu =========
1. View All Vertices
2. Find Path (All Possible Paths and Shortest Path)
3. Add Vertex
4. Remove Path
5. View All Path
6. Exit
Enter your choice: 3
Enter the source vertex: D
Enter the destination vertex: E
Enter the weight of the edge: 5
Vertex and edge added successfully.

========= Menu =========
1. View All Vertices
2. Find Path (All Possible Paths and Shortest Path)
3. Add Vertex
4. Remove Path
5. View All Path
6. Exit
Enter your choice: 4

===== All Connections =====
1. A,B,4
2. A,C,2
3. A,D,3
4. B,E,5
5. B,C,3
6. C,E,6
7. C,D,2
8. D,F,7
9. E,G,1
10. G,C,1
11. A,G,10
12. A,D,2
13. A,D,1
14. A,C,1
15. C,D,5
16. D,E,15
17. D,E,5
0.Menu
Enter the number of the path you want to delete: 16
Path deleted successfully.

========= Menu =========
1. View All Vertices
2. Find Path (All Possible Paths and Shortest Path)
3. Add Vertex
4. Remove Path
5. View All Path
6. Exit
Enter your choice: 5

===== All Connections =====
A -> B (Weight: 4)
A -> C (Weight: 2)
A -> D (Weight: 3)
A -> G (Weight: 10)
A -> D (Weight: 2)
A -> D (Weight: 1)
A -> C (Weight: 1)
B -> E (Weight: 5)
B -> C (Weight: 3)
C -> E (Weight: 6)
C -> D (Weight: 2)
C -> D (Weight: 5)
D -> F (Weight: 7)
D -> E (Weight: 5)
E -> G (Weight: 1)
G -> C (Weight: 1)

========= Menu =========
1. View All Vertices
2. Find Path (All Possible Paths and Shortest Path)
3. Add Vertex
4. Remove Path
5. View All Path
6. Exit
Enter your choice: 6
Exiting. Goodbye!
BUILD SUCCESSFUL (total time: 41 seconds)
