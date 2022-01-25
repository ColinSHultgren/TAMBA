# Contents
- [General characteristics](#general)
- [Structure](#structure)
- [Article content](#content)
- [Context](#context)
- [Comments](#comments)
- [Lecture comments](#lecture-comments)
- [References](#references)
- [Questions](#questions)
- [Zettels](#zettels)

# General
#### Author(s)
- [Ibrahim Dinçer](https://scholar.google.com/citations?user=mLx9ZO0AAAAJ&hl=en) - University of Ontario Institute of Technology
- [Marc A. Rosen](https://scholar.google.ca/citations?user=gWt3wuUAAAAJ&hl=en) - Professor, University of Ontario Institute of Technology

#### Abstract
In this chapter, theoretical and practical aspects of thermodynamics most relevant to energy and exergy analyses are described. Mass, energy, entropy, and exergy balances are discussed. The exergy of systems and flows is explained, as is exergy destruction.

Exergy analysis is a thermodynamic analysis technique based on the Second Law of Thermodynamics (SLT), which provides an alternative and illuminating means of assessing and comparing processes and systems rationally and meaningfully. Exergy analysis can assist in improving and optimising designs. 

The chapter reviews fundamental principles and such related issues as reference-environment selection, efficiency definition, and material properties acquisition. General implications of exergy analysis results are discussed, and a step-by-step procedure for energy and exergy analyses is given. Exergy nomenclature is described.

#### Key-words
- exergy
- exergy analysis
- energy analysis
- exergy consumption
- exergy balance
- reference environment
- efficiency
- exergy property

#### First two sentences of the introduction
Exergy analysis is a thermodynamic analysis technique based on the SLT, which provides an alternative and illuminating means of assessing and comparing processes and systems rationally and meaningfully. In particular, exergy analysis yields efficiencies that provide a true measure of how nearly actual performance approaches the ideal, and identifies more clearly than energy analysis the causes and locations of thermodynamic losses.

#### Last two sentences of the introduction
Increasing application and recognition of the usefulness of exergy methods by those in industry, government, and academia has been observed in recent years. Exergy has also become increasingly used internationally. 

#### (Notable) figures
#### Publication
- [ ] peer-reviewed

Elsevier.
#### Article type
Tertiary literature, textbook.

# Structure
- Introduction.
- Why energy and exergy analyses?
- Nomenclature.
- Balances for mass, energy, and entropy.
  - Conceptual balances.
  - Detailed balances.
- Exergy of systems and flows.
  - Exergy of a closed system.
  - Exergy of flows:
    - matter flow,
    - thermal energy,
    - work,
    - electricity.
- Exergy consumption.
- Exergy balance.
- Reference environment.
  - Theoretical characteristics of the reference environment.
  - Models for the reference environment.
- Efficiencies and other measures of merti.
- Procedure for energy and exergy analyses.
- Energy and exergy properties.
- Implications of results of exergy analyses.
- Closing remarks.

# Article content
## Main concepts
#### Exergy analysis
Technique based on the second law of thermodynamics to assess and compare processes and systems regarding their efficiencies. Exergy associated with an energy quantity is a quantitative assessment of its usefulness or quality. Although energy cannot be destroyed, it can be degraded.

## Supporting concepts
#### Efficiencies
Ratios of energy quantities, used to assess and compare various systems.

#### Negentropy
A quantity defined such that the negentropy consumption during a process is equal to the negative of the entropy creation. Its value is not defined, but is a measure of order.

## Summary of key points
## Abbreviations
|abr|abbreviation|
|---|------------|
|FLT|first law of thermodynamics|
|HHV|higher heat value|
|SLT|second law of thermodynamics|

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
    - In a stationary compressible system at dead state (P<sub>0</sub>, T<sub>0</sub>), there is only internal energy.
    - When it undergoes a reversible process from initial state (P,T) to dead state (P<sub>0</sub>, T<sub>0</sub>) the useful work delivered during this process is the exergy of the system at its initial state, which equals the exergy of the internal energy of the system.
  - Example:
    - what is the available power at a wind turbine with a rotor radius of five metres, if the average wind velocity at STC is 25 m/s?
    - a perfect wind turbine will bring the air to a dead state (complete stop) by capturing all the energy in the air
    - kinetic energy equals exergy
      - _x_ = _v_<sup>2</sup> * 0.5 = 312 * 5 Joules per kilogramme
    - quantity of air passing through the rotor over time
      - _m_ = ρ _Av_ = ρ * (π _r_<sup>2</sup> * 0.5) * _v_
        - _m_ = 1 * 18 * 0.5(3 * 14 (5)<sup>2</sup>) * 25 = 1157 * 8 kilogrammes per second
    - available power
      - _w_ = _xm_ = 312 * 5(1157 * 8) = 361 kiloWatt

# References
## Most cited reference(s)
## Interesting-looking reference(s)

# Questions
- Explain why exergy analysis has become a major topic in many thermodynamics courses and why increasing numbers of people use it in the analysis of energy systems.
- Exergy analysis allows the determination of the upper limits of system efficiency and quantification of the causes of degradation of system performance. Can similar results be obtained using an energy analysis?
- Define the following terms and explain, where appropriate, their differences: exergy, available energy, availability, work capability, essergy, exergy consumption, irreversibility, lost work, dissipated work, dissipation, exergy destruction, and recovered exergy.
- Carry out research to find out who invented the word “exergy” and when. Why is the term “exergy” more commonly used than “availability”?
- Investigate the literature to identify the various symbols used for exergy, closed system exergy, flow exergy, and irreversibility. Are there any standard or commonly accepted symbols for these terms? 
- What is the difference between closed system exergy and flow exergy? Express flow exergy in terms of closed system exergy.
- The exergy of kinetic and potential energy are equal to the kinetic and potential energy, respectively. Consequently, some people argue that an exergy analysis involving a wind turbine or a hydroelectric power plant is meaningless. Do you agree? Explain.
- Is there any relationship between the exergy of heat transfer and work output for a Carnot heat engine? Explain.
- Is the statement “the exergy of work is equal to work” always correct? Explain. 
- Write mass, energy, entropy, and exergy balances for the following devices: 
  - an adiabatic steam turbine, 
  - an air compressor with heat loss from the air to the surroundings, 
  - an adiabatic nozzle, and 
  - a diffuser with heat loss to the surroundings.
- Why have several classes of reference-environment models been proposed?
- Some researchers argue that “efficiency should be used only after it is clearly defined.” Do you agree? Explain.
- What is the difference between energy and exergy efficiency? Define both for an adiabatic turbine.
- Some researchers consider the “isentropic efficiency” a type of “first-law adiabatic efficiency” even though isentropic is a term associated with the SLT. What is your opinion?
- One person claims that the exergy efficiency of a system is always greater than its energy efficiency while another person claims the opposite. Which person is correct? Explain with examples.
- Define each of the following efficiencies for a compressor and explain under which conditions they should be used: 
  - isentropic efficiency, 
  - isothermal efficiency, and 
  - exergy efficiency.
- An engineer wants to express the performance of a hydraulic turbine using an isentropic efficiency, in terms of enthalpies. Is this reasonable? Explain with examples. Can you recommend better alternatives?
- How do you define and express the exergy of a fuel? 
- Is there any relationship between the exergy of a fuel and its lower or higher heating value?
- A student claims that the thermal and exergy efficiencies of a fossil-fuel power plant are very close to each other. Do you agree? Explain.
- How can one use the results of an exergy analysis to improve system efficiency? 
- Can exergy analysis be used in the design of a thermal system? Explain.
- Can exergy analysis be used in the optimisation of a thermal system? Explain.
- An exergy analysis of the components of a system indicates that the exergy efficiency of component A is much smaller than that of component B. Does this mean that the priority for investing resources should be improving the performance of component A rather than component B?
