# LIC-LAB
lab assessments
# Experiment-1
Question : Given that POWER, P=100µ W; Perform DC Analysis, Transient Analysis and AC Analysis for the Given Circuit Designs and also check what happens when the width is increased or decreased of each mosfet;

# Design-1 :
![image](https://github.com/user-attachments/assets/209dfa11-987d-46b8-bcc5-9112c871f6e3)

Using the Formula for Power, 

P=V*I

We will get the Values of Id as,

Id= 5.55 * 10^-5 A


<img width="288" alt="image" src="https://github.com/user-attachments/assets/bc74a5dd-df32-4b2a-8d35-7025ea8b718e" />

we have to get the output current, Id for the given circuits by adjusting the values of L & W( Length and Width of the Channel of the MOSFET)

Length and Width of the Channel used to obtain the given Current is shown in the figure below;

 

1) DC ANALYSIS:

   Procedure for Performing DC Analysis:
   we have to select the dc output print(DC op pnt) in the Edit Simulation Command and Run the Simulation



   The Figure below shows the Values obtained from the DC Analysis : 

  <img width="475" alt="image" src="https://github.com/user-attachments/assets/9fa994dd-a2ac-4581-a97c-b954b89716af" />


2) Transient Analysis:

   Procedure for Performing Transient Analysis:
   we have to select the Transient Analysis in the Edit Simulation Command,  Give the stop time as 1ms and Run the Simulation.

  
   The Graph below shows the Transient Response of the Given Design;
<img width="405" alt="image" src="https://github.com/user-attachments/assets/c761c265-7554-4f9f-833d-a165612c9bfd" />
<img width="1280" alt="image" src="https://github.com/user-attachments/assets/94fba57f-613c-4f58-913a-d1b938b9e38b" />

  
   
3) AC Analysis:
   
   Procedure for Performing AC Analysis:
   we have to select the AC Analysis in the Edit Simulation Command,  Give the values as shown in the figure beowl and Run th Simulation.


   The Graph below shows the AC Analysis of the Given Design;
<img width="408" alt="image" src="https://github.com/user-attachments/assets/2d9affbf-6f27-4022-8f3b-12e1ab4c7929" />
<img width="1280" alt="image" src="https://github.com/user-attachments/assets/af031be8-c3d1-4b93-8d0a-3f3571c729f8" />



 

# RESULT( Design-1):
 1) DC Analysis:
     1. The calculated drain current (Id) matches the expected value based on power and voltage, Id = 5.55*10^-5 A.
     2. By adjusting the MOSFET’s channel dimensions (L & W) where L=90um and W= 618um, The current requirement was succesfully achecived.
     4. The circuit behaves as expected under DC conditions.

 2) Transient Analysis:
     1. The transient response graph shows how the circuit behaves over time.
     2. The response is smooth, with no unexpected delays or distortions.
     3. The circuit reacts well to changes, confirming its stability.

 3) AC Analysis:
     1. The AC response graph confirms that the circuit remains stable at different frequencies.
     2. The gain(9.9 dB) and phase shift(which is nearly 180deg) align with theoretical expectations.
     3. The circuit maintains its performance across the tested frequency range.

# INFERENCE( Design-1):
   1. The experiment confirms that by properly selecting the MOSFET dimensions, we can control the drain current effectively.
   2. Impact of Width Adjustments:
         1. M1 has a influence on Id, meaning its width affects the output current.
   3. The circuit performs well in all three analyses—DC, transient, and AC—demonstrating its reliability.
   4. Overall, the design works as intended, following theoretical predictions and proving its practical feasibility.



# Design-2

<img width="970" alt="image" src="https://github.com/user-attachments/assets/2b174039-6239-46e5-8185-056a0a6e8d06" />


Aim : To find DC operating point,find gain using transient analysis and AC analysis.

Components : Mosfets (M1 and M2),DC power supply.

Procedure :

• Make the circuit connection as show above.

• Connect DC power supply to the gate terminal.

• Connect the source terminal to the ground.

• Set the input voltage by obtaining VTC curve and VDD to 1.8 V.

Using the Formula for Power, 

P=V*I/n

We will get the Values of Id as,

Id= 5.56 * 10^-5 A

we have to get the output current, Id for the given circuits by adjusting the values of L & W of both the MOSFETS M1 & M2 ( Length and Width of the Channel of the MOSFET)


<img width="478" alt="image" src="https://github.com/user-attachments/assets/e16018bc-dcd3-4e11-ac1b-3f21fca48c10" />

Now we will be performing the DC, Transient and AC Anlaysis;

1) DC ANALYSIS:

   Procedure for Performing DC Analysis:
   we have to select the dc output print(DC op pnt) in the Edit Simulation Command and Run the Simulation

 
<img width="475" alt="image" src="https://github.com/user-attachments/assets/b72896f7-55d9-4ece-9ea9-5398464b8ca5" />


 

2) Transient Analysis:

   Procedure for Performing Transient Analysis:
   we have to select the Transient Analysis in the Edit Simulation Command,  Give the stop time as 1ms and Run the Simulation.

  <img width="408" alt="image" src="https://github.com/user-attachments/assets/c61593bb-f6ed-4cf3-b4c6-70fed7be5c05" />


   The Graph below shows the Transient Response of the Given Design;

<img width="1280" alt="image" src="https://github.com/user-attachments/assets/bd7f96a5-723f-43d8-ba54-42b55ac9df81" />


3) AC Analysis:
   
   Procedure for Performing AC Analysis:
   we have to select the AC Analysis in the Edit Simulation Command,  Give the values as shown in the figure beowl and Run th Simulation.

<img width="407" alt="image" src="https://github.com/user-attachments/assets/6ca1ecff-ae82-459c-9dfc-85be1c859392" />
<img width="1280" alt="image" src="https://github.com/user-attachments/assets/e7348483-1eb1-4c3c-b882-82c351bec49c" />


# RESULT(DESIGN-2)
1.DC Analysis:

   1. The calculated drain current (Id) aligns with the expected value based on power and voltage, where the value of Id = 5.56*10^-5 A .
   2. By fine-tuning the channel dimensions (L & W) of both MOSFETs ( M1 & M2), the desired current was achieved,
         1. M1 : L= 180nm  , W= 1234nm.
         2. M2 : L= 180nm  , W= 1234nm.      
   4. The circuit operates correctly within the selected DC parameters.

2.Transient Analysis:

   1. The transient response graph confirms that the circuit transitions smoothly over time.
   2. The circuit responds effectively to input variations, indicating stable operation.
   3. It has the Gain of around 1.555

3.AC Analysis:

   1. The AC response graph confirms that the circuit maintains stability over the tested frequency range.
   2. The gain(4.2 dB) and phase shift (which is nearly 180deg) align with theoretical expectations.
   3. The circuit functions as expected under AC conditions.

# Inference (Design-2):
  1. The experiment validates that by appropriately selecting the MOSFET dimensions (L & W), the drain current can be precisely controlled.
  2. The voltage transfer characteristics (VTC) helped in selecting the correct operating voltage (0.8V) for saturation.
  3. The design meets the expected performance criteria and follows theoretical predictions, demonstrating its feasibility in practical applications.
