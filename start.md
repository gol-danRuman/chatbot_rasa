python3 --verion
# Rasa support python 3.6 or 3.7 version
python3 -m venv ./venv
# Create virtual env for python
source ./venv/bini/activate
# To activate venv
pip install rasa
# to install rasa
rasa init
# to initialize rasa project
# First creates a mood bot about being sad or happy
data/nlu.yml => for intent
data/stories.yml => for dialogues
domain.yml => register intent(nlu) or dialogues(stories)
# Changes to make own bot
rasa train 
# to train model and add changes
