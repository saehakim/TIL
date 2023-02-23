## margin vs padding
<br>
<br>

### **margin**

- `margin`은 정해진 요소 주위의 바깥 여백 영역을 설정한다.
- 모든 여백 속성은 다음 값을 가질 수 있다.
    - auto - 브라우저가 여백을 계산
    - length - px, pt, cm 등의 여백을 지정.
    - % - 포함하는 요소 너비의 여백을 %로 지정.
    - inherit - 여백이 상위 요소에서 상속되어야 함을 지정.
- `margin-` 뒤에 `top`, `right`, `bottom`, `left`를 작성하여 각 측면에 대한 여백을 개별로 지정 가능하다.
    
    ```css
    p {
      margin-top: 100px;
      margin-bottom: 100px;
      margin-right: 150px;
      margin-left: 80px;
    }
    ```
    
- 코드의 간소화를 위해 각 margin속성에 네 방향의 여백 값을 한번에 지정할 수 있다.
    
    ```css
    p {
      margin: 100px 150px 100px 80px;
    }
    ```
    
     위-오른쪽-아래-왼쪽 순으로 여백 값을 지정한다. 시계방향을 떠올리면 된다.