---
published: true
layout:         single ## 여러 레이아웃이 있다. "single", "splash" ...
title:          작업 환경 설정 ## 포스트 제목
category:       React ## 포스트 카테고리
tags:           ## 포스트 태그
comments:       ## 댓글 기능
---

### 설치 순서
1. Node.js/npm, yarn 설치하기
   - Node.js를 설치하면 Node.js 패키지 매니저 도구인 npm이 설치됨 
   
2. 코드 에디터 설치하기
   - 코드 에디터는 VS Code를 사용
   - VS Code 확장 프로그램 설치
      - ESLint
      - Reactjs Code Snippets
      - Prettier-Code formatter
      
3. Git 설치하기
   ```
   sudo apt-get install git-all
   ```
4. create-react-app으로 프로젝트 만들기    
   ```
   npm init react-app <프로젝트명>
   ```
   
### 프로젝트 생성 완료 후
   ```
   cd <프로젝트명>
   npm start
   ```

### 결과
브라우저에 자동으로 리액트 페이지가 띄워짐
만약 페이지가 자동으로 열리지 않았다면 브라우저 주소창에 링크를 직접 
- https://localhost:3000/








