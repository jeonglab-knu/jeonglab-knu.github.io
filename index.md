---
---

# 과학계산연구실

강원대학교 과학계산연구실(Scientific Computing Laboratory)에 오신 것을 환영합니다.
우리 연구실은 정다래 교수의 지도 아래 수치해석(Numerical Analysis)을 연구합니다.
수학 모델을 컴퓨터로 정확하고 효율적으로 풀어내는 계산 방법을 개발하고 분석합니다.

{% include section.html %}

## 둘러보기

{% capture text %}

수치해석을 중심으로 한 우리 연구실의 연구 주제와 논문을 소개합니다.

{%
  include button.html
  link="research"
  text="논문 보기"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="연구"
  text=text
%}

{% capture text %}

우리 연구실에서 진행하고 있는 연구 프로젝트를 소개합니다.

{%
  include button.html
  link="projects"
  text="프로젝트 보기"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="프로젝트"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

과학계산연구실을 함께 만들어 가는 사람들을 소개합니다.

{%
  include button.html
  link="team"
  text="구성원 보기"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="구성원"
  text=text
%}
