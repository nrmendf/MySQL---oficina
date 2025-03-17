# MySQL---oficina

Projeto de Banco de Dados para Oficina Mecânica
Este projeto tem como objetivo criar e implementar um banco de dados relacional para gerenciar as operações de uma oficina mecânica. O sistema permite o controle de clientes, veículos, ordens de serviço, serviços realizados, pagamentos e funcionários. O projeto foi desenvolvido utilizando o modelo relacional, baseado em um esquema conceitual representado por um modelo Entidade-Relacionamento (ER).

Objetivo do Projeto
O projeto tem como principal objetivo otimizar o processo de gestão das atividades de uma oficina mecânica, proporcionando uma visão mais clara e eficiente das interações entre clientes, veículos, serviços e pagamentos. Através de consultas SQL complexas, a oficina pode facilmente gerenciar ordens de serviço, consultar dados de clientes e veículos, calcular valores de serviços e acompanhar o progresso do trabalho realizado.

Esquema Lógico do Banco de Dados
O banco de dados foi modelado a partir de um modelo ER e foi transformado em um esquema lógico utilizando o modelo relacional. As principais entidades e relacionamentos do sistema são:

Entidades e Tabelas:
Clientes: Contém informações sobre os clientes da oficina.
Veículos: Armazena informações sobre os veículos de cada cliente.
Funcionários: Registra os dados dos funcionários da oficina, como mecânicos e assistentes.
Ordens de Serviço: Gerencia as ordens de serviço abertas para os veículos.
Serviços: Contém os tipos de serviços oferecidos pela oficina (ex: troca de óleo, alinhamento de direção, etc.).
Itens de Serviço: Relaciona os serviços realizados em cada ordem de serviço.
Pagamentos: Registra os pagamentos realizados pelos clientes por cada ordem de serviço.
Relacionamentos:
Clientes e Veículos: Um cliente pode ter vários veículos, mas cada veículo pertence a um único cliente.
Veículos e Ordens de Serviço: Cada veículo pode ter várias ordens de serviço.
Ordens de Serviço e Serviços: Uma ordem de serviço pode incluir múltiplos serviços.
Ordens de Serviço e Funcionários: Cada ordem de serviço é associada a um funcionário (mecânico).
Ordens de Serviço e Pagamentos: Cada pagamento é feito por uma ordem de serviço específica.


Conclusão
Este projeto visa otimizar a gestão de uma oficina mecânica por meio de um banco de dados relacional eficiente. O banco de dados foi projetado para ser expansível, permitindo a inclusão de novas funcionalidades no futuro. As consultas SQL avançadas ajudam a responder a várias perguntas importantes, como o valor total de serviços realizados, ordens de serviço abertas, e o gerenciamento de pagamentos e ordens.
