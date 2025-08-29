# 🥊 Checking Class - Siam Muay Thai  

O **Checking Class da Siam Muay Thai** nasceu a partir de uma necessidade real: os alunos precisavam avisar pelo WhatsApp sobre sua presença nas aulas e, com o aumento do número de praticantes, a organização manual desses check-ins se tornou algo complexo e pouco eficiente.  

Diante desse cenário, surgiu a oportunidade de **automatizar o processo**, criando uma aplicação em que os alunos possam registrar sua presença de forma simples, através de um login, enquanto o professor acompanha em tempo real a quantidade de alunos e o status de cada aula.  
<br>
## 🎯 Objetivo  
Centralizar o **registro de presença** em uma plataforma web:  
- **Alunos** realizam o check-in de forma rápida e prática.  
- **Professores** têm uma visão clara e em tempo real do status da aula, facilitando o acompanhamento de presenças e a organização da turma.  
<br>


## Requisitos do Sistema

## Requisitos Funcionais (RF)
- O aluno deve poder criar uma conta e fazer login.
- O aluno deve poder realizar check-in em uma aula.
- O aluno deve poder cadastrar/atualizar sua foto de perfil.
- O sistema deve exibir ao aluno o histórico e progresso em aulas.
- O administrador deve poder criar, editar e excluir turmas semanais.
- O administrador deve visualizar em tempo real os alunos presentes em cada aula.
- O administrador deve poder gerar relatórios de frequência.

# Requisitos Não Funcionais (RNF)

- A aplicação deve ser responsiva (desktop, tablet, mobile).
- A aplicação deve suportar autenticação segura (JWT ou OAuth).
- O sistema deve registrar logs de acessos e operações críticas.
- Banco de dados relacional com consistência transacional (PostgreSQL).
 -O sistema deve ter disponibilidade mínima de 99%.
 
## 👥 Público-Alvo  
- **Professor (Administrador)**  
- **Alunos**  

<br>

## ⚙️ Requisitos Técnicos  

### 🖥️ Tecnologias  
- **Frontend**: Plataforma web responsiva  
- **Backend**: Java + Spring Boot  
- **Banco de Dados**: PostgreSQL

<br>


## 🚀 Funcionalidades  

### 👨‍💼 Administrador  
- Gerenciar turmas semanais (**CRUD completo**)  
- Monitorar a frequência dos alunos em cada aula  

### 👤 Aluno  
- Realizar check-in nas aulas  
- Cadastrar e atualizar foto de perfil  
- Acompanhar seu progresso na academia  

