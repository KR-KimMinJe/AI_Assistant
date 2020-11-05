# Ⅰ. **개요**
*   개발 기간 : 2020.03.10 ~ 2020.05.21
*   개발 목적 : 사용자에게 보다 높은 효율의 학습 환경을 제공하고자<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;물리적인 교정이 아닌 각각의 사용자에 알맞은 자세, 집중 방향 제시
*   컴퓨터교육학회 2021년 1월 게재 확정
  
# Ⅱ. **동작 구성도**
<img src="https://user-images.githubusercontent.com/73852272/98143998-2a523a80-1f0d-11eb-9fd1-a04037a6c43a.png" width="400" hieght="400">

# Ⅲ. **개발환경**
<img src="https://user-images.githubusercontent.com/73852272/98143872-02fb6d80-1f0d-11eb-820b-2d17f9cfd335.png" width="400" hieght="400">

# Ⅳ. **주요기능**
### 1. 음성인식을 통한 제어
### 2. 시선판단을 통한 집중도 판단
### 3. 세그멘테이션을 통한 자세 분석

# Ⅴ. 세부기능
### 1. 음성인식 기반 편의 기능
<img src="https://user-images.githubusercontent.com/73852272/98150787-8bc8d800-1f12-11eb-85da-c781c35ccd3e.png" width="400" hieght="400">

*  '친구야' 단어로 음성제어
*  날씨 및 현재 시간 조회
*  Google, Youtube 검색
*  간단한 사칙연산
*  일정 관리

### 2. 집중도 판단
<img src="https://user-images.githubusercontent.com/73852272/98151426-7bfdc380-1f13-11eb-8d9a-052ae23fdeec.jpg" width="400" hieght="400">

* OpenCV 기반 LandMark68 Algorithm을 이용하여 눈의 개폐 횟수로<br>
 졸음판단 및 시선을 파악하여 집중 여부 확인

### 3. 자세 분석
<img src="https://user-images.githubusercontent.com/73852272/98152143-97b59980-1f14-11eb-9aa8-8eefd4051a47.png" width="400" hieght="400">

* 사용자의 주시 방향을 고려하여 유동적으로 머리, 등, 엉덩이의 기울어짐을 판단한다.

# Ⅵ. 자세분석 고려사항
<img src="https://user-images.githubusercontent.com/73852272/98157461-bae44700-1f1c-11eb-97d4-a41656fc7805.png" width="400" hieght="400">

* '사람' 객체와 '사람이 아닌' 객체의 구분이 명확하여야 한다.

<img src="https://user-images.githubusercontent.com/73852272/98157743-1f9fa180-1f1d-11eb-9998-4841291c1cd1.png" width="400" hieght="400">

* 다양한 각도, 자세에서도 동일한 Segmentation 성능이 유지되어야 한다.


# Ⅶ. 구현 동영상
*  Link = https://youtu.be/dMjOFrg5LDc

