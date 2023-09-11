# vancouver-datajam-2023
A repo containing material for a workshop on Gradio, which was run as part of Vancouver Datajam 2023

Author: Sampoorna Biswas

This workshop demonstrates how to develop quick and easy UI for ML-based apps using (Gradio)[https://github.com/gradio-app/gradio].

Workshop level: intermediate to advanced
Background knowledge: 
- Basic knowledge of Python
- Familiarity with Jupyter notebooks

## Workshop Structure
1. Introduction
2. Setup
3. Building a hello world app with Gradio
4. Building a text to image generation app with Gradio
5. Building a conversational question-answering chatbot with Gradio

## Pre-requisites and Setup

1. Python 3.6 or higher
2. A [Google account](https://accounts.google.com/signup/v2/createaccount), if you want to use Colab. Alternatively you can set it up on your local machine.
3. Create a [GitHub account](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account)
4. Create an [OpenAI account](https://platform.openai.com/signup)

### Running the notebooks on Colab
1. Clone the repository
```
    git clone https://github.com/sampoorna/vancouver-datajam-2023.git
    cd vancouver-datajam-2023
```
2. Go to [Google Colab](https://colab.research.google.com/)
3. File -> Upload notebook (you might be prompted to sign up if you are not logged in). Make sure you use this option and _not_ the upload icon on the left sidebar.
4. Find the notebooks in your local machine and upload just `hello-world.ipynb` for now.
5. Open the left sidebar and use the upload icon to add `requirements.txt`. These are the Python packages that you will need to install.
6. Insert a new code cell at the very top of the notebook and type in `!pip install -r requirements.txt`. Running this cell will install all the packages.
7. That's it! You should be able to run the notebook on the Colab interface.

Additional notes: 
1. Each notebook is uploaded to its own space so you will need to repeat this when you switch to a different notebook. 
2. When uploading files that a notebook needs to access, always use the upload icon on the left sidebar. To access these files, you can directly use the file name.