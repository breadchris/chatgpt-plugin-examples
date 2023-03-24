# Simple TODO plugin, No Auth

## Run
```bash
python -m venv env
. env/bin/activate
pip install -r requirements.txt
python serve.py
```

## Build and Run with Docker
```shell
docker build . -t simple-todo-plugin-no-auth
docker run -it --rm -p 8080:8080 simple-todo-plugin-no-auth
```
