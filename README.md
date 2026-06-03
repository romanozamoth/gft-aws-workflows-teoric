# Desafio DIO - AWS Step Functions

## Descrição

Este repositório foi desenvolvido como parte do laboratório da DIO com foco em AWS Step Functions.

O objetivo da prática foi compreender como criar, executar e monitorar workflows automatizados utilizando máquinas de estado (State Machines) para orquestrar processos na nuvem.

---

# Objetivos do Laboratório

* Compreender o funcionamento do AWS Step Functions.
* Criar uma State Machine.
* Definir estados e transições.
* Executar workflows.
* Monitorar execuções.
* Documentar os conhecimentos adquiridos.

---

# O que é AWS Step Functions?

AWS Step Functions é um serviço de orquestração serverless que permite coordenar múltiplos serviços AWS através de fluxos de trabalho visuais chamados State Machines.

Esses workflows permitem automatizar processos complexos sem a necessidade de gerenciar infraestrutura.

---

# Estrutura de uma State Machine

Uma State Machine é composta por:

* Start State
* Estados intermediários
* Regras de transição
* Estado final

Exemplo simplificado:

Início → Processamento → Validação → Finalização

---

# Atividades Realizadas

## 1. Acesso ao Console AWS

Foi realizado o acesso ao console e navegação até o serviço AWS Step Functions.

---

## 2. Criação da State Machine

Durante a prática foi criada uma máquina de estados contendo:

* Estado inicial
* Estados de processamento
* Estados de decisão
* Estado final

---

## 3. Configuração dos Estados

Foram explorados os principais tipos de estados:

### Task

Executa uma ação ou serviço.

### Choice

Realiza decisões condicionais.

### Wait

Pausa a execução por um período definido.

### Pass

Encaminha dados sem processamento.

### Fail

Finaliza a execução com erro.

### Succeed

Finaliza a execução com sucesso.

---

## 4. Execução do Workflow

Após a configuração, o fluxo foi executado para validação do comportamento esperado.

Foram analisados:

* Entrada de dados
* Saída de dados
* Histórico da execução
* Tempo de processamento

---

## 5. Monitoramento

Utilização do painel de monitoramento para acompanhar:

* Status das execuções
* Estados executados
* Logs
* Tratamento de falhas

---

# Conceitos Aprendidos

## Orquestração

Permite coordenar múltiplas etapas de um processo de forma automatizada.

## State Machine

Representação visual de um fluxo de execução.

## Serverless

Modelo em que não há necessidade de gerenciamento de servidores.

## Tratamento de Erros

Possibilidade de definir estratégias de Retry e Catch para falhas.

## Observabilidade

Monitoramento detalhado das execuções através do histórico fornecido pelo serviço.

---

# Benefícios do AWS Step Functions

* Automação de processos
* Integração com diversos serviços AWS
* Redução de código customizado
* Melhor rastreabilidade
* Escalabilidade automática

---

# Insights Pessoais

Durante o laboratório percebi que o AWS Step Functions simplifica significativamente a construção de fluxos de negócio complexos.

A visualização gráfica facilita a compreensão do processo e o monitoramento das execuções torna a identificação de falhas muito mais simples quando comparado a implementações totalmente baseadas em código.

O conceito de State Machine demonstrou ser uma abordagem eficiente para integrar múltiplos serviços AWS de forma organizada e escalável.

---

# Conclusão

O laboratório permitiu compreender os fundamentos da orquestração de workflows utilizando AWS Step Functions, além de reforçar conceitos importantes de automação, integração entre serviços e monitoramento de processos em ambientes cloud.
