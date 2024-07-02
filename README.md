# Sistema de Saúde - Agendamento de Consultas e Vacinação

Este projeto é um sistema de saúde desenvolvido para facilitar o agendamento de consultas médicas e alertar pacientes idosos sobre a necessidade de vacinação. A aplicação é composta por três partes principais: uma API em Laravel para o backend, um frontend web em React (Next.js) e um aplicativo móvel em Flutter.

## Tecnologias Utilizadas

- **Backend (API)**: Laravel
- **Frontend Web**: React (Next.js)
- **Aplicativo Móvel**: Flutter (Android)

## Funcionalidades

### 1. Agendamento de Consultas
- Pacientes podem agendar consultas com médicos disponíveis.
- Médicos podem visualizar e confirmar consultas agendadas.

### 2. Gerenciamento de Pacientes e Médicos
- CRUD completo para pacientes e médicos.
- Informações detalhadas de pacientes (histórico médico, informações pessoais).
- Informações de médicos (especialidade, horários de atendimento).

### 3. Alerta de Vacinação para Idosos
- Sistema de alerta que notifica pacientes idosos sobre a necessidade de vacinação.
- Integração com calendário para lembretes automáticos.

### 4. Frontend Web (React - Next.js)
- Interface responsiva e amigável para agendamento de consultas e gerenciamento de pacientes/médicos.
- Dashboard para visualização rápida de consultas agendadas e alertas de vacinação.

### 5. Aplicativo Móvel (Flutter - Android)
- Aplicativo para pacientes receberem alertas de vacinação e agendarem consultas diretamente pelo celular.
- Integração com notificações push para lembretes de consultas e vacinas.

## Instalação e Configuração

### Pré-requisitos

- Node.js (para frontend React)
- Composer (para Laravel)
- Flutter SDK (para aplicativo Android)

### Backend (API - Laravel)

1. Clone o repositório do backend:

   ```bash
   git clone https://github.com/seu-usuario/api-saude-laravel.git
   cd api-saude-laravel
