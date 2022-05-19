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
- D : 아래로 한 칸 이동  
이때 여행가 A가 NxN 크기의 정사각형 공간을 벗어나는 움직임은 무시됩니다.  
이때 주어진 입력 계획에 의한 최종 여행자의 위치를 출력하는 프로그램을 작성하시오.

<br>
<b><u><span style="font-size:20px">입력</span></u></b>

여러개의 숫자로 구성된 하나의 문자열 S가 입력된다.(1 <= S의 길이 <= 20)

<br>
<b><u><span style="font-size:20px">출력</span></u></b>

주어진 연산자를 이용해 만들어질 수 있는 가장 큰 수를 출력한다.

<br>
<br>

# 문제 풀이

---

**Greedy Algorithm 참고내용**
- 일반적인 상황에서 Greedy Algorithm은 최적의 해를 보장할 수 없을 때가 많다.<br>
- 하지만 Coding Test에선 일반적으로 Greedy Algorithm문제에서 이를 사용해 얻은 해가 최적의 해가 되는 경우가 많다.<br>
위 참고사항을 준수하며, 풀어보자.<br>

<br>
<br>

# 작성 코드

## Python

<script src="https://gist.github.com/easyoung-lee/e97426746a7cd2482944b1203f77af42.js"></script>

<br>
<br>

---
[참고 : '동빈나'님의 (이코테 2021 강의 몰아보기) 2. 그리디 & 구현 영상](https://www.youtube.com/watch?v=2zjoKjt97vQ&list=PLRx0vPvlEmdAghTr5mXQxGpHjWqSz0dgC&index=2)

---
