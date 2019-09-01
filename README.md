# Comparador de Método de Busca

O trabalho consiste em demonstrar uma comparação do número de buscas respectivo aos métodos: Linear, Sentinela, Binário, Interpolação e Indexada.

## Abra com o Link
- Comparador de método de busca: https://comparador-metodos-busca.herokuapp.com/


## Ou execute locamente com virtualenv
- Crie um arquivo virtualenv `virtualenv -p python3 env`
- Ative com `source env/bin/activate`
- Instale os requirimentos `pip install -r requirements.txt`
- Execute o servidor web gunicorn `gunicorn app:app --bind 0.0.0.0:5000 --reload`

## Execução
1) Insira o valor máximo do array
2) Insira o valor chave a ser buscado
3) Insira os 2 métodos de busca a serem comparados
4) Visualize a comparação quanto ao número de buscas