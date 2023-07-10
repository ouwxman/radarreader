# radarreader

This Github repository contains a Jupyter notebook to read and plot PX-1000 radar data. Sample PX-1000 data from the 12 May 2023 tornado near Cole, Oklahoma are provided in sample.zip. The PX-1000 data files are netCDF files, which are a type of self-describing file format. Each radar variable is written into a different file. For example, the reflectivity files end with Z.nc and Doppler velocity end with V.nc.  

You can follow the instructions in the Jupyter notebook. However, a few preparation steps are helpful. First, unzip the files in sample.zip. If you are using the OU library's Nautilis JupyterHub server, then you can upload the radar files to the server along with the Python notebook. To generate a plot, just change the file path and directory (if needed). There are additional questions for self-experimentation with Python plotting and radar analysis.
