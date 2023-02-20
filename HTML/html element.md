## HTML element

---

### **`<meta>`**

- HTML 문서에 대한 메타데이터를 정의한다.
- 항상 <head> 요소 안에 들어가며 일반적으로 문자 집합, 페이지 설명, 키워드, 문서 작성자 및 뷰포트( 웹 콘텐츠를 볼 수 있는 창 영역) 설정을 지정하는 데 사용된다.
- viewport 설정
    
    ```html
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    ```
    
    - 모든 웹 페이지에 다음 <meta> 요소를 포함해야 한다.
    - `width=device-width` 부분은 장치의 화면 너비(장치에 따라 다름)를 따르도록 페이지의 너비를 설정한다.
    - `initial-scale=1.0` 부분은 브라우저에서 페이지를 처음 로드할 때 초기 확대/축소 수준을 설정한다.

<br>
<br>    

### **`<b>` vs `<strong>`** 

- `<strong>` 는 더 중요한 내용을 위해 사용, `<b>` 는 더 중요하다는 것을 나타내지 않고 텍스트에 주의를 끌기 위해 사용된다.
- 장식을 위해 텍스트를 굵게 표시하려면 CSS font-weight 속성을 사용해야 한다.

<br>
<br>

### **`<label>`**

- 사용자 인터페이스 항목의 설명을 나타낸다.
- `<label>`을 `<input>` 요소와 연관시키려면, `<input>`에  `id`속성을 넣어야 한다. 그리고 `<label` 에 `id`와 같은 값의 `for`속성을 넣어야 한다.
    
    ```html
    <div class="preference">
        <label for="cheese">Do you like cheese?</label>
        <input type="checkbox" name="cheese" id="cheese">
    </div>
    ```
    
- 또는 `<label>` 내부에 직접 `<input>`을 중첩할 수 있다. 이 경우 연관이 암시적이기 때문에 `for` 및 `id` 특성이 필요하지 않다.
    
    ```html
    <label>
      Do you like cheese?
      <input type="checkbox" name="cheese" />
    </label>
    ```

<br>
<br>

출처:  [w3schools][w3schoolslink]

[w3schoolslink]: https://www.w3schools.com/tags/tag_meta.asp "w3schools "