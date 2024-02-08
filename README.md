# Meu TCC

Orientação para executar o Sistema de Informações Geográficas no ambiente Flask.

## Execução

Para executar a aplicação, o arquivo ZIP disponível no [Google Drive](https://drive.google.com/file/d/1INNV341FqIuCswYtEQI3Le1K-UBa_13i/view?usp=sharing) deve ser extraído dentro do diretório principal. Onde:
- Na pasta "cidades" se encontram os arquivos lidos pela aplicação;
- O arquivo "dataset.xlsx" é o dataset anonimizado disponibilizado pela empresa;
- As pastas static/imagens é o local onde os gráficos gerados vão ser armazenados.

Depois, no seu terminal, acesse o diretório principal e execute o comando "flask run"

Observações:
- Antes da execução, certifique-se de que seu ambiente possua o Python instalado. E também, o framework e as bibliotecas seguintes:
  - Flask (pip install Flask)
  - Folium (pip install folium. Provavelmente, você deverá instala-lo globalmente)
  - Scipy (pip install scipy)
  - Matplotlib (pip install matplotlib)
  - Pandas(pip install pandas)
  - Openpyxl (pip install openpyxl)
- O arquivo "dataset.xlsx" não é utilizado pela aplicação, somente a pasta "cidades".
