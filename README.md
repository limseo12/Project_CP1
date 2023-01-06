# 게임시장매출분석예측 입니다.
피쳐간의 상관관계와 머신러닝 모델을 이용해 매출을 분석 예측하였습니다.

기간 2022/6/27 ~ 2022/7/7 (총14일) 주말포함x

Project_CP1 첫 협업 프로젝트입니다

데이터 : https://www.vgchartz.com/gamedb/  해외게임사이트에 있는 데이터와 캐글의 videogame 데이터를 합쳤습니다.

맡은 파트 : 여러 회귀 모델들을 찾아 적용하였습니다.\
            많은 회귀모델들을 공부할겸 여러 모델들을 찾아서 적용해 보았습니다.\
            추가작업으로 필요없는 부분을 제거하고 딥러닝 부분을 추가하였습니다.(개인)

비교한 모델 :Linear regression,KNeighborsRegressor,Decision Tree Regressor,RandomForest Regressor,SVM (SVR)
            XGBoost, LGBM, keras.model

문제점: 현재 모델 성능이 매우 좋지 않은 상태이며 인코딩과 스케일링등 다양한 시도를 하였으나\
        결국 데이터의 문제로 보여짐.\
        다양한 사이트에서 여러 데이터를 가져와 사용하였기 때문에\
        데이터가 고르지 못하고 극단값이 많이 존재하여 중앙값으로 모델을\
        학습시키는 방안을 생각중입니다.

수정한것: 데이터의 기존의 매출단위를 k 에서 m 으로 변경하였었으나 단위가 커져버려 변강하지 않는 쪽으로 하였습니다.\
          라벨 인코딩(머신러닝)과 원핫인코딩(딥러닝)을 모델별로 다르게 사용해 보았는데 성능이 좋지않아\
          인코딩후 스탠다드 스케일을 적용하여서 조금이나마 향상 시켰습니다.
          
