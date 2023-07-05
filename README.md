# Ativ1SQL
create database de
ID	Nome	Cargo	Salário	Departamento
1	João	Analista	2500	RH
2	Maria	Gerente	3500	Finanças
3	Pedro	Desenvolvedor	1800	TI
4	Ana	Assistente	1900	Vendas
5	Luiza	Estagiário	1200	RH
Atributos relevantes dos colaboradores:

ID: Identificação única de cada colaborador.
Nome: Nome do colaborador.
Cargo: Cargo ocupado pelo colaborador na empresa.
Salário: Salário mensal do colaborador.
Departamento: Departamento em que o colaborador trabalha.
Agora, vamos executar as consultas solicitadas:

SELECT que retorna todos os colaboradores com salário maior do que 2000:
sql
 code
SELECT * FROM Colaboradores WHERE Salário > 2000;


ID	Nome	Cargo	Salário	Departamento
1	João	Analista	2500	RH
2	Maria	Gerente	3500	Finanças
SELECT que retorna todos os colaboradores com salário menor do que 2000:
sql
Copy code
SELECT * FROM Colaboradores WHERE Salário < 2000;


ID	Nome	Cargo	Salário	Departamento
3	Pedro	Desenvolvedor	1800	TI
4	Ana	Assistente	1900	Vendas
5	Luiza	Estagiário	1200	RH
Para atualizar um registro na tabela, você pode usar a seguinte query de atualização. Vamos supor que desejamos atualizar o salário do colaborador de ID 3 para 2000:

sql
Copy code
UPDATE Colaboradores SET Salário = 2000 WHERE ID = 3;
