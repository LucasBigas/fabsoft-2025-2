# Fábrica de Software 2025/2
Lucas Bigas Padilha

## Propostas de projeto
- Nome do sistema: Sistema Clinico 
  - Funcionalidade 1 Cadastrar dados do Paciente
  - Funcionalidade 2 Cadastrar Medicos 
  - Funcionalidade 3 Cadastrar Especialidades
  - Funcionalidade 4 Cadastrar Exames
  - Funcionalidade 5 Cadastrar clinicas 
  - Funcionalidade 6 Cadastrar Tipos de Pagamentos
  - Funcionalidade 7 Agendar consulta
  - Funcionalidade 8 Prontuário Eletrônico
  - Funcionalidade 9 Agendar exames 
  - Funcionalidade 10 Controle de Convênios/Planos de Saúde
  - Funcionalidade 11 Entrega de Exames
  - Funcionalidade 12 Cadastrar Agenda
  - *Funcionalidade 13 Sistema de Permissoes e login Medicos e Recepcionista

## Aula 05/08

- JRE - Java Runtime Enviroment
  - Ambiente mínimo para executar um programa Java
  - JVM - Java Virtual Machine (java.exe ou javaw.exe)

- JDK - Java Development Kit
  - [Adoptium JDK](https://adoptium.net/pt-BR)
  - Ambiente de DESENVOLVIMENTO (javac.exe) compilador

- COMPILAÇÃO
  1) Escreve um programa em java (arquivo.java)
  2) Compilação arquivo.java -> javac.exe -> bytecode arquivo.class
- EXECUÇÃO
  3) Passar .class -> java.exe (JVM) -> ling máquina

- VSCode
  - [VSCode](https://code.visualstudio.com/)
  - [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
    
## Histórias de Usuário
- Como um funcionário, eu gostaria de cadastrar um paciente, para que ele possa ser atendido na clínica.
- Como um funcionário, eu gostaria de editar os dados de um paciente, para corrigir informações incorretas.
- Como um funcionário, eu gostaria de excluir um paciente, caso seja necessário remover registros duplicados ou incorretos.
- Como um funcionário, eu gostaria de visualizar a lista de pacientes cadastrados, para facilitar a consulta.
  
- Como um funcionário, eu gostaria de cadastrar um médico, para que ele possa atender pacientes na clínica.
- Como um funcionário, eu gostaria de editar os dados de um médico, para atualizar informações como especialidade ou contato.
- Como um funcionário, eu gostaria de excluir um médico, caso ele não trabalhe mais na clínica.
- Como um funcionário, eu gostaria de consultar a lista de médicos, para verificar quem está disponível.

- Como um funcionário, eu gostaria de cadastrar uma especialidade médica, para associar aos médicos.  
- Como um funcionário, eu gostaria de editar uma especialidade, para corrigir informações ou nomes.  
- Como um funcionário, eu gostaria de excluir uma especialidade, caso não seja mais utilizada.

- Como um funcionário, eu gostaria de cadastrar um exame, para que ele possa ser agendado e realizado.  
- Como um funcionário, eu gostaria de editar um exame, para atualizar informações de procedimento ou preço.  
- Como um funcionário, eu gostaria de excluir um exame, caso não seja mais oferecido.  

- Como um funcionário, eu gostaria de cadastrar uma clínica, para poder associar atendimentos e exames.  
- Como um funcionário, eu gostaria de editar os dados de uma clínica, para manter informações atualizadas.  
- Como um funcionário, eu gostaria de excluir uma clínica, caso ela não esteja mais disponível.  

- Como um funcionário, eu gostaria de cadastrar tipos de pagamento (dinheiro, cartão, convênio), para registrar transações.  
- Como um funcionário, eu gostaria de editar tipos de pagamento, para corrigir informações.  
- Como um funcionário, eu gostaria de excluir tipos de pagamento, caso não sejam mais aceitos.

- Como um funcionário, eu gostaria de agendar uma consulta, para organizar o atendimento do paciente.  
- Como um funcionário, eu gostaria de editar uma consulta, caso haja alteração de horário ou médico.  
- Como um funcionário, eu gostaria de cancelar uma consulta, caso o paciente não possa comparecer.  
- Como um funcionário, eu gostaria de visualizar todas as consultas agendadas, para gerenciar a agenda.  

- Como um médico, eu gostaria de registrar informações no prontuário do paciente, para manter histórico clínico atualizado.  
- Como um médico, eu gostaria de consultar o prontuário de um paciente, para verificar seu histórico e diagnósticos.  
- Como um médico, eu gostaria de editar o prontuário, para corrigir informações ou adicionar novos dados.  

- Como um funcionário, eu gostaria de agendar um exame, para organizar a realização dos procedimentos.  
- Como um funcionário, eu gostaria de editar um exame agendado, para ajustar data ou horário.  
- Como um funcionário, eu gostaria de cancelar um exame, caso o paciente não possa comparecer.  
- Como um funcionário, eu gostaria de visualizar todos os exames agendados, para gerenciar a agenda.  

- Como um funcionário, eu gostaria de cadastrar convênios, para registrar planos aceitos na clínica.  
- Como um funcionário, eu gostaria de editar convênios, para atualizar informações ou contatos.  
- Como um funcionário, eu gostaria de excluir convênios, caso não sejam mais aceitos.  
- Como um funcionário, eu gostaria de consultar convênios, para verificar cobertura e autorização de exames.  

- Como um funcionário, eu gostaria de registrar a entrega de exames ao paciente, para confirmar que ele recebeu o resultado.  
- Como um funcionário, eu gostaria de consultar os exames entregues, para controlar o histórico de entrega.

- Como um funcionário, eu gostaria de cadastrar a agenda de médicos, para organizar horários de atendimento.  
- Como um funcionário, eu gostaria de editar a agenda de médicos, para ajustar horários ou folgas.  
- Como um funcionário, eu gostaria de excluir horários da agenda, caso não estejam disponíveis.  
- Como um funcionário, eu gostaria de visualizar a agenda completa, para gerenciar consultas e exames.  
  
