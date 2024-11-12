Padrões - Equipe de DBA

A equipe de DBA do projeto será responsável pela criação de tabelas e views do sistema.




Desenvolvimento Padrões sobre Banco de Dados
integrantes do grupo : Miguel , Kamilly e Yasmim
Objetivo
O sistema tem o objetivo de organizar e gerenciar os veículos,
motoristas, multas, manutenções e empréstimos de forma prática e
eficiente. Ele deve facilitar a consulta de informações e a criação
de relatórios sobre o uso da frota.
Boas Práticas
● Organização dos Dados (Normalização): Estrutura as tabelas
para que cada informação fique em um lugar específico e sem
repetição desnecessária.
● Relações entre Tabelas: Usam
chaves para ligar as informações de motoristas, veículos, multas, etc., garantindo que tudo esteja conectado.
● Índices para Pesquisa Rápida: Cria índices (marcadores) em campos frequentemente consultados, como o ID dos motoristas e veículos, para acelerar buscas no banco de dados.
● Segurança e Controle de Acesso: Defina quem pode ver ou alterar os dados, dando permissão para cada nível de usuário (ex.: gerentes, administradores).
modelo conceitual


