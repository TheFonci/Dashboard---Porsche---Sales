  <div align="center">
  
  PORSCHE · SALES INTELLIGENCE
  Transformando dados de vendas em decisões mais inteligentes.
  Uma dashboard interativa para explorar o desempenho comercial da Porsche, identificar preferências por região e revelar padrões de compra com uma experiência visual inspirada no universo premium da marca.
  
  Business Intelligence · Data Analytics · Dashboard Interativa
  </div>
  
  Visão geral
  Porsche Sales Intelligence é um projeto de análise visual de dados desenvolvido para facilitar a leitura de indicadores comerciais em uma única interface. A aplicação reúne métricas de vendas, receita, ticket médio, modelos em destaque e tendências por ano-modelo, permitindo investigar diferentes recortes da base com poucos cliques.
  
  A proposta combina uma apresentação minimalista — com tons escuros, detalhes em vermelho e elementos tipográficos discretos — a uma navegação objetiva, priorizando clareza, hierarquia visual e leitura rápida dos resultados.
  Funcionalidades
  - Filtros dinâmicos: explore os registros por modelo Porsche, ano-modelo, cidade, forma de pagamento e período de venda.
  - Indicadores-chave (KPIs): acompanhe o volume de vendas, a receita total, o ticket médio e o modelo líder no recorte selecionado.
  - Ranking de modelos: identifique os modelos com maior frequência na base filtrada.
  - Distribuição por ano-modelo: compare a presença de diferentes anos-modelo entre os registros.
  - Insights automáticos: visualize destaques sobre preferências por cidade, ano-modelo, formas de pagamento e modelos populares.
  - Liderança por cidade: consulte o modelo mais frequente em cada cidade, o volume de vendas, sua participação local e a receita associada.
  - Layout responsivo: interface adaptada para telas menores, com reorganização dos filtros e painéis.
  Prévia da experiência
  A dashboard é organizada em quatro áreas principais:
  Área	O que apresenta
  Exploração	Filtros para personalizar o recorte de análise  
  Visão geral	KPIs para uma leitura rápida do desempenho
  Análise de mercado	Rankings, distribuição por ano-modelo e insights
  Desempenho regional	Modelos líderes e participação por cidade
  
  
  Tecnologias utilizadas
  O projeto foi implementado em uma página web independente, utilizando:
  - HTML5 — estrutura e organização do conteúdo.
  - CSS3 — identidade visual, componentes, grid responsivo e adaptação para dispositivos móveis.
  - JavaScript (Vanilla) — filtragem dos registros, cálculos dos indicadores e renderização dinâmica dos resultados.
  Não há dependência de frameworks front-end ou de um processo de build para abrir a página.
  Como executar
  1. Baixe ou clone este repositório.
  2. Localize o arquivo index.html.
  3. Abra-o em um navegador moderno.
  Como a aplicação está concentrada em um arquivo HTML com CSS, JavaScript e dados incorporados, não é necessário instalar dependências para visualizar a dashboard.
  Estrutura do projeto
  porsche-sales-intelligence/
  └── index.html   # Interface, estilos, lógica analítica e conjunto de dados
  Indicadores e lógica analítica
  Os principais indicadores são calculados com base nos registros que correspondem aos filtros ativos:
  - Vendas no recorte: quantidade de registros filtrados.
  - Receita total: soma dos valores de venda dos registros filtrados.
  - Ticket médio: receita total dividida pela quantidade de registros.
  - Modelo líder: modelo com maior frequência no recorte atual.
  - Modelos líderes por cidade: modelo mais frequente em cada cidade, acompanhado de volume, participação local e receita.
  Os insights são atualizados de acordo com os dados selecionados, ajudando a responder perguntas como:
  - Quais modelos aparecem com maior frequência em cada cidade?
  - Qual ano-modelo concentra mais registros no período selecionado?
  - Quais formas de pagamento são mais recorrentes?
  - Quais modelos se destacam no recorte analisado?
  Sobre os dados
  A aplicação utiliza uma base de dados incorporada ao próprio index.html, com campos relacionados a modelo Porsche, ano-modelo, preço de venda, data, cidade e forma de pagamento.
  
  Importante: os resultados representam os registros presentes na base fornecida e devem ser interpretados dentro desse contexto. Datas inválidas são desconsideradas nas análises por período, conforme indicado na própria dashboard. Antes de utilizar os números para decisões operacionais, recomenda-se validar a qualidade, a completude e a representatividade dos dados.
  Direção visual
  A interface adota uma linguagem visual editorial e premium:
  - Fundo em tons neutros e painéis claros para favorecer a leitura.
  - Cabeçalho escuro com destaque tipográfico.
  - Vermelho como cor de acento para sinalizar elementos relevantes.
  - Espaçamento generoso, bordas sutis e hierarquia consistente.
  - Componentes responsivos para manter a experiência funcional em diferentes tamanhos de tela.
  O layout é uma referência visual inspirada no posicionamento premium da Porsche e não representa, por si só, um produto oficial da marca.
  Possíveis evoluções
  - Conectar a dashboard a uma fonte de dados atualizada automaticamente.
  - Adicionar comparativos entre períodos e evolução mensal de vendas.
  - Incluir segmentações por estado, status de entrega e quilometragem.
  - Exportar relatórios e dados filtrados para CSV ou PDF.
  - Incorporar testes automatizados e validações de qualidade dos dados.
  Licença e uso
  Este repositório é apresentado como projeto demonstrativo de análise de dados. Defina uma licença explícita antes de permitir reutilização ou redistribuição por terceiros. Porsche e seus elementos de marca pertencem aos respectivos titulares.
  <div align="center">

Porsche Sales Intelligence
Clareza nos dados. Precisão na análise. Inteligência para decidir.
</div>
