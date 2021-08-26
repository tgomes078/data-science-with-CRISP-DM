# O modelo de referência CRISP-DM

O modelo de processo atual para mineração de dados fornece uma visão geral do ciclo de vida de um projeto de mineração de dados. Ele contém as fases de um projeto, suas respectivas tarefas e os relacionamentos entre essas tarefas. Nesse nível de descrição, não é possível identificar todos os relacionamentos. Poderiam existir relacionamentos entre quaisquer tarefas de mineração de dados, dependendo dos objetivos, do plano de fundo e do interesse do usuário - e mais importante - nos dados.

![Figura_1_-_Fases_do_modelo_de_referência_CRISP-DM](../image/Figura_1_-_Fases_do_modelo_de_referência_CRISP-DM.png)

*Figura 1 - Fases do modelo de referência CRISP-DM*

O ciclo de vida de um projeto de mineração de dados consiste em seis fases, mostradas na *Figura 1*. A sequência das fases não é rígida. É sempre necessário ir e voltar entre diferentes fases. O resultado de cada fase determina qual fase, ou tarefa específica de uma fase, deve ser executada a seguir. As setas indicam as dependências mais importantes e frequentes entre as fases.

O círculo externo na *Figura 1* simboliza a natureza cíclica da própria mineração de dados. A mineração de dados não termina quando uma solução é implantada. As lições aprendidas durante o processo e com a solução implantada podem desencadear novas questões comerciais, muitas vezes mais focadas. Os processos subsequentes de mineração de dados se beneficiarão das experiências dos anteriores. A seguir, descrevemos brevemente cada fase:

## 1. Entendimento do negócio
Essa fase inicial concentra-se no entendimento dos objetivos e requisitos do projeto sob uma perspectiva de negócios e, em seguida, na conversão desse conhecimento em uma definição de problema de mineração de dados e em um plano preliminar desenvolvido para atingir os objetivos.

## 2. Compreensão dos dados
A fase de entendimento dos dados começa com a coleta inicial de dados e prossegue com as atividades que permitem familiarizar-se com os dados, identificar problemas de qualidade dos dados, descobrir as primeiras idéias sobre os dados e / ou detectar subconjuntos interessantes para formar hipóteses sobre informações ocultas.

## 3. Preparação de dados
A fase de preparação de dados abrange todas as atividades necessárias para construir o conjunto de dados final [dados que serão alimentados na (s) ferramenta (s) de modelagem] a partir dos dados brutos iniciais. É provável que as tarefas de preparação de dados sejam executadas várias vezes e não em nenhuma ordem prescrita. As tarefas incluem seleção de tabela, registro e atributo, além de transformação e limpeza de dados para ferramentas de modelagem.

## 4. Modelagem
Nesta fase, várias técnicas de modelagem são selecionadas e aplicadas, e seus parâmetros são calibrados para valores ideais. Normalmente, existem várias técnicas para o mesmo tipo de problema de mineração de dados. Algumas técnicas têm requisitos específicos na forma de dados. Portanto, muitas vezes é necessário voltar à fase de preparação de dados.

## 5. Avaliação
Nesta fase do projeto, você construiu um modelo (ou modelos) que parece ter alta qualidade da perspectiva da análise de dados. Antes de prosseguir para a implantação final do modelo, é importante avaliá-lo completamente e revisar as etapas executadas para criá-lo, para garantir que o modelo atinja adequadamente os objetivos de negócios. Um objetivo principal é determinar se há algum problema comercial importante que não foi suficientemente considerado. No final desta fase, uma decisão sobre o uso dos resultados da mineração de dados deve ser alcançada.

## 6. Implantação
A criação do modelo geralmente não é o fim do projeto. Mesmo que o objetivo do modelo seja aumentar o conhecimento dos dados, o conhecimento adquirido precisará ser organizado e apresentado de forma que o cliente possa usá-lo. Geralmente envolve a aplicação de modelos "ativos" nos processos de tomada de decisão de uma organização - por exemplo, personalização em tempo real de páginas da Web ou pontuação repetida de bancos de dados de marketing. Dependendo dos requisitos, a fase de implantação pode ser tão simples quanto gerar um relatório ou tão complexa quanto implementar um processo de mineração de dados repetível em toda a empresa. Em muitos casos, é o cliente, não o analista de dados, quem executa as etapas de implantação. No entanto, mesmo que o analista realize o esforço de implantação, é importante que o cliente entenda de antemão quais ações precisam ser executadas para realmente fazer uso dos modelos criados.

![Figura_2_-_Tarefas_genéricas__negrito__e_saídas__itálico__do_modelo_de_referência_CRISP-DM](../image/Figura_2_-_Tarefas_genéricas__negrito__e_saídas__itálico__do_modelo_de_referência_CRISP-DM.png)

*Figura 2 - Tarefas genéricas (negrito) e saídas (itálico) do modelo de referência CRISP-DM*

A Figura 2 apresenta um resumo das fases acompanhadas de tarefas genéricas (**negrito**) e saídas (*itálico*). Nas seções a seguir, descrevemos cada tarefa genérica e suas saídas com mais detalhes. Concentramos nossa atenção em visões gerais de tarefas e resumos de resultados.

# Tarefas genéricas
## 1. Entendimento do negócio
### 1.1. Determinar objetivos de negócios
#### Objetivo 
O primeiro objetivo do analista de dados é entender completamente, de uma perspectiva de negócios, o que o cliente realmente deseja realizar. Muitas vezes, o cliente tem muitos objetivos e restrições concorrentes que devem ser adequadamente equilibrados. O objetivo do analista é descobrir fatores importantes, no início, que podem influenciar o resultado do projeto. Uma possível conseqüência de negligenciar esta etapa é gastar muito esforço produzindo as respostas certas para as perguntas erradas.

Artefato   | Descrição 
:--------- | ------
1.1.1. Plano de fundo (background) | Registre as informações conhecidas sobre as situações negociais da organização  no início do projeto. 
1.1.2. Objetivos do negócio | Descreva o objetivo principal do cliente, de uma perspectiva comercial. Além do objetivo comercial principal, normalmente existem outras questões comerciais relacionadas que o cliente gostaria de abordar. **Por exemplo**, o objetivo principal dos negócios pode ser manter os clientes atuais, prevendo quando eles tendem a se mudar para um concorrente. Exemplos de perguntas comerciais relacionadas são "Como o canal principal usado (por exemplo, caixa eletrônico, visita a agências, Internet) afeta se os clientes ficam ou vão?" ou "As taxas de caixa eletrônico mais baixas reduzirão significativamente o número de clientes de alto valor que saem?"
1.1.3. Critérios de sucesso para o negócio | Descreva os critérios para um resultado bem-sucedido ou útil do projeto do ponto de vista comercial. Isso pode ser bastante específico e capaz de ser mensurado objetivamente, **por exemplo**, redução da rotatividade de clientes para um determinado nível ou pode ser geral e subjetivo, como *"fornecer informações úteis sobre os relacionamentos"* . Neste último caso, deve-se indicar quem faz o julgamento subjetivo.

### 1.2. Avaliar a situação
#### Objetivo
Essa tarefa envolve uma pesquisa de fatos mais detalhada sobre todos os recursos, restrições, suposições e outros fatores que devem ser considerados na determinação da meta de análise de dados e do plano do projeto. Na tarefa anterior, seu objetivo é chegar rapidamente ao cerne da situação. Aqui, você deseja expandir os detalhes.

Artefato   | Descrição 
:--------- | ------
1.2.1. Inventário de recursos | Liste os recursos disponíveis para o projeto, incluindo pessoal (especialistas em negócios, especialistas em dados, suporte técnico, especialistas em mineração de dados), dados (extratos fixos, acesso a dados ativos, armazenados ou operacionais), recursos de computação (plataformas de hardware) e software (ferramentas de mineração de dados, outro software relevante).
1.2.2. Requisitos, premissas e restrições | Liste todos os **requisitos** do projeto, incluindo o cronograma de conclusão, a compreensibilidade e a qualidade dos resultados e a segurança, além de questões legais. Como parte desta saída, verifique se você tem permissão para usar os dados. Liste as **premissas** feitas pelo projeto. Essas podem ser suposições sobre os dados que podem ser verificadas durante a mineração de dados, mas também podem incluir suposições não verificáveis sobre os negócios relacionados ao projeto. É particularmente importante listar o último se isso afetará a validade dos resultados. Liste as **restrições** no projeto. Essas podem ser restrições à disponibilidade de recursos, mas também podem incluir restrições tecnológicas, como o tamanho do conjunto de dados que é prático para a modelagem.
1.2.3. Riscos e contingências | Liste os riscos ou eventos que podem atrasar o projeto ou causar uma falha. Liste os planos de contingência correspondentes, que medidas serão tomadas se esses riscos ou eventos ocorrerem.
1.2.4. Terminologia (glossário) | Compile um glossário de terminologia relevante para o projeto. Isso pode incluir dois componentes: (1) Um glossário de terminologia comercial relevante, que faz parte do entendimento comercial disponível para o projeto. A construção deste glossário é um útil exercício de "elicitação do conhecimento" e de educação. (2) Um glossário de terminologia de mineração de dados, ilustrado com exemplos relevantes para o problema de negócios em questão.
1.2.5. Custos e benefícios | Construa uma análise de custo-benefício para o projeto, que compare os custos do projeto com os benefícios potenciais para o negócio, se for bem-sucedido. A comparação deve ser o mais específica possível. Por exemplo, use medidas monetárias em uma situação comercial.

### 1.3. Determinar objetivos de mineração de dados
#### Objetivo
Uma meta de negócios estabelece objetivos na terminologia de negócios. Uma meta de mineração de dados indica os objetivos do projeto em termos técnicos. Por exemplo, a meta de negócios pode ser "Aumentar as vendas do catálogo para clientes existentes". Uma meta de mineração de dados pode ser "Prever quantos widgets um cliente comprará, considerando suas compras nos últimos três anos, informações demográficas (idade, salário, cidade etc.) e o preço do item".

Artefato   | Descrição 
:--------- | ------
1.3.1. Objetivos da mineração de dados | Descreva os resultados pretendidos do projeto que permitem alcançar os objetivos de negócios.
1.3.2. Critérios de sucesso da mineração de dados | Defina os critérios para um resultado bem-sucedido do projeto em termos técnicos - por exemplo, um certo nível de precisão preditiva ou um perfil de propensão à compra com um determinado grau de "elevação". Como nos critérios de sucesso nos negócios, pode ser necessário descrevê-los em termos subjetivos, caso em que a pessoa ou pessoas que fazem o julgamento subjetivo devem ser identificadas.

### 1.4. Produzir plano de projeto
#### Objetivo
Descreva o plano pretendido para atingir as metas de mineração de dados e, assim, atingir as metas de negócios. O plano deve especificar as etapas a serem executadas durante o restante do projeto, incluindo a seleção inicial de ferramentas e técnicas.

Artefato   | Descrição 
:--------- | ------
1.4.1. Plano de projeto | Liste os estágios a serem executados no projeto, juntamente com sua duração, recursos necessários, entradas, saídas e dependências. Sempre que possível, explique as iterações em larga escala no processo de mineração de dados - por exemplo, repetições das fases de modelagem e avaliação. Como parte do plano do projeto, também é importante analisar as dependências entre o cronograma e os riscos. Marque os resultados dessas análises explicitamente no plano do projeto, idealmente com ações e recomendações se os riscos forem manifestos. Nota: o plano do projeto contém planos detalhados para cada fase. Decida nesse momento qual estratégia de avaliação será usada na fase de avaliação. O plano do projeto é um documento dinâmico, no sentido de que, ao final de cada fase, é necessária uma revisão do progresso e das realizações e uma atualização correspondente do plano do projeto. Pontos de revisão específicos para essas atualizações fazem parte do plano do projeto.
1.4.2. Avaliação inicial de ferramentas e técnicas | No final da primeira fase, uma avaliação inicial de ferramentas e técnicas deve ser realizada. Aqui, por exemplo, você seleciona uma ferramenta de mineração de dados que suporta vários métodos para diferentes estágios do processo. É importante avaliar ferramentas e técnicas no início do processo, pois a seleção de ferramentas e técnicas pode influenciar todo o projeto.

## 2. Entendimento dos dados
### 2.1. Coletar dados iniciais
#### Objetivo
Adquira os dados (ou acesso aos dados) listados nos recursos do projeto. Essa coleção inicial inclui o carregamento de dados, se necessário para o entendimento dos dados. Por exemplo, se você usar uma ferramenta específica para entender os dados, faz todo o sentido carregar seus dados nessa ferramenta. Esse esforço possivelmente leva a etapas iniciais de preparação de dados. Nota: se você adquirir várias fontes de dados, a integração é um problema adicional, aqui ou na fase posterior da preparação de dados.

Artefato   | Descrição 
:--------- | ------
2.1.1. Relatório inicial de coleta de dados | Liste os conjuntos de dados adquiridos, juntamente com seus locais, os métodos usados para adquiri-los e quaisquer problemas encontrados. Registre os problemas encontrados e quaisquer resoluções alcançadas. Isso ajudará na replicação futura deste projeto ou na execução de projetos futuros semelhantes.

### 2.2. Descrever dados
#### Objetivo
Examine as propriedades "brutas" ou "superficiais" dos dados adquiridos e relate os resultados.

Artefato   | Descrição 
:--------- | ------
2.2.1. Relatório de descrição de dados | Descreva os dados que foram adquiridos, incluindo o formato dos dados, a quantidade de dados (por exemplo, o número de registros e campos em cada tabela), as identidades dos campos e quaisquer outros recursos de superfície que foram descobertos. Avalie se os dados adquiridos atendem aos requisitos relevantes.

### 2.3. Explorar dados
#### Objetivo
Esta tarefa aborda questões de mineração de dados usando técnicas de consulta, visualização e relatório. Isso inclui a distribuição de relacionamentos dos principais atributos (por exemplo, o atributo de destino de uma tarefa de previsão) entre pares ou um pequeno número de atributos, resultados de agregações simples, propriedades de subpopulações significativas e análises estatísticas simples. Essas análises podem abordar diretamente os objetivos de mineração de dados; eles também podem contribuir ou refinar a descrição dos dados e os relatórios de qualidade, além de alimentar as etapas de transformação e de preparação de dados necessárias para análises adicionais.

Artefato   | Descrição 
:--------- | ------
2.3.1. Relatório de exploração de dados | Descreva os resultados desta tarefa, incluindo as primeiras descobertas ou hipóteses iniciais e seu impacto no restante do projeto. Se apropriado, inclua gráficos e plotagens para indicar características de dados que sugerem um exame mais aprofundado de subconjuntos de dados interessantes.

### 2.4. Verificar a qualidade dos dados
#### Objetivo
Examine a qualidade dos dados, abordando questões como: Os dados estão completos (abrange todos os casos necessários)? Está correto ou contém erros e, se houver erros, quão comuns são? Existem valores ausentes nos dados? Em caso afirmativo, como eles são representados, onde ocorrem e quão comuns são?

Artefato   | Descrição 
:--------- | ------
2.4.1. Relatório de qualidade de dados | Listar os resultados da verificação da qualidade dos dados; se houver problemas de qualidade, liste as possíveis soluções. As soluções para problemas de qualidade dos dados geralmente dependem muito dos dados e do conhecimento comercial.

## 3. Preparação dos dados
Artefato   | Descrição 
:--------- | ------
3.0.1. Conjunto de Dados | Estes são os conjuntos de dados produzidos pela fase de preparação de dados, que serão usados para modelar ou para o principal trabalho de análise do projeto.
3.0.2. Descrição do conjunto de dados | Descreva o (s) conjunto (s) de dados que serão usados para a modelagem e o trabalho de análise principal do projeto.

### 3.1. Selecionar dados
#### Objetivo
Decida sobre os dados a serem usados para análise. Os critérios incluem relevância para as metas de mineração de dados, qualidade e restrições técnicas, como limites no volume ou tipos de dados. Observe que a seleção de dados abrange a seleção de atributos (colunas) e a seleção de registros (linhas) em uma tabela.

Artefato   | Descrição 
:--------- | ------
3.1.1. Justificativa para inclusão / exclusão de dados | Liste os dados a serem incluídos / excluídos e os motivos dessas decisões.

### 3.2. Limpar dados
#### Objetivo
Aumente a qualidade dos dados para o nível exigido pelas técnicas de análise selecionadas. Isso pode envolver a seleção de subconjuntos limpos de dados, a inserção de padrões adequados ou técnicas mais ambiciosas, como a estimativa de dados ausentes por modelagem.

Artefato   | Descrição 
:--------- | ------
3.2.1. Relatório de limpeza de dados | Descreva quais decisões e ações foram tomadas para solucionar os problemas de qualidade dos dados relatados durante a tarefa Verificar qualidade dos dados da fase Entendimento de dados. As transformações dos dados para fins de limpeza e o possível impacto nos resultados da análise devem ser consideradas.

### 3.3. Construir dados
#### Objetivo
Esta tarefa inclui operações construtivas de preparação de dados, como a produção de atributos derivados ou novos registros inteiros ou valores transformados para atributos existentes.

Artefato   | Descrição 
:--------- | ------
3.3.1. Atributos derivados | Atributos derivados são novos atributos construídos a partir de um ou mais atributos existentes no mesmo registro. Exemplo: area = comprimento * largura.
3.3.2. Registros gerados | Descreva a criação de registros completamente novos. Exemplo: Crie registros para clientes que não fizeram compras durante o ano passado. Não havia razão para ter esses registros nos dados brutos, mas, para fins de modelagem, pode fazer sentido representar explicitamente o fato de que certos clientes fizeram zero compras.

### 3.4. Integrar dados
#### Objetivo
Esses são métodos pelos quais as informações são combinadas de várias tabelas ou registros para criar novos registros ou valores.

Artefato   | Descrição 
:--------- | ------
3.4.1. Dados mesclados | Mesclar tabelas refere-se à união de duas ou mais tabelas que possuem informações diferentes sobre os mesmos objetos. Exemplo: uma cadeia de varejo possui uma tabela com informações sobre as características gerais de cada loja (por exemplo, espaço físico, tipo de shopping), outra tabela com dados de vendas resumidos (por exemplo, lucro, porcentagem de variação nas vendas do ano anterior) e outra com informações sobre a demografia da área circundante. Cada uma dessas tabelas contém um registro para cada loja. Essas tabelas podem ser mescladas em uma nova tabela com um registro para cada loja, combinando campos das tabelas de origem. Os dados mesclados também abrangem agregações. Agregação refere-se a operações nas quais novos valores são calculados resumindo informações de vários registros e / ou tabelas. Por exemplo, convertendo uma tabela de compras de clientes em que há um registro para cada compra em uma nova tabela em que há um registro para cada cliente, com campos como número de compras, valor médio da compra, porcentagem de pedidos cobrados no cartão de crédito, por cento dos itens em promoção etc.

### 3.5. Formatar dados
#### Objetivo
As transformações de formatação se referem principalmente a modificações sintáticas feitas nos dados que não alteram seu significado, mas podem ser requeridas pela ferramenta de modelagem.

Artefato   | Descrição 
:--------- | ------
3.5.1. Dados reformatados | Algumas ferramentas têm requisitos na ordem dos atributos, como o primeiro campo sendo um identificador exclusivo para cada registro ou o último campo sendo o campo de resultado que o modelo deve prever. Pode ser importante alterar a ordem dos registros no conjunto de dados. Talvez a ferramenta de modelagem exija que os registros sejam classificados de acordo com o valor do atributo de resultado. Geralmente, os registros do conjunto de dados são inicialmente ordenados de alguma forma, mas o algoritmo de modelagem precisa que eles estejam em uma ordem bastante aleatória. Por exemplo, ao usar redes neurais, geralmente é melhor que os registros sejam apresentados em uma ordem aleatória, embora algumas ferramentas lidem com isso automaticamente sem intervenção explícita do usuário. Além disso, há alterações puramente sintáticas feitas para satisfazer os requisitos da ferramenta de modelagem específica. Exemplos: removendo vírgulas de dentro de campos de texto em arquivos de dados delimitados por vírgula, aparando todos os valores com no máximo 32 caracteres.

## 4. Modelagem
### 4.1. Selecionar técnica de modelagem
#### Objetivo
Como a primeira etapa da modelagem, selecione a técnica de modelagem real a ser usada. Embora você já tenha selecionado uma ferramenta durante a fase de Entendimento comercial, esta tarefa se refere à técnica de modelagem específica, por exemplo, criação de árvore de decisão com 5.0 ou geração de rede neural com propagação reversa. Se várias técnicas forem aplicadas, execute esta tarefa separadamente para cada técnica.

Artefato   | Descrição 
:--------- | ------
4.1.1. Técnica de modelagem | Documente a técnica de modelagem real a ser usada.
4.1.2. Pressupostos de modelagem | Muitas técnicas de modelagem fazem suposições específicas sobre os dados - por exemplo, que todos os atributos têm distribuições uniformes, nenhum valor ausente é permitido, o atributo de classe deve ser simbólico etc. Registre as suposições feitas.

### 4.2. Gerar procedimento ou mecanismo de teste
#### Objetivo
Antes de realmente construir um modelo, precisamos gerar um procedimento ou mecanismo para testar a qualidade e validade do modelo. Por exemplo, em tarefas supervisionadas de mineração de dados, como classificação, é comum usar taxas de erro como medidas de qualidade para modelos de mineração de dados. Portanto, normalmente separamos o conjunto de dados em conjuntos de treinamento e teste, construímos o modelo no conjunto de treinamento e estimamos sua qualidade no conjunto de teste separado.

Artefato   | Descrição 
:--------- | ------
4.2.1. Projeto de teste | Descreva o plano pretendido para treinamento, teste e avaliação dos modelos. Um componente principal do plano é determinar como dividir o conjunto de dados disponível em conjuntos de dados de treinamento, teste e validação.

### 4.3. Construir modelo
#### Objetivo
Execute a ferramenta de modelagem no conjunto de dados preparado para criar um ou mais modelos.

Artefato   | Descrição 
:--------- | ------
4.3.1. Configuração de parâmetros | Com qualquer ferramenta de modelagem, geralmente há um grande número de parâmetros que podem ser ajustados. Liste os parâmetros e seus valores escolhidos, juntamente com a justificativa para a escolha das configurações de parâmetros.
4.3.2. Modelos | Estes são os modelos reais produzidos pela ferramenta de modelagem, não um relatório.
4.3.3. Descrição dos modelos | Descreva os modelos resultantes. Relate a interpretação dos modelos e documente as dificuldades encontradas com seus significados.

### 4.4. Avaliar modelo
#### Objetivo
O engenheiro de mineração de dados interpreta os modelos de acordo com seu conhecimento de domínio, os critérios de sucesso da mineração de dados e o design de teste desejado. O engenheiro de mineração de dados avalia o sucesso da aplicação das técnicas de modelagem e descoberta tecnicamente; ele entra em contato com analistas de negócios e especialistas em domínio posteriormente para discutir os resultados da mineração de dados no contexto de negócios. Observe que esta tarefa considera apenas modelos, enquanto a fase de avaliação também leva em consideração todos os outros resultados que foram produzidos no decorrer do projeto. O engenheiro de mineração de dados tenta classificar os modelos. Ele avalia os modelos de acordo com os critérios de avaliação. Na medida do possível, ele também leva em consideração os objetivos e os critérios de sucesso nos negócios. Na maioria dos projetos de mineração de dados, o engenheiro de mineração de dados aplica uma única técnica mais de uma vez ou gera resultados de mineração de dados com várias técnicas diferentes. Nesta tarefa, ele também compara todos os resultados de acordo com os critérios de avaliação.

Artefato   | Descrição 
:--------- | ------
4.4.1. Avaliação do modelo | Resuma os resultados desta tarefa, liste as qualidades dos modelos gerados (por exemplo, em termos de precisão) e classifique sua qualidade em relação uma à outra.
4.4.2. Revisão da configuração de parâmetros | De acordo com a avaliação do modelo, revise as configurações de parâmetros e ajuste-as para a próxima execução na tarefa Build Model. Itere a construção e a avaliação do modelo até que você acredite firmemente que encontrou os melhores modelos. Documente todas essas revisões e avaliações.

## 5. Avaliação
### 5.1. Avaliar resultados
#### Objetivo
As etapas de avaliação anteriores trataram de fatores como a precisão e a generalidade do modelo. Esta etapa avalia o grau em que o modelo atende aos objetivos de negócios e procura determinar se há algum motivo comercial por que esse modelo é deficiente. Outra opção é testar o (s) modelo (s) em aplicativos de teste no aplicativo real, se restrições de tempo e orçamento permitirem. Além disso, a avaliação também avalia outros resultados de mineração de dados gerados. Os resultados da mineração de dados envolvem modelos necessariamente relacionados aos objetivos de negócios originais e todas as outras descobertas que não estão necessariamente relacionadas aos objetivos de negócios originais, mas também podem revelar desafios, informações ou dicas adicionais para orientações futuras.

Artefato   | Descrição 
:--------- | ------
5.1.1. Avaliação com relação aos critérios de sucesso para o negócio | Resuma os resultados da avaliação em termos de critérios de sucesso nos negócios, incluindo uma declaração final sobre se o projeto já atende aos objetivos iniciais dos negócios.
5.1.2. Modelos aprovados | Após avaliar os modelos com relação aos critérios de sucesso nos negócios, os modelos gerados que atendem aos critérios selecionados se tornam os modelos aprovados.

### 5.2. Processo de revisão
#### Objetivo
Nesse ponto, os modelos resultantes parecem ser satisfatórios e satisfazer as necessidades de negócios. Agora é apropriado fazer uma revisão mais completa do compromisso de mineração de dados, a fim de determinar se há algum fator ou tarefa importante que de alguma forma tenha sido negligenciada. Esta revisão também aborda questões de garantia de qualidade - por exemplo: Criamos o modelo corretamente? Utilizamos apenas os atributos que podemos usar e que estão disponíveis para análises futuras?

Artefato   | Descrição 
:--------- | ------
5.2.1. Revisão do processo | Resuma a revisão do processo e destaque as atividades perdidas e as que devem ser repetidas.

### 5.3. Determinar próximos passos
#### Objetivo
Dependendo dos resultados da avaliação e da revisão do processo, a equipe do projeto decide como a melhor execução. A equipe decide se deve concluir este projeto e seguir para a implantação, iniciar outrasiterações ou configurar novos projetos de mineração de dados. Esta tarefa inclui análises dos recursos restantes e orçamento, que podem influenciar as decisões.

Artefato   | Descrição 
:--------- | ------
5.3.1. Lista de possíveis ações | Liste as possíveis ações adicionais, juntamente com os motivos a favor e contra cada opção.
5.3.2. Decisão (descrição e justificativa) | Descreva a decisão de como proceder, juntamente com a justificativa.

## 6. Aplicação (implantação)
### 6.1. Planejar implantação
#### Objetivo
Esta tarefa obtém os resultados da avaliação e determina uma estratégia para implantação. Se um procedimento geral foi identificado para criar o (s) modelo (s) relevante (s), este procedimento está documentado aqui para implantação posterior.

Artefato   | Descrição 
:--------- | ------
6.1.1. Plano de implantação | Resuma a estratégia de implantação, incluindo as etapas necessárias e como executá-las.

### 6.2. Planejar monitoramento e manutenção
#### Objetivo
O monitoramento e a manutenção são questões importantes se o resultado da mineração de dados se tornar parte dos negócios diários e de seu ambiente. A preparação cuidadosa de uma estratégia de manutenção ajuda a evitar períodos desnecessariamente longos de uso incorreto dos resultados da mineração de dados. Para monitorar a implantação dos resultados da datamining, o projeto precisa de um plano detalhado do processo de monitoramento. Este plano leva em consideração o tipo específico de implantação.

Artefato   | Descrição 
:--------- | ------
6.2.1. Plano monitoramento e manutenção | Resuma a estratégia de monitoramento e manutenção, incluindo as etapas necessárias e como executá-las.

### 6.3. Produzir relatório final
#### Objetivo
No final do projeto, a equipe do projeto redige um relatório final. Dependendo do plano de implantação, este relatório pode ser apenas um resumo do projeto e de suas experiências (se ainda não foram documentados como uma atividade em andamento) ou pode ser uma apresentação final e abrangente dos resultados da mineração de dados.

Artefato   | Descrição 
:--------- | ------
6.3.1. Relatório final | Este é o relatório final escrito do trabalho de mineração de dados. Inclui todos os resultados anteriores, resumindo e organizando os resultados.
6.3.2. Apresentação final | Também haverá frequentemente uma reunião na conclusão do projeto, na qual os resultados são apresentados ao cliente.

### 6.4. Revisar projeto
#### Objetivo
Avalie o que deu certo e o que deu errado, o que foi bem feito e o que precisa ser aprimorado.

Artefato   | Descrição 
:--------- | ------
6.4.1. Documentação da experiência | Resuma a experiência importante adquirida durante o projeto. Por exemplo, armadilhas, abordagens enganosas ou dicas para selecionar as técnicas de mineração de dados mais adequadas em situações semelhantes podem fazer parte desta documentação. Nos projetos ideais, a documentação da experiência também abrange todos os relatórios que foram escritos por membros individuais do projeto durante as fases anteriores do projeto.