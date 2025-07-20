# Cypress Avançado - Repositório de Curso

Este repositório contém material prático para aprendizado de testes automatizados com Cypress. Aqui você encontrará exercícios, exemplos e arquivos de apoio organizados didaticamente.

> ⚠️ **Aviso**: Este repositório serve exclusivamente para fins educacionais e não deve ser considerado um projeto de produção.

## Estrutura do Repositório

```
├── cypress/
│   ├── e2e/          # Testes organizados por aula
│   ├── fixtures/     # Arquivos de dados usados nos testes
│   └── support/      # Comandos customizados e configurações globais
├── cypress.config.js # Arquivo de configuração do Cypress
├── package.json      # Dependências do projeto
└── README.md         # Documentação do projeto
```

## Pré-requisitos

- Node.js (versão 14 ou superior)
- npm ou yarn

## Instalação

1. Clone o repositório:
```bash
git clone <url-do-repositorio>
cd cypress-avancado
```

2. Instale as dependências:
```bash
npm install
```

## Execução dos Testes

### Interface Gráfica
Para abrir o Cypress Test Runner:
```bash
npx cypress open
```

### Modo Headless
Para executar todos os testes no terminal:
```bash
npx cypress run
```

### Executar testes específicos
```bash
npx cypress run --spec "cypress/e2e/aula-01/*.cy.js"
```

## Recursos Utilizados

- **Simulação de APIs**: Testes incluem interceptações e mocks já configurados
- **Comandos customizados**: Implementações reutilizáveis para operações comuns
- **Fixtures**: Dados de teste organizados em arquivos JSON
- **Page Objects**: Padrão implementado para melhor manutenibilidade

## Metodologia

O código foi desenvolvido com foco didático, priorizando:

- ✅ Simplicidade e clareza
- ✅ Comentários explicativos
- ✅ Exemplos práticos
- ✅ Boas práticas de automação

## Suporte

Para dúvidas sobre o conteúdo, consulte a documentação oficial do [Cypress](https://docs.cypress.io/).

## Licença

Este material é destinado exclusivamente para fins educacionais.

---

**Desenvolvido para aprendizado em Cypress** 🧪
