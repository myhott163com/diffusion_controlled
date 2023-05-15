# DIFFUSION-CONTROLLED REACTION RATES
\title{
DIFFUSION-CONTROLLED REACTION RATES
}

\author{
Frank C. Collins* and George E. Kimball \\ From the Department of Chemistry, Columbia University, New York, N. Y. \\ Received March 9,19199
}

\section{INT'RODUCTION}

The theory of the kinetics of colloid coagulation as a diffusioncontrolled process was originally developed by Smoluchowski (1) using Fick's law of diffusion. As ordinarily applied, the theory is based on the assumptions that around one of the reactant particles a concentration gradient for the other species is set up, and that the rate of flow of particles in this concentration gradient is governed by Fick's law of diffusion. The fundamental differential equation

$$
\frac{\partial c}{\partial t}=D \nabla^{2} c
$$

is solved with the boundary condition $c=0$ on the suriace of a sphere of radius $R$, this sphere representing the distance of closest approach of two particles. The simultaneous diffusion of both species of particles is taken eare of by taking $D$ to be the sum of the diffusion coefficients of the two species.

The solution to Eq. (1) with this boundary condition is

$$
c(r, t)=c_{o}\left[1-\frac{R}{r} e r f c \frac{r-R}{\sqrt{4} \overline{D t}}\right]
$$

where

$$
\operatorname{erfc} x=\frac{2}{\sqrt{\pi}} \int_{x}^{\infty} e^{-x^{2}} d z
$$

and $c_{o}$ is the initial concentration of the diffusing species, supposed uniform at $t=0$. The flux across the boundary sphere at $r=R$ is

$$
\begin{aligned}
\Phi & =4 \pi R^{2} D\left(\frac{\partial c}{\partial r}\right)_{r=R} \\
& =4 \pi D R c_{o}\left(1+\frac{R}{\sqrt{\pi D t}}\right) .
\end{aligned}
$$

* Present address: Polytechnic Institute of Brooklyn. In the colloid coagulation process, the time-dependent term is small and may be neglected.

The Smoluchowski theory was extended to ordinary bimolecular chemical reactions by Sveshnikoff $(2$ ) in connection with the quenching of fluorescence in liquid solution. Here there is competition between a first and a second order reaction. After photo-excitation of a fluorescent molecule, fluorescence may ensue or the molecule may be deactivated by collision with a quencher. The normal half-life of the excited state is of the order of $10^{-8}$ sec. and the quenching process is presumably diffusioncontrolled. A further modification of the original Smoluchowski theory by Sveshnikoff (2) was to assume that if only a fraction $\alpha$ of the collisions is effective, the only modification needed is to multiply the flux given by Eq. (5) by the factor $\alpha$.

The Smoluchowski theory was further developed by Umberger and LaMer (3) to include diffusion in a potential field as in the case of ions, following Debye (4). Use was made of the transient term in Eq. (5) because of the extremely short half life of the excited species. Following a suggestion from one of us (G. E. K.), Williamson and LaMer (5) abandoned the use of the transient term in the Smoluchowski equation, pointing out that there is but little difference between the Smoluchowski limiting flux and the encounter frequency using a quasi crystalline liquid model.

On closer examination of this theory, a number of disturbing points may be raised. Iirst, what is the nature of the postulated concentration gradient? Suppose that our two species of particle are $A$ and $B$, and that we consider the neighborhood of a certain A particle. Initially, this is surrounded by a uniform concentration of B. A gradient in this concentration can only be set up by the reaction of B particles with the A particle. But this reaction can only take place once. After such a reaction there is no longer an $A$ particle at the center, and the concentration gradient so formed secms to have lost its interest.

Second, the flux given by Eq. (j) becomes infinite at $t=0$. In most cases the flux falls to a reasonable value in an extremely small time, and the total amount of reaction predicted is finite, but nevertheless the singular rate at $t=0$ is a blemish on the theory, and, in the case of the quenching of fluorescence, where the important time interval is the first $10^{-8}$ sec. after excitation, the initial rate may be very significant.

'Third, when not every collision between particles is effective, the Sveshnikoff procedure of multiplying the flux by $\alpha$ is not self-consistent. From Eq. (2) we find that decrease of the total amount of the diffusing species from the amount present at $t=0$ is

$$
M=c_{0} \int_{R}^{\infty} 4 \pi r R \operatorname{erfc} \frac{r-R}{\sqrt{4 \bar{D} t}} d r
$$

The time derivative of this is

$$
\frac{d M}{d t}=4 \pi D R c_{o}\left(1+\frac{R}{\sqrt{\pi D t}}\right)
$$

'This is exactly equivalent to Eq. (5). But if the flux is modified by a factor $\alpha$, not equal to unity, the flux is no longer equal to the rate of decrease of the total amount of the diffusing species. It follows that Eq. (2) cannot correctly describe the concentration when $\alpha \neq 1$.

We attempt in this paper to remove these difficulties.

\section{'The Nature of the Coxchntration Gradient}

Let us first consider a system containing only a single $A$ particle and a single $B$ particle in a volume $V$, which may or may not be filled with solvent. By a well-known theorem (1) we may consider the A particle stationary and let the $B$ do all the moving. In such a system the concentration of $B$ is $1 / V$, in the sense that probability of finding the $\mathrm{B}$ particle in the volume element $d v$ is $(1 / V) d v$.

To study the behavior of this system, let us consider a large number $N$ of replicas, with the initial position of the $\mathrm{B}$ molecule distributed at random in the various replicas.

To any of these replica systems, Fick's law should apply, provided that $c$ is interpreted as the probability density of the position of the $B$ particle. But in the course of its motion, the $B$ particle may approach the A particle to the distance $R$, the reaction distance. At such a point, the reaction may or may not take place. If it does not, the $B$ particle will diffuse away. If it does, both the $A$ and $B$ particles are destroyed. However, instead of removing such systems from our assembly, it makes no difference if we assume instead that the $\perp$ and $B$ molecules are marked as "reacted," and allow the diffusion to continue. By this device we can keep the total number of replica systems constant.

Now suppose that we divide our volume $V$ into a large number of equal volume elements $\Delta v_{k}$. The state of any replica system can be specified by stating the volume element containing the $B$ particle, and whether or not reaction has taken place. The state of the whole assembly can be specified by giving a set of numbers $N_{k}$ and $M_{k}$, where $N_{k}$ is the number of systems in which the $\mathrm{B}$ particle is in $\Delta v_{k}$ and has not reacted, and $M_{k}$ is the number of systems in which the B particle is in $\Delta v_{k}$ and has reacted. By letting $\Delta v_{k}$ approach zero, we are led to two functions $n(x, y, z)$ and $m(x, y, z)$ such that $n(x, y, z) d x d y d z$ is the number of unreacted systems in which the $B$ particle lies in the volume element $d x d y d z$ located at $x, y, z$, and $m(x, y, z)$ is the number of reacted systems in which the $\mathrm{B}$ particle is in $d x d y d z$.

Except at the reaction surface, we may assume for the prescnt that the values of $n$ and $m$ change according to the diffusion equations 

$$
\begin{aligned}
& \frac{\partial n}{\partial t}=D \nabla^{2} n, \\
& \frac{\partial m}{\partial t}=D \nabla^{2} m .
\end{aligned}
$$

Further, since no systems leave the assembly, the sum $n+m$ must remain constant both in time and space. It follows, therefore, that whatever law we assume to govern the conversion of unreacted to reacted particles at the reaction surface, the gradients at this surface must satisfy

$$
\left(\frac{\partial n}{\partial r}\right)_{R}=-\left(\frac{\partial m}{\partial r}\right)_{k}
$$

A suitable boundary condition at $r=R$, together with a zero normal derivative of both $n$ and $m$ on the surface of the volume $V$, therefore, should enable both the functions $n$ and $m$ to be found as functions of time.

At any time, the function $n$ will be smaller near the A particle than elsewhere, while the function $m$ will be larger near the A particle than elsewhere. The integral of $n$ over the entire volume must steadily decrease, while that of $m$ must increase with time.

Now the fundamental question is: If we know that at time $t$ the A particle has not reacted, what is the probability of finding the B particle in the volume element $d x d y d z$ ? Note that this asks for an a posteriori probability, which must be distinguished carefully from the probability of finding the $\mathrm{B}$ particle in the volume element $d x d y d z$ if we do not know whether or not the $A$ particle has reacted. The fallacy of the argument that no concentration can be set up until the 1 molecule has reacted lies in the fact that the knowledge that an A molecule has existed for a length of time without reacting does affect the a posteriori probability.

By Bayes' theorem, the a posteriori probability of finding the B particle in the volume element $d x d y d z$, if we know that the $A$ particle has not reacted is

$$
\frac{n(x, y, z) d x d y d z}{\iint_{V} \int_{V} n(x, y, z) d x d y d z}
$$

This is correct whether the reaction with $A$ destroys the $B$ molecule (as in the case of an ordinary chemical reaction) or does not (as in the case of the quenching of fluorescence). On the other hand, if we do not know whether or not $A$ has reacted, the probability of finding the $B$ particle in $d x d y d z$ is

$$
\frac{1}{N} n(x, y, z) d x d y d z
$$

if the reaction destroys the $B$ particle, and

$$
\frac{1}{N}[n(x, y, z)+m(x, y, z)] d x d y d z
$$

if the reaction does not destroy the $B$ particle. This last expression reduces to $\frac{d x d y d z}{V}$, a constant, but is not ordinarily the probability we wish.

If we turn our attention to the A particle, the probability that it has not reacted at a given time is

$$
\frac{1}{N} \int_{0} \int_{v} n(x, y, z) d x d y d z
$$

We must distinguish between two reaction rates. The a priori probability at $t=0$ that the $A$ particle will react between $t$ and $t+d t$ is the simple derivative of $\mathrm{Fq}$. (14)

$$
-\frac{1}{N}\left[\iint_{V} \frac{\partial}{\partial t} n(x, y, z) d x d y d z\right] d t
$$

But if, at time $t$, we linow that i has not yet reacted, the a posteriori probability that $A$ will react in $d t$ is

$$
-\frac{\int^{\cdot} \int_{V}^{*} \frac{\partial}{\partial t} n(x, y, z) d x d y d z}{\iint_{V} n(x, y, z) d x d y d z} d t
$$

Replacing $\left.\frac{\partial n}{\partial t} b y\right) D \nabla^{2} n$ (Fq. 8), and application of the divergence theorem, the probabilities (15) and (16) can be expressed as surface integrals. Eq. (15) becomes

$$
-\frac{D}{N} d t \iint_{\text {Suriace }}^{\infty}(\nabla n) \cdot n d S
$$

and (16) becomes

$$
-D d t \cdot \frac{\iint_{\text {Suriace }}(\nabla n) \cdot n d S}{\iint_{V}^{*} n d x d y d z},
$$

where, in these equations, $n$ is the outward normal. But on the outer surface of $V, \nabla n=0$, so that these reduce to

$$
-+\frac{4 \pi R^{2} D d t}{N^{--}}\left(\frac{\partial n}{\partial r}\right)_{R}
$$

and

$$
-\frac{4 \pi R^{2} D d d t\left(\frac{\partial n}{\partial r}\right)_{R}}{\iint_{V} n d x d y d z}
$$

Obviously Eq. (19) is exactly the same as the result which would have been obtained if we had considered the rate of destruction of $\mathrm{B}$ particles in a single system consisting of one A particle at the origin surrounded by $N$ B particles diffusing and being destroyed at the surface of the $A$ particle.

We must now generalize these results by considering an A particle in a volume $V$ containing $M \mathrm{~B}$ particles. If we assume the $\mathrm{B}$ particles to be independent, the a priori probability that the A particle has not reacted with any particular $\mathrm{B}$ particle is still given by Eq. (14). Putting

$$
\frac{1}{N} \iiint_{V} n d x d y d z=1-\delta
$$

the probability that the A particle has not reacted with any $B$ molecule is

$$
Q=(1-\delta)^{M}
$$

which, if $M$ is large and $\delta$ is small but $M \delta$ is of the order of unity, then by a well-known theorem (6)

$$
Q=e^{-M \delta}
$$

The reaction rate $\Phi_{M}$ is now

$$
\begin{aligned}
\Phi_{M} & =-\frac{\partial}{\partial t} e^{-M \delta} \\
& =M e^{-M \delta} \frac{\partial \delta}{\partial t} \\
& =M e^{-M \delta} 4 \pi R^{2} \frac{I}{N}\left(\frac{\partial n}{\partial T}\right)_{R} .
\end{aligned}
$$

If $M \delta$ is small this is simply $M$ times the result of $F q$. (19)

$$
\Phi_{M}=4 \pi R^{2} \frac{D M}{N}\left(\frac{\partial n}{\partial r}\right)_{R}
$$

If we define a concentration $c$ and $c_{o}$ by

$$
c=\frac{M}{N} n, \quad c_{n}=\frac{M}{V}
$$

then $c$ obeys Fick's law, and the rate of reaction becomes

$$
\Phi_{M}=4 \pi R^{2} D\left(\frac{\partial c}{\partial r}\right)_{R}
$$

This is exactly the result used by Smoluchowski and Sveshnikoff as far as its mathematical interpretation is concerned, but its physical significance is different.

If $M \delta$ is not small, Eq. (25) cannot be regarded as correct but should be replaced by liq. (23). In this case we may still write

$$
\frac{\partial \ln Q}{\partial t}=-4 \pi R^{2} D\left(\frac{\partial c}{\partial r}\right)_{k}
$$

\section{BoUNDARY CONDITroxs}

In the above treatment, the boundary conditions at $r=R$ have been left unformulated. As pointed out in the introduction, the usual boundary condition, $c=0$ at $r=R$, cannot be correct if not every $B$ particle which reaches the reaction radius reacts. An obvious modification is to assume that the probability that a $B$ particle reacts with an A particle is proportional to the probability that the $\mathrm{B}$ particle lies between $r=R$ and $r=R+\Delta R$, where $\Delta R$ is a small distance. This is equivalent to the assumption

$$
\Phi_{M H}=k 4 \pi R^{2} c(l)
$$

where $l$ is of the nature of a specific reaction rate. Combining this with Fq. (25). we find the boundary condition

$$
c(R)=\gamma\left(\frac{\partial c}{\partial r}\right)_{R}
$$

with $\gamma=\frac{D}{\not{k}}$.

The solution of Eq. (1) with the boundary condition (28) is well known (7). The solution is

$c / c_{o}=1-\frac{R-\beta}{r}\left\{\operatorname{erfc} \frac{r-R}{\sqrt{4 \cdot D t}}\right.$

$$
\left.+e^{\left(D t / \beta^{2}\right) \div(r-R) / \beta} \operatorname{erfc}\left(\frac{\sqrt{D t}}{\beta}+\frac{r-R}{\sqrt{4 D t}}\right)\right\}
$$

where $\beta$ is related to $\gamma$ by

$$
\frac{1}{\beta}=\frac{1}{\gamma}+\frac{1}{R}
$$

The expression for $\Phi_{M}$ becomes

$$
\Phi_{M}=4 \pi I c_{o}\left[R-\beta+\frac{(R-\beta)^{2}}{\beta} e^{D t: \beta^{2}} \operatorname{erfc} \frac{\sqrt{D t}}{\beta}\right]
$$

There are a number of interesting points concerning this solution. At large values of $t$ we may use the asymptotic expression (8)

$$
\operatorname{erfc} x=\frac{1}{\sqrt{\pi}} e^{-x^{2}}\left(\frac{1}{x}-\frac{1}{2 x^{3}}+\frac{3}{4 x^{5}}-\cdots\right)
$$

to obtain

$$
\Phi_{M}=4 \pi D c_{o}(R-\beta)\left[1+\frac{R-\beta}{\sqrt{\pi D t}}\left(1-\frac{\beta^{2}}{2 D t}-\cdots\right)\right]
$$

We see that even at large times this never reduces to Eq. (5), but differs from it by the replacement of $R$ by $R-\beta$.

At small times, we find

$$
\Phi_{M}=4 \pi D c_{o}(R-\beta)\left[1+\frac{R-\beta}{\beta}\left(1-\frac{2}{\beta} \sqrt{\frac{D}{\pi}}-\cdots\right)\right]
$$

This remains finite even at $t=0$, the limiting value at $t=0$ being in fact $4 \pi R^{2} k c_{o}$.

There are two other important limiting cases, those for large and small values of the specific rate $k$. For small $k, \gamma$ is large and $\beta$ is nearly equal to $R$. In fact, we may put

$$
\beta=R-\frac{R^{2}}{D} k
$$

Correct to terms of order $k^{2}$ we then have

$$
\Phi_{M}=4 \pi R^{2} c_{o} h\left[1+\frac{R k}{D} e^{D t R^{2}} \operatorname{erf} c_{-} \frac{\sqrt{D} t}{R}\right] .
$$

As $k$ approaches 0 , we have a smooth transition to ordinary reaction kineties.

For large $k$, on the other hand, $\gamma$ and $\beta$ both become small, and are given by

$$
\beta=\gamma=\frac{D}{k}
$$

under these conditions, Eq. (32) again applies. Rearranging as a power series in $\beta$ gives

$$
\Phi_{M}=4 \pi D c_{o} R\left(1+\frac{R}{\sqrt{\pi D t}}\right)\left(1-\frac{\beta}{R}\right) \cdots
$$

This goes smoothly into the Smoluchowski form as $\beta$ approaches zero.

\section{Diffusion as a "JUmp" Process}

With the modification of the boundary condition given by Eq. (28), and the reinterpretation in terms of a posteriori probability, the objections stated at the beginning of this paper have been removed. However, it has long been realized that Fick's law is not an exact description of the diffusion process, but rather the limiting form approached by the equations describing the Brownian motion of the particles. This Brownian motion may be approximated by the assumption that the particles move by jumps of mean square length $\left\langle l^{2}\right\rangle$ with a jumping frequency $\nu$. The diffusion constant is then

$$
D=\frac{1}{6} \nu\left\langle l^{2}\right\rangle
$$

and Fick's law is obtained by letting $\left\langle l^{3}\right\rangle$ approach 0 and $\nu$ approach infinity in such a way that $D$ remains constant. The earlier work in this field is admirably summarized by Chandrasekhar (9).

In particular, it has been shown that, if the jumping particles are destroyed on reaching a surface, the distribution of the partieles approaches the solution of the diffusion equation with its boundary condition $c=0$ on the surface in question. We must now consider the question: If diffusion is represented by the "jump" picture, but with only a probability $p$ of being destroyed if they strike a boundary surface, is the boundary condition of Eq. (28) its proper limiting boundary condition?

To this end we shall consider only the case of a plane boundary, and a distribution of particles uniform in the directions parallel to this plane, so that the problem can be considered as one-dimensional. Taking $x$ as the coordinate perpendicular to the boundary plane, we shall suppose that the jump lengths are governed by a distribution function $\varphi(s)$, such that the probability that a given component of any jump lies between $s$ and $s+d s$ is $\varphi(s) d s$. The function $\varphi(s)$ must satisfy the equations:

$$
\begin{aligned}
& \int_{-\infty}^{\infty} \varphi(s) d s=1, \\
& \int_{-\infty}^{\infty} s \varphi(s) d s=0, \\
& \int_{-\infty}^{\infty} s^{2} \varphi(s) d s=\frac{1}{3}\left\langle l^{2}\right\rangle .
\end{aligned}
$$

If the concentration of particles is given by $c(x, t)$, and the jumps take place at random times, then $c(x, t)$ must satisfy the equation

$$
\frac{\partial c(x, t)}{\partial t}=-\nu c(x, t)+\nu \int_{-\infty}^{\infty} c(x-s, t) \varphi(s) d s
$$

at least in regions far from the boundary.

If the boundary is taken to be at $x=0$ (with the particles on the positive side) the rate at which particles strike the boundary is

$$
\Phi_{0}=\nu \int_{-\infty}^{0} \varphi(s) \int_{0}^{s} c(x, t) d x d s
$$

In order to be able to go to the limit of infinitesimal jumps at infinite frequency, let us introduce a parameter $\lambda$ in the following way. We keep the function $\varphi(s)$ unchanged, but reinterpret it by the assumption that $\varphi(s) d s$ is the probability of a jump component lying between $\lambda s$ and $\lambda(s+d s)$. We also reinterpret $\nu$, by taking the jump frequency to be $\nu / \lambda^{2}$. This makes the mean square jump length $\lambda^{2}\left\langle l^{2}\right\rangle$, but keeps $D$ the same. Eq. (41) now must be modified to

$$
\frac{\partial c(x, t)}{\partial t}=-\frac{\nu}{\lambda^{2}} c(x, t)+\frac{\nu}{\lambda^{2}} \int_{-\infty}^{\infty} c(x-\lambda s, t) \varphi(s) d s
$$

and $\mathrm{Eq} .(42)$ to

$$
\Phi_{11}=\frac{\nu}{\lambda^{2}} \int_{-\infty}^{0} \varphi(s) \int_{0}^{\lambda_{s}} c(x, t) d x d s
$$

The actual situation is given by $\lambda=1$, and by going to the limit $\lambda=\infty$ we should approach Fick's law.

By taking $\lambda$ small enough, we can make Eq. (43) apply at any $x>0$. If we expand $c(x-\lambda s, t)$ in a power series in $\lambda$

$$
c(x-\lambda s, t)=c(x, t)-\lambda s\left(\frac{\partial c}{\partial x}\right)_{x, t}+\frac{1}{2} \lambda^{2} s^{2}\left(\frac{\partial^{2} c}{\partial x^{2}}\right)_{x, t}-\cdots
$$

and substitute in Eq. (43), we obtain

$$
\begin{aligned}
\frac{\partial c(x, t)}{\partial t}=-\frac{\nu}{\lambda^{2}} c(x, t) & +\frac{\nu}{\lambda^{2}} c(x, t) \int_{-\infty}^{\infty} \varphi(s) d s \\
& -\frac{\nu}{\lambda}\left(\frac{\partial c}{\partial x}\right)_{x, t} \int_{-\infty}^{\infty} s \varphi(s) d s \\
& +\frac{1}{2} \nu\left(\frac{\partial^{2} c}{\partial x^{2}}\right)_{x, t} \int_{-\infty}^{\infty} s^{2} \varphi(s) d s \\
& -\frac{1}{6} \nu \lambda\left(\frac{\partial^{3} c}{\partial x^{3}}\right)_{x, t} \int_{-\infty}^{\infty} s^{3} \varphi(s) d s+\cdots \\
& +\frac{(-1)^{m}}{m !} \nu \lambda^{m-2}\left(\frac{\partial^{m} c}{\partial x^{m}}\right)_{x, t}^{\infty} \int_{-\infty}^{\infty} s^{m} \varphi(s) d s \\
& =D\left(\frac{\partial^{2} c}{\partial x^{2}}\right)_{x, t}+\sum_{m=1}^{\infty} \frac{(-\lambda)^{m}}{(m+2) !} \nu \mu_{m,+2}\left(\frac{\partial^{m+2} c}{\partial x^{m+2}}\right) \lambda^{m}
\end{aligned}
$$

where we have put

$$
\mu_{n_{i}}=\int_{-\infty}^{\infty} s^{m} \varphi(s) d s
$$

As $\lambda \rightarrow 0$ the series term approaches 0 , and Eq. (46) approaches Eq. (1) . In Eq. (44), expanding $c(x, t)$ about $x=0$

$$
\int_{0}^{\lambda s} c(x, t) d x=\lambda s c(0, t)+\frac{1}{2} \lambda^{2} s^{2}\left(\frac{\partial c}{\partial x}\right)_{0 . t}-\cdots
$$

and

$$
\begin{aligned}
& \Phi_{o}=\frac{\nu}{\lambda} c(0, t) \int_{-\infty}^{0} \varphi(s) d s+\frac{1}{2} \nu\left(\frac{\partial c}{\partial x}\right)_{0, t} \int_{-\infty}^{u} s \varphi(s) d s \\
& +\frac{1}{6} \nu \lambda\left(\frac{\partial^{2} c}{\partial x^{2}}\right)_{0 . t} \int_{-x}^{0} \varphi(s) d s+\cdots .
\end{aligned}
$$

Now

$$
\int_{-\infty}^{0} \varphi(s) d s=\frac{1}{2}
$$

and we can define

$$
\mu_{m}^{\prime}=2 \int_{-\infty}^{0} s^{m} \varphi(s) d s
$$

Hence

$$
\Phi_{o}=\frac{\nu}{2 \lambda} c(0, t)+{ }_{1}^{1} \nu \mu_{1}^{\prime}\left(\frac{\partial c}{\partial x}\right)_{0 . t}+\frac{1}{12} \nu \lambda \mu_{2}^{\prime}\left(\frac{\partial^{2} c}{\partial x^{2}}\right)_{0, t}+\cdots .
$$

As $\lambda \rightarrow 0, \Phi_{o}$ therefore becomes infinite. We are, however, interested in the reaction rate $p \Phi_{o}$, and we must give attention to the behavior of $p$ as $\lambda$ is varied. The inerease in the jumping frequency as $\lambda \rightarrow 0$ is one of our own making. If we assume $p$ to be independent of $\lambda$, then a particle situated near the reaction surface will have a rate of reaction which increases without limit if $\lambda$ is made to approach 0 . In order to obtain a reaction rate which approaches neither 0 nor $\propto$ as $\lambda \rightarrow 0$, we may take $p$ proportional to $\lambda$. We therefore assume

$$
p=p_{n} \lambda
$$

Then

$$
p \Phi_{o}=\frac{\nu p_{o}}{2} c(0, t)+\frac{p_{o}}{4} \nu \lambda \mu_{1}^{\prime}\left(\frac{\partial c}{\partial x}\right)_{0,1}+\cdots
$$

and now in the limit $\lambda \rightarrow 0$

$$
p \Phi_{o} \rightarrow \frac{\nu p_{o}}{2} c(0, t)
$$

Now for any positive $x$, however small, the fact that, in the limit $\lambda \rightarrow 0$, Eq. (1) applies, implies in turn that the leftward flux across the surface at. $x$ is

$$
\Phi_{x}=D\left(\frac{\partial c}{\partial x}\right)_{x, t}
$$

If we let $x$ approach 0 , this approaches

$$
\Phi^{\prime}=I\left(\frac{\partial c}{\partial x}\right)_{0,1} .
$$

But, sinee the particles are conserved, this requires $p \Phi_{0}=\Phi_{o}^{\prime}$ and

$$
\left.\nu \frac{p_{o}}{2} c(0, t)=1\right)\left(\frac{\partial c}{\partial x}\right)_{0 . t}
$$

This is essentially equivalent to the assumption of Eq. (28), and we have established the fact that the limiting form of the equations for "jump" diffusion lead to the modified boundary condition.

\section{Initial Renction Rate}

The above formulated boundary condition has been shown to be valid at large values of the time but involves a "reaction rate" constant $k$ which has not been definitely evaluated. In this section a power series solution will be developed for use at small times which enables evaluation of the constant $k$. 'The method, while perfectly general, will be discussed in the one-dimensional case for the sake of brevity. 'The concentration as a power series in $t$ is

$$
c=\sum_{k=0}^{\infty} c_{k} t^{k}
$$

which, substituted in Eq. (41) and equating the coefficients of corresponding powers of $t$, leads to the following recursion formula:

$$
(k+1) c_{k+1}(x)=-v c_{k}(x)+\nu \int_{-\infty}^{\infty} c_{k}(x-s) \varphi(s) d s
$$

Using the given initial condition and any specific function $\varphi(s)$, the coefficients in Fq. (59) may be calculated using Eq. (60).

Assuming that every particle entering the origin reacts, we have the rate equation

$$
\begin{aligned}
\Phi & =\frac{\partial}{\partial t} \int_{0}^{\infty} c d x \\
& =\sum_{k=1}^{\infty}(k+1) t^{k} \int_{0}^{\infty} c_{k \div 1} d x .
\end{aligned}
$$

The initial rate involves only the first term of the series and is readily found to be

$$
\Phi(O)=\frac{v c_{o} \mu_{1}^{\prime}}{z}
$$

where $\mu_{1}^{\prime}$ is defined as in Fiq. (51). The constant $k$ may then be evaluated using the one-dimensional analog of Eq. (27) and is

$$
k=\frac{\nu}{2} \mu_{1}^{\prime}
$$

For the case of incomplete reaction, the rate const int $k$ may be adjusted by multiplication by a suitable probability factor.

\section{CoNCLLSION}

The fundamental concepts of the Smoluchowski theory have been shown to be valid and to enter into all bimolecular reaction processes. $A$ modified solution to the diffusion equation has been obtained which avoids the singularity of the original Smoluchowski solution at the starting point of time. The modified solution is extended to the case where only a fraction of the encounters of the reactants brings about reaction and leads to limiting forms corresponding to diffusion control and activation energy control.

A detailed investigation of the applications of the above conclusion to a number of reactions which are wholly or partially diffusion-controlled is being started. These inchude quenching of fluorescence and free radical polymerizations.

\section{ReFFRENCES}

1. Smorccrowsк, M. v., Ann. Physik 48, 1103 (1915); Z. physik. Chem. 92, 129 (1917).

2. SveshNikoff, B., Actu Physicochim. U.R.S.S. 3, 257 (1935).

3. Lmberger, J. Q., and La.Mer, V. K., J. Am. Chem. Soc. 67, 1099 (1945).

t. Debye, P., Trans. Electrochem. Soc. 82, 265 (1942).

5. Williamson, B., And La Me.R, V. K., J. Am. Chem. Soc. 70, 717 (1948).

6. FrY, T. C., Probability and Its Engineering Lises, p. 107. Van Nostrand, New York, 1928.

7. CarsLa $;$ H. S., Mathematical Theory of the Conduction of Heat in Solids, p. 50 . Mac.Millan, London, 1921.

8. DWight, H. B., Tables of Integrals and Other Mathematical Data, p. 115. Macmillan, New York, 1934.

9. Chandrasekhar, S., Rev. Mod. Phys. 15, 1 (1943).
