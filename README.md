## AIM 

This Experiment is on the Analysis and Design of Differential Amplifiers.
## Theory

Differential amplifiers apply gain not to one input signal but to the difference between two input signals. This means that a differential amplifier naturally eliminates noise or interference that is present in both input signals.
Differential amplification also suppresses common-mode signals—in other words, a DC offset that is present in both input signals will be removed, and the gain will be applied only to the signal of interest (assuming, of course, that the signal of interest is not present in both inputs). This is particularly advantageous in the context of IC design because it eliminates the need for bulky DC-blocking capacitors.
The subtraction that occurs in a differential pair makes it easy to incorporate the circuit into a negative-feedback amplifier
General diagram of differential amplifier
![image](https://github.com/user-attachments/assets/e34a8398-8d83-42dd-b083-d5f3867709f3)

Coming to the experiment and analysis.

Q. Design and analyze the differential amplifier for the following specifications. Vdd = 2v , P <= 1mW , Vicm = 1v , Vocm = 1.1v , Vp = 0.4V.
To perform the DC Analysis,Transient Analysis, Frequency Response and to extract the parameters.

## Circuit diagram cosisting of resitor
<img width="1278" alt="Screenshot 2025-03-10 100543" src="https://github.com/user-attachments/assets/48e8e8da-358f-40e4-9752-7a384bde8f4b" />

![WhatsApp Image 2025-03-11 at 18 23 03_3be1290d](https://github.com/user-attachments/assets/833d31c9-0b0f-4d83-82c4-58edc292065b)

## DC ANALYSIS
DC operating point with all parameter
<img width="475" alt="Screenshot 2025-03-10 100621" src="https://github.com/user-attachments/assets/2f28d486-968e-4cf8-a155-aca37a28c53b" />
W/l Value of Mosfet 1
<img width="276" alt="Screenshot 2025-03-10 100639" src="https://github.com/user-attachments/assets/52ca191c-9d7c-45e5-a181-f58957cc078e" />
W/l Value of Mosfet 2
<img width="275" alt="Screenshot 2025-03-10 100659" src="https://github.com/user-attachments/assets/a3b9959b-6aa0-41bf-921d-f5b8f71114ba" />
so from this Q point is (0.6V,0.25 mA)
## Transient analysis
Circuit Waveforms 
<img width="1280" alt="Screenshot 2025-03-10 100930" src="https://github.com/user-attachments/assets/e0eaf303-85f7-40b2-8d5f-5da623dbdbe1" />
From this we derived the value of gain which is given by 
Av= Voutpp/Vinpp
The value obtained from simulation was Av=-1.816 
And the calculation for Vin max and Vout max is uploaded below
![WhatsApp Image 2025-03-11 at 18 33 07_ea72f5c3](https://github.com/user-attachments/assets/61de47e6-accf-4a12-ad3e-433600f88539)
## AC analysis
<img width="1280" alt="Screenshot 2025-03-11 183506" src="https://github.com/user-attachments/assets/c0d68373-2cad-4920-8fcf-4d2f5e61ce60" />
From this the 3 db BW can be determined as 6 GHz


## Circuit diagram replacing resistor with current souce
<img width="1280" alt="Screenshot 2025-03-10 101204" src="https://github.com/user-attachments/assets/435c923c-d0a9-4065-9692-ac0cf2c11bc6" />


## DC ANALYSIS
DC operating point with all parameter
<img width="1280" alt="Screenshot 2025-03-10 101229" src="https://github.com/user-attachments/assets/7a22e155-1170-4ad0-ae76-ef098c8b3190" />

W/l Value of Mosfet 1
<img width="276" alt="Screenshot 2025-03-10 100639" src="https://github.com/user-attachments/assets/52ca191c-9d7c-45e5-a181-f58957cc078e" />
W/l Value of Mosfet 2
<img width="275" alt="Screenshot 2025-03-10 100659" src="https://github.com/user-attachments/assets/a3b9959b-6aa0-41bf-921d-f5b8f71114ba" />
so from this Q point is (0.6V,0.25 mA)
## Transient analysis
Circuit Waveforms 
<img width="1280" alt="Screenshot 2025-03-10 100930" src="https://github.com/user-attachments/assets/e0eaf303-85f7-40b2-8d5f-5da623dbdbe1" />
From this we derived the value of gain which is given by 
Av= Voutpp/Vinpp
The value obtained from simulation was Av=-1.816 
And the calculation for Vin max and Vout max is uploaded below
![WhatsApp Image 2025-03-11 at 18 33 07_ea72f5c3](https://github.com/user-attachments/assets/61de47e6-accf-4a12-ad3e-433600f88539)
## AC analysis
<img width="1280" alt="Screenshot 2025-03-11 183506" src="https://github.com/user-attachments/assets/c0d68373-2cad-4920-8fcf-4d2f5e61ce60" />
From this the 3 db BW can be determined as 6 GHz

## Circuit diagram replacing current source with mosfet as constant current source
<img width="1280" alt="Screenshot 2025-03-10 101204" src="https://github.com/user-attachments/assets/435c923c-d0a9-4065-9692-ac0cf2c11bc6" />


## DC ANALYSIS
DC operating point with all parameter
<img width="1055" alt="Screenshot 2025-03-11 161544" src="https://github.com/user-attachments/assets/cfd3afb7-e65e-4c78-a789-214a56d77ded" />

W/l Value of Mosfet 1
<img width="276" alt="Screenshot 2025-03-10 100639" src="https://github.com/user-attachments/assets/52ca191c-9d7c-45e5-a181-f58957cc078e" />
W/l Value of Mosfet 2
<img width="275" alt="Screenshot 2025-03-10 100659" src="https://github.com/user-attachments/assets/a3b9959b-6aa0-41bf-921d-f5b8f71114ba" />
W/l Value of Mosfet 3(constant current source)
<img width="277" alt="image" src="https://github.com/user-attachments/assets/c1a9a31e-d2f2-4345-bf78-073801ffa90c" />
so from this Q point is (0.6V,0.25 mA)
## Transient analysis
Circuit Waveforms 
<img width="1280" alt="Screenshot 2025-03-10 100930" src="https://github.com/user-attachments/assets/e0eaf303-85f7-40b2-8d5f-5da623dbdbe1" />
From this we derived the value of gain which is given by 
Av= Voutpp/Vinpp
The value obtained from simulation was Av=-1.816 
And the calculation for Vin max and Vout max is uploaded below
![WhatsApp Image 2025-03-11 at 18 33 07_ea72f5c3](https://github.com/user-attachments/assets/61de47e6-accf-4a12-ad3e-433600f88539)
## AC analysis
<img width="1280" alt="Screenshot 2025-03-11 183506" src="https://github.com/user-attachments/assets/c0d68373-2cad-4920-8fcf-4d2f5e61ce60" />
From this the 3 db BW can be determined as 6 GHz

## Result and inference

1. Noise Rejection (Common-Mode Rejection): Differential amplifiers effectively remove common-mode noise, making them ideal where low-level signals need to be extracted from noisy environments.

2. Operating in Saturation Region: The MOSFETs in the differential pair must remain in saturation to ensure high transconductance and gain. 

3. Gain Characteristics: The voltage gain of the designed amplifier was approximately -1.861 V/V (5.2dB), which aligns with the small-signal model prediction  Av = gm*Rd.

4. Common-Mode Input and Output Range: The common-mode input voltage range was found to be 0.766V to 1.466V, while the common-mode output voltage range was 0.633V to 1.100V, defining the operational limits.

5. Large Signal Behavior: The circuit exhibits 180° phase shift between input and output, confirming inverting behavior. Beyond certain input limits, the output clips due to saturation effects.

6. Effect of Increasing Iss or W/L: Increasing Iss improves linearity, allowing for a wider input range, while increasing W/L reduces linearity, limiting the acceptable input range before transistor cut-off occurs.
   
7. The AC / Transient Analysis we have applied an input AC Voltage is given at only one end.This helps to better analyse the analysis part.

8.  However adding the 180 deg phase shift signal to other end increases the gain as the difference of these 2 signals increases.

9. Also we need to need observe that the 'BODY-EFFECT' plays a role here , and thus we know that it increases the threshold voltage thus we are using Vtn = 0.497V and not Vth = 0.366V.

10. In all the cases, the circuit lies within the Power Budget (<=1mW).

