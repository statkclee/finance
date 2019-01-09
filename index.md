---
layout: page
title: 금융(Finance)
---

> ### 기계와의 경쟁을 준비하며... AI is a Superpower {.callout}
>
> "고대에는 '땅'이 가장 중요했고 땅이 소수에게 집중되자 인간은 귀족과 평민으로 구분됐으며, 
> 근대에는 '기계'가 중요해지면서 기계가 소수에게 집중되자 인간은 자본가와 노동자 계급으로 구분됐다". 
> 이제는 **데이터**가 또 한번 인류를 구분하는 기준이 될 것이다. 
> 향후 데이터가 소수에게 집중되면 단순 계급에 그치는 게 아니라 데이터를 가진 종과 그렇지 못한 종으로 분류될 것이이다. [^joongang-yuval]
>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [유발 하라리(Yuval Noah Harari)](https://www.youtube.com/watch?v=7Xs3auqcX7k) 
>
> "AI is a superpower!!!", 인공지능을 체득하면 슈퍼파워를 손에 쥘 것이다. 
> 
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Andrew Ng](https://twitter.com/andrewyng/status/728986380638916609)
> 
> 금수저, 은수저 슈퍼파워를 받은 사람과 기계학습을 통달한 흑수저들간의 무한경쟁이 드뎌 시작되었다. 물론, 
> 금수저를 입에 물고 기계학습을 통달한 사람이 가장 유리한 출발을 시작한 것도 사실이다.
>
> "The future is here, it's just not evenly distributed yet."  
> 
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - William Gibson



## 학습목차 

- **[금융/시계열 데이터 - Tidyverse 시계열 데이터 전쟁](finance-tidyquant.html)**
    - [금융데이터 가져오기](finance-data-import.html)
    - [날짜/시간 데이터 기초](ds-date-basics.html)
        - [날짜/시간 데이터 - lubridate](data-handling-timendate.html)
        - [불규칙 시계열 데이터](ds-irregular-time-series.html)         
    - [시계열 데이터 다루기- padr, tibbletime](stat-time-series-basics.html)
- **시계열 데이터 살펴보기**
    - [탐색적 시계열 데이터 분석](stat-time-series-eda.html)
    - [시계열 예측 성능기준(benchmark)](stat-time-series-benchmark.html)
- **시계열 모형 - 단일모형**
    - [태양흑점수(sunspot) 예측](finance-time-series-sunspot.html)
    - [시계열 모형 식별 도구 - 자기상관, 승법, 가법, 분해 ...](stat-time-series-tools.html)
    - [자기회귀이동평균(ARMA) 모형 - `airpassenger`](stat-time-series-arma.html)
    - [계절 자기회귀이동평균(SARIMA)](https://statkclee.github.io/statistics/stat-time-series-sarima.html)
- **시계열 모형 - 앙상블 모형**
    - [시계열 데이터 예측(forecast)](https://statkclee.github.io/statistics/stat-time-series-forecast.html)
    - [시계열 예측 자동화](https://statkclee.github.io/statistics/stat-forecast-automation.html)
    - [체중 예측 - `tibble`](forecast-tibble.html)
- **응용**
    - [금융공학을 위한 R 언어 기초](stat-fe-r.html)
    - [블록체인(Block Chain)](finance-blockchain.html)
    - [실업률 예측 - tidyquant](ts-unemployment-tidyquant.html)    
- **[주식투자](finance-stock.html)**
    - [재무제표(Financial Statement)](financial-report.html)

### [xwMOOC 오픈 교재](https://statkclee.github.io/xwMOOC/)

- **컴퓨팅 사고력(Computational Thinking)**
    - [컴퓨터 과학 언플러그드](http://statkclee.github.io/unplugged)  
    - [리보그 - 프로그래밍과 문제해결](https://statkclee.github.io/code-perspectives/)  
         - [러플](http://statkclee.github.io/rur-ple/)  
    - [파이썬 거북이](http://swcarpentry.github.io/python-novice-turtles/index-kr.html)  
    - [정보과학을 위한 파이썬](https://statkclee.github.io/pythonlearn-kr/)  
        + [정보 과학을 위한 R - R for Informatics](https://statkclee.github.io/r4inf/)
    - [소프트웨어 카펜트리 5.3](http://statkclee.github.io/swcarpentry-version-5-3-new/)
    - [기호 수학(Symbolic Math)](https://statkclee.github.io/symbolic-math/)
    - [데이터 과학을 위한 R 알고리즘](https://statkclee.github.io/r-algorithm/)
    - [데이터 과학을 위한 저작도구](https://statkclee.github.io/ds-authoring/)
        - [The Official xwMOOC Blog](https://xwmooc.netlify.com/)
    - [비즈니스를 위한 오픈 소스 소프트웨어](http://statkclee.github.io/open-source-for-business/)    
- **데이터 과학**
    - [R 데이터과학](https://statkclee.github.io/data-science/)
    - [시각화](https://statkclee.github.io/viz/)
    - [데이터 과학– 기초 통계](https://statkclee.github.io/statistics/)    
        - [공개 기초 통계학 - OpenIntro Statistics](https://statkclee.github.io/openIntro-statistics-bookdown/)
    - [보안 R](https://statkclee.github.io/security/) - TBA
    - **다양한 데이터**
        + [텍스트 - 자연어처리(NLP)](https://statkclee.github.io/text/)
        + [네트워크(network)](https://statkclee.github.io/network)
        + [공간통계를 위한 데이터 과학](https://statkclee.github.io/spatial/)        
        + [고생대 프로젝트](http://statkclee.github.io/trilobite)
        + [금융(finance)](https://statkclee.github.io/finance/)
        + [자동차 데이터 분석](https://statkclee.github.io/automotive/)
        + 비즈니스 프로세스(Business Process) - bupar
    - **모형**
        + [데이터 과학 - 모형](https://statkclee.github.io/model/)
        + [금융(finance)](https://statkclee.github.io/finance/)
    - [~~R 팩키지~~](http://r-pkgs.xwmooc.org/)
    - [~~통계적 사고~~](http://think-stat.xwmooc.org/)
- **빅데이터**
    - [빅데이터(Big Data)](http://statkclee.github.io/bigdata)
    - [데이터 제품](https://statkclee.github.io/data-product/)
    - [R 도커](http://statkclee.github.io/r-docker/)
- **기계학습, 딥러닝, 인공지능**
    - [고성능 컴퓨팅(HPC)](http://statkclee.github.io/hpc)
    - [기계학습](http://statkclee.github.io/ml)
    - [딥러닝](http://statkclee.github.io/deep-learning)
    - [R 병렬 프로그래밍](http://statkclee.github.io/parallel-r/)
    - [인공지능 연구회](https://statkclee.github.io/ai-lab/)
- [IoT 오픈 하드웨어(라즈베리 파이)](http://statkclee.github.io/raspberry-pi)
    - [$100 오픈 컴퓨터](https://statkclee.github.io/one-page/)   
    - [$100 오픈 슈퍼컴퓨터](https://statkclee.github.io/hpc/)
- [선거와 투표](http://statkclee.github.io/politics)
    - [저녁이 있는 삶과 새판짜기 - 제7공화국](https://statkclee.github.io/hq/)

