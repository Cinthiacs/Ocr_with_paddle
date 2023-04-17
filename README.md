# Ocr_with_paddle
Algorítimo desenvolvido em Python através da IDE JupyterNotebook que utiliza o reconhecimento óptico de caracteres (OCR) para extrair informações de documentos pessoais (RG e CNH) e fazer correções ortográficas nas informações extraídas.

## Instalação
Antes de executar o programa, é necessário instalar as seguintes bibliotecas:

* paddlepaddle==2.2.2  https://mirror.baidu.com/pypi/simple
* paddleocr
* symspellpy
* pyspellchecker
* opencv-python

### Você pode instalá-las usando o gerenciador de pacotes pip:

*  !python -m pip install paddlepaddle==2.2.2 -i https://mirror.baidu.com/pypi/simple
* !pip install paddleocr
* !python -m pip install -U symspellpy
* !pip install pyspellchecker
* !pip install opencv-python

### Como usar

```bash
# clonar repositório
git clone https://github.com/Cinthiacs/Ocr_with_paddle.git
```

* Para usar o programa, execute o arquivo "Ocr_paddlepaddle.ipynb" em uma IDE Jupyter.
* Ao executar, ele lerá uma lista de nomes e sobrenomes em formato de texto e os converterá em um arquivo CSV. Em seguida, o programa lê duas imagens: uma CNH e um RG. 
* O OCR Paddle é usado para extrair informações dessas imagens.
* Extrai as informações de texto como CPF, nome, data de nascimento, data de emissão, naturalidade e filiação das imagens. Em seguida, é usada a biblioteca PySpellChecker em português "pt" para corrigir possíveis erros ortográficos nas informações extraídas.

* O programa imprime as informações extraídas e as correções ortográficas na saída do console.

## Contribuição
Sinta-se livre para contribuir para este projeto enviando pull requests.

### Autora
Cinthia Cavalheiro.
