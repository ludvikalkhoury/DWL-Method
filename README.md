This is a supplement to:
"Dual Wavelength Photoplethysmography Framework for Heart Rate Calculation," a paper by:

Ludvik Alkhoury*, JiWon Choi*, Vishnu D. Chandran†, Gabriela B. De Carvalho†, Saikat Pal*,†, and Moshe Kam*

*Department of Electrical and Computer Engineering,
Newark College of Engineering,
New Jersey Institute of Technology, New Jersey 07102, USA

†Department of Biomedical Engineering,
Newark College of Engineering,
New Jersey Institute of Technology, New Jersey 07102, USA

Correspondance: Moshe Kam at kam@njit.edu

We provide two datasets; wrist-dataset and palm-dataset. Each dataset contains the following sensor measurements collected from fourteen (14) participants. The data collection campaign was approved by the Institutional Review Board of the New Jersey Institute of Technology on September 14th, 2021, protocol number 2108010504.

1- Electrocadiagraphy (ECG) waveform (1st column)     
2- 3-axial X, Y, and Z accelerometer readings (2nd, 3rd, and 4th columns, respectively)   
3- 3-axial X, Y, and Z gyroscope readings (5th, 6th, and 7th columns, respectively)   
4- Green photoplethysmopraghy (PPG) waveforms (8th column)   
5- Infrared photoplethysmopraghy (PPG) waveforms (9th column)  

Note: The sampling frequency is 100 Hz

* Wrist-dataset: In the wrist-dataset, green and infrared PPG signals were collected from the wrist of the participant. 
* Palm-dataset: In the palm-dataset, green and infrared PPG signals were collected from the palm of the participant. 

In addition to the raw sensor measurements, we provide a file titled "R_Peaks" for each one of the ECG waveforms we collected. The "R_peaks" file contains the locations of the R-peaks in the corresponding ECG signal. The R-peaks are used to calculate a heart rate ground truth. 

Finally, we provide Tables of the Mean Absolute Error (MAE), Mean Absolute Error Percent (MAEP), and performance index (PI) calculated from all the fourteen (14) participants of the wrist-dataset and palm-dataset. 

If you use the dataset, please cite the paper as follows: Alkhoury, L., Choi, J., Chandran, V. D., De Carvalho, G. B., Pal, S., & Kam, M. (2022). Dual Wavelength Photoplethysmography Framework for Heart Rate Calculation. Sensors, 22(24), 9955.
