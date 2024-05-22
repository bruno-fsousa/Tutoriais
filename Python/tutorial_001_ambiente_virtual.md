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
