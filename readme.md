# Talking GPT-3 Chatbot

You can talk to this chatbot without typing. It listens through your microphone and speaks
through your speaker, using GPT-3 to generate responses.

I made this to share the fun I've been having by using GPT-3 as a chatbot. Give it a go,
and tweak the prompts to see what other personalities you can give it!


## Installing dependencies

Create a virtual environment, and install the necessary packages by typing the commands
below into a terminal. Make sure to be in the same directory as this repo!

```shell
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -r requirements.txt
```

After installation, you can enter this newly created environment using:

```shell
source .venv/bin/activate
```

You can exit the virtual environment with this simple command:

```shell
deactivate
```

### OpenAI API Key

You need to update `config.py` with your API Key.

```python
openai_api_key = "{INSERT_YOUR_API_KEY_HERE}"
```


### Running the Chatbot

You can run the chatbot by either opening `chatbot.ipynb` as a Jupyter Notebook, or
by typing `python chatbot.py` on the terminal.

When talking to the AI, please wait for the text "Human:" to appear before you start
talking. It is not listening until that text appears!

### Personality

There are 4 personalities that are currently available:
* default
* sarcastic
* qna
* friend

The `-p` switch can be used to select one. So to choose 'sarcastic', you can type
`python chatbot.py -p sarcastic` into the terminal.





