# C50 Plucking a string 
     
  
## Aim   
 To show the frequency-components in a plucked string and how they depend on the strings tension.    
  
## Subjects   
 3B22 (Standing Waves) 3C50 (Wave Analysis and Synthesis)   
  
## Diagram   
   
```{figure} figures/figure_0.png  
---  
width: 50%  
name: figures/figure_0.png  
---  
caption  
``` 
     
  
## Equipment   
 
 *  Sonometer with detector (we use PASCO WA9613). 
 *  Steel string, d=.5mm (μ=1.5x10-3kg/m). 
 *  Two masses (.5kg and 1kg). 
 *  Data-acquisition system (we use PASCO ScienceWorkshop).
      
  
## Presentation   
 Set up the demonstration as shown in Diagram and connect the detector, that is placed near the string, to the interface. The software is set up to have an oscilloscope screen and an FFT display (frequency spectrum) as in Figure 1. 1. Load the string with .5kg (see Diagram, mass hanging at the end of the lever). Pluck, by hand/nail, the string (moving it in a vertical direction).We do this in two ways:  a.  Pluck the string in its centre. The scope display shows a more or less symmetric shape. The FFT display shows the frequency components in it. Using the crosshair cursor we read: 102-, 289-,  473-, 663Hz. Very roughly the relationship 1:3:5:7 is visible in these frequencies. b. Pluck the string close to its end.  The scope display shows a more or less sawtooth shape, and while it dampens becomes more or less sinusoidal. The FFT display shows the frequency components in it. The fundamental frequency is very high compared to the higher harmonics. (Using the crosshair cursor we read: 102-, 190-, 288-, 385-, 473-, 570-, 666-, 755-, 853Hz, etc. Very roughly the relationship 1:2:3:4:5:6:7:8:9 is visible in these frequencies.) 2. Loading the string with another force.       a.  By hand. When the string is plucked, we pull the weight. We see on the FFT-display shift the frequency components to higher frequencies.       b. Load the string with 1kg. Again the string is plucked, first in its centre, and next close to its end. The observed frequencies are now: 2a: 140-, 268-, 405-, 541-, 677-, 799-, 939Hz; 2b: 140-, 405-, 678Hz (see Figure 1). Compare these data with the results of the first part of our demonstration and show that the ratio’s 140/102; 268/190; 405/288; 541/385; etc. are all very close to2.   
```{figure} figures/figure_1.png  
---  
width: 50%  
name: figures/figure_1.png  
---  
caption  
``` 
    Simulation: To support the results of our demonstration we show the simulation of a vibrating string. To do so we choose “Loaded String Simulation”, a JAVA-Applet on the site http:www.falstad.com/ in which the string can be plucked at different points using the mouse. Adjusting the simulation speed top ‘low’ the vibrating string is shown in slow motion, clearly showing its frequency amplitude components (and its first three phasors). You can hear also the sound of the plucked string and observe the difference between a centre-pluck and an end-pluck.   
  
## Explanation   
 Grasping a string near its end to pluck it, makes the triangular shape in the oscillating string to be expected. The FFTdisplay distincts a fundamental frequency and a number of its harmonics. In general a triangular shape appears when to a fundamental frequency a second harmonic (first overtone), a third harmonic (second overtone), etc. is added. The demonstration verifies this. Grasping the string in its centre to make it oscillating, a symmetric waveform is to be expected with uneven harmonics in it. When the crosshair cursor is used in the FFT-display to read the observed frequencies it shows that doubling the string's tension means a factor 2in increase in frequency.  A standing wave occurs when travelling waves/pulses after their reflections at the end of the string interfere positively, giving large standing amplitudes. The speed of pulses/waves travelling along the string is:Fvμ=, (see "Speed of a single pulse on different strings (1)" in this database) . vfλ= and so: 12vFfLλμ==, L being the length of the string. Our demonstration in doubling the string tension (F ) verifies the squareroot of F  in relation to f. (When we fill up the formula 12vFfLλμ== with the data of our demonstration we calculate a fundamental frequency of 115Hz (Demonstration yields 102Hz).  --------------------------------------------------------------------------------------------------------- That many frequencies occur in a plucked string can be explained by showing the solution on the one-dimensional wave equation. This equation, 2222210ffxct∂∂−=∂∂, can generally be solved by:12(,)xxfxtftftcc⎛⎞⎛⎞=−++⎜⎟⎜⎟⎝⎠⎝⎠(d’Alembert solution), where 1f and 2f can be any function. So nf can be any time-harmonic solution like (/)itxcAeω−−+(/)itxcBeω−++(/)itxcCeω−+(/)itxcDeω+, etc., in which ω can have many values. For a string with fixed ends we get a number (n ) of possible standing waves; n different modes of vibration: 1nnωω=, n = 1, 2, 3, … 1ω is called fundamental frequency; the others harmonics or overtones.   
  
## Sources   
 
 *  Mansfield, M and O'Sullivan, C., Understanding physics, pag. 344-345 and 349-350 
 *  Young, H.D. and Freeman, R.A., University Physics, pag. 627-630
 