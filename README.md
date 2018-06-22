# Pischool_bnl_label
Pischool Project on image classification

This is the first repo before pushing everything to PiSchool official repo

The web scraper works in python 3.6 with the following command on the terminal

python scrapeImages.py --search "italian passport" --num_images 20 --d 
"passport_images/"

You need to define the number of images that you would like the snippet to fetch, on 
the example is 20. Furthermore, the folder that they are saved is "passport_images" 
and it is in the same folder as the py file. The searching word is the "italian 
passport"

The images are saved without an extension, therefore they need to be renamed so on 
cmd the command is ren *.* *.jpg
