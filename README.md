# Kickstarter를 이용한 클라우드펀딩 성공요소 분석
:dollar: Cloud funding success factor analysis using Kickstarter  
  #WebCrawling #DecidionTree   
    
      
kickstarter 클라우드펀딩 홈페이지에서 프로젝트를 크롤링한 후 성공요소를 분석합니다. 성공, 실패한 프로젝트 데이터를 수집하여 DecisionTree학습 및 시각화를 통해 어떠한 Feature가 프로젝트 성공여부에 크게 영향을 끼치는지 확인합니다. 각 Feature가 얼마나 중요한지 평가하는 Feature importance 특성 중요도를 이용해 각 특성의 중요도를 파악합니다.  
  
## Dataset  
**킥스타터(Kickstarter)**  
+ 2009년 시작된 미국의 크라우드 펀딩 서비스  
+ 프로젝트에 기부하여 일정금액이 넘으면 돈을 제공하고, 목표액을 넘지 못하면 투자를 하지 않아도 된다.  
+ 투자자는 돈이 아닌 해당 시제품, 감사인사, 티셔츠, 작가와의 식사 등 다른 유무형 형태의 보상을 받는다.  

## Method  
  
 데이터 수집 > 데이터 전처리 > 패키지 및 데이터 로드 > 속성과 클래스 마킹 > 데이터 학습 > DecisionTree 표현 및 feature importance 시각화  

## Result  

프로젝트의 성공 여부에 가장 크게 영향을 미치는 feature는 후원자의 수 입니다.  
