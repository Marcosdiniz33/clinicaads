# Documento de Requisitos - Sistema de Agendamento

## 1. Objetivo
Permitir o acesso da agenda por diversos profissionais para um maior controle do agendamento, evitando choques de horário e cancelamentos.

## 2. Escopo
- Cadastro de usuários
- Disponibilidade de cada profissional
- Cadastro de pacientes
- Agendar e cancelar consultas
- Exibir mensagem de erro em caso de choque de horário ou agendamento fora do horário permitido
- Visualizar agenda diária e semanal

## 3. Escopo Fora do Projeto (Out of Scope)
- Agendamento domiciliar
- Notificação por SMS/E-mail
- Prontuário eletrônico
- Relatórios avançados
- Faturamento e convênios

## 4. Regras de Negócio
- Não pode haver conflito de horários entre consultas
- A consulta só pode ocorrer no horário disponibilizado pelo profissional
- Cancelamento deve liberar o slot imediatamente para novo agendamento
- A duração padrão de cada consulta é de 30 minutos

## 5. Premissas
- Horário comercial: das 08h às 18h
- MVP limitado a 10 profissionais
- Cadastro para até 500 pacientes

## 6. Stakeholders
- Atendentes
- Médicos
- Pacientes
- Gestor da clínica
