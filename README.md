# Stern Brocot comparison Julia vs Python


#Python version

Python 3.7.6 (default, Jan  8 2020, 19:59:22) 

[GCC 7.3.0] :: Anaconda, Inc. on linux

#Julia Version 

1.8.1 (2022-09-06)

Date 18 Feb 2023

#Box Spec

OS:         Ubuntu 22.04.1 LTS x86_64

Kernel:     5.15.0-60-generic 

Shell:      bash 5.1.16 

CPU:        AMD Ryzen 9 3900X (24) @ 3.800G 

Memory:     64Gb RAM
                     
#Intent:

Implement Stern Brocot in Python and Julia using TDD and nothing too clever

For speed comparison

Roughly simlar logic in the two versions

I love Python and Julia
This is a fair but real-life test in a nerd's attic
Using the versions I had to hand
And the way I normally code
And the same archiecture on the same afternoon etc.

Python

1 layers                              0.000002879590399970766 seconds
2 layers                              0.000005017571400003362 seconds
4 layers                              0.000014577579199976754 seconds
8 layers                              0.00019980101569999533 seconds
12 layers                             0.0033494253342999402 seconds
13 layers                             0.0067446708239000145 seconds
14 layers                             0.013931729978600016 seconds
15 layers                             0.030198445934199937 seconds
16 layers                             withdraws, estimated to take 10 minutes total

Julia

1 layers  elapsed time (ns):  1590    0.000002 seconds
2 layers  elapsed time (ns):  1770    0.000002 seconds
4 layers  elapsed time (ns):  1350    0.000001 seconds
8 layers  elapsed time (ns):  1410    0.000001 seconds
12 layers elapsed time (ns):  1980    0.000002 seconds
13 layers elapsed time (ns):  1670    0.000002 seconds
14 layers elapsed time (ns):  2030    0.000002 seconds
15 layers elapsed time (ns):  2150    0.000002 seconds
16 layers elapsed time (ns):  2220    0.000002 seconds
24 layers elapsed time (ns):  2310    0.000002 seconds
