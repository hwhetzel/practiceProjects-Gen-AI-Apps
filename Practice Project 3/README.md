**Before running any of the files, do the following**

**Create and activate a Python virtual environment**

`pip3 install virtualenv`

`virtualenv my_env`

`source my_env/bin/activate`

**Install the required Python libraries**

`pip install transformers==4.36.0 torch==2.1.1 gradio==5.23.2 langchain==0.0.343 ibm_watson_machine_learning==1.0.335 huggingface-hub==0.28.1`

**Install ffmpeg (for handling audio files)**

`sudo apt update`

`sudo apt install ffmpeg -y`

**Add an mp3 file of your choice (make sure its not that long)**

**To run the final product, type in the terminal**

`python3 speech_analyzer.py`