Main
runs the program, is a pointer to the differnet functions.

ConvertToSpreadsheet
takes a 1d array of number as input, converts this to a ND array 
that can be displayed on a spreadsheet.

findCalibrationFactor
For each input, set the deformation and press measure to find
the corresponding voltage. Save the calibration factors to a file
when you are done calibrating.

splitInput
internal function that splits a 1D array in to four arrays with
elements 0,4,8 on the first 1,5,9 on the second etc.

splitInput2
internal function that splits a 1D array in to two arrays with 
elemnts 0,2,4 in the first and 1,3,5 in the second.

Measure
Runs a measurment specified in setTestProcedure with the calibration
factors found with findCalibrationFactor. Create a .txt file and 
set the path to that file. Make sure you set enough samples to get
a smooth wave in the graph.  

When using PCI 6014, have a wire beteween 34 and 4, so you have a ground
reference.


Håkon Arnø Hoff
haakoaho@stud.ntnu.no
