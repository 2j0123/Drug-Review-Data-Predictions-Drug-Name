# WASSUP_Project_Team7_2
## Drug Data
<br/>

### Drug_Data_EDA.ipynb
<br/>

### Drug_Data_Preprocess.ipynb
**결측치 제거**

**'review'**
* [X] html 코드 텍스트 제거 
* [X] apostrophe 제거
* [X] 숫자와 영어 알파벳을 제외한 모든 문자 공백으로 대체
* [X] 숫자와 수치형 단위 제거
* [X] 소문자로 변환
* [X] 토큰화
* [X] 불용어 제거
* [X] Lemmatization
* [X] 공백 수정 및 토큰 연결
* [X] Stemming
* [X] 길이 100이상 리뷰 행 제거
* [ ] Padding
* [ ] Embedding

**'condition'**
* [X] html 코드 텍스트 제거 
* [X] apostrophe 제거
* [X] 숫자와 영어 알파벳을 제외한 모든 문자 공백으로 대체
* [X] 소문자로 변환
* [X] 토큰화
* [X] 공백수정
* [X] Stemming 
* [ ] Padding
* [ ] Embedding

**'drugName'**
* [X] Label Encoding

**'rating'**
* [X] 파생변수 'sentiment' 생성

**'useCount'**
* [X] 파생변수 'uC_rank' 생성

**'date'**
* [X] datetime 형식으로 수정한 'fixed date' 생성

**'fixed_condition', 'fixed_review'**
* [X] 'fixed_condition', 'fixed_review'이 모두 빈 리스트인 행 제거
* [X] 결합
* [X] 등장 빈도 3회 미만 단어 제거

### Drug_Data_Modeling.ipynb
**TPOT**