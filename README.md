# Quantum-Efficiency-Calculator-for-Electrochemiluminescence
This repository takes in pulsing or CV data, emission spectrum, hardware quantum efficiency and relevant background scans to find the quantum efficiency of the ECL emission.
The code and math is detailed extensively in a publication in Analytical Chemistry, named 'Absolute Electrochemiluminescence Efficiency Quantification Strategy Exemplified with Ru(bpy)32+ in the Annihilation Pathway' in 2021. https://pubs.acs.org/doi/abs/10.1021/acs.analchem.1c02403

Many parameters are needed for the successful determination of the quantum efficiency and reading the above text is necessary to use this software efficiently. Please reach out to me if you cannot access the manuscript.

This app will perform all of the math discussed in the publication after you supply the relevant information. Example data files are supplied to test the program and pictures are provided below.

Tab 1 contains all the data loading necessary to run the program:

![screen1](https://github.com/user-attachments/assets/c8df281e-2122-4313-b66a-4e6d16b8960c)

Tab 2 contains all the necessary quantitative values to calculate the quantum efficiency which is all described in detail in the above publication. After inputting all data and quantitative values in tab 1 and 2 respectively, clicking the 'Calculate C Factor' button produces the following image:

![screen2b](https://github.com/user-attachments/assets/73c83507-dbfc-444d-a7a8-93c6e9abd5fb)

Once everything has been filled in on Tab 1 and 2, clicking the 'QE Pulsing Calculation' button produces the quantum efficiency of the ECL process as a percentage. In this example, the Rubpy23+ electrochemiluminescence annihilation pathway was pulsing at 10 Hz to produce 0.2263 %:

![screen3](https://github.com/user-attachments/assets/4bfcf4e1-3390-4a0c-895f-874529cd37ff)
