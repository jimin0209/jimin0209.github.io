---
published: true
layout: single ## 여러 레이아웃이 있다. "single", "splash" ...
title: 1주차 위클리 페이퍼 ## 포스트 제목
category: Sprint ## 포스트 카테고리
tags: ## 포스트 태그
comments: ## 댓글 기능
---

### CSS의 Cascading에 대해 설명해 주세요.

## CSS란?

Cascading Style Sheet의 약자이다. 이는 마크업 언어가 실제 표시되는 방법을 기술하는 스타일 언이다.

## Cascading이란?

Cascade는 계단식 형태의 폭포를 의미한다.
CSS에서 Cascading은 여러 CSS 규칙이 적용될 순서에 따라 합치는 것이다.
한 마디로, 규칙을 순서에 따라 계단식으로 합치는 것이다.

---

### Cascade 순서(우선순위)

**1. 스타일 시트의 종류**
인라인스타일(HTML에 직접 작성) > 스타일 시트(Style.css) > user agent stylesheet(브라우저 기본 css)

**2. 코드상의 순서**
똑같은 선택자를 쓰는 경우에는 나중에 적은 코드가 우선 순위가 높다.

**3. 선택자의 명시도(Specificity)**
선택자마다 점수가 있고, 점수가 높을 수록 우선 순위가 높다.
VS code에서 선택자에 마우스를 올려보면 명시도를 확인할 수 있다.
선택자가 복잡할 수록 명시도 점수가 높다.
[참고: 명시도 계산하는 도구 사이트]
https://specificity.keegan.st/
