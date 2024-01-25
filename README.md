### 12. 수학수식 : LaTex 구문

### 10. 표
|No|함수|의미|
|:------------------:|------------------:|------------------|
|1|lower()|문자열을 소문자로 변환|
|2|upper()|문자열을 대문자로 변환|
|3|replace()|문자열 바꾸기|
|4|find()|찾는 문자열의 인덱스(없으면 -1 반환)|
|5|strip()|앞뒤 공백 제거|

### 9. 글자 강조
일반 **굵은글씨**  
이텔릭체 *이텔릭*  

### 8. 같은페이지 하이퍼 링크
[여기](#4-코드블럭)

### 7. 하이퍼 링크
```
[링크텍스트](링크URL "설명") 
```
[Daum cafe](https://cafe.daum.net/pcwk "수업자료 cafe")

### 6.가로선
화면 전체를 가로지르는 가로선: -,*을 3개 이상
---
***
----

### 5. 목록
---
1. 아이템1
2. 아이템2  
   9. 1단계 하위 아이템  
     10. 2단계 하위 아이템
9. 아이템3
---
- 아이템1
+ 아이템2
  - 1단계 하위 아이템
    * 2단계 하위 아이템
* 아이템3
---



#### 무순서 목록
* 목록이름1
- 목록이름2
+ 목록이름3

#### 순서있는 목록
1. 목록1
1. 목록2
1. 목록3




### 4. 코드블록
```JAVA
public class Hello{
  public static void main(String[] args){
     System.out.println("Hello, world");
  }

}

```

### 3. 인용상자
# 4-코드블럭
>여기에 인용할 내용을 넣으면 됩니다.  
>빈 줄이 없으면 자동으로 인용 상자에 포함 됩니다.
식사 맛나게 하셨나요?

인용이 끝났습니다.


### 2. 헤더
''' #을 1개부터 6개 까지 6단계로 사용 '''
# JAVA
## ORACLE
### HTML
#### CSS
##### JAVASCRIPT
###### SPRING




### 1. 문단 구분을 위한 개행
겨울 바다를 걸어 보아요.  
(개행: space 2개)  
겨울을 만끼 하세요

