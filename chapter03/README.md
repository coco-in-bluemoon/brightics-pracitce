# 3장 통계분석

### [1. 확률 변수와 확률 분포](./notes/확률%20변수와%20확률%20분포.md)

### [2. 팀색적 데이터 분석](./notes/탐색적%20데이터%20분석.md)

### [3. 추정과 검정](./notes/추정과%20검정.md)

### [4. 분산분석](./notes/분산분석.md)

### [5. 상관분석](./notes/상관분석.md)

### [6. 시계열분석](./notes/시계열분석.md)

- 연속형 변수 변환: Min-Max Normalization과 Standardization
- 범주형 변수 변환: One Hot Encoding
- 시계열 변수 변환: Lead와 Lag

[실습파일: 데이터 변환](./데이터%20변환.json)
![](./images/workflow_데이터변환.png)

### [3. 파생변수의 생성](./notes/파생변수의%20생성.md)
- Add Function Column(s)와 Query Executor로 파생변수 생성
- 숫자, 문자, 날짜를 위한 함수 | 집계 함수 | 윈도우 함수

[실습파일: 파생변수의 생성](./파생변수의%20생성.json)

![](./images/workflow_파생변수의생성.png)

[실습파일: 집계 함수의 활용](./함수의%20활용.json)

![](./images/workflow_함수의활용.png)

[실습파일: 집계 함수의 활용](./집계%20함수의%20활용.json)

![](./images/workflow_집계함수의활용.png)

[실습파일: 윈도우 함수의 활용](./윈도우%20함수의%20활용.json)

![](./images/workflow_윈도우함수의활용.png)

### [4. 행과 열의 핸들링과 정렬](./notes/행과%20열의%20핸들링과%20정렬.md)
- Select Column: 열 관리
- Filter: 조건에 맞는 행 관리
- Sort: 정렬


### [5. 데이터 결합 및 형태 변환](./notes/데이터%20결합%20및%20형태%20변환.md)
- 결합을 위한 함수: Join, Bind Row Column
- 형태 변환을 위한 함수: Pivot, Unpivot

[실습파일: 행 결합](./행%20결합.json)

![](./images/workflow_행결합.png)

[실습파일: 열 결합](./열%20결합.json)

![](./images/workflow_열결합.png)

[실습파일: 데이터 형태 변환](./데이터%20형태%20변환.json)

![](./images/workflow_데이터형태변환.png)


### [6. 표본 추출(sampling)](./notes/표본%20추출.md)
- 표본 추출 방법: Random Samplint, 층화 추출, 군집 추출, 계통 추출
- 클래스 불균형 해소를 위한 과대추출과 과소추출

[실습파일: 표본 추출](./표본%20추출.json)

![](./images/workflow_표본추출.png)
