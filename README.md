# FER (Facial Expression Recognition)
Identificador de expressões faciais implementado em rede neural convolucional.

Trabalho de concusão pós graduação.

Base de dados obtida em:<br>
https://www.kaggle.com/datasets/msambare/fer2013


Apresentação rápida no Canva<br>
https://www.canva.com/design/DAF_llzhgN0/lzoGuQ1_j8d9AuPwSNl30g/view?utm_content=DAF_llzhgN0&utm_campaign=designshare&utm_medium=link&utm_source=editor
<br><br>
Instruções:<br>
1) arquivo FER-2013 gerador da rede_v3.ipynb
responsável por gerar a rede neural e salvar os dados dos "pesos" da rede nos arquivos rede_FER-2013_v3.h5 e rede_FER-2013_v3.json

2) arquivo Testador rede FER-2013_v3.ipynb
aplicação feita para rodar a rede com os pesos já salvos lendo a partir dos arquivos rede_FER-2013_v3.h5 e rede_FER-2013_v3.json

3) arquivos rede_FER-2013_v3.h5 e rede_FER-2013_v3.json
são os arquivos gerados pela primeira aplicação responsável por salvar todo o processamento da rede.
obs: o github não me permite upar arquivos maiores que 25MB, então o arquivo rede_FER-2013_v3.h5 foi quebrado em dois com o winrar (part1 e part2) e precisa ser descompactado)

4) Pasta Base de Dados
Aqui vocês deve salvar os arquivos obtidos através do link do kaggle que já estão subdivididos em treino e teste. Mantenha a estrutura original.
https://www.kaggle.com/datasets/msambare/fer2013

obs: os arquivos foto (x).jpg da pasta Capturas não serão fornecidos por serem pessoais, mas nessa pasta você pode adicionar os arquivos que quiser para que a rede faça o reconhecimento.
