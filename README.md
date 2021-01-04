#Simulação de um sistema em tempo real
Esta é uma simulação de sistema em tempo real. A ideia do projeto é implementar o serviço de empacotamento de latas por meio do sistema de laço principal com tratador de interrupções, em que tarefas periódicas estão no laço principal e as tarefas aperiódicas são tratadas como interrupções via software. O processo do sistema passa por 2 etapas, a primeira etapa é responsável por realizar o controle de qualidade do produto, por meio de visão computacional será possível reconhecer qualquer avaria na estrutura física da lata, a segunda etapa é separar as latas de qualidade aceitável das latas danificadas, as primeiras vão ser direcionadas para o empacotamento, já as latas com problemas serão direcionadas para o descarte.

![](SimulacaoSistema.gif)
