# abrir o anaconda Prompt 

# Primeiro passo é entrar dentro da pasta do projeto utilizando

    cd caminhodapasta

# Próximo passo é entrar dentro da variável de ambiente utilizando 

    conda activate lpbotvenv

# Sempre que realizar uma alteração nas intents ou respostas, utilizar o comando 

    rasa train

# Após encerrar o processo de treinamento, utilizar o comando

    rasa shell

# Sequencia para adicionar uma intents

    1. Adicionar na nlu
    2. Adicionar as respostas no domain
    3. Adicionar a intent e as respostas nas regras (Ligar uma intent com uma resposta)

# Rodar o servidor rasa para utilizar em plataformas externas

    rasa run --cors "*" --debug
