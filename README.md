# Desafio para Vaga de Desenvolvedor PHP
## O objetivo desta tarefa é testar seus conhecimentos e domínio com a linguagem PHP.

Os tópicos que analisaremos são:
* O design da solução fornecida
* A qualidade do código
* O teste de unidade
* Aderência aos requisitos

# Seu desafio
## Desenvolver um tradutor do Layout Febraban Conta Eletrônica de Telecomunicações - V3R0 em PHP (Laravel), Mysql ou SQL Server, HTML, CSS e Bootstrap.

https://portal.febraban.org.br/pagina/3176/33/pt-br/layout-conta-eletronica

Estrutura Padrão do Arquivo
O layout é composto por 10 tipos de registro, identificados nas duas primeiras posições de cada registro.

- Tipo 00 - Header - Apenas um por arquivo
- Tipo 10 - Resumo - Apenas um por recurso
- Tipo 20 - Endereço(s) dos Recursos - Apenas um por recurso
- Tipo 30 - Chamadas - Nenhum, um ou mais por recurso.
- Tipo 40 - Serviços - Nenhum, um ou mais por recurso.
- Tipo 50 - Descontos - Nenhum, um ou mais.
- Tipo 60 - Planos - Nenhum, um ou mais.
- Tipo 70 - Ajustes - Nenhum, um ou mais.
- Tipo 80 - Nota Fiscal - Um ou mais por arquivo
- Tipo 90 - Informativo (Valor gerencial) - Nenhum, um ou mais
- Tipo 99 - Trailler - Apenas um por arquivo

A FEBRABAN - Federação Brasileira de Bancos - é a principal entidade representativa do setor bancário brasileiro. Fundada em 1967, na cidade de São Paulo, é uma associação sem fins lucrativos que tem o compromisso de fortalecer o sistema financeiro e suas relações com a sociedade e contribuir para o desenvolvimento econômico, social e sustentável do País.

Requisitos obrigatórios:

- O sistema deve ter uma identidade legal utilizando Bootstrap 4.
- A solução apresentada deve ter um botão para upload do arquivo da FEBRABAN.
- A solução apresentada deve ter um botão para consultar o histórico de todos os arquivos processados, contendo as informações compostas pelo "Tipo 00 - Header" do layout FEBRABAN. Apenas uma lista em formato de tabela simples.
- Observar todas as regras da aba "Introdução" no layout FEBRABAN.
- Todos os dados devem ser carregados no banco de dados.
- Os valores monetários estão representados em REAIS, contudo, no momento da importação do arquivo FEBRABAN, o sistema deve também identificar e calcular o valor em EURO e em DÓLAR através da API https://docs.awesomeapi.com.br/api-de-moedas - Caso prefira poderá utilizar outra API que seja pública e gratuita.


