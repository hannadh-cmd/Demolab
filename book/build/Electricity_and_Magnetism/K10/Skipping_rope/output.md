# Skipping rope 
    
<b> Aim: </b>  
 To show that in a skipping rope an electric voltage is induced. (The strength of the Earth's magnetic field can be determined.)    
<b> Subjects: </b>  
 5K10 (Induced Currents and Forces)   
<b> Diagram: </b>  
   
```{figure} figures/figure_0.png  
---  
width: 50%  
name: figures/figure_0.png  
---  
caption  
``` 
      
<b> Equipment: </b>  
 
 *  Compass needle. 
 *  Skipping rope; 10m of a heavy flexible insulated copper wire. 
 *  Overheadsheet with drawing of skipping rope catenary, to determine area. 
 *  Operational amplifier, amplificationfactor=1000. 
 *  Oscilloscope. 
 *  Data-acquisition system (we use PASCO "ScienceWorkshop"). 
 *  Beamer to project monitor image.
     
<b> Presentation: </b>  
 The compass needle is placed on the overheadprojector to indicate the North-South direction in the lecturehall.   
```{figure} figures/figure_1.png  
---  
width: 50%  
name: figures/figure_1.png  
---  
caption  
``` 
 The demonstration is set up as shown in Diagram, and positioned so that the axis of rotation of the skipping rope is perpendicular to the indicated N-S direction (see Diagram A). The skipping rope is connected to the operational amplifier circuit (see Figure 1A). The output of the amplifier is connected to the oscilloscope, having a slowly moving time-base (.1sec/DIV). The skipping rope is set in rotation (see Diagram C) and the moving spot on the oscilloscope screen is seen to move up and down, showing positive - and negative induced voltages. When the skipping rope is speeded up the amplitude of the induced voltage increases. In order to observe the induced voltage more in detail, the output is also connected to the interface of the data-acquisition system. A voltage-time graph is displayed to the students and they observe the registration of the (1000 times amplified) induced voltage while the skipping rope is making about 15 full turns, some slow, some fast (see Figure2). Clearly the sinusoidal shape of the induced voltage can be observed.      
```{figure} figures/figure_2.png  
---  
width: 50%  
name: figures/figure_2.png  
---  
caption  
``` 
 Finally, a part of the graph with a full cycle is selected and by means of the graph features in the statistics software the integration of a selected one half of a sine is determined (see Figure 2B). We read 0.155Vs. Applying Faraday's induction law and estimating the area of the skipping rope (use the overheadsheet), we find for the Earth's magnetic field Bo=28uT (see Explanation). This is good enough (good enough for a demonstration) when compared with values given in literature.   
<b> Explanation: </b>  
 The induced voltage (E) is given by Faraday's induction law as 0()dAEtBdt=-. Bo is the magnetic flux density; A is the area spanned by the skipping rope and its rotational axis. The plane of the skipping rope changes as0cosAAtw= (see Figure1C), so 0sindAAtdtw=-, and 00()sinEtBAtww=: the induced voltage (E) changes sinusoidally as the registered graph shows convincingly. An interesting quantity is()Etdt∫ (voltage surge, or voltage impulse, in units [Vs]). We will use this quantity to determine the Earth's magnetic field. From Faraday's induction law: 0()EtdtBdA=- and 0sindAAtdtww=-, we get: 00()sinEtdtBAtdtww=-∫∫. When we look at one half of a full cycle, we have: ()00000()cos2EtdtBAtBApw=-=∫. From Figure2B we read ()Etdt∫ equals 0,155Vs. Figure 1B is used to estimate the area Ao of the catenary of the suspended 