# Algorithm

-그래프-

1. 인접행렬
Q1. 정점 x와 y가 연결이 되어있는가? (Y/N)  ->  O(1) 장점
Q2. 정점 x와 연결이 되어 있는 모든 정점을 출력하라.  ->  O(n) 단점
n x n 행렬이므로 n^2 에 해당하는 메모리를 다 써야한다.  -> 단점

2. 인접리스트
Q1. 정점 x와 y가 연결이 되어있는가? (Y/N)  ->  O(차수)  ->  인접 여부를 보려면 인접한 정점을 모두 봐야한다. 이거는 인접행렬에 비해 단점
Q2. 정점 x와 연결이 되어 있는 모든 정점을 출력하라.  ->  O(n)  ->  이거는 인접행렬에 비해 장점
메모리를 필요한 만큼만 쓰면 된다  ->  장점

-그래프 순회-
1. DFS
2. BFS
