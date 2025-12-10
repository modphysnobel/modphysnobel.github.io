[**Volume III: Waves**](./volume-III.md)

[**Previous: 9.3. Communication forms for describing scientific texts.**](./vol-III-chap-9-sect-2.md) 

***

## APPENDIX 9A. Representation of the superposition of a sine waves packet.

As in any wave description, the propagation velocity of the wave is $u=λν$, where $ν$ is its frequency and $λ$ its wavelength. According to Planck $E=hν$; however, de Broglie proposed that $p=mv=h/λ$ and Einstein that $E=mc^2$. Therefore $ν=E/h=mc^2/h$ and since $λ=h/mv$, $u=λν=(h/mv)(mc^2/h)=c^2/v$, implies that $u>>c$, which is contrary to Einstein's special theory of relativity.

According to the above we must have $u≠v$, therefore the matter wave represented by a pure sinusoidal function $ψ(x,t)$ is not useful for describing a  probability density $│ψ(x,t)│^2$ that makes possible the localization of the particle in some defined place at a given time. To correct this situation, it will be convenient to superimpose several sine waves to form a packet of waves with different frequencies, so that the packet can be localized and propagate over a finite region of space. 

Let us consider two waves of equal amplitude $A$ that differ slightly in the value of the wave number by an infinitesimal quantity $Δk$ and in the value of the angular frequency by $Δω$. If $y_1=Asin(kx−ωt)$ and $y_2=Asin[(k+Δk)x–(ω+Δω)t]$; their superposition will be $y=y_1+y_2=Asin(kx−ωt)+Asin[(k+Δk)x–(ω+Δω)t]$.

Let us consider two waves of equal amplitude $A$ that differ slightly in the value of the wave number by an infinitesimal quantity $Δk$ and in the value of the angular frequency by $Δω$. If $y_1=Asin(kx−ωt)$ and $y_2=Asin[(k+Δk)x–(ω+Δω)t]$; their superposition will be $y=y_1+y_2=Asin(kx−ωt)+Asin[(k+Δk)x–(ω+Δω)t]$.

The pulse or packet composed by the superposition of these two waves ($y=y_1+y_2$) travels with a velocity, the group velocity ($v_g$) defined as the limit of $Δω/Δk$, such that $v_g=dω/dk$. Group velocity is different from the characteristic velocities of each one of the component waves of the packet. These are the called phase velocity $v_f=ω/k$, defined in terms of the angular velocity $ω$ and the wave number $k=2π/λ$. Thus, for each of the waves in the packet, $v_{f1}=ω/k$ and $v_{f2}=(ω+Δω)/(k+Δk)$. Since it has been assumed that $Δω<<ω$ and that also $Δk<<k$, both phase velocities are almost equal; that is, $v_{f1}≈v_{f2}$.

If $C=(kx−ωt)$ and $D=[(k+Δk)x−(ω+Δω)t]$, the packet representing the superposition of waves $y_1$ and $y_2$ is expressed as $y=A[sinC+sinD]$. Considering the trigonometric identity $sinC+sinD=2sin[½(C+D)]cos[½(C−D)]$, we have the following relationships $C+D=[(2k+Δk)x−(2ω+Δω)t]$ and $C−D=[(−Δk)x−(−Δω)t]=−[(Δk)x−(Δω)t]$. Since $cos(−θ)=cos(θ)$, then $y=2Asin[(k+½Δk)x−(ω+½Δω)t]cos[(½Δk)x−(½Δω)t]$.

If we consider that $Δk<<k$ and $Δω<<ω$, then the superposition of two waves will be $y=2Asin[kx–ωt]cos[(½Δk)x–(½Δω)t]$. This package represents a sine wave of the type of $y_1$, with double amplitude and also modulated by the factor $cos[(½Δk)x−(½Δω)t]$.

In view of the previous results, it is convenient to review how group and phase velocities are now compared in the case of de Broglie matter waves and consider what happens with a packet formed by the superposition of matter waves.

In Section 9.1 we have considered that the sinusoidal function $A(x,t)≈sin[2πν(t−\frac{x}{w})]$ represents a wave with frequency $ν$, wavelength $λ$ and phase velocity $w=λν$. The following relations were obtained $ν=γν_0$ and $w=\frac{c^2}{v}$.

From $E=hν=mc^2=γm_0c^2=γhν_0$ it follows that $w=2πν=2π(γν_0)=γω_0$. As $w=\frac{c^2}{v}$ and $λ=w/ν=(\frac{c^2}{v})(\frac{1}{γν_0})$, then $k=\frac{2π}{λ}=2π(\frac{v(γν_0)}{c^2})=(\frac{γ}{c})(\frac{v}{c})(2πν_0)=(\frac{β}{c})(γw_0)$, where $β=\frac{v}{c}$ and $γ=\frac{1}{\sqrt{(1−β^2)}}$.

According to the definition of the phase velocity $v_f=\frac{w}{k}=\frac{γw_0}{(\frac{β}{c})(γw_0)}=\frac{c}{β}=\frac{c^2}{v}$.

On the other hand, the group velocity is $v_g=dω/dk=(dω/dβ)/(dk/dβ)$.

$\frac{dω}{dβ}=\frac{d(γω_0)}{dβ}=(ω_0)\frac{d(γ)}{dβ}$; $\frac{dγ}{dβ}=(−½)(−2β)[1−β^2]^{-\frac{3}{2}}=βγ^3$ then $\frac{dω}{dβ}=(ω_0)(βγ^3)$

$\frac{dk}{dβ}=\frac{d(βγω_0/c)}{dβ}=(\frac{ω_0}{c})\frac{d(βγ)}{dβ}=(\frac{ω_0}{c})[β\frac{d(γ)}{dβ}+γ\frac{d(β)}{dβ}]=(\frac{ω_0}{c})[β(βγ^3)+γ]=(\frac{γω_0}{c})[β^2γ^2+1]$

$[β^2γ^2+1]=\frac{β^2}{1−β^2}+1=\frac{(β^2+1−β^2)}{1−β^2}=\frac{1}{1−β^2}=γ^2$, hence $\frac{dk}{dβ}=(\frac{γω_0}{c})(γ^2)=\frac{γ^3ω_0}{c}$.

Summarizing $v_g=\frac{dω}{dk}=\frac{(\frac{dω}{dβ})}{(\frac{dk}{dβ})}=\frac{(ω_0)(βγ^3)}{(\frac{γ^3ω_0}{c})}=βc=(\frac{v}{c})(c)=v$. This means that the velocity of the group ($v_g$) is equal to the velocity of the particle $v$ and that the superposition of a packet of sine waves is an appropriate representation of the matter wave. It represents the localization amplitude of the particle; their corresponding localization probability is the square of that amplitude, which makes physical sense.

***

[**Next: 10.1.  The Michelson interferometer and the Michelson-Morley experiment.**](./vol-III-chap-10-sect-1.md)



