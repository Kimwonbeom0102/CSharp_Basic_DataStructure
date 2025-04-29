# 🧠 C# 자료구조 학습 정리

본 저장소는 C# 언어를 기반으로 자료구조를 학습한 내용을 정리한 개인 학습용 프로젝트입니다.  
개발 입문 약 4개월 차 시점에, 에티버스러닝 부트캠프(2024.08.05 ~ 2025.02.07)를 통해 배운 수업 내용을 기반으로 작성되었습니다.  
자료구조의 기초 개념을 익히고, Visual Studio에서 직접 구조를 구현하며 구조별 동작 원리를 이해하는 데 목적이 있습니다.

📌 학습 시점: 개발 입문 약 4개월 차  
📌 출처: 에티버스러닝 부트캠프 (6개월 과정)  
📌 툴: Visual Studio, Draw.io (구조 시각화에 사용)  
📌 참고: 수업에서 제공된 실습 예제 기반 코드 포함

---

## 📂 자료구조 목록

### 🔹 1. 배열 (Dynamic Array)
- 고정 크기 배열의 한계를 보완한 구조
- 요소 추가 시 자동 확장 및 내부 복사 처리 구현
- 📂 [MyDynamicArray.cs](https://github.com/Kimwonbeom0102/CSharp_Basic_DataStructure/blob/master/DynamicArray/MyDynamicArray.cs)
- 📘 [학습 정리 Notion](https://www.notion.so/ArrayList-1574b04e10ea802ca389ff0ce0281ca8)

---

### 🔹 2. 연결 리스트 (Linked List)
- 노드를 포인터로 연결한 구조
- 단일 연결 리스트 구조 구현 및 삽입/삭제 연산 학습
- [MyLinkedList`1.cs](https://github.com/Kimwonbeom0102/CSharp_Basic_DataStructure/blob/master/DynamicArray/MyLinkedList%601.cs)
- 📘 [학습 정리 Notion](https://www.notion.so/Linked-List-1574b04e10ea808bb1d8f535f8c603fd)

---

### 🔹 3. 스택 (Stack)
- LIFO(후입선출) 구조
- 기본 `Push`, `Pop`, `Peek` 메서드 구현
- [MyStack`1.cs](https://github.com/Kimwonbeom0102/CSharp_Basic_DataStructure/blob/master/DynamicArray/MyStack%601.cs)
- 📘 [학습 정리 Notion](https://www.notion.so/1594b04e10ea80d58908c90394451c58)

---

### 🔹 4. 큐 (Queue)
- FIFO(선입선출) 구조
- 순차 큐 및 원형 큐 개념 학습
- [MyQueue`1.cs](https://github.com/Kimwonbeom0102/CSharp_Basic_DataStructure/blob/master/DynamicArray/MyQueue%601.cs)
- 📘 [학습 정리 Notion](https://www.notion.so/1594b04e10ea806b8e96eba5cfa15c94)

---

### 🔹 5. 해시테이블 (Hash Table)
- 키-값 구조의 데이터 저장 방식
- 충돌 해결 및 해시 함수 설계 개념 학습
- [MyHashtable`2.cs](https://github.com/Kimwonbeom0102/CSharp_Basic_DataStructure/blob/master/DynamicArray/MyHashtable%602.cs)
- 📘 [학습 정리 Notion](https://www.notion.so/14d4b04e10ea80f5bd74f886f0511c99)

---

### 🔹 6. 우선순위 큐 (Priority Queue)
- 우선순위가 높은 요소를 먼저 꺼내는 자료구조
- 힙(Heap) 기반 구조 이해
- [MyPriorityQueue.cs](https://github.com/Kimwonbeom0102/CSharp_Basic_DataStructure/blob/master/DynamicArray/MyPriorityQueue.cs)
- [MyPriorityQueue.cs](./MyPriorityQueue.cs)

---

### 🔹 7. 이진 트리 (Binary Tree)
- 이진 탐색 트리(Binary Search Tree) 구조 구현
- 삽입, 탐색, 삭제 메서드 구성
- [MyAVLTree`1.cs](https://github.com/Kimwonbeom0102/CSharp_Basic_DataStructure/blob/master/DynamicArray/MyAVLTree%601.cs)
- 📘 참고 다이어그램  
  ![Binary Tree Diagram](./A_pair_of_diagrams_side-by-side_illustrate_binary_.png)

---

### 🔹 8. 정렬 알고리즘 (Sorting Algorithms)
- 선택 정렬, 삽입 정렬 등 기본 정렬 알고리즘 구조
- [ArrayExtensions.cs](https://github.com/Kimwonbeom0102/CSharp_Basic_DataStructure/blob/master/SortAlgorithm/ArrayExtensions.cs)
- 📘 [정리된 내용 보기](https://www.notion.so/14d4b04e10ea80f5bd74f886f0511c99)

---

## 📝 기타
- 코드는 대부분 수업 실습 기반으로 구성되었으며, 그 과정에서 동작 원리를 직접 분석하고 주석을 추가하여 정리하였습니다.
- 학습에 사용된 다이어그램은 [Draw.io]를 활용해 작성하였습니다.

---

💬 학습 과정에서 발생한 이슈, 느낀 점, 코드 설명 등은 별도 노션이나 주석에 정리해두었습니다.  
개발자 초급자의 학습 과정이니 가볍게 봐주시고, 피드백은 언제든 환영합니다!
