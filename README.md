java c
ECSE 304-335
Microelectronics
Midterm Examination
Design Specifications - Please Complete this Page First
This exam is unique to each student.  On this page you will derive your speifications that you be required to work with for some of the problems below.
To recieve a grade for Question 2 and 3, this section must be completed correctly. Fill in the table with your 9-digital ID number:
(1)
(2)
(3)
(4)
(5)
(6)
(7)
(8)
(9)









Now, the 9th digit will be used to compute the power supply voltage VCC and the 8th digit will be used to specify the voltage gain, AV. Please perform. the following computation:

List the results in the table below:
V CC
AV
vo,Q



Question 1:
Design the MOS circuit shown above to obtain a DC voltage of +0.2 V at the drains of Q1 and Q2 when vG1= vG2= 0 V. Operate all transistors with an overdrive voltage equal to 0.25 V and assume the current bias levels shown in the diagram.
Assume that for the process technology in which the circuit is fabricated, Vtn = 0.4 V and µnCox = 200 µA/V2. Neglect channel-length modulation.
(a) Determine the values of the reference current resistor, R.
[2 points]
(b) Determine the values of the drain current iD1 for Q1.
[1 points]
(c) Determine the values of RD.
[1 points]
(d) Determine the W/L ratios of Q1, Q2, Q3, and Q4.
[4 points]
(e) What is the lowest input common-mode voltage level for your design?  [1 points]
(f) What is the maximum input common-mode voltage level for your design?  [1 points]
Question 2:
Through the separate steps below, you are to provide the design details for
constructing a pnp CE amplifier with an emitter degenerate resistor such that its
output is set to 0.7*VCC and has a voltage gain with a magnitude equal to that related to your ID number (found above).  The circuit is to be powered with a single power
supply having a level of VCC. One side of the emitter degenerate resistor is to be connected to VCC the other to the emitter terminal of the pnp transistor.
An npn transistor-based current mirror is to be used to supply the bias current
required by your CE amplifier so that the output voltage bias point is realized. Use a resistor to supply the reference current to the current mirror circuit.
Assume a bipolar process with npn and pnp devices described by |VA | = 100 V, β =
100 and IS = 2x10-15 A. Use your ID # generated values for VCC and Av.
(a) Provide a schematic of your amplifier design; identify all unknown components with unique names.
[1 point]
(b) Find an expression for the overall voltage gain of the CE amplifier in terms of the small- signal transistor parameters and any other circuit components. Sh代 写ECSE 304-335 Microelectronics Midterm ExaminationR
代做程序编程语言ow all work and any assumptions used to simplify the expressions.
[3 points]
(c) Convert the voltage gain expression found in part (b) in terms of the physically controllable parameters such as bias voltage levels, components, etc.
[2 points]
(d) Select all biasing levels and component values such that the output node voltage is set to0.7*VCC and that the amplifier has an input-output voltage gain with a magnitude of Av V/V. Identify what are your design independent variables and which are dependent. Use your ID # generated values for VDD and Av.
[3 points]
(e) Show that all transistors are operating in their active region.  [1 points]
Question 3:
For the circuit that you designed in Question 2, answer the following questions:
(a) Enter the circuit into a SPICE simulation tool and provide the input that you entered (Spice Description Langauge or schematic) below. Identify your simulation tool. Identify the input and output nodes using labels IN and OUT, respectively. Use the values that were calculated in
Question 2.  The input and output generated by Spice must be provided for grading.  [2 point]
(b) Write the model statements for the npn and pnp transistors based on the parameters listed in Question 2 above.
[1 point](c) Compute the DC bias points of the circuit and identify the voltage at the base, emitter and collector terminals of the main amplifying transistor.  What SPICE command did you use to extract these results? What mode of operation is the amplifying transistor operating in?
[2 point]
(d) In your design problem of Question 2, the transistor was assumed to be operating in the
active region and the output collector voltage was to be set to vo,Q.  If this is not achieved, what can you do to adjust this output level?  Perform. this operation and show all SPICE steps used to achieve your results. The data generated by LTspice is what will be graded.
[2 point](e) Now that your circuit is biased at the correct level, let us compute the low-frequency small- signal AC gain of the circuit from the base to the collector.  What is the SPICE command that should be used and what was added to complete the analysis.
[2 point]
(f) To confirm that the design is indeed operating as a voltage amplifier, consider injecting a time-vary sinusoidal signal at the base with an amplitude of 1 mV and frequency of 1 kHz. Provide a plot of the output signal over 3 ms and re-confirm that the voltage gain is indeed greater than your desided Av. If it is not, can you suggest a reason why it is not.
To avoid strange transient plot results, it is always a good idea to disable the plot compression routine by including the following option statement:
.option plotwinsize=0
[1 point]

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
