---
title:  "나의 첫번째 글"
excerpt: "깃허브 블로그 글 작성하는 방법"

categories:
- Blog

toc: true
toc_sticky: true

date: 2022-12-14
---
## 머리말 작성  
글을 작성하기에 앞서 머리말을 작성해주어야 한다.
```
---
        title:  "여기에 제목을 적어"
        excerpt: "여기에는 한 줄 요약"

        categories:
        - Blog //여기에 카테고리명을 적어
        tags:
        - [Blog, jekyll, Github, Git] //이건 말그대로 태그들

        toc: true //목차 나오게 할 건지?
        toc_sticky: false //스크롤 하는 대로 목차 따라다니게 할 건지

        date: 2022-12-14 //작성일
        last_modified_at: 2022-12-14 //마지막 수정일
---
```
태그때문에 자꾸 오류가 나는데,,? 지우니까 잘 됨..  
아니 그래서 글을 어떻게 쓰는 거야..  
일단 스페이스 두 번 + 엔터 하면 다음줄에서 글 쓸 수 있다함...

>인용도 할 수 있음. ">" 입력하면 된다.. (따옴표 빼고)

## 링크 거는 방법?
아는거 하나 나왔다. 이건 벨로그에서 해 봄.
### 1. 커스텀 링크
[코테없이 취업하는 방법](https://media.giphy.com/media/KDRv3QggAjyo/giphy.gif "날 눌러")  
[] 이 안에 코테없이~ 적고 (여기에 url 적으면 됨)

### 2. 그냥 URL로 바로 연결
<https://o-sulloc.github.io>  
<> 이 안에 적으면 됨.
