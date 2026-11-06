## RAG-APP

This is an implementation of RAG App for question answering.

## Requirements 
`the operating system is Fedora so all the commands for Linux`

- Python 3.12 or later

### Install Python using UV

1) Download and install UV form [here] curl -LsSf https://astral.sh/uv/install.sh | sh
2) create new environment using the following commands
```bash
$ uv venv name-of-your-venv --python 3.12
```
3) Activate you Environment
```bash
$ source name-of-your-venv/bin/activate
```

### Install the requirements packages

```bash
$ uv add -r requirements.txt
```

### Run FastAPI Server 
```bash
$ uvicorn main:app --reload --host 0.0.0.0 --port 8000
```