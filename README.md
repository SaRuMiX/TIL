# TIL
## dasdasdas
### front
#### CSS
##### 
<u>한글</u>

1. ~~EDEDEDEDED~~
2. *D* , _D_
3. **D** , __D__
4. ol /ol -> 1.
5. ul /ul -> - 

[강의](https://www.youtube.com/watch?v=WcED6Ia1IY4&list=PLuHgQVnccGMAnWgUYiAW2cTzSBywFO75B&index=6)

[이름] ( 링크 넣으면 이동 된다 ) 
- 순서
- GSM <em>아미르</em>
- 

- fii
ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ
오늘 배운 내용들 프론트엔드
h1 {
  font-size:~~px;
  text=align:center;

}

#은 id
.은 클래스
#active
.active
a {
  코드
}
위 코드는 CSS 선택자는 우선 순위 순으로 적어 놓은 것 


            a{
                border-width:5px;
                border-color:red;
                border-style: solid;
            }
이 코드는 보더로 폰트의 주변을 감싼다

 25/05/14


            @media(min-height:800px){
                div {
                    display:none;
                }

미디어 쿼리

측정 조건이 충족 되면 그 아래에 적힌 조건이 실행 된다.
저 예시는 사이트의 창의 세로의 길이가 800px 이하면 사라진다.

height나 width 






ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ
자바스크립트

var name = 'english is bad language';
alert("English is a West Germanic language that emerged in early medieval England and has since become a global lingua franca.[4][5][6] The namesake of the language is the Angles, one of the Germanic peoples" +name+ "that migrated to Britain after its Roman occupiers left. English is the most spoken language in the world, primarily due to the global influences of the former British Empire (succeeded by the Commonwealth of Nations) and the United States. It is the most widely learned second language in the world, with more second-language speakers than native speakers. However, English is only the third-most name name name eng spoken native language, after Mandarin Chinese and Spanish.[3]")
name 이라는 변수에 'english is bad language' 를 저장 하고 이 name 변수를 사용 할때는 +변수이름+ 로 사용 할 수 있다


if() {}
C언어랑 똑같다.

var는 변수를 선언할때 사용된다.

var (배열이름) = [변수 항목 , 변수 항목];

배열을 만들고 배열의 항목 갯수를 확인하고 싶으면
배열이름.length를 입력하면 배열의 항목 갯수를 알려준다.

배열에서 어떤 항목이 어디에 존재하는지 확인하고 싶으면
배열이름.indexOf(항목이름);을 검색하면 내가 항목이름에 적은 값이
배열에서 어디에 위치하는지 숫자로 알려준다.

이미 선언 되어 있는 배열에 값을 집어 넣을때에는
배열이름.push(항목이름); 으로 배열에 값을 넣을 수 있다.

반복문
    var i = 0;
    while(i < 3){
        document.write('<li>2</li>');
        document.write('<li>3</li>');
            i = i + 1;  
    }
        document.write('<li>4</li>');
변수 선언 후 while 반복문의 조건이 참 또는 거짓이 되어서 반복문이 작동 되도록 한다.

배열 + 반복문 가능

    var arr = ['first', 'second','third'];
    var i = 0;
    while(i < arr.length){
        document.write('<li>'+arr[i]+'</li>');

            i = i + 1;  
    }

    
