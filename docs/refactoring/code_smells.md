---
layout: default
title: Code Smells
nav_order: 1
parent: Guideline
has_children: true
---

# 변경이 필요한 코드

## 일반

##### 1. Mysterious Name
* 함수명, 변수명 확인
* get/set이 정확히 해당 동작만 하는지 확인

##### 2. Duplicated Code

##### 3. Long Function

##### 4. Long Parameter List

##### 5. Global Data

##### 6. Mutable Data
* 외부에서 예상치 못하게 데이터를 변경하는 것을 막아야 함

---

## 모듈 단위

##### 1. Divergent Change

##### 2. Shotgun Surgery
* 하나를 수정하면 연쇄적으로 수정이 필요하게 되는 경우

##### 3. Feature Envy

##### 4. Data Clumps

##### 5. Primitive Obsession

##### 6. Repeated Switches
* Switches 대신 다형성을 이용
