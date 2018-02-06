# Baseball Analysis

<hr/>

 ### -  목적 : 본 프로젝트는 기초적인 ML 알고리즘 구현과 RDBMS를 연동하여 python 코드를 작성하는 연습을 함과 동시에, 선수들의 유형 분석, 성적과 흥행의 상관관계 등의 여러 Issue들에 대해 통계적 방법을 통해 분석해보는 데에 목적이 있다.
 
 <hr/>
 
 ### -  분석 순서 및 우선순위
 
  1. [Lahman.com의 MLB 데이터](http://www.seanlahman.com/baseball-archive/statistics/)를 mysql을 이용하여 db에 저장한다. 이 때 데이터는 현재의 양대리그 - 인터리그 형태가 시작된 94년도 이후의 데이터만을 사용한다.
  
  2. 데이터 분석
>    - 성적이 좋은 팀이 관중 흥행에 영향을 미치는가?
>    - 투수 / 타자별 선수들의 유형은 어떻게 나눌 수 있으며 그 유형은 어떤 유형인가?
>    - 한정된 자원(돈)으로 팀을 꾸려야 한다면 어떤 선수들을 영입해야 좋은 성적(혹은 흥행)을 달성할 수 있는가?
>    - 특정 선수가 새로 리그에 편입된다면, 그 선수의 적정 몸값은 어떻게 책정해야 하는가?
>    - 야구는 정말 '투수 놀음'인가? 타자들이 승리에 기여하는 정도와 투수들이 기여하는 정도는 어떻게 다른가?
    
  3. 분석 결과 정리
>    - django 워크프레임을 이용하여 웹 페이지 개발
>    - 가능하다면 AWS ec2를 이용하여 웹 페이지 호스팅