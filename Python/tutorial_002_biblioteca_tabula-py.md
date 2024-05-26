# Tutorial de instalação da biblioteca tabula-py do python

## Windows

### Instale o java

- Baixe o instalador a partir do [site oficial](https://www.java.com/pt-BR/download/manual.jsp)

- Abra o cmd do windows e digite a seguinte de comando:

```cmd
where java
```

e copie o caminho.

- Em seguida, abra o editor de variáveis de ambiente e adicione uma variável de ambiente chamada JAVA_HOME (com exatamente esse nome) e cole o caminho copiado nesta variável de ambiente.

- Agora o java está instalado e pronto para ser utilizado nos scripts do python.

### Instale o `tabula-py`

- Abra o cmd e digite a linha de comando

```python
pip install tabula-py
```

- Se tudo der certo com o comando acima, teste a instalação com o comando

```python
pip show tabula-py
```

- Isto imprimirá os detalhes da biblioteca `tabula-py`.
