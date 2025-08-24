# mini-rag-app
End to End RAG Application

## Requirements
- Python 3.8 or later 

#### Install python using MiniConda

1) Download and install MiniConda from [here]
2) Create a new environment using the follwing commands:
```bash
$ conda create -n mini-rag python=3.8
```
3) Activate the environment 
```bash 
$ conda activate mini-rag
```

### (optional) Setup your Command line interface for better readabilit

```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$ "
```


## Installation



### Install the required packages

```bash
$ pip install -r requirements.txt
```

### Setup the environment variables

```bash
$ cp .env.example .env

Set your environment variables in the `.env` file. Like `OPENAI_API_KEY` value.
