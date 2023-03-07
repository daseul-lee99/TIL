# 마크다운 활용법

<h5> 출처 </h5>

[마크다운(Markdown) 사용법 총 정리](https://poetic-code.tistory.com/99)





- 줄바꿈: `<br>`, `Shift + Enter`

- 문단: `<p></p>`

- 제목: `# 개수로 조절`

    # H1

    ## H2

    ### H3

    #### H4

    ##### H5

    ###### H6

<br>

- 구분선: `---`, `___`, `***`

    하이픈

    ---

    언더스코어

    ___

    애스터리스크

    ***

<br>

- 순서없는 목록: `*`, `+`, `-`, `처음 작성 후 Shift, Sift+Tab 으로 단계 조절`

* ORDER 1
  * ORDER 1-1
  * ORDER 1-2
    * ORDER 1-2-1
  * ORDER 2

<br>

- 순서있는 목록: `1. 2. 3.`, `처음 작성 후 Shift, Sift+Tab 으로 단계 조절`
  1. ORDER 1
  2. ORDER 2
     1. ORDER 2-1
  3. ORDER 3

<br>

- 강조: `*, _ 로 강조하고 싶은 부분 감싸기`, `1개: 이탤릭, 2개: 볼드, 3개: 이탤릭+볼드`

    Hello *World*

    Hello **World**

    Hello ***World***

<br>

- 인용: `>`, `#, * 등 조합 가능`

    > 인용구
    >
    > # H1 조합

    > > 이중 인용구

<br>

- 인라인 링크: `[화면에 표시될 글자](URI, "툴팁")`

    [마크다운(Markdown) 사용법 총 정리](https://poetic-code.tistory.com/99)

<br>

- 이미지 링크: `![화면에 표시될 글자](URI "툴팁")`

    ![강아지](C:\Users\nonghyup\Desktop\mine\typora\puppy.png)

<br>

- 특수문자 표기: `특수문자 앞에 \`

    \# H1

    \* ORDER1

<br>

- 인라인 코드 블럭: ` `` `

    `인라인 코드 블럭`

<br>

- 코드 블럭: ` ``` + ```, ~~~ + ~~~ `

    ```
    ​``` 코드
    블럭
    ```

    ~~~
    ​~~~ 코드
    블럭
    ~~~

    ```javascript
    언어 지정 코드 블럭 - javascript
    console.log("Hello");
    ```

<br>

- 테이블: `|, - 활용, : (정렬)`

    | 구분1 | 구분2 |
    |-|-|
    | 내용1 | 내용2 |
    | Hello | World |

    ```
    | 구분1 | 구분2 |
    |-|-|
    | 내용1 | 내용2 |
    | Hello | World |
    ```


<br>

- 목차: `[목차명](#링크가-걸릴-텍스트). 문서 내 헤딩 태그 기준으로 생성`

    # 목차

    - [마크다운 활용법](#마크다운-활용법)

<br>

- Badge

    [Badge](https://shields.io/)
    
    https://img.shields.io/badge/-Markdown-brightgreen

<br>

- 이모지

    [Emoji](https://gist.github.com/rxaviers/7360908)
    
    :smirk: