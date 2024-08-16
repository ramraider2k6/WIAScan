# WIAScan.py
Quick and dirty Python app to use **WIA** (Windows Image Aquisition API) scanning interface<BR>
The command line options are<BR>
**–colour**<BR>
**–y**<BR>
**–output**<BR><BR>

If you omit –colour then you get greyscale output<BR>
To force overwrite a jpeg file (JPG) use –y<BR>
And –output should be in quotes "path here" its the full file path you want to save<BR>
eg:<BR>
WIASCAN.py -colour -y -output "out\test01.jpg"
