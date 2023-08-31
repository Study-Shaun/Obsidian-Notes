### Ideal Diode
- two terminal device
- acts like a switch that can only conduct in one direction (that of the arrow symbol)
- is a short circuit for the region of conduction
- is an open circuit in the region of non-conduction
 
 ![[Pasted image 20230826133759.png]]
##### Questions to Consider:
- How close is the forward bias resistance of a practical diode to the ideal 0Ω?
- Is the reverse bias resistance large enough to approximate an open circuit?
### Semiconductor Materials
- conductivity level somewhere between an insulator and a conductor
- conductivity:
  ![[Pasted image 20230826134937.png]]
- typical resistivity values:
  ![[Pasted image 20230826135030.png]]
- most used:
	- germanium (Ge)
	- silicon (Si)
	- used cuz can be manufactured to high level of purity
	- shifting towards silicon and away from germanium
- Doping: changing the characteristics of the material by adding impurities
- Properties of Silicon & Germanium:
	- head and light sensitive
	- 1ppm of impurity in silicon can change it form poor to good conductor
	- atoms form a definite pattern - crystal lattice
	- crystal structure:
		![[Pasted image 20230826141457.png]]
	- periodicity of the structure doesn't change much with doping
	- covalent bonding in silicon:
		![[Pasted image 20230826141929.png]]
- Intrinsic Material - semiconductors that have been refined to have a very low level of impurities
- Intrinsic Carriers - free electrons in the material only due to natural causes
- increase in temperature -> substantial increase in number of free electrons
- Negative Temperature Coefficient -> semiconductors showing reduction in resistance with increase in temperature
	- conductors have a Positive Temperature Coefficient

### Energy Levels
- further away from the nucleus -> higher energy state
- free electron -> higher energy state than electron in atomic structure
- Valence & Conduction Bands:
	![[Pasted image 20230826150517.png]]
- work done: W = q * V (eV)
	- electron volt: 1 eV = 1.6 x 10$^{-19}$ J
	- joule: 1 J = 6.25 x 10$^{18}$ eV
- at 0K all the valence electrons of a semiconductor are locked in their outermost shell
	- conductor has electrons in the conduction band even at 0K
- at room temperature many valence electrons have enough energy to go to the conduction band

### Extrinsic Materials
- semiconductor that has been subjected to doping
- made by adding a predetermined number of impurity atoms to a germanium or silicon base
#### n - Type Semiconductor
- created by introducing pentavalent elements as the impurity
- impurities: antimony, arsenic & phosphorus
	![[Pasted image 20230826180738.png]]
- Donor Atoms - diffused impurities with 5 valence electrons
- free electron of the impurity have an energy level in the forbidden zone
	![[Pasted image 20230826205519.png]]
	- easier for them to absorb thermal energy and go the conduction band
	- there are a large number of carriers at room temperature
	- normally at room temp Si has 1 free electron for every 10$^{12}$ atoms
	- with doping of 1 in 10M, the carrier concentration increases by a ratio of 100,000 : 1
- majority carrier: electrons
	- minority carrier: holes
- when the 5th electron leaves the the donor atom, the atom acquires a positive charge
	![[Pasted image 20230826225919.png]]

#### p - Type Semiconductor
- created by introducing trivalent element as impurity
- impurities: boron, gallium & indium
	![[Pasted image 20230826205838.png]]
- Acceptor Atoms - diffused impurities with 3 valence electrons
- valence electrons break out of covalent bonds and fill the void created by a hole
	- then a new hole is created in the covalent bond which released the electron
	- transfer of holes from right to left
	- transfer of electron from left to right
	![[Pasted image 20230826225447.png]]
- majority carrier: holes
	- minority carrier: electrons
- when an electron occupies a void at an acceptor atom, it gains a negative charge
	![[Pasted image 20230826225943.png]]

### Semiconductor Diode
- formed by bringing n-type and p-type semiconductor together
- Depletion Region - the moment p & n are joined, electrons and holes will combine creating a with a lack of carriers near the junction
- voltage can be applied in three ways:
	1) V$_{D}$ = 0 V -> no bias
	2) V$_{D}$ > 0 V -> forward bias
	3) V$_{D}$ < 0 V -> reverse bias

#### No Applied Bias (V$_{D}$ = 0 V)
- holes in the n-type semiconductor that are in the depletion region will pass into the p-type semiconductor
- electrons in the p-type semiconductor that are in the depletion region will pass into the n-type semiconductor
	![[Pasted image 20230827004652.png]]
	![[Recording 20230827092029.webm]]
	![[Recording 20230827092305.webm]]
	![[Recording 20230827100213.webm]]

- majority carriers (electrons) of the n-type must overcome the attractive forces of the layer of positive ions
	- and also overcome the shield of negative ions in the p-type
	- can't migrate to the p-type side
- but cuz of the sheer number of carriers, a few will cross over, but it cancels out
- net flow of charge in anyone direction is zero
	![[Pasted image 20230827004704.png]]

#### Reverse-Bias Condition (V$_{D}$ < 0 V)
- external voltage is applied across the diode such that positive terminal is connected to n-type and negative terminal to p-type
- its pulls the holes in the p-side and the electrons in the n-side away from the junction
	- this causes the depletion region to widen
	![[Pasted image 20230827103343.png]]
	![[Recording 20230827102936.webm]]
- widening on the depletion makes it harder for majority charge carriers to cross across the junction
	- only minority charge carriers can pass
	- Reverse Saturation Current - very small current due to movement of minor charge carries in reverse bias

#### Forward Bias Condition (V$_{D}$ > 0 V)
- external voltage is applied across the diode such that positive terminal is connected to p-type and negative terminal to n-type
- this counter acts the barrier potential and reduces the depletion region
	- making it easier for the majority carriers to flow
	![[Pasted image 20230827111334.png]]
- as the voltage is increased, the barrier potential reduces and the current increases exponentially

#### I-V Graph for Forward and Reverse Bias
![[Pasted image 20230827111553.png]]

#### Relation b/w I$_{D}$ & I$_{S}$
- I$_{D}$ = I$_{S}$(e$^{kV/T}$ - 1)
	- I$_{D}$ -> net current flowing through the diode in forward bias
	- I$_{S}$ -> current due to minority charge carriers
	- k = 11,600 / η with η = 1 for Ge & η = 2 for Si
	- V -> voltage applied across the diode
	- T -> temperature in kelvin
- increases with increase in V like e$^{x}$ 
	![[Pasted image 20230827135832.png]]
- [[Dark - Chapter 1.pdf#page=14&selection=12,34,34,2]]

#### Zener Region
- for a sufficiently large negative voltage the current will suddenly start to increase rapidly
	- direction of current will be opposite to the direction when positive voltage is applied
- Zenner Potential (V$_{Z}$) - reverse bias potential at which the current flowing suddenly starts to increase
![[Pasted image 20230827143702.png]]
- minority charge carriers increase in number
	- eventually their kinetic energy is enough to release additional carriers from stable atoms
	- this starts a chain causing a high Avalanche Current
	- and the Avalanche Breakdown region is determined
- doping can reduce the required negative voltage for breakdown
	- if V$_{Z}$ is reduced to around -5V -> different mechanism -> Zenner Breakdown
	- strong electric fields generate carriers
- Zenner Region -> not only for low magnitude of negative voltage
- Peak Inverse Voltage (PIV) / Peak Reverse Voltage (PRV) - max reverse bias voltage that can be applied before entering the zenner region
	- PIV rating can be increased by connecting diodes in series
	- diodes can be connected in parallel to increase current carrying capacity

#### Silicon vs Germanium
- Si generally has higher PIV, current rating &  temperature range than Ge
- Si ~ 1000V ~ 200°C
	- Ge ~ 400V ~ 100°C
- η factor affects shape of the curve at low current levels
	- Ge: η = 1
	- Si: η = 2, drops to 1 at threshold potential
- Offset / Threshold / Firing potential (V$_{T}$)- potential at which the rise occurs
	- Si: V$_{T}$ = 0.7 (requires higher potential -> disadvantage)
	- Ge: V$_{T}$ = 0.3
	
	![[Pasted image 20230827144749.png]]

#### Temperature Effects
- in Si, reverse saturation current will approximately double for every increase of 10°C in temp
![[Pasted image 20230827145844.png]]
- for Ge: if  I$_{S}$ = 1 or 2 μA at 25°C, it will have leakage current of around 100μA at 100°C
	- undesirable since we want an open-circuit condition
- get bk to this: [[Dark - Chapter 1.pdf#page=17&selection=55,0,98,29]]

### Resistance Levels
- resistance will change based on the type of applied voltage

#### DC or Static Resistance
- on application of DC voltage the resistance can be found by just using R = V / I
	- resistance below the knee will be higher than the vertical section
	- resistance levels in the reverse-bias region are very high
- lower the current higher the dc resistance level

#### AC or Dynamic Resistance
- on application of sinusoidal input
- 