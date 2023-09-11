# 코코아 클론 코딩

> 학습 목표 : 노마드 코더 코코아 클론 코딩을 통해 css 기초를 중점적으로 공부한다.

<br>

# 3 LEANING CSS

### - 3.3 Blocks and Inlines

- block: `<div>`, `<h1>`, `<h2>`, ...

- inline: `<span>`, `<img>`, ...

<br>

### - 3.4 Margin part One

display 속성이 inline 인 요소는 높이와 너비를 가질 수 없다. (속성 주면 화면에서 안보임)

반면에 block은 높이와 너비를 가질 수 있다.

margin, border, padding은 기본적으로 box(display: block)이 가지는 속성.

브라우저는 자동으로 css를 적용하기도 한다. (예를들면, `<h1>`태그에 글자 크기, 굵기를 크게)

body에 margin 자동으로 들어가는 것도 브라우저에서 주는 것.

- margin : border 밖으로의 공간
- border : 경계
- padding : border 안으로의 공간

default 설정에서 body의 크기는 body 안에 있는 element들을 딱 맞게 들어갈 높이와 window 만큼의 너비를 가짐(기본 margin을 제외하고)

```css
/* one value */
margin: all;

/* two value */
margin: left righit;

/* four value */
margin: top righit bottum left;
```

<br>

---

### 1. Sign Up Screen part One

index.html을 만든다. 대부분의 웹 서버가 디폴트로 index.html을 찾아보도고 설정돼있다.

<br>

### 2. BEM : Block Element Modifier

class의 이름을 짓는 일종의 규칙이다.

- `--` 뒤에는 속성을 적는다.(색상, 크기 등...)
- `__` 뒤에는 해당 element의 역할을 적는다.

<br>

### 3. Font Awesome

- 아이콘을 사용하는 방법:
  직접 이미지를 만들고 추출, 혹은 svg 파일을 이용.(\*svg는 픽셀이 없는 이미지 파일 형식. 수학, 좌표으로만 구성된 형식)
  Heroicons또는 FontAwesome 검색해서 사용하면 된다.

<br>
