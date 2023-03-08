# Api

Api rest + swagger + flask + python

## Projeto utiliza
- Ubuntu 22.04.2 LTS
- vscode
- Python


## Instalar os pacotes 
```
sudo apt install python3-pip
sudo apt install python3.10-venv
```

## Para rodar o projeto
´´´
python3 -m venv venv
export FLASK_APP=main.py
source venv/bin/activate

pip install flask_restplus
pip install flask_restx
pip install flask
pip install Werkzeug

python3 main.py
´´´

## Para limpar os pycache

```
find . | grep -E "(__pycache__|\.pyc|\.pyo$)" | xargs rm -rf
```


