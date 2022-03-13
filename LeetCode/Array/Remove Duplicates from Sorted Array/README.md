# LeetCode Remove Duplicates from Sorted Array
### [문제 바로가기](https://leetcode.com/explore/interview/card/top-interview-questions-easy/92/array/727/)

### 💡 구현 아이디어
---
중복되는 값을 확인하기 위해 두 포인터를 적용한다. <br/>

1. `index`를 0으로 초기화
2. `nums`길이만큼 반복
3. 중복값이 아닐 경우, `index`를 증가시킴 
4. index번째 nums를 새로운 숫자(`nums[j]`)로 갱신 <br/><br/>


### ⛳️ 실행결과
---
| Runtime | Runtime Beats | Memory Usage | Memory Usage Beats |
| ------ | ------ | ------ | ------ |
|  1ms | 87.37% | 48.2 MB | 16.07% | <br/><br/>


### ✏️ 마치며
---
중복값을 확인하기 위해 `preNum`이라는 변수를 사용하여 비교했다.
또한 결과 nums를 업데이트하기 위해 `Arrays.sort(nums)`를 사용했는데 실행시간이 9ms가 걸렸다.
두 포인터를 적용하여 이러한 과정을 생략할 수 있었고 실행시간이 눈에 띄기 줄어들었다!
