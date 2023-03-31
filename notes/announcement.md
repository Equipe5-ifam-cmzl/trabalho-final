## 1. Ambiente Python

Eu recomendo que você crie um ambiente virtual com a lib [virtualenv](https://virtualenv.pypa.io/en/latest/installation.html) antes de executar os notebooks

E SUPONDO que você já instalou o virtualenv na sua máquina, execute os seguintes comandos:

1. Para gerar um ambiente virtual:

```shell
$ python -m vitualenv venv
```

(OBS.: a palavra 'venv' é o nome da pasta onde seu ambiente virtual estará hospedado, pode mudar se quiser!)

2. Ative o ambiente virtual na CLI com o comando (usando Git Bash):

```shell
$ source venv/Scripts/activate
```

3. Com isso, você poderá baixar as libs com o seguinte comando:

```shell
$ pip install -r requirements.txt
```

E pronto, ambiente pronto e configurado! ✌️🤓

## 2. Com relação a Lib do Tensorflow

Bem, você deverá instalar essa lib via-CLI (com permissões de Adm)

Passo a passo:

1. Clique com o botão direito do mouse no icone do seu terminal (prefêrencia Git Bash ou Windows Terminal).

2. Selecione o 'Executar como Administrador'

3. Rode o comando: 

```shell
$ pip install tensorflow
```
