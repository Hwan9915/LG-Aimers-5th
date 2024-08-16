# 코드 기록

> ## 양식
> ### 파일 이름 명
> 사용한 알고리즘 명 : 
> Score : 
> 설명


### catboost/submission-1.csv
- 사용한 알고리즘 명 : Catboost
- Score : 0.143
- 설명 : 기본코드에서 CatBoost 알고리즘만을 사용했지만, 아직은 상당히 알고리즘보단 데이터 전처리에 문제가 있으므로 언더샘플링이 아니라 다른 방식으로 접근해야겟다.

### automl/submission-1
- 사용한 알고리즘 명 : 앙상블(Random Forest, Extra Trees, Lightgbm Boost)
- Score : 0.156?
- 설명 : automl을 이용해서 F1 기준으로 가장 좋은 모델 3가지를 이용하고 앙상블을 이용하여 제출

### automl/submission-2 
- 사용한 알고리즘 명 : 앙상블(Random Forest, Extra Trees, Lightgbm Boost)
- Score : 0.16617842876165115
- hyperparameter
    - fold : 10
    - method : hard

### automl/submission-3
- 사용한 알고리즘 명 : 앙상블(Random Forest, Extra Trees, Lightgbm Boost)
- Score : 0.16617842876165115
- hyperparameter
    - fold : 20
    - method : hard

-> 점수가 동일함 fold의 차이는 크게 나지 않는 것으로 보임