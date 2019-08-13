# Better Unit System

## The need for a new unit system
Many awesome unit systems for describing physical quantities already exist, but they all have their disadvantages<sup>[Citation needed](https://xkcd.com/285/)</sup>.

As the most important example, [the SI system was ruined in the 2019 redefinition](https://en.wikipedia.org/wiki/2019_redefinition_of_the_SI_base_units). Nothing wrong with setting natural constants to specific values, but if you want to do thath, you don't take an approximation of a measured value from the old version of the system. You give the constant some sensible value, like exactly 1 of some unit.

Another important example, and a big inspiration for the present proposal is the [FFF system](https://en.wikipedia.org/wiki/FFF_system). However, it is quite limited and doesn't seem to have any official organization behind it for extensions and revisions. Thus, it is stagnant.

In addition, there are many great units that are not part of any consistent system, most importantly the [banana equivalent dose or BED](https://en.wikipedia.org/wiki/Banana_equivalent_dose).

For these reasons, and any you might add, the **Better Unit System** is hereby presented.

## The base units
|Name     |Symbol     |Measure                                             |Value in SI and/or other                                                                              |
|---------|-----------|----------------------------------------------------|------------------------------------------------------------------------------------------------------|
|boltzmann|z          |entropy                                             |1.380649×10<sup>-23</sup> m<sup>2</sup>⋅kg⋅s<sup>-2</sup>⋅K<sup>-1</sup>                              |
|bed      |d          |radiation exposure / speed squared (for some reason)|9.82×10<sup>-8</sup> m<sup>2</sup>⋅s<sup>-2</sup>                                                     |
|barrel   |e          |volume                                              |approximately 0.15899 m<sup>3</sup>                                                                  |
|bar      |r          |pressure                                            |10<sup>5</sup> kg⋅m<sup>-1</sup>⋅s<sup>-2</sup>                                                       |
|bermit   |frg        |permittivity                                        |approximately 8.8541878128×10<sup>-12</sup> s<sup>4</sup>⋅A<sup>2</sup>⋅m<sup>-3</sup>⋅kg<sup>-1</sup>|
|bunch    |h          |amount of substance                                 |approximately 1.66053917×10<sup>-9</sup> mol, exactly one billiard particles                          |
|bulb     |l          |luminous efficacy                                   |10.4 cd⋅s<sup>3</sup>⋅sr⋅kg<sup>-1</sup>⋅m<sup>-2</sup>                                               |
|borogove |g          |mimsiness                                           |just enough for brillig                                                                               |
|bulge    |owo        |arousal                                             |What's this?                                                                                          |

## Some derived units
The first step must be defining units corresponding to the dimensions of each SI base unit, just to show all the sceptics that this is an actually functional system.

We will start with length. It is simply the cubic root of volume, so the unit has the form e<sup>1/3</sup>. This unit is called barefoot (rft). Converted to SI, 1 rft ≈ 0.54174 m.

Next comes mass. Naturally, we get one by multiplying pressure with volume and dividing by radiation exposure. That is, the value for a unit of mass is r⋅e⋅d<sup>-1</sup>. According to a fine Middle Eastern tradition, the unit shall be named batman, with symbol t. In SI, 1 t ≈ 162000000000 kg. An average human weighs about 0.5 nt (nanobatmans).

Following similar logic, the unit for time has the form e<sup>1/3</sup>⋅d<sup>-1/2</sup>. It is called bittoolong (ttl). 1 ttl ≈ 1728 s, or about half an hour.

The unit for electrical current is called battery (y). No, it doesn't make much sense, but battery is a good name for an electrical unit and *someone* decided that the electrical base unit in SI would be that of current instead of voltage. Blame them, not me! Anygays, 1 y = 1 frg<sup>1/2</sup>⋅ttl<sup>-2</sup>⋅e<sup>1/2</sup>⋅t<sup>1/2</sup> = 1 frg<sup>1/2</sup>⋅e<sup>5/6</sup>⋅d<sup>1/2</sup>⋅r<sup>1/2</sup> ≈ 63.695 nA.

Temperature is a funny one, because it needs two different units, one absolute and one relative, similarly to Kelvin/Celsius and Fahrenheit/~~The thing whose name I never remember because who the fuck would ever need that~~Rankine. The absolute unit is called burn (°U). 1 °U = 1 r⋅e⋅z<sup>-1</sup> ≈ 1.1516×10<sup>27</sup> K. The relative unit, boil (°O) has the same unit size than degrees burn, but is shifted to have its zero at the point where helium-3 becomes superfluid, below which the so called [boojum phenomenon](https://en.wikipedia.org/wiki/Boojum_(superfluidity)) can be observed. Thus, a temperature of 0 °O ≈ 2.163×10<sup>-30</sup> °U and a temperature of 1 °O ≈ 1 °U.

Defining a unit for luminous intensity would be trivial, but who cares? Let's move on to more interesting things to show that the possibilities of the Better Unit System surpass those of the SI.

In cognitive neuroscience, the emotional state of an individual can be described in two dimensions: arousal and valence. We already have a unit for arousal, so one should be derived for valence. It is known that mimsiness is the product of flimsiness and miserability. Flimsiness is the reciprocal of strength (measured in units of pressure) and miserability is the reciprocal of positive valence. Thus, the unit of valence, known as bigsmile (sm), is defined. 1 sm = g<sup>-1</sup>⋅r<sup>-1</sup>.

## Values for some physical constants
Boltzmann constant: 1 z (Duh!)

Vacuum permittivity: 1 frg (Doy!)

Speed of light: approximately 957000000000 d<sup>1/2</sup> = 957 Grft/ttl (gigabarefoots per bittoolong)

Typical human body temperature: approximately 2.7×10<sup>-25</sup> °U

Hagedorn temperature (where all hadronic matter breaks down): approximately 1.7×10<sup>-15</sup> °U

Viscosity of whole milk in room temperature: approximately 12 prttl (picobar-bitstoolong)

## Disclaimers
The Better Unit System is subject to arbitrary revisions from any self-appointed member of the Better Committee for Weights and Measures. It is licensed under the [*Do What The Fuck You Want To Public License* (WTFPL)](http://www.wtfpl.net/). 
