# JKFLIPFLOP-USING-IF-ELSE

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![WhatsApp Image 2025-11-16 at 10 40 59 PM](https://github.com/user-attachments/assets/6cbdbd72-b9a0-451d-8b8d-9c945cd8f9fb)


By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**Procedure**

/* write all the steps invloved */

**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming.
![WhatsApp Image 2025-11-16 at 10 39 10 PM](https://github.com/user-attachments/assets/7d14bb3c-9462-42f9-8e47-5ff54925b716)




Developed by:NARENDRA KRISHNAM KS RegisterNumber:25008086

**RTL LOGIC FOR FLIPFLOPS**
![WhatsApp Image 2025-11-15 at 10 16 12 PM](https://github.com/user-attachments/assets/bcf8616e-c189-409e-8670-3dcb0b4178d7)


**TIMING DIGRAMS FOR FLIP FLOPS**
![WhatsApp Image 2025-11-16 at 10 40 17 PM](https://github.com/user-attachments/assets/6b3db4b7-06e3-49c6-ab4b-b3efbc08bd58)



**RESULTS**
Thus the JK flipflop is implemented and verified.
