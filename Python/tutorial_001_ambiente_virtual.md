### Criar um ambiente virtual

Digite o seguinte comando em um terminal:

```python
python -m venv nomeDoAmbienteVirtual
```

### Instalar uma biblioteca

1. Entre na pasta nomeDoAmbienteVirtual e procure pelo arquivo `activate`. Use o comando `dir` para listar os arquivos no windows.

2. **Após ativar o python do ambiente virtual**, use o comando 
```python
python -m pip install nomeDaBiblioteca
```
para instalar uma biblioteca.

### Criando o arquivo `requirements.txt`

Para criar o arquivo `requirements.txt`, faça:
```python
pip freeze > requirements.txt
```
