#  Automação de Relatório de Vendas

Este projeto tem como objetivo automatizar a análise de dados de vendas e o envio de relatórios por e-mail.
Ele utiliza Python e bibliotecas de manipulação de dados e automação de e-mail para gerar insights de maneira rápida e eficiente.

 ## Funcionalidades

Importação da base de dados em Excel.

Análise exploratória inicial:

 Exibe as primeiras linhas da base.

 Mostra número de linhas e colunas.

 Verifica tipos de dados e valores nulos.

Indicadores calculados automaticamente:

 Faturamento por loja.

 Quantidade de produtos vendidos por loja.

 Ticket médio por produto em cada loja.

Geração de relatório formatado em HTML com tabelas.

Envio automático por e-mail via SMTP (Gmail).

 ## Tecnologias utilizadas

Pandas → manipulação e análise de dados.

Openpyxl → leitura de arquivos Excel (.xlsx).

Smtplib e EmailMessage → automação de envio de e-mails.

## Exemplo de Relatório Enviado

O e-mail contém:

Tabela com faturamento por loja (valores formatados em R$).

Tabela com quantidade de produtos vendidos.

Tabela com ticket médio por loja.
