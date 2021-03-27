# Markdown Guide  
소프트웨어공학 Markdown README.md 작성

# CHAPTER 1. 머리글  
1. \# 뒤에 공백 후 문장을 작성한다.  
2. \#의 개수가 적을수록 글씨의 크기가 크다.(단 1~6개까지만 지원함)  
3. 예시  
    - `# Heading level 1`  
    - `## Heading level 2`  
    - `### Heading level 3`  
    - `##### Heading level 4`  
    - `##### Heading level 5`  
    - `###### Heading level 6`  

    # Heading level 1
    ## Heading level 2
    ### Heading level 3
    #### Heading level 4
    ##### Heading level 5
    ###### Heading level 6

4. Heading level 1과 2는 다른 표현방식이 존재한다.
    - `Heading level 1`  
    `==================`
    - `# Heading level 1` 과 같다.  

    Heading level 1
    ===============

    - `Heading level 2`  
    `------------------`
    - `## Heading level 2` 과 같다.  

    Heading level 2
    ---------------
5. \# 뒤에 공백이 반드시 들어가야한다.  
    - `#Heading` (X)
    - `# Heading` (O)

# CHAPTER 2. 단락  
1. 단락을 만들기 위해서는 빈 줄을 사용하여 하나 이상의 텍스트 줄을 분리한다.
2. 예시
    - I really like using Markdown.

      I think I'll use it to format all of my documents from now on.
3. 단, 단락을 만들 때 목록을 만든 것이 아니면 들여쓰기를 하지 말 것.

# CHAPTER 3. 줄 바꿈  
1. 줄을 바꾸기 위해서는 문장 끝에 공백을 두 개 이상 입력한다.
2. 공백을 두 개 이상 입력하지 않으면 그대로 문장이 이어서 출력된다.
3. 예시
    - This is the first line.__  
      And this is the second line.
    - This is the first line.
      And this is also the first line.

# CHAPTER 4. 굵게 강조  
1. 굵게 강조하고자 하는 단어나 구 전후에 공백 없이 두 개의 **\*** 혹은 __\___ 을 추가한다.
2. 예시
    - I just love **bold text**.  
      I just love \*\*bold text\*\*.  

    - I just love __bold text__.  
      I just love \_\_bold text\_\_.
3. 단, 굵게 강조할 양 옆이 띄어쓰기가 없다면 \*만 사용할 수 있다.
    - Love\*\*is\*\*bold. (O)
    - Love\_\_is\_\_bold. (X)

# CHAPTER 5. 기울이기 강조  
1. 기울여서 강조하고자 하는 단어나 구 전후에 공백 없이 한 개의 *\** 혹은 _\__ 을 추가한다.
2. 예시
    - Italicized text is the *cat's meow*.  
      Italicized text is the \*cat's meow\*.

    - Italicized text is the _cat's meow_.  
      Italicized text is the \_cat's meow\_.
3. 단, 기울여 강조할 양 옆이 띄어쓰기가 없다면 \*만 사용할 수 있다.
    - A\*cat\*meow. (O)
    - A\_cat\_meow. (X)

# CHAPTER 6. 굵게 기울이기 강조  
1. 굵게 동시에 기울여서 강조하고자 하는 단어나 구 전후에 공백 없이 세 개의 **\*** 혹은 __\___ 을 추가한다.
2. \*와 \_ 을 섞어서 사용이 가능하다.
3. 예시
    - This text is ***really important***.  
      This text is \*\*\*really important\*\*\*.

    - This text is ___really important___.  
      This text is \_\_\_really important\_\_\_.
    
    - This text is __*really important*__.  
      This text is \_\_\*really important\*\_\_.
    
    - This text is **_really important_**.  
      This text is \*\*\_really important\_\*\*.
4. 단, 굵게 동시에 기울여 강조할 양 옆이 띄어쓰기가 없다면 \*만 사용할 수 있다.
    - This is really\*\*\*very\*\*\*important text. (O)
    - This is really\_\_\_very\_\_\_important text. (X)
