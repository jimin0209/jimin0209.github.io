---
published: true
layout: single ## 여러 레이아웃이 있다. "single", "splash" ...
title: 코드 이해하기 ## 포스트 제목
category: React ## 포스트 카테고리
tags: ## 포스트 태그
comments: ## 댓글 기능
---

### 코드 이해하기

```javascript
import React from "react";
```

-   이 코드는 리액트를 불러와서 사용할 수 있게 해 줌
-   리액트 프로젝트를 만들 때 node_modules라는 디렉토리도 함께 생성됨
-   Node.js에서는 import가 아닌 require라는 구문으로 패키지를 불러옴
    <br/>
    <br/>
    <br/>

```javascript
import logo from "./logo.svg";
import "./App.css";
```

-   SVG 파일과 CSS 파일을 import하는 코드
-   리액트를 불러오는 코드 하단에 있음
-   이렇게 파일들을 불러오는 것은 웹팩의 로더(loader)라는 기능이 담당함
    <br/>
    <br/>
    <br/>

```javascript
function APP() {
    return (
        <div className="APP">
            <header className="App-header">
                <img src={logo} className="App-logo" alt="logo" />
                <p>
                    Edit <code>src/APP.js</code> and save to reload.
                </p>
                <a className="App-link" href="https://reactjs.org" target="_blank" rel="noopener noreferrer">
                    Learn React
                </a>
            </header>
        </div>
    );
}
```

-   App이라는 컴포넌트를 만들어 줌
-   function 키워드를 사용하여 만든 컴포넌트 → 함수형 컴포넌트
-   프로젝트에서 컴포넌트를 렌더링(렌더링이란 보여준다는 것을 의미)하면 함수에서 반환하고 있는 내용을 나타냄
-   함수에서 반환하는 내용을 보면 HTML 같지만, HTML이 아니고 문자열 템플릿도 아님
-   이런 코드는 JSX라고 부름

jsx
sdfaffa
