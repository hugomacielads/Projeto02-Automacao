# Automação de Indicadores

### Objetivo: Treinar e criar um Projeto Completo que envolva a automatização de um processo feito no computador

### Descrição:

Imagine que você trabalha em uma grande rede de lojas de roupa com 25 lojas espalhadas por todo o Brasil.

Todo dia, pela manhã, a equipe de análise de dados calcula os chamados One Pages e envia para o gerente de cada loja o OnePage da sua loja, bem como todas as informações usadas no cálculo dos indicadores.

Um One Page é um resumo muito simples e direto ao ponto, usado pela equipe de gerência de loja para saber os principais indicadores de cada loja e permitir em 1 página (daí o nome OnePage) tanto a comparação entre diferentes lojas, quanto quais indicadores aquela loja conseguiu cumprir naquele dia ou não.

Exemplo de OnePage:

Nosso papelc como analista de dados é conseguir criar um processo da forma mais automática possível para calcular o OnePage de cada loja e enviar um email para o gerente de cada loja com o seu OnePage no corpo do e-mail e também o arquivo completo com os dados da sua respectiva loja em anexo.

Ex: O e-mail a ser enviado para o Gerente da Loja A deve ser como exemplo

### Arquivos e Informações Importantes

- Arquivo Emails.xlsx com o nome, a loja e o e-mail de cada gerente.

- Arquivo Vendas.xlsx com as vendas de todas as lojas. Obs: Cada gerente só deve receber o OnePage e um arquivo em excel em anexo com as vendas da sua loja. As informações de outra loja não devem ser enviados ao gerente que não é daquela loja.

- Arquivo Lojas.csv com o nome de cada Loja

- Ao final, sua rotina deve enviar ainda um e-mail para a diretoria (informações também estão no arquivo Emails.xlsx) com 2 rankings das lojas em anexo, 1 ranking do dia e outro ranking anual. Além disso, no corpo do e-mail, deve ressaltar qual foi a melhor e a pior loja do dia e também a melhor e pior loja do ano. O ranking de uma loja é dado pelo faturamento da loja.

- As planilhas de cada loja devem ser salvas dentro da pasta da loja com a data da planilha, a fim de criar um histórico de backup

### Indicadores do OnePage

- Faturamento -> Meta Ano: 1.650.000 / Meta Dia: 1000
- Diversidade de Produtos (quantos produtos diferentes foram vendidos naquele período) -> Meta Ano: 120 / Meta Dia: 4
- Ticket Médio por Venda -> Meta Ano: 500 / Meta Dia: 500

Obs: Cada indicador deve ser calculado no dia e no ano. O indicador do dia deve ser o do último dia disponível na planilha de Vendas (a data mais recente)
Obs2: Dica para o caracter do sinal verde e vermelho: pegue o caracter desse site (https://fsymbols.com/keyboard/windows/alt-codes/list/) e formate com html

### Desestruturação do Problema

No Notebook Python está presente o código utilizado em cada um dos Passos a seguir:

Passo 1 - Importar Arquivos e Bibliotecas </br>
Passo 2 - Definir Criar uma Tabela para cada Loja e Definir o dia do Indicador </br>
Passo 3 - Salvar planilha na pasta de backup </br>
Passo 4 - Calcular indicador para 1 loja </br>
Passo 5 - Enviar por e-mail para o gerente </br>
Passo 6 - Automatização para envio para todas as lojas; </br>
Passo 7 - Criar Ranking para diretoria </br>
Passo 8 - Enviar E-mail para diretoria <br></br>

#### E-mail enviado aos Gerentes das 25 lojas
![Aut_OnePage](https://user-images.githubusercontent.com/70041844/150699160-7429ef1b-62ce-4d01-91fe-8f6f8eaace47.jpg) </br>
#### E-mail enviado a Diretoria com o Ranking de Faturamento das lojas
![Aut_OnePageDir](https://user-images.githubusercontent.com/70041844/150699005-c7304f07-d168-42c7-a68b-5d6b9af95737.jpg)</br>


