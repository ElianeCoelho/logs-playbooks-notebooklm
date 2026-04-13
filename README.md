# Caderno Temático com NotebookLM: Logs e Playbooks na Resposta a Incidentes

## Contexto e Objetivos

Este projeto foi desenvolvido como parte de um desafio prático com foco no uso da Inteligência Artificial como ferramenta de aprendizagem ativa. O tema escolhido foi a relação entre logs e playbooks na resposta a incidentes de segurança.

O objetivo deste caderno temático é compreender como os registros de eventos (logs) podem apoiar a identificação de incidentes e a organização de ações de resposta por meio de playbooks.

Ao final, a proposta é consolidar um miniguia de estudo com resumos, conceitos principais e prompts reutilizáveis para futuras revisões.

## Curadoria de Fontes

As fontes selecionadas para estudo no NotebookLM foram:

1. Guia sobre resposta a incidentes de segurança  
2. Material sobre análise de logs em segurança da informação  
3. Conteúdo sobre playbooks de resposta a incidentes  
4. Documento complementar sobre boas práticas de tratamento de eventos de segurança

## Engenharia de Prompts e Cicatrizes

### Prompt 1
"Explique o que são logs e qual sua importância na resposta a incidentes."

**Resultado:** trouxe uma explicação geral e útil para iniciar o estudo.  
**Dificuldade:** a resposta ficou ampla e pouco conectada ao uso prático.

### Prompt 2
"Como os logs podem ser usados para apoiar a construção de playbooks de resposta a incidentes?"

**Resultado:** a resposta já mostrou relação entre detecção, análise e ação.  
**Dificuldade:** ainda apresentou exemplos genéricos.

### Prompt 3
"Crie um resumo prático mostrando como eventos registrados em logs podem orientar ações em um playbook de resposta a incidentes."

**Resultado:** a resposta ficou mais objetiva e voltada à aplicação prática.  
**Aprendizado:** prompts mais específicos geram respostas mais úteis e reaproveitáveis.

## Miniguia de Estudo

### 1. Resumo Estruturado

Logs são registros de eventos gerados por sistemas, aplicações, dispositivos e serviços. Na segurança da informação, eles ajudam a identificar comportamentos suspeitos, rastrear ações executadas e apoiar investigações.

Playbooks são roteiros organizados que orientam as ações a serem tomadas diante de um incidente. Eles ajudam equipes a responder de forma mais rápida, padronizada e eficiente.

A relação entre logs e playbooks é importante porque os logs fornecem evidências e sinais do que está acontecendo, enquanto os playbooks organizam a resposta adequada a cada situação.

### Exemplo Prático

Um sistema pode registrar diversas tentativas de login falhas em um curto intervalo de tempo em seus logs.

Esse padrão pode indicar uma possível tentativa de ataque de força bruta.

A partir dessa evidência, um playbook de resposta a incidentes pode orientar ações como:
- analisar a origem dos acessos
- bloquear temporariamente o endereço IP
- verificar se houve comprometimento de contas
- registrar o incidente para análise posterior

Esse exemplo demonstra como os logs fornecem sinais do problema e os playbooks orientam a tomada de decisão.


### 2. Glossário

- **Log:** registro de evento gerado por um sistema.
- **Incidente de segurança:** evento que compromete ou ameaça a confidencialidade, integridade ou disponibilidade da informação.
- **Playbook:** conjunto estruturado de ações para responder a um incidente.
- **Evento:** ocorrência observável em um sistema ou rede.
- **Análise de logs:** processo de examinar registros para identificar falhas, comportamentos anormais ou incidentes.

### 3. Prompts Reutilizáveis

- "Explique este log em linguagem simples e indique se há sinais de incidente."
- "Quais indícios de incidente podem ser identificados neste registro?"
- "Transforme este cenário em um playbook básico de resposta."
- "Quais ações iniciais devem ser adotadas diante deste tipo de evento?"
- "Resuma a relação entre logs e resposta a incidentes."
