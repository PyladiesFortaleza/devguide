# O que diabos e para que diabos usaria uma virtualenv?

Quando trabalhamos com muitos projetos diferentes é desejável que as instalações da nossa máquina não intefiram nas intalações  dos nossos projetos. Ai que entra a virtualenv.


# Para criar sua venv(https://tutorial.djangogirls.org/pt/django_installation/)

python3 -m venv venv

# Para executar

venv\Scripts\activate

# Para ver as libs instaladas nessa venv
pip freeze

# Para gerar um arquivo .txt com as dependencias do seu ambiente

pip freeze > requirements.txt

## Eae?
Eae que agora para repassar as configurações do seu ambiente para outras pessoas basta passar o arquivo requirements.txt e :

pip install -r requirements.txt

### Obs 
Nunca versione sua venv
