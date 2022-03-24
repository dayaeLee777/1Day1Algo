# LeetCode First Unique Character in a String
### [문제 바로가기](https://leetcode.com/problems/first-unique-character-in-a-string/)

### 💡 구현 아이디어
---
1. int 배열 적용
    - 알파벳 길이만큼 int 배열을 생성하여 알파벳이 나온 수만큼 값을 증가시킨다.

2. Map 적용
    - 알파벳을 map의 key 값에 대응시켜 알파벳을 조회하며 value를 증가시킨다.

<br/>

### ⛳️ 실행결과
---
| Runtime | Runtime Beats | Memory Usage | Memory Usage Beats |
| ------ | ------ | ------ | ------ |
|  11ms | 76.19% | 59.6MB | 50.07% | 
|  57ms | 19.70% | 54.5MB | 17.87% |<br/><br/>


### ✏️ 마치며
---
속도를 따지면 Map보단 int 배열을 적용한 것이 더 효율적이다.<br/>
이번에 배운 함수는 `Map`의 `count.getOrDefault(c, 0)+1`이다.<br/>
이전에는 `if(map.get(key)==0)` 이라는 조건을 이용했었는데 앞으로는 `getOrDefault`를 적용해봐야겠다!

