Relative-Calcium-Change-
This  script is to analyze Ca²⁺ influx assay data. It calculates relative changes in Ca²⁺ levels, compares stimulant and negative control responses, performs a paired t-test for significance, and visualizes the data. 
Before start, please download the following: jupyter lab, pandas, openpxyl, scipy, matplotlib. You can open the file with jupyter lab.

A brief introduction to the sample data. I have an excel file with 2 sheets. First sheet is the measurements of the stimulant I tested.
The second sheet is the measurement of negative control. 
This is a Ca+2 influx assay data coming from FACS measurement, where I measure the cytoplasmic Ca2+ levels over time. 
In this analysis, I calculate the relative change of the Ca2+ after stimulation and compare it to the change after stimulation by negative control.
The data represents a 30-second long baseline measurement, followed by stimulation, followed by measurement up to 4 minutes.

You need to write the path where your file is located. Example --> 
(r"C:\Users\Benutzer1\Desktop\File1\Ca_measurements.xlsx", sheet_name='Stimulant')

