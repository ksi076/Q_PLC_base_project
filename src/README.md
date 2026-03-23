## 🧠 핵심알고리즘

---

### 1️⃣ 원점확립&후진

<img src="../img/algorithm/원점.png"  style="width:600px; height:600px">

○ 시스템 시작 or 동작 종료 

-> 내부 릴레이 ON

-> 실린더 후진

-> 원점확립

-> 내부 릴레이 OFF

---

### 2️⃣ 선입

<img src="../img/algorithm/선입1.png"  style="width:600px; height:200px">
<img src="../img/algorithm/선입2.png"  style="width:600px; height:400px">

○ 소재인식

-> 층 수 증가

-> 설정된 층 입고

-> 동작종료 & 층수 = 3

-> 층 수 초기화

---

### 3️⃣ 선출

<p align="center">
  <img src="../img/algorithm/선출1.png" width="1200">
  <img src="../img/algorithm/선출2.png" width="1200">
  <img src="../img/algorithm/선출3.png" width="1200">
</p>

○ 버튼 누름

-> 층 수, 선출 수량 증가

-> 설정된 층 출고

-> 층수 = 3

-> 층 수 초기화

---

### 4️⃣ 상태점검

<p align="center">
  <img src="../img/algorithm/상태1.png" width="1200">
  <img src="../img/algorithm/상태2.png" width="1200">
  <img src="../img/algorithm/상태3.png" width="1200">
</p>

○ 버튼 누름

-> 적재 중 위치 학습

-> 동작 완료

-> 원하는 층 버튼 누름

-> 학습된 위치의 소재 출고

-> 소재를 공급

-> 출고된 위치에 다시 입고

---

## 🚨 안전설계

### 5️ 비상정지 회로

<p align="center">
  <img src="../img/algorithm/비상정지.png" width="1200">
</p>
---

### 6️⃣ 후진완료 릴레이

<p align="center">
  <img src="../img/algorithm/후진완료.png" width="1200">
</p>

### 7️⃣ InerLock 회로

<p align="center">
  <img src="../img/algorithm/InerLock.png" width="1200">
</p>
---

## 🧾 [전체코드보러가기](../doc/project_ladder.pdf)
---



