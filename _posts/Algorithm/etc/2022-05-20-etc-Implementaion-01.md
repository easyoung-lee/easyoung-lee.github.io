---
layout: single
title:  "[Algorithm] Implementation - '상하좌우 문제'" 
categories: Algorithm
comments: true
author_profile: true
sidebar:
  nav: "docs"
tags: [Algorithm, Algorithm etc, Python]
toc: true
toc_sticky: true
toc_label: "About This Page"
toc_icon: "sticky-note"

---

📣 학습한 내용을 정리한 글입니다. <br>
<br>
**구현 알고리즘** 문제입니다. 문제에 대한 내용과 풀이 그리고 결과를 간단하게 작성하였으니 참고바랍니다.  
풀이 언어 : Python
{: .notice--warning}

# 문제 설명

---

<br>
<b><u><span style="font-size:20px">내용</span></u></b>

여행가 A는 NxN 크기의 정사각형 공간 위에 서 있습니다. 이 공간의 1x1 크기의 정사각형으로 나누어져 있습니다.  
가장 왼쪽 위 좌표는 (1, 1)이며, 가장 오른쪽 아래 좌표는 (N, N)에 해당합니다.  
여행가 A는 상, 하, 좌, 우 방향으로 이동할 수 있으며, 시작 좌표는 항상(1, 1)입니다.
- L : 왼쪽으로 한 칸 이동
- R : 오른쪽으로 한 칸 이동
- U : 위로 한 칸 이동
- D : 아래로 한 칸 이동<br>


이때 여행가 A가 NxN 크기의 정사각형 공간을 벗어나는 움직임은 무시됩니다. 주어진 입력 계획에 의한 최종 여행자의 위치를 출력하는 프로그램을 작성하시오.

<br>
<b><u><span style="font-size:20px">입력</span></u></b>

첫째 줄에 공간의 크기를 나타내는 N이 주어진다.(1 <= N <= 100)  
둘째 줄에 여행가 A가 이동할 계획서 내용이 주어진다.(1 <= 이동 횟수 <= 100)  
ex) 5 / R R R U D D


<br>
<b><u><span style="font-size:20px">출력</span></u></b>

여행가 A가 최종적으로 도착할 지점의 좌표(x, y)를 공백을 기분으로 구분하여 출력한다.

<br>
<br>

# 문제 풀이

---

**Implementation Algorithm 참고내용**
- 구현 유형의 문제는 일반적으로 풀이를 떠올리는 것은 쉽지만 소스코드로 옮기기 어려운 문제들을 말한다.<br>
- 예를 들어 코드가 길어지는 문제, 실수 연산을 다루고 특정 소수점 자리까지 출력해야하는 문제,  
적절한 라이브러리를 찾아서 사용해야하는 문제 등<br>

위 참고사항을 준수하며, 풀어보자.<br>
방향 벡터를 이용하여 주어진 계획서에 맞게 이동하는 배열을 만들어 A의 위치를 나타낼 수 있게 활용해준다.
<br>
<br>

# 작성 코드

## Python

<script src="https://gist.github.com/easyoung-lee/8991486f210d2a8a78927f9b9b708744.js"></script>

<br>
<br>

---
[참고 : '동빈나'님의 (이코테 2021 강의 몰아보기) 2. 그리디 & 구현 영상](https://www.youtube.com/watch?v=2zjoKjt97vQ&list=PLRx0vPvlEmdAghTr5mXQxGpHjWqSz0dgC&index=2)

---
