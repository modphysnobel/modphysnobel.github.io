
[**Volume II: Energy**](./volume-II.md)

[**Previous: 7.3. Procedures to solve problems and explain solutions.**](./vol-II-chap-7-sect-3.md) 

***

## 8. Conservation and transformation of energy.

!!! abstract "Introduction."

	*Why a metal generates electrons when it is radiated with light and a LED emits light when electrons flow through it?*
  
	This chapter deals with the production, conservation, dissipation and saving of energy. One of the most important practical problems to be faced in our time is conservation of energy in any process in which coming out energy must be equal to coming in energy minus what is spent to make the process possible and what is lost. Some missing energy is dissipated  meaning entropy increases. 

	**Learning objectives of Chapter 8.**

	After this Chapter you should be able to:

	- Describe Hamilton's principle of least action and Noether's theorem; then consider the existence of conservation laws in connection with symmetries in physical systems.  
	- Analyze Einstein´s explanation of the photoelectric effect and describe the 2014 Physics Nobel Prize awarded for the invention of LEDs.
	- Explain some conceptual developments and technological applications on energy connected with the four anthropological spaces related to the Earth, the Territory, the Merchandises and the Knowledge. 

!!! abstract "Description of content of Chapter 8."

	**Section 8.1. Conservation laws and the existence of symmetries.**

	We relate conservation laws to invariant properties of mathematical transformations associated to translation and rotations in space and translation in time. Furthermore, we describe Hamilton's principle of least action and relate Noether's theorem with conservation laws.

	**Section 8.2. Energy transformations in photocells and in Light Emitting Diodes (LED).**

	As a critical application of the conservation of energy we discuss theoretical and experimental aspects of the photoelectric effect. We also consider several documents related to the 2014 Physics Nobel Prize awarded to Isamu Akasaki (1929-2021), Hiroshi Amano (1960) and Shuji Nakamura (1954) “for the invention of efficient blue light-emitting diodes which has enabled bright and energy-saving white light sources".             

	**Section 8.3. Anthropological spaces for the development of collective intelligence.**

	We explain the meaning of Anthropological spaces for the development of collective intelligence and then consider the main conceptual developments and technological applications on energy connected with four anthropological spaces: the Earth, the Territory, the Merchandises and the Knowledge. 

## 8.1. Conservation laws and the existence of symmetries.

Since ancient times it has been assumed that the Newtonian space has the properties of being homogeneous, that is, it is the same in every region and there are no privileged reference points (the origin of the coordinate system can be anywhere). Furthermore, space is isotropic because there are no preferred orientations, all directions are equally appropriate. Time is also homogeneous, because there are no favorite moments for the description of the evolution of phenomena; every origin of time is equally valid.

Each one of the previous properties of space and time implies that a physical property remains constant in the system because an invariant mathematical condition applies. What remains invariant in each case is the consequence of a symmetry with respect to a specific transformation in space or time. 

The previous connection between three types of symmetry properties with their respective conservation laws is an example of the process of geometrization of mechanics. As an appropriate background to consider this connection, let us quote Richard Feynman (first two paragraphs of section 26-3 in his Volume I). He wrote the following in connection with *Fermat's principle of minimum time:*

"Now, in the further development of science we want more than a formula. First we have an observation, then numbers that we measure, then we have a law that sums up all the numbers. But the real glory of science is that we can find a way of thinking in such a way that the law is self-evident."

"The first way of thinking that made the law of light behavior evident was discovered by Fermat around 1650 and is called the principle of least time or Fermat's principle. His idea is that of all the possible paths it can take to get from one point to another, light takes the path that requires the **shortest time**."

### Hamilton's principle of least action and Noether's theorem.

The relationship between the invariance with respect to certain mathematical transformations and mechanical conservation laws is derived from a combined application of the principle of least action formulated in 1834 by William Rowan Hamilton (1805-1865) and one of the theorems established in 1918 by Amalie Emmy Noether (1882 - 1935). Before considering a very simplified description of such contributions, let us describe the notion of temporal evolution of a physical system in the configuration space.

- Hamilton's principle resembles Fermat's principle; instead of minimizing the travel time of light, it considers trajectories in mechanical systems and minimizes the physical quantity called action, which is the product of the energy involved in a process multiplied by the duration of the process.

- The evolution in time of a mechanical system is determined when the equations of motion of the system are solved. This mathematical procedure requires the complete description as a function of time of the position of each one of the particles in the system. In the most advanced treatment of Newtonian mechanics, analytical mechanics, a physical system of N particles is described in the so-called configuration phase space, This space is composed of 6N coordinates: 3N coordinates correspond to the components of positions $[(x_1,y_1,z_1,x_2,y_2…x_N,y_N,z_N )]$ and other 3N coordinates to the components of velocities $[(\dot{x_1},\dot{y_1},\dot{z_1},\dot{x_2},\dot{y_2}…\dot{x_N},\dot{y_N},\dot{z_N})]$. In this expression the following notation has been used $\dot{x_i}=v_{x_i}= \frac{dx_i}{dt}$ for $i=1,2,3,…,N$.
	
- The description in the configuration space is more efficient when generalized coordinates $(q,\dot{q})$ are used instead of the cartesian coordinates $(x,v)$. The canonically conjugate variable of $q_k$ is  $(\dot{q}) = (δq_k)/δt$, like the velocity associated with the position  ${\dot{x}}_{i} = v_{x_{i}} = \frac{dx_{i}}{dt}$.

- Within the framework of analytical mechanics, the Lagrangian function (L) is defined as the difference between the kinetic energy of the system ($E_c$) and its corresponding potential energy ($E_p$): $L = E_c – E_p$. This function depends on 6N generalized coordinates and of time $t$. In this context, the action function $S$ is defined as the time integral of the Lagrangian:

	$S= ∫_{t_i}^{t_f} [L(q,\dot{q})dt]$, where $L(q,\dot{q})$ means $L[(q_1,q_2,q_3,… q_N),(\dot{q}_1, \dot{q}_2, \dot{q}_3,...\dot{q}_N);t]$

- As the previous definition indicates, the integral corresponds to adding all possible trajectories that start at an initial time $t_i$ and end at a final time $t_f$. Under these conditions, Hamilton's principle of least action indicates that all the possible trajectories described in the configuration space makes the action variation null; that is to say that $δS = 0$.

- Now, let us consider a generalized coordinate system where the Lagrangian L does not depend on a certain variable $q_k$. This variable is called ignorable or cyclic. In this case, the variation of L with respect to such variable is zero, which technically means that its partial derivative is zero: $\frac{δL}{δq_k} =0$.  

- The previous variational condition is interpreted by saying that the absence or omission of an ignorable variable in the Lagrangian corresponds to a certain type of symmetry with respect to a transformation in space or in time. Noether showed that if a system has a specific type of symmetry concerning certain mathematical properties of space or time, then a physical conservation law exists when the Lagrangian remains invariant under one of those specific transformations that made invariant the description of the system.
	
Let's look at three application cases: 

1. If the homogeneity of time is considered, the Lagrangian does not depend on this variable, so $\frac{δL}{δt}=0$ and the system is invariant against translations in time. Since the variable conjugate to time is energy, there is a law of conservation of energy.

2. In the case of the homogeneity of space, the system is invariant against displacements in space because there are no privileged positions; this corresponds to the law of conservation of linear momentum.

3. The isotropy of space indicates that there are no privileged orientations, so that the system is invariant against a rotation in space, which implies that there is a law of conservation of angular momentum.

***

[**Next: 8.2. Energy transformations in photocells and in Light Emitting Diodes.**](./vol-II-chap-8-sect-2.md)



