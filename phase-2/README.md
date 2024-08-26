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
- 언더샘플링
- 사용한 알고리즘 명 : 앙상블
    - RandomForestClassifier
    - ExtraTreesClassifier
    - GradientBoostingClassifier
    - LGBMClassifier
    - DecisionTreeClassifier
    
- Score : 0.16560170394036208

### automl/submission-4
- 모든 데이터 사용
- 사용한 알고리즘 명 : 앙상블
    - RandomForestClassifier
    - ExtraTreesClassifier
    - LGBMClassifier
    - GradientBoostingClassifier

- Score : 0.0898876404494382

### automl/submission-5
- 언더 샘플링
- 성준님께서 처리하신 전처리 데이터셋을 이용
- 사용한 알고리즘 : 앙상블
    - RandomForestClassifier
    - LGBMClassifier
    - ExtraTreesClassifier
    - GradientBoostingClassifier

- Score : 0.16534260178748758

### automl/submission-6
- 언더 샘플링
- 성준님께서 처리하신 전처리 데이터셋을 이용
- 사용한 알고리즘 : RidgeClassifier

- Score : 0.16737160120845923

### automl/submission-7
- 언더 샘플링
- 변수 importance를 이용해 상위 7개의 col을 이용
- 사용한 알고리즘 : 앙상블
    - GradientBoostingClassifier
    - ExtraTreesClassifier

- Score : 0.08****


### automl/submission-8
- 언더 샘플링
- pca 기법을 이용
- 사용한 알고리즘 : 앙상블
    - AdaBoostClassifier
    - GradientBoostingClassifier
    - LGBMClassifier

- Score : 0.1610808002078462

### automl/submission-9
- 언더 샘플링
- pca 기법을 이용
- 사용한 알고리즘 : 앙상블
    - AdaBoostClassifier
    - GradientBoostingClassifier
    - LGBMClassifier
    - LinearDiscriminantAnalysis
    - RidgeClassifier

- Score : 0.164****

### automl/submission-10
- 언더 샘플링
- pca 기법을 이용
- 사용한 알고리즘 : RidgeClassifier

- Score : 0.16333725029377205


### automl/submission-11
- 언더 샘플링
- pca 기법을 이용
- 사용한 알고리즘 : 앙상블
    - LinearDiscriminantAnalysis
    - RidgeClassifier
    - LGBMClassifier\
    - AdaBoostClassifier
    - GradientBoostingClassifier
    - RandomForestClassifier
    - ExtraTreesClassifier
    - KNeighborsClassifier
    - DecisionTreeClassifier
    - LogisticRegression

- Score : 0.16732394366197184

### automl/submission-12
- 언더 샘플링(normal 3 : abnormal 1)
- pca 기법을 이용
- 사용한 알고리즘 : 앙상블
    - LinearDiscriminantAnalysis
    - RidgeClassifier
    - LGBMClassifier\
    - AdaBoostClassifier
    - GradientBoostingClassifier
    - RandomForestClassifier
    - ExtraTreesClassifier
    - KNeighborsClassifier
    - DecisionTreeClassifier
    - LogisticRegression

- Score : 0.138***

### automl/submission-12
- 언더 샘플링(normal 3 : abnormal 1)
- pca 기법을 이용
- 사용한 알고리즘 : 앙상블
    - LinearDiscriminantAnalysis
    - RidgeClassifier
    - LGBMClassifier\
    - AdaBoostClassifier
    - GradientBoostingClassifier
    - RandomForestClassifier
    - ExtraTreesClassifier
    - KNeighborsClassifier
    - DecisionTreeClassifier
    - LogisticRegression

- Score : 0.138***


### automl/submission-14
- Data Augmentation
- 사용한 알고리즘 : 앙상블
    - GradientBoostingClassifier
    - AdaBoostClassifier
    - RandomForestClassifier

- Score : 0.0999999*