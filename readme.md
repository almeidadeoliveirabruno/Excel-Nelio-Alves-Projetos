# Projeto 1: Controle Financeiro e Fluxo de Caixa

Este workbook Excel consolida o controle de entradas, saídas e a posição financeira de uma empresa/projeto, com dashboards atualizados.

### 🗂️ Estrutura de Planilhas

- **Início**  
  Página de abertura com instruções e visão geral do modelo.

- **Matriz**  
  Base de dados mestra que reúne todas as transações financeiras (entradas e saídas).

- **RegistroEntradas** / **RegistroSaídas**  
  Formulários para lançar manualmente cada novo recebimento ou pagamento.

- **PCEntradaN1**, **PCEntradaN2** / **PCSaídasN1**, **PCSaídasN2**  
  Planilhas de controle por nível de detalhamento das entradas e saídas.

- **FluxoCaixaConsolidado**  
  Consolida todas as entradas e saídas por período, gera saldo acumulado.

- **DetalheReceita** / **DetalheDespesa**  
  Análises detalhadas por categoria de receita e despesa.

- **ContasPagar** / **ContasReceber** / **ContasReceberVencidas**  
  Controle de vencimentos futuros e pendências.

- **DashBoardFinanceiroAtual** / **DashBoardFinanceiroAnual** / **DashBoardFinanceiroIAnualD** / **DashBoardAtualID**  
  Vários painéis com gráficos de linha, coluna e indicadores-chave (KPIs) de performance financeira.

### 🎯 Objetivos

1. Registrar e categorizar todas as transações financeiras.  
2. Monitorar o saldo de caixa dia a dia.  
3. Identificar variações mensais e anuais de receitas e despesas.  
4. Acompanhar contas a pagar e receber, incluindo inadimplência.  
5. Gerar relatórios e dashboards automáticos para tomada de decisão.

### 📌 Principais Recursos do Excel Usados

- **Tabelas estruturadas** para facilitar filtros e referências dinâmicas.  
- **Tabelas Dinâmicas** e **Gráficos Dinâmicos** para análise ágil.  
- **Formatação Condicional** para alertas (saldo negativo, contas vencidas).  
- **Validação de Dados** em formulário de lançamentos.

### 🚀 Como Usar

1. Preencha novas transações em **RegistroEntradas** e **RegistroSaídas**.  
2. Abra **FluxoCaixaConsolidado** para ver o saldo atualizado.  
3. Navegue nos dashboards para obter insights visuais.  
4. Atualize a seção de filtros (datas, categorias) para recortes específicos.


# Projeto 2: Perfil do Cliente – Dashboard de Vendas e Segmentação

Este workbook Excel agrupa informações de clientes e vendas, oferecendo painéis para analisar comportamento de compra e perfis.

### 🗂️ Estrutura de Planilhas

- **TabClientes**  
  Cadastro mestre de clientes com atributos (nome, idade, gênero, região, etc.).

- **TabVendas**  
  Registro de todas as transações de venda (cliente, data, produto, valor, canal).

- **Análise**  
  Planilha de métricas e indicadores (ticket médio, frequência de compra, CLV).

- **Painel**  
  Dashboard interativo com slicers e gráficos (barras, pizza, ranking de clientes).

### 🎯 Objetivos

1. Consolidar dados de clientes e vendas para análises rápidas.  
2. Calcular métricas como ticket médio, taxa de recompra e valor de vida do cliente.  
3. Segmentar clientes por perfil e comportamento.  
4. Apresentar visualizações claras para suporte a marketing e vendas.

### 📌 Principais Recursos do Excel Usados

- **Tabelas Dinâmicas** para cruzamento de TabClientes × TabVendas.  
- **Segmentação de Dados (Slicers)** para filtragem interativa.  
- **Gráficos Dinâmicos** vinculados às tabelas.  
- **Fórmulas** como `SOMASES`, `CONT.VALORES`, `MÉDIASE` para cálculos diretos.  
- **Formatação Condicional** para destacar top clientes ou categorias de risco.

### 🚀 Como Usar

1. Atualize **TabClientes** sempre que incluir novo cliente.  
2. Lance cada venda em **TabVendas**, preenchendo todos os campos.  
3. Na aba **Análise**, veja as métricas recalcularem automaticamente.  
4. No **Painel**, use os slicers para explorar segmentos e períodos específicos.

# Projeto 3: Ativo – Gestão de Carteira de Investimentos

Workbook Excel para controle de aportes, proventos e performance de carteira de ações e fundos imobiliários.

### 🗂️ Estrutura de Planilhas

- **TbAtivos**  
  Listagem de ativos disponíveis (código, tipo, setor).

- **TbAportes**  
  Registro de aportes (data, ativo, quantidade, preço).

- **TbProventos**  
  Histórico de proventos (dividendos, juros, rendimentos) por ativo.

- **ReCarteira**, **ReCarteiraAções**, **ReCarteiraFII**  
  Cálculo de posição atual da carteira (quantidade, valor de mercado, custo médio).

- **ReAportes**, **ReProventos**  
  Resumos de aportes feitos e proventos recebidos no período.

- **DashBoard** / **DashBoardAux**  
  Painel principal com gráficos de participação por ativo, rentabilidade, aportes x proventos.

### 🎯 Objetivos

1. Registrar e acompanhar aportes e proventos.  
2. Calcular custo médio, valor de mercado e rentabilidade.  
3. Visualizar composição da carteira e exposição por classe.  
4. Monitorar recebimentos de proventos mês a mês.

### 📌 Principais Recursos do Excel Usados

- **Tabelas Dinâmicas** para sumarização de aportes e proventos.  
- **Gráficos Dinâmicos** e **Gráficos de Rosca** para composição de carteira.  
- **Fórmulas** como `MÉDIASE`, `SOMARPRODUTO`, `PROCV` para cálculos de indicadores.  
- **Dashboard interativo** com segmentação por datas e classe de ativo.

### 🚀 Como Usar

1. Lance novos aportes em **TbAportes** e proventos em **TbProventos**.  
2. Verifique em **ReCarteira** sua posição atual.  
3. Consulte **DashBoard** para indicadores de performance e alocação.  
4. Ajuste filtros de período e tipo de ativo conforme necessidade.

