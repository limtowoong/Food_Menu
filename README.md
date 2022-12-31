# Food_Menu

<br>

```javascript
var menu = new Array();
```

<b>menu</b> 라는 배열을 생성해줍니다.

<br><br>

```javascript
do {
	input = prompt("먹고싶은 메뉴를 입력하시오.");
	menu.push(input);
} while (input != null);
```

prompt를 이용하여 input에 원하는 음식 값을 입력받고 menu 마지막 배열에 저장합니다.

배열에 입력을 반복하고, promt 창 '취소' 클릭 시 반복문 종료합니다.

<br><br>

```javascript
menu.pop();
```

취소 버튼 누를시 null값이 들어가며 while문이 종료됩니다.

<br><br>

```javascript
var menuNum = Math.floor(Math.random() * menu.length);
var result = menu[menuNum];
document.write(result);
```

입력한 음식 종류 중에서 랜덤하게 뽑아서 출력합니다.

<br><br>
