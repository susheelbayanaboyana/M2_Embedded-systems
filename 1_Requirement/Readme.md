
# Interfacing LED


Light Emitting Diodes or LEDs are the mostly commonly used components in many applications. They are made of semiconducting material. 
In this project, I will describe about basics of Interfacing LED with  Microcontroller.  
Needs no manual operation for switching ON and OFF. When there is a need of light 

# Identifying features

They are the most visible type of diode, that emit a fairly narrow bandwidth of either visible light at different coloured wavelengths,
 invisible infra-red light for remote controls or laser type light when a forward current is passed through them.

The “Light Emitting Diode” or LED as it is more commonly called, is basically just a specialised type of diode as they have very similar electrical characteristics to a PN junction diode.
 This means that an LED will pass current in its forward direction but block the flow of current in the reverse direction.

Light emitting diodes are made from a very thin layer of fairly heavily doped semiconductor material and depending on the semiconductor material used and the amount of doping,
 when forward biased an LED will emit a coloured light at a particular spectral wavelength.

# SWOT ANALYSIS

# Strength
Gives the users complete
control over the lighting
system, reduced electricity
consumption, and increased
sustainability

# Weakness
Traditional bulbs are cost-
effective and offer a hassle-
free installation process

# Opportunities
Rising government incentives for
energy-saving products. Rapid
urbanization and the rising need
for mobility could also largely fuel
the growth of this industry.
Scope of attracting corporate
clients is high.

# Threats
Cut throat competition
especially from traditional
lighting segemnts.
Increased cost and
complicated setup process
reduces the overall
demand for products.

# High level requirements

L.E.D (Light Emitting Diode)

I.C NE555 with Base

L.E.D (Light Emitting Diode) 5 pieces. (If using  white color then 4 Pcs)

Variable Resistance of 47 KΩ

P.C.B (Printed Circuit Board of 555 or Vero board.

# Low level Requirements

When light falls on the LDR then its resistance decreases which results in increase of the voltage at pin 2 of the IC 555.
IC 555 has got comparator inbuilt, which compares between the input voltage from pin2 and 1/3rd of the power supply voltage.
When input falls below 1/3rd then output is set high otherwise it is set low. Since in brightness, input voltage rises so we obtain
no positive voltage at output of pin 3 to drive relay or LED, besides in poor light condition we get output to energize.
