# MARKDOWN_20241202
MARKDOWN_20241202

### 1. 문단 구분을 위한 개행
겨울 바다를 걸어 보아요.  
(개행 : SPACE 2개)  
첫눈이 왔어요.

### 2. 제목(Header)
>제목은 # 기호를 사용하여 작성합니다. #의 개수로 제목의 수준(1~6)을 나타냅니다.

# H1 제목
## H2 제목
### H3 제목
#### H4 제목
##### H5 제목
###### H6 제목

### 3. 인용상자
>여기에 인용할 내용을 넣으면 됩니다.  
>빈 줄이 없으면 자동으로 인용 상자에 포함됩니다.  
식사 맛나게 하셨나요?

인용이 끝났습니다.

### 4. 코드 블럭
**인라인 코드** `System.out.println("Hello, world")`  
**코드 블럭**
```
public class Hello {
       public static void main(String[] args){
       //console : "Hello, world 메시지 출력"
       System.out.println("Hello, world");
       }
}
```

### 5. 목록
---
1. 아이템1  
   1.1 아이템1.1  
   1.2 아이템1.2  
2. 아이템2  
   2.1 아이템2.1  
   2.2 아이템2.2  
3. 아이템3
4. 아이템4
5. 아이템5
***
**순서 없는 리스트**  
- 아이템1  
+ 아이템2  
   - 1단계 하위 아이템
     * 2단계 하위 아이템
       - 3단계 하위 아이템

### 6. 링크(Link)
`[링크 텍스트](URL) 형태로 작성합니다.`    
[PCWK Daum](https://cafe.daum.net/pcwk)
**같은 페이지네 하이퍼 링크**  
[여기](###4-코드블럭)  
