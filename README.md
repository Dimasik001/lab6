<h1 align= "center"> МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<p align= "center">Лабораторная работа №6</p><br><br><br><br><br><br><br><br>
<p align= "right">Выполнил: Андреев Д.В.</p><br><br><br><br><br><br><br><br>
<p align="center">г. Южно-Сахалинск <br> 2023 год</p><br><br><br><br><br><br><br><br>
<h2 style="text-align: center">Введение</h2>
<p align="justify">JavaScript ("JS" для краткости) — это полноценный динамический язык программирования, который применяется к HTML документу, и может обеспечить динамическую интерактивность на веб-сайтах. Его разработал Brendan Eich, сооснователь проекта Mozilla, Mozilla Foundation и Mozilla Corporation. JavaScript сам по себе довольно компактный, но очень гибкий. Разработчиками написано большое количество инструментов поверх основного языка JavaScript, которые разблокируют огромное количество дополнительных функций с очень небольшим усилием. JavaScript невероятно универсален и дружелюбен к новичкам. Обладая большим опытом, вы сможете создавать игры, анимированную 2D и 3D графику, полномасштабные приложения с базами данных и многое другое!</p>
<h2 style="text-align: center">Цели и задачи</h2>
<ol align="justify"> <br>
<h2 align="center">Цели и задачи</h2>
Задачи:


```JavaScript
function func1() {
  alert("Кнопка была нажата!");
}

function func2() {
  var input = document.getElementById('myInput');
  input.value = "Новый текст!";
}

function func3() {
  var input = document.getElementById('myyInput').value;
  alert(input);
}

function func4() {
  alert(Math.pow(document.getElementById('myyInputt').value, 2))
}

function func5() {
  var temp = document.getElementById('input51').value; 
  document.getElementById('input51').value = document.getElementById('input52').value; 
  document.getElementById('input52').value = temp;
}

function func6() {
  this.innerHTML = 'Текст кнопки поменялся';
}


function func7() {
  document.getElementById('Inputs').style.color = 'green'
}

function func8() {
  document.getElementById('Innput').disabled = true;
    }
    function func88() {
      document.getElementById('Innput').disabled = false;
        }


function func9() {
   
}


function func10() {
    
}


function func11() {
  
    }

    function func12() {
      document.getElementById('myImage').src = 'suz.jpg'
    }
    
    function func13() {
      
       }


function func14() {

}

function func15() {

}  
var clickCount = 0;
function func16() {

  clickCount++;
  document.getElementById("clickCount").innerHTML = "Количество нажатий: " + clickCount;
  }
  
    
function func17() {

}

function func18() {
  
    document.getElementById('hide').style.display = 'none';

}
function func19() {
const massive = [10, 5, 20, 8, 15, 30, 25, 12];

let minel = massive[0];
let maxel = massive[0];
let indexmin = 0;
let indexmax = 0;

for (let i = 1; i < massive.length; i++) {
  if (massive[i] < minel) {
    minel = massive[i];
    indexmin = i;
  }
  if (massive[i] > maxel) {
    maxel = massive[i];
    indexmax = i;
  }
}

const sumindex = indexmin + indexmax;

alert('Сумма номеров минимального и максимального элементов: ' + sumindex);
}

function func20() {
  
  function calculate(num1, operator, num2) {
    switch (operator) {
      case '+':
        return num1 + num2;
      case '-':
        return num1 - num2;
      case '*':
        return num1 * num2;
      case '/':
        if (num2 !== 0) {
          return num1 / num2;
        } else {
          return 'Ошибка: Деление на ноль невозможно!';
        }
      default:
        return 'Ошибка: Неверный оператор!';
    }
  }
  
  
  const number1 = parseFloat(prompt('Введите первое число:'));
  const operator = prompt('Введите оператор (+, -, *, /):');
  const number2 = parseFloat(prompt('Введите второе число:'));
  
  const result = calculate(number1, operator, number2);
  
  alert(`Результат: ${result}`);
}

function func21() {


}

function func22() {

}
```
