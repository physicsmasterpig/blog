---
layout: post
title: "Special Relativity 1."
subtitle: "Special Relativity"
category: physics
tags: Classical-Mechanics
---

#특수상대론 #상대론 #상대성원리 #광속 #불변 #로렌츠 #변환 #갈릴레이 #관성좌표계 #인자 #로렌츠인자 #민코프스키 #우주시간 #세계선 #빛 #시간지연 #길이수축 #쌍둥이역설 #동시성 #상대성 #상대론적속력 #기하학 #불변갼격 #회전분석 #선속도 #고유시간 #4백터


상대성이론에는 일반상대성이론과 특수상대성이론이 있다. 아인슈타인이 발견한 이 이론의 역사에 관해서는 많은 자세한 글들이 있으니 참고하길 바란다. 이 글에서는 특수상대성이론의 개념을 알아보고 수학적으로 분석해볼 것이다.


특수상대성이론에는 2개의 가설이 있다.

상대성원리와 광속불변의 원리이다.

상대성원리: 모든 관성좌표계에서 물리법칙은 동등하다.

광속불변의 원리: 광속은 모든 관측자에 대해 같은 값을 가진다,


특수 상대론에서는 두 관성좌표계 사이의 관측량의 관계를 다룬다. 관측량은 주로 위치와 시간이다.

상대적 운동이 있는 두 관성좌표계 사이에서의 변환은 고전적으로는 갈릴레이 변환으로 해석되었다. 이에 대한 내용은 고전역학(Classical mechanics) - 1(뉴턴역학)에서 다루었으니 참고하길 바란다.

상대성이론에서는 갈릴레이 변환이 성립하지 않는다. 그 이유는 광속불변의 원리이다.

광속불변의 원리는 마이켈슨-몰리 실험에서 입증되었다. 본래 에테르의 존재성을 확인하기 위해 계획되었던 이 실험에서 광속이 언제나 일정함이 검증되었다. 계를 움직이고 회전시키고 여러 조작을 반복해도 같은 결과를 얻은 이 실험에 대해서는 유명하기 때문에 찾아보기를 추천한다.

![Full-width image](_posts/Physics/Classical-Mechanis/1.png)



$$
\begin{aligned} %!!15
  \phi(x,y) &= \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right) \\[2em]
            &= \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j)            \\[2em]
            &= (x_1, \ldots, x_n)
               \left(\begin{array}{ccc}
                 \phi(e_1, e_1)  & \cdots & \phi(e_1, e_n) \\
                 \vdots          & \ddots & \vdots         \\
                 \phi(e_n, e_1)  & \cdots & \phi(e_n, e_n)
               \end{array}\right)
               \left(\begin{array}{c}
                 y_1    \\
                 \vdots \\
                 y_n
               \end{array}\right)
\end{aligned}
$$

An optional caption for a math block
{:.figcaption}