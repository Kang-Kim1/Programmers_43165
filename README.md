# Programmers_43165
## 프로그래머스 - 타겟 넘버 (https://programmers.co.kr/learn/courses/30/lessons/43165)  
DFS 알고리즘을 사용하여 입력값의 덧,뺄셈에 대한 모든 결과값을 확인할 수 있었음.  
재귀 함수를 구현하였으며, 각 연산에 대한 재귀호출 + 예외처리 + 정답에 대한 조건문만으로 쉽게 풀 수 있었던 문제.

실행 순서는 다음과 같다 : 
1. 초기값을 넘겨 dfs 재귀함수 호출
2. 다음 index 값 & result값을 넘기며 덧셈 & 뺄셈에 대한 재귀 호출
3. 배열의 마지막 값까지 확인했을 경우, result값이 target값과 동일할 경우 answer 값 증가
4. answer 반환

