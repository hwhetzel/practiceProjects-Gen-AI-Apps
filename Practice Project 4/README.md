**Before running, do the following in order**

pip3 install virtualenv 

**create a virtual environment my_env**

virtualenv my_env 

**activate my_env**

source my_env/bin/activate 

git clone https://github.com/sinanazeri/build_own_chatbot_without_open_ai.git

mv build_own_chatbot_without_open_ai build_chatbot_for_your_data

cd build_chatbot_for_your_data

pip install -r requirements.txt

pip install langchain-community


**Once the steps are all done replace the `worker.py` file in the build_chatbot_for_your_data folder with the `worker.py` file from the repo**

**To run the app, type the following into the terminal**

`python3 server.py`

**The file you'll input should be a pdf**