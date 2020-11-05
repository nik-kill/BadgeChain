# BadgeChain
blockchain using python for badge issue and verification

#to install requirements
pip install -r requirements.txt

#to run locally
set FLASK_APP=node_server.py
flask run --port 8000

python run_app.py

#to run multiple nodes 
flask run --port 8001
flask run --port 8002
(on seprate terminals)
similarly can be multiple nodes can be run on different ports.

And then on webrowser

localhost:5000
localhost:8001
localhost:8002

Badges can be issued and then mined which will be synced with every peer  on the network.
