# Q&Aid
# Core logic

## Introduction

The code contains scripts for testing and deploying the core logic behind Q&Aid.

## Models

### VQA
TODO
https://github.com/aioz-ai/MICCAI19-MedVQA


## Prerequisites

```
pip install -r requirements.txt
```

## Run the server

```
uvicorn main:app --host 0.0.0.0 --port 8000
```

GET http://127.0.0.1:8000/models should return the list of available models.