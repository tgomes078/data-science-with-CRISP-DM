# A metodologia CRISP-DM

A metodologia CRISP-DM é descrita em termos de um modelo de processo hierárquico, consistindo em conjuntos de tarefas descritas em quatro níveis de abstração (de geral a específica): fase, tarefa genérica, tarefa especializada e instância do processo (consulte a figura 1).

No nível superior, o processo de mineração de dados é organizado em várias fases; cada fase consiste em várias tarefas genéricas de segundo nível. Esse segundo nível é chamado de genérico porque se destina a ser geral o suficiente para cobrir todas as situações possíveis de mineração de dados. As tarefas genéricas devem ser o mais completas e estáveis ​​possível. Meios completos que abrangem todo o processo de mineração de dados e todos os aplicativos possíveis de mineração de dados. Estável significa que o modelo deve ser válido para desenvolvimentos ainda imprevistos, como novas técnicas de modelagem.

O terceiro nível, o nível de tarefa especializada, é o local para descrever como as ações nas tarefas genéricas devem ser realizadas em determinadas situações específicas. Por exemplo, no segundo nível, pode haver uma tarefa genérica chamada dados limpos. O terceiro nível descreve como essa tarefa difere em diferentes situações, como a limpeza de valores numéricos versus a limpeza de valores categóricos, ou se o tipo de problema é clustering ou modelagem preditiva.

A descrição de fases e tarefas como etapas discretas executadas em uma ordem específica representa uma sequência idealizada de eventos. Na prática, muitas das tarefas podem ser executadas em uma ordem diferente, e muitas vezes será necessário voltar repetidamente às tarefas anteriores e repetir determinadas ações. Nosso modelo de processo não tenta capturar todas essas rotas possíveis por meio do processo de mineração de dados, porque isso exigiria um modelo de processo excessivamente complexo.

O quarto nível, a instância do processo, é um registro das ações, decisões e resultados de um compromisso real de mineração de dados. Uma instância do processo é organizada de acordo com as tarefas definidas nos níveis mais altos, mas representa o que realmente aconteceu em um compromisso específico, e não o que acontece em geral.

![Figura 1 - Repartição em quatro níveis da metodologia CRISP-DM](../image/Figura_1_-_Repartição_em_quatro_níveis_da_metodologia_CRISP-DM.png)