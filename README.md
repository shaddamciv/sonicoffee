# SonicCoffAI

Sonic Coff AI is a site that allows inference of news articles and creates a loop to trade based on the latest trend spotted by user. 
We used Zerepy and Allora alongwith Sonic to trade WETH to USDC and vice versa depending on news information. 

Currently works with both openai and ollama models.

The frontend is used for non developers to quickly setup and get it running.

!! Note this repo is meant to run on a local machine and not for server - client purposes.

## Installation
Steps

1. Fork this repo into your laptop 
2. Install python 3.11 and poetry
3. cd ZerePy
4. Run Backend - ```poetry run python main.py --server```
5. Run Frontend - ``` ```

## Postman examples

Refer the following file - coffai.postman_collection.json

Additional API for creating wallet 

curl -X POST "http://localhost:8000/agent/setenv" \
     -H "Content-Type: application/json" \
     -d '{
           "OPENAI_API_KEY": "sk-"
         }'