# vancouver-datajam-2023
A repo containing material for a workshop on Gradio, which was run as part of Vancouver Datajam 2023

Author: Sampoorna Biswas

This workshop demonstrates how to develop quick and easy UI for ML-based apps using (Gradio)[https://github.com/gradio-app/gradio].

To start, click here or on the button below:

Start Workshop

Note: It may take a few seconds for the notebook to load.

Scroll down to the Running it locally section if you prefer to run things locally.

Workshop level: intermediate to advanced
Background knowledge
Familiarity with JupyterLab.

## Workshop Structure
1. Introduction
2. Setup
3. Building a hello world app with Gradio
4. Building a text to image generation app with Gradio
5. Building a conversational chatbot with Gradio

Documentation

## Pre-requisites and Setup

1. Python 3.6 or higher
2. Install [anaconda](https://docs.anaconda.com/free/anaconda/install/)
3. Create a [GitHub account](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account)
4. Create an [OpenAI account](https://platform.openai.com/signup)

```
    # clone the repository
    git clone https://github.com/sampoorna/vancouver-datajam-2023.git
    cd vancouver-datajam-2023

    # create a virtual environment
    python3 -m venv env
    source env/bin/activate

    # install dependencies
    pip install invoke
    invoke setup --from-lock
```