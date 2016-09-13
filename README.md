# pyCaffeSRCNN

http://mmlab.ie.cuhk.edu.hk/projects/SRCNN.html

* srcnn_gen_filter.py
==
this may help you test SRCNN without building 'matcaffe'
you have to use SRCNN with your trained model of SRCNN but you don't want to build 'matcaffe' 

this python script can generate matrix compatible with SRCNN test matlab code

{your_download_path}/srcnn_gen_filter.py -caffemodel {the location of caffemodel you trained} -mat {the location of srcnn_mat.prototxt}

after you call this script, you can find 'filter.mat' file in the same {location of this project}
and then you can test your filter in Test code for SRCNN - http://mmlab.ie.cuhk.edu.hk/projects/SRCNN/SRCNN_v1.zip
