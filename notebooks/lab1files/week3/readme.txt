OVERVIEW OF FILES CONTAINED WITHIN THIS DIRECTORY

DATA
----
This directory contains ten 5-minute excerpts of ECG recordings taken from
longer recordings in the MIT-BIH Malignant Ventricular Arrhythmia Database. 
All of these records were sampled at 250 Hz. The original record names and the 
positions of the excerpts within each record are shown in the 'Source' column 
in the table below.

Record	Source			    Contents
n_418	418 ( 6:30-11:30)	many short V flutter episodes
n_421	421 ( 0:00- 5:00)	noise
n_422	422 (21:30-26:30)	V fib
n_423	423 (24:50-29:50)	noise, A fib
n_424	424 (19:10-24:10)	V fib, asystole, nodal rhythm, sinus rhythm
n_425	425 (15:00-20:00)	noise, VT, V bigeminy, many isolated PVCs
n_426	426 ( 9:00-14:00)	V fib
n_429	429 (29:00-34:00)	V flutter (2 episodes), VT
n_430	430 ( 4:10- 9:10)	V flutter, V fib
n_605	605 (25:00-30:00)	noise, long VT, V bigeminy


ANNOTATIONS
-----------
Each data file contains a corresponding annotation file, named atr_nxxx.txt.
These files contain the cardiologist's identification of the cardiac rhythm 
(e.g. ventricular tachycardia) within each ECG data file. Each annotation file 
contains 7 columns, but only the first (time), second (sample), and last (rhythm) 
contain meaningful information. Each rhythm marker, such as "(VT", identifies 
the start of each corresponding rhythm within the ECG record. 
