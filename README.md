# DIO_data_analytics
Repositório contendo todos os desafios concluídos do bootcamp de Python Data Analytics da DIO. <br>
Para acessar os desafios, mude a **branch atual** para alguma das opções disponíveis.

## Extraindo os Dados do Azure ☁
Para realizar esse desafio, foi criado uma instância de banco de dados MySQL na Azure e inserido diversos dados de uma modelagem simples. <br>
Após essa instanciação, no PowerBI se inseriu o endereço de conexão para o banco de dados e foi realizada a extração dos dados na nuvem.

## Tratamento dos Dados ✨
Agora, com os dados já disponíveis localmente é iniciado o processo de tratamento, que estão descritos nas etapas seguintes:
1. Remoção de colunas inválidas, com informações não pertinentes para minha análise.
2. Correção de colunas, removendo linhas nulas e definindo corretamente tipos de dados.
3. Divisão de colunas complexas em campos menores, como um endereço dividido em pedaços individuais.
4. Criação de novas consultas com a mesclagem entre tabelas, permitindo a visualização de dados relacionados.
5. Criação de novas consulta com a atribuição de tabelas, adicionando novas informações.

![Transformação_dados](https://github.com/Gabryel-Barboza/DIO_data_analytics/assets/73187678/5281e222-2d22-4671-a5cf-4cc81ba501f3)
<hr>

**Qual a diferença entre mesclar e atribuir consultas no PowerBI?** <br>
* A mesclagem de tabelas é feita para retornar uma consulta de valores correspondentes entre tabelas, ou seja, retornar uma única consulta com as informações que são de um mesmo indivíduo, por exemplo. Nesse caso, como se fosse um JOIN do SQL.
* Já a atribuição de tabelas apenas adiciona uma consulta inteira a outra consulta, concatenando as informações, independente de serem correspondentes a algum indivíduo ou não.
<br>

## Criando um relatório simples 📊
Após o tratamento dos dados, foi criado um relatório para demonstrar a relação entre eles. <br>
Por se tratar de uma base simples, nada muito complexo foi criado.

![Relatório_transformação_dados](https://github.com/Gabryel-Barboza/DIO_data_analytics/assets/73187678/be2a0f81-3cfc-44de-835d-2674a550eac6)

