Pallone et al., 2025
Orbital forcing of the eastern equatorial Pacific thermocline in the late Pleistocene
Source Code and Source Files

1. System Requirements
System requirements for installing Anaconda can be found here (https://docs.anaconda.com/anaconda/system-requirements/) and are restated below.

Anaconda System requirements (As of 2024-10-21)
	•	License: Free for individuals and small organizations (<200 employees). A paid license is required for larger organizations and anyone embedding or mirroring Anaconda. See the TOS for details.
	•	Operating system: Windows 10 or later, 64-bit macOS 10.15+ (for Intel) or 64-bit macOS 11.1+ (for Apple Silicon), or Linux, including Ubuntu, RedHat, CentOS 7+, and others.
	•	If your operating system is older than what is currently supported, you can find older versions of the Anaconda installers in our archive that might work for you. See Using Anaconda on older operating systems for version recommendations.
	•	System architecture: Windows - 64-bit x86; MacOS - 64-bit x86 or Apple Silicon (ARM64); Linux - 64-bit x86, 64-bit aarch64 (AWS Graviton2), or s390x (Linux on IBM Z & LinuxONE).
	•	The linux-aarch64 Miniconda installer requires glibc >=2.26 and thus will not work with CentOS 7, Ubuntu 16.04, or Debian 9 (“stretch”).
	•	The linux-aarch64 package builds might not be compatible with certain Raspberry Pi setups, as Anaconda uses compiler options that target the server-class Neoverse N1/N2 microarchitecture.
	•	Minimum 5 GB disk space to download and install.

2. Installation Guide
This Jupyter notebook was designed using Python 3.9.13.

Anaconda (https://www.anaconda.com/download/) includes all the packages required to run the Source Code in Jupyter notebook. 
Installation instructions for Anaconda can be found here: https://docs.anaconda.com/anaconda/install/. Installation on a typical desktop computer should take approximately 15 minutes. 

You can also download the individual packages listed below.
	•	Jupyter: https://jupyter.org/install 
	•	SciPy: https://scipy.org/
	•	NumPy: https://numpy.org/
	•	Pandas: https://pandas.pydata.org/ 
	•	Matplotlib: https://matplotlib.org/stable/install/index.html 
	•	Astropy: https://docs.astropy.org/en/stable/install.html 
	•	Pillow (PIL): https://pypi.org/project/pillow/
	•	Xarray: https://docs.xarray.dev/en/latest/getting-started-guide/installing.html
	•	Cartopy: https://pypi.org/project/Cartopy/

3. Demo
Instructions to open and run a Jupyter notebook in Anaconda can be found here: https://docs.anaconda.com/ae-notebooks/user-guide/basic-tasks/apps/jupyter/. Expected outputs are provided in Pallone_25_Data_4.xlsx, Pallone_25_Data_5.xlsx, and Pallone_25_Data_6.xlsx, as well as in the manuscript main text and supplemental figures. The expected run time to replicate results presented in this manuscript on a typical desktop computer is under 5 minutes. 

4. Instructions for use
Instructions for use are included in the Jupyter notebook. This also includes instructions for reproducing all quantitative results in the manuscript. 
