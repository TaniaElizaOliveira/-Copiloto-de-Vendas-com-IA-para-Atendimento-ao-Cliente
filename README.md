# Copiloto de Vendas com IA para Atendimento ao Cliente

## Tema escolhido

O tema escolhido foi a criação de um **Copiloto de Vendas com IA genérico**, adaptável para diferentes tipos de produtos e serviços.

A solução pode ser usada em áreas como iluminação, tecnologia, moda, serviços, cursos, produtos digitais, consultoria, equipamentos, acessórios ou qualquer outro contexto comercial.

## Utilizador principal da solução

O utilizador principal é a pessoa vendedora, atendente comercial, responsável por atendimento online ou equipa comercial que precisa responder clientes com mais clareza, rapidez e estratégia.

## Problema de vendas ou atendimento que a solução resolve

Durante o atendimento comercial, muitos clientes demonstram interesse, mas ainda não sabem exatamente o que querem comprar, têm dúvidas, comparam preços ou apresentam objeções.

O copiloto ajuda a pessoa vendedora a:

- Entender melhor a necessidade do cliente;
- Fazer perguntas de qualificação;
- Sugerir uma oferta principal;
- Sugerir produtos ou serviços complementares;
- Lidar com objeções;
- Criar mensagens prontas para WhatsApp, Instagram, email ou chat;
- Indicar a próxima melhor ação comercial.

O objetivo não é substituir a pessoa vendedora, mas apoiar o atendimento com respostas mais claras, úteis e contextualizadas.

## Abordagem utilizada

A abordagem escolhida foi um **copiloto de vendas com prompt estruturado e base de conhecimento**.

A solução usa:

- Um prompt principal para orientar o comportamento da IA;
- Uma pequena base de conhecimento com contexto do negócio, produtos/serviços, perguntas frequentes e objeções comerciais;
- Exemplos práticos de atendimento para demonstrar o funcionamento.

## Estrutura do projeto

```text
copiloto-vendas-ia-atendimento-cliente/
│
├── README.md
├── .gitignore
│
├── prompt/
│   └── assistente-vendas-generico.md
│
├── knowledge/
│   ├── contexto-do-negocio.md
│   ├── produtos-servicos.md
│   ├── perguntas-frequentes.md
│   └── objecoes-comerciais.md
│
└── exemplos/
    ├── exemplo-1-cliente-duvida.md
    ├── exemplo-2-cliente-preco.md
    └── exemplo-3-cliente-indeciso.md
```

## Base de conhecimento utilizada

A base de conhecimento está na pasta `knowledge/`.

Ela contém informações sobre:

- Contexto geral do negócio;
- Tipos de produtos e serviços que podem ser vendidos;
- Perguntas frequentes feitas por clientes;
- Objeções comerciais comuns;
- Formas de responder com clareza e foco no cliente.

## Prompt principal do Copiloto

O prompt principal está disponível em:

```text
prompt/assistente-vendas-generico.md
```

Esse prompt define o papel da IA como assistente de vendas, orienta o formato das respostas e estabelece regras para evitar insistência, promessas falsas ou recomendações sem contexto.

## Exemplo de utilização

### Entrada do vendedor

```text
Interesse: cliente quer comprar lâmpadas LED para uma loja, mas está preocupado com o preço.
```

### Saída esperada do Copiloto

```text
A) Leitura do interesse do cliente
O cliente quer reduzir custos de energia na loja e está a avaliar se a troca para LED compensa financeiramente.

B) Diagnóstico de oportunidade
Classificação: Misto.
Existe potencial de venda principal, mas o cliente tem objeção de preço. É preciso mostrar valor e custo-benefício.

C) Perguntas de qualificação
1. Quantas lâmpadas pretende substituir?
2. A loja usa iluminação durante muitas horas por dia?
3. Prefere luz quente, neutra ou fria?
4. Tem uma faixa de orçamento definida?
5. Quer uma opção mais económica ou uma solução com maior durabilidade?

D) Oferta principal recomendada
Oferecer lâmpadas LED adequadas para uso comercial, destacando economia de energia e maior durabilidade.

E) Oferta complementar inteligente
Sugerir acessórios ou produtos complementares apenas se forem úteis, como luminárias, sensores ou opções de maior eficiência.

F) Estratégia de ancoragem
Apresentar uma opção de custo-benefício e uma opção mais completa, sem inventar preços.

G) Mensagem pronta para enviar ao cliente
Compreendo a preocupação com o preço. Para uma loja, as lâmpadas LED costumam fazer sentido porque ajudam a reduzir o consumo de energia e têm maior durabilidade. Posso indicar uma opção com boa relação qualidade/preço, mas para acertar melhor precisava de saber quantas lâmpadas pretende substituir e se prefere luz quente, neutra ou fria.
```

## Possíveis melhorias futuras

Algumas melhorias possíveis:

- Criar um chatbot real integrado num site;
- Integrar o copiloto com WhatsApp ou Instagram;
- Ligar a IA a um catálogo de produtos;
- Criar uma pontuação para priorizar leads;
- Guardar histórico de conversas;
- Gerar propostas comerciais automáticas;
- Adaptar o copiloto para setores específicos;
- Criar uma interface simples em web app.

## Resultado esperado

Este projeto demonstra como a IA pode apoiar vendas e atendimento ao cliente de forma prática, ajudando a pessoa vendedora a organizar informações, responder melhor aos clientes e aumentar oportunidades de conversão.
