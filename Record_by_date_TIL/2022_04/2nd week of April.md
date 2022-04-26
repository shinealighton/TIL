# Record by date _ TIL
- 공부한 내용을 날짜별로 간단하게 기록한 것이다.
---
## 2nd week of April 2022 (2022년 4월 2째주)

### 2022.04.11
- github 사용법 공부
   - 매일 공부한 내용을 github에 작성하는 'TIL(Today I Learned)'에 대해 알았고, 실천하기 위해 만들었다.
   - 앞으로 Github 사용하기 위해 repository 생성 및 기본적인 관리(README, .gitignore 파일 생성)
   - repository생성, git생성, github의 repository와 연결, add, commit, push, pull을 반복하면서 익숙해지도록 실습했다. 

### 2022.04.12
- <오늘 한 것> : 
   - kaggle의 ['01_Titanic__EDA To Prediction(DieTanic)'](https://github.com/shinealighton/Study/tree/main/kaggle_study/01_Titanic__EDA%20To%20Prediction(DieTanic))을 작성하며 공부

- [<배운것>](https://github.com/shinealighton/TIL/tree/main/Study_Collection) : 

   #### 1. EDA(Exploratory Data Analysis) : 탐색적 데이터 분석

   - EDA 개념 :
      - 수집한 데이터(raw data)를 다양한 각도에서 관찰하고 이해하는 과정.
      - 즉, 데이터 분석 전, 그래프나 통계적인 방법으로 자료를 직관적으로 바라보는 과정
   - 과정 : 
      - 데이터를 전체적오로 살피기 (head, tail 부분 확인)
      - 이상치, 결측치 확인, 수치형/범주형 등 확인
      - 데이터의 각 feature값 관찰
      - feature들 간의 관계를 관찰하여 패턴 확인 (상관관계, 시각화 등)
      
         > 참고자료 : - 김현우, "EDA (Exploratory Data Analysis) 탐색적 데이터 분석.", TEAM EDA(티스토리), last modified September 16, 2018, https://eda-ai-lab.tistory.com/13

   #### 2. 경로  
   
      import os
      
      # <디렉토리 위치 확인 및 변경>
      # Python 현재 디렉토리 위치 
      print(os.getcwd()) #현재 위치해 있는 폴더 경로
      # 작업 디렉토리 변경
      os.chdir('변경할 경로')
      
      # <상대, 절대 경로>
      # 절대경로 : 고유한 경로. 한번에 해당 위치로 감.  : 전체 경로 작성
      # 상대경로 : 현재 위치 기준으로 그 안에 있는 특정 위치 지정. : ../현재경로기준에서 이동할 위치
         - os.chidr('../') # 상위 폴더로 이동
         - os.chdir('./하위폴더' # 하위폴더로 이동)

   #### 3. 데이터분석에 필요한 대표적인 라이브러리
   - 판다스(Pandas) : 데이터 분석 라이브러리로 데이터 프레임(Data Frame)을 활용하여 다양한 분석이 가능
   - 넘파이(Numpy) : 과학 연산을 돕는 라이브러리로 리스트, 배열 등을 빠르게 연산 가능
   - Matplotlib : 데이터 시각화를 돕는 라이브러리

      > 참고자료 : 코딩하는 마케터, "#4. 주피터 노트북 판다스 라이브러리 설치하기 (파이썬).", 마케터의 코딩스쿨(티스토리), last modified March 24, 2021, https://marketer-coding-school.tistory.com/entry/4-%EC%A3%BC%ED%94%BC%ED%84%B0-%EB%85%B8%ED%8A%B8%EB%B6%81-%ED%8C%90%EB%8B%A4%EC%8A%A4-%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC-%EC%84%A4%EC%B9%98%ED%95%98%EA%B8%B0-%ED%8C%8C%EC%9D%B4%EC%8D%AC.

- <개선할 것>
   - 문제 : 처음부터 개념을 하나씩 다 공부하면서 하니 시간이 너무 오래걸리는 문제 발생. 
   - 해결 방법 : 따라서 나눠서 해보자. 
      - 1) 먼저, kaggle 코드를 해석과 함께 쭉 작성해보면서 공부하기. (전체적인 흐름 파악) 
      - 2) 그 다음에 코드를 다시 보며 자세히 개념 공부. (자세한 개념 공부)

### 2022.04.12
- <오늘 한 것> : '2022 국제인공지능대전 (AI EXPO KOREA)' 참여.
   - 장소 : 서울 COEX 3층 Hall D
   - 일시 : 2022.04.13(수) ~ 2022.04.15(금)까지 개최 -> 13일(수)에 참석
   - 내용 : 박람회 부스 관람 + 세미나 참석

- #### <'2022 국제인공지능대전 (AI EXPO KOREA)' 세미나>
   - 1. 제목 : 
      - 장소 : 
      - 일시 : 
      - 강연자님 : 
      - 인상깊은 내용 : -> 공개 안될 경우. gitignore파일로 연결
      - 느낀점 : 

   - 2. 제목 : 
      - 장소 : 
      - 일시 : 
      - 강연자님 : 
      - 인상깊은 내용 : 
      - 느낀점 : 

---
## 3nd week of April 2022 (2022년 4월 3째주)

- #### 2022.04.19
- <오늘 한 것> : 
   - 프로젝트 계획 수립
   - face detection 개념 공부
   - face detection 구현
      - 1. OpenCV의 - Hear Cascade 로 얼굴 감지 실습
   - .
   - 즉,
   - **1. 얼굴 인식(이미지 -> 영상)**
    - **1-1. (이미지) 모든 사람의 얼굴 인식** 
        - **<1. 모델 선정 및 개념공부>**
        - 1) 따라해볼 프로젝트 모델, 개념, 자료 찾기
        - 2) 프로젝트 따라해보기
            - (OpenCV - Hear Cascade)
                - 실습1. 1. 따라하기 프로젝트 : 제목 : [OpenCV로 얼굴 감지] - Hear Cascade
                    - (그대로 공부)
                    
- #### 2022.04.21
- <오늘 한 것> : 
   - Hear Cascade 알고리즘 실습했던 것과 참고자료들 참고해서 나의 data로 조금씩 수정하며 face detection 구현해보기
   - 다른 모델 선택
   - .
   - 즉,
       - 실습2. 2. 따라하기 프로젝트 : 제목 : [OpenCV강좌 - Haar Cascades에 대해 알아보자] - Hear Cascade
           - (+ 3가지 자료 적용하여 작성. 내 data 사용. 조금 변형)
       - 3) 다른 모델 선택

---
## 4nd week of April 2022 (2022년 4월 4째주)

- #### 2022.04.25
- <오늘 한 것> : 
   - 이전 'Hear Cascade' 알고리즘을 사용했을 때의 문제점 등을 보완하여, face detection을 구현하기 위해 
   - 다른 알고리즘을 이용한 프로젝트 자료 검색, 마스크 써도 인식할 수 있는 data 검색 함.
   - . 
   - 즉,
   - <- 1-1. (이미지) 모든 사람의 얼굴 인식> 중
      - 3) 다른모델 선택하기

- #### 2022.04.26
- <오늘 한 것> : 
   - face detection을 하기 위해 사용할 알고리즘을 찾기 위해 다양한 알고리즘 종류와 각 개념을 공부했다. 
   - (전체 개념 공부, 그 중에서도 CNN, ReNet 중심으로 더 공부 진행)
   - .
   - 즉,
   - <- 1-1. (이미지) 모든 사람의 얼굴 인식> 중
   - 3) 다른 모델 선택 (마스크 쓴 사람도 인식되도록)
      - (0.) 객체 검출 알고리즘 종류 및 개념
         - 객체 검출에 사용할 수 있는 알고리즘 종류와 각각의 개념 공부 : 
            - CNN : CNN -> R-CNN -> Fast R-CNN -> Faster R-CNN
            - YOLO : YOLOv1 -> YOLOv2 -> YOLOv3 -> YOLOv4 -> YOLOv5
            - VGGNET : VGG16, VGG19
            - ResNet
   
   
