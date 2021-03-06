## 코딩테스트 준비
[백준](https://www.acmicpc.net/step)  
[프로그래머스](https://programmers.co.kr/)
- [ ] 1단계: 프로그래밍 문법 공부
- [ ] 2단계: 코드업에서 쉬운 문제부터 200문제 가량 풀기
- [ ] 3단계: 유형별 알고리즘 이론과 핵심 문제풀이
- [ ] 4단계: 백준에서 유형별 문제 20개 이상 풀기
- [ ] 5단계: 백준 삼성SW 역량테스트 문제집 풀기
- [ ] 6단계: 프로그래머스 카카오 문제집 풀기
- [ ] 7단계: 주요 알고리즘 유형 복습하면서 골드 1~5문제 마스터

## 시간 복잡도
* 특정한 크기의 입력에 대하여 알고리즘의 수행 시간 분석
* `빅오 표기법(Big-O Natation)` 빠르게 증가하는 항만을 고려하는 표기법 ex. 𝟑𝐍𝟑 +𝟓𝐍𝟐 +𝟏,𝟎𝟎𝟎,𝟎𝟎𝟎 ==> 𝑶 (𝑵𝟑)  
* 코딩테스트 시험 제한은 통상 1 ~ 5초 (연산 횟수가 5억을 넘어가는 경우 평균 1 ~ 3초 소요)
```js
const startTime = new Date().getTime();
// 알고리즘 풀이 영역

const endTime = new Date().getTime();
console.log(endTime - startTime) // 수행 시간 측정
```
순위 | 명칭 | 해석 | 예시
:--: | :--: | :--: | :--:
좋음 | O(1) | 상수 시간 |
. | O(logN) | 로그 시간 |
. | O(N) | 선형 시간 | N개의 데이터 총합을 계산 (수행시간은 데이터 갯수에 비례)
. | O(NlogN) | 로그 선형 시간 |
. | O(N²) | 이차 시간 | 2중 반복문 이용 (내부에 다른 함수가 없다는 가정)
. | O(N³) | 삼차 시간 |
나쁨 | O(2ⁿ) | 지수 시간 | 



## 공간 복잡도
* 특정한 크기의 입력에 대하여 알고리즘의 메모리 사용량 분석
