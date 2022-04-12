# Collect What I study (공부한 것을 모아둔 곳이다.)
- Study_Collection

## * Python

   ### 1. [ 경로 설정. 확인. (+ 상대/절대 경로) ]
    
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

---

## * 머신러닝. 딥러닝
    
   ### 1. [ EDA(Exploratory Data Analysis) : 탐색적 데이터 분석 ]

    - EDA 개념 :
        - 수집한 데이터(raw data)를 다양한 각도에서 관찰하고 이해하는 과정.
        - 즉, 데이터 분석 전, 그래프나 통계적인 방법으로 자료를 직관적으로 바라보는 과정
    - 과정 : 
        - 데이터를 전체적오로 살피기 (head, tail 부분 확인)
        - 이상치, 결측치 확인, 수치형/범주형 등 확인
        - 데이터의 각 feature값 관찰
        - feature들 간의 관계를 관찰하여 패턴 확인 (상관관계, 시각화 등)
        
        > 참고자료 : - 김현우, "EDA (Exploratory Data Analysis) 탐색적 데이터 분석.", TEAM EDA(티스토리), last modified September 16, 2018, https://eda-ai-lab.tistory.com/13


   ### 2. [ 데이터분석에 필요한 대표적인 라이브러리 ]

    - 판다스(Pandas) : 데이터 분석 라이브러리로 데이터 프레임(Data Frame)을 활용하여 다양한 분석이 가능
    - 넘파이(Numpy) : 과학 연산을 돕는 라이브러리로 리스트, 배열 등을 빠르게 연산 가능
    - Matplotlib : 데이터 시각화를 돕는 라이브러리

        > 참고자료 : 코딩하는 마케터, "#4. 주피터 노트북 판다스 라이브러리 설치하기 (파이썬).", 마케터의 코딩스쿨(티스토리), last modified March 24, 2021, https://marketer-coding-school.tistory.com/entry/4-%EC%A3%BC%ED%94%BC%ED%84%B0-%EB%85%B8%ED%8A%B8%EB%B6%81-%ED%8C%90%EB%8B%A4%EC%8A%A4-%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC-%EC%84%A4%EC%B9%98%ED%95%98%EA%B8%B0-%ED%8C%8C%EC%9D%B4%EC%8D%AC.

