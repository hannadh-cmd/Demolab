# L20 LRC circuits 
    
  
## Aim   
 To show the effect of frequency on current and voltages in an LRC-series (and -parallel) circuit.    
  
## Subjects   
 5L20 (LCR Circuits - AC)   
  
## Diagram   
   
```{figure} figures/figure_0.png  
---  
width: 50%  
name: figures/figure_0.png  
---  
caption  
``` 
      
  
## Equipment   
 
 *  Signal generator. 
 *  Large display to show frequency-setting of signal generator. 
 *  Resistance box. 
 *  Capacitor box. 
 *  Coil, n=500, with iron core. 
 *  3 multiscale V-meters. 
 *  A-meter.
     
  
## Presentation   
 The circuit is made as shown in Diagram and Figure1.      
```{figure} figures/figure_1.png  
---  
width: 50%  
name: figures/figure_1.png  
---  
caption  
``` 
 C is made 1uF. The value of R is made zero. The voltage of the signal generator is made 6V. 
 *  The frequency is set at 100Hz. Students can read that all the voltage appears at C: VC=6V; VL=0V. 
 *  The frequency is made 10kHz. Students can read that now all the voltage appears at L: VC=0V; VL=6V. These first two measurements can be discussed now. After this discussion the question is raised: "what happens between 100Hz and 10kHz?" 
 *  The frequency is set at 1kHz. Students can read now that VC=5V; VL=11V. When it is the fist time that students are confronted with ac-circuits, these readings will produce many questions: "How is it possible that a 6V power supply gives in the circuit (11+5=)16V?; is Kirchhoff's rule no longer valid?, etc.". The vectorconcept of ac using a phasordiagram can be introduced to explain the observed phenomenon. 
 *  Now it is interesting to explore the region between 100Hz and 10kHz. Lowering the frequency from 1kHz downwards, both VC and VL will rise steeply. We measure at 670Hz VC=VL=140V! Students can also observe that in this situation I is at a maximum. The results can be discussed now.  It is easy to change the circuit into a LC-parallelcircuit (). L and C have now an ammeter in series. Again measurements are made at f=100Hz, f=10kHz and f=1kHz and after that going down to resonance. We measured: - 100Hz: IC=0; IL=.16A; Itotal=.16A - 10kHz: IC=.35A; IL=.0; Itotal=.35A - 1kHz: IC=35mA; IL=17mA; Itotal=18mA - 670Hz: IC=25mA; IL=25mA; Itotal=1.4mA These results are similar to those measured in the seriescircuit but now the questions will be raised in relation to the currents.
    
  
## Explanation   
 The first readings of the demonstration can be explained when students have a basic idea of a capacitor and inductance.  
 *  Supposing the frequency extremely low (dc) it is clear that a capacitor conducts no current (it is an insulator) and so it will have a very high resistance. At low frequencies the capacitor is charged in a time very small compared to the periodtime of the ac-source and so the capacitor has constantly the same voltage (almost) as the source. This voltage opposes the sourcevoltage and so no current will flow. At very high frequencies the charging time of the capacitor is equal to or larger than the periodtime and so the capacitor is charging (and discharging) continuously: a current is flowing. 
 *  At extreme low frequencies the coil has a very low inductance (Dt=large) and only a voltage due to its resistance of the copper wires appears across its terminals. At high frequencies the coil will produce a high induced voltage (Dt=small), so at high frequencies a high voltage can be expected across it. In this qualitative way the opposite frequency-response of C and L can be talked into the students. A more thorough analysis is needed to understand all the results that can be shown in this demonstration. A phasor-diagram is needed.      
```{figure} figures/figure_2.png  
---  
width: 50%  
name: figures/figure_2.png  
---  
caption  
``` 
 Many textbooks show these diagrams. Figure2 shows the diagrams that apply to our demonstrations. The explanation of the results measured in the parallel circuit can be explained using a current pha
sordiagram.    
  
## Remarks   
 
 *  A lot more can be shown with this demonstration. For instance the influence of R. 
 *  Also a mathematical analysis is possible using the capacitance XC=(wC)-1 and inductance XL=wL. Many textbooks sh
ow how to do this.    
  
## Sources   
 
 *  Mansfield, M and O'Sullivan, C., Understanding physics, pag. 531-535 
 *  McComb,W.D., Dynamics and Relativity, pag. 84-86 
 *  Roest, R., Inleiding Mechanica, pag. 281-283 
 *  Young, H.D. and Freeman, R.A., University Physics, pag. 987-1013
  