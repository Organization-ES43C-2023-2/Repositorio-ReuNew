# 1. Requisitos Não Funcionais

<p align="justify">A <i>Tabela 2</i> a seguir contém os <b>Requisitos Não Funcionais (RNF)</b> elicitados utizando a técnica de Brainstorm.</p>

| ID    |                                 Requisito NF                                                                                                | Categoria/Tipo                       | Prioridade | Requisitos Relacionados |
| :--:  | :-----------------------------------------------------------------------:                                                                   |:-------------:                       | :--------: | :-----------------:     |
| RNF01 |  O usuário administrador de grupo deve ser capaz de gerenciar os usuários da tabela, como remover e modificar suas permissões (adicionar usuário, remover usuário, modificar tabela)               | Organização/Administração            |Média       |        -                |
| RNF02 |  O aplicativo não deve passar mais de 170mbs.                                                                                               |  Organizacionais/Implementação       |Alta        |    -                    |
| RNF03 |  O aplicativo é de formato desktop, sendo software e web tendo um design responsivo.                                                        |  Organizacionais/Implementação       |Alta        |     -                   |
| RNF04 |  As informações de dados estarão guardados em SQL (Postgre ou MYSQL) para poder realizar consultas futuramente e auxiliar a manipulação de dados.                                                                       |  Manutenibilidade                    |Alta        |    RNF04                   |
| RNF05 |  O sistema deve estar integrado com o e-mail do usuário para que ocorra a comunicação automática entre o software, tarefas e notificações.  |  Interoperabilidade                  |Baixa       |     RF01                |
| RNF06 |  O sistema deve ter um tempo de resposta rápida de no máximo 3 segundos para a manipulação de dados e tabelas                                                       |  Desempenho/Espaço/Eficiência        |Alta        |     RNF01               |
| RNF07 |  O sistema deve proteger os dados dos usuários por meio de criptografia, garantindo a confidencialidade e a integridade das informações, sendo que a pessoa que acessará os dados sensíveis será o administrador do projeto                           |  Segurança                           |Alta        | RF01,RF02,RF03,RF04,RF09|
| RNF08 |  O sistema deve estar disponível a todo tempo, exceto quando for necessário desativar o sistema para a manutenção.                          |  Interoperabilidade                  |Média       |     -                   |
| RNF09 |  A interface deve ser interativa, instintiva e simples de se utilizar.                                                                      |  Usabilidade                         |Alta        |     -                   |
| RNF10 |  O sistema deve estar seguindo as normas de LGPD.                                                                                           |  Segurança/Ética/Privacidade         |Média       |     RF01,RF02,RF03,RF04 |
| RNF11 |  O sistema deve ter suportes para diferentes tipos de linguas e formatos de data, hora e local.                                             |  Interoperabilidade                  |Média       |     RNF02               |
| RNF12 |  O aplicativo precisa de revisões e correção de bugs após a entrega em sprints caso seja necessário.                                        |  Padrões/Entrega/Confiabilidade      |Média       |     -                   |

<div style="text-align: center">
<p>Tabela 2: Requisitos Não Funcionais</p>
</div>

# 2. Referências

https://moodle.utfpr.edu.br/pluginfile.php/3039489/mod_resource/content/3/08_RS_Elicita%C3%A7%C3%A3o_e_Analise_de_Requisitos_PARTE_01.pdf


<a href="../README.md">VOLTAR INÍCIO</a>
