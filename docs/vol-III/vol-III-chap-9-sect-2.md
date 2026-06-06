[**Volume III: Waves**](https://modphysnobel.github.io/vol-III/volume-III/)

[**Previous: 9.1. Correspondence and uncertainty principles in Quantum Physics.**](https://modphysnobel.github.io/vol-III/vol-III-chap-9-sect-1/)
***

## 9.2. Correspondence and uncertainty principles in Quantum Physics.

The mathematical treatment of the concept of matter wave proposed by de Broglie requires that the motion of a quantum particle at a point $\vec{r}$ and at time $t$ must be described by a function of wave nature, the so-called wave function, which is represented as $ψ(\vec{r},t)$. This wave function has no physical meaning. It is the square of its absolute value, the probability density $P = │ψ(\vec{r},t)│^2$, that determines experimentally when and where the particle described by the wave function $ψ(\vec{r},t)$ is at position $\vec{r}(t)$ at time $t$.

According to Newtonian mechanics, the equation of motion for classical particles of mass $m$ and velocity $\vec{v}$ is $\vec{F} = d\vec{p}/dt$, where $\vec{p} = m\vec{v}$ is its linear momentum. Will this classical mechanics be appropriate to describe the movement of matter waves proposed by de Broglie? Let us see and suppose that $\vec{u}$ is the velocity with which such a wave propagates; this will corresponds to the velocity $v$ with which the particle described by the wave function $ψ(\vec{r},t)$ moves. If this movement is in the direction of the X-axis, the wave function will be $ψ(x,t)$.

As in any wave description, the propagation velocity of the wave is $u = λν$, where $ν$ is its frequency and $λ$ its wavelength. According to Planck $E = hν$; however, de Broglie proposed that  $p = mv = h/λ$ and Einstein  that $E = mc^2$. Therefore $ν = E/h = mc^2/h$ and since $λ = h/mv$, $u = λν = (h/mv)(mc^2/h) = c^2/v$, implies that $u >>c$, which is contrary to Einstein's special theory of relativity.       

According to the above we must have $u ≠ v$, therefore the matter wave represented by a pure sinusoidal function $ψ(x,t)$, which is not located at any point in space, cannot be used to describe a probability density $│ψ (x,t)│^2$ that makes possible the localization of the particle in some defined place at a given time. 

To correct previous situation, it will be convenient to superimpose several sine waves to form a packet of waves with different frequencies, so that the packet can be localized and propagate over a finite region of space. Let us consider two waves of equal amplitude $A$ that differ slightly in the value of the wave number by an infinitesimal quantity $Δk$ and in the value of the angular frequency by $Δω$. If $y_1 = Asin(kx - ωt)$ and $y_2 = Asin[(k+Δk)x – (ω+Δω)t]$; their superposition will be $y = y_1 + y_2 = Asin(kx - ωt) + Asin[(k+Δk)x – (ω+Δω)t]$. 	       	   

The pulse or packet composed by the superposition of these two waves ($y = y_1 + y_2$) travels with a velocity, the group velocity ($v_g$) defined as the limit of $Δω/Δk$, such that $v_g = dω/dk$. Group velocity is different from the characteristic velocities of each one of the component waves of the packet. These are the called phase velocity $v_f = ω/k$, defined in terms of the angular velocity $ω$ and the wave number $k = 2π/λ$. Thus, for each of the waves in the packet, $v_{f1} = ω/k$ and $v_{f2} = (ω+Δω)/(k+Δk)$. Since it has been assumed that $Δω << ω$ and that also $Δk << k$, both phase velocities are almost equal; that is, $v_{f1} ≈ v_{f2}$. 
                  
If $C = (kx-ωt)$ and $D = [(k+Δk)x - (ω+Δω)t]$, the packet representing the superposition of waves $y_1$ and $y_2$ is expressed as $y =  A[sinC + sinD]$. Considering the trigonometric identity $sinC + sinD = 2sin[½(C+D)]cos[½(C-D)]$, we have the following relationships $C + D = [(2k+Δk)x - (2ω+Δω)t ]$ and $C - D = [(-Δk)x - (-Δω)t] = - [(Δk)x - (Δω)t]$. Since $cos(-θ) = cos(θ)$, then $y = 2Asin[(k+½Δk)x - (ω+½Δω)t]cos[(½Δk)x - (½Δω)t]$.

If we consider that $Δk << k$ and $Δω << ω$, then the superposition of two waves will be $y = 2Asin[kx – ωt]cos[(½Δk)x – (½Δω)t]$. This package represents a sine wave of the type of $y_1$, with double amplitude and also modulated by the factor $cos[(½Δk)x - (½Δω)t]$.

In view of the previous results, it is convenient to review how group and phase velocities are now compared in the case of de Broglie matter waves and consider what happens with a packet formed by the superposition of matter waves.

In Section 9.1 we have considered that the sinusoidal function $A(x,t)≈sin[2πν(t- x/w)]$ represents a wave with frequency $ν$, wavelength $λ$ and phase velocity $w = λν$. The following relations were obtained $ν= γν_0$ and $w=  c^2/v$.

From $E = hν = mc^2 = γm_0c^2 = γhν_0$ it follows that $w = 2πν = 2π(γν_0) = γω_0$. As  $w=  \frac{c^2}{v}$ and $λ = w/ ν = (\frac{c^2}{v})(\frac{1}{γν_0})$, then $k= \frac{2π}{λ}= 2π(\frac{v(γν_0 )}{c^2})=(\frac{γ}{c})(\frac{v}{c})(2πν_0 )= (\frac{β}{c})(γw_0 )$, where $β= \frac{v}{c}$  and $γ=\frac{1}{\sqrt{(1- β^2 )}}$.

According to the definition of the phase velocity $v_f= \frac{w}{k}=\frac{γw_0}{(\frac{β}{c})(γw_0 )} = \frac{c}{β}= \frac{c^2}{v}$. 

On the other hand, the group velocity is $v_g = dω/dk = (dω/dβ)/(dk/dβ)$.

$\frac{dω}{dβ}=\frac{d(γω_0 )}{dβ}= (ω_0)\frac{d(γ)}{dβ}$; $\frac{dγ}{dβ}= (-½)(-2β)[1- β^2 ]^{-3/2}=βγ^3$  then  $\frac{dω}{dβ}  = (ω_0)(βγ^3)$ 

$\frac{dk}{dβ}=\frac{d(βγω_0/c)}{dβ}=(\frac{ω_0}{c})  \frac{d(βγ)}{dβ}= (\frac{ω_0}{c})[β \frac{d(γ)}{dβ}+ γ \frac{d(β)}{dβ}]= (\frac{ω_0}{c})[β(βγ^3)+ γ]=(\frac{γω_0}{c})[β^2 γ^2+ 1]$

$[β^2 γ^2+ 1]=  \frac{β^2}{1- β^2}+ 1=  \frac{(β^2+ 1- β^2 )}{1- β^2 }  =  \frac{1}{1- β^2 }= γ^2$,  hence $\frac{dk}{dβ}= (\frac{γω_0}{c})(γ^2 )=  \frac{γ^3 ω_0}{c}$.  

Summarizing $v_g=  \frac{dω}{dk}=  \frac{(\frac{dω}{dβ})}{(\frac{dk}{dβ}) }  =  \frac{(ω_0)(βγ^3)}{(\frac{γ^3 ω_0}{c} )}=βc= (\frac{v}{c})(c)=v$. This means that the velocity of the group ($v_g$) is equal to the velocity of the particle $v$ and that the superposition of a packet of sine waves is an appropriate representation of the matter wave. It represents the localization amplitude of the particle; their corresponding localization probability is the square of that amplitude, which makes physical sense.

Classically, the concepts of corpuscle and wave are well defined; they are represented mathematically in precise ways. A corpuscle has a shape circumscribed to a finite and small region of space where its position at any time can be located, so that its trajectory is observable and measurable. This does not happen with photons.

Classically a wave is a continuous disturbance "scattered" in a certain region of space. In fact, a pure sine wave propagates occupying all space: it comes from minus infinity and goes towards plus infinity. Such a wave propagates with a certain velocity in a medium that is material for mechanical waves but that does not require ether for electromagnetic waves. Such propagations are described in terms of wave equations and their solutions allow us to explain interference and diffraction. This does not happen when electrons are considered as punctual corpuscles. Nevertheless, their matter waves are diffracted. Furthermore, an appropriate representation of matter waves requires to superimpose several sine waves to form a packet of waves with different frequencies.

By accepting that in quantum physics there is no sharp separation between the classical conceptualizations of waves and corpuscles, we are faced with two disturbing circumstances: (1) when light interacts with matter it loses its wave characteristics related to its propagation and quantized impact and (2) when different components of matter (like particles) interact with radiation, they lose their corpuscular properties and show diffraction. Therefore, what kind of motion equation will satisfy the matter waves proposed by de Broglie?


### Does light behave as a wave or a corpuscle?

By considering only the magnitude of vectors, the motion of a particle with linear momentum $p = mv$ is described by Newton's second law $F = dp/dt$ and if the mass $m$ is constant, $F = m[d^2r(t)/dt^2]$. When the expression of the law of the force $F$ acting on the particle is known, solving the equation of motion will indicate how the position evolves in time $r(t)$ and what kind of trajectory is obtained. Furthermore, the sinusoidal function $y(x,t) = Asin(kx – ωt)$ is a solution of the equation of motion of a harmonic oscillator with frequency $ω = 2πν$, this function satisfies the corresponding wave equation $d^2y/dt^2 = - (ω^2)y$. 

Judging by the differences in the mathematical form of the two previous equations of motion, their respective solutions will represent quite different physical entities. Under such conditions, will it be possible to derive the dynamics of quantum particles from the laws of wave propagation? What must be the appropriate equation of motion of matter waves characterized by the wave functions $ψ(r,t)$ ? 

The answer to the last question was given in 1926 by [Erwin Rudolf Josef Alexander Schrödinger](https://en.wikipedia.org/wiki/Erwin_Schr%C3%B6dinger) (1887 - 1961). To get an idea of what Schrödinger's equation means, it is convenient to refer to Fermat's and Hamilton's principles (see Section 8.1).

The principle of minimum time or [Fermat's principle](https://en.wikipedia.org/wiki/Fermat%27s_principle) indicates that: "of all the possible paths that light can take to get from one point to another, it takes the path that requires *the shortest time*." [Pierre de Fermat](https://en.wikipedia.org/wiki/Pierre_de_Fermat) (1601 - 1665) developed this principle around 1650 to explain light propagation as well as reflection and refraction phenomena. He considered that the front of a light wave spends a minimum time to move in different media. About 1744 [Louis Moreau de Maupertuis](https://en.wikipedia.org/wiki/Pierre_Louis_Maupertuis) (1698 - 1759) formulated a variational principle of least action and indicated that the perfection of the universe required a principle of economic operation to avoid unnecessary expenditure of energy.

Years later, [William Rowan Hamilton](https://en.wikipedia.org/wiki/William_Rowan_Hamilton) (1805 - 1865) proposed that the path followed by a traveling ray of light is minimal with respect to time for wave theory of light or with respect to action for the corpuscular theory. Hamilton demonstrated in 1826 that the study about optical rays can be made in terms of a characteristic function, the action, satisfying a [principle of least action](https://en.wikipedia.org/wiki/Action_principles). For conservative systems such principle corresponds to Newton's second law. (A more formal discussion of Fermat's and Hamilton's principles has been considered in Section 8.1.)

To develop his wave equation, Schrödinger considered that if wave optics tends as a limiting case to geometric optics, which can be derived from the application of the variational principle of minimum time (Fermat´s principle), in the new wave mechanics Hamilton's principle of least action would be the analogue of a "geometric mechanics" describing the motion of quantum particles like electrons. 

Remember that matter waves associated to electrons have wave wavelengths of the order of the Bohr´s radio $λ≈ a_0  = 10^{-10}  m=1 Å$. Then, why a truck does not diffract as a quantum particle? Because their corresponding wavelength  $λ_{truck}≪a_0$. If a truck has a mass $m=3,600 kg$ and a velocity $v=100 km/hr$, then its linear momentum $p=mv=$(3,600 kg)(100 km/hr)$= 10^5$ kg m/s; the corresponding wavelength  $λ=  \frac{h}{p}=  \frac{6.63 \times 10^{-34}  J.s}{10^5 kg m/s}= 6.63 \times 10^{-39} m$, which is practically null and undetectable by conventional physical media. 

### Principles of correspondence and uncertainty.

In the quantum world, a wave-particle duality is manifested, causality is not strict, nor determinism is absolute. The representations and interpretations of microscopic entities contrast strongly with what is proposed in classical physics. In the quantum world, new principles apply, such as the Bohr´s correspondence principle and Heisenberg's uncertainty principle. 

Correspondence principle indicates that classical results are limiting cases of quantum results when the value of [Planck´s constant](https://en.wikipedia.org/wiki/Planck_constant) is strictly negligeable. Indeterminacy or uncertainty principle refers to an inequality satisfied when the product of the uncertainties of two physical quantities is equal or lesser than *h*. For instance: the lack of precision in the measurement of the position of a moving particle multiplied by the lack of precision in the measurement of the component of the linear momentum in the same direction of the displacement must be equal or lesser than *h*. Both measurements must simultaneously be made on the same particle, in the same place and at the same time.
	
As a sort of reconciliation between classical physics and the revolutionary changes of the new physics, in 1923 [Niels Bohr](https://en.wikipedia.org/wiki/Niels_Bohr) proposed a coherent framework for the objective description of nature, his **correspondence principle:** *"Any new theory in physics must be reduced to the corresponding classical theory, when the new theory is applied to the special situation in which the classical theory is valid”*.

In the quantum world, the value of Planck's constant is significant; however, when quantum approaches and results are extrapolated when *h* tends towards zero, the predictions of classical physics must be recovered. For example, if we apply the Bohr shell model and calculate the value of the transition frequency between stationary orbits for very large values of the principal quantum number n, the frequency predicted by Bohr should correspond to the radiation frequency of electromagnetic waves as predicted by classical electromagnetism.

Let us consider an electron of charge $-q$ in a circular orbit of radius $r$ around a proton of charge $+q$. Their Coulomb interaction is $F_C = k/r^2$, with potential energy $E_p = -k/r$, $k = q^2$. The electronic orbital movement is due to the action of a mechanical force $F_M = (mv^2)/r$, where $v$ is the velocity of the electron. If the magnitudes of these forces are equal $F_C = F_M$, then $k/r^2 = (mv^2)/r$,  $E_c = ½mv^2 = ½k/r$ and $E = E_c + E_p = ½k/r -k/r = -½k/r$. As the angular velocity $ω = 2πν$ and $v = ωr$, then $E_c = ½mv^2 = ½m(ωr)^2 = ½(m)(2 π ν)^2[r^2]$. Nevertheless $E_C = ½k/r$, then the frequency of oscillation is $ν = (1/2π)[k/(mr^3)]^{½}$.

Up to now everything has been a classic treatment. Using the value obtained by Bohr $r = a_0(n^2)$, where $a_0 = [(ђ^2)/(mk)]$, then the frequency of an electronic orbit will be $ν_{class} = (1/2π)[k/m]^{½}[r^3]^{-½} = (1/2π)[k/m]^{½}[(a_0^3)(n^6)]^{-½} = (1/2π)[k/m]^{1/2} [(mk / ђ^2)]^{3/2} (n^{-3}) = (1/2π)[(mk^2)/(ђ)^3](n^{-3})$.	

Besides, according to Bohr the energy of a stationary state is $E_n = -R/(n^2)$, where the Rydberg constant is $R = (mk^2)/[2(ђ)^2]$. Furthermore, the transition between the states $E_i$ and $E_f$ is $hν = E_i – E_f = R[1/(n_f)^2 - 1/(n_i)^2]$. If such states are highly excited then $n_i - n_f = Δn$ and it can be approximated that $n_i + n_f = n_i + (n_i - Δn) = 2n_i – Δn ≈ 2n$.  Considering that $n_i ≈ n_f ≈ n$ then $[1/(n_f)^2 – 1/(n_i)^2] = [(n_i)^2 -(n_f)^2]/[(n_i)^2(n_f)^2]  = [(n_i -n_f)(n_i +n_f)]/[n^4]  ≈ (2Δn)/(n^3)$. If now such states correspond to neighboring levels where $Δn = 1$, for very large values of $n$ Bohr's theory prediction for the quantized energies of the radiation is $hν = R[1/(n_f)^2 - 1/(n_i)^2]$ which corresponds to $hν = ((mk^2)/[2(ђ)^2])((2Δn)/(n^3))$. When $Δn = 1$ the frequency for the quantum conditions is $ν_{quant} = [(mk^2)]/[h(ђ)^2][n^{-3}]$. Considering $ђ = h/(2π)$ the expressions for $ν_{class}$ and $ν_{quant}$ exactly coincide.

The uncertainty principle is incompatible to classical physics because in that world there is no impediment to simultaneously describe the position and velocity of a particle. However, in the quantum world, the representation of waves that occupy large regions in space does not coincide with the representation that corresponds to well-located corpuscles in space. Suppose that $Δx$ and $Δp_x$ designate, respectively, the indeterminacies in the measurements of the position and of the component of the linear momentum ($p_x = mv_x$) of a particle in the direction of the X axis. Both measurements are made at the same time and for the same particle. Classically, the value of $Δx$ does not depend at all on that of $Δp_x$, but quantumly the so-called Heisenberg **indeterminacy or uncertainty principle** proposed by [Werner Heisenberg](https://en.wikipedia.org/wiki/Werner_Heisenberg) must be satisfied. This principle establishes that the product of such uncertainties is of the order of Planck's constant ($h ≈ 6.6 \times 10^{-34} Js$). This principle can be represented as follows: $Δx Δp_x  ≥ h/(2π)$.

Next section 11.3 includes a hypothetical dialogue between Bohr and Heisenberg about correspondence and uncertainty principles; it has been prepared by selecting some excerpts of their respective Nobel Lectures.

WORK: “The discovery of the electron and radioactivity in the late 19th century led to different models being proposed for the atom’s structure. In 1913, Niels Bohr proposed a theory for the hydrogen atom, based on quantum theory that some physical quantities only take discrete values. Electrons move around a nucleus, but only in prescribed orbits, and If electrons jump to a lower-energy orbit, the difference is sent out as radiation. Bohr’s model explained why atoms only emit light of fixed wavelengths, and later incorporated the theories on light quanta.”

MLA style: Niels Bohr – Facts. NobelPrize.org. Nobel Prize Outreach AB 2024. Wed. 5 Jun 2024. <https://www.nobelprize.org/prizes/physics/1922/bohr/facts/>

NOBEL LECTURE: *The Structure of the Atom* by Bohr.

MLA style: Niels Bohr – Nobel Lecture. NobelPrize.org. Nobel Prize Outreach AB 2023. Tue. 21 Feb 2023. https://www.nobelprize.org/prizes/physics/1922/bohr/lecture/

WORK: “In Niels Bohr’s theory of the atom, electrons absorb and emit radiation of fixed wavelengths when jumping between fixed orbits around a nucleus. The theory provided a good description of the spectrum created by the hydrogen atom, but needed to be developed to suit more complicated atoms and molecules. In 1925, Werner Heisenberg formulated a type of quantum mechanics based on matrices. In 1927 he proposed the “uncertainty relation”, setting limits for how precisely the position and velocity of a particle can be simultaneously determined.”

MLA style: Werner Heisenberg – Facts. NobelPrize.org. Nobel Prize Outreach AB 2024. Wed. 5 Jun 2024. <https://www.nobelprize.org/prizes/physics/1932/heisenberg/facts/>

NOBEL LECTURE: *The Development of Quantum Mechanics* by Heisenberg.
    
MLA style: Werner Heisenberg – Nobel Lecture. NobelPrize.org. Nobel Prize Outreach AB 2023. Tue. 21 Feb 2023. https://www.nobelprize.org/prizes/physics/1932/heisenberg/lecture/


***
[**Next: 9.3. Communication forms for describing scientific texts.**](https://modphysnobel.github.io/vol-III/vol-III-chap-9-sect-3/)
