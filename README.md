# SlicerCondaWinBin
Instructions:
1) Download the simpleitk egg file and the SlicerConda executable

2) Install http://repo.continuum.io/miniconda/Miniconda-3.9.1-Windows-x86_64.exe to C:\miniconda

3) At a command prompt, do a C:\miniconda\scripts\easy_install SimpleITK-0.9.0b1.post16-py2.7-win-amd64.egg

4)Run the SlicerConda Installer.



Issues:
If you want simpleitk outside of slicer (since we installed the egg to the system miniconda installation), you'll need to find the DLLs in your Slicer install folder and add them to your path.
