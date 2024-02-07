# fastchat-demo

## Getting started
- make sure you are in the PRP notebook and have open-ai 0.28.1 installed
    * go to the terminal in do `pip list | openai`
    * if nothing if returned, stop the server and make sure you have selected the PRP notebook
- git clone to workspace
- create a env.yaml file
- copy and paste template from env-template.yaml
- paste your API key into API key and the file name under file_name

## Make Changes
- to change the initial prompt for LLM, change `initial_prompt`
- to change the prompt, make changes to the "process paper.txt" section either by changing the pre-processing or by using a new txt file
- to change the LLM, change `model = models.data[X].id`, replace x with the index of the model you desire to use as shown in `print(models)`
  