# FIT-to-CSV-converter-for-windows

This code is intended to use for Garmin files products with heart rate monitor, I tested it with Fenix 5 Plus smart watch. The workout file from the Fenix 5 is *.fit and this one is binary file which means you can not see your data, you need to convert it to *.txt or better *.csv file. Once in csv format, just open it in Excel and watch your heart rate data. The Fitparse package extract all data from *.fit file to the ram memory and you get access to the raw data after conversion.  

<img src="picture/fenix5plus.png" width=300>
Fenix 5 Plus

The original code is from https://github.com/mcandocia/fit_processing
I did small modifications because the code is for Linux and the final *.csv file has empty line for each line of data. The modification that I did is in the end of write_fitfile_to_csv section. All credits is for mcandocia. 



First, you need to install Fitparse package. You can download it from: http://pythonhosted.org/fitparse/ the link in github is https://github.com/dtcooper/python-fitparse

After download go to the master directoy and look for setup.py using CMD windows terminal
in CMD run:

py setup.py install

Other libraries (CSV, OS and pytz) are installed with the basic Python 3 installation.
Now, place the FIT_to_CSV_forWin.py in the same location of the FIT file and the result will be CSV file with the same name.

Just run:

py FIT_to_CSV_forWin.py

<img src="picture/Capture.PNG" width=800>


