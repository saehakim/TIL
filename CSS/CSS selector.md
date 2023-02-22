## CSS selector

---

- CSS 선택자는 HTML 태그나 속성을 선택해서, 해당 영역에 스타일을 지정하기 위해 사용된다.

<br>
<br>

### **id selector**

- HTML 요소의 id 속성을 사용하여 특정 요소를 선택한다.
- 요소의 id는 페이지 내에서 고유하므로 id 선택자는 하나의 고유한 요소를 선택하는 데 사용된다.
- 특정 id를 가진 요소를 선택하려면 **해시(#)**뒤에 요소의 id를 쓰면 된다.
    
    ```css
    #first {
      text-align: center;
      color: red;
    }
    ```
    
<br>
<br>

### **class selector**

- 특정 클래스 속성을 가진 HTML 요소를 선택한다.
- 클래스의 요소를 선택하려면 **마침표(.)** 문자와 클래스 이름을 쓰면 된다.
    
    ```css
    .mycomment {
        color: blue;
        font-size: 35px;
    }
    ```
    
<br>
<br>


### **Universal Selector**

- 범용 선택자**(*)**는 페이지의 ****모든 HTML 요소를 선택한다.
    
    ```css
    * {
      text-align: center;
      color: blue;
    }
    ```
    
<br>
<br>


### **Grouping Selector**

- 동일한 스타일 정의가 있는 모든 html 요소를 선택할 때 사용되며 코드가 간소화 된다는 장점이 있다.
- 그룹화 할 경우,  각 선택자를 쉼표로 구분한다.

```css
h1, h2, p {
  text-align: center;
  color: red;
}
```

<br>
<br>
<br>
<br>
<br>


출처 : [w3schools][w3schoolslink]

[w3schoolslink]: https://www.w3schools.com/css/css_selectors.asp "w3schools CSS Selectors"