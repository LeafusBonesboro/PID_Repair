# PID_Repair
Sim to analyze cost of PID repairs

This is a process oriented sim. An object oriented sim can also be used
to save global variables being used

Each machine operates until RME comes(failure) we need assign this a
random duration d~uniform(30-60) hours

When a PID fails and the parts are available RME shuts 
line down to repair

the time it takes to repair =r~uniform(2-3) hours



There is an oppurtunity cost(OC) that is measured in production loss
Production loss=production working-production not working 

All 10 hours must be accounted for. The state of the PID must be
#recorded for accurate data. There are multiple states the PID can be in
#A few are listed here with more to be added as more information is gathered

As far as production goes 3 main events go into it. 1.the mechanical condition
of the line. 2.Workers on the line. 3. Available freight. 4. Capacity of 
downstream dpts. We will assume for the sake of getting this up and running
that 2,3, and 4 are all good to go and the only variable wil be 1.

10 hour work day
4 day work week

Run will start the sim.The pids need to broken down into sections but we
will just use 4 procces one for each pid. We will also get the daily OC which
include RME and parts.

2 types of shared resources. Repairer and spares


We need data from the pids. for each shift. what mechanical failures, if any,
 occured. Rubber bands, broken rollers, broken wheels, bad motors etc. Need to 
locate problem areas and get data to add into analysis. Need to measure the 
impact. Have the quarterbacks do it. 
