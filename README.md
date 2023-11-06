# Top 10 vídeos em alta YouTube

## Objetivo
Este projeto busca analisar os 10 vídeos mais populares do YouTube a cada dia para qualquer região do mundo. Para isso usaremos a API do YouTube que é disponível gratuitamente para  pequenas consultas.    

Através do notebook disponível [aqui](https://github.com/jeanmatheuss/API-youtube/blob/main/api-youtube.ipynb) podemos gerar um arquivo csv que contém as seguintes infos:

- video: Nome do vídeo
- views: Quantidade de vizualizações
- likes: Quantidade de gostei
- comentarios: Quantidade de comentários
- subscribers: Quantidade de inscritos no canal
- publicacao: Data da publicação
- link_video: Link direto para o vídeo
- horas-publicacao: Quantidade de horas que o vídeo foi publicado
- views/hora: Quantidade de vizualização por hora

A ídeia é montar um banco de dados diário para com essas informações e que sejam atualizadas diariamente em um horário determinado. 

E com isso analisar os tipos de vídeos que estão em alta, ou até mesmo algum canal que deseja verificar quais vídeos do próprio canal estão bombando.

## Visão Geral do Projeto
O projeto consiste em:

1. Coleta de Dados: Utilizando a API do YouTube, coletamos informações detalhadas sobre os vídeos em alta do YouTube. Isso inclui metadados como título, visualizações, likes, comentários e data de publicação.

2. Conversão de Categoria: Utilizamos a API do YouTube para converter os IDs numéricos das categorias em nomes de categoria legíveis, enriquecendo ainda mais nossos dados.

3. Armazenamento de Dados: Armazenamos os dados coletados em um formato que nos permite acessá-los facilmente para futuras análises e consultas.

4. Análise de Dados: Utilizando o *Power BI* faremos análises aprofundadas desses dados para extrair insights valiosos. Isso envolve identificar tendências, calcular métricas-chave e criar visualizações informativas.

## Pré-requisitos
Antes de executar o projeto, você precisará das seguintes dependências:

- Chave de API do YouTube: Você precisará de uma chave de API do YouTube para acessar a API do YouTube. Você pode obter uma chave em [Google Cloud Console](https://console.cloud.google.com/).

- Python: O projeto é implementado em Python, portanto, é necessário ter o Python instalado em seu ambiente.

- Bibliotecas Python: Certifique-se de instalar as bibliotecas Python necessárias, incluindo [google-api-python-client](https://github.com/youtube/api-samples/blob/master/python/README.md) para acessar a API do YouTube e pandas para manipulação de dados.


