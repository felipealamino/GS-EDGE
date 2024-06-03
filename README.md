Grupo: Innotech Hub
Integrates: Felipe Alamino (555819), Davi Vieira (556789), Luca Monteiro (556906)
-> Contextualização GS solicitou a implementação de um sistema de monitoramento ambiental para garantir as condições ideais do Oceano. O projeto envolve a utilização de sensores para medir temperatura, umidade, exibindo os resultados em um display LCD e acionando LEDs e um buzzer para alertar sobre possíveis desvios das condições ideais.

-> Explicação do Projeto O código fornecido utiliza diversos componentes Arduino para realizar o monitoramento ambiental:

Sensor DHT11: Mede a temperatura e umidade do ambiente.
Display LCD: Exibe as informações de temperatura, umidade.
LEDs RGB: Indicam visualmente as condições ambientais, com cores diferentes para cada faixa de valores.
Buzzer: Emite um som de alerta quando as condições ambientais estão fora do ideal.
-> O código é dividido em duas partes principais: Setup: Inicializa os componentes, define os pinos de entrada e saída, e exibe uma mensagem de carregamento no display LCD. Loop: Realiza as seguintes ações em um loop contínuo:

Lê os valores dos sensores de temperatura, umidade.
Exibe as informações no display LCD, alternando entre a umidade e temperatura a cada 2 segundos.
Acende os LEDs de acordo com os valores lidos, indicando se as condições estão dentro do ideal (verde), fora do ideal (vermelho) ou em uma faixa intermediária (amarelo).
Aciona o buzzer quando as condições estão fora do ideal.
Envia os valores lidos para a porta serial para monitoramento. O código também inclui funções auxiliares para acender os LEDs nas cores desejadas, exibir as informações no display LCD e acionar o buzzer.
-> Conclusão O projeto desenvolvido para a Global Solution utiliza tecnologia IOT para monitorar as condições ambientais do local de armazenamento do Oceano . Ao medir temperatura, umidade, o sistema alerta sobre possíveis desvios das condições ideais, permitindo que ajustes sejam feitos para preservar o Oceano. A exibição das informações no display LCD e o uso de LEDs e buzzer facilitam a visualização e compreensão do estado ambiental, tornando o sistema eficiente e fácil de usar.
