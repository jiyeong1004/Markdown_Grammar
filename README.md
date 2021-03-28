# Title

## Hi

### Hello

#### Markdown

##### Student

###### 2021.03.28

---

### 강조문

It is *italic*

It is **bold**

It is ***italic and bold***

It is ~~cancelled~~

---

### Blockquotes

>인용문
> >인용문 안의 인용문
> >>인용문 안의 인용문 안의 인용문

---

### List

* source (출처)
  * YouTube [Code with Joyce]
  * Title : Markdown 문법 10분 뽀개기

* 순서가 있는 것
 1. tab 키 or Spacebar 두 번 누르면 됨
 2. 숫자 순서대로 "1. 2. 3." 되는것은 앞에 숫자가 관련이 없다.
 3. 예를 들어 "1. 1. 1." 을 해줘도
 125. "1. 2. 3." 으로 나온다.

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

### Link

[naver](https://www.naver.com)

[링크 이름](링크 주소)


#### <참조를 이용한 링크>

[daum][daum-link]

[링크 이름][참조 이름]

[daum-link]: https://www.daum.net/

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
