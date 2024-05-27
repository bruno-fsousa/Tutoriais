# Instalação do pytesseract, do tesseract-ocr e do opencv-python:

## No Linux:

```bash
pip install opencv-python
pip install pytesseract
```

### Instale os pacotes de idiomas e o pacote para lidar com equações matemáticas.

```bash
sudo apt install -y tesseract-ocr
sudo apt install -y tesseract-ocr-por
sudo apt install -y tesseract-ocr-spa
sudo apt install -y tesseract-ocr-equ
```

## No Windows

### Instalação do ``pytesseract``
```cmd
pip install pytesseract
```

### Instalação do ``tesseract-ocr``
- Baixe o instalador do ``tesseract-ocr`` para o Windows no [Link](https://github.com/UB-Mannheim/tesseract/wiki).
- Durante a instalação copie o caminho da pasta do ``Tesseract-OCR``. Geralmente o caminho completo é
```cmd
C:\Program Files\Tesseract-OCR
```
- Após a instalação, talvez seja necessário adicionar o caminho completo da pasta ``Tesseract-OCR`` ao ``PATH`` do windows.
- Durante a instalação, adicione os pacotes de idioma, pelo menos o português, o espanhol e o de símbolos matemáticos. Veja o [tutorial](https://codetoprosper.com/tesseract-ocr-for-windows).

### Instalação <u>posterior</u> do pacote de idiomas para o tesseract-OCR:

Caso tenha esquecido de instalar os pacotes de idiomas durante a instalação, uma alternativa é adicioná-los manualmente conforme o seguinte passo.

- Baixe os arquivos de idiomas no seguinte link: [GitHub - tessdata](https://github.com/tesseract-ocr/tessdata)
  
  Português: `por.traineddata`

  Espanhol: `spa.traineddata`

  Em seguida, coloque os arquivos na pasta ``tessdata``, que se encontra dentro da pasta ``Tesseract-OCR``.

## Links Úteis:
- [Vídeo Tutorial](https://www.youtube.com/watch?v=GMqFZ7f0dy4)
- [Documentação Oficial](https://github.com/UB-Mannheim/tesseract/wiki)
- [Instalação no Windows](https://ironsoftware.com/csharp/ocr/blog/ocr-tools/tesseract-ocr-windows/)
- [Guia de Instalação](https://codetoprosper.com/tesseract-ocr-for-windows)
