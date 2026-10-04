# 🔧 Sistema Web de Gestão e Agendamento Inteligente para Oficinas Mecânicas

## 📌 Sobre o Projeto

O projeto consiste no desenvolvimento de um **sistema web de gestão e agendamento para oficinas mecânicas**, tendo como referência a oficina BF CAR, especializada na prestação de serviços de manutenção automotiva em veículos leves.

A proposta surgiu a partir da identificação de necessidades relacionadas à organização dos agendamentos, ao controle de entrada e saída de veículos, ao acompanhamento dos atendimentos e à comunicação entre a oficina e seus clientes.

O sistema pretende centralizar essas atividades em uma única plataforma, proporcionando maior organização dos processos internos e facilitando o acesso dos clientes às informações relacionadas aos seus veículos e serviços.

Além das funcionalidades tradicionais de gestão, o projeto prevê a utilização de mecanismos de automação e recursos inteligentes para auxiliar na triagem dos problemas apresentados pelos veículos, na comunicação com os clientes e na identificação de necessidades de manutenção preventiva.

## 🎯 Problema Identificado

A organização das atividades de uma oficina mecânica envolve diferentes etapas, desde o primeiro contato com o cliente até a conclusão do serviço e a entrega do veículo.

Nesse contexto, a falta de integração entre os processos pode dificultar o controle dos agendamentos, a identificação dos veículos que aguardam atendimento, o acompanhamento dos serviços em execução e a comunicação sobre o andamento dos reparos.

Outro aspecto importante é a necessidade de respeitar a capacidade operacional da oficina, evitando o recebimento de uma quantidade de veículos superior à que pode ser administrada diariamente.

Diante dessas necessidades, identificou-se a oportunidade de desenvolver uma solução que centralize as informações e auxilie na organização das atividades, tornando o gerenciamento dos atendimentos mais estruturado.

## 🚀 Objetivo Geral

Desenvolver um sistema web para auxiliar na gestão e no agendamento de serviços de uma oficina mecânica, centralizando informações de clientes, veículos e atendimentos, além de incorporar recursos de automação e funcionalidades inteligentes para melhorar a organização dos processos e a comunicação com os clientes.

## ⚙️ Funcionalidades Previstas

O sistema contará com diferentes funcionalidades, organizadas de acordo com as necessidades identificadas durante o levantamento de requisitos.

### 👤 1. Cadastro de Clientes e Veículos

Permitir o cadastro e a manutenção das informações dos clientes e de seus respectivos veículos, possibilitando a consulta e a atualização dos dados necessários para a realização dos atendimentos.

### 📅 2. Agendamento de Serviços

Disponibilizar uma funcionalidade para criação de agendamentos, permitindo consultar datas e horários disponíveis, realizar alterações e cancelar agendamentos conforme as regras estabelecidas pela oficina.

### 🚗 3. Controle da Capacidade Diária

Implementar um mecanismo de controle da quantidade de veículos agendados para cada dia, respeitando o limite operacional definido pela oficina, que atualmente trabalha com uma capacidade de até 10 veículos agendados por dia.

O sistema deverá considerar os agendamentos existentes e impedir novas reservas quando o limite diário for atingido, além de atualizar a disponibilidade quando um agendamento for cancelado ou alterado.

### 🔑 4. Controle de Entrada e Saída de Veículos

Permitir o registro da entrada e da saída dos veículos na oficina, mantendo informações sobre a movimentação e auxiliando no controle dos veículos que estão aguardando atendimento, em manutenção ou que já foram liberados.

### 📊 5. Acompanhamento do Status do Atendimento

Disponibilizar informações sobre o andamento dos atendimentos, permitindo que os usuários consultem a situação dos veículos de acordo com suas permissões de acesso.

### 🛠️ 6. Triagem Híbrida de Problemas

Implementar um módulo de triagem que combine informações fornecidas pelos clientes com a avaliação realizada pelos profissionais da oficina.

A proposta é permitir o registro dos problemas relatados pelo cliente e complementar essas informações com a análise técnica dos responsáveis pelo atendimento, contribuindo para uma identificação mais organizada das necessidades de manutenção do veículo.

### 💬 7. Comunicação Automatizada com Clientes

Integrar mecanismos de comunicação por meio de APIs, permitindo automatizar o envio de mensagens relacionadas a eventos importantes do atendimento, como confirmações de agendamento, alterações, cancelamentos e atualizações sobre o andamento dos serviços.

### 📚 8. Histórico de Manutenção

Manter um histórico dos atendimentos e serviços realizados nos veículos, possibilitando consultar informações sobre manutenções anteriores e utilizar esses registros como referência para futuros atendimentos.

### 🤖 9. Alertas de Manutenção Preventiva

Desenvolver uma funcionalidade para identificar possíveis necessidades de manutenção preventiva com base nas informações registradas no histórico dos veículos.

A proposta também contempla o uso dessas informações em estratégias de comunicação e marketing preditivo, permitindo identificar oportunidades de contato com clientes para alertas e lembretes de manutenção.

## 👥 Perfis de Usuário

O sistema prevê diferentes perfis de acesso, de acordo com as responsabilidades de cada usuário. A definição dos perfis e de suas respectivas permissões deverá garantir que cada usuário tenha acesso apenas às funcionalidades e informações necessárias para suas atividades.

Entre os perfis considerados estão:

* **Cliente:** poderá acessar as funcionalidades disponibilizadas para consulta de informações próprias, veículos e agendamentos.
* **Funcionário:** poderá utilizar as funcionalidades relacionadas às atividades operacionais da oficina, conforme suas permissões.
* **Administrador/Gerente:** poderá acessar funcionalidades administrativas e de gerenciamento do sistema, respeitando as permissões definidas.

As permissões específicas de cada perfil serão estabelecidas durante a definição dos requisitos do sistema.

## 💻 Tecnologias e Arquitetura

As tecnologias, ferramentas e decisões de arquitetura serão definidas e documentadas durante as etapas de planejamento e desenvolvimento do projeto.

A solução está sendo planejada como uma aplicação web, com o objetivo de permitir o acesso por diferentes dispositivos e facilitar a utilização das funcionalidades pelos usuários.

## 🔄 Metodologia de Desenvolvimento

O desenvolvimento do projeto está sendo conduzido com base em uma abordagem ágil, utilizando práticas do **Scrum e do Kanban** para organizar as atividades, acompanhar o progresso e facilitar a colaboração entre os integrantes da equipe.

O **Scrum** é utilizado para estruturar o trabalho em ciclos de desenvolvimento denominados *sprints*, permitindo definir objetivos, distribuir tarefas e acompanhar as entregas realizadas ao longo de cada etapa. A equipe também realiza reuniões periódicas para discutir o andamento das atividades, alinhar decisões e acompanhar possíveis dificuldades.

O **Kanban** é utilizado para visualizar e gerenciar o fluxo de trabalho, permitindo acompanhar o status de cada atividade desde o planejamento até sua conclusão. Para isso, é utilizada uma estrutura de quadro com colunas que representam as diferentes etapas de execução das tarefas.

Para auxiliar no gerenciamento e desenvolvimento do projeto, são utilizadas as seguintes ferramentas:

* **Trello:** gerenciamento das atividades por meio de um quadro Kanban, organização do backlog e acompanhamento das tarefas.
* **GitHub:** armazenamento do código-fonte, controle de versão e colaboração entre os integrantes da equipe.
* **Bizagi Modeler:** modelagem e documentação dos processos de negócio por meio da notação BPMN.

O desenvolvimento também contempla atividades de levantamento e documentação de requisitos funcionais e não funcionais, modelagem de processos, elaboração de diagramas, definição da estrutura do banco de dados e implementação das funcionalidades previstas.

## 📍 Situação Atual do Projeto

O projeto encontra-se em desenvolvimento acadêmico, passando pelas etapas de levantamento de informações, definição do escopo, documentação de requisitos e modelagem da solução.

As funcionalidades apresentadas neste documento representam a proposta do sistema e poderão ser detalhadas e refinadas conforme a evolução do projeto.

## 📂 Finalidade do Repositório

Este repositório tem como finalidade armazenar e organizar os arquivos, documentos e códigos-fonte relacionados ao desenvolvimento do sistema, permitindo o acompanhamento das alterações e a colaboração entre os integrantes da equipe.

## 🎓 Contexto Acadêmico

Projeto desenvolvido como parte da disciplina de Projeto Interdisciplinar (AAP) do curso de **Gestão da Tecnologia da Informação**, da Faculdade de Tecnologia (FATEC) de Barueri.
