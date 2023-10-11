--------------------------------------------------------
코드를 실행하기 전에 하기 사항을 숙지해 주세요.
--------------------------------------------------------

1. _preprocessing.ipynb

- 해당 파일은 온라인/오프라인 두 가지 버전으로 구성되어 있습니다. 
- 해당 파일은 데이터를 전처리하여 csv파일을 추출하기 위한 실행 파일이며, 추출된 csv파일은 모두 첨부하였습니다. 
- 전처리에 긴 시간이 소요되어, 실행 시 이점 고려부탁드립니다.
- 전처리 파일을 실행하지 않으신다면 하기 csv 파일들을 참조하여 _model.ipynb 파일을 실행시켜 주십시오.


# _preprocessing.ipynb 실행 시, 실행 시간을 단축시켜주는 csv파일 목록 

1) 온라인 
- online_buyam.csv
- online_buycnt.csv
- on_one_custs_df.csv 

2) 오프라인 
- offline_buyam.csv
- offline_buycnt.csv
- off_one_custs.pickle



# _model.ipynb 실행 시, 필요한 csv파일 목록 

1) 온라인 
- on_buyam_normal_final.csv
- on_buycnt_normal_final.csv
- purchase_online.csv 

2) 오프라인 
- off_buyam_normal_final.csv
- off_buycnt_normal_final.csv
- purchase_offline_nofood.csv

"""

2. _model.ipynb

- 해당 파일은 모델링이 완료된 파일이며 
- 위의 전처리된 csv파일을 읽어드려 실행됩니다. 
- 온라인/오프라인으로 구성되어 있습니다. 
(oneline_model.ipynb / offline_model.ipynb)

