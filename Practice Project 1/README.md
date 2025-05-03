Before running any of the files do the following:

pip3 install virtualenv 

# create a virtual environment my_env

virtualenv my_env 

# activate my_env

source my_env/bin/activate 

# installing required libraries in my_env

pip install langchain==0.1.11 gradio==5.23.2 transformers==4.38.2 bs4==0.0.2 requests==2.31.0 torch==2.2.1

when you want to run any of the type "python3" and then the file name in the terminal

To use the image_cap file, add a jpg image file to the folder and change the variable img_path to the files name
