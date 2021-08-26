# O guia do usuário do CRISP-DM
## 1. Entendimento do Negócio
### 1.1. Determinar os objetivos do negócio
##### Objetivo
O primeiro objetivo do analista é entender completamente, de uma perspectiva de negócios, o que o cliente realmente quer realizar. Muitas vezes o cliente tem muitos objetivos e restrições concorrentes que devem ser colocados em equilíbrio. O objetivo do analista é descobrir fatores importantes no início do projeto que pode influenciar o resultado final. Uma conseqüência provável de negligenciar esta etapa seria gastar uma grande esforço para produzir as respostas corretas para as perguntas erradas.

### 1.1.1 Background (Plano de Fundo)
Agrupar as informações conhecidas sobre a situação comercial da organização no início do projeto. Esses detalhes não apenas servem para identificar mais de perto os objetivos de negócios a serem alcançados, mas também servem para identificar recursos, humanos e materiais, que podem ser utilizados ou necessários durante o curso do projeto.

#### Atividades
##### Organização:
- [ ] Desenvolver gráficos organizacionais identificando divisões, departamentos e grupos de projetos. Os gráficos também devem identificar os nomes e responsabilidades dos gerentes.
- [ ] Identificar pessoas chave e seus papéis/funções
- [ ] Identificar um patrocinador interno (pode ser um patrocinador financeiro, um usuário principal ou um especialista)
- [ ] Indicar se existe um comitê diretor e listar seus membros
- [ ] Identificar as unidades de negócios afetadas pelo projeto (ex: Finanças, Marketing, Vendas)

##### Área do problema (domínio):
- [ ] Identificar a área do problema (marketing, atendimento ao cliente, desenvolvimento de negócios, etc.)
- [ ] Descrever o problema em termos gerais 
- [ ] Verificar a situação atual do projeto (por exemplo, verificar se já está claro na unidade de negócios que um projeto de mineração de dados deve ser executado ou se a mineração de dados precisa ser promovida como uma tecnologia chave nos negócios)
- [ ] Esclarecer os pré-requisitos do projeto (por exemplo, qual é a motivação do projeto?
já usa mineração de dados?)
- [ ] Se necessário, preparar apresentações e apresentar o trabalho mineração de dados para os negócios
- [ ] Identificar os grupos-alvo para o resultado do projeto (por exemplo, devemos entregar um relatório para a alta gerência ou um sistema operacional a ser usado por usuários finais ingênuos?)
- [ ] Identificar as necessidades e expectativas dos usuários

##### Solução atual:
- [ ] Descrever qualquer solução usada atualmente para resolver o problema
- [ ] Descrever as vantagens e desvantagens da solução atual e o nível em que ela é aceita pelos usuários

### 1.1.2. Objetivos do negócio
Descreva o objetivo principal do cliente, de uma perspectiva comercial. Além do objetivo de negócio principal, normalmente há um grande número de questões relacionadas que o cliente gostaria de endereçar. Por exemplo, o principal objetivo de negócio pode ser manter os clientes atuais prevendo quando eles tendem a se mudar para um concorrente, enquanto um objetivo secundário pode ser determinar se tarifas mais baixas afetam apenas um segmento específico de clientes.

#### Atividades:
- [ ] Descrever informalmente o problema a ser resolvido [Dicas e técnicas sugeridas](técnicas para auxiliar a descrever o problema em termos gerais)
- [ ] Especificar todas as perguntas de negócio da maneira mais precisa possível
- [ ] Especificar outros requisitos de negócio (por exemplo, a empresa não deseja perder clientes)
- [ ] Especificar os benefícios esperados em termos de negócios (usar termos ou expressões do contexto de negócios)

:zap: *__Cuidado para não definir metas inatingíveis. Torne-as o mais realistas possíveis__*

### 1.1.3. Critérios de sucesso para o negócio
Descreva os critérios para um resultado bem-sucedido ou útil do projeto do ponto de vista do negócio. O critério pode ser bastante específico e prontamente mensurável, como por exemplo a redução da rotatividade de clientes a um determinado nível. Também pode ser geral e subjetivo, como "fornece informações úteis sobre os relacionamentos". Neste último caso, certifique-se de
indicar quem faria o julgamento subjetivo.

#### Atividades:
- [ ] Especificar os critérios de sucesso para o negócio (ex: melhore a taxa de resposta em uma campanha de mala direta em 10% e a taxa de inscrição em 20%)
- [ ] Identificar quem avalia os critérios de sucesso

*__Lembre-se!__*
*Cada um dos critérios de sucesso deve estar relacionado a pelo menos um dos objetivos de negócios especificados.*

*__Boa idéia!__*
*Antes de iniciar a próxima tarefa de "avaliação da situação", você pode analisar experiências anteriores desse problema, internamente, usando CRISP-DM, ou externamente, usando soluções pré-empacotadas.*

### 1.2. Avaliar a situação
##### Objetivo
Essa tarefa envolve uma investigação mais detalhada sobre todos os recursos, restrições, suposições e outros fatores que devem ser considerados na determinação da meta de análise de dados e no desenvolvimento do plano do projeto.

### 1.2.1. Inventário de recursos
Listar os recursos disponíveis para o projeto, incluindo pessoal (especialistas de negócios e de dados, técnicos de suporte, especialistas em mineração de dados), dados (extratos, acesso a dados armazenados ou dados operacionais em tempo real), recursos de computação (plataformas de hardware) e software (ferramentas de mineração de dados, outros softwares relevantes).

#### Atividades
##### Recursos de hardware:
- [ ] Identificar o hardware base
- [ ] Estabelecer a disponibilidade do hardware base para o projeto de mineração de dados
- [ ] Verificar se o cronograma de manutenção de hardware está em conflito com a disponibilidade do hardware para o projeto de mineração de dados
- [ ] Identificar o hardware disponível para a ferramenta de mineração de dados a ser usada (se a ferramenta for conhecida neste estágio)

##### Fontes de dados e conhecimento:
- [ ] Identificar fontes de dados
- [ ] Identificar o tipo de fontes de dados (fontes online, especialistas, documentação escrita etc.)
- [ ] Identificar fontes de conhecimento
- [ ] Identificar o tipo de fontes de conhecimento (fontes online, especialistas, documentação escrita etc.)
- [ ] Verificar as ferramentas e técnicas disponíveis
- [ ] Descrever o conhecimento relevante relevante (informal ou formalmente)

##### Fonte de pessoas
- [ ] Identificar o patrocinador do projeto (se diferente do patrocinador interno, como na Seção 1.1.1)
- [ ] Identificar o administrador do sistema, o administrador de banco de dados e a equipe de suporte técnico para obter mais perguntas
- [ ] Identificar analistas de market, especialistas em mineração de dados e estatísticos e verifique sua disponibilidade
- [ ] Verificar a disponibilidade de especialistas em domínio para fases posteriores

*__Lembre-se!__*
*O projeto pode precisar de equipe técnica em momentos ímpares durante o projeto, por exemplo, durante a transformação de dados.*

### 1.2.2. Requisitos, premissas e restrições
Liste todos os **requisitos** do projeto, incluindo o cronograma de conclusão, compreensibilidade e qualidade dos resultados e segurança, além de questões legais. Como parte desta saída, verifique se você tem permissão para usar os dados.
Liste as **premissas** feitas pelo projeto. Essas podem ser suposições sobre os dados, que podem ser verificadas durante a mineração de dados, mas também podem incluir suposições não verificáveis relacionadas ao projeto. É particularmente importante listar os últimos se eles afetarão a validade dos resultados.
Liste as **restrições** feitas no projeto. Essas restrições podem envolver falta de recursos para executar algumas das tarefas do projeto no tempo necessário, ou pode haver restrições legais ou éticas no uso dos dados ou na solução necessária para executar a tarefa de mineração de dados.

#### Atividades
##### Requisitos:
- [ ] Especificar o perfil do grupo-alvo
- [ ] Capturar todos os requisitos no agendamento
- [ ] Capturar os requisitos de compreensibilidade, precisão, capacidade de implantação, manutenção e repetibilidade
do projeto de mineração de dados e o (s) modelo (s) resultante (s)
- [ ] Capturar os requisitos de segurança, restrições legais, privacidade, relatórios e cronograma do projeto

##### Premissas:
- [ ] Esclarecer todas as premissas (incluindo implícitas) e as explique (por exemplo, para resolver a questão comercial, é necessário um número mínimo de clientes com idade acima de 50 anos)
- [ ] Listar premissas sobre a qualidade dos dados (por exemplo, precisão, disponibilidade)
- [ ] Listar premissas sobre fatores externos (por exemplo, questões econômicas, produtos competitivos, avanços técnicos)
- [ ] Esclarecer premissas que levam a qualquer uma das estimativas (por exemplo, presume-se que o preço de uma ferramenta específica seja inferior a US $ 1.000)
- [ ] Listar todas as premissas sobre a necessidade de entender e descrever ou explicar o modelo (por exemplo, como o modelo e os resultados devem ser apresentados à gerência sênior / patrocinador)

##### Restrições:
- [ ] Verificar as restrições gerais (por exemplo, questões legais, orçamento, prazos e recursos)
- [ ] Verificar os direitos de acesso às fontes de dados (por exemplo, restrições de acesso, senha necessária)
- [ ] Verificar a acessibilidade técnica dos dados (sistemas operacionais, sistema de gerenciamento de dados, formato de arquivo ou banco de dados)
- [ ] Verificar se o conhecimento relevante está acessível
- [ ] Verificar as restrições orçamentárias (custos fixos, custos de implementação etc.)

*__Lembre-se!__*
*A lista de premissas também inclui premissas no início do projeto, ou seja, qual foi o ponto de partida do projeto.*

### 1.2.3. Riscos e contingências
Liste os riscos, ou seja, os eventos que podem ocorrer, impactando o cronograma, o custo ou o resultado. Liste os planos de contingência correspondentes: que medidas serão tomadas para evitar ou minimizar o impacto ou recuperar da ocorrência dos riscos previstos.

#### Atividades
##### Riscos:
- [ ] Identificar os riscos do negócio (por exemplo, o concorrente obtém melhores resultados primeiro)
- [ ] Identificar os riscos organizacionais (por exemplo, o departamento que solicita o projeto não tem financiamento para o projeto)
- [ ] Identificar riscos financeiros (por exemplo, financiamento adicional depende dos resultados iniciais da mineração de dados)
- [ ] Identificar riscos técnicos
- [ ] Identificar riscos que dependem de dados e fontes de dados (por exemplo, baixa qualidade e cobertura)

##### Desenvolver planos de contingência:
- [ ] Determinar as condições sob as quais cada risco pode ocorrer
- [ ] Desenvolver planos de contingência

### 1.2.4. Terminologia (glossário)
Compile um glossário de terminologia relevante para o projeto. Isso deve incluir pelo menos dois componentes:
1. Um glossário de terminologia comercial relevante, que faz parte do entendimento comercial disponível para o projeto
2. Um glossário de terminologia de mineração de dados, ilustrado com exemplos relevantes para o problema de negócios em questão.

#### Atividades:
- [ ] Verificar a disponibilidade prévia de glossários; caso contrário, comece a redigir glossários
- [ ] Converse com especialistas em domínio para entender sua terminologia
- [ ] Familiarize-se com a terminologia no negócio

### 1.2.5. Custos e benefícios
Prepare uma análise de custo-benefício para o projeto, comparando os custos do projeto com os benefícios potenciais para o negócio, se for bem-sucedido.

#### Atividades:
- [ ] Estimar custos para coleta de dados
- [ ] Estimar os custos de desenvolvimento e implementação de uma solução
- [ ] Identificar benefícios (por exemplo, maior satisfação do cliente, ROI e aumento da receita)
- [ ] Estimar custos operacionais

*__Boa idéia!__*
*A comparação deve ser a mais específica possível, pois isso permite que um melhor caso de negócios seja feito.*

:zap: *__Cuidado, lembre-se de identificar os custos ocultos, como extração e preparação repetidas de dados, alterações nos fluxos de trabalho e tempo necessário para o treinamento.__*

## 1.3. Determinar objetivos de mineração de dados
##### Objetivo
Uma meta de negócios estabelece objetivos na terminologia de negócios; uma meta de mineração de dados indica os objetivos do projeto em termos técnicos. Por exemplo, a meta de negócios pode ser "Aumentar as vendas de catálogos para clientes existentes", enquanto uma meta de mineração de dados pode ser "prever quantos widgets um cliente comprará, considerando suas compras nos últimos três anos, informações demográficas relevantes e o preço do item."

### 1.3.1. Objetivos da mineração de dados
Descreva os resultados pretendidos do projeto que permitem alcançar os objetivos de negócios. Observe que essas são normalmente saídas técnicas.

#### Atividades:
- [ ] Traduza as perguntas de negócios para as metas de mineração de dados (por exemplo, uma campanha de marketing requer segmentação de clientes para decidir a quem abordar nesta campanha; o nível / tamanho dos segmentos deve ser especificado).
- [ ] Especifique o tipo de problema de mineração de dados (por exemplo, classificação, descrição, previsão e cluster). Para mais detalhes sobre os tipos de problemas de mineração de dados, consulte o Apêndice 2.

*__Boa idéia!__*
*Pode ser sábio redefinir o problema. Por exemplo, modelar a retenção do produto em vez da retenção do cliente ao direcionar a retenção do cliente fornece resultados tarde demais para afetar o resultado.*

### 1.3.2. Critérios de sucesso da mineração de dados
Defina os critérios para um resultado bem-sucedido do projeto em termos técnicos, por exemplo, um certo nível de precisão preditiva ou um perfil de propensão à compra com um determinado grau de "elevação". Como nos critérios de sucesso nos negócios, pode ser necessário descrevê-los em termos subjetivos, caso em que a pessoa ou pessoas que fazem o julgamento subjetivo devem ser identificadas.

#### Atividades:
- [ ] Especifique critérios para avaliação do modelo (por exemplo, precisão, desempenho e complexidade do modelo)
- [ ] Definir parâmetros de referência para critérios de avaliação
- [ ] Especifique critérios que atendam a critérios subjetivos de avaliação (por exemplo, capacidade de explicação do modelo e dados e informações de marketing fornecidas pelo modelo)

:zap: *__Cuidado, lembre-se de que os critérios de sucesso da mineração de dados são diferentes dos critérios de sucesso nos negócios definidos anteriormente.__*

:zap: *__Cuidado, lembre-se de que é aconselhável planejar a implantação desde o início do projeto.__*

## 1.4. Produzir plano de projeto
##### Objetivo
Descreva o plano pretendido para atingir as metas de mineração de dados e, assim, atingir as metas de negócios.

### 1.4.1. Plano de projeto
Liste os estágios a serem executados no projeto, juntamente com sua duração, recursos necessários, entradas, saídas e dependências. Sempre que possível, explique as iterações de larga escala no processo de mineração de dados, por exemplo, repetições das fases de modelagem e avaliação. Como parte do plano do projeto, também é importante analisar as dependências entre o cronograma e os riscos. Marque explicitamente os resultados dessas análises no plano do projeto, idealmente com ações e recomendações para ações, se os riscos forem manifestos.

Embora essa seja a única tarefa na qual o plano do projeto é nomeado diretamente, ele deve ser consultado continuamente e revisado ao longo do projeto. O plano do projeto deve ser consultado no mínimo sempre que uma nova tarefa é iniciada ou uma nova iteração de uma tarefa ou atividade é iniciada.

#### Atividades:
- [ ] Definir o plano de processo inicial e discuta a viabilidade com todo o pessoal envolvido
- [ ] Combinar todas as metas identificadas e técnicas selecionadas em um procedimento coerente que resolve as questões comerciais e atende aos critérios de sucesso comercial
- [ ] Estimar o esforço e os recursos necessários para alcançar e implantar a solução. (É útil considerar a experiência de outras pessoas ao estimar escalas de tempo para projetos de mineração de dados. Por exemplo, costuma-se postular que 50 a 70% do tempo e esforço em um projeto de mineração de dados são usados na Fase de preparação de dados e 20-30 por cento na fase de compreensão de dados, enquanto apenas 10 a 20 por cento são gastos em cada uma das fases de modelagem, avaliação e entendimento de negócios e 5 a 10 por cento na fase de implantação.)
- [ ] Identificar etapas críticas
- [ ] Marcar pontos de decisão
- [ ] Marcar pontos de revisão
- [ ] Identificar iterações principais

### 1.4.2. Avaliação inicial de ferramentas e técnicas
No final da primeira fase, a equipe do projeto realiza uma avaliação inicial de ferramentas e técnicas. Aqui, é importante selecionar uma ferramenta de mineração de dados que suporte vários métodos para diferentes estágios do processo, pois a seleção de ferramentas e técnicas pode influenciar todo o projeto.

#### Atividades:
- [ ] Criar uma lista de critérios de seleção para ferramentas e técnicas (ou use um existente, se disponível)
- [ ] Escolher possíveis ferramentas e técnicas
- [ ] Avaliar a adequação das técnicas
- [ ] Revisar e priorizar as técnicas aplicáveis de acordo com a avaliação de soluções alternativas

# 2. Entendimento dos dados
## 2.1. Coletar dados iniciais
##### Objetivo
Adquira os dados (ou acesso aos dados) listados nos recursos do projeto. Essa coleção inicial inclui o carregamento de dados, se necessário para o entendimento dos dados. Por exemplo, se você pretende usar uma ferramenta específica para entender os dados, é lógico carregar seus dados nessa ferramenta.

### 2.1.1. Relatório inicial de coleta de dados
Descreva todos os vários dados usados para o projeto e inclua todos os requisitos de seleção para dados mais detalhados. O relatório de coleta de dados também deve definir se alguns atributos são relativamente mais importantes que outros.
Lembre-se de que qualquer avaliação da qualidade dos dados deve ser feita não apenas das fontes de dados individuais, mas também de quaisquer dados resultantes da fusão de fontes de dados. Devido a inconsistências entre as fontes, os dados mesclados podem apresentar problemas que não existem nas fontes de dados individuais.

#### Atividades
##### Planejamento de requisitos de dados:
- [ ] Planejar quais informações são necessárias (por exemplo, apenas para determinados atributos ou informações adicionais específicas)
- [ ] Verificar se todas as informações necessárias (para resolver os objetivos de mineração de dados) estão realmente disponíveis

##### Critério de seleção:
- [ ] Especificar critérios de seleção (por exemplo, quais atributos são necessários para as metas de mineração de dados especificadas? Quais atributos foram identificados como irrelevantes? Quantos atributos podemos lidar com as técnicas escolhidas?)
- [ ] Selecionar tabelas / arquivos de interesse
- [ ] Selecionar dados em uma tabela / arquivo
- [ ] Pensar em quanto tempo um histórico deve ser usado (por exemplo, mesmo que 18 meses de dados estejam disponíveis, apenas 12 meses podem ser necessários para o exercício)

:zap: *__Cuidado, esteja ciente de que os dados coletados de diferentes fontes podem causar problemas de qualidade quando mesclados (por exemplo, arquivos de endereço mesclados a um banco de dados de clientes podem mostrar inconsistências de formato, invalidez de dados etc.).__*

##### Inserção de dados:
- [ ] Se os dados contiverem entradas de texto livre, precisamos codificá-las para modelagem ou queremos agrupar entradas específicas?
- [ ] Como os atributos ausentes podem ser adquiridos?
- [ ] Como podemos extrair da melhor maneira os dados?

*__Boa idéia!__*

*Lembre-se de que algum conhecimento sobre os dados pode estar disponível em fontes não eletrônicas (por exemplo, de pessoas, texto impresso etc.).*

*Lembre-se de que pode ser necessário pré-processar os dados (dados de séries temporais, médias ponderadas etc.).*

## 2.2. Descrever dados
##### Objetivo
Examine as propriedades "brutas" dos dados adquiridos e relate os resultados.

### 2.2.1. Relatório de descrição de dados
Descreva os dados que foram adquiridos, incluindo o formato dos dados, a quantidade dos dados (por exemplo, o número de registros e campos em cada tabela), as identidades dos campos e quaisquer outros recursos de superfície que foram descobertos.

#### Atividades
##### Análise volumétrica de dados:
- [ ] Identificar dados e método de captura
- [ ] Acessar fontes de dados
- [ ] Use análises estatísticas, se apropriado
- [ ] Tabelas de relatórios e suas relações
- [ ] Verificar o volume de dados, número de múltiplos, complexidade
- [ ] Observar se os dados contêm entradas de texto livre

##### Tipos e valores de atributos:
- [ ] Verificar a acessibilidade e disponibilidade de atributos
- [ ] Verificar os tipos de atributo (numérico, simbólico, taxonomia etc.)
- [ ] Verificar intervalos de valores de atributos
- [ ] Analisar correlações de atributos
- [ ] Compreender o significado de cada atributo e valor do atributo em termos de negócios
- [ ] Para cada atributo, calcule as estatísticas básicas (por exemplo, distribuição da computação, média, máximo, min, desvio padrão, variação, modo, assimetria etc.)
- [ ] Analisar estatísticas básicas e relacionar os resultados ao significado em termos de negócios
- [ ] Decidir se o atributo é relevante para a meta específica de mineração de dados
- [ ] Determinar se o significado do atributo é usado consistentemente
- [ ] Entrevistar especialistas do domínio para obter sua opinião sobre a relevância dos atributos
- [ ] Decidir se é necessário equilibrar os dados (com base nas técnicas de modelagem a serem usadas)

###### Chaves:
- [ ] Analisar os principais relacionamentos
- [ ] Verificar a quantidade de sobreposições de valores de atributo-chave nas tabelas

###### Analisar premissas / objetivos:
- [ ] Atualize a lista de premissas, se necessário

## 2.3. Explorar dados
##### Objetivo
Esta tarefa aborda as questões de mineração de dados que podem ser tratadas usando técnicas de consulta, visualização e relatório. Essas análises podem abordar diretamente os objetivos de mineração de dados. No entanto, eles também podem contribuir ou refinar a descrição dos dados e os relatórios de qualidade, além de alimentar as etapas de transformação e preparação de outros dados necessárias antes que análises adicionais possam ocorrer.

### 2.3.1. Relatório de exploração de dados
Descreva os resultados desta tarefa, incluindo as primeiras descobertas ou hipóteses iniciais e seu impacto no restante do projeto. O relatório também pode incluir gráficos e gráficos que indicam características dos dados ou apontam para subconjuntos de dados interessantes, dignos de um exame mais aprofundado.

#### Atividades
##### Exploração de dados:
- [ ] Analisar as propriedades de atributos interessantes em detalhes (por exemplo, estatísticas básicas, subpopulações interessantes)
- [ ] Identificar características de subpopulações

##### Suposições de formulário para análises futuras:
- [ ] Considerar e avalie informações e descobertas no relatório de descrição de dados
- [ ] Formar uma hipótese e identificar ações
- [ ] Transformar a hipótese em uma meta de mineração de dados, se possível
- [ ] Esclarecer os objetivos de mineração de dados ou torne-os mais precisos. Uma pesquisa "cega" não é necessariamente inútil, mas é preferível uma pesquisa mais direcionada aos objetivos de negócios.
- [ ] Realizar análises básicas para verificar a hipótese

## 2.4. Verificar a qualidade dos dados
##### Objetivo
Examine a qualidade dos dados, abordando questões como: Os dados estão completos (abrange todos os casos necessários)? Está correto ou contém erros? Se houver erros, quão comuns eles são? Existem valores ausentes nos dados? Em caso afirmativo, como eles são representados, onde ocorrem e quão comuns são?

### 2.4.1. Relatório de qualidade de dados
Listar os resultados da verificação da qualidade dos dados; se houver problemas de qualidade, liste as possíveis soluções.

#### Atividades
- [ ] Identificar valores especiais e catalogue seu significado

##### Revisar chaves, atributos
- [ ] Verificar a cobertura (por exemplo, se todos os valores possíveis estão representados)
- [ ] Verificar chaves
- [ ] Verificar se os significados dos atributos e valores contidos se encaixam
- [ ] Identificar atributos ausentes e campos em branco
- [ ] Estabelecer o significado de dados ausentes
- [ ] Verificar se há atributos com valores diferentes que tenham significados semelhantes (por exemplo, baixa gordura, dieta)
- [ ] Verificar a ortografia e o formato dos valores (por exemplo, mesmo valor, mas às vezes começando com uma letra minúscula, às vezes com uma letra maiúscula)
- [ ] Verificar se há desvios e decida se um desvio é "ruído" ou pode indicar um fenômeno interessante
- [ ] Verificar a plausibilidade dos valores (por exemplo, todos os campos com os mesmos ou quase os mesmos valores)

*__Boa idéia!__*

*Revise todos os atributos que dão respostas conflitantes com o bom senso (por exemplo, adolescentes com altos níveis de renda).*

*Use gráficos de visualização, histogramas etc. para revelar inconsistências nos dados.*

##### Qualidade de dados em arquivos simples
- [ ] Se os dados estiverem armazenados em arquivos simples, verifique qual delimitador é usado e se ele é usado consistentemente em todos os atributos
- [ ] Se os dados estiverem armazenados em arquivos simples, verifique o número de campos em cada registro para ver se eles coincidem
 
##### Ruído e inconsistências entre fontes
- [ ] Verificar consistências e redundâncias entre fontes diferentes
- [ ] Plano para lidar com o ruído
- [ ] Detectar o tipo de ruído e quais atributos são afetados

*__Boa idéia!__*

*Lembre-se de que pode ser necessário excluir alguns dados, pois eles não apresentam comportamento positivo ou negativo (por exemplo, para verificar o comportamento do empréstimo dos clientes, excluir todos os que nunca fizeram empréstimos, não financiam uma hipoteca residencial, aqueles cuja hipoteca é próximo da maturidade, etc.).*

*Revise se as premissas são válidas ou não, considerando as informações atuais sobre dados e conhecimento comercial.*

# 3. Preparação dos dados
### 3.0.1. Conjunto de Dados
Estes são os conjuntos de dados produzidos pela fase de preparação de dados, usados para modelagem ou para os principais trabalhos de análise do projeto.

### 3.0.2. Descrição do conjunto de dados
Esta é a descrição do(s) conjunto(s) de dados usado para a modelagem ou para o trabalho de análise principal do projeto.

## 3.1. Selecionar dados
##### Objetivo
Decida sobre os dados a serem usados para análise. Os critérios incluem relevância para as metas de mineração de dados, qualidade e restrições técnicas, como limites no volume ou tipos de dados.

### 3.1.1. Justificativa para inclusão / exclusão de dados
Liste os dados a serem usados / excluídos e os motivos dessas decisões.

#### Atividades
- [ ] Coletar dados adicionais apropriados (de diferentes fontes - tanto internas quanto externas)
- [ ] Executar testes de significância e correlação para decidir se os campos devem ser incluídos
- [ ] Reconsiderar Critérios de Seleção de Dados (Consulte a Tarefa 2.1) à luz de experiências de qualidade e exploração de dados (ou seja, pode desejar incluir / excluir outros conjuntos de dados)
- [ ] Reconsiderar os Critérios de Seleção de Dados (consulte a Tarefa 2.1) à luz da experiência da modelagem (ou seja, a avaliação do modelo pode mostrar que outros conjuntos de dados são necessários)
- [ ] Selecionar subconjuntos de dados diferentes (por exemplo, atributos diferentes, apenas dados que atendem a determinadas condições)
- [ ] Considerar o uso de técnicas de amostragem (por exemplo, uma solução rápida pode envolver a divisão de conjuntos de dados de teste e treinamento ou a redução do tamanho do conjunto de dados de teste, se a ferramenta não puder lidar com o conjunto de dados completo. Também pode ser útil ter amostras ponderadas para dar importância diferente para atributos diferentes ou valores diferentes do mesmo atributo.)
- [ ] Documentar a justificativa para inclusão / exclusão
- [ ] Verificar as técnicas disponíveis para amostragem de dados

*__Boa idéia!__*

*Com base nos Critérios de Seleção de Dados, decida se um ou mais atributos são mais importantes que outros e pese os atributos adequadamente. Decida, com base no contexto (por exemplo, aplicativo, ferramenta etc.), como lidar com a ponderação.*

## 3.2. Limpar dados
##### Objetivo
Aumente a qualidade dos dados para o nível exigido pelas técnicas de análise selecionadas. Isso pode envolver a seleção de subconjuntos limpos de dados, a inserção de padrões adequados ou técnicas mais ambiciosas, como a estimativa de dados ausentes por modelagem.

### 3.2.1. Relatório de limpeza de dados
Descreva as decisões e ações que foram tomadas para solucionar os problemas de qualidade dos dados relatados durante a tarefa Verificar qualidade dos dados. Se os dados forem usados no exercício de mineração de dados, o relatório deve abordar questões pendentes de qualidade de dados e que possível efeito isso pode ter sobre os resultados.

#### Atividades
- [ ] Reconsiderar como lidar com qualquer tipo de ruído observado
- [ ] Corrigir, remover ou ignorar ruídos
- [ ] Decidir como lidar com valores especiais e seu significado. A área de valores especiais pode dar origem a muitos resultados estranhos e deve ser cuidadosamente examinada. Exemplos de valores especiais podem surgir através da realização de resultados de uma pesquisa em que algumas perguntas não foram feitas ou não foram respondidas. Isso pode resultar em um valor de 99 para dados desconhecidos. Por exemplo, 99 para estado civil ou afiliação política. Valores especiais também podem surgir quando os dados são truncados - por exemplo, 00 para pessoas de 100 anos ou todos os carros com 100.000 km no odômetro.
- [ ] Reconsiderar os Critérios de seleção de dados (consulte a Tarefa 2.1) à luz das experiências de limpeza de dados (ou seja, você pode incluir / excluir outros conjuntos de dados).

*__Boa idéia!__*

*Lembre-se de que alguns campos podem ser irrelevantes para as metas de mineração de dados e, portanto, o ruído nesses campos não tem significado. No entanto, se o ruído for ignorado por esses motivos, ele deve ser totalmente documentado, pois as circunstâncias podem mudar mais tarde.*

## 3.3. Construir dados
##### Objetivo
Esta tarefa inclui operações construtivas de preparação de dados, como produção de atributos derivados, preenchimento de novos registros ou valores transformados para atributos existentes.

#### Atividades
- [ ] Verificar os mecanismos de construção disponíveis com a lista de ferramentas sugeridas para o projeto
- [ ] Decidir se é melhor executar a construção dentro ou fora da ferramenta (ou seja, mais eficiente, exata e repetível)
- [ ] Reconsiderar os Critérios de Seleção de Dados (consulte a Tarefa 2.1) à luz das experiências de construção de dados (ou seja, você pode incluir / excluir outros conjuntos de dados)

### 3.3.1. Atributos derivados
Atributos derivados são novos atributos construídos a partir de um ou mais atributos existentes no mesmo registro. Um exemplo pode ser: area = length * width.

Por que precisamos construir atributos derivados durante o curso de uma investigação de mineração de dados? Não se deve pensar que apenas dados de bancos de dados ou outras fontes devem ser usados na construção de um modelo. Atributos derivados podem ser construídos porque:

*  O conhecimento de base nos convence de que algum fato é importante e deve ser representado, embora atualmente não tenhamos nenhum atributo para representá-lo.
*  O algoritmo de modelagem em uso lida apenas com certos tipos de dados - por exemplo, estamos usando linear
regressão e suspeitamos que existem certas não linearidades que não serão incluídas no modelo
*  O resultado da fase de modelagem sugere que certos fatos não estão sendo cobertos

#### Atividades
##### Atributos derivados:
- [ ] Decidir se algum atributo deve ser normalizado (por exemplo, ao usar um algoritmo de cluster com idade e renda, em determinadas moedas, a renda será dominada)
- [ ] Considerar adicionar novas informações sobre a importância relevante dos atributos adicionando novos atributos (por exemplo, pesos de atributos, normalização ponderada)
- [ ] Como os atributos ausentes podem ser construídos ou imputados? [Decida o tipo de construção (por exemplo, agregado, média, indução).]
- [ ] Adicionar novos atributos aos dados acessados

*__Boa idéia!__*

*Antes de adicionar Atributos Derivados, tente determinar se e como eles facilitam o processo do modelo ou facilitam o algoritmo de modelagem. Talvez “renda por pessoa” seja um atributo melhor / mais fácil de usar do que “renda por família”. Não derive atributos simplesmente para reduzir o número de atributos de entrada.*

*Outro tipo de atributo derivado é a transformação de atributo único, geralmente executada para atender às necessidades das ferramentas de modelagem.*

##### Transformações de atributo único:
- [ ] Especificar as etapas de transformação necessárias em termos de recursos de transformação disponíveis (por exemplo, alterar uma classificação de um atributo numérico)
- [ ] Executar etapas de transformação

*__Boa idéia!__*

*As transformações podem ser necessárias para alterar intervalos para campos simbólicos (por exemplo, idades para faixas etárias) ou campos simbólicos ("definitivamente sim", "sim", "não sei", "não") para valores numéricos. Ferramentas de modelagem ou algoritmos geralmente exigem isso.*

### 3.3.2. Registros gerados
Registros gerados são registros completamente novos, que adicionam novos conhecimentos ou representam novos dados que não são representados de outra forma (por exemplo, tendo segmentado os dados, pode ser útil gerar um registro para representar o membro prototípico de cada segmento para processamento adicional).

#### Atividades
- [ ] Verificar as técnicas disponíveis, se necessário (por exemplo, mecanismos para construir protótipos para cada segmento de dados segmentados).

## 3.4. Integrar dados
##### Objetivo
Estes são métodos para combinar informações de várias tabelas ou outras fontes de informações para criar novos registros ou valores.

### 3.4.1. Dados mesclados
Mesclar tabelas refere-se à união de duas ou mais tabelas que possuem informações diferentes sobre os mesmos objetos. Nesse estágio, também pode ser aconselhável gerar novos registros. Também pode ser recomendado gerar valores agregados.

Agregação refere-se a operações em que novos valores são calculados resumindo informações de vários registros e / ou tabelas.

#### Atividades
- [ ] Verificar se os recursos de integração são capazes de integrar as fontes de entrada conforme necessário
- [ ] Integrar fontes e armazenar resultados
- [ ] Reconsiderar os Critérios de Seleção de Dados (consulte a Tarefa 2.1) à luz das experiências de integração de dados (ou seja, você pode incluir / excluir outros conjuntos de dados)

*__Boa idéia!__*

*Lembre-se de que alguns conhecimentos podem estar contidos em formato não eletrônico.*

## 3.5. Formatar dados
##### Objetivo
As transformações de formatação se referem principalmente a modificações sintáticas feitas nos dados que não alteram seu significado, mas podem ser requeridas pela ferramenta de modelagem.

### 3.5.1. Dados reformatados
Algumas ferramentas têm requisitos na ordem dos atributos, como o primeiro campo sendo um identificador exclusivo para cada registro ou o último campo sendo o campo de resultado que o modelo deve prever.

#### Atividades
##### Reorganizando atributos:
- [ ] Algumas ferramentas têm requisitos na ordem dos atributos, como o primeiro campo sendo um identificador exclusivo para cada registro ou o último campo sendo o campo de resultado que o modelo deve prever.
 
##### Reordenando registros:
- [ ] Pode ser importante alterar a ordem dos registros no conjunto de dados. Talvez a ferramenta de modelagem exija que os registros sejam classificados de acordo com o valor do atributo de resultado.

##### Valor dentro da reformatação:
- [ ] Essas são mudanças puramente sintáticas feitas para satisfazer os requisitos da ferramenta de modelagem específica
- [ ] Reconsidere os Critérios de Seleção de Dados (consulte a Tarefa 2.1) à luz das experiências de limpeza de dados (ou seja, você pode incluir / excluir outros conjuntos de dados)

# 4. Modelagem
## 4.1. Selecionar técnica de modelagem
##### Objetivo
Como o primeiro passo na modelagem, selecione a técnica de modelagem inicial real. Se várias técnicas forem aplicadas, execute esta tarefa separadamente para cada técnica.

Lembre-se de que nem todas as ferramentas e técnicas são aplicáveis a todas as tarefas. Para certos problemas, apenas algumas técnicas são apropriadas (consulte o Apêndice 2, onde as técnicas apropriadas para certos tipos de problemas de mineração de dados são discutidas em mais detalhes). Os "requisitos políticos" e outras restrições limitam ainda mais as opções disponíveis para o engenheiro de mineração de dados. Pode ser que apenas uma ferramenta ou técnica esteja disponível para resolver o problema em questão - e que a ferramenta possa não ser absolutamente a melhor, do ponto de vista técnico.

<img src="/uploads/9ea39a1e55dcf125ded2104d61e8b546/Figura_1_-_Universo_de_Técnicas.png" width="600">

*Figura 1 - Universo de Técnicas*

### 4.1.1. Técnica de modelagem
Registre a técnica de modelagem real usada.

#### Atividade:
- [ ] Decidir a técnica apropriada para o exercício, levando em consideração a ferramenta selecionada.

### 4.1.2. Pressupostos de modelagem
Muitas técnicas de modelagem fazem suposições específicas sobre os dados.

#### Atividades:
- [ ] Definir quaisquer suposições internas feitas pela técnica sobre os dados (por exemplo, qualidade, formato, distribuição)
- [ ] Comparar essas suposições com as do Relatório de descrição de dados
- [ ] Certificar-se de que essas suposições sejam mantidas e retornem à fase de preparação de dados, se necessário

## 4.2. Gerar procedimento ou mecanismo de teste
##### Objetivo
Antes de construir um modelo, é necessário definir um procedimento para testar a qualidade e validade do modelo. Por exemplo, em tarefas supervisionadas de mineração de dados, como classificação, é comum usar taxas de erro como medidas de qualidade para modelos de mineração de dados. Portanto, o design do teste especifica que o conjunto de dados deve ser separado em conjuntos de treinamento e teste. O modelo é construído no conjunto de treinamento e sua qualidade estimada no conjunto de teste.

### 4.2.1. Projeto de teste
Descreva o plano pretendido para treinamento, teste e avaliação dos modelos. Um componente principal do plano é decidir como dividir o conjunto de dados disponível em dados de treinamento, dados de teste e conjuntos de testes de validação.

#### Atividades:
- [ ] Verificar os projetos de teste existentes para cada objetivo de mineração de dados separadamente
- [ ] Decidir as etapas necessárias (número de iterações, número de dobras, etc.)
- [ ] Preparar os dados necessários para o teste

## 4.3. Construir modelo
##### Objetivo
Execute a ferramenta de modelagem no conjunto de dados preparado para criar um ou mais modelos.

### 4.3.1. Configuração de parâmetros
Com qualquer ferramenta de modelagem, geralmente há um grande número de parâmetros que podem ser ajustados. Liste os parâmetros e seus valores escolhidos, juntamente com a justificativa da escolha.

#### Atividades:
- [ ] Definir parâmetros iniciais
- [ ] Documentar os motivos para escolher esses valores

### 4.3.2. Modelos
Execute a ferramenta de modelagem no conjunto de dados preparado para criar um ou mais modelos.

#### Atividades:
- [ ] Executar a técnica selecionada no conjunto de dados de entrada para produzir o modelo
- [ ] Resultados de mineração de dados pós-processo (por exemplo, editar regras, exibir árvores)

### 4.3.3. Descrição dos modelos
Descreva o modelo resultante e avalie sua precisão, robustez e possíveis deficiências esperadas. Relatório sobre a interpretação dos modelos e quaisquer dificuldades encontradas.

#### Atividades:
- [ ] Descrever quaisquer características do modelo atual que possam ser úteis para o futuro
- [ ] Registrar as configurações de parâmetros usadas para produzir o modelo
- [ ] Fornecer uma descrição detalhada do modelo e quaisquer recursos especiais
- [ ] Para modelos baseados em regras, listar as regras produzidas, além de qualquer avaliação por regra ou modelo geral
- [ ] Para modelos opacos, listar qualquer informação técnica sobre a precisão e cobertura do modelo (como topologia de rede neural) e quaisquer descrições comportamentais produzidas pelo processo de modelagem (como precisão ou sensibilidade)
- [ ] Descrever o comportamento e a interpretação do modelo
- [ ] Declarar conclusões sobre padrões nos dados (se houver); Às vezes, o modelo revela fatos importantes sobre os dados sem um processo de avaliação separado (por exemplo, que a saída ou conclusão é duplicada em uma das entradas)

## 4.4. Avaliar modelo
##### Objetivo
O modelo agora deve ser avaliado para garantir que atenda aos critérios de sucesso da mineração de dados e passe nos critérios de teste desejados. Esta é uma avaliação puramente técnica baseada no resultado das tarefas de modelagem.

### 4.4.1. Avaliação do modelo
Resuma os resultados desta tarefa, liste as qualidades dos modelos gerados (por exemplo, em termos de precisão) e classifique sua qualidade em relação uma à outra.

#### Atividades:
- [ ] Avaliar resultados com relação aos critérios de avaliação
- [ ] Resultado do teste de acordo com uma estratégia de teste (por exemplo: Treinamento e teste, validação cruzada, bootstrapping, etc.)
- [ ] Comparar resultados e interpretação da avaliação
- [ ] Criar classificação de resultados com relação aos critérios de sucesso e avaliação
- [ ] Selecionar os melhores modelos
- [ ] Interpretar resultados em termos de negócios (tanto quanto possível nesta fase)
- [ ] Obter comentários sobre modelos por especialistas em domínio ou dados
- [ ] Verificar a plausibilidade do modelo
- [ ] Verificar efeito no objetivo de mineração de dados
- [ ] Verificar o modelo em relação à base de conhecimento fornecida para ver se as informações descobertas são novas e úteis
- [ ] Verificar a confiabilidade do resultado
- [ ] Analisar o potencial de implantação de cada resultado
- [ ] Se houver uma descrição verbal do modelo gerado (por exemplo, por meio de regras), avaliar as regras: elas são lógicas, são viáveis, existem muitas ou poucas, ofendem o bom senso?
- [ ] Avaliar resultados
- [ ] Obter informações sobre por que uma certa técnica de modelagem e determinadas configurações de parâmetros levam a bons / maus resultados

*__Boa idéia!__*

*"Lift Tables" e "Gain Tables" podem ser construídas para determinar quão bem o modelo está prevendo.*

### 4.4.2. Revisão da configuração de parâmetros
De acordo com a avaliação do modelo, revise as configurações de parâmetros e ajuste-as para a próxima execução na tarefa Build Model. Itere a construção e a avaliação do modelo até encontrar o melhor modelo.

#### Atividade:
- [ ] Ajuste os parâmetros para produzir melhores modelos.

# 5. Avaliação
As etapas de avaliação anteriores trataram de fatores como a precisão e a generalidade do modelo. Esta etapa avalia o grau em que o modelo atende aos objetivos de negócios e procura determinar se há algum motivo comercial para que esse modelo seja deficiente. Ele compara os resultados com os critérios de avaliação definidos no início do projeto.

Uma boa maneira de definir as saídas totais de um projeto de mineração de dados é usar a equação:

*__RESULTADOS = MODELOS + DESCOBERTAS__*

Nesta equação, estamos definindo que a produção total do projeto de mineração de dados não é apenas os modelos (embora eles sejam, é claro, importantes), mas também as descobertas, que definimos como qualquer coisa (além do modelo) que é importante no cumprimento dos objetivos da empresa ou importante para levar a novas perguntas, linhas de abordagem ou efeitos colaterais (por exemplo, problemas de qualidade de dados descobertos pelo exercício de mineração de dados). Nota: Embora o modelo esteja diretamente conectado às questões de negócios, as descobertas não precisam estar relacionadas a nenhuma pergunta ou objetivo, desde que sejam importantes para o iniciador do projeto.

## 5.1. Avaliar resultados
##### Objetivo
Esta etapa avalia o grau em que o modelo atende aos objetivos de negócios e procura determinar se há algum motivo comercial para que esse modelo seja deficiente. Outra opção é testar o (s) modelo (s) em aplicativos de teste no aplicativo real, se restrições de tempo e orçamento permitirem.

Além disso, a avaliação também avalia outros resultados de mineração de dados gerados. Os resultados da mineração de dados abrangem modelos relacionados aos objetivos de negócios originais e a todas as outras descobertas. Alguns estão relacionados aos objetivos comerciais originais, enquanto outros podem revelar desafios, informações ou dicas adicionais para orientações futuras.

### 5.1.1. Avaliação com relação aos critérios de sucesso para o negócio
Resuma os resultados da avaliação em termos de critérios de sucesso nos negócios, incluindo uma declaração final relacionada ao fato de o projeto já atender aos objetivos iniciais dos negócios.

#### Atividades:
- [ ] Compreender os resultados da mineração de dados
- [ ] Interpretar os resultados em termos de aplicação
- [ ] Verificar efeito para a meta de mineração de dados
- [ ] Verificar o resultado da mineração de dados com base na base de conhecimento fornecida para ver se as informações descobertas são novas e úteis
- [ ] Avaliar os resultados com relação aos critérios de sucesso nos negócios (ou seja, o projeto alcançou os Objetivos de Negócios originais)
- [ ] Comparar resultados e interpretação da avaliação
- [ ] Classificar resultados com relação aos critérios de sucesso nos negócios
- [ ] Verificar o efeito do resultado no objetivo inicial do aplicativo
- [ ] Determinar se há novos objetivos de negócios a serem abordados posteriormente no projeto ou em novos projetos
- [ ] Recomendações estaduais para futuros projetos de mineração de dados

### 5.1.2. Modelos aprovados
Após acessar os modelos com relação aos critérios de sucesso nos negócios, selecione e aprove os modelos gerados que atendem aos critérios selecionados.

## 5.2. Processo de revisão
##### Objetivo
Nesse ponto, o modelo resultante parece ser satisfatório e parece satisfazer as necessidades de negócios. Agora é apropriado fazer uma revisão mais completa do compromisso de mineração de dados, a fim de determinar se há algum fator ou tarefa importante que de alguma forma tenha sido negligenciada. Nesta fase do exercício de mineração de dados, a Revisão do Processo assume a forma de uma Revisão da Garantia da Qualidade.

### 5.2.1. Revisão do processo
Resuma a revisão do processo e liste as atividades que foram perdidas e / ou devem ser repetidas.

#### Atividades:
- [ ] Forneça uma visão geral do processo de mineração de dados usado
- [ ] Analise o processo de mineração de dados. Para cada etapa do processo, pergunte:
*  Isso foi necessário?
*  Foi executado da melhor maneira?
*  De que maneira isso poderia ser melhorado?
- [ ] Identificar falhas
- [ ] Identifique etapas enganosas
- [ ] Identifique possíveis ações alternativas e / ou caminhos inesperados no processo
- [ ] Revise os resultados da mineração de dados com relação aos critérios de sucesso nos negócios

## 5.3. Determinar próximos passos
##### Objetivo
Com base nos resultados da avaliação e na revisão do processo, a equipe do projeto decide como proceder. As decisões a serem tomadas incluem a conclusão deste projeto e a implantação, o início de novas iterações ou a criação de novos projetos de mineração de dados.

### 5.3.1. Lista de possíveis ações
Liste possíveis ações adicionais, juntamente com os motivos a favor e contra cada opção.

#### Atividades:
- [ ] Analisar o potencial de implantação de cada resultado
- [ ] Estimar o potencial de melhoria do processo atual
- [ ] Verificar os recursos restantes para determinar se eles permitem iterações de processo adicionais (ou se recursos adicionais podem ser disponibilizados)
- [ ] Recomendar continuações alternativas
- [ ] Refinar o plano de processo

### 5.3.2. Decisão (descrição e justificativa)
Descreva as decisões tomadas, juntamente com a justificativa para elas.

#### Atividades:
- [ ] Classificar as ações possíveis
- [ ] Selecionar uma das ações possíveis
- [ ] Documentar os motivos da escolha

# 6. Aplicação (implantação)

## 6.1. Planejar implantação
##### Objetivo
Essa tarefa começa com os resultados da avaliação e termina com uma estratégia para implantação dos resultados da mineração de dados nos negócios.

### 6.1.1. Plano de implantação
Resuma a estratégia de implantação, incluindo as etapas necessárias e como executá-las.

#### Atividades:
- [ ] Resumir resultados implantáveis
- [ ] Desenvolver e avaliar planos alternativos para implantação
- [ ] Decidir por cada resultado distinto de conhecimento ou informação
- [ ] Determinar como o conhecimento ou as informações serão propagados para os usuários
- [ ] Decidir como o uso do resultado será monitorado e seus benefícios medidos (onde aplicável)
- [ ] Decidir para cada modelo implantável ou resultado de software
- [ ] Estabelecer como o resultado do modelo ou software será implantado nos sistemas da organização
- [ ] Determinar como seu uso será monitorado e seus benefícios medidos (onde aplicável)
- [ ] Identificar possíveis problemas durante a implantação (armadilhas a serem evitadas)

## 6.2. Planejar monitoramento e manutenção
##### Objetivo
O monitoramento e a manutenção são questões importantes se os resultados da mineração de dados se tornarem parte dos negócios diários e de seu ambiente. Uma preparação cuidadosa de uma estratégia de manutenção ajuda a evitar períodos desnecessariamente longos de uso incorreto dos resultados da mineração de dados. Para monitorar a implantação dos resultados da mineração de dados, o projeto precisa de um plano detalhado de monitoramento e manutenção. Este plano leva em consideração o tipo específico de implantação.

### 6.2.1. Plano monitoramento e manutenção
Resuma a estratégia de monitoramento e manutenção, incluindo as etapas necessárias e como executá-las.

#### Atividades:
- [ ] Verificar aspectos dinâmicos (ou seja, que coisas podem mudar no ambiente?)
- [ ] Decidir como a precisão será monitorada
- [ ] Determinar quando o resultado ou modelo de mineração de dados não deve mais ser usado. Identifique os critérios (validade, limiar de precisão, novos dados, alteração no domínio do aplicativo etc.) e o que deve acontecer se o modelo ou resultado não puder mais ser usado. (atualizar modelo, configurar novo projeto de mineração de dados etc.).
- [ ] Os objetivos de negócios do uso do modelo mudarão com o tempo? Documentar completamente o problema inicial que o modelo estava tentando resolver.
- [ ] Desenvolver plano de monitoramento e manutenção.

## 6.3. Produzir relatório final
##### Objetivo
No final do projeto, a equipe do projeto redige um relatório final. Dependendo do plano de implantação, este relatório pode ser apenas um resumo do projeto e sua experiência, ou uma apresentação final dos resultados da mineração de dados.

### 6.3.1. Relatório final
No final do projeto, haverá pelo menos um relatório final no qual todos os threads serão reunidos. Além de identificar os resultados obtidos, o relatório também deve descrever o processo, mostrar quais custos foram incorridos, definir desvios do plano original, descrever os planos de implementação e fazer recomendações para trabalhos futuros. O conteúdo detalhado real do relatório depende muito do público-alvo.

#### Atividades:
- [ ] Identificar quais relatórios são necessários (apresentação de slides, resumo de gerenciamento, descobertas detalhadas, explicação de modelos etc.)
- [ ] Analisar até que ponto as metas iniciais de mineração de dados foram cumpridas
- [ ] Identificar grupos-alvo para o relatório
- [ ] Estruturar os tópicos e conteúdo do (s) relatório (s)
- [ ] Selecionar descobertas a serem incluídas nos relatórios
- [ ] Escrever um relatório

### 6.3.2. Apresentação final
Além de um relatório final, pode ser necessário fazer uma apresentação final para resumir o projeto, talvez ao patrocinador da gerência, por exemplo. A apresentação normalmente contém um subconjunto das informações contidas no relatório final, estruturado de uma maneira diferente.

#### Atividades:
- [ ] Decida o grupo-alvo para a apresentação final e determine se eles já terão recebido o relatório final
- [ ] Selecione quais itens do relatório final devem ser incluídos na apresentação final

## 6.4. Revisar projeto
##### Objetivo
Avalie o que deu certo e o que deu errado, o que foi bem feito e o que precisa ser aprimorado.

### 6.4.1. Documentação da experiência
Resuma a experiência importante adquirida durante o projeto. Por exemplo, armadilhas, abordagens enganosas ou dicas para selecionar as técnicas de mineração de dados mais adequadas em situações semelhantes podem fazer parte desta documentação. Nos projetos ideais, a documentação da experiência também abrange todos os relatórios que foram escritos por membros individuais do projeto durante o projeto.

#### Atividades:
- [ ] Entrevistar todas as pessoas importantes envolvidas no projeto e pergunte a elas sobre sua experiência durante o projeto
- [ ] Se os usuários finais nos negócios trabalharem com os resultados da mineração de dados, entreviste-os: Eles estão satisfeitos? O que poderia ter sido feito melhor? Eles precisam de suporte adicional?
- [ ] Resumir o feedback e escreva a documentação da experiência
- [ ] Analisar o processo (coisas que funcionaram bem, erros cometidos, lições aprendidas etc.)
- [ ] Documentar o processo específico de mineração de dados (como os resultados e a experiência de aplicação do modelo podem ser inseridos no processo?)
- [ ] Generalizar a partir dos detalhes para tornar a experiência útil para projetos futuros