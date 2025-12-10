
[**Volume II: Energy**](./volume-II.md)

[**Previous: 5.1.  Kinetic theory of gases and Thermodynamics.**](./vol-II-chap-5-sect-1.md) 

***

## 5.2.  The photon as a quantum of energy.

### Quantization in classical Physics.

In classical physics, the spectrum of values of the variables that are measured generally corresponds to a continuum. For instance, when we are walking in a ramp there are no forbidden places for the feet (there is no restriction on the height h), unlike when we are walking in a staircase the foot can only be placed on the steps (Figure 5.2)


<p align="center" width="100%">
    <img width="300" src="https://github.com/modphysnobel/modphysnobel.github.io/blob/main/docs/vol-II/figs/chap-5-sect-2-fig1.png?raw=true"> 
</p>

<center>
(Images credit: adaptation by the authors of the image taken from CC Wikimedia Commons.)
</center>


**Figure 5.2.** Some positions of the feet are forbidden in a staircase but not in a ramp.

However, an important case where quantization does occur is that of the standing waves that are observed when a string of length L fixed at its ends is made to vibrate (Figure 5.3). Under these conditions, certain modes of vibration of the string are produced that do not change with time, that is, they remain stationary.

<p align="center" width="100%">
    <img width="300" src="https://github.com/modphysnobel/modphysnobel.github.io/blob/main/docs/vol-II/figs/chap-5-sect-2-fig2.JPG?raw=true"> 
</p>
	
<center>
(Images credit: adaptation by the authors of the image taken from CC Wikimedia Commons.)
</center>

**Figure 5.3.** First four modes of vibration of a standing wave.

When the wave reaches one of the fixed ends, it is reflected and returns reversing the direction of its propagation and the direction of vibration in the vertical sense, which is perpendicular to the direction of propagation of the wave. Consequently, interference occurs between the incident wave and the reflected wave. If, after each reflection, the interference between the incident and reflected waves is constructive, it is because the crests of the wave add to each other and the same occurs with the troughs. 

Previous pattern of vibration does not change with time if the following condition is satisfied: the distance between the fixed ends of the string (L) is a half-integer multiple of the corresponding wavelength (λ). This means that $L = n (λ/2)$, where n is a positive integer. The existence of a quantum number n determines the conditions for the production of the standing wave whose vibration modes are quantized because such a quantum number n can have only discrete values.

### Quantization of energy in the black body radiation.

The conceptual and experimental discrepancy between continuous and discrete values of physical variables started in modern times when modern physics was born on December 14, 1900. That day Max Planck presented to the German Physical Society a work describing his hypothesis of the quantization of energy and introduced the constant $h = 6.63 \times 10^{-34}$ J.s, which is measured in units of action (energy per time) and which now bears his name. Below, we present in four stages an elementary analysis of Planck's revolutionary contribution to solve a critical problem: energy quantization in the black body radiation.

STAGE 1: *Description in a common daily language of the basic notions and conceptual relationships required to interpret and solve a given problem. Main antecedents of the problem are described, and its difficulties are considered.*

A black body is a physical object that does not lose energy by reflection or transmission, only by emission; that is, it absorbs all the energy that falls on it. Since it does not reflect the incident light, it appears to the observer as something dark (black). Depending on the temperatures of the physical objects, they emit radiation visible to the human eye (the color of the object) or in other regions of the electromagnetic spectrum such as infrared when the object has been heated. 

A hollow opaque object functions as a blackbody when its interior walls are painted black and a small hole is drilled into it. All radiation that enters through the hole is absorbed and hardly leaves it. If this hollow cavity is placed inside an oven with controllable temperature, the intensity of the electromagnetic radiation emitted when the cavity is heated can be measured by an external optical device. In this case, for different furnace temperatures the intensity of the radiation measured with a spectrometer is a function of its wavelength, (Figure 5.4).

<div style="text-align:center;">
	<table width="100%">
	<tr>
		<th width="50%">
	<img src="https://upload.wikimedia.org/wikipedia/commons/3/3e/Radiaci%C3%B3n_y_efecto_fotoel%C3%A9ctrico_1.jpg" width=300 align=center> 
		</th>
		<th width="50%">
	<img src="https://upload.wikimedia.org/wikipedia/commons/c/c8/Black-body_radiation_vs_wavelength.png" width=300 align=center> 
		</th>
	</tr>
	</table>
	</div> 

<center>
(Images credit: CC Wikimedia Commons)
</center>

**Figure 5.4.** Diagram of a black body (left) and intensity of the experimental spectrum as a function of the wavelength, at different temperatures (right).

In 1879 [Josef Stefan](https://en.wikipedia.org/wiki/Josef_Stefan) (1835-1893) inferred from his observations that the rate at which energy is radiated from a heating body should be proportional to the fourth power of its absolute temperature. Later, in 1884, an assistant of Stefan's at the University of Vienna, Ludwig Edward Boltzmann (1844-1906), calculated the speed of the particles of a gas to obtain the radiation pressure exerted by a piston on the molecules of the gas contained inside a cylinder. From these two contributions, an inference from experimental data and a theoretical derivation, the Stefan-Boltzmann law resulted: when the contributions of all wavelengths are added the total power radiated per unit area of the cavity opening is $I(T) = σT^4$, where σ is Stefan's constant.

***

STAGE 2: *Contextualized explanation in a technical language of the assumptions and approximations required to characterize the scenario, the objects and the agents that are described in the problem statement. An idea of what the solution to the problem should be is included.*

According to experimental results, the maximum intensity of the radiation emitted by the black body occurs for a $λ_{max}$ and its position shifts to the left (towards blue) as the temperature increases. This was specified by [Wilhelm Carl Werner Otto Fritz Franz Wien](https://en.wikipedia.org/wiki/Wilhelm_Wien) (1864-1928) when in 1893 he proposed the relation $λ_{max}T = a$, where $a$ is a constant. This relationship is known as Wien's displacement law (Figure 5.5). 
	
<p align="center">
	<img src="https://upload.wikimedia.org/wikipedia/commons/2/22/Blackbody_Spectrum.PNG" width=480 align=center>
	</p>

<center>
(Images credit: CC Wikimedia Commons)
</center>

**Figure 5.5.** Wien's displacement law that shows how the color of the radiation changes with the temperature of the emitting source for different wavelengths (λ).

Wien also proposed a function to describe the spectral energy density (u), or energy per unit of volume per unit of frequency of radiation within the blackbody cavity: $u(f,T) = α[(f)^3exp(-βf/T)]$, where f is the frequency, T is the temperature, and α and β are constants. This result is called Wien's power law and is considered in Wien´s Physics Nobel Lecture (section 5.3 and Appendix 5.1). 


WORK: “When a completely dark body is heated, it emits visible light and other electromagnetic radiation. The spectrum of the radiation is entirely dependent on the temperature of the body and not its composition. In 1893 Wilhelm Wien (1864-1928) formulated his displacement law, which indicates at which wavelength the radiation is most intense at a certain temperature. He subsequently also formulated a law indicating how the radiation spectrum varies as temperature changes. However, this does not apply to long wavelengths, and in 1900 Max Planck formulated a law that conforms better.”

MLA style: Wilhelm Wien – Facts. NobelPrize.org. Nobel Prize Outreach AB 2024. Tue. 16 Jan 2024. https://www.nobelprize.org/prizes/physics/1911/wien/facts/

NOBEL LECTURE: *On the Laws of Thermal Radiation* by Wien.

MLA style: Wilhelm Wien – Nobel Lecture. NobelPrize.org. Nobel Prize Outreach AB 2023. Sun. 24 Sep 2023. https://www.nobelprize.org/prizes/physics/1911/wien/lecture/	

Meanwhile, the British physicist [John William Strutt, third Baron Rayleigh](https://en.wikipedia.org/wiki/John_William_Strutt,_3rd_Baron_Rayleigh) (1842 – 1919), obtained in June 1900 a formula to calculate the number of free electromagnetic vibration modes per unit volume in the cavity and per unit wavelength. Later, the British astronomer [Sir James Hopwood Jeans](https://en.wikipedia.org/wiki/James_Jeans) (1877 – 1946) made some corrections, obtaining the expression $uλ=8πkT/λ$ for the energy density per unit interval of wavelength, later called the Rayleigh – Jeans law. This law was consistent with experiments for low infrared frequencies, where Wien's law failed, but for short wavelengths or high frequencies it predicted infinite emission in the ultraviolet, termed the “ultraviolet catastrophe”. 

Later, in an attempt to obtain a general equation, Thiesen, Lummer, Jahnke and Prigshein proposed in the early 1900s a general equation in terms of constants and the parameters $μ$ and $η$; Wien's law was obtained for $μ = 5$ and $η = 1$, while Rayleigh-Jeans law resulted when $μ = 4$, $η = 1$ and $b = 0$. Table I summarizes the expressions of the three laws described above, as well as the expression proposed by Thiesen, Lummer, Jahnke and Prigshein as a function of the parameters $μ$, $η$ and $b$. This Table also includes Planck's law which solve the problem (Figure 5.6).

<p align="center" width="100%">
    <img width="600" src="https://github.com/modphysnobel/modphysnobel.github.io/blob/main/docs/vol-II/figs/5.1.jpg?raw=true"> 
</p>

<p align="center">
	<img src="https://upload.wikimedia.org/wikipedia/commons/7/72/RWP-comparison.svg" width=480 align=center>
	</p>

<center>
(Images credit: CC Wikimedia Commons)
</center>

**Figure 5.6.** Radiation intensity as a function of frequency; comparison on logarithmic scales between the predictions of the Rayleigh-Jeans (red), Wien (blue) and Planck (green) laws.

In the limit of $λ→0$ Planck's law leads to Wien's law when $exp(hc/(kTλ)) >> 1$; while on the limit $λ→∞$ the Rayleigh-Jeans law is obtained when $hc/(kTλ) << 1$ and we use the approximation $exp(x) = 1 + x$.

***

STAGE 3: *Description in a formal language corresponding to the reasoning process that leads to the solution The use of diagrams, schemes and other iconic elements is proposed.* 

The possible reasoning followed by [Planck](https://en.wikipedia.org/wiki/Max_Planck) is described below:

**1. Incompatibility between experiments and theories:** Consider how the experimental values obtained by spectroscopists are compatible with theoretical predictions only at low frequencies (Wien's law) and at high frequencies ([Rayleigh-Jeans law](https://en.wikipedia.org/wiki/Rayleigh%E2%80%93Jeans_law)).

**2. Model of the black body:** For each value of the wavelength the intensity of the radiation emitted by the black body only depends on the temperature and is independent of the material of the cavity. Remember that at the beginning of the last century the physical existence of the atom was not yet accepted, nor was there a model of its structure.

**3. Model of the interaction between the radiation and the walls of the black body cavity:** Assumption that the cavity is constituted by a set of oscillators, represented by their characteristic frequency $f$, all of which are in interaction with the electromagnetic radiation that reaches the cavity.

**4. Quantum structure of the oscillators:** If the oscillators are oscillating electric dipoles, classically their vibration frequencies can correspond to emissions or absorptions in a continuum of frequencies. This imperative of classical physics will have to be radically modified when the energy quantum hypothesis is introduced.

**5. Boltzmann calculation:** The set of oscillators represents parts of the cavity in thermal equilibrium with the electromagnetic radiation contained in the cavity. To account for the energy of these oscillators, the statistical method followed by Boltzmann is applied. He calculated the behavior of an ideal gas composed of many molecules moving rapidly and disorderly inside a container, frequently colliding with each other and with the walls of the container.

**6. Discrete exchange of energy:** The exchange of energies between the oscillators that constitute the cavity and the electromagnetic radiation contained in it does **NOT** correspond to a continuum of values, but rather, were consistent with Planck hypothesis ($E = nhf$): the quantum of radiation must be an integer multiple ($n$) of the frequency ($f$).

***

STAGE 4: Consideration of the changes introduced by Planck's solution according to what characterizes [scientific revolutions](https://en.wikipedia.org/wiki/Scientific_Revolution) (Kuhn, 1962):
	
(1)	*Changes in meanings of basic terms and the way words and phrases relate to nature.*

In his initial proposal, Planck spoke of "resonators", later he would speak of oscillators. At that time, resonators were mainly identified with acoustics, since electromagnetic resonators had not yet been found. While resonators respond to a single frequency, oscillators can have multi-frequencies and graded excitations. On the other hand, he also changed the term “action energy” that corresponded to an energy interval by the concept of “energy quantum”. 

(2)	*Changes in taxonomic categories used for scientific descriptions and generalizations*.

Regarding taxonomic categories, the atomic theory was little accepted at that time; furthermore, matter and energy were only conceived to be continuous. It was necessary to obtain experimental evidence for the existence of the atom; only then it became appropriate to think of discrete distributions of matter. For Planck the quantization was a property of the interaction between the oscillators of the cavity with the radiation within it, while for Einstein quantization became a property of electromagnetic radiation in such a way that the photons become the energy quanta of the electromagnetic field. As will be seen in chapter 8 Einstein generalized the concept of a quantum of energy that later on will be called a photon. 
	
(3)	*Changes in metaphors, analogies or explanatory models*.

Planck solved the blackbody radiation problem by treating it in a similar way to the probabilistic problem Boltzmann addressed. However, Planck started from different premises; his hypothesis of the quantum of energy has no analogue in classical physics. (See section 5.3 and Appendix 5.2).


WORK: “When a black body is heated, electromagnetic radiation is emitted with a spectrum corresponding to the temperature of the body, and not to its composition. Calculating the form of the spectrum using then-known physical laws gave an unreasonable result; the radiation in the high-frequency area of the spectrum became infinite. Max Planck solved this problem in 1900 by introducing the theory of “quanta”, that is, that radiation consists of quanta with specific energies determined by a new fundamental constant, thereafter called Planck’s constant.”

MLA style: Max Planck – Facts. NobelPrize.org. Nobel Prize Outreach AB 2024. Wed. 17 Jan 2024. https://www.nobelprize.org/prizes/physics/1918/planck/facts/

NOBEL LECTURE: *The Genesis and Present State of Development of the Quantum Theory* by Planck.

MLA style: Max Planck – Nobel Lecture. NobelPrize.org. Nobel Prize Outreach AB 2023. Tue. 10 Jan 2023. https://www.nobelprize.org/prizes/physics/1918/planck/lecture/

***

[**Next: 5.3. Components of the explanation of scientific theories.**](./vol-II-chap-5-sect-3.md)