# README 파일 사용법
* **Git**에서는 **README.md** 파일을 이용해 **소개 및 설명서**를 작성할 수 있다.
* 확장자 **.md**는 **마크 다운(Markdown)** 의 약자로 다양한 분야에서 사용되고 있는 텍스트 양식이다.
* **마크 다운(Markdown)** 은 **HTML**로 변환이 가능하다. **특수기호**와 **문자**를 이용한 매우 간단한 구조의 문법을 사용하여 웹에서도 보다 빠르게 컨텐츠를 작성하고 보다 직관적으로 인식할 수 있다.
* **HTML** 문법과 혼용 가능하지만, 모든 HTML 마크업을 대신하지 못한다.

### README.md(마트 다운) 문법
* 아래 링크 클릭하면 해당 위치로 이동
1. [문서 제목 및 글머리 (Headers)](https://github.com/WONOBOT/github_study/tree/main/Github/README#1-%EB%AC%B8%EC%84%9C-%EC%A0%9C%EB%AA%A9-%EB%B0%8F-%EA%B8%80%EB%A8%B8%EB%A6%AC-headers)
2. [목록, 글머리 기호](https://github.com/WONOBOT/github_study/blob/main/Github/README/README.md#2-%EB%AA%A9%EB%A1%9D-%EA%B8%80%EB%A8%B8%EB%A6%AC-%EA%B8%B0%ED%98%B8)
3. [체크박스](https://github.com/WONOBOT/github_study/blob/main/Github/README/README.md#3-%EC%B2%B4%ED%81%AC%EB%B0%95%EC%8A%A4)
4. [수평선 (Horizontal Rules)](https://github.com/WONOBOT/github_study/blob/main/Github/README/README.md#4-%EC%88%98%ED%8F%89%EC%84%A0-horizontal-rules)
5. [링크](https://github.com/WONOBOT/github_study/blob/main/Github/README/README.md#5-%EB%A7%81%ED%81%AC)
6. [강조](https://github.com/WONOBOT/github_study/blob/main/Github/README/README.md#6-%EA%B0%95%EC%A1%B0)
7. [줄바꿈](https://github.com/WONOBOT/github_study/blob/main/Github/README/README.md#7-%EC%A4%84%EB%B0%94%EA%BF%88)
8. [인용구](https://github.com/WONOBOT/github_study/blob/main/Github/README/README.md#8-%EC%9D%B8%EC%9A%A9%EA%B5%AC)
9. [들여쓰기](https://github.com/WONOBOT/github_study/blob/main/Github/README/README.md#9-%EB%93%A4%EC%97%AC%EC%93%B0%EA%B8%B0)
10. [코드블럭](https://github.com/WONOBOT/github_study/blob/main/Github/README/README.md#10-%EC%BD%94%EB%93%9C%EB%B8%94%EB%9F%AD)
11. [표 (Table)](https://github.com/WONOBOT/github_study/blob/main/Github/README/README.md#11-%ED%91%9C-table)
12. [특수기호 (Backslash Escapes)](https://github.com/WONOBOT/github_study/blob/main/Github/README/README.md#12-%ED%8A%B9%EC%88%98%EA%B8%B0%ED%98%B8-backslash-escapes)
--------
#### 1. 문서 제목 및 글머리 (Headers)

* 큰 제목: 문서 제목
    ```
    H1 큰 제목
    =============
    ```
  * 결과

    H1 큰 제목
    =============

* 작은 제목: 문서 부제목
    ```
    H2 부제목
    -------------
    ```
  * 결과

    H2 부제목
    -------------

* 글머리 <br>
  글머리: 1~6까지만 지원

  | MD 문법 | HTML 문법 | 설명|
  |:--|:--|:--|
  |# H1|\<h1>H1\</h1>| 큰 제목 or 글머리1|
  |## H2|\<h2>H2\</h2>| 작은 제목 or 글머리2|
  |### H3|\<h3>H3\</h3>| 글머리3|
  |#### H4|\<h4>H4\</h4>| 글머리4|
  |##### H5|\<h5>H5\</h5>| 글머리5|
  |###### H6|\<h6>H6\</h6>| 글머리6|
  
  ```
  # H1
  ## H2
  ### H3
  #### H4
  ##### H5
  ###### H6
  ```
  * 결과
  # H1
  ## H2
  ### H3
  #### H4
  ##### H5
  ###### H6
  ####### H7(지원하지 않음)

  ```
  <h1>H1</h1>
  <h2>H2</h2>
  <h3>H3</h3>
  <h4>H4</h4>
  <h5>H5</h5>
  <h6>H6</h6>
  ```
  * 결과
  <h1>H1</h1>
  <h2>H2</h2>
  <h3>H3</h3>
  <h4>H4</h4>
  <h5>H5</h5>
  <h6>H6</h6>
  <h7>H7</h7>(지원하지 않음)

----------
#### 2. 목록, 글머리 기호
* 순서있는 목록(번호)
    - 순서있는 목록은 숫자와 점 `1.` 또는 숫자와 소괄호 `1)` 를 혼용 사용 가능 <br>
      2개 이상의 목록 쓸때 `1.`와 `1)` 섞어 사용 가능
    ```
    1. 목록 1
    2. 목록 2
    3. 목록 3

    1) 목록 1
    2) 목록 2
    3) 목록 3

    1. 첫번째 목록 1
    2. 첫번째 목록 2

    1) 두번째 목록 1
    2) 두번째 목록 2
    
    1. 세번째 목록 1
    2. 세번째 목록 2
    ```
    
    * 결과
1. 목록 1
2. 목록 2
3. 목록 3

1) 목록 1
2) 목록 2
3) 목록 3

1. 첫번째 목록 1
2. 첫번째 목록 2

1) 두번째 목록 1
2) 두번째 목록 2

1. 세번째 목록 1
2. 세번째 목록 2

    - 중간에 다른 번호가 있어도 내림차순으로 나옴
    ```
    1) 목록 1
    3) 목록 3
    2) 목록 2
    ```

    * 결과    
1) 목록 1
3) 목록 3
2) 목록 2

    - 하위 목록은 여백(space bar) 3개 혹은 Tap 으로 구분
    ```
    1. 목록 1
        1. 소목록 1
        2. 소목록 2
            1. 소목록 1
            2. 소목록 2

    1) 목록 1
        1) 소목록 1
        2) 소목록 2
            1) 소목록 1
            2) 소목록 2

    1. 목록 1
        1) 소목록 1
        2) 소목록 2
            1. 소목록 1
            2. 소목록 2
    ```

    * 결과
1. 목록 1
    1. 소목록 1
    2. 소목록 2
        1. 소목록 1
        2. 소목록 2

1) 목록 1
    1) 소목록 1
    2) 소목록 2
        1) 소목록 1
        2) 소목록 2

1. 목록 1
    1) 소목록 1
    2) 소목록 2
        1. 소목록 1
        2. 소목록 2

* 순서없는 목록(글머리 기호: `*`, `+`, `-` 지원) <br>
같은 기호로 입력해도 되고, 기호들을 혼합해서 사용 가능 <br>
글머리 기호도 하위 목록은 탭 1개나 여백(space bar) 3개부터 감소
    ```
    * 글머리 기호 1
        * 글머리 기호 2
            * 글머리 기호 3

    + 글머리 기호 1
        + 글머리 기호 2
            + 글머리 기호 3

    - 글머리 기호 1
        - 글머리 기호 2
            - 글머리 기호 3

    * 혼합 글머리 기호 1
        - 혼합 글머리 기호 2
            + 혼합 글머리 기호 3
    ```
    
    * 결과
* 글머리 기호 1
    * 글머리 기호 2
        * 글머리 기호 3

+ 글머리 기호 1
    + 글머리 기호 2
        + 글머리 기호 3

- 글머리 기호 1
    - 글머리 기호 2
        - 글머리 기호 3

* 혼합 글머리 기호 1
    - 혼합 글머리 기호 2
        + 혼합 글머리 기호 3

----------
#### 3. 체크박스
* 대괄호 `[`, `]`앞뒤로 space(여백) 입력 필수
    ```
    - [ ] 체크박스(false)
    - [x] 체크박스(true)
    ```
    
    * 결과
    - [ ] 체크박스(false)
    - [x] 체크박스(true)

----------
#### 4. 수평선 (Horizontal Rules)
* 아래 줄은 모두 수평선, 마크다운 문서를 미리보기로 출력할 때 **페이지 나누기** 용도로 많이 사용

    ```
    * * *

    ***

    *****

    - - -

    ---------------------------------------
    ```
    * 결과
    * * *

    ***

    *****

    - - -

    --------------------------------------- 
    <br>

----------
#### 5. 링크
* 참조링크

    ```
    [link keyword][id]

    [id]: URL "Optional Title here"

    // code
    Link: [Google][googlelink]

    [googlelink]: https://google.com "Go google"
    ```
    * 결과

    Link: [Google][googlelink]

    [googlelink]: https://google.com "Go google"

* 외부링크
    ```
    사용문법: [Title](link)
    적용예: [Google](https://google.com, "google link")
    ```

    * 결과
    
    Link: [Google](https://google.com, "google link")

* 자동연결
    ```
    일반적인 URL 혹은 이메일주소인 경우 적절한 형식으로 링크를 형성

    외부링크: <http://example.com/>
    이메일링크: <address@example.com>
    ```

    * 결과
    
    외부링크: <http://example.com/> <br>
    이메일링크: <address@example.com>

----------
#### 6. 강조
* 문장 중간에 사용할 경우에는 띄어쓰기를 사용하는 것이 좋음
    ```    
    *기울임체*
    _기울임체_
    **볼드체**
    __볼드체__
    ***기울임 볼드체***
    ___기울임 볼드체___
    ~~취소선~~
    
    문장 중간에 사용할 경우에는 **띄어쓰기** 를 사용하는 것이 좋음
    ```
    * 결과 <br>

    *기울임체* <br>
    _기울임체_ <br>
    **볼드체** <br>
    __볼드체__ <br>
    ***기울임 볼드체*** <br>
    ___기울임 볼드체___ <br>
    ~~취소선~~ <br>

    문장 중간에 사용할 경우에는 **띄어쓰기** 를 사용하는 것이 좋음
----------
#### 7. 줄바꿈
* 줄바꿈을 하지않으면 Enter를 입력해도 문장이 이어서 나옴
  | MD 문법 | HTML 문법 |
  |:--|:--|
  |'_ _ _'|\<br>|
    ```
    1. 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다. 
    이렇게

    2. 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다._ _ _\\ 띄어쓰기
    이렇게

    3. 줄 바꿈을 하기 위해서는 문장 마지막에서 \<br>을 쓴다. <br>
    이렇게
    ```
    * 결과 <br>
    1. 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다.
    이렇게
    2. 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다.    \
    이렇게
    3. 줄 바꿈을 하기 위해서는 문장 마지막에서 **\<br>** 을 쓴다. <br>
    이렇게

----------
#### 8. 인용구
* 이메일에서 사용하는 ```>``` 블럭인용문자를 이용
    ```
    > 첫번째 인용구
    >	> 두번째 인용구
    >	>	> 세번째 인용구
    ```

    * 결과
    > 첫번째 인용구
    >	> 두번째 인용구
    >	>	> 세번째 인용구

* 이 안에서는 다른 마크다운 요소를 포함할 수 있음
    ```
    > # H1 큰 제목
    > * 글머리 기호
    >	```
    >	code
    >	```
    ```
    
    * 결과
    > # H1 큰 제목
    > * 글머리 
    >	```
    >	code
    >	```

----------
#### 9. 들여쓰기
* 4개의 공백 또는 하나의 탭으로 들여쓰기를 만나면 변환되기 시작하여 들여쓰지 않은 행을 만날때까지 변환됨
    ```
    This is a normal paragraph:

        This is a code block.

    end code block.
    ```

    * 결과 <br>
    
    This is a normal paragraph:

        This is a code block.

    end code block.

* 한줄 띄어쓰지 않으면 인식이 제대로 안되는 문제가 발생
    ```
    This is a normal paragraph:
        This is a code block.
    end code block.
    ```

    * 결과 <br>
    This is a normal paragraph:
        This is a code block.
    end code block.

----------
#### 10. 코드블럭
코드블럭은 다음과 같이 2가지 방식 사용가능

* `<pre><code>{code}</code></pre>` 이용방식
    ```
    <pre>
    <code>
    void main() {
        printf("Hello, world!");
    }
    </code>
    </pre>
    ```
    * 결과
    <pre>
    <code>
    void main() {
        printf("Hello, world!");
    }
    </code>
    </pre>

* 코드블럭코드("\```") 을 이용하는 방법

    <pre>
    <code>
    ```
    void main() {
        printf("Hello, world!");
    }
    ```
    </code>
    </pre>
    * 결과
    ```
    void main() {
        printf("Hello, world!");
    }
    ```

    **깃헙**에서는 코드블럭코드("\```") 시작점에 사용하는 언어를 선언하여 [문법강조(Syntax highlighting)](https://docs.github.com/en/github/writing-on-github/creating-and-highlighting-code-blocks#syntax-highlighting)이 가능 <br>
    | 언어 | 혼용가능 |
    |:--|:--|
    |Bash|bash|
    |C#|cs|
    |C++|cpp|
    |CSS|css|
    |Diff|diff|
    |HTML, XML|html|
    |HTTP|http|
    |Ini|ini|
    |JSON|json|
    |Java|java|
    |JavaScript|javascript|
    |PHP|php|
    |Perl|perl|
    |Python|python|
    |Ruby|ruby|
    |SQL|sql|
    
    <pre>
    <code>
    ```C++
    void main() {
        printf("Hello, world!");
    }
    ```
    </code>
    </pre>
    
    * 결과
    ```C++
    void main() {
        printf("Hello, world!");
    }
    ```
    ---
    <pre>
    <code>
    ```Python
    def hello():
    print('Hello, world!')
    
    hello()
    ```
    </code>
    </pre>
    
    * 결과
    ```Python
    def hello():
    print('Hello, world!')
    
    hello()
    ```
    ---
    <pre>
    <code>
    ```java
    public class BootSpringBootApplication {
      public static void main(String[] args) {
        System.out.println("Hello, world!");
      }
    }
    ```
    </code>
    </pre>
    
    * 결과
    ```java
    public class BootSpringBootApplication {
      public static void main(String[] args) {
        System.out.println("Hello, world!");
      }
    }
    ```

----------
#### 11. 표 (Table)
* 각 셀의 구분은 **파이프`|` 기호** 로 하며, **첫번째 줄 헤더(제목)** 아래 **두번째 줄에`|---|`** 을 입력해서 표(table) 입력임을 표시 <br>
  **(`---'는 개수 무관)**
    ```
    | 제목 1 | 제목 2 | 제목 3 | 제목 4 |
    |--------|-------|--------|--------|
    | 내용 1 | 내용 2 | 내용 3 | 내용 4 |
    | 내용 5 | 내용 6 | 내용 7 | 내용 8 |
    ```
    
    * 결과

    | 제목 1 | 제목 2 | 제목 3 | 제목 4 |
    |--------|-------|--------|--------|
    | 내용 1 | 내용 2 | 내용 3 | 내용 4 |
    | 내용 5 | 내용 6 | 내용 7 | 내용 8 |

* **두번째줄** 에  **`:`기호** 를 사용해 표 내부 글자를 정렬 할수 있음 <br>
  ex) **왼쪽 정렬 - `:--`, 가운데 정렬 - `:-:`, 오른쪽 정렬 - `--:`** <br>
  **(기본값은 왼쪽정렬)**
    ```
    | 기본 정렬 | 왼쪽 정렬 | 가운데 정렬 | 오른쪽 정렬 |
    |-----|:----|:-----:|-----:|
    | 내용 1 | 내용 2 | 내용 3 | 내용 4 |
    | 내용 5 | 내용 6 | 내용 7 | 내용 8 |
    ```
    
    * 결과

    | 기본 정렬 | 왼쪽 정렬 | 가운데 정렬 | 오른쪽 정렬 |
    |-----|:----|:-----:|-----:|
    | 내용 1 | 내용 2 | 내용 3 | 내용 4 |
    | 내용 5 | 내용 6 | 내용 7 | 내용 8 |

----------
#### 12. 특수기호 (Backslash Escapes)
* **Backslash `\`** 를 이용해 특수 기호를 표시할 수 있음

    ```
    \\
    \`
    \*
    \_
    \{ \}
    \[ \]
    \( \)
    \#
    \+
    \-
    \.
    \!
    ```
    
    * 결과  <br>
    \\ <br>
    \` <br>
    \* <br>
    \_ <br>
    \{ \} <br>
    \[ \] <br>
    \( \) <br>
    \# <br>
    \+ <br>
    \- <br>
    \. <br>
    \! <br>
    
----------
Emoji 이모지 Using emoji ( GitHub Flavored Markdown ), 이미지
