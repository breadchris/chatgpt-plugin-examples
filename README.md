# ChatGPT Plugin Examples
This repository contains examples of ChatGPT plugins that demonstrate how to build and deploy plugins on the OpenAI platform. The examples were taken from the [OpenAI Platform documentation](https://platform.openai.com/docs/plugins/examples) and have been added to this repository to make it easier to read and use.

Each example includes a Dockerfile to help with deployment of the plugin. You can use the Dockerfile to build and run the plugin locally or deploy it to a remote server.

## Quick Start
```
git clone https://github.com/breadchris/chatgpt-plugin-examples.git
cd chatgpt-plugin-examples/simple-todo-no-auth
python -m venv env
. env/bin/activate
pip install -r requirements.txt
python serve.py
```

## Examples
Each example is contained in its own directory with its own README.md file. The README.md file provides instructions on how to build and run the plugin using the Dockerfile.

- [Simple todo list plugin with no auth](simple-todo-no-auth/)
- [Simple todo list plugin with service level auth](simple-todo-service-auth/)
- [Simple sports stats plugin](sports-stats-plugin/)
- Semantic search and retrieval plugin (contained in its [own repo](https://github.com/openai/chatgpt-retrieval-plugin))

## Contributing
If you have a new example that you would like to contribute, please fork this repository and submit a pull request with your changes. We welcome contributions from the community!

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
