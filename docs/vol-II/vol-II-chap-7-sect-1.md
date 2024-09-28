
[**Volume II: Energy**](./volume-II.md)

[**Previous: 6.3. Identification of concepts and descriptions of models.**](./vol-II-chap-6-sect-3.md) 

***

# 7.  Brownian motion and specific heats.


*Under what conditions is statistical mechanics necessary?*

Physical systems can be characterized in terms of three of properties of their components: size (Siz), velocity (Vel), and number (Num). When Num is very large, it is impossible to solve the equations of motion for all the degrees of freedom of the system. Under such conditions, statistical mechanics applies different mathematical procedures, essentially probabilistic, to calculate values of macroscopic quantities describing the system. Given a microscopic [model of the system](https://en.wikipedia.org/wiki/Systems_modeling), a [statistical](https://en.wikipedia.org/wiki/Statistics) procedure is applied to calculate average values, fluctuations, deviations, correlations, and other mathematical functions of physical interest.

### Learning objectives of Chapter 7.

After this Chapter you should be able to: 

- Explain the phenomena of [Brownian motion](https://en.wikipedia.org/wiki/Brownian_motion) from both perspectives: the theoretical one based on Einstein´s interpretation and the experimental one derived from Perrin´s work.
- Describe the calculations of the [specific heat in solids](https://en.wikipedia.org/wiki/Specific_heat_capacity) according to the models proposed by Dulong and Petit, by Einstein and by Debye.
- Describe the problem-solving steps proposed by Langevin to obtain Einstein´s Brownian motion equation.

### Description of content of Chapter 7.

Section 7.1. Experimental results concerning the Brownian motion.**

We discuss two contributions to the study of Brownian motion: the theoretical calculation made by Einstein and the experimental procedures reported by Perrin. We also consider the 1926 Physics Nobel Lecture *Discontinuous Structure of Matter* by J.B. Perrin. 

Section 7.2. Statistical mechanical calculations of the specific heat in solids.**

We consider the calculations of the specific heat at constant volume in solids, according to three models: the classic model by Dulong and Petit where the solid is formed by independent classical harmonic oscillators, the quantum models by Einstein where the solid is composed by quantized harmonic oscillators all of them with the same frequency, and the quantum model by Deby where the solid is a continuous elastic body whose internal energy is due to quantized vibrational states of stationary elastic waves, the phonons.

Section 7.3. Procedure to solve problems and explain solutions.

We apply the *Procedure to solve problems and explain solutions* in the description of the steps of [Langevin´s procedure](https://en.wikipedia.org/wiki/Langevin_equation) to obtain Einstein's equation of Brownian motion.

## 7.1. Experimental results concerning the Brownian motion.

To calculate average values of quantities related to physical observables, interpretation models and calculation procedures must be proposed and tested. The models describe with a certain level of approximation the probability distribution functions about the possible configurational states of the system or microstates. The procedures for counting and mathematically operating with the formal representations of these configurational states serve to calculate macroscopic quantities characterizing the physical system. 

### Einstein´s procedures.

[Albert Einstein](https://en.wikipedia.org/wiki/Albert_Einstein) (1879-1955) carried out in 1905 one of the first [statistical mechanics](https://en.wikipedia.org/wiki/Statistical_mechanics) calculations to explain the Brownian movement. He assumed the existence of two types of molecules in the system under study: the Brownian particles (pollen) and the molecules of the liquid medium (water). In addition, he identified the root mean square displacement of the Brownian particle instead of its velocity as the appropriate observable characteristic and related the random motion of a particle to the [diffusion](https://en.wikipedia.org/wiki/Einstein_relation_(kinetic_theory)) of many particles.

In the article *On the Motion Required by the Molecular Kinetic Theory of Heat of Particles Suspended in Fluids at Rest* Einstein stated the following: “In this article it will be shown that, according to the molecular-kinetic theory of heat, bodies of a microscopically visible size suspended in liquids must carry out, as a result of thermal molecular movements, movements of such a magnitude that they can be easily observed with a microscope”.

Einstein considered the fact that atoms have a real and not hypothetical existence and that therefore a fluid like water has an atomic structure. At that time, the real existence of the atom was questioned as a physical component of matter and not as an explanatory hypothesis, uncertain and perhaps unnecessary, useful for codifying certain regularities. Einstein assumed that a particle immersed in an aqueous solution will experience collisions and make erratic movements, as a consequence of a pressure similar to the osmotic pressure exerted by the atoms of the fluid on the dissolved particle.

The expression $D = (RT)/(6πηaN_A)$ is called the [Stokes-Einstein equation](https://en.wikipedia.org/wiki/Einstein_relation_(kinetic_theory)), where the diffusion coefficient ($D$) is linear with temperature ($T$) and the constant of proportionality depends on the size ($a$) of the particle and the viscosity ($η$) of the fluid (viscosity is the resistance to flow). The equation contains also universal constants such as the universal gas constant ($R$) and Avogadro's number ($N_A$). (Avogadro's number is the number of molecules that contain equal volumes of gases at fixed temperatures and pressures.) 

The diffusion of the particles can be seen as a probabilistic process where the variable is the displacement and not the velocity: the average displacement in the $X$-direction ($λ_x$) of the suspended particles depends on the diffusion coefficient ($D$) and on a time ($t$) of observation during which the displacement in $X$ occurs. That is to say $λ_x=\sqrt{〈x^2〉}=\sqrt{2Dt}$. 

Einstein used the two previous equations that define $D$ and $λ_x$ and predicted that the root mean square deviation of the random displacements in an X direction had a linear behavior with respect to the temperature $T$ of the liquid and the time $t$ during which the Brownian particle suffers collisions with surrounding water molecules:

<center>
$<ΔX^2> =[(k_BT)/(3πηa)](t)$
</center>

In the previous equation, the Boltzmann constant $k_B = R/N_A$ where $N_A$ is Avogadro's number and $R$ is the universal gas constant (Figure 7.1).
	
<p align="center" width="100%">
    <img width="380" src="https://github.com/modphysnobel/modphysnobel.github.io/blob/main/docs/vol-II/figs/chap-7-sect-1-fig4.jpg?raw=true"> 
</p>


<center>
(Images credit: CC Wikimedia Commons)
</center>

**Figure 7.1.** Graph of the equation obtained by Einstein.

In Figure 7.1, the time t on the horizontal axis indicates two moments: before the collisions (segment O to N) when the Brownian particle is placed in the liquid and moves freely until the collisions begin, and during the collisions (segment N to M) when the trajectory of the Brownian particle changes randomly satisfying Einstein's linear equation. In section 7.3 we obtain this equation by following Langevin procedure.

Einstein's theoretical work contributed to the following: (1) to demonstrate the discontinuous structure of matter and prove the existence of atoms; (2) to develop ideas and procedures of statistical mechanics, which lays the foundations of thermodynamics, and (3) to test experimentally ideas derived from statistical calculations that led to the exact measurement of quantities such as Avogadro's number and the mass of the hydrogen molecule.

### Observations and measurements of the Brownian motion.

The first observations of Brownian motion were made in 1785 by Jan Ingenhousz (1730-1799), who described the "erratic" motion of carbon particles on the surface of alcohol. In 1827, the botanist [Robert Brown](https://en.wikipedia.org/wiki/Robert_Brown_(botanist,_born_1773)) (1773-1858) observed under a microscope the random movements of pollen grains from the plant *Clarkia pulchell* suspended in water. He published his results in a book with the not so brief title of *A brief account of microscopical observations made in the months of June, July and August, 1827, on the particles contained in the pollen of plants; and on the general existence of active molecules in organic and inorganic bodies*.

Many years later in 1910, [Jean Perrin](https://en.wikipedia.org/wiki/Jean_Baptiste_Perrin) (1870-1942) published the results of his work in the article *Brownian motion and molecular reality* and in the book *Les atoms* edited in French in 1914 and translated into English in 1916. The reported results verified Einstein's theory.

Perrin carried out experiments on sedimentation (the settling of suspended particles caused by gravity) and was able to prove the validity of the analogy between the molecules of a gas and the particles suspended in a liquid. He observed the movement of the particles through a microscope, whose eyepiece was equipped with a grid that served as a coordinate system (Figure 7.2). He showed that the displacement of particles resulted in a certain vertical distribution and counted the number of particles contained in a drop of water located at different depths. The concentration of particles was higher at greater depths.
	
<div style="text-align:center;">
	<table cellspacing="0" cellpadding="0">
	<tbody>
	<tr>
		<td>
		<img width="120" src="https://github.com/modphysnobel/modphysnobel.github.io/blob/main/docs/vol-II/figs/chap-7-sect-1-fig5.jpg?raw=true"> 
		</td>
		<td>
		<img width="480" src="https://github.com/modphysnobel/modphysnobel.github.io/blob/main/docs/vol-II/figs/chap-7-sect-1-fig6.jpg?raw=true"> 
		</td>
	</tr>
	</tbody>
	</table> 
	</div> 

<center>
(Source: images taken from the book *Les atomes* by Perrin.)
</center>


**Figure 7.2.** Distribution of equilibrium heights of particles within a gravitational field (left image) and successive positions recorded every 30 seconds; the projections of displacements in the x-direction are also indicated (right image).

To carry out his experiments, Perrin first very carefully prepared particles of the same radius ($0.53 \times 10^{-6}$ m)and then he marked on the microscope reticule the successive positions of a chosen particle. Then he plotted those points on a paper, determined the corresponding displacements of the particle and calculated the mean square value of those displacements. 
	
It was estimated that the Brownian particle received the order of $10^{14}$ collisions per second from the water molecules in the surrounding media. By substituting his measurements in Einstein's equation, Perrin obtained the value of Avogadro's number ($N_A$). The following Table 7.1 contains the values obtained by Einstein and by Perrin; numerical values in the third column are multiplied by the factor $10^{23}$. 

<p align="center" width="100%">
    <img width="600" src="https://github.com/modphysnobel/modphysnobel.github.io/blob/main/docs/vol-II/figs/7.1.jpg?raw=true"> 
</p>


<center>
(Source: information obtained from Pais´ book.)
</center>

The 1926 Physics Nobel Prize was awarded to Jean Baptiste Perrin (1870-1942) "for his work on the discontinuous structure of matter, and especially for his discovery of sedimentation equilibrium". In what follows, we quote the document Work describing the contributions made by Perrin and then we indicate the title of his Nobel Lecture and its corresponding subtitles. The complete texts of the sections with subtitles in boldface are included in Appendix 7.1. All the references of these documents in MLA format are given.
	

WORK: “During the 1880s atoms and molecules became important scientific concepts, but whether or not they actually had a physical existence was still a matter of dispute. Jean Perrin (1870-1942) maintained that if molecules were real, particles blended into a liquid should not all sink to the bottom but should distribute themselves throughout the liquid. In 1908 he could substantiate this through experimentation. He also substantiated Einstein’s theory that Brownian motion—the random movement of small particles in a liquid—was due to collisions between the particles and molecules in the liquid.”

MLA style: Jean Baptiste Perrin – Facts. NobelPrize.org. Nobel Prize Outreach AB 2024. Wed. 24 Jan 2024. https://www.nobelprize.org/prizes/physics/1926/perrin/facts/

NOBEL LECTURE: *Discontinuous Structure of Matter* by Perrin. 

- Introduction
- **The Brownian movement**
- Law of the vertical distribution of an emulsion
- Non-diluted emulsions
- **Measurements of the Brownian movement**
- The molecular reality
- Monomolecular films
- The discontinuous structure of the atom

MLA style: Jean Baptiste Perrin – Nobel Lecture. NobelPrize.org. Nobel Prize Outreach AB 2023. Mon. 23 Jan 2023. https://www.nobelprize.org/prizes/physics/1926/perrin/lecture/

In what follows, we include in three boxes information related to Brownian motion obtained from Perrin´s Nobel Lecture: the first box refers to key concepts most frequently employed in the Lecture; next two boxes describe the main issues considered in the Lecture that require physical and mathematical models for their representation and interpretation. Any complete quoted paragraph obtained from the Lecture is indicated in between quotation marks. 

<p align="center" width="100%">
    <img width="600" src="https://github.com/modphysnobel/modphysnobel.github.io/blob/main/docs/vol-II/figs/7.2.jpg?raw=true"> 
</p>


!!! quote "Box 7.1. *Issues requiring explaining models in Perrin´s Lecture (1)*."

	•	The appearance or disappearance of molecules in chemical reactions imply the existence of a small number of simple indestructible bodies which can always be recovered without any change in their nature: the atoms. <br>
	•	The fundamental laws of chemistry concern the discontinuity between chemical species and their discontinuous variation according to the rule of multiple proportions. Understanding these laws requires that compounds molecules contain whole number of atoms. <br>
	•	According to Avogadro’s hypothesis equal numbers of heavy or light molecules develop equal pressures at the same temperature and in equal volumes: When gaseous masses, at the same temperature and pressure, occupy equal volumes, they all contain the same number of molecules. <br>
	•	Crystallography refers to laws of discontinuity of elementary cells which are repeated periodically along the three dimensions of the crystal lattice. <br>
	•	The kinetic theory of gases indicates that matter is made of elastic molecules which are on the average fairly widely separated from one another so that, between two collisions, each molecule can move in a straight line, the duration of the collision being negligible in relation to that of the free path. <br>
	•	As Clausius observed, the molecules are all the smaller as the mean free path. <br>
	•	Brownian motion is observed when a microscopic particle placed in water (or any other liquid), instead of falling in a regular manner exhibits a continuous and perfectly irregular agitation. … The Brownian movement (an experimental fact) leads us to the hypothesis of the molecules. <br>
	•	A stable emulsion is comparable to a solution. An emulsion is formed when a large number of identical particles (grains) are in suspension in a liquid. It will be assumed that Avogadro’s law applies to emulsions as it does to gases. <br>
	•	The law of Van’t Hoff is an extension of Avogadro’s law to solutions: : “Equal numbers of molecules, regardless of the kind, in the gaseous state or dissolved, exert – at the same temperature and in equal volumes – equal pressures on the walls detaining them”. <br>
	•	In a vertical column of a gas in equilibrium the density decreases as the altitude increases. <br>
	•	A non-diluted emulsion is comparable to a compressed liquid of which the molecules would be visible. <br>
	•	In a stable emulsion made of equal grains each one of them has an effective weight equal to its actual downward weight reduced by the upward push that according with Archimedes’ principle is equal to the weight of the liquid displaced by the volume of each grain. <br>
	•	The equilibrium distribution of an emulsion is due to the Brownian movement…. In an emulsion the mean square of the horizontal displacement of a grain is proportional to the duration of each free rectilinear displacement. Such displacements are due to a great number of collisions of the surrounding molecules of the liquid with the grain molecules. <br>
	•	There is a diffusion for the grains of an emulsion just as for the molecules of a solution. The steady state in a vertical column of emulsion is produced and maintained by the interplay of two opposing actions, gravity and the Brownian movement… At each level the flow through diffusion towards the poor regions is equal to that which gravity produces towards the rich regions. <br>
	•	To calculate the flow produced by gravity, the mean velocity of fall of a grain animated by a Brownian movement is calculated by Stokes’ law, which applies to the uniform fall in a viscous liquid of a large sphere. <br>
	•	There exists equality between the mean energy of translation and the mean energy of rotation. <br>
	•	Einstein’s formulae were checked by seeing whether they led always to the same value for Avogadro’s number. <br>
	•	Different values for the Avogadro’s number were obtained depending on the experimental procedure used: distribution of emulsions analogous to gases, emulsions analogous to liquids, fluctuations in concentrated emulsions, translational Brownian movement or rotational Brownian movement.

!!! quote "Box 7.2. *Issues requiring explaining models in Perrin´s Lecture (2)*."

	•	Avogadro’s number has been obtained by means of measurements relating other phenomena such as: critical opalescence, the blueness of the sky, light diffused by gases, black-body radiation, measurements of the electric charges of charged microscopic dust or radioactivity. <br>
	•	The objective reality of molecules and atoms which was doubted twenty years ago, can today be accepted as a principle the consequences of which can always be proved. <br>
	•	Further contributions by Perrin to improve the knowledge of the manner in which matter is discontinuous: <br>
	-- in 1895: indication that cathode rays have a negative electric charge and attempts to measure its relation charge to mass; <br>
	-- in 1901: assumption that the atom has a structure like a solar system, revealing that the atom as well as the nucleus are discontinuous and have their own components; <br>
	-- in 1920: consideration that atoms can be condensations of a whole number of hydrogen atoms, the small differences which exist are explained by the large variations of internal energy which may accompany their condensations; <br>
	-- in 1920: indication that the loss of energy which must accompany the condensation of hydrogen into helium suffices alone to account for approximately one hundred milliard years of solar radiation at the present rate; <br>
	-- in 1923: interpretation of Rutherford transmutations of elements not as being the effect of an explosive disintegration but on the contrary, as an integration (the helium nucleus combines with the nucleus that it has hit, to form a radioactive atom which soon expels a proton, and that there finally remains an atom which is three units heavier than the atom that has been hit).

***

[**Next: 7.2.  Statistical mechanical calculations of the specific heat in solids.**](./vol-II-chap-7-sect-2.md)
