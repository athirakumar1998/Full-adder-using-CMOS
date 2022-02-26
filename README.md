# FULL ADDER USING CMOS
# Abstract
This paper proposes the design of a Full adder using
28 conventional cmos transistors , presents a full adder cell having
reduced power and delay.This adder uses regular cmos structures
(pull up and pull down networks) with pmos and nmos as a part
of a complementary network.The full adder is designed in 0.28um
technology and the advantage of this design is its high noise
margin and thus reliable operation at low voltage.The layout
of the cmos gate was also simplified due to the complementary
transistor pairs.It’s advantages include robustness and scalability
at low supply voltages.
# Introduction
Circuit realization for low power and low
area has become an important issue with the growth
of integrated circuit towards very high integration
density and high operating frequencies. The full
adder circuit adds three one-bit binary numbers
(Cin, A, B) and outputs two one-bit binary
numbers, a sum (SUM) and a carry (COUT). Due
to the important role played by Full adder in
various arithmetic units, optimized design of Full
adder to achieve low power, small size and delay is
needed. The primary concern to design Full adder
is to obtain low power consumption and delay in
critical path and full output swing with low number
of transistors to implement it.
The relation between the
inputs and outputs are given as
 ;sum = A ⊕ B ⊕ C ; 
carry = Cout = AB + BC + AC ;
Full Adder performs the addition bit by bit with carry input and
provides output with carry output. The carry output becomes
the carry input for next input combination.The normal full
adder operation will give the above mentioned equations.But
it requires more number of transistors and area to realise.So
the inverted form of carry output obtained is considering as an
input component thereby obtaining the sum output equation
that depends on four different varioble inputs.  Then the
above equations can be altered as
 ;sum = ABC + (A + B + C)Co¯ut ;
Cout = AB + C(A + B) ;
These outputs can be implemented using the 0.28um cmos
technology which is cost effective and used for low power
applications. Here the primary concern to design Full adder is
to obtain low power consumption and delay in critical path and
full output swing with low number of transistors to implement it.
# Tools used
* Synopsis custom compiler
* Synopsis prime wave
* Synopsys 28nm PDK
# FULL ADDER 

* Truth table
 
 ![tt](https://user-images.githubusercontent.com/100459907/155833551-b1218065-05b8-4c54-bdd5-cc293435cc78.JPG)
 * Reference Design

![hack1](https://user-images.githubusercontent.com/100459907/155833840-cf638074-aeb3-4eab-938e-e18b9acdc3c8.JPG)
* Reference Waveforms

![hack2](https://user-images.githubusercontent.com/100459907/155833864-a138d788-9d56-4f91-b8d0-f88a7e7d12b4.JPG)
# Full adder schematic diagram
![p3](https://user-images.githubusercontent.com/100459907/155837369-fa4d56dc-b30b-4cbd-bd3b-50e5a4f7dab1.JPG)
# Full adder input specifications
* Input A 
![A](https://user-images.githubusercontent.com/100459907/155837411-5576eaff-bb09-42a1-8de3-774144de2872.JPG)
* Input B 
![B](https://user-images.githubusercontent.com/100459907/155837441-ec1e7016-62e7-4896-b1c0-43fc768d3edf.JPG)
* Input C
![C](https://user-images.githubusercontent.com/100459907/155837461-1d79684a-47dc-4657-87ae-72c933b06715.JPG)
# Full adder symbol
![Capture](https://user-images.githubusercontent.com/100459907/155837475-234c2b22-ed6a-43d7-bd19-ea2cf7193292.JPG)












