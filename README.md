

<br>

# 프로젝트 소개

이 프로젝트는 React를 사용하여 만든 퀴즈 앱입니다. 
`vite`을 통해 기본적인 프로젝트 환경을 구성했습니다.

간단하게 만드는 프로젝트인만큼 `next.js`와 같은 서버사이드렌더링을 도와주는 프레임워크까지는 불필요하다 생각해 `vite`를 사용하였습니다.
사용자 경험을 향상시키기 위해 시간 제한과 즉각적인 피드백을 제공하는 것이 핵심입니다. 또한 코드는 모듈화되어 있어서 쉽게 유지보수할 수 있습니다.


# Stack



 <img src="https://img.shields.io/badge/npm-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white">


 <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=white">

 <img src="https://img.shields.io/badge/vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">


 <img src="https://img.shields.io/badge/eslint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white">

 <img src="https://img.shields.io/badge/prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=white">



<br>

# 웹페이지 영상
![quiz](https://github.com/jungo0/Shopping-Project/assets/81670100/93224ee2-3b23-42d7-bae9-e456031fd837)

|

### 기능
<br>

1. 퀴즈:
   
- 퀴즈는 여러 개의 질문으로 구성됩니다.
- 각 질문은 텍스트 형식으로 제공됩니다.
- 사용자는 각 질문에 대한 답변을 선택할 수 있습니다.
<br>

3. 타이머:
   
- 각 질문에는 타이머가 포함되어 있습니다.
- 타이머는 일정 시간(보통은 10초) 동안 사용자에게 답변을 선택할 기회를 부여합니다.
- 시간이 초과되면 사용자가 답변을 제출하지 않은 경우 기본값이 선택됩니다.
<br>

4. 질문 선택:
   
- 사용자가 질문에 대한 답변을 선택하면 즉시 피드백을 받습니다.
- 정답이면 초록색, 오답이면 빨간색으로 표시됩니다.
- 피드백은 사용자가 답을 제출하거나 타이머가 만료되었을 때 표시됩니다.
<br>

6. 요약:
   
- 퀴즈가 종료되면 사용자에게 결과가 요약되어 보여집니다.
- 각 질문에 대한 사용자의 답변과 정답이 표시됩니다.
- 사용자의 전반적인 성적이 표시되어 퀴즈의 결과를 요약합니다.


