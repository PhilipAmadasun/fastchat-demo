# fastchat-demo

## Getting started
- log into http://jupyterhub.sdsu.edu/ using your sdsu credentials, select your resources (minimal is fine) and select "Stack PRP" image. [Here is a guide for reference](https://sdsu-research-ci.github.io/instructionalcluster/students/loggingin)
- make sure you have open-ai 0.28.1 installed
    * go to the terminal and enter `pip list | grep openai`
    * if nothing if returned, [stop the server](https://sdsu-research-ci.github.io/instructionalcluster/faqs/stopnotebook) and make sure you have selected the "Stack PRP" Image from the list of container images
- git clone this repo into your workspace
- create a `env.yaml` file
- copy and paste template from `env-template.yaml`
- paste your API key into API key and the file name under file_name if not using `paper.txt`

## Make Changes
- click into the `fastchat-demo.ipynb` notebook
- to change the initial prompt for LLM, change `initial_prompt`
- to change the prompt, make changes to the "process paper.txt" section either by changing the code for pre-processing and/or by using a new txt file
- to change the LLM, change `model = models.data[X].id`, replacing X with the index of the model you desire to use as shown in `print(models)`
  
