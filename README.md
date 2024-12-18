# Descrição
O "Mosdepth2csv" é um script desenvolvido para processar arquivos nomeados como "thresholds.bed.gz", gerados pela ferramenta mosdepth, que é configurada com o parâmetro --threshold. O objetivo deste script é extrair informações relevantes desses arquivos e transformá-las no formato CSV (valores separados por vírgulas). Posteriormente, esses arquivos CSV são agrupados e comprimidos em um arquivo zip, para facilitar o armazenamento ou a distribuição. Esse script funciona como uma ferramenta para converter e organizar os dados produzidos pelo mosdepth em um formato mais acessível e gerenciável.

# Uso:

Para usar o mosdepth, primeiro baixe o script via git clone:
```
git clone https://github.com/jlpitta/mosdepth2csv.git
```

Dentro do diretório recém-baixado mosdepth2csv, você pode encontrar não apenas o script mosdepth2csv, mas também alguns arquivos "thresholds.bed.gz" que servem como exemplos de entrada. Além disso, há um arquivo chamado Mosdepth_Feb29_094836.zip, que é um exemplo de saída gerado pelo script. O formato do nome do arquivo de saída indica o dia e a hora em que o arquivo foi criado (neste exemplo, 29 de fevereiro às 09:48:36). Isso é útil para distinguir facilmente os resultados de várias execuções do script.

Para testar o script, basta executar o script mosdepth2csv com uma das opções abaixo:
```
./mosdepth2Csv
```
ou
```
bash mosdepth2Csv
```
Para facilitar o uso do script, adicione o caminho do script à variável de ambiente PATH ou crie um link simbólico na pasta /bin do usuário.

Para executar o mosdepth2csv nos seus dados, navegue até o diretório que contém os resultados gerados pelo mosdepth (com arquivos nomeados como "thresholds.bed.gz"). Execute o script a partir deste diretório, fornecendo o caminho completo para o script ou simplesmente digitando "mosdepth2csv" se o script estiver no PATH ou adicionado à pasta /bin do usuário.
