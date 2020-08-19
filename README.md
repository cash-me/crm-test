# Teste para vaga de Desenvolvedor CRM
Teste da CashMe para a vaga de Desenvolvedor CRM

## Introdução

O objetivo do teste é avaliar a experiência com o CRM Dynamics e a capacidade do candidato de aprender novas tecnologias, escrever código limpo e testado automaticamente. 
Sabemos que o prazo é um desafio e que atingir a perfeição será impossível, então a priorização dos esforços é importante e também será avaliada.

## Descrição da tarefa

A tarefa consiste em criar um microserviço simples (CRUD) que armazene quais CPFs estão em uma lista negra e por qual motivo eles foram cadastrados 
(ex.: associação a organizações terrorristas). Este microsserviço, 
ao receber um novo registro (chamada via API), deve fazer uma chamada (também via API) para cancelar todas as oportunidades e cotações do mesmo CPF no CRM Dynamics

Etapas sugeridas:

1. Criar uma conta pessoal no Github
2. Criar uma conta de testes para utilizar o CRM Dynamics
3. Criar o microserviço (sugestão é utilizar .netcore)
4. Efetuar conexão com CRM para cancelar oportunidades e cotações vinculadas a contato ou conta
5. Fazer um hook que aciona a API do CRM quando há um cadastro de novo CPF  
6. Subir o código final para o Github e adicionar em uma pasta os prints das configurações que foram realizadas no CRM

## Observações

1. A avalição será feita 100% no que estiver versionado no Github. Não serão aceitos códigos ou planos de teste enviados por outro canal (ex.: e-mail)
2. O prazo para realizar o teste é de uma semana já considerando que o candidato trabalhe no horário comercial
3. Qualquer dúvida ou dificuldade entre em contato com o recrutador ou com o responsável técnico pelo teste
