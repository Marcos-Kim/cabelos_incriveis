#### Estudo de Caso: Salão de Cabeleireiro "Cabelos Incríveis"
## Contexto:
O salão de cabeleireiro "Cabelos Incríveis" é um estabelecimento localizado em uma 
área movimentada da cidade. O salão oferece uma variedade de serviços, incluindo 
cortes de cabelo, coloração, tratamentos capilares, manicure e pedicure. Eles têm uma 
equipe de cabeleireiros talentosos e uma base de clientes fiéis.
Desafio:
O salão de cabeleireiro "Cabelos Incríveis" está enfrentando dificuldades para gerenciar 
eficientemente seus clientes, agendamentos, estoque de produtos e informações dos 
funcionários. Eles precisam de um sistema de banco de dados para ajudar a organizar e
automatizar esses processos.
Requisitos do Sistema:
• Gerenciamento de Clientes:
o Cadastro de novos clientes com informações como nome, endereço, 
telefone, e-mail, preferências de serviços, histórico de serviços realizados, 
etc.
o Registro de serviços realizados por cada cliente, incluindo datas, tipos de 
serviço, cabeleireiro responsável, etc.
o Possibilidade de atualização e exclusão de informações de clientes.
• Agendamento de Serviços:
o Capacidade de agendar serviços para clientes, incluindo data, horário, tipo 
de serviço, cabeleireiro responsável, etc.
o Visualização rápida de disponibilidade de horários e cabeleireiros para 
agendamentos.
• Gerenciamento de Estoque:
o Controle de estoque de produtos utilizados no salão, como tinturas, 
shampoos, condicionadores, etc.
o Registro de entrada e saída de produtos, incluindo quantidades e datas.
• Informações dos Funcionários:
o Cadastro de informações dos funcionários, incluindo nome, função, 
horário de trabalho, salário, etc.
o Atribuição de serviços realizados por cada funcionário e 
acompanhamento de seu desempenho.
Modelo Lógico do Banco de Dados:
Baseado nos requisitos acima, podemos definir um modelo lógico básico para o banco 
de dados do salão de cabeleireiro "Cabelos Incríveis". Aqui está um esboço simplificado:
• Tabelas:
o Clientes
▪ Cliente_ID (Chave Primária)
▪ Nome
▪ Endereço
▪ Telefone
▪ E-mail
▪ Preferências
o Serviços
▪ Serviço_ID (Chave Primária)
▪ Tipo
▪ Descrição
▪ Preço
o Agendamentos
▪ Agendamento_ID (Chave Primária)
▪ Cliente_ID (Chave Estrangeira referenciando a tabela Clientes)
▪ Serviço_ID (Chave Estrangeira referenciando a tabela Serviços)
▪ Data
▪ Horário
▪ Cabeleireiro
o Estoque
▪ Produto_ID (Chave Primária)
▪ Nome
▪ Quantidade
▪ Data_Entrada
▪ Data_Saída
o Funcionários
▪ Funcionário_ID (Chave Primária)
▪ Nome
▪ Função
▪ Horário_Trabalho
▪ Salário

### Modelo lógico:

<img src="modelo_logico_cabelos_incriveis.png">

## 1ª Normalização

<img src="mod_log_cab_incr_1a_normalizacao.png">

## 2ª Normalização

<img src="mod_log_cab_incr_2a_normalizacao.png">

## 3ª Normalização

<img src="mod_log_cab_incr_3a_normalizacao.png">

### Modelo conceitual:

<img src="modelo_logico_cabelos_incriveis.png">
