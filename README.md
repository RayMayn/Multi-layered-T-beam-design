# Multi-layered-T-beam-design
Multi-Layered T-beam design. Conforms ACI 318


Hello guys
This is my first app using VBA
The app is versatile as it can be used for investigations and designs.

The analysis conforms ACI 318 and its computation is iterative base on
Reinforced Concrete Mechanics and Design by Wight MacGregor.
Thus assumption like yielding of compressive steel can't be assumed as the computation 
relies on the exact behavior of the material.
I'll show my computations.

This is the first version of the app so bear with me.

Inputs are:
fc'=compressive strength of concrete [17:28-55]MPa
 fy =yield strength of steel[276-414/420]MPa
 db =diameter of main/horizontal bars,mm
 dv =diameter of stirrups,mm
 dagg =diameter of aggregates,mm
 cc =concrete cover, mm 
 l =length of beam,mm 
 ln =clear span of beam,mm 
 ln,left =clear span of left adjacent slab,mm 
 ln,right =clear span of right adjacent slab,mm 
 bw = width of beam cross section,mm 
 tf =thickness of flange/slab,mm 

 beam geometry(ss[simply supported],oec[one end continuous],bec[both end continuous],c[cantilever]) 
 h=heigth of beam,mm 
 Moment demands,KNm=you got to compute for this, common load combination (1.2*Deadload moment+1.6*Liveload moment) 
 Shear demands,KN=solve this too, use the same load combination(1.2*Deadload shear+1.6*Liveload shear) 


Outputs are:
Ultimate Moment Capacity,
Number of Bars for flexural design, and
Number of stirrups.

Computation will be added later.

Updates will be done as soon as possible.

Donate on my PayPal PayPal.Me/raymayn as I make more applications
