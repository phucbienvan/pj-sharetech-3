
```
python3 -m venv venv
source venv/bin/activate
export PYTHONPATH=.
cp .env.example .env
pip install python-dotenv google-generativeai
python3 main.py --prompt=input text
```
