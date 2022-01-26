# Contents
- [General characteristics](#general)
- [Structure](#structure)
- [Article content](#content)
- [Context](#context)
- [Comments](#comments)
- [Lecture comments](#lecture-comments)
- [References](#references)
- [Questions](#questions)

# General
#### Author(s)
- Katharina Krischer - professor of physics at the Technische Universität München, Germany
- Konrad Schönleber - researcher in the group of Prof. Krischer which he joined after graduating in physics from the Technische Universität München

#### First two sentences of the introduction
It is a central challenge for humanity to convert its energy infrastructure into a sustainable one. Sustainable energy supply means that the energy needs of the present are met without restricting the ability of future generations to satisfy their needs, as defined in the ‘Agenda 21’ by the United Nations.
#### Last two sentences of the introduction
This evaluation is a complex process and requires a detailed understanding of the energy supply technologies and the processes involved. It is the goal of this book to provide such a detailed understanding on the physical level for the important processes involved in the generation of electrical energy.
#### (Notable) figures
- Figure 2 - Energy flow through a converter from primary to final energy (left circle) and a converter from final to net energy (right circle). The widths of the arrows are proportional representations of the amounts of energy in the respective forms.
  - ![image](https://user-images.githubusercontent.com/78508062/151052980-680880f5-3a62-48de-b9f9-8e3a92f3f621.png)
- Figure 5 - Energy and exergy flow through an ideal converter (left) and a realistic converter where irreversibilities reduce the amount of work that can be performed (right). The width of the arrows is proportional to the amount of energy in the respective forms.
  - ![image](https://user-images.githubusercontent.com/78508062/151059803-d3a8acec-d6fe-44d8-8c02-df6b8570dbfa.png)

#### Publication
- [ ] peer-reviewed

De Gruyter.
#### Article type
Tertiary literature, chapter of a textbook.

# Structure
- Terms and definitions.
    - Primary energy.
    - Final energy.
    - Net power.
  - Units.
  - Example: energy consumption and production.
- Energy conversion processes.
  - Exergy.
  - Conversion efficiency.
  - Example: heating of a room.

# Equations
- Consider a heat engine working periodically between two fixed temperature levels, _T_<sub>h</sub> > _T_<sub>c</sub>. An amount of heat _Q_ provided isothermally at a temperature _T_ in a reversible process is exactly given by _Q = ST_, with _S_ being the change in the entropy in the thermodynamic system which the heat enters. 
- This increase of entropy in the system is transported by the heat itself, _i.e._ the heat input is accompanied by an entropy input of _S_. The input heat _Q_<sub>in</sub> at the higher temperature level of the heat engine _T_<sub>h</sub> thus takes the value _Q_<sub>in</sub> = _ST_<sub>h</sub>. 
- In the assumed reversible processes the entropy in the heat engine is conserved in all state changes not involving heat transfers. This means that the same amount of entropy that enters the heat engine has to be discarded in each cycle. To achieve this, an amount of heat _Q_<sub>out</sub> = _ST_<sub>c</sub> has to be rejected at the lower temperature level. Thus, the maximal mechanical energy output _E_<sub>mech,out</sub> by a periodically working heat engine is given by
  - _E_<sub>mech,out</sub> = _Q_<sub>in</sub> - _Q_<sub>out</sub> = Δ _S_(_T_<sub>h</sub> - _T_<sub>c</sub>)
- The maximal efficiency of the heat engine then correspondingly amounts to
  - ![\begin{align*}
\eta &= \frac{E_{mech,out}}{Q_{in}} - \frac{\Delta S(T_h - T_c)}{\Delta ST_h} &=1 -\frac{T_c}{T_h} 
\end{align*}
](https://render.githubusercontent.com/render/math?math=%5Cdisplaystyle+%5Cbegin%7Balign%2A%7D%0A%5Ceta+%26%3D+%5Cfrac%7BE_%7Bmech%2Cout%7D%7D%7BQ_%7Bin%7D%7D+-+%5Cfrac%7B%5CDelta+S%28T_h+-+T_c%29%7D%7B%5CDelta+ST_h%7D+%26%3D1+-%5Cfrac%7BT_c%7D%7BT_h%7D+%0A%5Cend%7Balign%2A%7D%0A)
- For a waterwheel when an amount m of water is added at the inlet at a height of _h_<sub>in</sub>, the energy input _E_<sub>in</sub> is the potential energy in the gravitational field of the earth, _i.e._ _E_<sub>in</sub> = _mgh_<sub>in</sub>. 
- The amount _m_ of water then crosses the waterwheel and is discarded at the outlet at height _h_<sub>out</sub>, a process associated with an energy loss of _E_<sub>loss</sub> = _mgh_<sub>out</sub>.
- In a perfect process, the maximal amount of energy extractable from the waterwheel _E_<sub>out</sub> is thus given by _E_<sub>out</sub> = _mg_(_h_<sub>in</sub> - _h_<sub>out</sub>), and the efficiency of the process is consequently given by
  - ![\begin{align*}
\eta &= \frac{E_{out}}{E_{in}} &= \frac {mg(h_{in}-h_{out})}{mgh_{in}} &=1- \frac{h_{out}}{h_{in}} \end{align*}
](https://render.githubusercontent.com/render/math?math=%5Cdisplaystyle+%5Cbegin%7Balign%2A%7D%0A%5Ceta+%26%3D+%5Cfrac%7BE_%7Bout%7D%7D%7BE_%7Bin%7D%7D+%26%3D+%5Cfrac+%7Bmg%28h_%7Bin%7D-h_%7Bout%7D%29%7D%7Bmgh_%7Bin%7D%7D+%26%3D1-+%5Cfrac%7Bh_%7Bout%7D%7D%7Bh_%7Bin%7D%7D+%5Cend%7Balign%2A%7D%0A)
- The second law of thermodynamics states that maximal extractable work in general is not identical with the amount of energy itself. The part of the energy that can be converted into useful work is called exergy or availability, Φ, the rest is called anergy, _A_. Any amount of energy, _E_, can thus be
decomposed into these two contributions:
  - _E = Φ + A_
    - _E_: amount of energy
    - _Φ_: exergy or availability, the part of energy that can be converted into useful work
    - _A_: anergy, the part of energy that cannot be converted into useful work
- Energy of first-law efficiency
  - ![\begin{align*}
\eta_1 &= \frac{E_{out}}{E_{in}}  \end{align*}
](https://render.githubusercontent.com/render/math?math=%5Cdisplaystyle+%5Cbegin%7Balign%2A%7D%0A%5Ceta_1+%26%3D+%5Cfrac%7BE_%7Bout%7D%7D%7BE_%7Bin%7D%7D++%5Cend%7Balign%2A%7D%0A)
  - For the conversion process of an amount of energy in one form, _E_<sub>in</sub>, into energy in another desired form, _E_<sub>out</sub>, an efficiency 1 can be given.
- Exergy or second-law efficiency and efficiency
  - ![\begin{align*}
\eta_2 &= \frac{\phi_{out}}{\phi_{in}}  \end{align*}
](https://render.githubusercontent.com/render/math?math=%5Cdisplaystyle+%5Cbegin%7Balign%2A%7D%0A%5Ceta_2+%26%3D+%5Cfrac%7B%5Cphi_%7Bout%7D%7D%7B%5Cphi_%7Bin%7D%7D++%5Cend%7Balign%2A%7D%0A)
  - _Φ_: exergy or availability, the part of energy that can be converted into useful work
- During direct electrical heating no energy is converted into an undesired form as all the electrical input energy is converted to heat leading to a first law efficiency of
  - ![\begin{align*}
\eta_1 &= \frac{Q_{out}}{\E_{(el) in}}  &=1\end{align*}
](https://render.githubusercontent.com/render/math?math=%5Cdisplaystyle+%5Cbegin%7Balign%2A%7D%0A%5Ceta_1+%26%3D+%5Cfrac%7BQ_%7Bout%7D%7D%7B%5CE_%7B%28el%29+in%7D%7D++%26%3D1%5Cend%7Balign%2A%7D%0A)

# Article content
## Main concepts
## Supporting concepts
#### Primary power
The total amount of energy stored in the different natural energy sources, such as fossil fuels, is called primary energy. Primary energy cannot be used directly but has to be refined in a process that takes away a part of the energy. The end product of the refinery process is the final energy. Refinery first means the refinery process necessary to produce energy in the form of directly usable fuels, such as diesel or gasoline, from natural sources such as crude oil. More importantly, another process that can also be seen as a refining of energy is the conversion of primary energy carriers, for example coal, gas, or uranium, into electrical energy as final energy. It is the latter process that accounts for most of the difference between primary and final energy.

#### Final energy
#### Net power

## Summary of key points
- In the discussion of energy consumption, three terms with different meanings are frequently used: primary energy, final energy, and net energy. These terms are also synonymously applied to powers instead of energies, _i.e._ primary power, final power, and net power.
## Abbreviations

# Context
## Significance

# Comments

# Lecture comments
- What is energy?
  - Fundamentally, energy is something that can be stored within systems in various forms and can be converted from one form to the other.
  - However, providing energy sustainably means ”energy needs of the present are met without restricting the ability of future generations to satisfy their needs” [^1], under three conditions:
    - they should not be consumed,
    - they should not lead to emissions of environmental pollutants,
    - they should not lead to negative impacts on health and social justice.
  - Most of the energy sources today voilate all three conditions – fossil based.
  - Today most of the sustainable energy sources violate at least one of the three conditions.
- Energy analysis.
  - Energy analysis is based on the first law of thermodynamics and its statement of energy conservation.
  - Primary energy – energy in its natural form that hasn’t undergone any transformational processes.
  - Final energy – energy available at the point of use after undergoing one or many transformation processes.
  - Useful or net energy – energy available in the form of final application for end-use.
  - ![image](https://user-images.githubusercontent.com/78508062/150938831-3904b51d-cfbb-4c8f-b7a3-56ee76eaf080.png)
  - ![image](https://user-images.githubusercontent.com/78508062/150939172-88308d6a-427a-4eb9-8ac5-2d626acb4263.png)
  - Indicators:
    - energy intensity,
    - energy efficiency,
    - emissions intensity of energy.
- Exergy/availability.
  - While quantities of energy allow for bookkeeping – based on the first law of thermodynamics, exergy involves the quality of energy and its degradation during energy conversion.
  - Exergy analysis is based on the second law of thermodynamics.
  - Exergy is a property that enables us to determine the useful work potential of a given amount of energy at a given state (dead state).
  - ![image](https://user-images.githubusercontent.com/78508062/150939942-b497fdda-75e0-4ec2-a586-bdfb17fbd3a8.png)
- Irreversibility.
  - Irreversibility is the difference between reversible work and useful work.
    - _I_ = _W_<sub>r</sub> - _W_<sub>u</sub>
      - _I_: irreversibility
      - _W_<sub>r</sub>: reversible work
      - _W_<sub>u</sub>: useful work
  - Reversible work is the maximum useful work that can be produced (or the minimum work consumed) as a system undergoes a process between the specified initial and final states.
  - Difference between actual work and surround work is useful work.
    - _W_<sub>u</sub> = _W_ - _W_<sub>s</sub>
      - _W_: actual work
      - _W_<sub>s</sub>: reversible work
      - _W_<sub>u</sub>: useful work
  - ![image](https://user-images.githubusercontent.com/78508062/150942786-28ffff0d-4842-4df2-8662-52f1ef85a3c7.png)
  - When _a_ expands inside a cylinder to push a piston, it has to work against the atmospheric pressure _P_<sub>0</sub>. This work is irreversible and cannot be recovered and utilised and it called surrounding work.
    - _W_<sub>surroundings</sub> = _P_<sub>0</sub>(_V_<sub>2</sub> - _V_<sub>1</sub>).
      - _W_<sub>surroundings</sub>: surrounding work
      - _P_<sub>0</sub>: pressure of the surroundings
      - _V_<sub>2</sub> - _V_<sub>1</sub>: volume change of the system
- Exergy.
  - Exergy associated with kinetic energy.
    - Kinetic energy can be converted to work entirely regardless of its surrounding – exergy of kinetic energy equals the kinetic energy itself.
  - Exergy associated with potential energy.
    - Similarly potential energy can also be converted to work entirely regardless of its surrounding – which equals to kinetic energy itself.
  - Exergy associated with internal energy.
    - In a stationary compressible system at dead state (P0, T0), there is only internal energy.
    - When it undergoes a reversible process from initial state (P,T) to dead state (P0, T0) the useful work delivered during this process is the exergy of the system at its initial state, which equals the exergy of the internal energy of the system.
  - Example:
    - what is the available power at a wind turbine with a rotor radius of five metres, if the average wind velocity at STC is 25 m/s?
    - a perfect wind turbine will bring the air to a dead state (complete stop) by capturing all the energy in the air
    - kinetic energy equals exergy
      - _x_ = _v_<sup>2</sup> * 0.5 = 312 * 5 Joules per kilogramme
    - quantity of air passing through the rotor over time
      - _m_ = ρ_Av_ = ρ * (π_r_<sup>2</sup> * 0.5) * _v_
        - _m_ = 1 * 18 * 0.5(3 * 14 (5)<sup>2</sup>) * 25 = 1157 * 8 kilogrammes per second
    - available power
      - _w_ = _xm_ = 312 * 5(1157 * 8) = 361 kiloWatt

# References
## Most cited reference(s)
## Interesting-looking reference(s)

# Questions
## Before reading
## During reading
## After reading
