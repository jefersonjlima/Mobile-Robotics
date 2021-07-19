# Método de Avaliação

## Cálculo da média:

onde:
- N1 = T1 * 0,7 + Exercícios * 0,3
- N2 = T2 * 0,7 + Exercicios * 0,3
- N3 = T3 * 0.8 + Exercicios * 0,2

# Descrição da Avaliações

## Desafio 01 - Corrida

### Objetivos:

* Introdução aos conceitos de controle em malha-aberta.
* Familiarização com a utilização de sensores, pelo processamento dos sinais medidos.
Arduino
    * Utilização das saídas digitais
    * Familiarização com a execução de tarefas em paralelo

### Material para consulta:

### Avaliação:
* O robô deverá ser mostrado em funcionamento no dia da apresentação.
* Deve ser feito um relatório contendo as principais decisões tomadas e desafios encontrados, assim como uma pequena explicação do funcionamento da robô. Adicione fotos e vídeos do desenvolvimento e experimentos realizados.
* O relatório deve estar disponível na página do grupo até a data de entrega.
Pontuação
* Funcionamento: 5 pontos (Criatividade na resolução do problema, eficácia do mecanismo, software, etc)
Construção: 4 pontos (Mecânica e Acabamento: estrutura rígida, fios organizados, conectores bem feitos, etc)
* Documentação: 3 pontos (Decisões tomadas, figuras ilustrativas, vídeos, etc)


### Tarefas:
1. Locomoção: Desenvolva um robô móvel capaz de realizar um determinado caminho que será selecionado através do menu. A figura abaixo representa os três caminhos que o robô deverá executar. A locomoção deve iniciar e terminar nos pontos demarcados em vermelho.


    OBS: Devem ser utilizados no máximo 2 motores.
    
2. Identificação de cor
* Faça uma montagem utilizando um LDR e 3 LEDs (vermelho, verde, azul) para identificar blocos posicionados à frente do sensor.
    * OBS: Um exemplo de montagem sensor para estimação de cor pode ser visto aqui (observe, no entanto, que a interface do sensor descrito nessa página é para o RCX da Lego, e não para o Arduino).
* Acenda cada um dos LEDs individualmente e verifique o valor das medidas.
    * OBS 1: Digital Pins as Outputs - funções pinMode() e digitalWrite().
    * OBS 2: O grupo é responsável por adquirir os LEDs. Verifique a maneira correta de fazer a ligação (resistores, etc). Caso queira, o grupo pode fazer a montagem utilizando apenas 1 LED (RGB) que emite as três cores.
* Crie uma interface que informe a cor do bloco identificado na tela do Arduino de acordo com os dados coletados pelo sensor.
3. Multitarefa e tomada de decisão: O robô deverá realizar duas tarefas simultaneamente (Referência).
O robô deverá locomover-se por uma trajetória em linha reta. Em um determinado momento, o robô deve identificar a presença de um bloco à sua frente (por exemplo, através de um sensor óptico). O robô deverá tomar uma decisão com base na cor do bloco identificado. Ações possíveis:
* Bloco Azul → vire à direita 90 graus e ande para frente;
* Bloco Verde → vire à esquerda 90 graus e ande para frente;
* Bloco Amarelo → gire 180 graus e ande para frente;
* Bloco Vermelho→ pare e dê um giro de 360 graus (permanecendo parado após o giro).
    * OBS: Após a identificação da cor, o robô deve fazer um pequeno movimento para trás antes de realizar o giro para não mover o bloco.
* Todas as tarefas devem ser interrompidas se o robô não encontrar nenhum bloco no intervalo de 10s.
4. Menu: Todas as tarefas devem ser facilmente acessadas através de um menu. A facilidade de uso desse menu também será avaliado.


## Desafio 02 - Simulação e Telemetria

## Desafio 03 - Localização e Mapeamento



* https://homepages.dcc.ufmg.br/~doug/cursos/doku.php?id=cursos:introrobotica:2019-1:index
