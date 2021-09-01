## Definição
<p align = "justify">
O GOMS é um métodos de análise de tarefas que permite a representação do conhecimento necessário para a realização de uma tarefa por parte de um usuário. Nessas representações podemos encontrar goals que são as metas e submetas que o usuário deseja fazer, operators que são as ações que o software permite que o usuário tome e que são diretamente relacionadas com o dispositivo em si, methods que são sequências claras de goals e operators que permitem o usuário concluir uma tarefa, selection rules que são as regras que o usuário pode seguir para decidir qual método usará para atingir uma goal. Dentre as limitações, podemos citar que o GOMS não considera o comportamento do usuário, por exemplo, fadiga, influências do ambiente social ou fatores organizacionais. O GOMS também não considera erros e considera apenas que usuário experientes estajam usando e não usuário iniciantes.
</p>

<p align = "justify">
O CMN-GOMS é um proposta de união entre o GOMS e o KML, que define uma sintaxe padronizada onde há uma única hierarquia estrita de objetivos, onde os operadores são executados estritamente em ordem sequencial e os métodos são representados numa notação semelhante a um pseudocódigo. Essa técnica requer uma estrita estrutura de regras de seleção de operação de método de objetivo. 
</p>

<p align = "justify">
A estrutura é rígida o suficiente para que o avaliador represente as tarefas em um formato de pseudo-código (nenhuma sintaxe formal é ditada). Ele também fornece um guia sobre como formular regras de seleção.
</p>

<p align = "justify">
Este método também pode ser usado para estimar a carga que a tarefa coloca no usuário. Por exemplo, examinar o número de níveis abaixo da árvore de tarefas em que um ramo de objetivo é pode ser usado para estimar a demanda de memória que a tarefa coloca no sistema. O processo deve lembrar informações sobre todos os níveis acima da ramificação atual. Essa técnica é mais flexível do que o modelo de nível de pressionamento de tecla (KLM) porque o pseudocódigo está em uma forma geral. Ou seja, ele pode ser executado para diferentes cenários percorrendo diferentes ramos, enquanto o procedimento KLM é uma lista simples que deve ser recriada para cada tarefa diferente.
</p>

## Análise

<p align = "justify">
Essa é uma análise que busca mapear a sequência e quantidade de objetivos, subobjetivos, métodos e operações utilizados para atingir algumas tarefas de caráter rotineiro do site, foco desse projeto. Cabe destacar que para cada objetivo é partido do princípio que o usuário está na página inicial do site. Abaixo está a lista de objetivos analisados.
</p>

<div align = "justify">
<pre>
GOAL 0: descobrir informações sobre a cidade de Londrina
	GOAL 1: encontrar secção sobre dados relacionados à COVID-19
		OP.1.1: examinar dados sobre casos de COVID-19
        OP.1.2: examinar dados sobre vacinação contra à COVID-19
        OP.1.3: examinar dados sobre as despesas da prefeitura com 
		o programa de vacinação
	GOAL 2: obter informações sobre a cidade
		OP.2.1: examinar texto sobre historia da cidade
		OP.2.2: examinar texto sobre economia
		OP.2.3: examinar texto sobre emancipação
		OP.2.4: examinar texto sobre crescimento
		OP.2.5: examinar dados sobre Londrina
</pre>
</div>

### Referências

> Livro: BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. 1ª edição, Rio de Janeiro: Elsevier, 2010.

### Versionamento

|Versão|Data|Modificação|Autor|
|:--:|:--:|:--:|:--:|
|0.1|25/08|Criação do documento sobre CMN-GOMS|Vitor Diniz|
|0.2|26/08|Modificando e ajustando documento|Vitor Diniz|
|1.0|26/08|Finalizando análise de tarefa CMN-GOMS|Vitor Diniz|
|1.1|27/08|Revisando o documento|Abner Filipe|