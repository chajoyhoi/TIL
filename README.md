# 240111 수업정리
### Markdown <-> Markup [HTML(M : Markup)]
일반 텍스트로 문서를 작성하는 간단한 방법, 
주로 개발자들이 텍스트와 코드를 작성해 문서화하기 위해 사용한다.

-특징 
: 작성된 Markdown 문서는 다른 프로그램에 의해 변환되어 출력됨

### 마크다운 미리보기 켜는법 
1) 마크다운 파일 마우스 우측 클릭 
2) Open Preview 클릭 

### Heading
-? 
```
# 제목입니다.
## 제목2
### 제목3
#### 제목4
```

### 리스트 
-목록을 표시하기 위해 사용, 순서가 있는 리스트와 순서가 없는 리스트 제공
```
1. 순서가 
    1. 있는
1. 목록 

- 순서가 
    - 없는 
- 목록
```
### Code block & Inline code block 
-일반 텍스트와 달리 해당 프로그래밍 언어에 맞춰서 텍스트 스타일을 변환 
*개발에서 마크다운을 사용하는 가장 큰 이유
```python
print('Hello')
```
파이썬은 `print` 함수를 사용해 텍스트를 출력한다. 

```js
console.log('Hello World!)
```

javascript는 `console.log` 를 이용해서 출력한다.

### 링크 & 이미지 
-특정 주소를 사용해 다른 페이지로 이동하는 링크 혹은 이미지를 출력 
*이미지의 너비와 높이는 마크다운으로 조절할 수 없음(HTML필요)

[구글로 가기](https://www.google.com)

![이미지](https://picsum.photos/200/300)

![이미지](https://i.namu.wiki/i/plYksH3UeGGZLVgjTfbJ8rf1vN2HMIl9ztcpxtfpeQwCYR1CBh3SzbQ0RsgbZ65xiYR-fk7A3Dxy7cExs4rABQ.webp)

### 텍스트 관련 문법
-굵게, 기울임, 취소선

**굵게**

*기울여서*

~~취소선~~

-수평선
: 단락을 구분할 때 사용하는 수평선 
: 하이픈(-)을 3개 이상 적으면 작동 
------

인용한 내용
> 랄라라

#마크다운 작성을 도와주는 마크다운 에디터 
-Typora(but 유료.. ㅠ)
-MarkText (무료)  
-Markdown All in One (VSCode 확장 프로그램)
