# Business Intelligence na Construção Civil

## DESAFIO DE PROJETO

### Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM

**Business Intelligence na Construção Civil**

Uma aplicação prática do NotebookLM para transformar materiais técnicos sobre Business Intelligence e Construção Civil em um assistente inteligente de aprendizagem, criado para apoiar meus estudos e ampliar minha capacidade de análise e tomada de decisão baseada em dados.

---

# Contexto

A transformação digital vem modificando a forma como obras são planejadas, executadas e monitoradas. Nesse cenário, o Business Intelligence (BI) se destaca como uma ferramenta estratégica para organizar informações, acompanhar indicadores de desempenho e apoiar a tomada de decisões durante todo o ciclo de uma obra.

Como estudante de Engenharia Civil, tenho percebido a importância da análise de dados para o planejamento, controle físico-financeiro, produtividade, custos e gestão de obras. Ao mesmo tempo, venho despertando um interesse crescente por Business Intelligence e suas aplicações no setor da construção.

Diante desse contexto, este projeto propõe a construção de um caderno temático utilizando o NotebookLM, transformando a Inteligência Artificial em um assistente especializado de aprendizagem. A partir de materiais técnicos e referências confiáveis, o objetivo é centralizar o conhecimento em uma única base de consulta, permitindo compreender conceitos de BI, explorar ferramentas de análise de dados e identificar aplicações práticas na Engenharia Civil.

---

# Objetivo Geral

Utilizar o NotebookLM para desenvolver um assistente inteligente de aprendizagem sobre Business Intelligence aplicado à Construção Civil, apoiando meus estudos por meio de respostas fundamentadas em fontes confiáveis e facilitando a compreensão de conceitos, ferramentas, indicadores e aplicações práticas da análise de dados na gestão de obras.

---

# Objetivos de estudo

* Compreender os fundamentos de Business Intelligence.
* Aprender como os dados podem apoiar a gestão de obras.
* Conhecer os principais indicadores utilizados na construção civil.
* Entender conceitos de ETL, Data Warehouse e modelagem de dados.
* Aprender boas práticas para criação de dashboards.
* Explorar o uso do Power BI na análise de custos, produtividade e planejamento.
* Desenvolver uma base de conhecimento organizada para consultas e revisões.
* Utilizar engenharia de prompts para potencializar o uso do NotebookLM como ferramenta de aprendizagem.

---

# Escopo do Assistente

O assistente foi projetado para atuar como uma ferramenta complementar aos estudos sobre Business Intelligence aplicado à Construção Civil, oferecendo respostas fundamentadas e contextualizadas nas fontes disponibilizadas no NotebookLM.

---

# Curadoria de fontes

Foram selecionadas fontes técnicas e acadêmicas relacionadas a Business Intelligence, Power BI e gestão da Construção Civil. A base de conhecimento do NotebookLM é composta por materiais adicionais utilizados durante a exploração do tema. Abaixo são apresentadas as principais fontes utilizadas como referência para o desenvolvimento do projeto.

1. [Power BI Fundamentals](./power-bi-fundamentals.zip)
2. [ANÁLISE DO POWER BI COMO FERRAMENTA DE GERENCIAMENTO](./ANÁLISE%20DO%20POWER%20BI%20COMO%20FERRAMENTA%20DE%20GERENCIAMENTO.pdf)
3. [Aula-1_12.05.2020-Curso-Gerenciamento-de-Obras-](./Aula-1_12.05.2020-Curso-Gerenciamento-de-Obras-.pdf)
4. [Aplicação do Business Intelligence and Analytics na construção civil](./Aplica%C3%A7%C3%A3o%20do%20Business%20Intelligence%20and%20Analytics%20na%20constru%C3%A7%C3%A3o%20civil.pdf)
5. [BIM Guia completo]([https://www.youtube.com/...](https://sienge.com.br/blog/tudo-sobre-bim/)
---

# Engenharia de Prompts e "Cicatrizes"

A engenharia de prompts foi utilizada como estratégia de aprendizagem e investigação, buscando explorar a aplicação do Business Intelligence no contexto da Construção Civil.

Em vez de utilizar o NotebookLM apenas para obter definições, foram elaboradas perguntas estratégicas que exigissem análise, correlação entre conceitos, interpretação de cenários e aplicação prática.

Os prompts foram refinados progressivamente a partir das respostas obtidas, considerando a qualidade das informações, a utilização das fontes, a profundidade da análise e a aderência ao contexto da Construção Civil.

---

# 01. Quais dados de uma obra realmente têm valor para BI?

## Prompt inicial

> Quais tipos de dados gerados durante o planejamento e execução de uma obra apresentam maior potencial para serem utilizados em uma solução de Business Intelligence?

## Resposta obtida

> Os dados gerados durante o planejamento e a execução de uma obra que apresentam maior potencial para soluções de Business Intelligence (BI) abrangem as esferas financeira, temporal, operacional e técnica. A centralização dessas informações permite uma visão estratégica, facilitando a identificação de desvios e o suporte à tomada de decisão.
>
> Com base nas fontes, os principais tipos de dados incluem:

### 1. Dados de Planejamento e Orçamentação

* **Orçamentos e Custos Previstos:** Planilhas orçamentárias analíticas, incluindo quantitativos de serviços, insumos (materiais, mão de obra e equipamentos) e o cálculo do BDI (Benefício e Despesas Indiretas).
* **Cronogramas Físico-Financeiros:** Prazos estipulados para cada etapa, datas de início e término e o fluxo de desembolso previsto.
* **Curva ABC:** Classificação de insumos e serviços por impacto financeiro, essencial para priorizar negociações e controle de estoque.
* **Estudos de Viabilidade:** Dados sobre a viabilidade econômica e financeira do empreendimento.

### 2. Dados de Execução e Monitoramento

* **Acompanhamento "Previsto vs. Realizado":** Comparação em tempo real entre o progresso físico e os gastos reais em relação ao que foi planejado.
* **Medições de Obra:** Registros de serviços efetivamente executados e liberações de pagamentos para empreiteiros.
* **Apropriação de Recursos:** Dados detalhados sobre o consumo de materiais, horas de mão de obra (histogramas) e utilização de equipamentos.
* **Diário de Obras:** Registros diários de atividades, efetivo, clima, ocorrências e imprevistos.
* **Gestão de Suprimentos:** Requisições de compra, cotações, pedidos, notas fiscais e controle de entrada de materiais no canteiro.

### 3. Indicadores de Desempenho e Qualidade

* **Produtividade:** Relação entre a duração planejada e a real, ou metros quadrados produzidos por equipe, para ajustar planejamentos futuros.
* **Gestão da Qualidade e Segurança:** Dados de ensaios, controle tecnológico, não conformidades, documentos de segurança (como PPRA e PCMSO) e registros de treinamentos.
* **Impacto Ambiental:** Índices de desperdício de materiais e consumo de água e energia.

### 4. Dados Técnicos e de Projetos

* **Extração de Quantitativos (BIM/CAD):** Volumes de concreto, áreas de revestimento e contagem de elementos extraídos diretamente de modelos 3D (BIM) ou desenhos CAD.
* **Status de Projetos:** Controle de revisões de plantas e documentos técnicos para evitar o uso de informações obsoletas no campo.

### 5. Dados Administrativos e Contratuais

* **Contratos e Aditivos:** Status de contratação, prazos contratuais, marcos ("milestones") e termos aditivos.
* **Fluxo de Caixa:** Controle analítico de contas a pagar e a receber, entradas e saídas de recursos financeiros da obra.

A utilização desses dados em ferramentas como o Power BI permite que gestores substituam o acompanhamento manual por dashboards interativos, que unificam fontes distintas (Excel, ERPs, SQL, BIM) para monitorar o progresso da obra em tempo real através de dispositivos móveis.

## Fontes

* Análise do Power BI como ferramenta de gerenciamento de projetos
* Vídeo: Como praticar Power BI na Construção Civil
* Aplicação do Business Intelligence e Analytics na Construção Civil
* Curso Gerenciamento de Obras
* Tecnologia como apoio ao gerenciamento

## Problema identificado na resposta

A resposta inicial apresentou um levantamento amplo e organizado dos principais tipos de dados gerados no planejamento e na execução de uma obra.

Entretanto, a análise permaneceu predominantemente descritiva, concentrando-se na identificação dos dados e não aprofundando suficientemente a relação entre cada tipo de dado, os indicadores que podem ser derivados dele e as decisões de gestão que essas informações podem apoiar.

Diante disso, o prompt foi refinado para investigar não apenas quais dados podem ser utilizados em BI, mas também como esses dados podem ser transformados em informações relevantes para a gestão de uma obra.

## Variação do prompt

> A partir dos tipos de dados identificados na resposta anterior, aprofunde a análise sobre o valor desses dados para uma solução de Business Intelligence aplicada à Construção Civil.
>
> Para cada categoria de dados, explique:
>
> * quais informações podem ser extraídas;
> * quais indicadores podem ser construídos ou acompanhados;
> * quais comparações ou análises podem ser realizadas;
> * quais decisões de gestão essas informações podem apoiar.
>
> Priorize exemplos relacionados a planejamento, custos, prazo, produtividade e execução física da obra.
>
> Estabeleça, sempre que possível, a relação entre dado, indicador, análise e tomada de decisão.

## Nova resposta

A análise de Business Intelligence (BI) na construção civil transforma dados brutos em inteligência estratégica, permitindo que gestores substituam a intuição por decisões baseadas em fatos.

Abaixo, detalho as categorias principais, estabelecendo o ciclo entre o dado, o indicador e a tomada de decisão.

### 6. Dados de Planejamento e Orçamentação

**Informações extraídas:** Quantitativos de serviços e insumos, custos unitários (CPU) e o orçamento analítico detalhado.

**Indicadores construídos:** Curva ABC (concentração financeira por item), Custo por metro quadrado (m²) e margem de BDI (Benefício e Despesas Indiretas).

**Análises realizadas:** Identificação de quais insumos (como aço ou concreto) representam o maior peso no custo total (itens de Classe A), permitindo focar esforços onde o impacto financeiro é maior.

**Decisão de gestão:** Priorização de negociações estratégicas com fornecedores dos itens Classe A para proteger o orçamento e garantir a margem de lucro.

### 7. Dados de Prazos e Cronograma

**Informações extraídas:** Datas de início e término de tarefas, interdependências (caminho crítico) e marcos contratuais ("milestones").

**Indicadores construídos:** Percentual de avanço físico, Desvio de prazo (dias de atraso/adiantamento) e a Curva S física.

**Análises realizadas:** Comparação entre o "Previsto vs. Realizado" para identificar se o ritmo da obra permitirá a entrega no prazo estipulado. A interatividade do BI permite filtrar semanas críticas de baixo desempenho.

**Decisão de gestão:** Aceleração de frentes de serviço atrasadas por meio da alocação de equipes extras ou turnos adicionais para evitar multas contratuais.

### 8. Dados de Custos e Execução Financeira

**Informações extraídas:** Notas fiscais lançadas no ERP, medições de empreiteiros, fluxo de caixa analítico e variações de índices como o INCC.

**Indicadores construídos:** Curva S financeira, Saldo de contrato e Variação de custo nominal e percentual.

**Análises realizadas:** Cruzamento do desembolso real com a correção monetária (INCC) para entender se o estouro de custos é fruto de inflação de mercado ou ineficiência na gestão de canteiro.

**Decisão de gestão:** Readequação do fluxo de desembolso, antecipação de compras de insumos para evitar altas futuras e aplicação de aditivos contratuais quando necessário.

### 9. Dados de Produtividade e Recursos

**Informações extraídas:** Histogramas de mão de obra e equipamentos, registros do Diário de Obras (RDO) e apropriações de campo.

**Indicadores construídos:** Índice de Produtividade (ex: m² de alvenaria por pedreiro/dia) e Taxa de ociosidade de equipamentos.

**Análises realizadas:** Benchmarking entre diferentes obras ou equipes para identificar quais possuem melhor performance e quais precisam de treinamento ou substituição.

**Decisão de gestão:** Dimensionamento correto da equipe para as próximas etapas, evitando equipes subdimensionadas (que geram atrasos) ou superdimensionadas (que geram custos desnecessários).

### 10. Dados de Execução Física e Materiais

**Informações extraídas:** Volumes de materiais recebidos vs. quantitativos extraídos de modelos BIM ou desenhos técnicos.

**Indicadores construídos:** Índice de Desperdício e percentual de Material em estoque vs. Necessário.

**Análises realizadas:** Identificação de discrepâncias entre o que foi projetado e o que foi efetivamente consumido na obra, sinalizando falhas na execução ou perdas excessivas.

**Decisão de gestão:** Ajuste nos processos de recebimento e armazenamento de materiais ou correção de metodologias executivas que estejam gerando retrabalho e desperdício.

A integração desses dados em um Data Warehouse centralizado permite que as decisões sejam tomadas de forma ágil ("aqui e agora"), reduzindo as incertezas e transformando o Power BI em um sistema de suporte à decisão essencial para a competitividade da construtora.

### Fontes utilizadas

* AcadBi Modulo 1
* Live Power BI para construção civil
* Tecnologia como apoio ao planejamento
* Aplicação do BI and Analytics
* TCC aplicação do Power BI

---

# 02. Como estruturar um dashboard de BI para uma obra?

## Prompt inicial

> Como um dashboard de Business Intelligence poderia ser estruturado para o acompanhamento de uma obra?

## Resposta obtida

A estruturação de um dashboard de Business Intelligence para o acompanhamento de uma obra deve ser pensada para transformar dados brutos em insights estratégicos, permitindo uma gestão ágil e fundamentada em fatos.

Com base nos documentos, um dashboard eficaz é composto por três pilares principais: o processo de tratamento de dados, a seleção de indicadores-chave (KPIs) e a aplicação de técnicas de visualização e storytelling.

### 12. Estrutura de Dados e Modelagem (Back-end)

Antes da visualização, o dashboard requer uma base sólida:

* **ETL (Extração, Transformação e Carga):** Os dados são extraídos de fontes como planilhas Excel, ERPs (como o Sienge ou TOTVS) ou softwares de planejamento (MS Project). No Power BI, utiliza-se o Power Query para limpar e padronizar essas informações.
* **Modelagem de Dados:** Recomenda-se o uso do esquema em estrela (Star Schema), onde uma "tabela fato" (com registros de eventos como custos ou medições) é conectada a "tabelas dimensão" (como calendário, lista de serviços ou responsáveis).
* **Medidas DAX:** São criadas fórmulas para cálculos complexos, como acumulados de custo, percentuais de desvio e tendências.

### 13. Conteúdo e Indicadores Sugeridos (Visualizações)

Um dashboard de obra costuma ser dividido em telas ou áreas temáticas para facilitar a navegação:

#### Visão Geral e Planejamento

* **Cartões:** Para exibir valores totais, como Custo Total, Prazo Decorrido e Valor por m².
* **Tabela de Avanço (EAP):** Listagem das etapas da obra com seus respectivos percentuais de conclusão.
* **Marcos Contratuais:** Painel de status para monitorar datas críticas do cronograma.

#### Custos e Orçamento

* **Curva S (Física e Financeira):** Gráfico de linhas que compara o avanço planejado acumulado versus o realizado, destacando desvios ao longo do tempo.
* **Curva ABC:** Gráficos (como o Treemap) que mostram o peso financeiro de cada insumo ou pacote de serviço, permitindo focar nos itens de maior impacto.
* **Gráficos de Dispersão:** Úteis para identificar tarefas "fora da curva" que estão custando muito acima do esperado.

#### Recursos e Produtividade

* **Histogramas de Mão de Obra e Equipamentos:** Gráficos de barras que mostram a mobilização semanal de trabalhadores (prevista vs. real), ajudando a identificar equipes subdimensionadas.
* **Indicadores de Recebimento de Materiais:** Comparação entre o quantitativo extraído do modelo BIM/Revit e o que já foi efetivamente entregue no canteiro.

### 14. Design e Storytelling (Front-end)

A apresentação visual deve conduzir o olhar do gestor para o que realmente importa:

* **Padrão de Leitura em Z:** As informações mais críticas (como KPIs principais) devem ficar no canto superior esquerdo, seguindo o movimento natural dos olhos.
* **Recursos Pré-atentivos:** Uso estratégico de cores (ex: azul para metas atingidas, vermelho para atrasos) e ícones para facilitar a interpretação rápida.
* **Interatividade:** O uso de segmentadores de dados (filtros) permite que o usuário selecione períodos específicos, obras ou frentes de serviço, atualizando todos os gráficos instantaneamente.
* **Design Profissional:** Utilização de ferramentas como o Figma para criar planos de fundo que organizam e separam visualmente cada indicador.

### 15. Acesso e Mobilidade

A estrutura final deve ser publicada no Power BI Online (SaaS) para compartilhamento com as partes interessadas.

Isso permite que engenheiros e clientes acessem o dashboard via Power BI Mobile diretamente de smartphones ou tablets no canteiro de obras, eliminando a dependência de relatórios físicos ou e-mails.

## Fontes

* Aplicação BI e Analitycs
* Anélise do Power BI como ferramenta
* Dashboard com storytelling
* Power BI Fundamentals
* Live Power BI para construção civil
* TCC aplicação do Power BI

## Problema identificado na resposta

A resposta apresentou uma estrutura técnica abrangente, contemplando desde o tratamento dos dados até a publicação do dashboard.

Entretanto, apresentou uma grande quantidade de indicadores e recursos de visualização sem aprofundar os critérios utilizados para definir quais informações são prioritárias para o usuário do dashboard.

O refinamento buscou compreender como selecionar e organizar os indicadores de acordo com as necessidades de gestão da obra, evitando que o excesso de informações prejudique a análise e a tomada de decisão.

## Variação do prompt

> A partir da estrutura apresentada, aprofunde os critérios para definir quais indicadores e informações devem realmente compor um dashboard destinado à gestão de uma obra.
>
> Considere diferentes necessidades de acompanhamento, como prazo, custos, avanço físico, produtividade e recursos. Explique como priorizar os indicadores, quais informações poderiam ser apresentadas em uma visão geral e quais poderiam ser disponibilizadas em análises mais detalhadas.
>
> Analise também como evitar o excesso de informações e como garantir que o dashboard apoie efetivamente a identificação de desvios e a tomada de decisão.

## Nova resposta

Para definir os indicadores e informações de um dashboard de gestão de obras, o critério fundamental é a capacidade de suporte à tomada de decisão, transformando dados brutos em inteligência estratégica.

A estruturação deve seguir uma lógica de priorização baseada no impacto financeiro e operacional, utilizando técnicas de Storytelling para garantir clareza e evitar a sobrecarga de informações.

Abaixo, detalho os critérios de seleção e organização das informações:

### 1. Critérios de Priorização de Indicadores

A priorização deve ser guiada pela Tríplice Restrição (Escopo, Tempo e Custo) e pela Curva ABC.

* **Foco no Impacto (Regra 80/20):** O dashboard deve destacar os itens da "Classe A", que representam cerca de 80% do valor total do orçamento, permitindo que o gestor concentre esforços onde o risco financeiro é maior.
* **Níveis de Gestão:**

  * **Estratégico:** Visão de longo prazo e saúde financeira global (ex: ROI, desvio orçamentário total).
  * **Tático/Operacional:** Acompanhamento "aqui e agora", como produtividade diária e marcos semanais.

### 2. Estrutura da Informação: Visão Geral vs. Detalhada

Um dashboard eficaz deve ser organizado para conduzir o olhar do usuário através de uma hierarquia lógica.

#### Visão Geral (Painel Principal)

Deve fornecer uma "fotografia" instantânea do status da obra para decisões rápidas:

* **Cartões de Resumo:** Custo Total Realizado vs. Previsto, Percentual de Avanço Físico e Dias Decorridos/Restantes.
* **Curva S (Física e Financeira):** Gráfico macro que compara o progresso acumulado planejado com o real, evidenciando tendências de atraso ou estouro orçamentário.
* **Status de Marcos Contratuais:** Sinalizadores coloridos (semáforos) para datas críticas.

#### Análises Detalhadas (Níveis de Drill-down)

Permitem investigar a causa raiz dos desvios apontados na visão geral:

* **Custos por Insumo:** Detalhamento do orçamento analítico para identificar quais serviços específicos (ex: concreto, armação) estão gerando variações.
* **Histogramas de Recursos:** Gráficos de barras comparando a mobilização prevista vs. real de mão de obra e equipamentos para ajustar o dimensionamento das equipes.
* **Produtividade:** Índices específicos, como m² de alvenaria por pedreiro/dia, para comparar a performance entre diferentes equipes ou obras.
* **Gestão de Suprimentos:** Acompanhamento do recebimento de materiais (quantitativo extraído do BIM vs. Notas Fiscais recebidas) para evitar desabastecimento.

### 3. Como Evitar o Excesso de Informações

O excesso de dados pode causar confusão e paralisia na tomada de decisão. Para mitigar isso:

* **Remoção de Saturação:** Elimine elementos visuais irrelevantes, como bordas excessivas ou cores desnecessárias que não agregam valor à análise.
* **Padrão de Leitura em Z:** Posicione os indicadores mais críticos no canto superior esquerdo, seguindo o movimento natural dos olhos durante a leitura.
* **Uso de Filtros Interativos (Slicers):** Em vez de mostrar todos os dados de uma vez, utilize segmentadores por período (mês/ano), etapa da obra ou tipo de serviço.

### 4. Garantia de Apoio à Tomada de Decisão

Para que o dashboard não seja apenas um "painel de visualização", ele deve estar integrado ao ciclo PDCA (Planejar, Fazer, Checar, Agir):

* **Identificação Visual de Desvios:** Utilize recursos pré-atentivos, como cores (vermelho para desvios negativos, azul para metas atingidas) e ícones de alerta para destacar onde a intervenção é necessária.
* **Confiabilidade da Fonte:** A eficácia da decisão depende da qualidade do dado no ERP ou no Data Warehouse. Dados errados levam a decisões equivocadas.
* **Mobilidade:** O acesso via dispositivos móveis permite que o engenheiro identifique um desvio de produtividade diretamente no canteiro e tome medidas corretivas imediatas, como a realocação de frentes de serviço.

## Fontes utilizadas

* Aplicação BI e Analitycs
* Anélise do Power BI como ferramenta
* Dashboard com storytelling
* Power BI Fundamentals
* Live Power BI para construção civil
* TCC aplicação do Power BI
* Tecnologia como apoio
* AcadBI

---

# 03. BI começa no dashboard?

## Prompt inicial

> Imagine que uma construtora deseja implementar Business Intelligence, mas seus dados são descentralizados, possuem inconsistências e são atualizados manualmente.
>
> Analise se a implementação de um dashboard seria suficiente para solucionar o problema.
>
> Explique quais problemas deveriam ser tratados antes da criação das visualizações e quais etapas seriam necessárias para que os dados pudessem gerar informações confiáveis para a tomada de decisão.

## Resposta obtida

A implementação de um dashboard não seria suficiente para solucionar o problema de forma isolada.

Na verdade, criar visualizações sobre dados descentralizados e inconsistentes pode ser perigoso, pois, como indicam as fontes, "dados errados levam a relatórios errados, o que pode resultar em decisões equivocadas".

Para que a construtora gere informações confiáveis, é necessário tratar a base tecnológica e os processos de gestão antes de chegar à camada visual.

Abaixo, detalho os problemas a serem tratados e as etapas necessárias:

### 6. Problemas que devem ser tratados antes das visualizações

* **Obtenção Caótica da Informação:** A descentralização (dados em planilhas diversas, e-mails e anotações) gera o que as fontes chamam de "obtenção caótica", onde não se sabe onde o dado está ou qual é o seu nível de consistência. É preciso primeiro unificar os dados em um repositório único (como um Data Warehouse) para evitar discussões sobre qual fonte é a correta em reuniões de decisão.
* **Inconsistências na Fonte:** O Power BI não corrige dados corrompidos ou que não condizem com a realidade; a correção deve ocorrer na fonte (como o ERP ou a planilha original). Erros de preenchimento manual e duplicidades precisam ser sanados para garantir a integridade.
* **Processos Manuais e Obsoletos:** O uso exclusivo de planilhas manuais gera riscos de perda de informação e falhas de comunicação. A gestão deve migrar para um modelo onde a coleta de dados no canteiro de obras seja parte de um processo bem definido e, preferencialmente, automatizado.

### 7. Etapas para gerar informações confiáveis (Ciclo de BI)

Para transformar esse cenário, a construtora deve seguir estas etapas técnicas e gerenciais:

### 8. Extração, Transformação e Carga (ETL)

Utilizando ferramentas como o Power Query, deve-se conectar às diversas fontes (Excel, bancos de dados, PDFs), realizar a limpeza dos dados (remover colunas inúteis, filtrar nulos, ajustar tipos de dados) e padronizá-los.

### 9. Modelagem de Dados

Após o tratamento, as tabelas devem ser organizadas.

Recomenda-se o uso do Star Schema (esquema em estrela), conectando "tabelas fato" (eventos como medições e custos) a "tabelas dimensão" (contexto como calendário, lista de obras ou fornecedores).

### 10. Criação de Medidas e Indicadores (DAX)

Antes de criar gráficos, é necessário definir as regras de negócio através de fórmulas (linguagem DAX).

Isso garante que indicadores como "Custo por m²" ou "Desvio de Prazo" sejam calculados de forma idêntica para todos os projetos.

### 11. Implementação de uma Camada Semântica

É essencial que a informação "sirva" aos usuários em uma linguagem de negócios clara, para que todos na construtora entendam o significado de cada indicador sem necessidade de intérpretes.

### 12. Criação do Dashboard com Storytelling

Somente nesta última etapa os dados são visualizados.

Deve-se usar técnicas de Storytelling para organizar os gráficos de forma lógica (seguindo o padrão de leitura em Z), destacando o que é mais importante para a tomada de decisão rápida.

Em resumo: O dashboard é apenas a "ponta do iceberg". O valor real do Business Intelligence reside na qualidade do tratamento dos dados (ETL) e na confiabilidade da fonte, permitindo que o gestor deixe de "andar com os olhos vendados" e passe a agir com base em fatos integrados.

## Fontes

* Aplicação BI e Analytics
* AcadBI
* O que é Data Warehouse
* Tecnologia como apoio ao planejamento
* Dashboard com storytelling
* Live Power BI para construção civil

---

# 04. Como BIM e BI podem trabalhar juntos na Construção Civil?

## Prompt inicial

> Como a integração entre Building Information Modeling (BIM) e Business Intelligence (BI) pode contribuir para a análise e tomada de decisão na Construção Civil? Explique quais tipos de dados provenientes de modelos BIM poderiam ser utilizados em uma solução de BI e quais análises poderiam ser realizadas a partir dessa integração.

## Resposta obtida

A integração entre Building Information Modeling (BIM) e Business Intelligence (BI) contribui para a construção civil ao transformar modelos digitais inteligentes em fontes de dados estratégicos, permitindo uma gestão de obras mais eficiente, previsível e baseada em informações precisas.

Enquanto o BIM gera uma representação digital rica em detalhes técnicos, o BI permite analisar esses dados de forma dinâmica e interativa, apoiando a tomada de decisão rápida tanto no escritório quanto no canteiro de obras através de dispositivos móveis.

### Contribuições para a Tomada de Decisão

* **Redução de incertezas e riscos:** A análise visual de dados integrados mitiga falhas de planejamento e estouros de orçamento ao permitir a identificação de problemas antes mesmo da execução física.
* **Colaboração e transparência:** Centraliza as informações de diferentes disciplinas (arquitetura, estrutura, instalações), garantindo que todos os envolvidos trabalhem com uma única fonte da verdade.
* **Agilidade operacional:** Relatórios automáticos eliminam a necessidade de apresentações manuais e e-mails constantes, fornecendo atualizações em tempo real sobre o status da obra.

### Tipos de Dados Provenientes de Modelos BIM

Para uma solução de BI, podem ser extraídos diversos dados estruturados de modelos BIM (como arquivos do Revit ou IFC):

* **Quantitativos:** Volumes de concreto, contagem de blocos cerâmicos, áreas de revestimento e pesos de armação.
* **Parâmetros e Especificações:** Dados detalhados sobre cada elemento, como espessura de paredes, tipos de materiais e propriedades físicas.
* **Cronograma (BIM 4D):** Informações de prazos e sequenciamento de atividades vinculadas aos objetos espaciais.
* **Custos (BIM 5D):** Valores associados a cada insumo e serviço, permitindo a análise do impacto financeiro ao longo do tempo.
* **Desempenho e Manutenção (BIM 6D e 7D):** Dados sobre consumo de energia, vida útil de equipamentos e registros para manutenção preventiva.

### Análises Realizadas a Partir da Integração

A união dessas tecnologias permite realizar análises complexas que vão além do acompanhamento tradicional:

* **Acompanhamento de Recebimento de Materiais:** Comparação em tempo real entre o quantitativo extraído do modelo BIM e o que foi efetivamente entregue e registrado no canteiro, permitindo monitorar o progresso diário.
* **Simulação de Cenários de Execução:** Análise visual do progresso da obra para comparar diferentes métodos construtivos e escolher a opção mais eficiente em termos de custo-benefício.
* **Detecção de Conflitos (Clash Detection):** Identificação de interferências entre sistemas (ex: tubulação hidráulica passando por uma viga) antes da obra começar, evitando retrabalhos dispendiosos.
* **Orçamentação Interativa com Modelo 3D:** Dashboards que permitem clicar em um elemento do modelo 3D para visualizar instantaneamente seu peso no orçamento total e sua posição na Curva ABC.
* **Ajuste de Produtividade Futura:** Comparação entre durações planejadas no modelo e durações reais coletadas em campo para corrigir parâmetros de produtividade em planejamentos de obras futuras.

## Fontes

* BIM guia completo
* Análise do Power BI como ferramenta de gerenciamento
* Live Power BI para construção
* Vídeo como praticar

## Problema identificado na resposta

A resposta apresentou diversas possibilidades de integração entre BIM e BI, porém algumas aplicações foram apresentadas de forma ampla, sem distinguir claramente quais funcionalidades pertencem ao BIM e quais análises são efetivamente realizadas pelo BI.

Também foi necessário aprofundar como os dados provenientes do BIM poderiam ser transformados em indicadores e informações gerenciais dentro de uma solução de BI.

## Variação do prompt

> Aprofunde a relação entre BIM e Business Intelligence na Construção Civil, diferenciando claramente o papel de cada tecnologia.
>
> Explique quais informações podem ser originadas ou estruturadas em um modelo BIM e quais etapas seriam necessárias para que esses dados fossem utilizados em uma solução de BI.
>
> Mostre como os dados provenientes do BIM poderiam ser transformados em indicadores, análises e informações gerenciais relacionadas a custos, planejamento, quantitativos, produtividade e execução da obra.
>
> Diferencie também funcionalidades próprias do BIM, como modelagem e detecção de conflitos, das análises que podem ser potencializadas pelo BI. Utilize exemplos práticos de uma obra para demonstrar essa integração.

## Nova resposta

A relação entre Building Information Modeling (BIM) e Business Intelligence (BI) na Construção Civil é sinérgica: o BIM é o grande gerador de dados técnicos e espaciais qualificados, enquanto o BI é a ferramenta que processa, integra e transforma esses dados em insights estratégicos para a gestão.

Abaixo, aprofundo essa integração, detalhando os papéis de cada tecnologia, o fluxo de dados e as análises gerenciais resultantes.

### 1. Diferenciação de Papéis: BIM vs. BI

* **Papel do BIM (Building Information Modeling):** É uma metodologia de trabalho baseada em modelos digitais inteligentes que servem como uma base de dados completa da edificação. O foco do BIM está na criação, coordenação e gestão da informação técnica (geometria, materiais, cronograma 4D e custos 5D) ao longo de todo o ciclo de vida da obra.
* **Papel do BI (Business Intelligence):** É um conjunto de processos e ferramentas (como o Power BI) que coleta dados de diversas fontes (incluindo o BIM), trata essas informações e as exibe em dashboards interativos. O foco do BI é o suporte à tomada de decisão rápida, permitindo analisar tendências, identificar desvios e comparar desempenhos.

### 2. Informações Originadas no Modelo BIM

Um modelo BIM bem estruturado pode originar uma vasta gama de dados que servirão como "combustível" para o BI:

* **Quantitativos Precisos:** Volumes de concreto, áreas de revestimento, contagem de peças (ex: blocos, esquadrias) e pesos de armação.
* **Especificações Técnicas:** Propriedades físicas dos materiais, espessuras e camadas de componentes.
* **Dados Temporais (4D):** Sequenciamento de atividades e prazos vinculados diretamente aos objetos do modelo.
* **Dados Financeiros (5D):** Orçamentação detalhada vinculada aos quantitativos do projeto.

### 3. Etapas para Integração BIM → BI

Para que os dados do BIM sejam úteis em uma solução de BI, eles devem passar por um fluxo de tratamento:

### 4. Extração

Os dados são exportados do software BIM (como Revit ou Archicad) em formatos estruturados como Excel (.xlsx), CSV ou via conexão direta por API.

### 5. ETL (Extração, Transformação e Carga)

Utiliza-se o Power Query para limpar os dados brutos, remover colunas desnecessárias e padronizar nomenclaturas.

### 6. Modelagem

As tabelas do BIM são conectadas a outras fontes (como dados reais de campo ou ERP) usando esquemas como o Star Schema, criando relações entre "fato" (o que ocorreu) e "dimensão" (contexto).

### 7. Criação de Medidas (DAX)

Aplicam-se fórmulas para calcular indicadores específicos, como produtividade ou desvios orçamentários.

### 8. Transformação de Dados em Informação Gerencial

A integração permite análises que antes seriam manuais e lentas:

* **Custos:** O BI pode criar um Treemap ou Curva ABC interativa. Se o gestor clica no pacote de "Estrutura" no dashboard, o gráfico de dispersão mostra instantaneamente quais itens (lajes, vigas ou pilares) são os mais onerosos.
* **Planejamento e Execução:** Comparação entre o cronograma 4D e o progresso real coletado em campo. O BI destaca visualmente (ex: em cores) quais tarefas estão com início ou término atrasado.
* **Quantitativos e Suprimentos:** Controle de recebimento de materiais. O dashboard compara o quantitativo extraído do BIM com as notas fiscais lançadas. É possível ver, por exemplo, que o projeto previa 8.172 blocos e apenas 2.285 foram entregues até o momento.
* **Produtividade:** Cruzamento das áreas (m²) do modelo BIM com o histograma de mão de obra (horas) para calcular indicadores como m² de alvenaria/pedreiro/dia, permitindo comparar o desempenho de diferentes equipes.

### 9. BIM Nativo vs. BI Potencializado

É crucial diferenciar o que cada tecnologia faz sozinha e como se complementam:

* **Funcionalidades Próprias do BIM:** Visualização 3D, simulação de eficiência energética (6D), gestão de manutenção (7D) e Clash Detection (detecção automática de interferências entre arquitetura, estrutura e instalações ainda na fase de projeto).
* **Análises Potencializadas pelo BI:** Análise de tendência financeira (Curva S), monitoramento em tempo real via dispositivos móveis, simulações de cenários de custos ("E se o preço do aço subir 20%?") e benchmarking entre múltiplas obras da construtora.

### Exemplo Prático de Integração

Imagine uma obra de um edifício.

No BIM, o engenheiro identifica um conflito (clash) entre uma viga e uma tubulação e o resolve antes de construir.

Simultaneamente, os quantitativos atualizados desse modelo são enviados ao Power BI.

No canteiro, o apontador registra que a equipe de alvenaria produziu menos que o planejado em uma semana.

O BI cruza esse dado com a área total de alvenaria do modelo BIM e gera um alerta visual em vermelho no dashboard do gestor, mostrando que, naquele ritmo, a entrega do marco contratual da fachada atrasará 15 dias e custará 5% a mais do que o previsto na Curva S.

## Fontes utilizadas

* BIM guia completo
* TCC aplicações
* Power BI Fundamentals
* Aplicações BI e Analytics
* Análise do Power BI como ferramenta de gerenciamento
* Live Power BI para construção
* Dashboard com storytelling

---

# 05. BI aplicado ao controle de custos

## Prompt inicial

> Como o Business Intelligence pode contribuir para o controle de custos de uma obra? Analise quais dados deveriam ser acompanhados, quais informações podem ser extraídas desses dados e como essas informações poderiam apoiar a identificação de desvios e a tomada de decisão.

## Resposta obtida

O Business Intelligence (BI) contribui para o controle de custos de uma obra ao transformar dados fragmentados em uma visão estratégica e integrada, permitindo que gestores identifiquem falhas financeiras em tempo real e tomem decisões baseadas em fatos, e não apenas em intuição.

A implementação de soluções como o Power BI elimina a dependência de planilhas isoladas e manuais, que muitas vezes apresentam dados inconsistentes e dificultam a percepção de gargalos orçamentários.

Abaixo, analiso os dados necessários, as informações extraídas e o apoio à decisão:

### 1. Dados que devem ser acompanhados

Para um controle de custos eficaz, o BI deve processar dados provenientes de diferentes setores:

* **Planejamento e Orçamentação:** Orçamento analítico (custos diretos, indiretos e BDI), planilha de quantidades de serviços e insumos, e o cronograma físico-financeiro.
* **Execução Financeira:** Notas fiscais lançadas no ERP, medições de serviços executados e pagamentos a empreiteiros.
* **Recursos e Insumos:** Histogramas de mão de obra, registros de consumo de materiais e utilização de equipamentos.
* **Indicadores de Mercado:** Índices de correção monetária, como o INCC, para ajustar o poder de compra do orçamento ao longo do tempo.

### 2. Informações extraídas desses dados

A integração dessas fontes em um dashboard permite extrair indicadores críticos para a saúde financeira:

* **Análise "Previsto vs. Realizado":** Comparação imediata entre o custo orçado e o desembolso real, destacando o saldo (positivo ou negativo) de cada etapa da obra.
* **Curva S Financeira:** Gráfico que mostra a evolução do gasto acumulado ao longo do tempo, permitindo visualizar tendências de estouro orçamentário meses antes de elas se tornarem críticas.
* **Curva ABC Interativa:** Identificação visual (através de recursos como o Treemap) dos itens que representam o maior peso financeiro (Classe A), permitindo focar o controle onde o impacto é maior.
* **Custo Unitário e Parâmetros:** Extração do custo real por metro quadrado (m²) ou por unidade de serviço (ex: R$/m³ de concreto), servindo de base para comparativos entre diferentes obras.

### 3. Apoio à identificação de desvios e tomada de decisão

O valor real do BI reside na agilidade de resposta que ele proporciona ao gestor:

* **Alertas Visuais de Desvios:** O uso de cores (como vermelho para etapas que superaram a meta) permite que o engenheiro identifique instantaneamente qual serviço está gerando prejuízo.
* **Análise de Causa Raiz:** Ao notar um desvio na Curva S, o gestor pode realizar um drill-down (detalhamento) para entender se o custo subiu devido ao aumento de preços de insumos (inflação) ou por baixa produtividade das equipes em campo.
* **Negociações Estratégicas:** Com a Curva ABC mapeada, a gestão pode priorizar negociações com fornecedores dos itens que mais impactam o orçamento, protegendo a margem de lucro da empresa.
* **Simulação e Replanejamento:** A automação permite simular cenários e introduzir novas "linhas de base" (replanejamentos) de forma rápida, ajustando a alocação de recursos e equipes para recuperar o desempenho financeiro.
* **Mobilidade no Canteiro:** O acesso aos dados via dispositivos móveis permite que decisões de corte de gastos ou realocação de frentes de serviço sejam tomadas "aqui e agora", diretamente no local da execução.

Em suma, o Business Intelligence garante a confiabilidade da informação, pois dados integrados e limpos (processo de ETL) evitam decisões equivocadas baseadas em relatórios corrompidos ou obsoletos.

## Fontes

* AcadBI
* Curso de gerenciamento de obras
* Tecnologia como apoio ao planejamento
* TCC aplicação
* Live Power BI
* Aplicação BI e Analytics

## Problema identificado na resposta

A resposta apresentou diversos indicadores e recursos que podem ser utilizados no controle de custos, porém não aprofundou suficientemente a relação entre o desvio identificado e sua causa.

O dashboard consegue mostrar que existe uma diferença entre o custo previsto e o realizado, mas é necessário compreender como os dados podem ser cruzados para investigar a origem desse desvio e apoiar uma decisão corretiva.

## Variação do prompt

> Aprofunde a análise do uso de Business Intelligence no controle de custos de uma obra, considerando não apenas a identificação de desvios entre o previsto e o realizado, mas também a investigação de suas possíveis causas.
>
> Considere um cenário em que determinada etapa da obra apresente um custo superior ao previsto. Explique como o BI poderia cruzar diferentes tipos de dados — como orçamento, quantitativos, preços de insumos, medições, produtividade da mão de obra, consumo de materiais e cronograma — para identificar os fatores que contribuíram para esse desvio.
>
> A partir dessa análise, explique como as informações obtidas poderiam apoiar diferentes decisões de gestão, como negociação com fornecedores, alteração de métodos executivos, redistribuição de recursos ou replanejamento da obra.

## Nova resposta

A aplicação de Business Intelligence (BI) no controle de custos de uma obra vai além do simples monitoramento do "Previsto vs. Realizado".

O valor estratégico do BI reside na sua capacidade de integrar e cruzar dados heterogêneos para identificar a causa raiz das variações financeiras, permitindo que o gestor deixe de ser um observador de prejuízos e passe a atuar preventivamente.

Abaixo, detalho como o BI investiga desvios e apoia a gestão em um cenário de custos excedentes.

### 1. Identificação e Investigação de Desvios (Causa Raiz)

Em um cenário onde uma etapa da obra (como a estrutura) apresenta custo superior ao previsto, o BI permite uma investigação multinível através de recursos como o drill-down (detalhamento progressivo) e o cruzamento das seguintes fontes:

* **Preços de Insumos vs. Orçamento e Inflação:** O BI cruza as notas fiscais lançadas no ERP com os preços unitários do orçamento inicial. Ao aplicar a correção pelo INCC (Índice Nacional de Custo de Construção), o sistema identifica se o estouro é fruto de uma inflação de mercado acima do esperado ou de falhas no processo de compras e negociação.
* **Quantitativos vs. Consumo Real:** Cruzando o quantitativo extraído de modelos BIM ou projetos com os registros de recebimento de materiais no canteiro, o BI aponta discrepâncias. Se a obra recebeu mais concreto do que o projetado, o sistema sinaliza desperdícios operacionais, falhas na execução ou perdas por estocagem inadequada.
* **Produtividade da Mão de Obra e Histogramas:** O BI integra os dados de medição física com o histograma de pessoal (horas trabalhadas). Se o custo da mão de obra subiu sem o respectivo avanço físico, o sistema calcula índices de produtividade (ex: m² de alvenaria por pedreiro/dia) e os compara com parâmetros históricos, revelando se a equipe está subdimensionada ou operando com baixa performance.
* **Cronograma e Prazos:** Atrasos em tarefas críticas impactam custos indiretos e de operacionalidade. O BI permite visualizar se a mobilização tardia de recursos ou equipamentos ociosos gerou desvios financeiros que não estavam visíveis em relatórios de custo isolados.

### 2. Apoio à Tomada de Decisão de Gestão

A análise visual e integrada desses dados transforma a percepção do gestor, fundamentando decisões rápidas para mitigar danos e recuperar o lucro previsto:

* **Negociação com Fornecedores:** Com o auxílio da Curva ABC Interativa, o gestor foca seus esforços de negociação nos itens de "Classe A" (que representam a maior fatia do custo). Se o BI mostra que o preço do aço é o principal ofensor, a construtora pode buscar compras em escala ou antecipação de pedidos para proteger o orçamento contra novas altas.
* **Alteração de Métodos Executivos:** Se os indicadores de produtividade demonstram que o método atual é ineficiente ou gera muito desperdício, o BI fornece subsídios para simular e adotar novas metodologias construtivas (como o uso de pré-moldados ou alteração de fornecedores de sistemas fôrmas) antes que o erro se propague para as próximas etapas.
* **Redistribuição de Recursos:** Através da análise dos histogramas, o gestor pode identificar equipes ociosas em frentes de serviço secundárias e realocar esses profissionais para reforçar o caminho crítico da obra, evitando multas contratuais por atraso.
* **Replanejamento da Obra:** Quando os desvios são identificados como irreversíveis na linha de base original, o BI facilita a criação de um replanejamento (nova linha de base). Isso permite ajustar o fluxo de caixa, readequar estratégias de fornecimento e alinhar as expectativas com os stakeholders e clientes de forma transparente e baseada em dados.

Em resumo, o BI na construção civil atua como um sistema de suporte à decisão que unifica a "única fonte da verdade", garantindo que as ações corretivas sejam tomadas no "aqui e agora" para proteger a saúde financeira e a rentabilidade do empreendimento.

## Fontes utilizadas

* AcadBI
* Curso de gerenciamento de obras
* Tecnologia como apoio ao planejamento
* TCC aplicação
* Live Power BI
* Aplicação BI e Analytics

---

# 06. ETL aplicado à realidade de uma construtora

## Prompt inicial

> Como o processo de ETL poderia ser aplicado a dados provenientes de diferentes fontes utilizadas por uma construtora?

## Resposta obtida

O processo de ETL (Extração, Transformação e Carga) é a espinha dorsal de uma solução de Business Intelligence para uma construtora, pois permite que dados fragmentados e em formatos distintos sejam convertidos em informações úteis e confiáveis.

Esse processo é comumente realizado através do Power Query, um editor interno que permite "esculpir" os dados brutos até que atinjam o formato desejado para análise.

Abaixo, detalho como cada etapa do ETL se aplica à realidade de uma construtora:

### 4. Extração (Extraction)

Nesta fase, o sistema de BI se conecta às diversas fontes de dados utilizadas no dia a dia da obra e do escritório.

Exemplos comuns incluem:

* **ERPs (como Sienge ou TOTVS):** Extração de dados financeiros, notas fiscais e medições via banco de dados SQL ou APIs.
* **Planilhas Excel e Arquivos CSV:** Utilizados para orçamentos analíticos, cronogramas de suprimentos e listas de presença.
* **Modelos BIM (Revit):** Extração de tabelas de quantitativos precisos diretamente do modelo 3D.
* **Arquivos PDF:** Extração de dados de planilhas orçamentárias de licitações públicas ou documentos de fornecedores que não estão em formato editável.
* **MS Project:** Dados de cronograma físico para monitoramento de prazos.

### 5. Transformação (Transformation)

Esta é a etapa mais crítica, onde as regras de negócio são aplicadas e as inconsistências são sanadas.

Segundo as fontes, os dados na construção civil raramente estão prontos para uso imediato.

As principais ações de transformação incluem:

* **Limpeza de Dados:** Remoção de colunas desnecessárias, linhas de totais que podem causar duplicidade na soma e tratamento de valores nulos.
* **Padronização de Nomenclatura:** Garantir que colunas como "Quantidade" ou "Preço Unitário" tenham nomes idênticos em diferentes fontes para permitir o reaproveitamento de dashboards.
* **Tratamento de Hierarquias (EAP):** Ajuste de códigos de estrutura analítica (ex: remover pontos de códigos como "1.1.2") para que o BI reconheça corretamente os níveis de serviço no orçamento.
* **Dinamização (Unpivot):** Transformar planilhas onde os meses estão em colunas separadas em uma estrutura de linhas, facilitando a criação de análises temporais e Curvas S.
* **Correção de Inconsistências:** Identificação e exclusão de erros de preenchimento manual no ERP, como corretores duplicados ou despesas lançadas em categorias erradas.

### 6. Carga (Load)

Após a limpeza e modelagem, os dados são carregados para o modelo de dados do Power BI.

* **Modelagem Star Schema:** Organização das tabelas em "Fatos" (eventos como vendas ou custos) e "Dimensões" (contextos como calendário, lista de obras ou fornecedores).
* **Criação de Tabelas Calendário:** Geração de uma tabela mestre de datas (geralmente via script na linguagem M) para conectar cronogramas de diferentes fontes em um único eixo temporal.
* **Aplicação de Medidas DAX:** Criação de fórmulas para cálculos complexos, como desvios orçamentários, produtividade por equipe e avanço físico acumulado.

Ao final desse ciclo, a construtora passa a ter uma "única fonte da verdade", garantindo que os relatórios reflitam fielmente a realidade do campo e apoiem decisões estratégicas rápidas.

## Fontes

* Aplicação BI e Analytics
* Dashboard com storytelling
* Power BI Fundamentals
* Análise do Power BI como ferramenta de gerenciamento
* Vídeo como praticar BI
* Curso gerenciamento

## Problema identificado na resposta

A resposta apresentou de forma detalhada as etapas de extração, transformação e carga, mas concentrou-se principalmente nas operações técnicas realizadas sobre os dados.

Faltou aprofundar os critérios utilizados para definir como os dados devem ser tratados quando existem divergências entre fontes, ausência de informações ou diferentes padrões de preenchimento.

## Variação do prompt

> Aprofunde a aplicação do processo de ETL em uma construtora considerando um cenário em que diferentes setores fornecem informações sobre uma mesma obra, mas os dados apresentam formatos, nomenclaturas, unidades de medida e valores diferentes entre si.
>
> Explique como o processo de ETL deve lidar com essas divergências e quais critérios podem ser utilizados para determinar a origem mais confiável de uma informação. Considere também situações em que existam dados duplicados, ausentes, inconsistentes ou incompatíveis entre diferentes fontes.
>
> Mostre como essas decisões de tratamento influenciam a confiabilidade dos indicadores e dashboards produzidos posteriormente no Power BI.

## Nova resposta

O processo de ETL (Extração, Transformação e Carga) em uma construtora é o que transforma o cenário de "obtenção caótica da informação" em um sistema de suporte à decisão confiável.

Em um ambiente onde diferentes setores (como engenharia, financeiro e suprimentos) fornecem dados sobre a mesma obra, o ETL atua como um filtro que padroniza divergências e garante a integridade da análise.

### 1. Tratamento de Divergências no ETL

Quando os dados chegam com formatos, nomenclaturas e unidades distintas, o Power Query (editor do Power BI) funciona como um "escultor" para moldar essa matéria-prima bruta:

* **Padronização de Nomenclatura e Formato:** Se o setor de suprimentos usa "Qtd" e o planejamento usa "Quantidade", o ETL deve renomear essas colunas para um padrão único. Isso é vital para que as fórmulas DAX (medidas) consigam encontrar os dados e realizar cálculos sem gerar erros.
* **Ajuste de Unidades de Medida e Tipos de Dados:** O Power BI identifica automaticamente tipos de dados (como texto ou número inteiro), mas cabe ao gestor configurar o tratamento para que unidades incompatíveis sejam convertidas antes da análise. Por exemplo, garantir que valores financeiros em diferentes planilhas estejam todos em formato decimal e na mesma moeda.
* **Tratamento de Hierarquias (EAP):** A divergência mais crítica em obras costuma ser a Estrutura Analítica do Projeto (EAP). Enquanto um setor pode detalhar a obra em 5 níveis, outro pode usar apenas 2. O processo de ETL deve criar códigos de hierarquia únicos para permitir o cruzamento correto entre orçamento, cronograma e medições.

### 2. Critérios de Confiabilidade e Gestão de Dados Problemáticos

Para determinar a origem mais confiável e tratar inconsistências, o BI adota os seguintes critérios:

* **Unificação em Repositório Único:** O objetivo fundamental é centralizar os dados em um Data Warehouse (DW) ou Data Mart, criando uma "única fonte da verdade" e eliminando discussões em reuniões sobre qual planilha está correta.
* **Tratamento de Inconsistências e Duplicidade:** Através de filtros e recursos visuais no Power Query, é possível localizar erros de preenchimento manual no ERP, como corretores duplicados ou despesas lançadas em categorias erradas. O comando de "Remover Duplicadas" é essencial para evitar a inflação artificial de custos.
* **Dados Ausentes ou Nulos:** Durante a limpeza, linhas nulas ou totais de planilhas (que causariam duplicidade na soma final) devem ser filtradas e removidas para não corromper os indicadores.

### 3. Influência na Confiabilidade dos Dashboards

As decisões tomadas durante o ETL impactam diretamente a qualidade da gestão:

* **Garantia da "Fonte da Verdade":** Se os dados de origem estiverem corrompidos ou não condizerem com a realidade, o Power BI não poderá corrigi-los automaticamente; a correção deve ser feita na fonte ou durante o tratamento. "Dados errados levam a relatórios errados", o que pode resultar em decisões estratégicas equivocadas.
* **Estabilidade das Medidas:** Se o tratamento do ETL não for rigoroso, qualquer mudança mínima na fonte de dados (como renomear uma aba de Excel) fará com que os indicadores do dashboard "quebrem" (fiquem em vermelho), paralisando o acompanhamento da obra.
* **Narrativa de Gestão (Storytelling):** Dados bem tratados permitem a criação de dashboards claros que seguem padrões lógicos de leitura (como o padrão em Z), facilitando a identificação imediata de desvios na Curva S ou na Curva ABC.

Em suma, um processo de ETL bem executado permite que o engenheiro saia da função de "conferidor de planilhas" e passe a atuar como um gestor que analisa tendências e toma medidas preventivas "aqui e agora" para garantir o lucro e o prazo do empreendimento.

## Fontes

* AcadBI
* O que é Data Warehouse
* Aplicação BI e Analytics
* Live
* Excel intermediário
* Dashboard com storytelling
* Power BI Fundamentals
* Vídeo como praticar BI
* Curso gerenciamento
