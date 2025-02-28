# Ciclo de um ReAct Agent

Primeiramente, nosso agente irá analisar o prompt do sistema, que deve ser algo do tipo:
    "Você trabalhará sempre no seguinte ciclo: primeiro você pensa sobre o problema dado, então você faz a ação necessária, pausa e e verifica se está condizente com o problema. Fique nesse loop até encontrar a resposta final, na qual você entregará ao sistema"

Uma coisa importante para se adicionar ao prompt inicial são as ferramentas disponíveis para uso, para que o sistema fique completo.

![As imagens a seguir foi um print recortado do vídeo, pois o mesmo não colocou o fluxo na descrição e achei muito interessante para visualização](\ReACtDiagSimp.png "Print do vídeo base do youtube")

Basicamente, temos:
1- Usuário pede algo
2- Agente utiliza LLM para pensar sobre o problema que precisa resolver
3- Utiliza as ferramentas disponíveis para poder solucionar o problema da maneira mais precisa possível
4- 