***DESAFIO DE CURSO DIO - Projeto de Excel ✒***         
****DASHBOARD DE VENDAS****

## 📄 Descrição


Este projeto foi desenvolvido com o intuito de criar um dashboard de vendas, ajudando analistas a entender os índices de inscrição de produtos do XBOX (dados fictícios, apenas para exemplificar), e aplicar conceitos de Excel de criação de *Dashboards* e transformação de dados em informações claras e uteis para tomada de descisão.  

Nesta planilha temos dois gráficos, base de dados, tabelas de cálculos e também *assets* que fazem parte para a criação do Dashboard.   
Valew ressaltar o contexto que foi entregue neste projeto:   
> Alguém da gerência do departamento de vendas da "XBOX" pediu a criação de um *Dashboard* sobre o "XBOX GAME PASS Subscription Sales" ou "Vendas de assinaturas do XBOX GAME PASS", e que neste Dashboard precisa responder quatro pontos:
> Qual faturamento TOTAL DE VENDAS de PLANOS ANUAIS (contendo todas as assinaturas agregadas);
> Qual faturamento TOTAL DE VENDAS de PLANOS ANUAIS, separados por "Auto renovação" ou "Não é Auto Renovação";
> Qual o Total de Vendas de assinaturas do "EA PLAY Season Pass";
> Qual é o TOTAL DE ASSINATURAS do "MINECRAFT Season Pass".   

> Precisa conter gráficos dínamicos e interativos, que possa permitir uma análise eficaz do desempenho de vendas e para a tomada de decisões baseadas em dados. 

Este projeto pode ser usado como base para futuras expansões e personalizações. 


## ⚙ Estrutura


Neste projeto, foi utilizado o **Método ABCDE** de organização, compartilhado pelo professor do curso. Na qual separa as tarefas de criação de projetos/Dashboards para melhor eficiência na criação e organização.   
Os seguintes painéis seria:
1. ASSETS: Recursos essenciais e complementares que serão utilizados no projeto, isso inclui imagens, vídeos, gifs e paletas de cores;
2. BASES: Base de dados necessários para que a análise seja feita sobre ele;
3. CÁLCULOS: Campo que processa a base de dados para transformar em informações;

5. *DASHBOARD*: Painel visual para análises claras. 

Para os usuários que irão trabalhar os dados principais de vendas, todas as funcionalidades estão no painel de ***DASHBOARD***.
(Imagem 1)   

## 🧱 Passo a Passo


### ASSETS


Neste primeiro painel é onde separamos os recursos que iremos utilizar em todo o projeto, especialmente para os painéis que o usuário/analista irá trabalhar. Tais recursos seria: 

#### Paleta de cores 
  1. $\color{#9BC848}{\textsf{Xbox Color 1}}$: #9BC848;
  2. $\color{#22C55E}{\textsf{Xbox Color 2}}$: #22C55E;
  3. $\color{#2AE6B1}{\textsf{Menus 1}}$: #2AE6B1;
  4. $\color{#5BF6A8}{\textsf{Menus 2}}$: #5BF6A8.

#### Logos 
  1. XBOX: Logo do segmento de games da empresa; 
  2. XBOX ONE: Produto da empresa, opicional; 
  3. EA Play: Assinatura adicional e opicional do Game Pass para jogos da *Eletronic Arts*;
  4. Minecraft: Logo do jogo sandbox, que nele contém um adicional do Game Pass chamado "*Minecraft Season Pass Price*";  

#### Ícones
  1. Usuários: Ícone de pessoa a depender do usuário/analista/gerente;
  2. Lupa: Ícone de Pesquisa/Filtragem;


### Bases


No painel de **BASES** 








> OBS: Não é um valor que precisa seguir a risca. 
Se sentir que precisa economizar mais ou investir mais do que a sugestão, na **Etapa 2** você pode inserir um novo valor que irá confirmar o quanto em R$ será separado mensalmente e investido.   

É também possível alterar o tipo de **VISUALIZAÇÃO** no painel ao lado. Ao clicar na célula, irá aparecer duas opções.   
1. "Informar avisos" adiciona textos que pode ajudar o usuário a entender os campos editáveis, útil para pessoas que não estão familiarizados e/ou esclarescer o que precisa inserir. 
2. "Simples" é a visualização limpa e padrão, útil para quem está mais familiarizado no uso de simuladores.


### Etapa 2: Investimento mensal

Nesta etapa, o usuário pode fazer as confirmações do seu investimento no painel **INVESTIMENTO MENSAL**: 
1. *Aporte mensal*, o quanto vai investir mensalmente; 
2. *Investimento Anual* é por quantos anos o usuário irá investir;
3. *Taxa de rendimento mensal em %*, normalmente é ≈ 1,08%.
  Após inserir esses dados, e também o *Rendimento Carteira* em **INICIALIZAÇÃO**, será gerado o Patrimonio Acumulado e os Dividendos Mensais. Você pode alterar os dados acima para ver novos resultados. 


### Etapa 3: Entender outros Cenários

Nesta etapa, temos a tabela não-editável **CENÁRIOS**:
- Ela serve para o usuário visualizar diferentes retornos de investimentos em diferentes anos; 
- Esses cálculos são parecidos com o painel de **INVESTIMENTO MENSAL** e depende dos dados inseridos. 


### Etapa 4: Identificando seu Perfíl de Investidor
Nesta etapa, o usuário pode inserir no painel **PERFIL DE INVESTIMENTO** o seu estilo de investimento em uma lista com três opções: 

1. Conservador: Investidor(a) que prioriza segurança e estabilidade. Estes tem baixa tolerância à oscilações ou que estão começando a investir.
2. Moderado: Investidor(a) que prioriza opções equilibradas e diversificadas. Estes tem tolerância moderada à oscilações e que tem mais experiência no mercado.
3. Agressivo: Investidor(a) que prioriza oportunidades de alto riscos. Estes tem alta tolerância à oscilações e que se preparam para enfretar perdas temporárias.
Depois de escolher uma das opções, será gerado cálculos na tabela abaixo. Essa tabela divide o *Aporte Mensal* em 6 categorias, cada uma com uma sugestão de investimendo ideal a depender de cada tipo de Perfil.
Por exemplo: Para um investidor Conservador, será priorizado investir o dinheiro do *Aporte Mensal* em Fundos Imobiliários (FIIs) de "Tijolo", enquanto para um investidor Agressivo terá mais prioridade para os de Papel.


## 📈 Gráficos

Temos dois gráficos nesta planilha:
1. Gráfico de Colunas - Linha do Tempo do Investimento - Vinculada diretamente no painel **CENÁRIOS**, representa os dados de *Retorno em Anos* e o *Patrimônio Acumulado*. 
2. Gráfico de Pizza   - Sugestão de investimento por Tipos de FII's - Vinculada diretamente a tabela de Tipos de FII, contendo o resultado do percentual de cada categoria.

## 🛠 Considerações Finais

Também tem uma planilha ****"CHAVE CONFIG"**** que são dados para alimentar o painel **PERFIL DE INVESTIMENTO**

Gostaria de agradecer ao professor da DIO, Felipe Aguiar, pelas aulas fantásticas e explicações sobre o tema.
Futuramente posso fazer um ajuste ou outro no arquivo e em suas funcionalidades, caso necessário.

  Microsoft Excel.
  Fórmulas usadas: SE, E, VF, PROCV.
  Formatação Condicional e Gráfico de Pizza e Colunas.

## 📁 Planilha



## 📥 Download da Planilha do Projeto
