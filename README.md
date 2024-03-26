# eda-repo-5

### 프로젝트 기간 : 3/20 ~ 3/26

# < 국내 증시 데이터 조사 >

## 서론 : 프로젝트 소개

<aside>
📌 소개 : 국내 증시에 대해 데이터 수집 기반으로 시장에 영향을 미치는 요소 및 동향을 분석

</aside>

- 국내 증시를 조사하게 된 이유

1. 우리나라 증시가 어떤 과정을 거쳐 지금에 이르렀는지 알아보고 싶다.

2. 국장(국내 시장)에 투자 했다가 손해를 본 경험이 있다.

3. 증시를 보고 우리나라 경제 규모가 어느정도 성장했는지 알아 싶다.

4. 증시 규모를 보고 국내 대표 기업들의 가치 파악하고 싶다.

5. 외국인 투자자가 국내 증시에서 얼마나 영향에 끼치는지 알아보고 싶다.

- 왜 20년 기준으로 했는가?
    - 20년 주기의 경제순환률을 가진다는 '쿠즈네츠 파동', 노벨경제학상 수상자인 사이먼 쿠즈네츠의 이론 하 국내 증시 20년치 데이터 속에서 향후 우리가 투자할 방향 모색하기.

- 증시 지수 산출은 어떻게 되는가?
    - 증권 시장에 상장된 모든 종목의 주식가격을 먼저 더해 종목 수로 나눈 평균값을 구하고 이를 기준기점으로 평균값이 증시 지수가 된다.

## 프로젝트 멤버 구성

### 팀명 : 개미지옥

(개미지옥에서 살아남아 슈퍼개미가 될때까지)

### 팀장 : 김요한

### 팀원 : **박서연, 조성오**

## 프로젝트 기술

![mysql](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/9217f5c0-4e7d-461d-bf1a-4840efb63b0a)
![matplotlib](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/50bbab9c-8ee3-42d6-879f-06b0c276c41e)
![pandas](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/9b469d18-f787-49db-b042-2045ada0b20f)
![download](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/3f656e3c-4440-43d7-ac7a-35817a70bcd1)

## 🔍데이터 수집

- 네이버 뉴스, 증권
- krx(한국증권거래소) https://www.krx.co.kr/main/main.jsp

## 📊본론 : 데이터 분석

<aside>
🔥 투자 금액이 어디에 집중되고 있는가?

</aside>

## 1. 코스피, 코스닥

### 1) 코스피, 코스닥 각각 20년치의 상승 지표와 하락 지표 정리

(코스피 종가)

![Untitled](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/16642286-6bda-442f-9dea-fc9ebd6514cc)

(코스피 거래량)

![Untitled1](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/cb412f9c-c089-4ccc-a5c0-5ad8d1cc7f23)

(코스닥 종가)
![Untitled2](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/efd48a70-5afd-41eb-b446-0ddff0281979)

(코스닥 거래량)

![Untitled3](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/8bc63ca9-e9e1-4cd3-b19f-b90d411d6f1b)

(코스피, 코스닥 전체 지표)

![5](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/8260c79c-3908-4a6d-9e67-b5ca75ddeb1a)

(매수 그래프)
![6](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/91093b91-aac1-4874-b1c1-b67fb0929e43)

## 2. 전체 거래 대금

### 1) 코스피, 코스닥의 상승, 하락 폭이 큰 연도 분석(2008년~2009년, 2020년~2021년)

- 2008년 news

(뉴스 기사)

![7](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/7098d3a2-d4da-4f99-8b72-56220be8e4c9)


하락 이유 : 미국 주택 가격하락과 이에 연동되어 있던 파생상품 투자로 인한 은행의 대규모 손실, 은행이 무너지면서 신용경색과 시중에 돈이 회전하지 못하면서 나타난 실물경제의 과사이다.

마지막으로 미국의 소비가 무너지고 이를 메워줄 수 있는 신흥국의 성장이 따라와 주지 못해 주식 폭락한다.

(워드 클라우드 시각화)

![8](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/da08f9a8-9b3a-4c87-acbc-a7cadc44eec9)

- 2009년 news

(뉴스 기사)

![9](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/4ccbb8b4-61ea-4b60-8cb6-15d9f7bf4c4c)
![10](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/a5ca87df-82f4-46a1-826c-b5ec5014486a)


회복 이유 : 미국중앙은행인 연방준비제도이사회가 정책금리를 제로 수준으로 낮춘데 이어  미국내 소비 위축의 충격을 최소화했다. 그 이후로 2009년 하반기부터 경제는 서서히 회복하고 주가가 이에 변영해 반등했다.

(워드 클라우드 시각화)

![11](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/32b999ac-4ab3-407a-8daa-9130211c1a15)


- 2020년 news

(뉴스 기사)

![12](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/bc135c7b-a06d-4bda-af42-cb11310449f5)


하락 이유 : 2008년 금융 위기 이후 저성장, 저물가 상황에서 미국을 중심으로 한 주요국 중앙은행들을 꾸준히 완화적 통화정책을 이어오던 중 코로나19 사태가 벌어졌다.

당시 현금을 어마어마하게 풀려버린 탓에 유동성으로 인해 소비의 확대, 공급부족, 인플레이션이 일시적인 것이라는 착각으로 대처가 늦어서 전세계적으로 물가상승 압력이 높아졌다.

(워드 클라우드 시각화)

![13](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/60324512-4214-4d64-bbe9-f2b320398283)

- 2021년 news

(뉴스 기사)

![14](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/24ab9eca-6ec8-4116-8cc5-73b5d5048f55)

![15](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/d7bd684e-a139-41d7-a687-3457903d7948)

![16](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/1dadbf3e-7d27-4784-8978-1c7e588d108e)

![17](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/988d9452-2cc5-4ccf-805c-25dafd8b5ad1)

상승 이유 : 인플레이션을 제압하기 위한 기준 금리인상과 같은 긴축을 단행. 국내 상장기업의 영업이익이 조금씩 회복되고 있고 실적에 비해 주가가 낮은 수준으로 있다. 특히 국내 반도체 업종의 이익 개선이 이어질 수 있고 긍정적인 영향을 미칠 것으로 생각되어 개인들이 대량 매수하면서 코스피가 회복되었다.

이후 외국인 매도로 인해 폭락

![18](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/042a282a-4413-4175-8f47-db281ae86d38)

(워드 클라우드 시각화)

![19](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/a01cfc72-ffb9-48d9-aff5-377a0ed5a6bf)

### 2) 거래 대량이 가장 큰 2020년 기준 1년 전/후 : 상위 10개 업종 분석

- 특정하는 코스피 성장 수치와 코스닥 하락 수치를 기록한 동일 산업을 놓고 왜 이런 상반된 모습이 나타났는지 고민
- 2019년

(거래대금, 거래량)

![20](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/fa1f7ee0-0f93-4826-a738-359d9fa42634)


(시각화)

![21](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/ff46ebe8-fedf-4ec0-82ef-9cc73c9c149c)

![22](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/29c175e2-ef50-4864-bd50-d425735e67bb)



- 2020년

(거래대금, 거래량)

![23](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/270df705-9c46-4baf-9ae8-500ec5277d7a)

(시각화)

![24](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/8b089e8d-5c35-4caf-ae44-6ba60dddbc35)

![25](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/bb12723a-c280-4b4e-8e43-9ea646a71b68)

(뉴스 기사)

![26](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/148f7b08-2ffd-4422-957b-60dcb156e377)

- 2021년

(거래대금, 거래량)

![27](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/0f75b20a-8a18-4184-bcc7-71167107c76b)


(시각화)

![28](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/40be545c-2e8a-43b1-908c-798d6d8803df)

![29](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/ad60988a-9c72-4b46-8a91-c9b71be6dbe0)

(매수 그래프)

### 3) 돈을 벌기 위해 미래에 어떤 산업에 투자하면 좋을까 - 개미의 시선

- 잠시 화재 돌리기
- 박서연님이 넣은 주식,,, 항공사를 알아볼까?

![30](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/2e80eb3a-9cc5-4615-9d22-a3bafe26fffe)

![31](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/e6c13406-2da5-41ba-bacb-9813a763def1)

![32](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/7895d07b-b56a-4658-9f98-2168ed88e59c)

![33](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/6acaa0ce-eaff-4ea2-8d6c-f036b9b517cb)

![34](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/fa487589-70cf-4957-b3a3-9902b9978d9e)

![35](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/3798508d-3114-4f58-9ebc-c48076858761)

## 3. 한국 시장에 외국인 투자 비율

- 종목별 투자 비율 - 우리나라 코스닥과 코스피는 누구의 영향을 많이 받을지
    - 위의 결과를 통해 도출할 수 있는 몇 가지 고민

![36](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/f0f9cd6a-8a65-4191-b97c-38c46b943ff8)

![37](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/62dca684-f227-43a2-baa1-60f2be724722)

![38](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/269cb913-2c5a-4374-9c0f-327266236de4)

## 📈 결론 : 앞으로 한국 경제는 어떤가?

## 다시 2008년 때처럼,,,

![5](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/8260c79c-3908-4a6d-9e67-b5ca75ddeb1a)
![39](https://github.com/addinedu-ros-5th/eda-repo-5/assets/163628109/9dcfc889-85cd-47ad-9a15-141200b69824)

### 쉽지 않겠다.
