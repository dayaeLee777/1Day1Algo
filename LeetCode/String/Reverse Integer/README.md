# LeetCode Reverse Integer
### [문제 바로가기](https://leetcode.com/explore/interview/card/top-interview-questions-easy/127/strings/880/)

### 💡 구현 아이디어
---
숫자 x를 뒤집어야하기 때문에 10으로 `나머지 연산`, `나눗셈 연산`을 하여 계산한다.
<br/>

### ⛳️ 실행결과
---
| Runtime | Runtime Beats | Memory Usage | Memory Usage Beats |
| ------ | ------ | ------ | ------ |
|  1ms | 98.82% | 42.3MB | 57.57% | <br/><br/>


### ✏️ 마치며
---
`[-2^31, 2^31 - 1]`의 범위 내에 있어여 하기 때문에 반복문 내에서 아래의 조건을 넣어줘야한다.
```
if(result > (Integer.MAX_VALUE - 1) / 10 || result < Integer.MIN_VALUE / 10)
```
result가 Integer 범위를 벗어나지 않도록 중간에 조건을 추가해줘야하는데 이를 생각해내는데 시간이 걸렸다.
계산 전, 조건을 확인하는 절차를 추가할 수 있도록!!!!!
