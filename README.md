# kaggle_survey2021
2021년 캐글 설문조사 데이터분석 공모전

# 참여인원
이름|깃헙주소
--|--
김기훈|https://github.com/Sep-eg
김진우|
박주윤|https://github.com/xper100
박지영|
정은지|


# 데이터 이름
데이터프레임 또는 컬럼명을 명시할 때 사용할 이름들입니다. **협업 시 통일된 명칭을 사용하여 작업이 용이할 수 있도록 참고**해주시기 바랍니다! 

## 데이터프레임
**데이터프레임명은 'response'**로 해주세요! 
ex) response = pd.DataFrame('kaggle_survey_2021_responses.csv')

## 설문지
**각 설문지(컬럼)마다 정의된 이름**입니다.

설문지번호 | 사용할 명칭 | 설명 | 특이사항
:--|:--|:--|:--
Q1 | Age |  나이 | 
Q2 | Gender |  성별 | 
Q3 | Country |  국적 | 
Q4 | FormalEducation | 최종학력  | 
Q5 | JobTitle  | 직함 | 
Q6 | YearsToCode  | 프로그래밍 또는 코드 사용기간 | 
Q7 | Language_regular | 일반적으로 사용하는 기간  | 
Q8 | Language_first | 데이터사이언스로서 추천하는 언어 | 
Q9 | IDE | 사용하는 소프트웨어 어플리케이션 인터페이스(IDE) | 
Q10 | Notebook | 사용하는 Notebook ex) Jupyter Notebook, Kaggle Notebook, etc. | 
Q11 | Computer  | 사용하는 컴퓨터 또는 컴퓨팅 플랫폼 ex) labtop, NVIDIA, etc. | 
Q12 | Hardware | 딥러닝을 위해 사용하는 하드웨어 (TPU, GPU, etc)  | 
Q13 | Duration_TPU | TPU 사용한 횟수 | 
Q14 | Vis_library  | 평소에 사용하는 시각화 라이브러리 | 
Q15 | Years_ML_Method | ML 방법론을 사용한 년수 | 
Q16 | ML_framework | 사용하는 ML 프레임워크 ex) TensorFlow, Keras, Scikit-learn, etc. | 
Q17 | ML_algorithm | 사용하는 ML 알고리즘 |  
Q18 | Method_CV  | 사용하는 컴퓨터비전 방법론 | Q17에서 관련된 선택지를 골랐을 때
Q19 | Method_NLP | 사용하는 장연어처리 방법론| Q17에서 관련된 선택지를 골랐을 때
Q20 | JobIndustry  | 현재 종사하는 산업 |
Q21 | CompanySize | 회사규모 | 
Q22 | Num_Workloads |  사내 데이터사이언스 관련 업무에 종사하는 직원 수 | 
Q23 | ML_Applied  |  사내에 머신러닝 방법을 비즈니스에 접목시키는가? | 
Q24 | Activities_role |  맡은 업무 중 데이터와 관련된 내용은? | 
Q25 | Year_Compensation  |  연봉 ($USD) | 
Q26 | Spent_amount_ML   |  5년간 머신러닝 또는 관련 서비스에 투자한 총 금액  | 
Q27 | Cloud_platform  | 사용하는 클라우드 플랫폼 | 
Q28 | Best_Cloud_platform   | 사용하는 클라우드 플랫폼 중 가장 좋았던 플랫폼  | Q27에서 2개이상 선택한 응답자  
Q29 | Use_Cloud_platform   |  사용하는 클라우드 컴퓨팅 제품 | Q27에서 AWS/Azure/GCP 를 사용한 응답자에 한해서 선택
Q30 | Use_Data_Storage  |  |  Q27에서 AWS/Azure/GCP 를 사용한 응답자에 한해서 선택
Q31 | Use_ML_product   |  사용하는 머신러닝 관련제품 | 
Q32 | BigData_product |  어떤 빅데이터 상품(관계형 데이터베이스, 데이터 웨어하우스, 데이터 호수 등)을 사용하는지 선택 | 
Q33 | Best_BigData_product  |  사용하는 빅데이터상품 중 가장 자주 쓰는 제품 | Q32를 2개이상의 제품을 선택한 응답자만 해당
Q34 | BI_Tool  |  사용하는 BI Tool |
Q35 | Best_BI_Tool   | 사용하는 BI Tool 중 가장 좋았던 제품  | Q34에서 2개이상 선택한 응답자만 해당
Q36 | AutoML_Tool  |  자동화 머신러닝 툴을 사용하는지 선택 | 
Q37 | Which_AutoML_Tool   |  자동화 머신러닝 툴을 사용하는지 선택  | Q36 질문지의 보완된 선택지로 어떤 AutoMl 툴을 사용하는지 선택(다중선택)
Q38 | ManageML  |  머신러닝 실험들을 도화줄 툴들을 사용하는가? | 
Q39 | PublicToDeploy  |   데이터분석 또는 머신러닝 앱을 배포하는 곳 | 
Q40 | PlatformToLear_DS  |   데이터사이언스를 배울때 사용했던 플랫폼 | 
Q41 | PrimaryTool  |  직장 또는 학교에서 데이터분석시 우선적으로 사용하는 도구 | 
Q42 | MediaSourceToLearn  |   데이터사이언스와 관련된 주제를 다루는 미디어 중 가장 선호하는 채널은? | 


