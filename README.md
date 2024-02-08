# Meu TCC

O Sistema de Informações Geográficas para Análise de Falhas da Rede FTTH pode ser acessado [aqui](https://web-production-49e56.up.railway.app/). Abaixo, seguem as orientações para executar o Sistema de Informações Geográficas no seu ambiente Flask.

## Execução

Para executar a aplicação em seu computador, você pode, primeiramente, fazer o download do arquivo ZIP deste repositório e extraí-lo dentro do diretório principal. Onde:
- Na pasta "cidades" se encontram os arquivos lidos pela aplicação;
- O arquivo "dataset.xlsx" é o dataset anonimizado disponibilizado pela empresa;
- As pastas static/imagens é o local onde os gráficos gerados vão ser armazenados;
- A pasta templates é onde se localiza as páginas HTML;
- E o arquivo app.py é onde se localiza todo o script Python.

Depois, no seu terminal, acesse o diretório principal e execute o comando "flask run" ou "python app.py".

Observações:
- Antes da execução, certifique-se de que seu ambiente possua o Python instalado. E também, o framework e as bibliotecas seguintes:
  - Flask (pip install Flask)
  - Folium (pip install folium. Provavelmente, você deverá instala-lo globalmente)
  - Scipy (pip install scipy)
  - Matplotlib (pip install matplotlib)
  - Pandas(pip install pandas)
  - Openpyxl (pip install openpyxl)
- Os arquivos "dataset.xlsx", "Procfile" e "requirements.txt" não são utilizados pela aplicação.
