# Markdown-Cheat-sheet-in-Korean

This is intended as a quick reference and showcase. For more complete info, see [John Gruber's original spec](http://daringfireball.net/projects/markdown/) and the [Github-flavored Markdown info page](http://github.github.com/github-flavored-markdown/).

Note that there is also a [Cheatsheet specific to Markdown Here](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet) if that's what you're looking for. You can also check out [more Markdown tools](https://github.com/adam-p/markdown-here/wiki/Other-Markdown-Tools).

**목차**

[헤더](#헤더)

[강조](#강조)

[열거](#열거)

[링크](#링크)

[이미지](#이미지)

[코드](#코드)

[표](#표)

[블록강조](#블록강조)

[HTML](#HTML)

[구분선](#구분선)

[선끊기](#선끊기)

[유튜브](#유튜브)

헤더
-----
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

H1, H2에 밑줄을 추가한 버전도 쓸 수도 있습니다.

Alt-H1
=====
Alt-H2
-----
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

H1, H2에 밑줄을 추가한 버전도 쓸 수도 있습니다.

Alt-H1
=====
Alt-H2
-----

강조
----- 
```
이탤릭체는 *별표* 혹은 _언더대쉬_ 를 원하는 글 양 옆에 두어 쓸 수 있습니다.

굵은체는 **별표 두 개** 혹은 __언더대쉬 두 개__ 를 원하는 글 양 옆에 두어 쓸 수 있습니다.

강조효과를 중첩할 수 도 있습니다. **별표 두 개와 _언더대쉬_**.

가운뎃줄은 ~~물결표 두개~~ 를 원하는 글 양 옆에 두어 쓸 수 있습니다.
```
이탤릭체는 *별표* 혹은 _언더대쉬_ 를 원하는 글 양 옆에 두어 쓸 수 있습니다.

굵은체는 **별표 두 개** 혹은 __언더대쉬 두 개__ 를 원하는 글 양 옆에 두어 쓸 수 있습니다.

강조효과를 중첩할 수 도 있습니다. **별표 두 개와 _언더대쉬_**.

가운뎃줄은 ~~물결표 두개~~ 를 원하는 글 양 옆에 두어 쓸 수 있습니다.

열거
----- 
```
1. 첫번째 번호 항목
2. 그 다음 번호 항목
⋅⋅⋅* 하위 단계의 번호 없는 항목
1. 번호는 순차적이지 않아도 동작 합니다.
⋅⋅⋅1. 하위 단계의 번호 항목
4. 마지막 번호 항목
(위의 항목에 한 줄 간격을 주지 않으면 이어 써집니다.)
⋅⋅⋅이렇게 긴 문장도 항목 안에 넣을 수 있습니다. 좌측에 들여쓰기가 생기고 이전 항목 간에 여백이 생깁니다.
⋅⋅⋅그러나 엔터를 해도 줄이 하나로 합쳐집니다.

⋅⋅⋅이를 막기 위해 줄이 끝나는 곳에 스페이스를 두개 넣어서 이를 막을 수 있습니다.⋅⋅
⋅⋅⋅줄을 나누어도 문단이 나누어지지 않았기에 이전 항목 간에 여백이 생기지 않습니다.

* 번호 없는 항목은 별표를 찍어 쓸 수 있습니다.
- 마이너스 표시도 됩니다.
+ 플러스 표시도 되고요.
```
1. 첫번째 번호 항목
2. 그 다음 번호 항목
   * 하위 단계의 번호 없는 항목
1. 번호는 순차적이지 않아도 동작 합니다.
   1. 하위 단계의 번호 항목
4. 마지막 번호 항목
(위의 항목에 한 줄 간격을 주지 않으면 이어 써집니다.)

   이렇게 긴 문장도 항목 안에 넣을 수 있습니다. 좌측에 들여쓰기가 생기고 이전 항목 간에 여백이 생깁니다.
   그러나 엔터를 해도 줄이 하나로 합쳐집니다.

   이를 막기 위해 줄이 끝나는 곳에 스페이스를 두개 넣어서 이를 막을 수 있습니다.  
   줄을 나누어도 문단이 나누어지지 않았기에 이전 항목 간에 여백이 생기지 않습니다.

* 번호 없는 항목은 별표를 찍어 쓸 수 있습니다.
- 마이너스 표시도 됩니다.
+ 플러스 표시도 되고요.

링크
----- 
```
[인라인 링크](https://www.google.com)

[제목을 가진 인라인 링크](https://www.google.com "Google's Homepage")

[레포지토리에 있는 파일도 링크 할 수 있습니다](../blob/master/LICENSE)

[참조 링크][네이버]

아니면 참조 링크 그 자체로 링크 할 수 있습니다. [네이버].

Some text to show that the reference links can follow later.

[네이버]: http://www.naver.com
```
[인라인 링크](https://www.google.com)

[호버 텍스트를 가진 인라인 링크](https://www.google.com "Google's Homepage")

[레포지토리에 있는 파일도 링크 할 수 있습니다](../blob/master/LICENSE)

[참조 링크][네이버]

아니면 참조 링크 그 자체로 링크 할 수 있습니다. [네이버].

Some text to show that the reference links can follow later.

[네이버]: http://www.naver.com

이미지
----- 
```
인라인 방식  
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "호버 텍스트 1")

참조 방식  
![alt text][로고1]

[로고1]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "호보 텍스트 2"
```

코드
-----
`(삐침표)를 3개 연달아 써서 원하는 코드를 표시할 수 있습니다.
```
'''javascript
var s = "자스";
alert(s);
'''

'''python
s = "파이썬"
print(s)
'''

'''
언어를 사용하지 명시하지 않고 표시합니다.
html을 표시할 때 사용됩니다.
**tag**
'''
```


표
----- 
블록강조
----- 
HTML
----- 
구분선
----- 
선끊기
----- 
유튜브
-----
