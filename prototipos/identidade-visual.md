# Identidade visual da RotaRango

Fonte única para o protótipo no Figma e para os slides. Os esboços em `esbocos/esbocos.html` já usam estes valores.

## Ideia

O nome tem duas metades, e cada uma ganhou uma cor:

- **rango** (comida) usa **pimenta**, uma cor quente. É a face da marca e do app do cliente. No delivery de comida, cor quente remete a comida e abre o apetite. O tom queimado se afasta do vermelho vivo do iFood e do laranja claro do Rappi.
- **rota** (logística) usa **petróleo**. É a cor da operação: app do entregador, portal do restaurante e backoffice. Passa confiança e lembra mapa.
- **Mostarda** liga as duas: serve de destaque, de selo "novo" e do que pede ação do entregador.

O tom é brasileiro, informal sem ser infantil, direto e confiável. A marca fala com "você".

## Cores

| Token | Hex | Uso |
| --- | --- | --- |
| Pimenta 700 | `#C2410C` | Logo, botão principal do cliente, links do cliente |
| Pimenta 950 | `#431407` | Cartão do código de entrega (fundo escuro no app do cliente) |
| Pimenta 100 | `#FFEDD5` | Fundo suave de destaque no cliente |
| Mostarda 500 | `#F5B700` | Destaque, ação do entregador, contagem regressiva, selo "novo" (texto sempre escuro por cima) |
| Mostarda 100 | `#FFF4CC` | Fundo de selo |
| Petróleo 700 | `#0F766E` | Botão principal na operação (restaurante e backoffice) |
| Petróleo 900 | `#0B3B39` | Menu lateral web, base do modo escuro do entregador |
| Petróleo 100 / 50 | `#E6F4F1` / `#F2FAF8` | Fundo de área de trabalho web, selos informativos |
| Creme | `#FFF8EE` | Fundo do app do cliente |
| Tinta | `#1C2426` | Texto principal |
| Cinza 600 | `#5B6B6E` | Texto secundário |
| Cinza 300 / 100 | `#D5DDDC` / `#EEF2F1` | Bordas e divisórias |

**Estados.** Usar sempre texto escuro sobre fundo claro do mesmo tom:

| Estado | Texto | Fundo |
| --- | --- | --- |
| Sucesso (pago, entregue, aprovado) | `#276749` | `#E6F4EA` |
| Alerta (pendência, atraso, divergência) | `#92400E` | `#FEF3C7` |
| Erro (recusado, inválido) | `#C53030` | `#FDECEC` |
| Informação (em análise, em andamento) | `#115E59` | `#E6F4F1` |

**Contraste (WCAG 2.1 AA, RNF04)**, todos medidos:

| Combinação | Contraste |
| --- | --- |
| Branco sobre pimenta | 5,18 : 1 |
| Branco sobre petróleo | 5,47 : 1 |
| Tinta sobre mostarda | 8,77 : 1 |
| Tinta sobre creme | 14,98 : 1 |
| Cinza 600 sobre creme | 5,28 : 1 |
| Pimenta sobre creme | 4,91 : 1 |
| Mostarda sobre o fundo escuro do entregador | 9,87 : 1 |
| Mostarda sobre pimenta 950 | 8,69 : 1 |
| Selos de estado: sucesso, alerta, erro, informação | 5,92 / 6,37 / 4,79 / 6,71 : 1 |

Mostarda nunca é cor de texto sobre fundo branco (1,8 : 1). Sobre fundo escuro, pode.

## Tipografia

- **Plus Jakarta Sans** (Google Fonts):
  - títulos 800;
  - rótulos e botões 700;
  - texto 400 e 500.
- Tamanhos no app:
  - título de tela 17–20 px;
  - texto 14 px;
  - legenda 11–12 px;
  - valor em destaque 30–40 px.
- **JetBrains Mono 700** para número de pedido (`#4821`), código de entrega (`4827`) e contagem regressiva.

## Forma e espaço

- Cantos:
  - 12 px em cartões e botões;
  - 20 px em folhas e painéis grandes;
  - pílula para chips e selos.
- Espaçamento em múltiplos de 4.
- Margem lateral de 16 px no celular.
- Sombra suave e esverdeada: `0 4px 14px rgba(11,59,57,.08)`.
- Alvo de toque mínimo de 48 px. No app do entregador, o botão principal tem 60 px.

## Por perfil

| Perfil | Base | Ação principal | Observação |
| --- | --- | --- | --- |
| Cliente (app) | Creme, fotos quentes de comida | Pimenta | Botão principal fixo no rodapé |
| Entregador (app) | **Escuro** (`#0E1A1A` e petróleo 900) | Mostarda com texto escuro | Usado na rua, de dia e de noite: alto contraste, letra grande, uma decisão por tela |
| Restaurante (web) | Menu petróleo 900 e área petróleo 50 | Petróleo | Tela de balcão, vista de longe |
| Plataforma (web) | Igual ao restaurante | Petróleo | Densa: fila à esquerda, detalhe à direita, motivo obrigatório nas decisões |

## Logo

- **Símbolo:** quadrado de cantos arredondados em pimenta. Dentro, uma rota branca em curva que sai de um ponto branco e termina num ponto mostarda (o destino).
- **Escrita:** tudo em minúsculas, em Plus Jakarta Sans 800, com "rota" em petróleo e "rango" em pimenta.
- **Sobre fundo escuro** (menu web, modo escuro, slide de abertura), a escrita fica **toda branca**: pimenta e petróleo não têm contraste ali. O símbolo continua pimenta.
- O SVG do símbolo está no cabeçalho de `esbocos/esbocos.html`.

## Para os slides

- **Fundos:**
  - creme, para conteúdo;
  - petróleo 900, para abertura, divisória de seção e encerramento.
- **Títulos** em Plus Jakarta Sans 800, na cor tinta ou branca.
- **Destaques:**
  - pimenta para tudo que é do cliente ou da marca;
  - petróleo para operação e processos;
  - mostarda para números e chamadas.
- **Diagramas BPMN** sempre sobre fundo branco, em cartão com canto de 12 px.
