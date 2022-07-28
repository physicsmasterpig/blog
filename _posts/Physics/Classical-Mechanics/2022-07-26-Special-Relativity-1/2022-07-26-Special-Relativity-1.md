---
layout: post
title: "Special Relativity 1."
subtitle: "Special Relativity"
category: physics
tags: classical-mechanics
image: 
  path: /assets/img/physics/2022-07-26-Special-Relativity-1/2.png
---

#특수상대론 #상대론 #상대성원리 #광속 #불변 #로렌츠 #변환 #갈릴레이 #관성좌표계 #인자 #로렌츠인자 #민코프스키 #우주시간 #세계선 #빛 #시간지연 #길이수축 #쌍둥이역설 #동시성 #상대성 #상대론적속력 #기하학 #불변갼격 #회전분석 #선속도 #고유시간 #4백터

<!--more-->

상대성이론에는 일반상대성이론과 특수상대성이론이 있다. 아인슈타인이 발견한 이 이론의 역사에 관해서는 많은 자세한 글들이 있으니 참고하길 바란다. 이 글에서는 특수상대성이론의 개념을 알아보고 수학적으로 분석해볼 것이다.


특수상대성이론에는 2개의 가설이 있다.

상대성원리와 광속불변의 원리이다.

상대성원리: 모든 관성좌표계에서 물리법칙은 동등하다.

광속불변의 원리: 광속은 모든 관측자에 대해 같은 값을 가진다,


특수 상대론에서는 두 관성좌표계 사이의 관측량의 관계를 다룬다. 관측량은 주로 위치와 시간이다.

상대적 운동이 있는 두 관성좌표계 사이에서의 변환은 고전적으로는 갈릴레이 변환으로 해석되었다. 이에 대한 내용은 고전역학(Classical mechanics) - 1(뉴턴역학)에서 다루었으니 참고하길 바란다.

상대성이론에서는 갈릴레이 변환이 성립하지 않는다. 그 이유는 광속불변의 원리이다.

광속불변의 원리는 마이켈슨-몰리 실험에서 입증되었다. 본래 에테르의 존재성을 확인하기 위해 계획되었던 이 실험에서 광속이 언제나 일정함이 검증되었다. 계를 움직이고 회전시키고 여러 조작을 반복해도 같은 결과를 얻은 이 실험에 대해서는 유명하기 때문에 찾아보기를 추천한다.

![Full-width image](/assets/img/physics/2022-07-26-Special-Relativity-1/1.png){:.centered}
Figure 1. Michelson-Morley Interferometer.
{:.figcaption}

사진에서 거울 2개와 반거울을 이용하여 빛을 거리가 같은 다른 두 경로로 검출기에 도달하게 하는데, 계를 움직이거나 회전시키면서 측정해도 빛의 속도가 일정함을 확인했다.

그러면, 로렌츠 변환에 대해서 알아보자.

![Full-width image](/assets/img/physics/2022-07-26-Special-Relativity-1/2.png){:.centered}
Figure 2. Two different Inertial Coordinates with a constant relative speed.
{:.figcaption}

두 관성좌표계 $$S,~S'$$이 상대속력 $$v$$로 움직이고 있다. 이때 운동은 $$x$$-축에 대해서만 생각하자.

그러면 항상 다음과 같은 함수 $$f,~g$$가 존재한다.

$$\begin{aligned}&
x'=f\left(x,\ t\right),\ \ t'=g\left(x,\ t\right)
\end{aligned}$$

관성 좌표계이므로 변환 $$(x, t) \mapsto (x',t')$$은 선형적이다. 또한, 상대속도가 $$v$$임을 고려하면 $$x=vt$$일 때 $$x'=0$$가 되어야 한다. 그러므로 다음과 같이 표현된다. 

$$\begin{aligned}& x'=\gamma \left(x-vt\right) \end{aligned}$$

여기서 감마는 속력의 함수이다.

감마는 특이한 성질을 가진다. 로렌츠 변환은 상대속력에 의존하는 변환이기 때문에 다음을 만족한다.


$$\begin{aligned}&\gamma _v=\gamma _{-v}\end{aligned}$$

그러므로 좌표계의 관점을 바꾸면 아래의 식을 만족한다.

$$\begin{aligned}&x=\gamma \left(x-vt\right)\end{aligned}$$

2개의 식을 연립하면 될 것 같지만, 한가지가 더 필요하다. 바로 광속 불변의 원리이다. 두 좌표계에서 신뢰할 수 있는 물리량은 광속밖에 없기 때문에 빛의 이동을 사건으로 생각하여 $$v$$에 $$c$$를 대입하면 된다.
$$x=ct, ~x'=ct'$$를 대입하여 연립하면, $$\gamma =\sqrt{\frac{1}{1-c^2 /v^2}}$$이다. 

따라서 로렌츠 변환(rorentz transformations)는 다음과 같다.

$$\begin{aligned}&\begin{cases}x'=\gamma \left(x-\frac{v}{c}ct\right)\\y'=y\\z'=z\\t'=\gamma \left(ct-\frac{v}{c}x\right)\end{cases}\end{aligned}$$

이 로렌츠 변환을 이해하기 쉽도록 나타낸 것이 바로 민코프스키 다이어그램이다.

민코프스키 다이어그램의 형태는 아래와 같다. 공간축과 시간축으로 구성되있는 복소좌표계이다.

![Full-width image](/assets/img/physics/2022-07-26-Special-Relativity-1/3.png){:.centered}
Figure 3. Minkoffski Diagram. 
{:.figcaption}

세계선 위의 점은 사건을 나타낸다.

이 복소좌표계 상에서 모든 사건은 빛의 속도로 움직인다. 만약 공간에 대해서 멈춰있다면 시간축에 대해서 빛의 속도로 움직인다. 공간축에서의 속도가 빨라질수록 시간축에서의 속도가 느려진다.

이 세계선을 이용하면 다양한 역설을 해결할 수 있다. 이는 다음글인 역설편에서 더 자세히 다루겠다. 맛보기만 하면 아래 그림과 같이 움직이는 좌표계에서 본 세계는 좌표축이 빛의 세계선 쪽으로 회전한 형태로 된다. 그래서 기하적으로 두 좌표계 사이의 시간 간격과 공간 간격을 간편히 계산할 수 있다.

![Full-width image](/assets/img/physics/2022-07-26-Special-Relativity-1/4.png){:.centered}


Figure 4. Minkoffski Diagram. 
{:.figcaption}

여기서 끝난다면 좋겠지만, 더 심화적으로 우주 시간의 기하학을 알아보도록 하자. 뒤로 나올 내용은 꽤 높은 수준의 수학이 사용되므로 어렵다면 넘어가도 좋다.

먼저, 시공간 간격을 정의한다.


$$\begin{aligned}&\Delta s^2=c^2\Delta t^2-\Delta x^2-\Delta y^2-\Delta z^2\end{aligned}$$

시공간 간격이 의미를 가지는 이유는 좌표계에 무관하게 같은 값을 가지기 때문이다. 유도는 간단하게 할 수 있기 때문에 생략하도록 하겠다.

시공간의 간격제곱의 부호에 따라서 인과관계의 성립 여부가 갈리는데, 아래와 같다.

$$\begin{aligned}&\begin{cases}\Delta s^2>0\ :\ 시간꼴\ 간격\\\Delta s^2<0\ :\ 공간꼴\ 간격\\\Delta s^2=0\ :\ 빛꼴\ 간격\end{cases}\end{aligned}$$

시간꼴 간격에서는 두 사건이 시간적으로 가깝게 연결되있는 상태이다. 인과관계가 성립하고 빛꼴 간격과 더불어 실제로 일어날 수 있는 경우이다.

공간꼴 간격에서는 두 사건이 공간적으로 가깝게 연결되있는 상태이다. 인과관계가 성립하지 않는다.

빛꼴 간격에서는 두 사건을 빛으로 연결 가능하다. 다시 말하면 두 사건 사이의 정보가 빛의 속도로 전달된다.

![Full-width image](/assets/img/physics/2022-07-26-Special-Relativity-1/5.jpg){:.centered}
Figure 5. Light Cone. 
https://ko.wikipedia.org/wiki/%EC%84%B8%EA%B3%84%EC%84%A0
{:.figcaption}

위의 그림은 입체적으로 표현한 민코프스키 다이어그램이다. 위의 개념을 이해하기 좋을 것 같아서 가져왔다.

이제 정말 수학적으로 분석해보자.

우리는 회전 분석(Rotational analogy)를 해보자.

앞서서 로렌츠 변환이 선형변환이라는 말을 한 적이 있다. 이를 수학적으로 표현하면 다음과 같다.

$$\begin{aligned}&\vec{x'}=R\vec{x}\end{aligned}$$

물론 두 좌표계의 관측자가 정보를 공유한다는 보장이 없지만, 한가지 공유되어야 할 양이 있다. 원점으로부터의 거리이다. 이를 위해선 회전행렬이 다음을 만족해야 한다.


$$\begin{aligned}&s_{Euclideun}^2=x^2+y^2+z^2=x'^2+y'^2+z'^2\ \ \&\ \ R^TR=1\end{aligned}$$

이제 로렌츠 변환과 회전 사이의 관계를 자세히 살펴보자.

로렌츠 군을 정의하기 위해서 빌드업을 하겠다.

좌표계 $$X$$에서 관측하는 물리량을 4-vector로 표현하자.


$$\begin{aligned}&X^{\mu }=\left(ct,\ x,\ y,\ z\right),\ \ \mu =0,\ 1,\ 2,\ 3\end{aligned}$$

그러면 시공간 간격을 다음과 같이 구할 수 있다.

$$\begin{aligned}&X\cdot X=X^T\eta X=X^{\mu }\eta _{\mu \nu }X^{\nu }=c^2t^2-x^2-y^2-z^2 \\

&Where, \eta =\begin{pmatrix}1&0&0&0\\0&-1&0&0\\0&0&-1&0\\0&0&0&-1\end{pmatrix}\end{aligned}$$

로렌츠 변환을 하나의 회전변환이라고 생각하고 대문자 람다로 표기하자.

$$\begin{aligned}&X'=\Lambda X\ \ \Rightarrow \ \ X'\cdot X'=X\cdot X=\Delta s^2\ \ \Rightarrow \ \ \Lambda ^T\eta \Lambda =\eta \end{aligned}$$

물론 인덱스를 명확히 표기하면 다음과 같다.

$$\begin{aligned}&X'^{\mu }=\Lambda _{\nu }^{\mu }X^{\nu }\end{aligned}$$

위에서 나온 식을 다시 살펴보자. 우리가 원하는 람다는 아래를 만족한다.


$$\begin{aligned}&\Lambda ^T\eta \Lambda =\eta \end{aligned}$$

양변이 모두 대칭행렬이므로 방정식은 10개의 정보를 제공한다. 그리고 람다는 4곱하기4 행렬이므로 16개의 정보를 가진다. 따라서 해는 총 6개라고 유추할 수 있다.

위의 방정식의 해는 2가지로 나뉜다.

첫번째 해의 형식은 다음과 같다.

$$
\left(
\begin{array}{c | c}
    1 & \begin{matrix}0 & 0 & 0\end{matrix} \\
    \hline
    \begin{matrix} 0\\0\\0\end{matrix} & R
\end{array}
\right)
$$

우리에게 부담스럽지 않은 형태이다. 이 행렬은 시간은 그대로 두고 공간을 바꾼다. 이를 다시 처음의 방정식에 대입하면 행렬 R은 다음을 만족한다.

$$\begin{aligned}&R^TR=1\end{aligned}$$

이는 앞서 봤듯이 회전행렬이 만족해야 하는 조건이다!

$$x,~ y, ~z$$축에 대한 회전행렬이 존재하므로 이 형태의 해가 3개가 나온다.

나머지 3개는 다음과 같은 형태를 띈다.


$$
\left(
\begin{array}{c | c}
     \begin{matrix}\gamma  && - \frac{\gamma }{v} \\\\ - \frac{\gamma}{v} && \gamma\end{matrix} & \begin{matrix} 0 && 0 \\\\ 0&& 0\end{matrix}\\\\
    \hline\\
    \begin{matrix} 0&&0\\\\0&&0\end{matrix} & \begin{matrix}1 && 0\\\\ 0 && 1\end{matrix}
\end{array}
\right)
$$

이것은 우리가 봤던 로렌츠 변환이다! 역시 $$ x,~ y,~ z$$축으로 운동할 수 있으므로 해가 3개가 나온다.

위의 방정식을 만족하는 6개의 해의 집합을 로렌츠 군이라고 부른다. 또는, 직교군 $$O(1,~ 3)$$이라고 부른다. 즉, 로렌츠 군은 시공간에 대한 로렌츠 변환과 회전변환으로 구성된다. 이 군은 대칭성의 측면에서 중요하게 다뤄진다.

위의 방정식의 양변에 디터미넌트를 취하면 다음과 같다.

$$\begin{aligned}&\det \Lambda ^2=1\end{aligned}$$

여기서 경우는 2가지로 나뉜다.

$$\begin{aligned}&\begin{cases}\det \Lambda =1\ \ \Rightarrow \ \ proper\ lorentz\ group,\ SO\left(1,\ 3\right)\\\det \Lambda =-1\end{cases}\end{aligned}$$

또한, 변환이 시간의 방향을 역전시킬수도 있다. 그러나 시간의 방향을 보존하는 경우를 orthochronous 하다고 한다. proper orthochronus group을 $$SO^+(1, 3)$$이라고 부르지만 종종 +를 생략하기도 한다.

그러면, 이제부터 특수상대론의 몇가지 개념들을 나열하겠다.


신속도(Rapidity)의 개념은 상대론에서 생각하는 속도이다. 물체가 느리게 움직일때는 우리가 아는 속도와 같지만 빨라지면 얘기가 달라진다. 빛의 속도와 같은 제한이 없는 속도일 뿐더러, 상대론적인 속력을 구할 때 불편함이 없이 그냥 더하면 된다는 장점이 있다.

람다의 왼쪽 위 2 바이 2 행렬만 취해서 분석하자.

$$
\begin{pmatrix}\gamma && - \frac{\gamma v}{c} \\\\ - \frac{\gamma v}{c} &&\gamma\end{pmatrix}
$$

간단한(!???) 대수를 거치면 다음을 얻을 수 있다. 우리가 아는 상대론적 속력 공식이다.

$$\begin{aligned}&\Lambda \left[v_1\right]\Lambda \left[v_2\right]=\begin{pmatrix}\gamma_1 && - \frac{\gamma_1 v}{c} \\\\ - \frac{\gamma_1 v}{c} &&\gamma_1\end{pmatrix}\begin{pmatrix}\gamma_2 && - \frac{\gamma_2 v}{c} \\\\ - \frac{\gamma_2 v}{c} &&\gamma_2\end{pmatrix}=\Lambda \left[\frac{v_1+v_2}{1+v_1v_2/c^2}\right]\end{aligned}$$

해보면 알겠지만 이 과정은 상당히 번거롭고 지루하다. 결과도 심지어는 더럽다. 이를 간편하게 해줄 방법에 대한 힌트를 회전 행렬에서 찾아보자.

우리는 회전 행렬에서의 합성이 꽤나 단순하단 사실을 안다.

$$\begin{aligned}&R\left[\theta \right]=\begin{pmatrix}\cos \theta && \sin \theta \\\\ -\sin\theta&&\cos \theta\end{pmatrix}\end{aligned}$$

그러므로

$$\begin{aligned}&R\left[\theta _1\right]R\left[\theta _2\right]=R\left[\theta _1+\theta _2\right]\end{aligned}$$

이 성질을 이용하기 위해 신속도를 다음과 같이 정의한다.

$$\begin{aligned}&\gamma =\cosh \phi \\ 
&\Rightarrow \ \ \sinh \phi =\frac{v\gamma }{c}\end{aligned}$$

그러면 람다를 신속도를 이용해 다시 표기할 수 있다.

$$\begin{aligned}&\Lambda \left[\phi \right]=\begin{pmatrix}\cosh \theta && \sinh \theta \\\\ -\sinh\theta&&\cosh \theta\end{pmatrix}\end{aligned}$$

따라서 위의 더럽고 지루했던 속도 합은 깔끔해진다.

$$\begin{aligned}&\Lambda \left[\phi_1 \right] \Lambda \left[\phi _2\right]=\Lambda \left[\phi _1\phi _2\right]\end{aligned}$$

다음으로 상대론적 역학을 보자.

고유시간(proper time)은 아래와 같이 응용된다.

$$\begin{aligned}&\vec{x'}=0인\ S'에서\Delta s^2=c^2\Delta t^2 \\
&\Rightarrow \ \ \Delta \tau =\frac{\Delta s}{c}\ \ 고유시간!!\\
&d\tau =\sqrt{dt^2-\frac{d\vec{x}^2}{c^2}}=dt\sqrt{1-\frac{u^2}{c^2}} \\
&\Rightarrow \ \ \gamma =\frac{dt}{d\tau } \\
&\Rightarrow \ \ T=\int _{\ }^{\ }d\tau =\int _{\ }^{\ }\frac{dt}{\gamma }\end{aligned}$$

고유시간은 정의에서 볼 수 있듯이 모든 관측자가 동의할 수 있는 값이다.

일반적으로 입자는 직선으로 움직이지 않는다.(민코프스키 다이어그램에서 )

앞으로 입자의 세계선을 $$x(\tau)$$ 와 $$t(\tau)$$로 변수화하는 것은 몇가지 이점을 가져다 줄 것이다.

위의 시간 계산이 그 예이다.

다음으로 4-velocity를 알아보자.

입자의 위치를 위에서 배운 고유 시간으로 변수화하자.


$$\begin{aligned}&X\left(\tau \right)=\begin{pmatrix}ct\left(\tau \right)\\\vec{x}\left(\tau \right)\end{pmatrix}\end{aligned}$$

이것으로 우린 4-velocity를 정의할 수 있다.

계속 말하지만 고유시간은 관측자에 무관하기 때문에 좋은 척도가 될 수 있다.

$$\begin{aligned}&U=\frac{dX\left(\tau \right)}{d\tau }=\begin{pmatrix}c\frac{dt\left(\tau \right)}{d\tau }\\\frac{d\vec{x}\left(\tau \right)}{d\tau }\end{pmatrix}=\frac{dt}{d\tau }\begin{pmatrix}c\\\vec{u}\end{pmatrix}=\gamma \begin{pmatrix}c\\\vec{u}\end{pmatrix}\end{aligned}$$

4-velocity 역시 좋은 정의이다. 왜냐하면 그 형태에서 볼 수 있듯이 좌표계 변환에 대해서 동일하게 변환되기 때문이다. 앞서 신속도를 정의할 때도 상대론적 속도의 불편함을 주목했듯이 여기서도 마찬가지이다.


$$\begin{aligned}&U'=\Lambda U\ \ \left(\because d\tau 가\ 모든\ 관측자에게\ 동일\right)\end{aligned}$$

만약, 우리가 4-velocity를 고유 시간이 아니라 그냥 시간을 이용해서 정의했더라면 계산에서 꽤나 어려움을 겪었을 것이다.

입자의 위치, 속도의 형태를 보면 모두 4-vector이다. 4-vetor는 4개의 요소를 가지는 벡터 중에서 로렌츠 변환을 따르는 것들을 통칭한다.

우리가 앞서서 로렌츠 군의 특성을 언급했듯이 4-velocity는 다음의 성질을 가진다.

$$\begin{aligned}&U\cdot U=U^T\eta U=U'\cdot U'=\gamma ^2\left(c^2-u^2\right)=c^2\end{aligned}$$

뉴턴역학과 비슷하게 4-velocity 역시 3개의 요소만 알면 충분하다. 위의 성질을 만족하기 때문이다.

우리가 여태껏 구한 상대론적 상대속도는 오직 한 축에 대한 운동만이었다. 만약 사건의 이동이 관성좌표계 사이의 상대이동과 평행하지 않으면 어떻게 될까? 즉, $$S,\ S'$$이 $$x$$축에 대해 $$v$$의 상대속도로 움직이고 있는데, 사건 $$A$$가 $$xy$$평면에서 $$u$$의 속도로, 각도 $$(\alpha)$$를 가지고 운동한다면 어떻게 될까?

우리는 4-velocity로 구할 수 있다.

$$\begin{aligned}
&U=\begin{pmatrix}\gamma _uc\\u\gamma _u\cos \alpha \\u\gamma _u\sin \alpha \\0\end{pmatrix}\ \ \Rightarrow \ \ U'=\Lambda U=\gamma _u\begin{pmatrix}\left(1-\frac{uv}{c^2}\cos \alpha \right)\gamma _vc\\\left(u\cos \alpha -v\right)\gamma _v\\u\sin \alpha \\0\end{pmatrix}\equiv \begin{pmatrix}\gamma _{u'}c\\u'\gamma _{u'}\cos \alpha '\\u'\gamma _{u'}\sin \alpha '\\0\end{pmatrix}\\
&\therefore u'\cos \alpha '=\frac{u\cos \alpha -v}{1-uv\cos \alpha /c^2},\ \ \tan \alpha '=\frac{u\sin \alpha }{\gamma _v\left(u\cos \alpha -v\right)}
\end{aligned}$$

4-velocity를 정의했으니 4-momentum도 정의할 수 있다.

$$\begin{aligned}&P=mU=\begin{pmatrix}mc\gamma \\m\gamma \vec{u}\end{pmatrix}=\begin{pmatrix}mc\gamma \\\vec{p}\end{pmatrix}\end{aligned}$$

한번, 4-momentum의 시간 요소를 감마에 대해서 테일러 전개해보자.

$$\begin{aligned}&P^0=\frac{mc}{\sqrt{1-\frac{u^2}{c^2}}}=\frac{1}{c}\left(mc^2+\frac{1}{2}mu^2+\cdots \right)\end{aligned}$$

괄호 속의 첫번째 항은 상수이고 두번째 항은 비상대론적인 운동에너지이다. 여기서 우리는 4-momentum의 시간 요소가 에너지와 연관있음을 강하게 추측할 수 있다.(물론 에너지를 $$c$$로 나눈 것) 그러므로 아래와 같이 추측하자.

$$\begin{aligned}&P=\begin{pmatrix}E/c\\\vec{p}\end{pmatrix}\end{aligned}$$

엄밀한 증명은 뇌터의 정리를 이용해서 할 수 있다. 역시 나중에 소개하겠다.

어쨌든간에 이를 통해 입자의 총에너지를 다음과 같이 얻는다.

$$\begin{aligned}&E=\gamma mc^2\end{aligned}$$

질량-에너지 등가 공식과 매우 유사하지만 앞에 뭔가가 달려있다.

우리가 아는 공식에는 감마가 달려있지 않은데, 그 이유는 우리가 알고 있는 공식이 정지에너지에 대한 것이기 때문이다. 위의 에너지는 총 에너지로 정지에너지와 운동에너지를 포함한다. 그러면 정지에너지는 어떻게 구하냐?

간단한 계산으로 운동에너지를 먼저 구하면 된다.

$$\begin{aligned}&T=\int _0^pvdp=pv-\int _0^vpdv=pv-\int _0^vm_0\gamma vdv=pv-m_0\int _0^v\frac{v}{\sqrt{1-v^2/c^2}}dv\\
&=pv-m_0c\int _0^v\frac{v}{\sqrt{c^2-v^2}}dv\\ 
&=pv-m_0c\int _c^{\sqrt{c^2-v^2}}\frac{-t}{t}dt\\
&=pv+m_0c\left[t\right]_c^{\sqrt{c^2-v^2}}\\
&=pv-m_0c\left(c-\sqrt{c^2-v^2}\right)\\
&=m_0\gamma v^2-\left(1-\sqrt{1-v^2/c^2}\right)m_0c^2\\
&=\left(\gamma -1\right)m_0c^2\end{aligned}$$

그러므로 운동에너지를 구했으니까 정지 에너지가 우리가 아는 형태가 됨을 알 수 있다.

운동량을 가지고 계산의 편의를 위한 공식만 하나 더 만들어보겠다.

정석이 있지만 계산이 귀찮기 때문에 트릭을 써보자.

앞에서 우리는 4-vector들의 내적이 좌표계에 무관한 성질을 가짐을 알고 있다. 그렇기 때문에 운동량을 입자의 속도가 0인 좌표계에서 한번 내젹하고 그냥 한번 내적해보자.

$$\begin{aligned}&P\cdot P=m^2c^2=\frac{E^2}{c^2}-p^2\\
&\Rightarrow \ \ E^2=p^2c^2+m^2c^4\end{aligned}$$

이 공식은 꽤 요긴하게 쓰인다.

지금 한번 써보자. 바로 질량이 없는 입자이다.

질량이 없는 입자는 광자로 우리가 알고 있는 빛이다. 고전적으로 빛은 운동량을 가지지 않는다. 질량이 없기 때문이다. 그러나 지금 유도한 공식에 따르면 빛은 $$h\nu$$의 에너지를 가지기 때문에 운동량을 가진다. 이것은 물질의 파동성에서도 응용되고 수없이 많이 쓰인다. 빛의 운동량에 대해서는 나중에 자세히 알아보자.

* 타키온이라고 하는 입자는 허수 질량을 가진다. 특수상대론에서 이 경우 운동량의 내적이 음수이기 때문에 빛보다 빠르게 움직여야 하지만 그렇지 않다. 이것에 대해서는 양자장론이 해결한다고 한다. 자세히는 몰라유;;

이제 정말 마지막으로 특수상대론에서의 뉴턴 역학과 가속 운동에 대해서 알아보고 마치겠다.

4-vector force를 생각하자.

$$\begin{aligned}&F^{\mu }=\frac{dP^{\mu }}{d\tau }=\begin{pmatrix}F^0\\\gamma \vec{f}\end{pmatrix}\end{aligned}$$

운동량과 힘은 다음과 같은 관계를 가졌다.

$$\begin{aligned}&\vec{f}=\frac{d\vec{p}}{dt}=\frac{d\vec{p}}{d\tau }\frac{d\tau }{dt}=\gamma \frac{d\vec{p}}{d\tau }\end{aligned}$$

우리는 4-vector force의 첫번째 항에도 적용해보면 시간에 따른 에너지의 변화와 연관이 있을것이라 추측할 수 있다. 4-mometum의 첫번째 항이 에너지와 관련있었기 때문이다.

$$\begin{aligned}&F^0=\frac{dP^0}{d\tau }=\frac{\gamma }{c}\frac{dE}{dt}\end{aligned}$$

이것으로 우리는 잘 아는 결론을 이끌어낼 수 있다.

운동량의 내적은 항상 보존되기 때문에


$$\begin{aligned}&0=\frac{d}{d\tau }\left(P\cdot P\right)=2P^0\frac{dP^0}{d\tau }-2\vec{p}\cdot \frac{d\vec{p}}{d\tau }=2\gamma ^2\left(\frac{dE}{dt}-\vec{u}\cdot \vec{f}\right)\end{aligned}$$

에너지는 보존된다.

가속의 개념이 특수상대론에서 나와서 어색할 수도 있다. 특수상대론은 관성좌표계에서 모든 것을 설명하기 때문이다. 정의는 아래와 같다.

$$\begin{aligned}&A\equiv \frac{dU}{d\tau }\end{aligned}$$

항상 가속도와 속도는 orthogonal 함을 알아두자.

$$\begin{aligned}&\left(\because A\cdot U=\frac{dU}{d\tau }\cdot U=\frac{1}{2}\frac{d}{d\tau }\left(U\cdot U\right)=\frac{1}{2}\frac{d}{d\tau }\left(c^2\right)=0\right)\end{aligned}$$

$$S$$좌표계에서의 가속도와 속도를 이용해서 표현하면 다음과 같다.

$$\begin{aligned}&A=\gamma \begin{pmatrix}\dot{\gamma }\\\dot{\gamma }\vec{u}+\gamma \vec{a}\end{pmatrix}\ \ where\ \dot{\gamma }=\frac{d\gamma }{dt}\end{aligned}$$

이제 속도가 0으로 보이는 좌표계 $$S'$$을 선택해서 생각해보자. 4-vector이기 때문에 로렌츠 변환의 관계가 있어야 한다.

$$\begin{aligned}&A'=\gamma \begin{pmatrix}0\\\vec{a'}\end{pmatrix}\\
&A=\gamma \begin{pmatrix}\dot{\gamma }\\\dot{\gamma }\vec{u}+\gamma \vec{a}\end{pmatrix}=\begin{pmatrix}\gamma &u\gamma /c\\u\gamma /c&\gamma \end{pmatrix}\begin{pmatrix}0\\\vec{a'}\end{pmatrix}=\begin{pmatrix}u\gamma \vec{a'}/c\\\gamma \vec{a'}\end{pmatrix}\\
&\Rightarrow \ \ \vec{a}\equiv \dot{u}=\left(1-v^2/c^2\right)^{3/2}\vec{a'}\end{aligned}$$

$$S'$$ 좌표계에서 등가속도 운동을 한다고 가정하면 다음을 만족한다. $$S$$좌표계에서는 등가속도 운동이 아니다.


$$\begin{aligned}&u=\frac{\vec{a'}ct}{\sqrt{c^2+a'^2t^2}}\ \ \Rightarrow \ \ \gamma =\sqrt{1+\frac{a'^2t^2}{c^2}}\end{aligned}$$

시간에 따른 위치는 다음과 같다.


$$\begin{aligned}&x=\frac{c}{a'}\left(\sqrt{c^2+a'^2t^2}-c\right)\end{aligned}$$

입자는 민코프스키 다이어그램에서 쌍곡선을 따라 움직인다.

![Full-width image](/assets/img/physics/2022-07-26-Special-Relativity-1/6.png){:.centered}
Figure 6. Minkoffski Diagram.
{:.figcaption}

$$x=ct$$를 경계선으로 그 왼쪽의 세상은 가속하는 관측자에게는 미지의 세계일 것이다.

이 경계선을 rindler event horizon이라고 부른다. 블랙홀의 사건의 지평선과 많은 것을 공유한다.

만약 이 지평선 너머를 보고 싶다면 가속을 멈추면 된다. 이제 블랙홀에서 같은 것을 시도해보기를 바란다. 굉장한 용기가 필요할 것이다.

진짜 마지막으로 관측자가 느낄 시간에 대해 구해보고 마친다.


$$\begin{aligned}\tau =\int _0^t\frac{cd\overline {t}}{\sqrt{c^2+a'^2\tilde{t}^2}}=\frac{c}{a'}\sinh ^{-1}\left(\frac{a't}{c}\right)\end{aligned}$$

---

문제 1.

시계 $$C$$가 관성좌표계 $$S$$의 원점에 있고 시계 $$C'$$이 관성 좌표계 $$S'$$의 원점에 있다. 현재 두 시계는 0초로 동기화 되어있고 두 좌표계는 $$u$$의 속도로 운동한다.

(1) $$C$$가 $$t_1$$에 보낸 라디오 신호를 $$C'$$이 $$t_2'$$에 받는다. 이 과정을 민코프스키 다이어그램에 나타내어라.

(2) $$t_1$$과 $$t_2'$$의 관계를 구하여라.


문제 2.

광자가 $$S$$좌표계에서 $$E$$의 에너지를 가지고 $$x$$축과 $$\theta$$의 각을 이루면서 직진하고 있다. $$S$$와 $$x$$축 방향으로 $$u$$의 속도로 멀어지는 좌표계 $$S'$$에서 본 에너지와 각도가 다음과 같음을 구하시오.

$$\begin{aligned}&E'=\gamma E\left(1-\beta \cos \theta \right),\ \ \cos \theta '=\frac{\cos \theta -\beta }{1-\beta \cos \theta }\\
&where\ \beta =\frac{v}{c}\end{aligned}$$

추가로 $$\theta=0$$일 때 빛의 도플러 이동을 증명하시오.


문제 3.

좌표계 $$S$$에서 어떤 입자의 4-momentum이 $$P$$이다. 4-velocity가 $$U$$인 관측자가 입자를 관측했을 때 속도가 $$v$$였다. $$v$$를 $$U$$와 $$P$$로 나타내시오.


문제 4.

질량 $$m_0$$인 입자가 폭발해서 질량이 $$m_1$$인 입자와 $$m_2$$인 입자로 쪼개졌다. 각 입자의 에너지를 구하시오.

(힌트: $$(P_0 - P_1)\cdot(P_0 - P_1)$$와 $$(P_0 - P_2 ) \cdot (P_0 - P_2 )$$가 보존된다.)


문제 5.

(1) 어떤 로켓이 자신에 대해 상대속력 $$u$$로 연료를 분사하고 있다. 시간에 따라서 로켓의 질량을 $$m$$으로 하고 속도를 $$v$$로 하자. (좌표계는 로켓의 처음 좌표계이다. 정지한 상태였을 때)

로켓의 4-momentum의 미소 변화를 이용해서 다음 방정식을 이끌어내라.

$$\begin{aligned}&\frac{d\left(m\gamma v\right)}{dv}=\left(\frac{u-v}{1-uv/c^2}\right)\frac{d\left(m\gamma \right)}{dv}\end{aligned}$$

(2) 위의 방정식을 정리해서 $$m$$, $$\gamma$$에 대한 미분방정식으로 바꾸고 상대론적 로켓방정식을 유도해라.

$$\begin{aligned}&v=c\tanh \left(\frac{u}{c}\log r\right),\ \ where\ r=\frac{m_0}{m}\end{aligned}$$

(3) 만약 로켓이 분출하는 연료가 광자라면 이에 대한 로켓방정식을 유도해봐라.


---

풀이 1.

(1)

![Full-width image](/assets/img/physics/2022-07-26-Special-Relativity-1/7.png){:.centered}

(2)

다음 식을 연립하면 된다.

$$\begin{aligned}&\begin{cases}ct_2=\frac{x}{\beta }\\ct_2=x+ct_1\\ct_2'=\sqrt{1-\beta ^2}ct_2\end{cases}\\
&\Rightarrow \ \ t_1=t_2'\sqrt{\frac{1-\beta }{1+\beta }}\end{aligned}$$

풀이 2.

4-velocity에서 했던 것을 떠올리자.

$$\begin{aligned}&U=\begin{pmatrix}\gamma _uc\\u\gamma _u\cos \alpha \\u\gamma _u\sin \alpha \\0\end{pmatrix}\ \ \Rightarrow \ \ U'=\Lambda U=\gamma _u\begin{pmatrix}\left(1-\frac{uv}{c^2}\cos \alpha \right)\gamma _vc\\\left(u\cos \alpha -v\right)\gamma _v\\u\sin \alpha \\0\end{pmatrix}\equiv \begin{pmatrix}\gamma _{u'}c\\u'\gamma _{u'}\cos \alpha '\\u'\gamma _{u'}\sin \alpha '\\0\end{pmatrix}\\
&\therefore u'\cos \alpha '=\frac{u\cos \alpha -v}{1-uv\cos \alpha /c^2},\ \ \tan \alpha '=\frac{u\sin \alpha }{\gamma _v\left(u\cos \alpha -v\right)}\end{aligned}$$

똑같이 전개하면 4-mometum의 변환관계도 알 수 있다. 대입하면

$$
\begin{aligned}&
E'=\gamma E\left(1-\beta \cos \theta \right),\ \ \cos \theta '=\frac{\cos \theta -\beta }{1-\beta \cos \theta }\\
&where\ \beta =\frac{v}{c}
\end{aligned}$$

$$\theta$$가 0이면 에너지가 다음과 같이 변환된다.

$$\begin{aligned}&hf'=E'=\frac{1}{\sqrt{1-\beta ^2}}E\left(1-\beta \right)=hf\sqrt{\frac{1-\beta }{1+\beta }}\end{aligned}$$

풀이 3.

관측자의 좌표계로 변환하면 된다.

$$\begin{aligned}
&U'=\Lambda U=\begin{pmatrix}c\\0\end{pmatrix}\\
&P'=\Lambda P=m\gamma \begin{pmatrix}c\\v\end{pmatrix}\\
&\Rightarrow \ \ U'\cdot P'=\Lambda ^2U\cdot P=U\cdot P=m\gamma c^2=\frac{mc^2}{\sqrt{1-\beta ^2}}\\
&\Rightarrow \ \ \frac{v}{c}=\beta =\sqrt{1-\frac{m^2c^4}{\left(P\cdot U\right)^2}}=\sqrt{1-\frac{\left(P\cdot P\right)c^2}{\left(P\cdot U\right)^2}}
\end{aligned}
$$

풀이 4.

$$
\begin{aligned}
E_1 = c^2 \frac{m_0^2 + m_1^2 - m_2^2 }{2m_0} ~~and ~~ E_2 = c^2 \frac{m_0^2 + m_2^2 - m_1^2}{2m_0}
\end{aligned}
$$


풀이 5.

(1)

지면에 대한 연료의 속력을 $$u'$$, 이에 대한 감마를 $$\gamma'$$이라고 두자. 전체 4-momentum은 보존되기 때문에 다음을 만족한다.

$$
\begin{aligned}
&dP_{rocket}=\begin{pmatrix}cd\left(m\gamma \right)\\d\left(m\gamma v\right)\end{pmatrix}=-dP_{fuel}=\begin{pmatrix}\gamma 'cdm\\\gamma 'u'dm\end{pmatrix}\\
&\Rightarrow \ \ \begin{cases}cd\left(m\gamma \right)=\gamma 'cdm\\d\left(m\gamma v\right)=\gamma 'u'dm\end{cases}\\
&\Rightarrow \ \ d\left(m\gamma v\right)=u'd\left(m\gamma \right)\\
&\Rightarrow \ \ \frac{d\left(m\gamma v\right)}{dv}=\left(\frac{v-u}{1-uv/c^2}\right)\frac{d\left(m\gamma \right)}{dv}
\end{aligned}
$$

(2)

곱의 미분으로 왼쪽 항을 쪼개주면 된다.

$$\begin{aligned} 
&\left(\frac{v-u}{1-uv/c^2}\right)\frac{d\left(m\gamma \right)}{dv}=\frac{d\left(m\gamma v\right)}{dv}=m\gamma +v\frac{d\left(m\gamma \right)}{dv}\\
&\Rightarrow \ \ \frac{1}{m\gamma }d\left(m\gamma \right)=\frac{c^2-uv}{u\left(v^2-c^2\right)}dv\\
&\Rightarrow \ \ \ln \left(\frac{m\gamma }{m_0}\right)=\int _0^v\frac{c^2-uv}{u\left(v^2-c^2\right)}dv=\int _0^v\frac{1}{2u}\left(\frac{c-u}{v-c}-\frac{c+u}{v+c}\right)dv\\
&\qquad\qquad\qquad~=\frac{c-u}{2u}\ln \left(\frac{c-v}{c}\right)-\frac{c+u}{2u}\ln \left(\frac{c+v}{c}\right)=\frac{c}{2u}\ln \left(\frac{c-v}{c+v}\right)-\ln \sqrt{1-\frac{v^2}{c^2}}\\
&\qquad\qquad\qquad~=\frac{c}{2u}\ln \left(\frac{c-v}{c+v}\right)+\ln \gamma =\ln \gamma -\ln r\\
&\Rightarrow \ \ \ln r=\frac{c}{2u}\ln \left(\frac{c+v}{c-v}\right)\\
&\therefore v=c\tanh \left(\frac{u}{c}\ln r\right)
\end{aligned}
$$
