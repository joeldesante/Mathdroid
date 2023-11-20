# Mathdroid 🤖
A math problem solver with emotions!

This is a very simple project that aims to use freely available language models to assist users with solving reasonably complex math problems!

## How to Get Started

You will need to install the following dependencies before attempting to run Mathdroid.
- Ollama (https://ollama.ai)
- LLaMA2 (Meta Language Model)
- Python3 with Flask

1. Install Ollama (https://ollama.ai). This is used to manage the `llama2` model.
2. Run the commands `ollama pull llama2` then `ollama run llama2`
3. Install Python3 and then install flask `pip3 install flask`
4. Start the server with `flask --app main run`

Once these steps are complete you will be able to access the interface from your browser through `localhost`.

## Why?
I built this for fun.

## Known issues
- Right now endpoints are hardcoded. If you want to host this for public use you will need to change the endpoints so that they don't use `localhost`
- The bot will not always respond with an accurate output. It's a language model, it tries its best.
