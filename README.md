Run Local Server API:
1. First clone the repo
2. cd BAT_NLP_Audio
3. conda create --name Bat_NLP python==3.10
4. conda activate Bat_NLP
5. pip install -r requirements.txt
6. python main_api.py
N.B: After running all the commands in the terminal the local server will be available

Make the API to GLOBAL:
1. First download the ngrok. If you already downloaded the ngrok then ignore it 
2. config the ngrok auth: ngrok config add-authtoken 2Qm8hS1zPhVXiLjEdlI4738tLzF_2QJwGJMK5oTbQD33QSVXS
3. ngrok http --domain=hawkeyes.ngrok.app 8020