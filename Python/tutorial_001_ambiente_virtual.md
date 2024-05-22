# Tutorial de criação de ambiente virtual do python

## Windows

### Criar um ambiente virtual

Digite o seguinte comando em um terminal:

```python
python -m venv nomeDoAmbienteVirtual
```

### Instalar uma biblioteca

1. Entre na pasta nomeDoAmbienteVirtual com o comando
```cmd
cd c:\Caminho\completo\do\nomeDoAmbienteVirtual
```
e procure pelo arquivo `activate`. Use o comando
```cmd
dir /s /b | findstr /i /r "\\activate$"
```
Use o comando `dir` para listar os arquivos no windows.

3. Para ativar o ambiente virtual, entre na pasta que contém o arquivo `activate` e use o comando
```cmd
.\activate
```

1. **Após ativar o ambiente virtual**, use o comando
```python
python -m pip install nomeDaBiblioteca
```
para instalar uma biblioteca.

### Criando o arquivo `requirements.txt`

Para criar o arquivo `requirements.txt`, faça:
```python
pip freeze > requirements.txt
```

## Linux

1. Para criar um ambiente virtual, abra um terminal do linux e digite o seguinte comando:
```bash
cd ~/ && python -m venv /Caminho/Completo/da/Pasta/AmbienteVirtual
```

2. **Ative o ambiente virtual.** Para isto:

- Entre na pasta `AmbienteVirtual` com o comando
```bash
cd /Caminho/Completo/da/Pasta/AmbienteVirtual
```

- Procure pelo arquivo `activate` através do comando
```bash
find . -type f -iname "activate" | grep -i "activate$"
```

- Execute o comando `activate` através do comando
```bash
source /Caminho/Completo/do/Arquivo/"activate$"
```

3. **Instalação de bibliotecas**

- Após ativar o ambiente virtual, entre na pasta `AmbienteVirtual` e use o comando
```python
python -m pip install nomeDaBiblioteca
```
para instalar uma biblioteca.

4. **Criação do arquivo `requirements.txt`**

Para criar o arquivo `requirements.txt`, execute o comando
```python
pip freeze > requirements.txt
```