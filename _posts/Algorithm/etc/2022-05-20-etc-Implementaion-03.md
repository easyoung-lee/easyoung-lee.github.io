---
layout: single
title:  "[Algorithm] Implementation - '문자열 재정렬 문제'" 
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

알파벳 대문자와 숫자(0~9)로만 구성된 문자열이 입력으로 주어진다.  
이때 모든 알파벳을 오름차순으로 정렬하여 이어서 풀력한 뒤에, 그 뒤에 모든 숫자를 더한 값을 이어서 출력한다.

<br>
<b><u><span style="font-size:20px">입력</span></u></b>

첫째 줄에 하나의 문자열 S가 주어진다.(1 <= S의 길이 <= 10,000)  
ex) K1KA5CB7


<br>
<b><u><span style="font-size:20px">출력</span></u></b>

첫째 줄에 문제에서 요구하는 정답을 출력한다.  
ex) ABCKK13

<br>
<br>

# 문제 풀이

---

**Implementation Algorithm 참고내용**
- 구현 유형의 문제는 일반적으로 풀이를 떠올리는 것은 쉽지만 소스코드로 옮기기 어려운 문제들을 말한다.<br>
- 예를 들어 코드가 길어지는 문제, 실수 연산을 다루고 특정 소수점 자리까지 출력해야하는 문제,  
적절한 라이브러리를 찾아서 사용해야하는 문제 등<br>

위 참고사항을 준수하며, 풀어보자.<br>
문자열이 입력되었을 때 문자 하나하나 확인하면서 숫자인 경우는 따로 합계를 구하고 문자인 경우는 별도의 리스트에 저장한다.  
결과적으로 리스트에 저장된 알파벳을 오름차순으로 정렬한뒤 합계를 구한 숫자를 뒤에 붙여 출력한다.
<br>
<br>

# 작성 코드

## Python

<script src="https://gist.github.com/easyoung-lee/440d3d7af0c1877777fce13481a2d9bb.js"></script>

<br>
<br>

---
[참고 : '동빈나'님의 (이코테 2021 강의 몰아보기) 2. 그리디 & 구현 영상](https://www.youtube.com/watch?v=2zjoKjt97vQ&list=PLRx0vPvlEmdAghTr5mXQxGpHjWqSz0dgC&index=2)

---
