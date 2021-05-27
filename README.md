# GANs
Generative Adversarial Network


I have uploaded todays work. 

Following the summary of today#s work at RotoLab


Iteration 1.
Parameter: snaps= 15,  Gamma=10
Result: ticks  fid
        0       306.288
        15      178
        30      82
        45      52
        60      37
        

From inital FID = 307 to FID = 37.77 in 60 ticks. 

With Gamma =10, the GANs model showed sign of convergence. 
The models has learned the underlying structure of the images. 
But lot of iteration are needed to get to a conclusable result.
As the converence rate was slow, the value of gamma needed to optimized further.


Iteration2.
Parameter: snaps= 10,  Gamma=0.23405714285714288

This was done by using values generated with another script 'gamma_calculate'.
Value of 0.23 was generated from script and choosed for further iteration.

The effect has to be seen as the training with new value has not reached a conclusive state.



