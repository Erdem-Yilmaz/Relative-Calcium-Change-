Relative-Calcium-Change
This script analyzes Ca²⁺ influx assay data. It calculates the relative changes in Ca²⁺ levels, compares the stimulant and negative control responses, performs a paired t-test for significance, and visualizes the data. Before starting, please download the following: Jupyter Lab, Pandas, OpenPyXL, SciPy, and Matplotlib. You can open the file with Jupyter Lab.

A brief introduction to the sample data:
I have an Excel file with two sheets. The first sheet contains the measurements of the stimulant I tested, and the second sheet contains the measurements of the negative control. This data comes from a Ca²⁺ influx assay performed using FACS, where I measure the cytoplasmic Ca²⁺ levels over time. In this analysis, I calculate the relative change in Ca²⁺ after stimulation and compare it to the change observed after stimulation with the negative control. The data represents a 30-second baseline measurement, followed by stimulation, and then measurements taken for up to 4 minutes.

Remember to specific your own path where your file is located . Example -->
(r"C:\Users\Benutzer1\Desktop\File1\Ca_measurements.xlsx", sheet_name='Stimulant')
