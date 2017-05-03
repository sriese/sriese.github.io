BSidesCharm 2017 Microsoft Patch Analysis for Exploitation - Stephen Sims
===================

https://www.youtube.com/watch?v=LHNcBVQF1tM

Structure of Microsoft Patches
--------
As of October 2016 changed to Cumulative Update (CU) model - each month contains the previous month/s patches

PowerShell tool by Greg Lineras (@Laughing_Mantis) that is useful for parsing the Cumulative Update package for only the recently modified updates (i.e. what we care about)

April 2017 - must go to https://portal.msrc.microsoft.com/en-us/security-guidance to download CU's
https://portal.msrc.microsoft.com/en-us/security-guidance/summary for finding the actual vulnerability information (previously found in TechNet)

Binary Diffing Tools
--------
Zynamics/Google BinDiff - free
Core Security turbodiff - free
DarunGrim4 - free, Standalone - still need IDA
patchdiff2 - free, needs licensed copy of IDA or turbodiff 5.0
Diaphora - free written in Python so abit slower

*34:29* Reversing Demo
--------
34:29 Demo reversing MS