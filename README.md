# Batch background remover
## This is a preprocessing script for an ASL classifier: https://colab.research.google.com/drive/1qbhsZ-rFdZz6AC4Vp05SiN_dcjF7JxI8?usp=sharing

This file loads all photos in jpg format from a directry called "TEST_DATA/" and removes all the backgrounds.
The processed images are saved in a directry called "TEST_DATA_MASKED/". 
Files keep their original names, but saved in png.

Results are not prefect, but for what they are needed they get the job done.

This background remover was based off of https://github.com/nikhilroxtomar/Remove-Photo-Background-using-TensorFlow
