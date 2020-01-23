# 보스톤 마라톤 데이터를 이용한 데이터 차트 만들기(Colab 개발환경)
- 보스톤 마라톤 데이터를 manipulate 과정을 통해 데이터를 정제후
- make data chart 실시

# -manipulate-data
- CSV 파일 읽어오기(pd.read_csv)
- 불필요한 열 삭제하기(drop)
- 데이터 추가하기
- 데이터 선택하기
- 데이터 합치기
- 데이터 저장하기

# -Make-data-Chart
0.마운트하기
- google colab에 gdrive mount 하기(아래 링크 클릭후, 내용 복사 후 입력하기)

1.Column, Bar 차트
- Bar 차트는 비교 및 순위 매기기(Comparsion and Ranking)에 주로 사용된다.
- 예시) 보스턴 마라톤 출전하는 미국인 중 주(state)별 비율

2.Dual Axis 차트, 파레토 차트 이해.
- Dual Axis 차트는 비교 및 순위 매기기(Comparsion and Ranking)에 주로 사용된다.공유하는 x축을 사용하여 2개의 y-axes를 사용한다. 
- Pareto 차트는 경제적 불균형을 설명할 때, 먼저 사용되었다. (20:80)
- 선택과 집중을 할 때 사용된다.(공정률 해결 등) 
- 가장 큰 원인을 찾을 때, 유용하게 사용될 수 있다.
- 예시) 2015~2017 출전하는 사람 나이비율

3.Pie 파이 차트
- 목적은 part to whole이며, 얼만큼 차지하는지에 대해 표현을 해준다.
- 예시) 2015~2017 남/여 비율

4.Line 라인 차트
- 추세 및 트렌드에 대해 사용하는 차트, 많이 사용되고 있는 차트.
- 예시) 2015~2017 상위 100명의 거리별 기록

5.Scatter 차트 이해
- Correlation 연관 관계. 머신러닝에 대해서 사용되어진다.
- 예시) 20~60 나이대별 Official Time

6.Bubble chart
- Scatter를 산포도로 나타냄. 점을 넓이를 통하여 데이터를 보여줌.
- BCG Matrix : 오설팅 / 컨설팅에 많이 사용됨.
- 예시)2시간 지난 후, 사람들이 어디(위도,경도)에 위치하는지 표현

7.Heat Map chart
- 빅데이터 분석 및 R / 엑셀을 사용하여 구현 가능.  데이터 값에 따라 Great, Normal, poor 를 표시해 준다.색 온도를 다르게 하여 시각화를 해준다.
- 예시) 참가자 중에서 어떤 성별,나이들이 보스턴 마라톤에 참여하는지 확인

8.Histogram
- 데이터들이 얼마나 퍼져있는지 확인용, 분포(distribution), 선택과 집중.
- 예시) 2015~2017 연령대별 분포

9.Box Plot chart
- 분포(distribution). 최대,최소, 25%,75%, 중간값
- 예시) 남,여 pace를 비교

10.Geo Chart
- 직관적인 Chart . 지도를 나타내는 차트
- 예시) 2시간 후, 사람들의 위치 표시

11.시각적 효과 사용
