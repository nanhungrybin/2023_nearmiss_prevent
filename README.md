## 📁Project name📁
Prediction of corporate near misses based on stacking ensemble model and establishment of prevention strategy through segmentation

스태킹 앙상블 모델 기반 기업의 아차사고 발생 예측 및 세그멘테이션을 통한 예방 전략 수립

- 발표자료 : https://docs.google.com/presentation/d/1OeYIwWoetGNCt6viMe-ztzH7LsLcq7Ks/edit#slide=id.p1

## 📁Summary📁

- 본 연구는 "2018 산업안전보건실태조사"를 활용하여 아차사고의 발생을 예측하고 세그멘테이션을 통해 집단별 아차사고 위험도를 파악하여 개별화된 아차사고 예방 전략을 수립하고자 했다. 
5219개 사업장 응답을 활용하였고 모형 구축 도구는 python을 이용하였다.   

- 아차사고의 발생을 예측하기 위해서는 첫째로 불안전행동과 불안전상태의 수준을 구하고 이를 조합할 필요가 있다. 따라서 아차사고의 원인인 불안전행동과 불안전상태의 영향요인을 활용하여 개별 예측모델을 구축한다. 근로자 불안전 행동 수준을 예측으로는 Ridge, Lasso, XGBRegressor, LGBMRegressor 개별모델을 구축한 뒤 CV 세트 기반의 스태킹 앙상블 기법을 이용한다. 근로자 불안전 상태 수준의 예측으로는 나이브베이즈, SVM, Knn, 인공신경망, 로지스틱 회귀모델의 개별 모델을 구축한 후 최종 Stacking 모델을 위한 Classifier로 로지스틱 회귀모델을 적용하여 스태킹 앙상블을 통해 최종 메타모델을 만들어 한다. 다음으로는 예측한 불안전 행동 수준과 불안전 상태 수준의 결합을 통해 아차사고 발생 위험도를 예측한다. 마지막으로는 예측된 아차사고 발생 위험도를 기반으로 k-means 군집분석을 통해 세그멘테이션을 진행한다. 아차사고 발생 위험도별로 실루엣 계수를 통해 총 2개로 형성된 각 군집의 특징을 파악하여 맞춤화된 아차사고 예방 전략을 수립하도록 제안했다.

![image](https://github.com/nanhungrybin/2023_nearmiss_prevent/assets/97181397/df9a1bea-aa02-44f1-98b8-a7fa9723dfb0)

## 📁대회 관련 사항📁
- 공모전 명칭: 제 10회 산업안전보건 논문경진대회
- 논문주제: 산업안전보건연구원 국가승인 통계인 "근로환경조사" 또는 "산업안전보건 실태조사"를 활용한 산업안전보건 분야 자유주제
- 논문제출 : 본문, 부록, 참고문헌 포함 최대 30매 이내 작성
- 공모전 공지사항: https://oshri.kosha.or.kr/oshri/customerInformation/papercontestnotice.do?mode=view&articleNo=438548&article.offset=0&articleLimit=10)

## 📁역할📁

- 개인참가
- 논문작성, 논문리딩 및 자료조사, 연구 주제 아이디어 기획, Data analysis

## 📁성과📁

- 최우수상 수상
- https://oshri.kosha.or.kr/oshri/customerInformation/papercontestnotice.do?mode=view&articleNo=442861&article.offset=0&articleLimit=10

## 📁시기📁

- 프로젝트 진행 기간 (2023.5 ~ 2023.6)

