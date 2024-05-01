
[**Volume II: Energy**](./volume-II.md)

[**Previous: 7.2.  Statistical mechanical calculations of the specific heat in solids.**](./vol-II-chap-7-sect-2.md) 

***

## 7.3. Procedures to solve problems and explain solutions. 

In this section we apply the TADIR procedure in the description of the seven steps of the statistical treatment used in 1908 by Paul Langevin (1872 - 1946) to obtain Einstein´s equation for explaining Brownian motion $(λ_x)^2 = <ΔX^2> = bt$, when $b = (k_BT)/(3πηa)$. 

TADIR is a problem solving procedure composed of five components: Translation (T), Analysis (A), Design (D), Implementation (I) and Review (R). The first four components (TADI) are of cognitive nature and the last one (R) is metacognitive. In the following diagram we define the five TADIR components and in Box 7.1 we indicate the corresponding steps proposed by Langevin to obtain Einstein´s equation.  

<p align="center" width="100%">
    <img width="200" src="https://github.com/modphysnobel/modphysnobel.github.io/blob/main/docs/vol-II/figs/chap-7-sect-3-fig1.PNG?raw=true"> 
</p>

<center>
(Image credit: drawings made by the authors.)
</center>

!!! bug "Box 7.1. TADIR steps of Langevin´s procedure."

<div style="text-align:center;">
	<table cellspacing="0" cellpadding="0">
	<tbody>
	<tr>
		<td style="text-align: center">
	TRANSLATION
	</td>
		<td>
	1. To describe the initial conditions that define the problem.
	</td>
	</tr>
	<tr>
		<td  style="text-align: center" rowspan=2>
	ANALYSISE
	</td>
		<td>
	2. To obtain average values.
	</td>
		<td>
	3. To calculate the average kinetic energies of the Brownian particles.
		</td>
	</tr>
	<tr>
		<td  style="text-align: center" rowspan=2>
	IMPLEMENTATION
	</td>
		<td>
	6. To calculate the root mean squares of the displacements in random walks.
		</td>
	</tr>
	<tr>
		<td>
	7. To calculate the integrals incorporating random walk results.
	</td>
	</tr>
	<tr>
		<td style="text-align: center">
	REVIEW
	</td>
	</tr>
	</tbody>
	</table> 
	</div> 







In what follows we first define each TADIR component of the problem solving procedure and then describe the corresponding steps proposed by Langevin to obtain Einstein´s equation.

**TRANSLATION:** Concise description in natural language to identify the main objects, agents, and events characterizing the problem.

Langevin describes the physical variables that intervene in the equation of motion of the Brownian particle and explains its interactions with the environment in terms of two forces: a force (F) which is the consequence of aleatory collisions produced on the Brownian particle by the very small molecules of the surrounding medium and the friction force (f) characterized by its viscosity (η) that experiments the Brownian particle during their displacements.

STEP 1. To describe the initial conditions that define the problem.

Each particle is spherical in shape with a radius $a4, has a mass $m$ and velocity $v = dr /dt$ where $r$ is the displacement. Two forces act on the Brownian particle: the force $F$ resulting from collisions and the friction force $f$, which acts in the opposite direction to the force $F$. 

According to Stokes' formula: $f = 6πηav$, where $v$ is the speed of the particle. Therefore, Newton's second law indicates that:

$m\frac{d^2r}{dt^2}=F-6πηa\frac{dr}{dt}$...(1)

Taking the X component of the displacement r and multiplying by x both parts of the previous equation of motion, we have

$mx\frac{d^2x}{dt^2}=xF_x-6πηax\frac{dx}{dt}$...(2)

From the relation $\frac{d(x^2)}{dt}=2x\frac{dx}{dt}$  it is obtained by simple derivation

$x\frac{dx}{dt}=\frac{1}{2}\frac{d(x^2)}{dt}$...(3)

Deriving again with respect to time previous equation we obtain

$\frac{1}{2}\frac{d^2(x^2)}{dt^2}=\frac{dx}{dt}(\frac{dx}{dt})+x\frac{d^2x}{dt^2}=(\frac{dx}{dt})^2+x\frac{d^2x}{dt^2}$...(4)

then, it results

$x\frac{d^2x}{dt^2}=\frac{1}{2}\frac{d^2(x^2)}{dt^2}-(\frac{dx}{dt})^2$...(5)

By substituting the previous equation into the equation of motion (2), we found that

$\frac{m}{2}\frac{d^2(x^2)}{dt^2}-m(\frac{dx}{dt})^2=xF_x-6πηa\frac{1}{2}\frac{d(x^2)}{dt}$...(6)

**ANALYSIS:**  Contextualized explanation in technical language to make clear and precise those approximations and simplifications required to solve the problem.

Langevin's derivation starts from the energy equipartition theorem, which establishes that the average kinetic energy of the Brownian particle is $ε = ½k_BT$ for each degree of freedom; therefore $E = 3ε$. At this point, Langevin considers the problem in one dimension and makes the assumption that the displacement in the ($x$) direction is not correlated with the force ($F_x$) in that direction.

STEP 2. To obtain average values.  

If a fairly large number of particles is considered, the above equation (6) is true for any particle and also for the average values of the magnitudes that appear in it. Therefore, taking average values

$\frac{m}{2}\frac{d^2(\bar{x^2})}{dt^2}-m\bar{(\frac{dx}{dt})^2}=\bar{xF_x}-3πηa\frac{d(\bar{x^2})}{dt}$...(7)

For a large number of particles, both quantities $x$ and $F_x$ are not correlated and can take both positive or negative values, so ($\bar{xF_x} = 0)$ and the equation of motion is left as

$\frac{m}{2}\frac{d^2(\bar{x^2})}{dt^2}-m\bar{(\frac{dx}{dt})^2}=-3πηa\frac{d(\bar{x^2})}{dt}$...(8)

STEP 3. To calculate the average kinetic energies of the Brownian particles.

The magnitude $\bar{(\frac{dx}{dt})^2}$ represents the average value of the square of the projection of the velocity $v$ on the $X$ axis. Since the motion of the particles is completely random, then the average values of the squares of the components of the velocity in each of the three coordinate axes must be equal, that is:

$\bar{(\frac{dx}{dt})^2}=\bar{(\frac{dy}{dt})^2}\bar{(\frac{dz}{dt})^2}$...(9)

The sum of these magnitudes must be equal to the average value of the square of the velocity $\bar{v^2}$ of the particles:

$\bar{(\frac{dx}{dt})^2}=\bar{(\frac{dy}{dt})^2}\bar{(\frac{dz}{dt})^2}=\bar{v^2}$...(10)

Then, the average value of each one of these components

$\bar{(\frac{dx}{dt})^2}=\frac{1}{3}\bar{v^2}$...(11)

Therefore, $m\bar{(\frac{dx}{dt})^2}=\frac{1}{3}m\bar{v^2}=\frac{2}{3}\frac{m\bar{v^2}}{2}$ , which corresponds to $⅔E_c$, where the kinetic energy $E_c = (3)(½)k_BT$ according to the energy equipartition theorem; $k = k_B$ is the Bolotzmann´s constant. As there are three degrees of freedom, it follows that

$m\bar{(\frac{dx}{dt})^2}=\frac{2}{3}\frac{m\bar{v^2}}{2}=kT$...(12)

DESIGN: Structural interconnection in a formal language: to integrate specialized concepts and models required for obtaining the solution.

To integrate the equation of motion of the Brownian particle, Langevin makes a change of variables, applies initial conditions with values that are consistent with the conditions of the experiment, and expresses the equation of motion in terms of finite increments.

STEP 4. To integrate the equation of motion.

Using equations (8) and (12) and defining

$\frac{d(\bar{x^2})}{dt}=Z$...(13)

equation (8) $\frac{m}{2}\frac{d^2(\bar{x^2})}{dt^2}-m\bar{(\frac{dx}{dt})^2}=-3πηa\frac{d(\bar{x^2})}{dt}$ can be expressed as

$\frac{m}{2}\frac{dZ}{dt}-kT=-3πηaZ$...(14)

After the separation of variables, the above equation becomes:

$\frac{dZ}{Z-\frac{kT}{3πηa}}=-\frac{6πηa}{m}dt$...(15)

If the limits of integration are, respectively, $0$ and $Z$ on the left and $0$ and $t$ on the right:

$\int_{0}^{Z} \frac{dZ}{Z-\frac{kT}{3πηa}}=-\int_{0}^{t} \frac{6πηa}{m}dt$...(16)

Integrating the above equation, we get

$ln(Z-\frac{kT}{3πηa})-ln(\frac{-kT}{3πηa})=\frac{-6πηa}{m}t$...(17)

Defining the quantities $A=kT/3πηa$ and $B= -(\frac{6πηa}{m})(t)$, the above equation can be expressed as $ln(Z – A) – ln (-A) = ln[(Z – A)/(-A)] = ln [(A – Z)/(A)] = - B$. This equation corresponds to $(A – Z)/(A) = exp(-B)$ and solving for $Z$ it results $Z = A[1 – exp(-B)]$. Using the definitions of $A$ and $B$ as well as equation (13) we get

$Z=\frac{kT}{3πηa}(1-e^{\frac{-6πηa}{m}t})=\frac{d(\bar{x^2})}{dt}$...(18)

STEP 5. To make approximations according to experimental conditions.

The conditions of the experiment are such that, in CGS units, $a ∼ 10^{-6}$ cm and $η ∼ 10^{-2}$. As the density of spherical particles (ρ) is of the order of unity, the mass is $m ∼ 10^{-18}$ g (the corresponding volume is $a^3 = (10^{-6})^3$). Therefore, for $t ≈ 10^{-5}$ s, the term $B = (6πηat)/m ∼ 10^6$ and the term $exp(-B)$ can be neglected. Consequently, if the time intervals between consecutive observations of the particles are greater than $10^{-5}$ s and remembering the definition of $Z$ in (13), after canceling the term of the exponential $exp(-B)$, it is obtained that equation (18) corresponds to

$\frac{d(\bar{x^2})}{dt}=\frac{kT}{3πηa}$...(19)

For finite intervals $Δt$ the above equation can be written in the form: $\frac{Δ\bar{x^2}}{Δt}=\frac{kT}{3πηa}$

Last equation can be expressed as

$Δ\bar{x^2}=\frac{kT}{3πηa}Δt$...(20)

**IMPLEMENTATION:** Practical obtention of results and their representations in iconic language to solve the problem and represent its results in terms of symbols, images, equations, numbers, diagrams, designs, pictures, …

Since Brownian motion is similar to the diffusion of molecules in a gas, both statistical processes can be treated according to the random walk model. Langevin considers first a one-dimensional model of the random work and describes it as a linear time dependence of the root mean square deviation of the particle.

STEP 6. To calculate the root mean squares of the displacements in random walks.

In the random walk problem a walker tosses a coin and takes one step forward if the result is heads and one step back if the result is tails. Each step represents the displacement between two consecutive points on the path. The problem consists in determining the average of the distance ($x_N$), traveled from the origin after $N$ steps.

If the probability of one step forward and one step back are equal, the average displacement $〈x_N〉$ will be zero; however, the average value of a quantity  $〈x_N^2〉$ is always positive. 

If the size of each step is $λ$, then the total distance traveled after the first step will correspond $x_1 = ± λ$, from where $(x_1)^2 = + λ^2$.  

For the second step, the distance will have to be $x_2 = x_1 ± λ$, so that $(x_2)^2 = (x_1 ± λ)^2$, from where $(x_2)^2 = (x_1)^2 ± 2 λx_1 + λ^2$. Taking average values and given that $〈x_1〉 = 0$ and that $〈x_1^2〉 = 〈λ^2〉 = λ^2$, the result is $〈x_2^2〉 = 〈x_1^2〉 ± 2λ〈x_1〉 + 〈λ^2〉 = 〈x_1^2〉 + λ^2 = 2λ^2$. 

For the next step $x_3 = x_2  ± λ$ and therefore $〈x_3^2〉 = 〈x_2^2〉 ± 2λ〈x^2〉+ 〈λ^2〉$, so that $〈x_3^2〉 = 〈x_2^2〉  + 〈λ^2〉 = 2λ^2 + λ^2 = 3λ^2$. Generalizing the process, we will have

$[〈x_N^2〉]^{1/2} = [Nλ^2]^{1/2} = N^{1/2}λ$...(21)

Applying the previous result to the movement of the Brownian particles, if their average speed is $\bar{v}$, the total distance traveled in time $t$ will be $d = \bar{v}t$ and the number of collisions $N$ in that same time $t$ will be equal to the distance traveled d between the size of each step $λ$:  $N = \bar{v}t /λ$. Since $〈x_N^2〉 = Nλ^2$, the mean square distance will be proportional to the time during which the $N$ steps have been taken, that is to say

$〈x_N^2〉 = (\bar{v}t/λ)(λ^2) = (\bar{v}tλ) = (\bar{v}λ)t$...(22)

STEP 7. To calculate the integrals incorporating random walk results.

Previous equation of motion (8) corresponded to

$(\frac{m}{2})(\frac{d^2〈x^2〉}{dt^2})- (m)〈(\frac{dx}{dt})^2〉 =  (-3πηa)(\frac{d〈x^2〉}{dt})$...(23)

Given the linear dependence with time of equation (22), its second derivative with respect to time is zero and therefore the first term of equation (23) is null, resulting

$(m)〈(\frac{dx}{dt})^2〉 = (3πηa)(\frac{d〈x^2〉}{dt})$...(24)
		
Applying the energy equipartition theorem in STEP 3, equation (12) was obtained, which indicates that the first term of (24) is equal to $k_BT$, therefore 

$k_BT=(3πηa)(\frac{d〈x^2〉}{dt})$...(25)

Using separation of variables and integrating both sides we get,

$〈x^2〉 =(\frac{k_BT}{3πηa})t$...(26)

This corresponds exactly to the equation obtained by Einstein $(λ_x)^2 = 〈ΔX^2〉 = bt$, where the slope of the straight-line was $b = (k_BT)/(3πηa)$. The graphical interpretation of this equation was already presented in Figure 7.1.

**REVIEW:**  Metacognitive reflection on the solution process and its consequences to start an helicoidal process for discussion of possible extensions or modifications to the initial statement of the problem.

The metacognitive component of the TADIR process would consist in comparing the Langevin procedure with that of Einstein with the purpose of considering conceptual and formal coincidences and differences. It could also refer to more complete approaches where the diffusion process is treated as a Markofian process (see for instance Pais).

***

### REFERENCES


EINSTEIN, A. On the Motion Required by the Molecular Kineteic Theory of Heat of Particles Suspended in Fluids at Rest. Annalen der Physik, 17, 549-560, (1905). 

EINSTEIN, A. Die Plancksche Theorie der Strahlung und die Theorie der spezifischen Wärme.  Annalen der Physik, 22, 180-190, (1907).

DEBYE P. Zur Theorie der spezifischen Wärmen. Annalen der Physik, 39, 789-839, (1912).

PETIT, A.T.; DULONG, P.L. Recherches sur quelques points importants de la Théorie de la Chaleur. Annales de Chimie et de Physique,.10: 395–413, (1819).

PAIS, A. “Subtle is the Lord…” The Science and the Life of Albert Einstein, Oxford University Press, Oxford, (1982).

PERRIN, J. Brownian Movement and Molecular Reality. (F. Soddy, Traducción). Taylor and Francis, London, (1910).

PERRIN, J. Les atomes, Cuarta edición, Librairie Alcan, París, (1914).

PERRIN, J. Atoms, (D.L. Hammick, Traductor), Van Nostrand, New York, (1916).

Perrin´s Physics Nobel Prize

MLA style: Jean Baptiste Perrin – Facts. NobelPrize.org. Nobel Prize Outreach AB 2024. Wed. 24 Jan 2024. <https://www.nobelprize.org/prizes/physics/1926/perrin/facts/>

MLA style: Jean Baptiste Perrin – Nobel Lecture. NobelPrize.org. Nobel Prize Outreach AB 2023. Mon. 23 Jan 2023. https://www.nobelprize.org/prizes/physics/1926/perrin/lecture/

***

[**Next: 8.1. Conservation laws and the existence of symmetries.**](./vol-II-chap-8-sect-1.md)
