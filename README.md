# Architecture Decision Records

## O que são ADRs?

- Registros documentais que capturam decisões arquiteturais importantes.
- Descrevem o contexto, as motivações e as consequências das decisões.

## Importância dos ADRs

- **Histórico de Decisões**: Mantém um registro histórico das decisões e suas justificativas.
- **Transparência**: Facilita a comunicação entre membros da equipe e stakeholders.
- **Consistência**: Ajuda a garantir que as decisões sejam consistentes ao longo do tempo.

## Estrutura de um ADR

- **Título**: Resumo conciso da decisão.
- **Contexto**: Descrição da situação atual e o problema a ser resolvido.
- **Decisão**: A escolha feita.
- **Consequências**: Impactos positivos e negativos da decisão.
- **Alternativas Consideradas**: Outras opções avaliadas e por que foram descartadas.

## Exemplo de ADR

### Contexto
Necessidade de um banco de dados para armazenar dados de usuários e transações.

### Decisão
Utilizar PostgreSQL como banco de dados principal.

### Consequências

- **Positivas**: Alta confiabilidade, suporte a ACID, boa comunidade de suporte.
- **Negativas**: Curva de aprendizado para novos desenvolvedores.

### Alternativas Consideradas

- **MySQL**: Descartado devido a limitações em algumas funcionalidades avançadas.
- **MongoDB**: Descartado por falta de suporte a transações ACID completas.

## Benefícios dos ADRs

- **Documentação Contínua**  
  Documenta o raciocínio por trás das decisões ao longo do tempo.

- **Facilidade na Onboarding**  
  Novos membros da equipe podem entender rapidamente as escolhas arquiteturais.

- **Suporte à Manutenção**  
  Facilita a manutenção e evolução do sistema ao longo do tempo.

## Ferramentas e Recursos

- **Ferramentas para ADRs**  
  - **Markdown**: Formato simples e eficiente para escrever ADRs.
  - **Git**: Ótimo para versionamento e colaboração.

- **Recursos Adicionais**  
  - **Adr-tools**: [https://github.com/npryce/adr-tools](https://github.com/npryce/adr-tools)  
    Conjunto de scripts para facilitar a criação de ADRs.
  - **Documentação do Template**: Exemplos e modelos para iniciar com ADRs.  
    Mantenha os ADRs em um repositório acessível a todos.
