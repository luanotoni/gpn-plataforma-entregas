# Plataforma de Entregas: GPN

Trabalho em grupo da disciplina **Gerência de Processos de Negócio**, do curso de Bacharelado em Sistemas de Informação do Ifes.
O tema escolhido é o **7: Plataforma de entregas (pedidos, restaurantes, entregadores e clientes)**.
A entrega é em **30/11/2026**.

## Integrantes

- Luan Oliveira
- Gabriele Modesto
- Danilo Pimenta
- Guilherme Costa

## Artefatos

| Artefato | Onde está |
|---|---|
| Relatório (em edição) | [Google Docs](https://docs.google.com/document/d/1aXC5tmnIrDs0h0d7FG10hV_hwDVPUg8ga8NAoBA5cxM/edit) |
| Relatório final | `relatorio/relatorio.pdf` |
| Modelos BPMN editáveis (BPMN 2.0 XML) | `processos/bpmn/` |
| Exportações dos diagramas (PNG/SVG/PDF) | `processos/imagens/` |
| Slides da apresentação (PDF e editável) | `apresentacao/` |
| Protótipos de interface | [Figma](https://press-dash-03238535.figma.site/) e `prototipos/` |

## Processos

| ID | Processo | Responsável |
|---|---|---|
| P1 | Credenciamento de restaurante | Gabriele Modesto |
| P2 | Cadastro e aprovação de entregador | Guilherme Costa |
| P3 | Gestão de cardápio e disponibilidade | Gabriele Modesto |
| P4 | Realização do pedido e pagamento | Luan Oliveira |
| P5 | Aceite e preparo do pedido | Danilo Pimenta |
| P6 | Despacho e execução da entrega | Guilherme Costa |
| P7 | Cancelamento, ocorrência e reembolso | Danilo Pimenta |
| P8 | Repasse financeiro | Luan Oliveira |
| C1 | Colaboração (Cliente, Plataforma, Restaurante, Entregador, Gateway, Banco) | Luan Oliveira |

## Partes comuns

| Integrante | Parte comum |
|---|---|
| Luan Oliveira | Colaboração BPMN, matriz de rastreabilidade e repositório |
| Gabriele Modesto | Modelo de negócio (Canvas, escopo e regras) |
| Danilo Pimenta | Histórias de usuário e requisitos |
| Guilherme Costa | Figma, mapa de navegação e slides |

Cada integrante faz a descrição, o BPMN, a validação (traces) e as telas dos próprios processos.

## Como contribuir

- Os diagramas são feitos no [bpmn.io](https://demo.bpmn.io) ou no Camunda Modeler. Cada processo é salvo como `processos/bpmn/P<N>-<nome>.bpmn`, com a exportação em `processos/imagens/P<N>-<nome>.png`.
- Cada integrante faz commit dos próprios arquivos, porque o histórico de contribuições entra na avaliação.
- O texto do relatório é escrito no Google Docs. Na entrega, ele é exportado para `relatorio/relatorio.pdf`.

## Estrutura do ZIP de entrega

```
relatorio.pdf
processos/      # .bpmn + imagens
apresentacao/   # slides PDF + editável
README.md       # este arquivo
```
