---
layout: post
title: "Ultimate Classical Mechanics Note"
subtitle: "Ultimate Classical Mechanics Note"
category: physics
tags: classical-mechanics
image: 
  path: /blog/assets/img/physics/2022-07-26-Special-Relativity-1/2.png
---
Mechanics of Single Particle

먼저, 입자 1개의 운동의 분석으로 시작한다. 역학을 하기에 앞서 입자의 운동에 관련된 변수를 정의해야 한다. 기본적으로 입자의 운동이란 시간에 따라서 입자가 변위하는 것을 말한다. 그렇기에 먼저, 입자의 위치를 정의해야 한다. 좌표축이 없는 유클리드 공간에서 입자의 위치를 논하는 것은 부적절하기에 좌표축을 도입한다. 자연스럽게 원점이 정의되며 입자의 위치는 원점에서부터 입자가 점유하고있는 점까지의 벡터이며 $$\textbf{r}$$으로 표기한다. 일반적으로 물리에서는 입자의 위치의 변화를 논하기 때문에 두 사건 사이의 위치 벡터를 사용한다. 이를 **변위**(Displacement)라고 부른다. 

시간에 따라 입자의 위치가 변하는 것이 바로 운동이며 그 정도를 논하는 것은 당연한 수순이다. 그렇기에 $$\Delta t$$의 시간 동안 입자의 위치가 얼마나 변하였는지를 보아야 한다. 

$$\begin{align}
    &\textbf{v}_{\textrm{Average}}:= \frac{\Delta {\textbf{r}}}{\Delta t}\\
    &\textbf{v}_{\textrm{Instantaneous}}:= \lim_{\Delta t \rightarrow 0} \frac{\Delta \textbf{r}}{\Delta t} = \frac{d \textbf{r}}{dt} = \dot{\textbf{r}}
\end{align}$$

위의 것은 **평균 속도**(Average Velocity)이고 아래 것은 **순간 속도**(Instantaneous Velocity)이다. 또한, 각각의 크기는 평균 속력(Average Speed)와 순간 속력(Instantaneous Speed)이다. 앞으로 대부분의 경우 순간 속도를 다룰 것이다. 


이제 우리는 이 속도를 가지고 입자가 운동하는 정도라고 말할 수 있다. 경험적으로 속도를 바꾸는 것은 힘이기 때문이다. 우주 공간에서 힘을 받지 않으면 등속으로 운동한다. 이 경우는 너무 단순하므로 우리는 운동의 변화가 일어나는데에 주목할 것이다. 한편, 운동의 변화를 논하기 위해서 운동하는 정도를 조금 더 엄밀히 할 필요가 있다. 경험적으로 같은 힘을 주더라도 어떤 물체는 속도가 크게 변하지만 어떤 것은 그렇지 않기 때문이다. 따라서 이러한 **관성**(Inertia)현상의 척도로 **질량**(Mass)\footnote{질량을 엄밀하게 정의하는 것은 상당히 중요하다. 사실 뉴턴 제 2법칙은 관성의 척도인 질량을 정의하는 식이다. 현대 물리학의 최전선에서는 다음과 같이 정의한다. \begin{center}
    \textit{Higgs}입자에 의한 \textbf{힉스장}(Like a Magnetic Field)이 입자와 상호 작용하는 정도.
\end{center}물론 전체 질량 중에서 힉스 입자는 4\%정도밖에 기여하지 않는다. 나머지 96\%정도는 강한 상호작용에 의한 결합 에너지의 형태로 저장된 질량이다. $$E=mc^2$$}를 사용하자. 즉, 운동의 정도인 \textbf{(선)운동량}(Linear Momentum)을 다음과 같이 정의하자. 
$$\begin{equation}
    \textrm{\textbf{p}}:=m \textrm{\textbf{v}}
\end{equation}$$
이제 우리는 자연스럽게 힘을 정의할 수 있다. 위치가 변하는 정도를 속도로 정의했던 것과 마찬가지의 방식으로 힘을 정의하면 된다. 
$$\begin{align}
    &\textrm{\textbf{F}}:=\frac{d\textrm{\textbf{p}}}{dt} = \frac{d(m\textrm{\textbf{v}})}{dt}=m\frac{d^2 \textrm{\textbf{r}}}{dt^2}=m\textrm{\textbf{a}}\\
    &\textrm{\textbf{a}}:=\frac{d^2 \textrm{\textbf{v}}}{dt^2}
\end{align}$$
이는 \textbf{뉴턴의 운동의 제 2법칙}(Newton's Second Law of Motion)이다. 힘의 분석을 위해서는 가속도가 도입되어야 한다. 

정의에 따라 입자 1개에 대한 \textbf{운동량 보존 법칙}(Conservation Theorem for the Linear Momentum)이 유도된다. 
$$\begin{equation}
    \textrm{\textbf{F}}=0 ~\Longrightarrow~\textrm{\textbf{p}}=const
\end{equation}$$
즉, 입자에 힘이 작용하지 않으면 운동량은 보존된다. 



힘의 작용에 의한 결과를 다른 시각에서 바라볼 수 있다. 바로 \textbf{에너지}(Energy)이다. 입자가 운동을 하면 이 입자는 자신의 운동을 감소시켜 주위에 어떤 입자를 운동시킬 수 있는 능력을 가지게 된다. 이를 두고 에너지가 상승했다고 표현하며 특별히 운동의 형태로 나타나는 것을 \textbf{운동 에너지}(Kinetic Energy)라고 부른다. 이러한 에너지는 결국 힘이 한 \textbf{일}(Work)의 결과로 볼 수 있는데, 힘이 한 일은 다음과 같이 정의한다. 
$$\begin{equation}
    w_{12}:=\int_{1}^{2}{\textrm{\textbf{F}}\cdot d\textrm{\textbf{s}}}
\end{equation}$$
이에 따라 운동 에너지를 정의할 수 있다. 입자에 한 일이 오로지 입자의 운동으로만 전달되었을 때 그 일을 구하면 된다. 
$$\begin{align}
    \int{\textrm{\textbf{F}}\cdot d\textrm{\textbf{s}}}=m\int{\frac{d\textrm{\textbf{v}}}{dt}\cdot \textrm{\textbf{v}}dt}= \frac{m}{2}\int{\frac{d}{dt}(v^2 ) dt}= \frac{1}{2}m(v_{f}^2 - v_{i}^2)
\end{align}$$
$$\begin{equation}
    T:=\frac{1}{2}mv^2
\end{equation}$$
한편, 에너지는 꼭 운동의 형태로만 저장되지 않는다. 예를 들어 중력의 상황에서 우리가 높은 곳에 물체를 놓으면 높을수록 더 많은 일을 할 수 있다. 이처럼 힘이 작용하는 공간에서 정의되는 에너지가 있다. 특별히 힘 중에서도 \textbf{보존력}(Conservative Force)를 선택한다. 보존력은 입자에 작용하는 힘 중에서 입자가 어떠한 경로로 움직여도 시작점과 끝점이 같다면 보존력에 의해 한 일이 일정한 힘을 말한다. 즉, 다음을 만족한다. 
$$\begin{equation}
    \oint{\textrm{\textbf{F}}_C \cdot d\textrm{\textbf{s}}}=0~\Longrightarrow~\textrm{\textbf{F}}_C = - \nabla V(\textrm{\textbf{r}})
\end{equation}$$
위는 스토크스 정리에 따른 결과이다. 폐곡선에 대한 선적분은 회전의 면적분과 같고 임의의 폐곡선에 대해서 회전이 0이란 뜻은 항등적으로 힘의 회전이 0이란 소리이다. 회전이 0인 벡터장은 어떤 스칼라 퍼텐셜의 발산으로 나타낼 수 있다. 그러한 퍼텐셜을 사용할 것이다. \textbf{퍼텐셜 에너지}(Potential Energy)의 정의는 다음과 같다. 
$$\begin{equation}
    \Delta V:=-\int_{i}^{f}{\textrm{\textbf{F}}_C \cdot d\textrm{\textbf{s}}}
\end{equation}$$
퍼텐셜 에너지의 차이가 정의된 반면, 절대적인 값의 퍼텐셜 에너지를 위치의 함수로써 정의하고 싶을 것이다. 보통 이런 경우 처음 위치 $$i$$를 무한히 멀리 떨어진 곳으로 설정하거나 적절한 위치로 설정한다. 그러나 중요한 것은 퍼텐셜 에너지는 차이만이 의미를 가진다는 것이다. 



이제 우리는 운동 에너지와 퍼텐셜 에너지의 합으로 \textbf{역학적 에너지}(Mechanical Energy)를 정의할 수 있다. \footnote{이러한 퍼텐셜이 퍼져있는 공간을 \textbf{장}(Field)라고 부른다. 장론에서는 입자와 장의 상호 작용으로 역학을 기술한다. 이러한 상호 작용을 고려하는 것은 상당히 중요하다. 다음의 예시를 보라. 

전자(Electron)은 질량이 $$m=10^{-31}\textrm{kg}$$이고 전하량이 $$q=-1.6\times 10^{-19}\textrm{C}$$이다. 전자의 반지름은 아무리 커봐야 $$10^{-18}\textrm{m}$$이하임이 알려져있다. 전자의 내부가 적당한 음전하의 분포로 이루어져 있으며 극단적으로 2개의 음전하 방울이 쌍극자를 이루는 모델을 고려하라. 그러면 전기력에 의한 위치 에너지는 $$10^{-9}\textrm{J}$$ 이상이다. 이러한 위치 에너지는 곧 전자의 정지 에너지를 설명하기 위함이다. 한편, $$E=mc^2$$에 따르면 전자의 정지 질량은 대략 $$10^{-13}\textrm{J}$$이다. 두 이론의 모순이 발생한 것이다. 다행이 이러한 모순은 \textbf{양자장론}(Quantum Field Theory)에서 해결한다. \textbf{불확정성 원리}(Uncertainty Principle)에 따르면 $$\Delta E \Delta t \geq \hbar$$이다. 즉, 충분히 작은 시간 간격 동안에는 아무리 진공 상태일지라도 에너지의 변화가 발생한다. 이러한 현상은 가만히 있는 전자에게 다음과 같은 상황을 발생시킨다.
\begin{center}
\begin{fmffile}{diagram}
\begin{fmfgraph*}(100,50)
    \fmfleft{i1}
    \fmfright{o1,o2}
    \fmf{photon,label=$\gamma$}{i1,w1}
    \fmf{electron,label=$e^{-}$}{w1,o1}
    \fmf{electron,label=$e^{+}$}{w1,o2}
\end{fmfgraph*}
\end{fmffile}
\end{center}
진공에서의 진동에 의해 전자에서 광자가 나오고 이 광자가 양전하를 가진 입자와 음전하를 가진 입자로 쪼개진다. 이 중 양전하를 가진 입자는 전자와 가까워지고 음전하를 가진 입자는 전자와 멀어지는데, 이러한 현상은 전자의 전하량을 감쇠시키는 효과를 미친다. 이에 따라 지나치게 컸던 전기적 위치 에너지를 정지 질량 에너지까지 낮출 수 있다. 핵심은 입자가 스스로만 상호작용하지 않고 장과 상호작용한다는 사실이다. }
$$\begin{equation}
    E_{Mechanical}:=T+V
\end{equation}$$
운동량에서와 마찬가지로 이에 대해서도 보존 법칙이 성립한다. \textbf{에너지 보존 법칙}(Conservation Theorem for the Energy)는 다음과 같다. 
$$\begin{equation}
    \textit{Force is Conservative} ~\Longrightarrow~\frac{d}{dt}(T+V)=0
\end{equation}$$
보존력이 작용하는 상황에서 역학적 에너지는 항상 일정하게 보존된다. 반대로 보존력 이외의 힘이 작용하면 시간에 따라 역학적 에너지가 변한다. 얼마나 변하는가? 어떤 힘이 한 일을 시간에 따라 미분한 것을 \textbf{일률}(Power)라고 부른다. 
$$\begin{equation}
    P:=\frac{dw}{dt}=\frac{d}{dt}\int{\textrm{\textbf{F}}\cdot d\textrm{\textbf{s}}}=\frac{d}{d\textrm{\textbf{s}}}\int{\textrm{\textbf{F}}\cdot d\textrm{\textbf{s}}}\frac{d\textrm{\textbf{s}}}{dt}=\textrm{\textbf{F}}\cdot\textrm{\textbf{v}}
\end{equation}$$
위를 해석하자면, 힘이 시간에 따라 일을 하는 정도는 힘의 크기와 속도에 비례한다. 즉, 계가 운동 에너지를 많이 가지고 있으면 일을 하기 수월해진다.


이제 입자 1개의 운동에 대한 논의가 모두 끝났다. 다음 단계로 입자계에 대한 분석을 해야할 것이다. 그러나 이에 앞서 입자 1개의 특별한 운동을 보자. 바로 회전 운동이다. 입자의 회전 운동은 가속 운동으로 힘이 작용해야 하며 이러한 운동은 입자 1개만 있는 상황에서는 일어날 수 없다. 그러나 원인을 모르지만 적절한 힘이 작용하여 원운동을 하고 있는 입자를 살펴보는 것은 흐름상 유용하다. 


회전 운동과 직선 운동은 상당히 밀접한 연관(Analogy)가 있다. 직선 운동에서 그랬던 것과 마찬가지로 회전 운동 역시 새롭게 정의해야 한다. 회전 운동을 기술하기 위해 필요한 기초가 무엇인가? 바로 각도이다. 주로 $$\theta$$로 표기한다. 직선 운동에서와의 유사성(Analogy)에 따라 회전 운동의 변화 등을 이용해 다음을 정의할 수 있다. 
$$\begin{align}
    &\omega_{\textrm{Average}}:= \frac{\Delta \theta}{\Delta t}\\
    &\omega_{\textrm{Instantaneous}}:= \lim_{\Delta t \rightarrow 0} \frac{\Delta \theta}{\Delta t} = \frac{d \theta}{dt} = \dot{\theta}
\end{align}$$
각각 \textbf{평균 각속도}(Average Angular Velocity)와 \textbf{순간 각속도}(Instantaneous Angular Velocity)이다. 벡터라고 생각해주길 바란다.(Bold체를 적용할 수 없다...) 회전하는 정도는 앞서 본 바와 같이 회전 관성 현상의 척도인 \textbf{회전 관성}(Moment of Inertia) $$I$$를 도입하여 각운동량(Angular Momentum)을 정의한다. 
$$\begin{equation}
    \textrm{\textbf{L}}:=I \omega
\end{equation}$$
이제 우리는 자연스럽게 힘을 정의할 수 있다. 위치가 변하는 정도를 속도로 정의했던 것과 마찬가지의 방식으로 힘을 정의하면 된다. 
$$\begin{align}
    &\tau:=\frac{d\textrm{\textbf{L}}}{dt} = \frac{d(I \omega)}{dt}=I\frac{d^2 \theta}{dt^2}=I\alpha\\
    &\alpha:=\frac{d^2 \theta}{dt^2}
\end{align}$$
정의에 따라 입자 1개에 대한 \textbf{각운동량 보존 법칙}(Conservation Theorem for the Linear Momentum)이 유도된다. 
$$\begin{equation}
    \tau = 0 ~ \Longrightarrow ~ \textrm{\textbf{L}}=const
\end{equation}$$
입자에 토크가 작용하지 않으면 각운동량이 보존된다.



선운동의 변수와 회전 운동의 변수는 다음과 같은 관계를 가진다. 
$$
\begin{align*}
    \textrm{\textbf{r}} ~&\Longleftrightarrow~\theta\\
    \textrm{\textbf{v}}=\frac{d \textrm{\textbf{r}}}{dt} ~&\Longleftrightarrow~ \omega = \frac{d \theta}{dt}\\
    \textrm{\textbf{a}}=\frac{d^2 \textrm{\textbf{r}}}{dt^2} ~&\Longleftrightarrow~ \alpha = \frac{d^2 \theta}{dt^2}\\
    \textrm{\textbf{p}}=m\textrm{\textbf{v}}~&\Longleftrightarrow~ \textrm{\textbf{L}}=I\omega = \textrm{\textbf{r}}\times\textrm{\textbf{p}}\\
    \textrm{\textbf{F}}=m\textrm{\textbf{a}}~&\Longleftrightarrow~ \tau=I\alpha = \textrm{\textbf{r}}\times\textrm{\textbf{F}}\\
    T = \frac{1}{2}mv^2 ~ &\Longleftrightarrow ~ T = \frac{1}{2}I \omega^2\\
    dw = \textrm{\textbf{F}}\cdot \textrm{\textbf{s}} ~&\Longleftrightarrow ~dw=\tau \cdot d \theta\\
    P=\textrm{\textbf{F}}\cdot \textrm{\textbf{v}}~&\Longleftrightarrow ~ P = \tau \cdot \omega 
\end{align*}
$$
자세한 증명은 부록을 참고하라. 