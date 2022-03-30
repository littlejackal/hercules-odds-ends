# Odds and ends 
Little efficiencies to make working with Hercules mainframe emulation easier

## dspray
Parse a dasd file (or folder of DASD files) and spray (ahem: extract) its 
contents to an output folder. Useful for inspecting datasets and contents of
partitioned datasets. 

Relies on Hercules' own dasdseq and dasdpdsu utilities until someone reinvents
the wheel with a python native dasd library.




