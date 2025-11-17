# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DESIGN OF ACTIVE LOW PASS,HIGH PASS AND BAND PASS FILTERS USING OP-AMP 

## AIM: 

To design and obtain the frequency response of 
i) First order Low Pass Filter (LPF) 
ii) First order High Pass Filter (HPF) 
iii) Band pass filter
 
## APPARATUS REQUIRED

<img width="625" height="170" alt="image" src="https://github.com/user-attachments/assets/900fc8b3-3a8c-4208-bf52-98cc9e281e21" />

## THEORY
## LOW PASS FILTER 
 A LPF allows frequencies from 0 to higher cut of frequency, fH.  At fH the gain is 0.707 
Amax, and after fH gain decreases at a constant rate with an increase in frequency.  The gain 
decreases 20dB each time the frequency is increased by 10.  Hence the rate at which the gain 
rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in 
frequency.  The frequency f=fH is called the cut off frequency because the gain of the filter at this 
frequency is down by 3 dB from 0 Hz.  Other equivalent terms for cut-off frequency are -3dB 
frequency, break frequency, or corner frequency.
# HIGH PASS FILTER 
The frequency at which the magnitude of the gain is 0.707 times the maximum value of 
gain is called low cut off frequency.  Obviously, all frequencies higher than fL are pass band 
frequencies with the highest frequency determined by the closed –loop band width all of the op
amp. 
# BAND PASS FILTER 
A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > 
fL.  Any input frequency outside this pass band is attenuated.  There are two types of band-pass 
filters.  Wide band pass and Narrow band pass filters.  We can define a filter as wide band pass if 
its quality factor Q <10.  If Q>10, then we call the filter a narrow band pass filter.  A wide band 
pass filter can be formed by simply cascading high-pass and low-pass sections.  The order of 
band pass filter depends on the order of high pass and low pass sections.

## CIRCUIT DIAGRAM: 
## LOW_PASS-

<img width="412" height="489" alt="image" src="https://github.com/user-attachments/assets/c6d6ec49-2523-49aa-af53-3092995a22c7" />

## HIGH-PASS-

<img width="449" height="432" alt="image" src="https://github.com/user-attachments/assets/1b2e49f0-9d83-4956-b6ce-c0c6ce43eef6" />

## BAND-PASS-

<img width="439" height="382" alt="image" src="https://github.com/user-attachments/assets/c6908b9e-3aa0-485f-990c-88bd2a6e0344" />

## MODEL GRAPH:
## LOW_PASS-

<img width="375" height="543" alt="image" src="https://github.com/user-attachments/assets/fa73bc1a-d595-4257-b1ad-41fe9831f235" />

## HIGH-PASS-

<img width="314" height="351" alt="image" src="https://github.com/user-attachments/assets/e8ae9183-e50a-4694-a8ec-fcdd9dc77778" />

## BAND-PASS-

<img width="334" height="385" alt="image" src="https://github.com/user-attachments/assets/b05fdbe2-1d39-4362-8b7d-7052bb403cec" />


## PROCEDURE - (LPF & HPF): 
1. Connect the circuit as shown in the circuit diagram. 
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. 
select the value of R1 & Rf depending on desired passband gain Af.. 
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
4. Tabulate the output voltage Vo with respect to different values of input frequency. 
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to  get approximately the same characteristic as shown in the model graph. 
# PROCEDURE:BAND PASS FILTER 
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given 
frequencies. 
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF 
followed by a LPF (i.e) HPF in series with LPF. 
3. Connect the circuit as shown in the circuit diagram. 
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
5. Tabulate the output voltage Vo with respect to different values of input frequency. 
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to get approximately the same characteristic as shown in the model graph

## DESIGN:LPF & HPF:

<img width="429" height="324" alt="image" src="https://github.com/user-attachments/assets/b0f0ac0a-3006-494c-9096-e91ae2d6e87c" />

# DESIGN: BAND PASS FILTER
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.  
1. Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency 
of HPF as fL = 1 KHz.  
2. Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf.  
Let C = 0.1μf.  
3. Calculate R from the expression.  
Given: fH = 2KHz  = 1/ (2πR1C1) 
   Let C1 = 0.1 µF, R1 = 7.9 KΩ 
Given: fL = 400Hz  = 1/ (2πR2C2) 
   Let C2 = 0.1 µF, R2 = 39.8 KΩ 
  Pass band Gain=4 
   Now   Ao = 1 + (Rf / R1)  
               2-1=(Rf / Ri) 
                Ri = Rf 
                 Let  Ri = Rf = 10 KΩ
## TABULATION:
## LOW_PASS

<img width="347" height="353" alt="image" src="https://github.com/user-attachments/assets/32a55d41-159a-4a6a-8e4d-6694f8ef4cfe" />

## HIGH-PASS

<img width="383" height="386" alt="image" src="https://github.com/user-attachments/assets/c7c3e82c-9a4d-4ecf-afd3-46c346bfa08c" />

## BAND-PASS

<img width="442" height="397" alt="image" src="https://github.com/user-attachments/assets/3079311c-668d-48c2-bbab-33872ad4f128" />

## GRAPH:
## LOW_PASS

<img width="409" height="321" alt="image" src="https://github.com/user-attachments/assets/5aa2407c-03b9-4ece-b382-70f99e6d093d" />


## HIGH-PASS

<img width="456" height="361" alt="image" src="https://github.com/user-attachments/assets/e8f4cd53-55df-42ae-8bab-278271a7e064" />

## BAND-PASS

<img width="434" height="354" alt="image" src="https://github.com/user-attachments/assets/45db7ec4-479f-4384-99fc-79fdd2b64334" />

 ## RESULTS:
Thus an Active Low pass, High pass and Band Pass Filters are designed and 
tested using op-amp IC 741. 

