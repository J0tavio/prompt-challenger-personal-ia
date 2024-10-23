# Criando um Assistente de Delivery com AWS Step Functions e Bedrock

## O que aprendi na jornada: 

### Step Functions, o que é?
<p>Imagine um fluxograma digital. 
  É assim que podemos visualizar de forma simples o AWS Step Functions. 
  Essa ferramenta da Amazon Web Services permite que você crie e orchestre fluxos de trabalho complexos, dividindo-os em tarefas menores e definindo a ordem em que elas serão executadas.</p>

### Para que serve?
 * Automatizar processos: Desde aprovações de documentos até pipelines de machine learning, o Step Functions permite automatizar tarefas repetitivas e complexas.
 * Orquestrar microsserviços: Se sua aplicação é dividida em pequenos serviços, o Step Functions pode coordenar a interação entre eles, garantindo que tudo funcione de forma sincronizada.
 * Gerenciar fluxos de trabalho: Você pode visualizar o status de cada etapa do seu processo, identificar gargalos e tomar decisões com base em dados reais.

### Como funciona?
 <p> O Step Functions define os estados do seu fluxo de trabalho. 
   Cada estado representa uma tarefa específica, como enviar um e-mail, processar um pagamento ou chamar uma função Lambda. 
   As transições definem a ordem em que os estados são executados, com base em condições ou resultados anteriores.</p>

## Exemplo: 
Imagine um processo de aprovação de um empréstimo. O fluxo de trabalho poderia ser dividido nos seguintes estados:

1. Receber solicitação: O sistema recebe a solicitação de empréstimo.
2. Verificar crédito: O sistema verifica o score de crédito do solicitante.
3. Aprovar ou rejeitar: Se o score for alto, o empréstimo é aprovado; caso contrário, é rejeitado.
4. Enviar notificação: O sistema envia uma notificação ao solicitante informando a decisão.

## Benefícios:
* Visualização clara: O Step Functions oferece uma interface visual intuitiva para criar e gerenciar seus fluxos de trabalho.
* Escalabilidade: Seus fluxos de trabalho podem escalar automaticamente para lidar com picos de demanda.
* Integração com outros serviços: O Step Functions se integra facilmente com outros serviços da AWS, como Lambda, S3 e DynamoDB.
* Resiliência: Ele oferece mecanismos para lidar com falhas e garantir que seus processos sejam executados de forma confiável.
