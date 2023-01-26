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

내용: 커져가는 게임시장의 분야별 수요를 예측하여 게임회사에서 게임을 제작할때\
제작의 방향성을 잡기위하여 머신러닝,딥러닝 모델을 이용하여 시장을 분석,예측 하였습니다.

ppt: \
![image](https://user-images.githubusercontent.com/93918673/214781775-3ca62674-b001-49bb-925a-2ed21e293853.png)
![image](https://user-images.githubusercontent.com/93918673/214782006-b6667ae0-fcc5-42fd-82da-035988de2ba7.png)
![image](https://user-images.githubusercontent.com/93918673/214782036-fc20700d-b434-4fd0-b828-39076f9f545e.png)
![image](https://user-images.githubusercontent.com/93918673/214782054-61812bc1-a838-4b14-a04d-49ed21842928.png)
![image](https://user-images.githubusercontent.com/93918673/214782074-de38f9b3-a4b0-4beb-88a2-61f5546020ab.png)
![image](https://user-images.githubusercontent.com/93918673/214782088-1d703c1f-34b7-4024-a4ac-352d86e75749.png)
![image](https://user-images.githubusercontent.com/93918673/214782108-672f7f4c-cba1-44e5-bf46-2bbb0f668ff6.png)
![image](https://user-images.githubusercontent.com/93918673/214782134-64ccb5c1-193c-4020-aaea-91e17d54b859.png)
![image](https://user-images.githubusercontent.com/93918673/214782160-eb87569b-d8c2-4edb-8282-037f951ba786.png)


수정한것: 데이터의 기존의 매출단위를 k 에서 m 으로 변경하였었으나 단위가 커져버려 변강하지 않는 쪽으로 하였습니다.\
          라벨 인코딩(머신러닝)과 원핫인코딩(딥러닝)을 모델에 따라 다르게 사용해 보았습니다. 그 뒤 성능을 더 향상시키기 위해\
          인코딩후 스탠다드 스케일을 적용하여 조금 향상 시켰습니다.
          
