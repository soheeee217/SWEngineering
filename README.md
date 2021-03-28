# GFM(GitHub Flavored Markdown) Guide
GFM 확장 가이드 마크다운

# CHAPTER 1. 구문강조
1. \`\`\`를 코드에 둘러싸면 코드가 강조된다.
2. 예시
    1. 입력
        - ```
            ```javascript
            fucntion fancyAlert(arg) {  
                if(arg) {  
                    $.facebox({div:`#foo`})  
                }  
            }  
          ```
                
    3. 출력
        - ```javascript
            function facyAlert(arg) {
                if(arg) {
                    $.facebox({div:`#foo`})
                }
            }
            ```

# CHAPTER 2. 작업목록
1. 목록에 \[\]표시 후에 x를 넣으면 
2. 예시
    1. 입력
        - ```- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
                - [x] list syntax required (any unordered or ordered list supported)
                - [x] this is a complete item
                - [ ] this is an incomplete item
          ```
    2. 출력
        - [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
        - [x] list syntax required (any unordered or ordered list supported)
        - [x] this is a complete item
        - [ ] this is an incomplete item

# CHAPTER 3. 테이블
1. 가로열들끼리는 \|로, 세로열들끼리는 \-로 분할하여 테이블을 만들 수 있다.
2. 예시
    1. 입력
        - ``` 
            First Header | Second Header
            ------------ | -------------
            Content from cell 1 | Content from cell 2
            Content in the first column | Content in the second column
          ```
    2. 출력
        - First Header | Second Header
            ------------ | -------------
            Content from cell 1 | Content from cell 2
            Content in the first column | Content in the second column
            
# CHAPTER 4. 사용자 이름 언급
1. \@뒤에 사용자의 이름을 적으면 해당 사용자를 언급할 수 있다.
2. 예시
    1. 입력
        -`@mentions`

# CHAPTER 5. URL 연결
1. URL을 적으면 자동으로 연결된다.
2. 예시
    1. 입력
        - `http://www.github.com/`
    2. 출력
        - http://www.github.com/

# CHAPTER 6. 취소선
1. 취소선을 표시하고자 하는 단어나 구 앞뒤에 \~\~를 넣는다.
2. 예시
    1. 입력
        - `~~word~~`
    2. 출력
        - ~~word~~
