# DVH
A DVH calculation with Python
# Function
Calculate dose volume histogram (DVH) from DICOM RT Structure data. 
  
# Description: 
filename: dvhcalc.py 

The file contains Methods reading DVH graph from an existing DICOM file or calculating DVH graph from a pair of rtss and rtdose files. 

# Installation

pip install -r requirements.txt

* this work is tested on Python2

# Usage

python dvhcalc.py

* it will read rtss and rtdose file from testdata/ folder and write dvh.png to results/ folder

# License
Copyright (c) 2016 glucee
Copyright (c) 2011-2016 Aditya Panchal
Copyright (c) 2010 Roy Keyes
This file is part of dicompyler-core, released under a BSD license.
   See the file license.txt included with this distribution, also
   available at https://github.com/dicompyler/dicompyler-core/
