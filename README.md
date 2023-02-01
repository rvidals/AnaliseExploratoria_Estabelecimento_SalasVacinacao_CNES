# Análise dos Estabelecimentos de Salas de Vacinação presentes no Cadastro Nacional de Estabelecimentos de Saúde (CNES) 

# Sobre o projeto
O [Cadastro Nacional de Estabelecimentos de Saúde (CNES)](https://wiki.saude.gov.br/cnes/index.php/P%C3%A1gina_principal) é o sistema de informação oficial de cadastramento de informações de todos os estabelecimentos de saúde do país, independentemente de sua natureza jurídica ou de integrarem o Sistema Único de Saúde(SUS). 

O CNES possui as seguintes finalidades:

1.  cadastrar e atualizar as informações sobre estabelecimentos de saúde e suas dimensões, como recursos físicos, trabalhadores e serviços;
  
2.  disponibilizar informações dos estabelecimentos de saúde para outros sistemas de informação;
  
3.  ofertar para a sociedade informações sobre a disponibilidade de serviços nos territórios, formas de acesso e funcionamento;
  
4.  fornecer informações que apoiem a tomada de decisão, o planejamento, a programação e o conhecimento pelos gestores, pesquisadores, trabalhadores e sociedade em geral acerca da organização, existência e disponibilidade de serviços, força de trabalho e capacidade instalada dos estabelecimentos de saúde e territórios.

Dessa forma, uma das demandas que tenho no Departamento de Imunizações e Doenças Imunopreveníveis do Ministério da Saúde (MS) é fazer a validação de estabelecimentos de vacinação de todos os estados a partir da sua localização geográfica. Para tal, necessito adquerir duas bases de dados rlEstabServClass+Ano+Mês e tbEstabelecimento+Ano+Mês (exemplo: rlEstabServClass202212), onde realizo uma série de tratamentos e limpezas para realizar o merge entre as tabelas. Por fim, faço a espacialização das unidades a partir das coordenadas geográficas utilizando um software de geoprocessamento, neste caso o QGIS, e em seguida valido a partir de uma série de informações e análises visuais e interpretativas com o Google Earth e Google Street View.

# Objetivo

Assim, o meu objetivo é avaliar a correlação da presença de sala de imunização, conforme a distribuição espacial a partir do Cadastro Nacional de Estabelecimento de Saúde (CNES), com a coberturas vacinais para o Estado do Acre, no ano de 2022. 

# Bibliotecas aplicadas
- [Pandas](https://pandas.pydata.org/)
- [Numpy](https://numpy.org/doc/stable/)

# Autor
Rogerio Vidal de Siqueira

<a href="https://www.linkedin.com/in/rogerio-vidal-de-siqueira-9478aa136/" target="_blank" rel="noopener noreferrer">Meu Linkdin</a>

