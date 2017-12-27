# Load-.mat-into-Python
Check how to load the .mat file into the python

import scipy.io as spio #'Python package'

Mat_Data = spio.loadmat('data.mat') #make a object type Dictonary

Frame_Data = Mat_Data['key'] # key is the set name with which our data set will define in object type

for loop:
data_cur = Frame_Data[i,0] #extract every single frame
end

for loop:
A = data_cur[r,c] # get the matrix value from single frame 
end
