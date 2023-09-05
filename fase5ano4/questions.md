CAP 1
Assinale a alternativa que NÃO representa um elemento da Internet das Coisas (IoT):

Middleware: Camada de software, situada entre a camada de aplicação e a camada de software básico dos dispositivos, cujo objetivo é suportar dispositivos e redes heterogêneas e, simultaneamente, oferecer uma visão de sistema único.

---

Qual tipo de rede representa a conexão entre um fone de ouvido Bluetooth e um celular?

WPAN: Wireless Personal Area Network

---

Assinale a alternativa que representa corretamente as três principais camadas de uma arquitetura IoT:

Camada de Aplicação, Camada de Rede e Camada de Percepção

--------------------------------------------------
CAP 2

Qual é a função utilizada no Arduino para ler o valor de uma porta analógica e retornar um valor inteiro equivalente à conversão digital da tensão presente no pino naquele momento?

analogRead

---

Assinale a alternativa que completa corretamente a frase abaixo: “ O segredo dos _____________, está nos _____________, capazes de converter energia de uma natureza em outra, ou seja, um transdutor pode ser usado para converter _____________, uma biológica, química e muitas outras, em uma grandeza elétrica”.

Dispositivos inteligentes, transdutores, grandeza mecânica

---
Esses sensores não necessitam de qualquer conversão, nem de condicionamento de sinal, pois tudo isso já está embutido no próprio silício do sensor, simplificando a quantidade de componentes necessários e reduzindo o tamanho total do circuito. Estamos falando de:  

Sensores digitais puros

--------------------------------------------------
CAP3

Essa ferramenta foi desenvolvida originalmente pela IBM e, hoje em dia, é mantida pela JS Foundation. Sua ampla utilização em aplicações de IoT é devida à facilidade e acessibilidade da ferramenta, que utiliza uma “linguagem” de programação visual, cujas aplicações são programadas em formas de fluxo de dados e funciona tanto local como na nuvem e até mesmo em dispositivos como a Raspberry Pi, BeagleBone e em dispositivos com Android. Estamos falando de:

Node-RED

---

Na aba de debug, no Node-RED, estarão todas as mensagens que os nós de debug irão exibir que receberam durante o fluxo. Com ela aberta, pressione mais algumas vezes no botão do inject e veja o time stamp sendo impresso, semelhante ao monitor serial do Arduino, para modificar o nome do nó e organizar o fluxo, modificamos a característica de:

Name (label)

---

"Este é o protocolo mais utilizado no mundo da Internet das Coisas, foi inventado em 1999 pensando na necessidade de uma comunicação que consumisse pouca bateria e com o mínimo de banda possível para conectar oleodutos utilizando satélites". Estamos falando de:

MQTT
--------------------------------------------------
CAP4

Em relação à sincronização de processos distribuídos, assinale a alternativa correta:

Em um sistema distribuído, frequentemente, precisamos saber qual é o estado do processo A, quando o processo B está em determinado ponto de sua execução, mas não podemos contar apenas com os relógios físicos individuais de cada máquina para saber o que é verdade ao mesmo tempo.
              

---

Um cliente quer sincronizar seu relógio com um servidor de tempo (método de Christian). Ele grava os tempos de viagem de ida e volta das mensagens e os carimbos de tempo retornados pelo servidor. Qual destas mensagens ele deve usar para configurar seu relógio? <Número da mensagem; tempo de viagem de ida e volta (ms); carimbo de tempo (hh:mm:ss.ms)>: <Mensagem #1; 22; 10:54:23.674>, <Mensagem #2; 24; 10:54:25.450>, <Mensagem #3; 20; 10:54:28.342>, <Mensagem #4; 30; 10:54:29.670> e <Mensagem #5; 26; 10:54:31.230>

Mensagem #3

---

A afirmação "Embora exista um sincronismo que atende a maioria das aplicações, não há garantia nem da compatibilidade dos relógios individuais de cada máquina com o relógio físico, nem da compatibilidade entre os diferentes relógios de cada máquina." refere-se à qual algoritmo/método de sincronização:

Algoritmo de Lamport

---

A afirmação "Normalmente, desprezam-se os horários muito afastados da média, muito atrasados ou muito adiantados." refere-se a qual algoritmo/método de sincronização:

Algoritmo de Berkeley

---

Em relação à sincronização de processos distribuídos, assinale a alternativa correta:

No método de Cristian há necessidade de um relógio central para garantir o sincronismo.
--------------------------------------------------
CAP5

Assinale a alternativa que completa corretamente a frase a seguir: "Um sistema de memória compartilhada distribuída (DSM – Distributed Shared Memory) implementa, _____________, um sistema de memória _____________ sobre um sistema de memória _____________. Além de apresentar uma boa escalabilidade, a DSM torna transparente ao programador o mecanismo de comunicação remota, preservando a fácil programação e a portabilidade típica de um sistema de memória compartilhada.".

logicamente / compartilhada / distribuída

---

Assinale a alternativa correta:

Memória compartilhada distribuída é uma abstração usada para o compartilhamento de dados entre computadores que não compartilham memória física.

---

Assinale a alternativa que contém um exemplo de memória compartilhada distribuída (DSM – Distributed Shared Memory):

Um arquivo mapeado em memória, compartilhado por diversos processos distribuídos, é um exemplo de DSM.

---

Em um sistema distribuído, a memória compartilhada distribuída é:

Uma combinação lógica de memórias físicas nos computadores que constituem o sistema distribuído.
--------------------------------------------------
CAP6

Em relação aos serviços Web, assinale a alternativa correta:

Os serviços Web são cada vez mais importantes nos sistemas distribuídos: eles suportam atividade conjunta na Internet global, incluindo a área fundamental da integração de empresa para empresa (business-to-business, B2B).

---
A arquitetura orientada a serviços (SOA, Service-Oriented Architecture) é:

Um conjunto de princípios de projeto.

---

Assinale a alternativa que completa corretamente a frase a seguir: "A computação em grade também pode ser vista como uma forma de computação em nuvem. Na maioria das situações, os termos são sinônimos, mas a computação em _____________, geralmente, pode ser vista como a precursora do paradigma mais geral da computação em _____________, com tendência para o suporte para aplicativos _____________.

grade / nuvem / científicos
--------------------------------------------------
CAP7

Software que roda na máquina em que o Docker está instalado; o usuário não interage diretamente com esse software". Estamos falando de:

Docker Daemon

---

Usado para criar imagens e contêineres no Docker". Estamos falando de:

Docker Engine

---

É a melhor opção quando se tem uma grande variedade de instâncias de SOs para gerenciar ou quando você precisa executar vários aplicativos em servidores diferentes". Estamos falando de:

Virtual Machine (VM)
--------------------------------------------------
CAP8

Como uma infraestrutura de nuvem, é sustentado pelos pilares: processamento (compute), rede (networking) e armazenamento (storage). Este SO faz uso de APIs com mecanismos comuns de autenticação para realizar tarefas de gerenciamento e provisionamento. "Estamos falando de:

OpenStack

---

Desempenha o papel de sistema operacional no nível de contêineres com a responsabilidade de executar tarefas de orquestração de contêineres”. Estamos falando de:

Kubernetes

---

Assinale a alternativa que completa corretamente a frase a seguir: "O papel do _____________ é utilizar o _____________ para criar contêineres nos nós do _____________ e tem como responsabilidades controlar, gerenciar e monitorar o estado dos contêineres Docker ao longo do cluster.

Kubernetes, Docker, cluster

--------------------------------------------------
CAP9

Dentre os diferentes tipos de saídas, quais não podem ser considerados do subgrupo "Custos Variáveis"?

Vendas de Serviços e Comissionamento.

---

Qual é o nome do processo pelo qual as empresas passam quando tentam transformar seus modelos tradicionais em modelos escaláveis?

Transformação digital.

---

Quais são as três principais categorias que precisamos avaliar para entender se o nosso modelo de negócio pode ou não gerar escala?

Configurações do negócio, entradas e saídas.

---

Por quanto tempo devemos projetar nossas questões financeiras na hora de atribuir um bom planejamento na Configuração do Negócio?

Cinco anos.

---

Qual é a principal diferença entre modelo tradicional e modelo escalável de negócio?

No modelo tradicional, os custos acompanham as receitas, enquanto no modelo escalável a receita cresce muito mais do que os custos.

---

Dentre os diferentes tipos de saídas, quais podem ser consideradas do subgrupo "Investimentos Iniciais"?

Abertura de Empresa, Contabilidade e Desenvolvimento do App/Site.
                
---

Dentre os itens a seguir, quais são considerados "Saídas" no modelo de negócio?

Investimentos Iniciais e Despesas Variáveis.

---

Dentre os itens a seguir, quais são considerados "Entradas" no modelo de negócio?

Venda de Produtos, Venda de Serviços e Comissionamento.
--------------------------------------------------