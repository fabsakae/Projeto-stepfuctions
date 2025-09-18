# Projeto-step functions
Projeto para o Bootcamp CodeGirls DIO/SantanderOPenAcademy
---
## O que é o AWS Step Functions?
* Step Functions é um orquestrador de fluxos de trabalho serverless na AWS. Ele permite que você conecte e coordene diferentes serviços da nuvem (como funções Lambda, serviços de machine learning, etc.) de uma forma visual e sem precisar escrever código de orquestração complexo. O resultado é um fluxo de trabalho automatizado, robusto e escalável. O ponto-chave é que ele orquestra o que já existe, e não cria os serviços do zero. Ele conecta os microserviços e outros serviços da AWS que você já criou.

***Você pode ter, por exemplo:***

1 - Uma função Lambda para processar um dado.

2 - Um serviço de machine learning para analisar esse dado.

3 - Um serviço de notificação para enviar um e-mail com o resultado.

O Step Functions vai ser o "mapa" que define a ordem em que essas etapas acontecem. Você o configura para dizer: "Primeiro, chame a Lambda. Se a Lambda der certo, chame o serviço de ML. E, no final, envie a notificação."Ele cuida de toda a lógica de estado: se uma etapa falhar, ele pode tentar novamente ou seguir um caminho de erro que você definiu.
