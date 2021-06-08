# AutoIgnition-Delay-for-Xylene-
Autoignition delay time is one of the fundamental combustion properties, which markedly differ for different types of commercial fuels. This property has conventionally been associated with the octane or cetane rating of a given fuel, and is generally used to assess the compatibility of the fuel with the intended end use in a reciprocating or rotary internal combustion engine. In this work, autoignition delay of xylene is calculated using the chemkin data of xylene. 
Chemkin files contains thermodynamic and species data which are converted to cantera form using python. Later, this .cti file is called using cantera and autoignition of xylene is calculated in batch reactor with mole fractions of RXYLENE: 0.00625, o2 :0.06562, Ar:0.92812'
Having the reactor pressure and temperature as the 1500 K and 8 Bar. Plot has been made between the ignition delay and the 1000/T. 

#### Libraries Used:
division, pandas, numpy, matplotlib, time, cantera

#### Programing Language
Python

#### IDE Used
Jupyter Notebook


