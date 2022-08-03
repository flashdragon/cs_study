# Tree
## 정점과 간선을 이용한 사이클을 이루지 않도록 구성한 그래프의 특수한 형태로, 계층이 있는 데이터를 표현하기에 적합하다
### 비선형 자료구조
### 계층적 관계를 표현한다.
### 노드와 간선으로 이루어져있다.

## Binary Tree(이진 트리)
### 루트 노드를 중심으로 두 개의 서브 트리로 나누어진다. 나누어진 두 서브 트리도 모두 이진 트리어야 한다.(공집합도 이진 트리)
### 각층별로 숫자를 매겨서 트리의 Level이라고 한다.
### 레벨의 값은 0부터 시작하므로 루트 노드의 레벨은 0이다.
### 트리의 최고 레벨을 트리의 height(높이)라고 한다.

### 포화 이진 트리: 모든 레벨이 꽉 찬 이진 트리
### 완전 이진 트리: 위에서 아래로, 왼쪽에서 오른쪽으로 순서대로 차곡 채워진 이진 트리

## BST(Binary Search Tree) 이진 탐색 트리
### 모든 노드의 키는 유일하다.
### 부모의 키가 왼쪽 자식 노드의 키보다 크다.
### 부모의 키가 오른쪽 자식 노드의 키보다 작다.
### 왼쪽, 오른쪽 서브트리도 이진 탐색 트리이다.

## Heap(힙)
### 최댓값 및 최솟값을 찾아내는 연산을 빠르게 하기 위해 고안된 완전 이진 트리를 기본으로 한 자료구조
### 힙에는 두가지 종류가 있으며, 부모노드의 키값이 자식노드의 키값보다 항상큰 최대힙, 부모노드의 키값이 자식노드의 키값보다 항상작은 최소힙이 있다.

## Priority Queue(우선순위 큐)
### 힙의 형태이고 들어간 순서와 상관없이 우선순위에 따라 데이터가 나온다.