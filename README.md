Olá, bem vindo ao meu teste!

Este documento descreve como utilizar o sistema proposto e também quais as tecnologias utilizadas na solução.

1. Tecnologias e Metodologinas:

Foram utilizadas as tecnologias Microsoft DotNet Core 3.1, C# como linguagem principal, AWS Lambda, AWS SQS para mensageria e API Rest.
Para organização do projeto foi utilizado DDD.

2. Funcionamento do projeto:

Temos um lambda que faz o disparo a cada 5 segundos de uma mensagem para fila SQS através do lambda (publisher), do outro lado, temos uma api faz o consumo (consumer) deste sqs disponibilizado 
as mensagem para consulta de um front-end (que pode ser em ReactJS).

3. Projetos:

Temos um projeto focado para publicação das mensagens na fila e outro para consumo da mesma.
Segue no repositório um diagrama que ilustra o funcionamento da solução.
