---
layout: default
title: 표준 출력 객체 비교
nav_order: 1
parent: C++
---

# 표준 출력 객체 비교

### std::cout
* 일반 출력 스트림
* 버퍼링 스트림
  * 일정 크기의 버퍼가 채워지거나 명시적으로 출력을 강제할 때까지 대기
  * line buffering 사용
    * 개행 문자가 나타날 때까지 버퍼에 저장

### std::cerr
* 오류 메시지 출력 스트림
* unbuffered 스트림
  * 출력 즉시 화면에 표시

### std::clog
* 로깅 메시지 출력 스트림
* 버퍼링 스트림
  * full buffering 사용
    * 버퍼가 가득 차거나, 명시적으로 출력을 강제할 때까지 버퍼에 데이터를 저장
    * 조건이 충족되면 버퍼의 내용을 출력

### 테스트
1번 테스트 (10000번)  
![4_1_img](/resources/images/cpp/4_1.png)

2번 테스트 (10000번)  
![4_2_img](/resources/images/cpp/4_2.png)

3번 테스트 (10000번)  
![5_1_img](/resources/images/cpp/5_1.png)

4번 테스트 (10000번)  
![5_2_img](/resources/images/cpp/5_2.png)

5번 테스트 (100000번)  
![10_5_3_img](/resources/images/cpp/10_5_3.png)
