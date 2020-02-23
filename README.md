# FIT-to-CVS-converter-for-windows

-
The original code is from https://github.com/mcandocia/examples
I did small modifications because the code is for Linux and the final csv file has empty line data by data. The modification that I did is in the end of write_fitfile_to_csv section. All credits is for mcandocia. 
-

First you need to install Fitparser package. You can download it from: http://pythonhosted.org/fitparse/
Go to the master directoy and look for setup.py using CMD (CMD windows terminal)
in CMD run:

py setup.py install

Problaby the other libraries (CSV, OS and pytz) are installed with the basic Python 3 installation.
Now place the FIT_to_CSV_forWin.py in the same location of the FIT file and the result will be CSV file with the same name.

Juts run:

py FIT_to_CSV_forWin.py



