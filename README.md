# :heart: capstone_tire
<p align="center">
  <img src="https://github.com/cvivis/webSocket-Practice/assets/42718588/e0371e3b-9b08-4b1b-9eca-a4906f2f64da">
</p>

# 개요
## 프로젝트 배경
<div>
<p>기존 타이어 마모도 확인에 가장 많이 사용되는 방법으로 시각을 통해 어림짐작하여 판단하거나 동전을 넣어보는 방법이 널리 퍼져 있어 판단 결과는 판단자의 주관에 의해 많이 달라진다.

하지만 타이어는 자동차의 소모품 중에서 안전과 깊은 연관성을 갖고 있기에 적절한 시기에 교체하는 것이 매우 중요해 기존의 방식 대신 인공지능 학습을 통해 타이어의 마모도를 판단하는 모델을 만들어 사용하는 것을 생각하게 되었습니다.</p>
  
</div>

## 프로젝트 구성 

**프로젝트 명칭** : Board Service   
**개발 인원**: 4명  
**주요 기능 ** :  
- flutter 앱개발 
- AI 인공지능 개발 
형상관리 툴 : GitHub
간단 소개 : 타이어 사진을 찍어 AI를 통해 마모도를 파악해 사용자에게 알려주는 어플

# 💛 세팅
<img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=Dart&logoColor=white">
<img src="https://img.shields.io/badge/flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white">
<br>

# :orange_heart: 사용 라이브러리 
- image_picker : 카메라와 갤러리 불러오는 기능 구현 및 사진이 저장된 파일의 경로 접근을 손쉽게 하기 위해 사용하였다.
- dio :  A powerful Http client for Dart 라고 소개하고 있는 라이브러리로 http 처럼 서버와 통신을 하기 위해 필요한 패키지다. 사진 파일의 출력을 form-data로 처리하고 서버와 http 통신을 통해 모델의 api를 사용하기 위해 사용하였다. 
- async : Future 와 Stream 을 사용하여 비동기를처리한다. async 및 await와 같은 키워드를 사용한 비동기 코딩을 지원. 사진 파일과 api를 통해 받아온 모델 결과값을 비동기적으로 처리하기위해 사용하였다.
- io : files, directories, processes, sockets, WebSockets, and HTTP clients and 웹 servers를 다루는 API를 제공한다. 사진 파일의 경로 처리를 위해 사용하였다.

# 💚 UI

<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/42718588/202400523-64ec919e-35f5-4bcf-9540-1aded709a69b.jpeg" width="200" height="400"/></td>
    <td><img src="https://user-images.githubusercontent.com/42718588/202400418-12286187-1e34-4afb-a1ad-7dbccf26bfea.jpeg" width="200" height="400"/></td>
    <td><img src="https://user-images.githubusercontent.com/42718588/202400161-3f0fd33a-75d4-4c21-8965-68c1ad992c0b.jpeg" width="200" height="400"/></td>
  <tr>
  <br>
    <tr>
    <td><img src="https://user-images.githubusercontent.com/42718588/202400433-14775ac6-63f6-45dc-aa83-dc6876f1ecdf.jpeg" width="200" height="400"/></td>
    <td><img src="https://user-images.githubusercontent.com/42718588/202400498-6d07b37f-32ef-42c4-84ad-ee709ea13510.jpeg" width="200" height="400"/></td>
    <td><img src="https://user-images.githubusercontent.com/42718588/202400534-11fe548a-e452-4e96-bad1-fb1ec3e87d1d.jpeg" width="200" height="400"/></td>
    
  </tr>
  <tr>
  <td><img src="https://user-images.githubusercontent.com/42718588/202400549-0b0bb1da-87ee-4b4c-a907-7f97c84038ee.jpeg" width="200" height="400"/></td>
  </tr>
</table>

# 💙 Flow Chart
<img src="https://user-images.githubusercontent.com/42718588/202404526-d1ab32de-6b60-4367-9581-e9071df0a43d.png" width="1500" height="300"/>



