# Welcome to 'Money Flow'

### ~ 2021.12.11 <br>

- App/ 에서 동작할 Expenses/ 와 NewExpense / 을 구분하여 만들었으며 <br>
  Expenses / 에서는 Data/State 를 저장, NewExpense / 는 Data/State 를 <br>
  생성 할 수 있도록 개발 진행 <br>
- 각 컴포넌트별 State 를 부모에게 끌어올리며 상속시키는 부분이 어렵게 다가왔다. <br>
- 사용할 State 관리에 대해 좀 더 깊게 이해할 필요가 있다. <br>

---

### ~ 2021.12.22 <br>

- Add Expense 버튼클릭해도 해당 내용이 추가가 안되서 오랜시간 해맸다..
- Date 변수이름을 Data 로 잘못 적어서 생긴 오류임을 찾아 수정완료
- 작성목록을 하드코딩이 아닌 useState를 사용하여 '...' 를 통해 복제한 내용을 띄울 수 있게 완료
  <img src="https://user-images.githubusercontent.com/77665102/146968837-2d11094b-f55f-440e-b059-b8614e993ba0.png" width="500" height="500" />

---

### ~ 2021.12.27 <br>

- Add New Expense 버튼을 조건부로 보이고 안보이게, 보인다면 새로운 값을 입력받을 수 있도록 하였다.
- !로 해당 state의 값을 true, false / && 을 사용하였다.
- Chart 를 동적으로 움직이도록 완성
- React의 Props 값을 주고 받는 것에 대해 이해가 되가는 중이다.
- amount 에 대한 값을 Chart 의 각 월별 값으로 props 로 받아왔다. <br>
 <img src="https://user-images.githubusercontent.com/77665102/147416840-6184c718-218a-40f2-a82a-42d12417e33e.png" width="500" height="500" />
