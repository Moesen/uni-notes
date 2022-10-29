# Basic principles
![[schematic_rocket.png]]
## Perfomance parameters
Considering the schematic above, applying equation 3.18 ![[Trajectory Dynamics#Equation 3 18|3.18]] 
leads to
$$
M \frac{dV}{dt} = mV_{e}+A_{e}(p_{e}-p_{a}) + F_{ext}
$$
The rocket thrust F comprises two contributions, from the exhaust momentum flux and the exhaust plane pressure difference:

$$F = mV_{e}+ A_{e}(p_{e}- p_{a})$$
From this equation we see, that we want $p_{e}-p_{a}=0$ as it is later shown that this will maximize $V_{e}$ (exhaust velocity)

###### Thrust at different altitudes
- Sea Level
$$F_{SL}=mV_{e}+A_{e}(p_{e}-p_{SL})$$
- At altitude *h*
$$
F_{h}= F_{SL}+A_{e}(p_{SL}-p_{h})
$$
- In vacuum when $p_{h}=0$
$$F_{0}=F_{SL}+A_{e}p_{SL}$$

#### Effective exhaust velocity
$$
V_{e}^{*} = V_{e}+ \frac{A_{e}(p_{e}-p_{a})}{m} \equiv I_{SP}g_{0}
$$
#### Specific Impulse
ISP is the specific impulse, the total impulse per uni#t propellant weight consumed, and is
given by
$$I_{SP} = \frac{I}{M_{p}g_{0}} = \frac{\int^{t}_{0}{F(t)dt}}{g_{o}\int^{0}_{t}m(t)dt}$$
whence $ISP =\frac{F}{ṁg0}$ for constant thrust and exhaust mass flow rate.

#### Mass by time with effective exhaust velocity
Equation (6.6) may be expressed in terms of $V_{e}^{∗}$ and, when this is constant, it may be integrated over the duration of rocket motor firing giving
$$
\Delta V = V_{b}-V_{o}=V_{e}^{*} \ln \left\{\frac{M_{0}}{M_{b}}\right\} + \intop_{0}^{t_{b}} \frac{F_{ext}}{M}dt
$$
Which gives
$$
\Delta V = V_{e} \ln R
$$
Where the *mass ration* $R$ is given by
$$
R = \frac{M_{0}}{M_{b}}
$$
## Nozzle flows
We analyse the flow through a convergent-divergent nozzle, downstream from the combustion chamber and as illustrated in Figure below,
![[nozzle_flow.png]]
with the aid of the following simplifying assumptions:
- The combustion products are homogeneous and of constant composition.
- The products at temperature T and molecular weight W obey the perfect gas law relating pressure p and density ρ:
$$p = \rho T (\frac{R_{0}}{W} )$$
where $R_{0}$ is the universal gas constant.
- The specific heat of the mixture is invariant with temperature and pressure.
- The flow is one-dimensional, steady and isentropic.

#### Conservation equation for mass and energy
$$
m = \rho VA
$$
$$
\frac{1}{2}V^{2}+C_{p}T = constant = \frac{1}{2}V_{c}^{2}+ C_{p}T_{c}
$$
where the subscript c denotes the initial state.
For an adiabatic flow process we have
$$
p \rho^{-\gamma} = constant
$$
$$
\frac{T}{T_{c}} = \left(\frac{\rho}{\rho_{c}}\right)^{\gamma-1} = \left(\frac{p}{p_{c}}\right)^{\frac{\gamma-1}{\gamma}}
$$
If the initial velocity V_c is negligibly small, then
$$
\frac{m}{A} = 
\left\{  
	\frac{	2\gamma}{\gamma-1} p_{c}\rho_{c}(\frac{p}{p_{c}})^{\frac{2}{\gamma}} 
	\left[
		1 - (\frac{p}{p_{c}})^\frac{\gamma-1}{\gamma}
	\right]
\right\}^\frac{1}{2}
$$
*Clearly* equation above exhibits a maximum value for (ṁ/A)corresponding to a critical throat condition, subscript *t*, at which


-----
### Rocket motors
Cannot really throttle, too low flow rate, and it goes out.

### Formulas
$$
\begin{flalign}
	&&\Delta V = V_{e}\ln{R}\\
	&&M \frac{dV}{dt} = m V_{e}+ A_{e} (p_{e}- p_{a} \\
	&&F = mV_{e}+ A_{e}(P_{e}- p_{a}) \\
	&Thrust Sea: &F_{SL} = mV_{e}+ A_{e}(p_{e}- p_{SL})	\\
	&Alt h: &F_{h}= F_{SL} + A_{e}(p_{SL}-p_{h})	 \\
	&Vac: &F_{0}= F_{SL}+A_{e} p_{SL}\\
	&&I = \int_{start}^{stop}  \tilde{F} dt \\
	&&I = M \cdot u \\
	&&F = I = m u_{e}\\
	&&I_{SP} = \frac{I}{\sum M_{p} g_{0}}\\
\end{flalign}
$$