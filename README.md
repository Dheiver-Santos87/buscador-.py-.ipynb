# buscador-.py-.ipynb

O código acima realiza a busca de um termo específico em arquivos de extensão .py e .ipynb em centenas de diretórios e subdiretórios.

Para isso, ele utiliza a função os.walk(), que percorre todos os arquivos e diretórios do diretório especificado e seus subdiretórios. Em seguida, para cada arquivo, ele verifica se a extensão é .py ou .ipynb, e se for, tenta abri-lo com a codificação UTF-8.

Caso ocorra algum erro de codificação, como o erro "UnicodeDecodeError", o código exibe uma mensagem de erro e continua a execução.

Após a leitura do arquivo, o código percorre cada linha do arquivo e verifica se o termo específico está presente na linha. Se estiver, os resultados são armazenados em uma lista de dicionários, que é posteriormente convertida em um dataframe com o pandas.

Esse código pode ser útil em diversas situações, como por exemplo, para buscar um determinado código ou função em arquivos de um projeto, ou para realizar uma pesquisa em um grande número de arquivos de forma automatizada.



