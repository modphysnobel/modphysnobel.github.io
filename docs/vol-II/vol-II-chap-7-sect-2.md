[**Volume II: Energy**](./volume-II.md)

[**Previous: 7.1. Experimental results concerning the Brownian motion.**](./vol-II-chap-7-sect-1.md) 

***

## 7.2.  Statistical mechanical calculations of the specific heat in solids.

This section contains  three examples of the calculation of the thermodynamic quantity known as specific heat at constant volume ($C_V$), following the procedures indicated by statistical mechanics. We analyze three models of a solid which assume that it is composed by: (1) free particles, (2) harmonic oscillators quantized with the same frequency, and (3) harmonic oscillators quantized with a frequency distribution.

The specific heat ($C$) is a thermodynamic quantity of an extensive nature: it increases with the size of the system and depends on its internal structure. It is defined as the quotient of the differential increase in the amount of heat ($δQ$) divided by the differential increase in temperature $(δT): C = δQ/δT$.

On the other hand, the internal energy ($U$) of a system is a function of the thermodynamic parameters of temperature ($T$), pressure ($p$) and volume ($V$). The internal energy $U$ is associated with the disordered movement that the components of the system present at the microscopic level. It corresponds to the total energy of the system, which has been necessary to create it. It is not connected with the block movements of the complete system (in bulk), nor with the energies caused when the complete system is under the action of external forces.

If the amount of heat $dQ$ is introduced to the system, the change in its internal energy ($dU$) is the sum of the heat transferred ($dQ$) plus or minus the work done $(pdV): dU = dQ ± pdV$. This equation corresponds to the first law of thermodynamics, associated with the conservation of energy.

If the volume of the system is constant, the specific heat at constant volume ($C_V$) only contains the term connected to the heat variation ($dQ$) since the contribution of work ($pdV$) is null, so $C_V = (δQ/δT )_V = (δU/δT)_V$. In other words, if we want to calculate $C_V$, we need to propose a model of the solid and a calculation procedure that allows us to obtain the quantity $(δU/δT)_V$. This requires understanding what the internal energy of the system represents and what to do to calculate it.

The variable $U$ has two components: the kinetic energy or thermal energy caused by the movements of translation, rotation and vibration of the microscopic components of the system (statistically connected with the temperature) and the potential energy associated with any static situation of the components that conforms the internal structure of the system, whose properties are manifested when the system interacts with the outside.

In statistical mechanics, the internal energy is equal to the average over the ensemble in question of the total energy of the system: $U = N_A <〈E〉$, where $〈E〉$ is the average value of the energy and $N_A$ is Avogadro's number. If the energy of each microstate has discrete values $E_i$, with probability $p_i$, $U= N_A〈E〉= N_A ∑_{i=1}^N p_i E_i$ where $p_i$ and $E_i$ are, respectively, the probability of occupation of the i-th microstate and its corresponding energy. These probabilities satisfy the normalization condition such that $∑_{i=1}^Np_i=1$.

When the energy spectrum is continuous, the summation in the previous equation becomes an integral; furthermore $p_i$ is described in terms of a normalized probability distribution function $f($**v, r**$)$ and $〈E〉=\frac{∬Ef(v,r)dvdr}{∬f(v,r)dvdr}$. In Cartesian coordinates we have $d$**v** $= dv_xdv_ydv_z$ and $d$**r** $= dxdydz$.

Next, for each one of the previously mentioned models, we consider four stages for calculating the internal energy, to then obtain the specific heat $C_V$. In the first two stages (STG1 and STG2)  the interpretation model of the physical system and the corresponding distribution function are described. The next two stages (STG3 and STG4) refer to the calculations of the average energy, the internal energy and the specific heat $C_V$.

### Dulong and Petit classic model.

STAGE 1: description of the physical system.

In this first model, the solid is a system of atoms considered as classical particles of mass $m$, subject to a harmonic oscillator potential of restitution constant $K$. The total energy of each atom in the crystal lattice is the sum of the kinetic energy  ($E_c$) plus the potential energy $(V):  E= E_c+V= ½mv^2 + ½Kr^2$.

In Cartesian coordinates $v^2 = v_x^2 + v_y^2 + v_z^2$ and $r^2 = x^2 + y^2 + z^2$. For simplicity, we will first deal with a one-dimensional problem, such that $v^2 = v_x^2$ and $r^2 = x^2$; Later, we will take into account the degrees of freedom corresponding to the other two coordinates. The complete motion is assumed to be the superposition of three independent motions, one in each dimension.

STAGE 2: description of the distribution function.

In this classical case, the function $f($**v, r**$)$ will correspond to the Maxwell-Boltzmann distribution, which describes the probability that one of the classical oscillators in the crystal lattice has an energy $E$ at temperature $T$. As we are considering only one degree of freedom, simplifying the notation and writing $v_x = v$, the total energy of the oscillator is $E = ½[mv^2 + Kx^2]$ and the distribution function $f($**v, r**$)  = f(v_x, x) =  e^{-βE}$ where $β = \frac{1}{k_B T}$ and $k_B$ is Boltzmann's constant.

STAGE 3: calculation of average energy.

Calculating the average energy in an oscillator in one dimension involves solving the following integrals $〈E〉 = \frac{∫_{-∞}^∞ dv ∫_{-∞}^∞ dx(Ee^{-βE})}{∫_{-∞}^∞ dv ∫_{-∞}^∞dx(e^{-βE})}$ . We will leave aside the details of the calculation; we simply indicate the result $〈E〉 =  \frac{1}{β}=k_B T$.

STAGE 4: calculation of internal energy and specific heat.

From the definition $U= N_A〈E〉$ and the previous result $〈E〉 =k_B T$, it can be obtained that $U = N_Ak_B T = RT$ with $R = N_Ak_B$. If the three degrees of freedom are considered, $U = 3RT$, from where $C_V = (δU/δT)_V = 3R = 3 \times  (8.3143 J K^{-1} mol^{-1}) = 24.9429 J K^{-1}mol^{-1}$. This means that the specific heat at constant volume is the same for all materials.

A similar result to the above ($C_V = 3R$) was obtained experimentally by Pierre-Louis Dulong (1785-1838) and Alexis-Thérèse Petit (1791-1820). These authors established that "the atoms of simple substances have exactly the same specific heat", as shown by the data they reported in their article *Recherches sur quelques points importants de la Théorie de la Chaleur*, published in 1819 in *Annales de Chimie et de Physique.*

The following Table 7.2 indicates in the first column the materials studied, in the second column the measured values of the specific heats ($C_V$), in the third column the relative weights of the atoms ($P_R$) and in the fourth column the products of the two previous columns; that is, the products of the weights of each atom multiplied by the measured specific heats, which practically give a constant value.

<div style="text-align:center;">
	<table cellspacing="0" cellpadding="0">
	<tbody>
	<tr>
	<th colspan="4" style="text-align: center">
	Table 7.2. Experimental values measured by Dulong and Petit in 1819.
	</th>
	</tr>
	<tr>
	<td style="text-align: center">
	Material
	</td>
	<td style="text-align: center">
	$C_V$
	</td>
	<td style="text-align: center">
	$P_R$
	</td>
	<td style="text-align: center">
	Constant
	</td>
	</tr>
	<tr>
	<td>
	Bismuth <br> 
	Lead <br>
	Gold <br>
	Platinum <br>
	Tin<br>
	Silver<br>
	Zinc <br>
	Tellurium<br>
	Copper<br>
	Nickel <br>
	Iron<br>
	Cobalt<br>
	Sulfur
	</td>
	<td>
	0.0288 
	0.0293 <br>
	0.0298 <br>
	0.0314 <br>
	0.0514 <br>
	0.0557 <br>
	0.0927 <br>
	0.0912 <br>
	0.0949 <br>
	0.1035 <br>
	0.1100 <br>
	0.1498 <br>
	0.1880  
	</td>
	<td>
	13.30 <br>
	12.95 <br>
	12.43 <br>
	11.16 <br>
	7.35 <br>
	6.75 <br>
	4.03 <br>
	4.03 <br>
	3.957 <br>
	3.69 <br>
	3.392 <br>
	2.46 <br>
	2.011 
	</td>
	<td>
	0.3830<br>
	0.3794<br>
	0.3704<br>
	0.3740<br>
	0.3779<br>
	0.3759<br>
	0.3736<br>
	0.3675<br>
	0.3755<br>
	0.3819<br>
	0.3731<br>
	0.3685<br>
	0.3780
	</td>
	</tr>
	</tbody>
	</table> 
	</div> 

<center>
	(Source: article published by Dulong and Petit (1819).)
	</center>

However, more precise and recent measurements have shown that the results obtained by Dulong and Petit are only valid at very high temperatures, where the value of the constant $3R ≈ 25 J K^{-1} mol^{-1}$ corresponds to the upper limit of the scale of the ordinates. In no way this value represents the behavior at low temperatures where, moreover, the experimental curves are different for different materials. Observe in Figure 7.3 how for different materials the values close to 300 K differ from the constant $3R ≈ 25 J K^{-1} mol^{-1}$, although for the first two materials, Lead (Pb) and Copper (Cu), the graphed values are much closer to that constant.

<p align="center">
	<img src="https://upload.wikimedia.org/wikipedia/commons/5/53/Moglft0304_calor_solidos.jpg" width=480 align=center>
	</p>

<center>
	(Source: article published by Dulong and Petit (1819).)
	</center>
	

**Figure 7.3.** Experimental values of specific heat at constant volume.

### Einstein's quantum model.

STAGE 1: description of the physical system.

In this case, the crystal lattice is supposed to be formed by atoms represented by independent harmonic oscillators, all with the same frequency ($ν_n = ν$ for all $n$), and quantized values of energy $E_n = nhν$; $n$ is a positive integer from zero to infinity and $h$ is Planck's constant.

STAGE 2:  description of the distribution function.

As in the previous model, the same Maxwell-Boltzmann distribution function is considered, now with discrete values of the energy $E_n: f($**v, r**$) = e^{-βE_n}$. 

STAGE 3: calculation of average energy.

Now the integrals are replaced by discrete sums and $〈E〉 =  \frac{∑_{n=0}^{n=∞}E_n e^{-βE_n}}{∑_{n=0}^{n=∞}e^{-βE_n}}$, where $E_n = nhν$ and  $n = 0, 1, 2 , ….. ∞$. The result is Planck's formula $〈E〉 = \frac{hν}{e^{βhν}- 1}$.

STAGE 4:  calculation of internal energy and specific heat.

As $U = 3N_A〈E〉$ and $C_V = (dU/dT)_V$ we will have that $C_V = (3N_Ahν)  \frac{d}{dT} (\frac{1}{e^{βhν}- 1})$ and remembering that $R = N_Ak_B$, it results the expression obtained by Einstein and published in  Annalen der Physik in 1907: 

$C_V = [(3R)(\frac{hν}{k_B T})^2 ]$ $\frac{e^{\frac{hν}{k_B T}}}{(e^{\frac{hν}{k_B T}}-1)^2}$

Now it is convenient to take two limit cases, depending on the temperature $T$. At high temperatures, the exponent $βhν = \frac{hν}{k_B T}≪1$. Then, developing to first order the exponential the average energy is $〈E〉 =   \frac{hν}{e^{βhν}- 1} = \frac{hν}{(1+ βhν+⋯ -1)} =   \frac{hν}{βhν} = k_B T$, from which Dulong and Petit's law is obtained $C_V  = (3N_A )   \frac{d〈E〉}{dT}=3N_A k_B=3R$.

At low temperatures $βhν =  \frac{hν}{k_B T}≫ 1$ and the exponential $e^{ \frac{hν}{k_B T}}≫ 1$, which results in:

$U=(3R)( \frac{hν}{k_B} )(e^{-βhν})$ and $C_V= \frac{dU}{dT} = (3R)( \frac{d}{dT})[\frac{hν}{k_B} (e^{-βhν})]=(3R)(\frac{hν}{k_B T})^2(e^{\frac{- hν}{k_B T}} )$.

### Debye's quantum model.

STAGE 1:  description of the physical system.

For low temperatures, the Einstein model predicts a value that does not vanish when the temperature is zero and also deviates considerably from the experimental results, even when it surpasses the inconsistency of Dulong and Petit's law, which predicts a constant value. To overcome this shortcoming of Einstein's model, Debye assumed in 1912 that each quantized oscillators had a different frequency. He considered the solid as a continuous elastic body, such that its internal energy was due to quantized vibrational states of stationary elastic waves, the called phonons.

The elastic waves that represent the phonons can vibrate both in a longitudinal direction with velocity $v_l$ and in a transverse direction with velocity $v_t$. There is one polarization direction for longitudinal waves and two perpendicular polarization directions for transverse waves. Therefore, the number of standing elastic waves in the interval of frequencies between $ν$ and $ν + dν$ will have two contributions: $n(ν)dν=(4πν^2dν)[\frac{1}{ν_l^3} + \frac{2}{ν_t^3})]$.

STAGE 2:  description of the distribution function.

As in Einstein's model, Debye considered that the same distribution function applies with discrete values of the energy $E_n: f($**v, r**$) = e^{-βE_n }$, but now $E_n$ is a continuous function of the quantized frequencies.

STAGE 3:  calculation of average energy.

Debye assumed that the statistics of the phonon system in the solid was the same as that used by Einstein: the one that corresponded to Planck photon gas. Following the previous model procedure, the same result was used for obtaining that $〈E〉=  \frac{hν}{e^{βhν}- 1}$.

STAGE 4:  calculation of internal energy and specific heat.

If the energy of waves with frequencies between $ν$ and $ν + dν$ is $n(ν)〈E〉dν$ and if $V_0$ is the volume of one kmol, the internal energy will be $U= (V_0 ) ∫_0^{ν_m}n(ν)〈E〉dν$.  In this equation the upper limit of integration $ν_m$ means that there is a finite number of standing waves so that the internal energy has a finite value. Under such conditions, the total number of standing waves will be equal to $3N_A$ degrees of freedom of one kmol of the solid and

$U=(V_0 ) ∫_0^{ν_m} n(ν)dν= (4πV_0)( \frac{1}{ν_l^3} + \frac{2}{ν_t^3}) ∫_0^{ν_m}ν^2 dν$.

Defining the variable $x= \frac{hν}{k_B T}$ and the Debye temperature $θ= \frac{hν_m}{k_B}$ , it results

$C_V= (9R)[(\frac{4T^3}{θ^3}) ∫_0^{x_m}(\frac{x^3}{e^x- 1})  dx- (\frac{θ}{T})(\frac{1}{e^{θ/T}- 1})]$

Figure 7.4 shows how Debye's result is better than Einstein's result near the origin and tends to a constant value for high temperatures.
	
<p align="center" width="100%">
    <img width="480" src="https://github.com/modphysnobel/modphysnobel.github.io/blob/main/docs/vol-II/figs/chap-7-sect-2-fig2.JPG?raw=true"> 
</p>
	

<center>
	(Image credit: CC Wikimedia Commons)
	</center>
	
**Figure 7.4.** Comparison in dimensionless units of the results of the three models of a solid.

Again, it is worth to consider two limiting cases. For high temperatures $\frac{θ}{T}≪1$ the second term is negligible and the integral can be calculated. Then, the Dulong and Petit law is obtained again

$C_V= (9R)[(\frac{4T^3}{θ^3})(\frac{1}{3})(\frac{θ}{T})^3- 1]=$ $(9R)[(\frac{4}{3})- 1] n=3R$

For low temperatures, $C_V= (9R)(\frac{4T^3}{θ^3})(\frac{π^4}{15})= (\frac{12Rπ^4}{5}) (\frac{T}{θ})^3$. This dependence on $T^3$ describes much better the experimental results. If the model is improved, especially if more complicated quantum effects are introduced in the description of the solid, the agreement with the experimental results will improve even more, although the calculation procedures will require numerical methods.

***

[**Next: 7.3.  Procedure to solve problems and explain solutions.**](./vol-II-chap-7-sect-3.md)