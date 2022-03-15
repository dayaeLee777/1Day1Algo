# LeetCode Contains Duplicate
### [문제 바로가기](https://leetcode.com/explore/interview/card/top-interview-questions-easy/92/array/578/)

### 💡 구현 아이디어
---
#### 정렬 후 앞뒤 숫자 비교
1. 주어진 배열을 sort 한다
2. 앞뒤 숫자를 비교하여 만약 숫자가 같다면 true 를 리턴

시간복잡도 : O(NlgN) <br/><br/>

#### Set 적용
1. Set 생성
2. 배열 요소가 Set에 존재하면 true를 리턴
3. 존재하지 않는다면 distinct에 배열요소를 추가

시간복잡도 : O(N) <br/><br/>

### ⛳️ 실행결과
---
| Runtime | Runtime Beats | Memory Usage | Memory Usage Beats |
| ------ | ------ | ------ | ------ |
|  27 ms | 16.06% | 68.4 MB | 65.09% |
|  21 ms | 29.68% | 70.6 MB | 38.78% |  <br/><br/>


### ✏️ 마치며
---
시간복잡도를 줄이기 위해선 HashSet을 적용하는것이 더 효율적이다.
