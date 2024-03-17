### Sistema de gestão de tarefas
Sistema de gestão de tarefas desenvolvido em Laravel 11 

### Requisitos não funcionais

1. O sistema deve permitir que o aluno acesse o aplicativo.
2. O sistema deve permitir que o aluno navegue até a seção de agendamento.
3. O sistema deve permitir que o aluno selecione o tipo de agendamento que deseja fazer (aula, atividade ou prova).
4. O sistema deve permitir que o aluno insira as informações necessárias para o agendamento.
5. O sistema deve permitir que o aluno confirme o agendamento.
6. O sistema deve confirmar que o agendamento foi bem-sucedido.
7. O sistema deve permitir que o aluno selecione a data e o horário da aula, atividade ou prova.
8. O sistema deve mostrar uma mensagem de erro caso o agendamento falhe.
9. O sistema deve permitir que o aluno tente o agendamento novamente ou retorne à tela inicial do aplicativo caso o agendamento falhe.
10. O sistema deve permitir que o aluno cancele o agendamento.
11. O sistema deve confirmar que o agendamento foi cancelado.
12. O sistema deve permitir que o aluno veja os agendamentos que fez.

# Requisitos Funcionais

1. O sistema deve ser fácil de usar e intuitivo, para que o aluno possa navegar facilmente até a seção de agendamento.
2. O sistema deve ser rápido e responsivo, para que o aluno possa fazer agendamentos sem atrasos ou problemas.
3. O sistema deve ser seguro, para que as informações do aluno sejam protegidas.
4. O sistema deve ser confiável, para que o aluno possa confiar que seus agendamentos serão feitos corretamente e que receberá as confirmações de agendamento apropriadas.
5. O sistema deve ser compatível com diferentes dispositivos e sistemas operacionais, para que todos os alunos possam usá-lo.
6. O sistema deve ser escalável, para que possa lidar com um grande número de agendamentos sem problemas.
7. O sistema deve ser flexível, para que possa ser facilmente atualizado e expandido conforme necessário.
8. O sistema deve ter um banco de dados para armazenar as informações dos alunos e seus agendamentos.
9. O banco de dados deve ser seguro e confiável e online, para que as informações dos alunos sejam protegidas e os agendamentos sejam feitos corretamente e confirmados apropriadamente.
10. O sistema deve ser criado com tecnologias modernas e atualizadas, sendo elas, HTML, CSS, JavaScript, Laravel, MySQL.
11. O sistema deve ser testado e validado para garantir que funcione corretamente e que os alunos possam fazer agendamentos sem problemas.


# Tabela de permissões
|  | Owner | Admin | User | Guest |
|---|---|---|---|---|
| Create Users | ✅ | ⚠️ | ❌ | ❌ |
| Read Users | ✅ | ✅ | ❌ | ❌ |
| Update Users | ✅ | ✅ | ❌ | ❌ |
| Delete Users | ✅ | ⚠️ | ❌ | ❌ |
| Create Tasks | ✅ | ✅ | ✅ | ❌ |
| Read Tasks | ✅ | ✅ | ✅ | ❌ |
| Update Tasks | ✅ | ✅ | ✅ | ❌ |
| Delete Tasks | ✅ | ✅ | ✅ | ❌ |
