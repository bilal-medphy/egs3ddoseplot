# egs3ddoseplot
python code to extract and plot from 3ddose file
Modified the original python code by ftessier/egs-plotdose-1d.py 
to make it to work with python3 (anaconda) and modified the file to take input interactively

Usage :
1. Open the file and modify the python environment setup at the first line as per your environment settings
2. save and make the file executable. 
3. Run from terminal
4. The input file, axes for plotting can be given as the argument.
  command line usage: 
    ./egs-doseplot.py x|y|z  a,b  filename
            
    x|y|z       axis of the dose profile
    a,b         coordinates along the other axes
    filename    3ddose file to plot without extension
        
    example:   egs-doseplot.py z 0,0 filename
        (extract the central z-axis dose profile for the filename.3ddose file)
  5. It can also be run in interactive mode by
    usage : ./egs-doseplot.py 
    it will ask for the filename to plot, axes to plot and other axes co-ordinates.
    If axes to plot and other axes coordinates are not provided then the plot will be done for 0.0.z
    
