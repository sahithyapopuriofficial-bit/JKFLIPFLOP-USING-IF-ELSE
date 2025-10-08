# JK FLIPFLOP-USING-IF-ELSE

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
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**Procedure**

1.Go to quartus software.

2.Set new environment.

3.Type the code to implement SR flipflop using verilog and validating their functionality using their functional tables.

4.Run the program.

5.Give inputs in the waveform table.

6.Run the program.

**PROGRAM**

Program for flipflops and verify its truth table in quartus using Verilog programming. 

Developed by: POPURI SAHITHYA  RegisterNumber: 25004681

<img width="1541" height="651" alt="{2DF3DCB9-59FE-4FA2-A65D-C2C8699B55C5}" src="https://github.com/user-attachments/assets/0a97c96e-d250-4545-9b85-8fc87845ea7e" />

**RTL LOGIC FOR FLIPFLOPS**

<img width="1526" height="714" alt="{F5D4529B-2B67-4E08-A101-A16AACD97103}" src="https://github.com/user-attachments/assets/581aa85b-e453-47c2-9a96-864be3d6ef38" />


**TIMING DIGRAMS FOR FLIP FLOPS**

<img width="1042" height="130" alt="{0D59AC58-0AB2-4F7B-ADCC-BF597866D7E6}" src="https://github.com/user-attachments/assets/3c9d870f-f5a1-4d2b-8733-31a66373124a" />

**RESULTS**
Implementation of JK flipflop using verilog and validating their functionality using their functional tables is executed and the output is verified successfully.
