# EPR_Apps
"Saveaftereachscan.ppp" is a ProDEL program for Bruker ELEXSYS EPR spectrometers to automatize saving data after each scan.
Load the program into the ProDEL programming panel of the Xepr software and click the Compile/Run button.
Set the first scan to save, the increment, and the total number of scans. Start the program by clicking the "Apply" button. 
By default, the data will be saved to the folder /home/xuser/xeprFiles/. Optionally, this path can be changed in the script.
Note that the Xepr software will be locked during execution of the ProDEL program i.e., no parameters etc. can be changed.
For stopping execution, click the "break" button in the bottom right corner of the Xepr window.
