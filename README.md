# Case Study: Produto Financeiro para Jovens em Ascensão

> Um estudo de caso de produto digital financeiro, da pesquisa ao código.

## Sobre o projeto

Este case documenta a criação do Dim, um produto financeiro voltado para jovens de periferia em ascensão financeira. Pessoas que já conquistaram renda, mas ainda escorregam em decisões financeiras por falta de visibilidade e hábito.

O projeto é um exercício prático de **Design Engineer**: pesquisa de usuário, definição de problema, design de produto, design system e desenvolvimento. Também é um estudo de **SDD (Spec-Driven Development)**, aprendido na prática durante a construção do Dim.

## O problema

> *"Jovens de periferia em ascensão financeira precisam de visibilidade real dos seus gastos no momento certo. Porque sem isso agem no impulso, tomando decisões que comprometem uma jornada que já custou muito para chegar até aqui."*

## Como usamos SDD

SDD significa desenvolver a partir de especificações. Antes de desenhar ou codar uma experiência, escrevemos uma **spec**: um acordo sobre o problema, o comportamento esperado e como verificaremos se ele funciona. Uma spec não é uma descrição fechada da interface; ela pode mudar quando aprendermos algo novo.

Nosso ciclo para cada recorte do produto é:

1. **Entender:** consultar pesquisa e separar evidências de hipóteses.
2. **Especificar:** registrar objetivo, fluxo, regras, estados e critérios de aceite em [`docs/specs/`](docs/specs/README.md). Critérios de aceite são condições observáveis para considerar o recorte funcionando.
3. **Desenhar:** explorar a experiência no Paper e ligar as telas à spec.
4. **Implementar:** desenvolver com Codex, usando a spec e o design como referência.
5. **Validar e aprender:** comparar o resultado com os critérios, registrar achados em [`docs/validation/`](docs/validation/README.md) e atualizar specs ou decisões quando necessário.

Vamos começar com um recorte pequeno: o check-in do almoço. A primeira spec será escrita junto com a exploração desse fluxo.

## Stack

| Ferramenta | Uso |
|---|---|
| Paper | Design System e Interface |
| Codex | Desenvolvimento |
| Magnific e Codex | Assets visuais |
| GitHub | Documentação da jornada |

## Estrutura do repositório

```text
README.md                 → Visão do projeto e método SDD
docs/
  project-brief.md       → Fundação do produto
  research.md            → Pesquisa inicial
  decisions.md           → Decisões de produto
  specs/README.md        → Como escrever as especificações
  validation/README.md   → Como registrar verificações e aprendizados
design/README.md          → Referências de design no Paper
dev/README.md             → Orientações para a futura aplicação
```

As specs, telas, assets e o código serão adicionados conforme cada experiência avançar.

## Jornada

- [x] Pesquisa inicial de usuário
- [x] Definição inicial do problema
- [x] Estrutura do repo e método SDD
- [ ] Primeira spec: check-in do almoço
- [ ] Design e protótipo do primeiro fluxo
- [ ] Implementação do primeiro fluxo
- [ ] Validação e retrospectiva

---

*Projeto em andamento. Acompanhe a evolução pelos commits.*
