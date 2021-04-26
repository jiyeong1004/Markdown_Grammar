<YouTube 참고>

[Code with Joyce](https://www.youtube.com/channel/UCTpRsT-oLzS1rh8TeIw2I8w) - [Markdown 문법 10분 뽀개기](https://www.youtube.com/watch?v=eHUVvQ2AHh0)

---

# H1

## H2

### H3

#### H4

##### H5

###### H6

H

---

### 강조문

_italic_, *italic*

__bold__, **bold**

___italic and bold___, ***italic and bold***

**blod and _italic_**

It is ~~cancelled~~

---

### Blockquotes

>인용문
> >인용문 안의 인용문
> >>인용문 안의 인용문 안의 인용문

---

### List

* List
  * 리스트
  * 안녕

* 순서가 있는 것
 1. tab 키 or Spacebar 두 번 누르면 됨
 2. 숫자 순서대로 "1. 2. 3." 되는것은 앞에 숫자가 관련이 없다.
 3. 예를 들어 "1. 1. 1." 을 해줘도
 125. "1. 2. 3." 으로 나온다.

+ 열심히 공부하자!

  - **깃허브 사용법** 연습

     * 마크다운 사용법 연습

- 꾸준히 하기!!!

---

### CodeBlock

```사용할 언어
// 코드 작성
```


```java
// Java

public class Hello{
 public static void main(String[] args){
  System.out.println("Hello Java World!");  // Java 문법이라고 지정해서 색도 자동으로 입혀진다.
 }
}
```

```c
// C

#include<stdio.h>

void main(void){
  printf("Hello C Wolrd!");  // C 문법이라고 지정해서 색도 자동으로 입혀진다.
}
```

---

`code`

---

### Link

[naver](https://www.naver.com)

[링크 이름](링크 주소)


#### <참조를 이용한 링크>

[Support badge free icon][Support badge free icon-link]

[링크 이름][참조 이름]

[Support badge free icon-link]: https://simpleicons.org

[참조 이름]:링크 주소

※ 여기서 주의할 점은 **]:** 여기 사이를 절대 띄우면 안 된다.

---

### Images

![logo](http://octodex.github.com/images/octdrey-catburn.jpg)

![이미지 이름](이미지 주소)

#### <참조를 이용한 이미지>

![logo][2]

![이미지 이름][참조 이름]

[2]:http://octodex.github.com/images/octdrey-catburn.jpg

[참조 이름]:이미지 주소(이미지 링크)

※ 여기서 주의할 점은 **]:** 여기 사이를 절대 띄우면 안 된다.
