[**Volume II: Energy**](./volume-II.md)

[**Previous: 8.1. Conservation laws and the existence of symmetries.**](./vol-II-chap-8-sect-1.md) 

***

## 8.2. Energy transformations in photocells and in Light Emitting Diodes.

Despite the existence of the first law of Thermodynamics establishing the conservation of energy, the second law indicates that in any transformation of energy the entropy increases or at least is maintained equal. This is a serious but inevitable condition imposed on any practical application of energy transforming devices.  Photocells and LEDs are important technological devices that minimize in effective ways their corresponding dissipation processes.  

!!! info "A photocell is an energy transforming device."

	Photocells convert light energy into an electric current in a similar way as in the photoelectric effect. There are three main types of photocells having specific functions:

	Photoconductive cells mainly function as light detectors. These devices have a beam of infrared light shining permanently on a light-dependent resistor; it produces a steady electric current. When the beam is interrupted the current is reduced. This change is detected by an electronic circuit that triggers specific actions like opening a door, sounding an alarm, turning on a faucet, …

	Photoemissive cells mainly function as light amplifiers where light knocks electrons from a cathode to an anode, increasing the current flow through an external circuit. These devices serve to detect different kinds of radiations or to intensify the dim light of a night-time sensor.

	Photovoltaic cells mainly function as power producers like miniature power plants generating a constant supply of electricity to be used to power electric appliances and solar panels or to charge batteries. In such devices light makes electrons move between layers of the material producing a voltage and a current in an external circuit.  

	For more information consult <https://en.wikipedia.org/wiki/Solar_cell>

!!! info "Experimental evidence and Einstein´s explanation of the photoelectric effect."

	In the photoelectric effect the energy of the photoelectrons that leave the metal is equal to the energy of the incoming photons minus the energy required by the electrons to be liberated from the surface of the metal (the work function). 

	It is for the application of the conservation of energy to the photoelectric effect that Einstein was recognized in 1921 with a Physics Nobel Prize. The Physics Nobel Committee explained that such Prize was awarded “for his services to Theoretical Physics, and especially for his discovery of the law of the photoelectric effect”. However, his Nobel Lecture was related to relativity theories; it was already considered in Section 4.2. 

	In a famous paper *On a heuristic point of view concerning the generation and conversion of light*, published in Annalen der Physik, 17, 132, (1905), Einstein wrote: *“The quanta of energy penetrate the surface of the material and their respective energies are at least in part changed into the kinetic energy of electrons.”*

	The photoelectric effect consists of the emission of electrons in certain metals due to the incidence of light radiation of certain frequencies; an electric current is generated as a consequence of the release of electrons that were trapped inside the metal. In metals there are electrons that move more or less freely through the crystal lattice; however, they will remain inside the metal surface unless they receive enough energy from the outside to overcome the metal work function (φ).

	The emission of the photoelectrons can be detected in an experimental setup using an ammeter (A) like the one shown in Figure 8.1. The stopping potential ($V_0$) is the potential difference required to stop the fastest electrons, such that the photoelectric current is zero. The quantity $eV_0$ measures the kinetic energy $E_c = ½mv^2$ of the most energetic photoelectrons. This energy is equal to the difference between the energy (hf) of the incident electromagnetic radiation and the energy that the electrons need to be released from the metal which corresponds to the work function (φ) characteristic of the metal.

	$E_c = ½mv^2=eV_0=hf-φ$

	<div style="text-align:center;">
	<table cellspacing="0" cellpadding="0">
	<tbody>
	<tr>
		<td>
			![Fig1](./figs/chap-8-sect-2-fig3.PNG){width="300"}
		</td>
		<td>
			![Fig2](./figs/chap-8-sect-2-fig4.jpg){width="300"}
		</td>
	</tr>
	</tbody>
	</table> 
	</div> 

	(Image credit: CC Wikimedia Commons)

	**Figure 8.1.** Experimental device to detect the photoelectric effect: Einstein equation (upper left part) and the braking potential as a function of frequency (graph at the right). The red dots are experimental values. The box indicates the meaning of the physical quantities.

	The classical electromagnetic theory was formulated by Maxwell between 1864 and 1873. This theory summarizes all the existing knowledge about electricity and magnetism in four mathematical formulas and predicts that the electromagnetic field is a wave traveling at the speed of light $c=1⁄\sqrt{ε_0 μ_0}$. Its value is $3 \times 10^8$ m/s, where $ε_0$ is the electrical permittivity and $μ_0$ the magnetic permeability, both in vacuum. This fact was verified experimentally by Heinrich Hertz (1857-1894). In 1887 he showed that light is an electromagnetic wave and discovered the photoelectric effect.

	Maxwell's theory is a wave theory and requires that the radiated energy be distributed uniformly and continuously in the wave front that propagates from the emitting source to the receiving device. According to this wave theory, light of any frequency should produce photoelectric emission. Given enough time, the illuminated electron could accumulate the energy necessary to be liberated from the metal, even if the intensity of the radiation was very weak. 

	According to classical electromagnetism, for an intensity of $10^{-10} W/m^2$ and a wavelength of $λ = 500$ nm (1 nm = $10^{-9}$ m), around 5 hours should pass before the emission of photoelectrons. However, the first experimental results showed that the emission of photoelectrons was almost instantaneous with an estimated delay of $10^{-9}$ seconds.

	In the first experiments about the photoelectric effect, carried out in 1887 by Heinrich Hertz and Wilhelm Hallwachs (1859-1922), a well-polished zinc plate was connected to an electroscope. When the metal was illuminated with ultraviolet light coming from the jumping spark of a voltaic arc the ejected electrons could charge the electroscope (Figure 8.2).

	<p align="center">
	![Fig5](./figs/chap-8-sect-2-fig2.JPG){width="640"}
	</p>

	**Figure 8.2.** Experimental device used by Hertz and Hallwachs.

	In 1899 Joseph John Thomson (1856-1940) and in 1902 Philipp Lenard (1862-1947) independently demonstrated that the action of light on a metallic surface was the cause of the emission of free negative charges that were identified as electrons. Further experimental results needed satisfactory explanations that could not be provided by the classical electromagnetic theory:

	(1) Increasing the intensity of the radiation increases the number of electrons leaving the metal but did not increases their energy and therefore their speed: the energy of the emitted electrons doesn't depend on the intensity of the light but on its frequency. 

	(2) For each type of metal there is a minimum or threshold frequency below which photoelectrons are not produced no matter how intense the radiation is. It corresponds to a minimum energy to liberate the electron and produce the photoelectric effect. This is the work function (φ) characteristic of each metal. 

	(3) The stopping potential $V_0$ measures the kinetic energy of the fastest photoelectrons ($v_{max}$) such that $½m(v_{max})^2 = eV_0$. The maximum of this kinetic energy was independent of light incoming intensity and for certain voltages the magnitude of the photoelectron current reached a saturation limit.

	Since 1916 Robert Millikan (1868-1953) carried out experiments for analyzing the linear relationship between the variables $V_0$ and $f$ in Einstein's equation $E_c = ½mv^2 = eV_0 = hf – φ$. After much testing he derived three consequences (see the graph shown earlier in Figure 8.1):

	1) The ordinate at the origin ($f = 0$) implies that $eV_0 = – φ$; therefore $φ/e$ measures the starting energy in electron-volts.

	2) The straight line $V_0 = (hf – φ)/e$ has a slope equal to $h/e$. Taking into account that the charge of the electron is $e = 1.6 \times 10^{-19}$ coulombs, the value of Planck's constant can be obtained by measuring the slope of the straight line formed by experimental data (red dots in Figure 8.1)

	3) The point of intersection with the horizontal axis ($V_0 = 0$) determines the threshold frequency ($f_0 = φ/h$) below which there is no emission of photoelectrons.

	Millikan published his results in a paper entitled *A Direct Photoelectric Determination of Planck´s “h”*. Phys. Rev. 7, 355 (1916). Later, Gerald Holton explained *How Robert Millikan experimentally tested Einstein's photoelectric theory* in *Centennial Focus: Millikan's Measurement of Planck's Constant*. Phys. Rev. Focus 3, 23, April 22 (1999). 

	Einstein’s explanation can be summarized as follows:

	1.	The energy of the incoming electromagnetic radiation is quantized and is made up of photons.

	2.	The intensity of the radiation depends on the number of photons whose energy is $hf$. 

	3.	The conservation of mechanical energy law implies that the kinetic energy with which the photoelectrons are released is equal to the energy of the incident radiation minus the energy necessary to extract the photoelectrons from the  metal (work function).

	4.	There is a threshold frequency below which the photoelectric effect does not occur.

	Einstein's explanation fully agrees with experimental results and although he said the same thing as Planck (energy is discontinuous and it goes into packets) it was differently applied. Einstein's original contribution consisted in quantizing all types of radiation and establishing a connection between the wave nature of light (waves with frequency $f$) and the corpuscular nature of light (photons with energy $E = hf$). In this way, the quantization of energy becomes a fundamental property of electromagnetic waves: its intensity depends on the number of photons and its energy is a function of frequency.

	Einstein took up Planck's work and transcended it: the quantization of energy is no longer a calculation artifice for explaining black body radiation but a fundamental physical property of all electromagnetic radiations. If the energy of a thermal oscillator in a hot substance is quantized (Planck's hypothesis), by conservation of energy, the emitted radiation must also be quantized (Einstein's hypothesis). If this quantization condition is valid for the interaction between the incident radiation and the resonators of the blackbody cavity (the Planck oscillators), it must also be valid when electromagnetic radiation is transferred to the photoelectrons (photoelectric effect).

	It is also important to point out different “philosophical” positions regarding what the explanation of physical phenomena means: it was the search of the absolute for Planck and the pursue of simplicity for Einstein. The use of Einstein's reasoning is surprising for its originality and audacity, since it gives a very simple explanation of the photoelectric effect: the photons passed their energy in fixed quantities to atoms inside the metal, knocking some of their electrons out of them, so producing an electric current. Furthermore, Einstein solved the discrepancy between the experimental results and the classical theory of electromagnetic radiation by generalizing the concept of photon as tha quantum of electromagnetic radiation.

	Einstein applied a whole new reasoning process and introduced the revolutionary hypothesis of the quantization of radiation energy (photons). He used the ideal gas model of particles to make an analogy with the quantized radiation model. He considered the entropy change of an ideal gas at constant temperature when the volume changes reversibily. From this he concluded, comparing equations, that the physical behavior of both systems must be equivalent: if the ideal gas refers to material "particles", the electromagnetic radiation must also refer to “particles”, in this case photons.

	An important application of the photoelectric effect was made by K.M. Siegbahn (1918-2007) who received the 1981 Physics Nobel Prize “for his contribution to the development of high-resolution electron spectroscopy”. According to the Nobel Physics Committee: Siegbahn *“developed highly accurate measurements of energy levels in atoms by irradiating them with photons and measuring the energy of the electrons emitted using the photoelectric effect.”* For more information see his Nobel Lecture Electron Spectroscopy for Atoms, Molecules and Condensed Matter. The reference in MLA format is given at the end of the chapter. 
	
!!! info "Nobel Lectures related to the invention of LED."

	A diode is an electronic component with two terminals (a cathode and an anode) that conducts current in one direction where the resistance is zero while in the other direction the resistance is high resistance. A semiconductor diode is a crystalline piece of a semiconductor material with a p-n junction connecting the two electrical terminals. 

	The n-region of the semiconductor has free electrons (excess electrons) and the p-region has free holes (absence or lack of electrons). When a positive voltage is applied to the p-region and a negative one to the n-region, the electrons on the n-region are pushed to the p-region and the electrons flow through the p material beyond the semiconductor boundaries.

	A Light Emitting Diode (LED) is a semiconductor diode that generates light when it is traversed by an electric current. As a photocell generates a current when a radiation impacts on a metal, in a sort of inverse photoelectric effect a LED generates light when a current traverse a semiconductor. Depending on the material of the semiconductor the emitted light will be of different frequency corresponding to red, green, yellow, amber, or infrared colors.

	In what follows we include three documents related to the 2014 Physics Nobel Prize: (1)  excerpts of Popular information: *Blue LEDs – Filling the world with new light*, (2) the complete transcription of document called WORK describing the main contributions of the three laureates, and (3) the subtitles describing the content of each one of the three Nobel Lectures. All the references are in MLA format are given at the end of the chapter.

	(1)	2014 Physics Nobel Prize: Popular information: *Blue LEDs – Filling the world with new light*.

	….”The white LED lamps are energy-efficient, long-lasting and emit a bright white light. Moreover, and unlike fluorescent lamps, they do not contain mercury.”

	“Red and green light-emitting diodes have been with us for almost half a century, but blue light was needed to really revolutionize lighting technology. Only the triad of red, green and blue can produce the white light that illuminates the world for us. Despite the high stakes and great efforts undertaken in the research community as well as in industry, blue light remained a challenge for three decades.” …. “Incandescent light bulbs had lit the 20th century; the 21st century will be lit by LED lamps.”

	**Saving energy and resources.**
	
	“A light-emitting diode consists of a number of layered semiconductor materials. In the LED, electricity is directly converted into light particles, photons, leading to efficiency gains compared to other light sources where most of the electricity is converted to heat and only a small amount into light. In incandescent bulbs, as well as in halogen lamps, electric current is used to heat a wire filament, making it glow. In fluorescent lamps (previously referred to as low-energy lamps, but with the advent of LED lamps that label has lost its meaning) a gas discharge is produced creating both heat and light.”
	
	…..
	
	“LEDs are also more long-lasting than other lamps. Incandescent bulbs tend to last 1,000 hours, as heat destroys the filament, while fluorescent lamps usually last around 10,000 hours. LEDs can last for 100,000 hours, thus greatly reducing materials consumption.”

	**Creating light in a semiconductor.**
	
	…. 
	
	“A light-emitting diode consists of several layers: an n-type layer with a surplus of negative electrons, and a p-type layer with an insufficient amount of electrons, also referred to as a layer with a surplus of positive holes.”

	“Between them is an active layer, to which the negative electrons and the positive holes are driven when an electric voltage is applied to the semiconductor. When electrons and holes meet they recombine and light is created. The light’s wavelength depends entirely on the semiconductor; blue light appears at the short-wave end of the rainbow and can only be produced in some materials.”
	
	……
	
	“The red light-emitting diode was invented in the end of the 1950s. They were used, for instance, in digital watches and calculators, or as indicators of on/off-status in various appliances. At an early stage it was evident that a light-emitting diode with short wavelength, consisting of highly energetic photons – a blue diode – was needed to create white light. Many laboratories tried, but without success.”

	**Challenging convention.**
	
	…..
	
	“Gallium nitride was the material of choice for both Akasaki and Amano as well as for Nakamura, and they eventually succeeded in their efforts, even though others had failed before them. Early on, the material was considered appropriate for producing blue light, but practical difficulties had proved enormous. No one was able to grow gallium nitride crystals of high enough quality, since it was seen as a hopeless endeavour to try to produce a fitting surface to grow the gallium nitride crystal on. Moreover, it was virtually impossible to create p-type layers in this material.”
	
	…..

	**Fiat lux – let there be light.**

	“In 1986, Akasaki and Amano were the first to succeed in creating a high-quality gallium nitride crystal by placing a layer of aluminium nitride on a sapphire substrate and then growing the high quality gallium nitride on top of it. A few years later, at the end of the 1980s, they made a breakthrough in creating a p-type layer. By coincidence Akasaki and Amano discovered that their material was glowing more intensely when it was studied in a scanning electron microscope. This suggested that the electronic beam from the microscope was making the p-type layer more efficient. In 1992 they were able to present their first diode emitting a bright blue light.”

	“Nakamura began developing his blue LED in 1988. Two years later, he too, succeeded in creating high-quality gallium nitride. He found his own clever way of creating the crystal by first growing a thin layer of gallium nitride at low temperature, and growing subsequent layers at a higher temperature.”

	“Nakamura could also explain why Akasaki and Amano had succeeded with their p-type layer: the electron beam removed the hydrogen that was preventing the p-type layer to form. For his part, Nakamura replaced the electron beam with a simpler and cheaper method: by heating the material he managed to create a functional p-type layer in 1992. Hence, Nakamura’s solutions were different from those of Akasaki and Amano.”

	“During the 1990s, both research groups succeeded in further improving their blue LEDs, making them more efficient. They created different gallium nitride alloys using aluminium or indium, and the LED’s structure became increasingly complex.”

	“Akasaki, together with Amano, as well as Nakamura, also invented a blue laser in which the blue LED, the size of a grain of sand, is a crucial component. Contrary to the dispersed light of the LED, a blue laser emits a cutting-sharp beam. Since blue light has a very short wavelength, it can be packed much tighter; with blue light the same area can store four times more information than with infrared light. This increase in storage capacity quickly led to the development of Blu-ray discs with longer playback times, as well as better laser printers.”

	…..
	
	**A bright revolution.**

	“The Laureates’ inventions revolutionized the field of illumination technology. New, more efficient, cheaper and smarter lamps are developed all the time. …. White LED lamps can be created in two different ways. One way is to use blue light to excite a phosphor so that it shines in red and green. When all colours come together, white light is produced. The other way is to construct the lamp out of three LEDs, red, green and blue, and let the eye do the work of combining the three colours into white.”

	“LED lamps are thus flexible light sources, already with several applications in the field of illumination – millions of different colours can be produced; the colours and intensity can be varied as needed. Colourful light panels, several hundred square metres in size, blink, change colours and patterns. And everything can be controlled by computers. The possibility to control the colour of light also implies that LED lamps can reproduce the alternations of natural light and follow our biological clock. Greenhouse-cultivation using artificial light is already a reality.”

	…..
	
	(2)	WORK: “Lighting plays a major role in our quality of life. The development of light-emitting diodes (LEDs) has made more efficient light sources possible. Creating white light that can be used for lighting requires a combination of red, green, and blue light. Blue LEDs proved to be much more difficult to create than red and green diodes. During the 1980s and 1990s Isamu Akasaki, Hiroshi Amano, and Shuji Nakamura successfully used the difficult-to-handle semiconductor gallium nitride to create efficient blue LEDs.”

	(3)	2014 PHYSICS NOBEL LECTURES

	ISAMU AKASAKI: *Fascinated Journeys into Blue Light.*

	1.	*INTRODUCTION*
	2.	*LED RESEARCH IN THE EARLY DAYS*
	3.   *BRIEF HISTORY OF RESEARCH ON GaN-BASED MATERIALS AND DEVICES* \
		3.1. *Early attempts at development of GaN blue LED* \
		3.2. *Reconsideration of growth technology* 
	4. *CREATION OF GaN SINGLE CRYSTAL WITH EXCELLENT QUALITY* 
		4.1. *Development of low-temperature buffer layer technology in MOVPE* \
		4.2. *Model for the growth mode*
	5. *DISCOVERY OF p-TYPE GaN AND DEMONSTRATION OF p-n JUNCTION BLUE/ UV LED*
	6. *CONDUCTIVITY CONTROL OF n-TYPE GaN AND NITRIDE ALLOYS*
	7. *BRIEF HISTORY OF NITRIDE-BASED BLUE LEDs*
	8. *DEVELOPMENT OF NITRIDE-BASED LDs AND OTHER DEVICES*
	9. *SUMMARY AND FUTURE EXPECTATIONS*

	HIROSHI AMANO: *Growth of GaN on Sapphire via Low-Temperature Deposited Buffer Layer and Realization of p-Type GaN by Mg Doping Followed by LowEnergy Electron Beam Irradiation.*

	1.	*MOTIVATION FOR STARTING BLUE LED RESEARCH*
	2.	*DIFFICULTY OF REALIZING HIGH-PERFORMANCE BLUE LEDs BASED ON GaN*
	3.	*FUNDING SITUATION OF OUR LABORATORY IN THE MID-1980S AND THE DIFFICULTY OF GROWING GaN ON A SAPPHIRE SUBSTRATE*
	4.	*LOW-TEMPERATURE DEPOSITED BUFFER LAYER*
	5.	*REALIZATION OF p-TYPE GaN*
	6.	*ATTEMPTS TO GROW InGaN*
	7.	*CONTRIBUTION OF InGaN-BASED BLUE LEDs TO ENERGY SAVING*

	SHUJI NAKAMURA: *Background Story of the Invention of Efficient Blue InGaN Light Emitting Diodes.*

	1.	*INTRODUCTION AND IMPACT OF WHITE LIGHT EMITTING DIODES*
	2.	*MATERIAL OF CHOICE: ZnSe VS. GaN*
	3.	*DEVELOPMENT OF GaN*
	4.	*DEVELOPMENT OF InGaN* \
		4.1	*InGaN based devices*\
		4.2	*Material Properties of InGaN*
	5.	*HISTORICAL DEVELOPMENT OF InGaN BASED LEDS* \
		5.1	*Luminous Efficacy* \
		5.2	*Significant Milestones on the Journey to the White LED* \
		5.3	*Contributions to the Efficient Blue LED*
	6.	*FORWARD LOOKING*

***

[**Next: 8.3. Anthropological spaces for the development of collective intelligence.**](./vol-II-chap-8-sect-3.md)