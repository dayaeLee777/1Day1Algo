# Codility PermCheck
### [문제 바로가기](https://app.codility.com/programmers/lessons/4-counting_elements/perm_check/)

### 💡 구현 아이디어
---
순열인지 확인하기 위해 주어진 A 배열을 `HashSet` 타입에 추가한다. <br/>

1. A 배열에 있는 값을 set에 추가한다.
2. 1~N까지 확인하며 set에 값이 존재하는지 확인한다.
<br/><br/>


### ⛳️ 실행결과
---
| Task Score | Correctness |
| ------ | ------ |
|  100% | 100% | <br/><br/>


### ✏️ 마치며
---
`HashSet`을 이용하여 순열이 만들어지는지 확인한다. 시간 복잡도 `O(N)` 또는 `O(Nlog(N))`이다.
