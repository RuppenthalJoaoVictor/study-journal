# Roadmap de Estudos

O que estou estudando, **por quê**, e em que ordem. Este arquivo existe para
parar de estudar coisas aleatórias e escolher com critério.

> Princípio: estudio para **resolver problemas**, não para decorar sintaxe. Cada
> item só entra aqui se eu já tiver um problema real que ele resolve.

## 🎯 Objetivo do período

Me candidatar a vagas de **Desenvolvedor Júnior** e passar nos processos
seletivos. Isso exige: código legível por terceiros, testes, e saber explicar
minhas decisões técnicas.

## 🟢 Em andamento

### Python: do básico ao profissional

| Tópico | Por quê | Status |
| :--- | :--- | :--- |
| Tipagem estática com `mypy` | É o que diferencia script de software | Em andamento |
| `pytest` + fixtures + cobertura | Teste é o que um recrutador nota primeiro | Em andamento |
| FastAPI + validação com Pydantic | Onde Python é forte em mercado | Em andamento |
| SQLAlchemy 2.0 (ORM) | É o que a maioria das vagas pede | Em andamento |
| Autenticação (bcrypt + JWT) | Praticado no `taskflow-api` | Em andamento |

### TypeScript: base sólida

| Tópico | Por quê | Status |
| :--- | :--- | :--- |
| Sistema de tipos estrito | `strict: true` pega bugs antes de rodar | Concluído |
| `noUncheckedIndexedAccess` | Evita o clássico "element is undefined" | Concluído |
| Node.js e o modelo de módulos (ESM) | Entender por que `.js` no import | Concluído |
| Testes com Vitest | Praticado no `devlog-cli` | Concluído |

## 🟡 Próximos

### Arquitetura e boas práticas

- **Repository e Service Layer** — separar acesso a dados da lógica de negócio
- **Princípios SOLID na prática** — não só a definição, mas quando quebrar
- **Testes de integração vs unitário** — saber qual usar e por quê
- **Docker** — entregar a aplicação rodando com um comando

### Frontend (o meu maior déficit)

- **React** — o que mais aparece em vaga júnior
- **Fetch e consumo de API** — conectar com o `taskflow-api`
- **CSS moderno** — o suficiente para não passar vergonha visual

## 🔴 Em espera

| Item | Motivo da espera |
| :--- | :--- |
| Machine Learning | À frente da minha prioridade atual |
| Go / Rust | Quero consolidar Python e TS antes |
| Contribuição open source | Quero estar contribuidor antes de usar como vitrine |

## 📏 Como meço progresso

Não por horas estudadas, mas por evidências:

- [x] Uma API REST completa com autenticação e testes
- [x] Um CLI funcional com testes e tipagem estrita
- [ ] Uma aplicação React consumindo uma API real
- [ ] 30 entradas neste diário
- [ ] Uma contribuição open source aceita

## 📚 Fontes

| Tema | Fonte |
| :--- | :--- |
| Python | Documentação oficial + *Fluent Python* |
| FastAPI | [Documentação oficial](https://fastapi.tiangolo.com/pt/) |
| SQLAlchemy | [Documentação 2.0](https://docs.sqlalchemy.org/en/20/) |
| TypeScript | [Handbook oficial](https://www.typescriptlang.org/docs/handbook/intro.html) |
| Práticas de código | [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html) |