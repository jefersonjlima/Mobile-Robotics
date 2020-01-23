## Planejamento Aulas - Disciplina Robótica Móvel

### Temas de aula

1. Introdução a Robótica Móvel

        Fundamentos
        Contexto Histórico
        Robótica e Aplicações
        Cinemática e Dinâmica(a)(b)(c)

> a. [Tese](https://www.overleaf.com/project/5c36e5b5f3af951f1e907ccf)
>
> b. [WHEELED MOBILE ROBOTICS - Examples Matlab](https://booksite.elsevier.com/9780128042045/manuscript.php)
>
> c. [Aula UFMG](https://homepages.dcc.ufmg.br/~doug/cursos/lib/exe/fetch.php?media=cursos:introrobotica:2019-1:aula07a-descricao-espacial-transformacoes-parte-1.pdf)
> 
> d. Otimo Cinematica - [Roland_Siegwart,_Illah_R._Nourbakhsh]_Introductio(z-lib.org)

2. Percepção e Ação
        
        Percepção
        Sensores(a)
            Reflexão
        Atuadores
            Ponte H
            Motor Polulu(b)
        Revisão Metodo Bayes
        Introdução ao Filtro de Kalman
        Arduino - Praticas(c)

> a. [Robótica Móvel Campinas](http://www.gasi.sorocaba.unesp.br/assimoes/lectures/rm/)
> 
> b. [Polulu Datasheet](https://www.pololu.com/file/0J1487/pololu-micro-metal-gearmotors-rev-4-2.pdf) 
>
> [Learning Robotics using Python]()

4. Paradigmas de Controle
        
        Revisão Controle Clássico
        Controle Moderno

3. Ambiente de Simulação
        
        Introdução ROS - Robotics Operating System

5. Localização e Mapeamento
    
        Adaptive Monte Carlo localization (AMCL)
        Odometria:
            Visual
                Camera RGB-D
                Calibração
                Aruco
        Localização com Filtro de Kalman

6. Tópicos Extra

        Hidden Markov Model
            Viterbi Algorithm
            Forward e Backward Algorithm
            Baum-Welch Algorithm
            PSO *

> [Triangulation problem solved by PSO](https://booksite.elsevier.com/9780128042045/content/src/Chapter5.zip)


### Tabela de planejamento:

|Aula|Dia| Tipo de Aula|Tópico | Tema| 
|---|---|---|---|---|
|1|02/Março|Teórica|Introdução à Robótica Móvel|Apresentação da Disciplina: Avaliações e Laboratórios|
|2|04/Março|Teórica||Introdução a Robótica: Contexto Histórico|
|3|09/Março|Teórica|| Frameworks modernos para desenvolvimento de projetos de Robótica Móvel |
|4|11/Março|Prática|||
|5|16/Março|Teórica||Cinemática & Dinâmica|
|6|18/Março|Prática|||
|7|23/Março|Teórica||Revisão Python - Simulação|
|8|25/Março|Prática|||
|9|30/Março|Teórica||Revisão Python - Simulação|
|10|01/Abril|Prática|||
|*11|06/Abril|Teórica|Paradigmas de Controle| Revisão Controle Clássico|
|12|08/Abril|Prática|||
|13|13/Abril|Teórica|| Controle Moderno|
|14|15/Abril|Prática|||
|15|22/Abril|Prática||Desafio 01 - Corrida por Controle Remoto|
|16|27/Abril|Teórica|Percepção e Ação||
|17|29/Abril|Prática|||
|-|04-09/Maio|Recesso||Recesso Semana de Capacitação|
|18|11/Maio|Teórica|||
|19|13/Maio|Prática|||
|20|18/Maio|Teórica|Ambiente de Simulação|Introdução ROS - Robotics Operating System|
|21|20/Maio|Prática|||
|*22|25/Maio|Teórica|||
|23|27/Maio|Prática|||
|24|01/Junho|Teórica|Localização e Mapeamento| Localização com Filtro de Kalman|
|25|03/Junho|Prática|||
|26|08/Junho|Teórica|| Adaptive Monte Carlo localization (AMCL)|
|27|10/Junho|Prática|||
|28|15/Junho|Teórica||Odometria Visual|
|29|17/Junho|Prática|||
|30|22/Junho|Teórica|||
|31|24/Junho|Prática|||
|32|01/Julho|Prática|||
|*33|06/Julho|Avaliação|| Desafio 03 - Mapeamento e Localização|
|34|08/Julho|Prática|||
|35|13/Julho|Avaliação| Geral |Reaproveitamento e Desempenho|




## Ementa Referência

Créditos: 4
Horas semanais de atividades teóricas: 4
Oferecimento: A critério da unidade de ensino
 
Pré-Requisitos
MC906/MC886
Ementa
Introdução, histórico e aplicações. Frameworks modernos para desenvolvimento de projetos de Robótica Móvel. Sensores e atuadores. Controle de robôs móveis. Mapeamento e localização. Navegação e planejamento de trajetórias. Coordenação de comportamentos.

Programa
1. Introdução à Robótica Móvel

            a. Introdução à Robótica Móvel  
            b. Contexto histórico
            c. Tipos de robôs móveis  
            d. Estado da arte em Robótica Móvel e aplicações
            e. Componentes de um Robô Móvel
            f. Frameworks modernos para desenvolvimento de projetos de Robótica Móvel

2. Movimento e Controle de robôs móveis

             a. Introdução à locomoção
             b. Tipos de locomoção
             c. Atuadores: definição e tipos
             d. Cinemática
             e. Tipos de controle (Frame, PID, Fuzzy, Neurais)

3. Percepção  

             a. Sensores: definição e tipos
             b. Fusão sensorial

4. Paradigmas de programação de robôs

             a. Reativo
             b. Hierárquico
             c. Híbrido

5. Localização e Mapeamento

             a. Ruídos em sensores e atuadores
             b. Tipos de representação do espaço
             c. Tipos de mapas
             d. Localização de Markov
             e. Localização com Filtro de Kalman
              f. SLAM - localização e mapeamento simultâneos

6. Navegação e planejamento

              a. Planejamento de trajetórias
              b. Desvio de obstáculos

7. Coordenação de tarefas

8. Outros tipos de locomoção

9. Projeto de robôs móveis

10. Tópicos avançados em Robótica Móvel

Bibliografia
1. SIEGWART, R.; NOURBAKHSH, I. Introduction to Autonomous Mobile Robots. Cambridge, Massachusetts: MIT Press, 2004.
2. MURPHY, Robin. R. Introduction to AI robotics. Cambridge, Massachusetts: MIT Press, 2000.
3. THRUN, S., BURGARD, W., FOX, D. Probabilistic Robotics. Cambridge, Massachusetts: MIT Press, 2005.
4. DUDEK, G.; JENKIN, M. Computational Principles of Mobile Robotics. Cambridge, Massachusetts: MIT Press, 2010.
5. RUSSEL, S. .; NORVIG, P. Artificial Intelligence: a modern approach. Prentice Hall. 3rd edition, 2009.
6. MITCHELL, T. Machine Learning. McGrawHill, 1997.