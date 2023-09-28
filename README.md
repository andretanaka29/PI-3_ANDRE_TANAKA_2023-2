# PI-3_ANDRE_TANAKA_2023-2

## Introdução
O projeto do Zênite Solar começou em 2013 ao receber a doação de um casco pela equipe da UFSC(Vento Sul), com isso a equipe do IFSC começou a participar do Desafio Solar Brasil(DSB). O DSB é um projeto de extensão universitária que através de uma corrida de barcos movidos a energia solar, visa o estímulo do desenvolvimento de tecnologia de fontes renováveis para embarcações.
Dentro do DSB existem várias provas, assim, o barco passa por várias situações de funcionamento e em cada situação existe um modo de usar os recursos existentes de melhor maneira. Para controlar o uso desses recursos é necessário um meio de acompanhamento do funcionamento dos sistemas do barco, um sistema de telemetria serve justamente para isso e para poder acompanhar esses dados da telemetria é necessário um sistema de transmissão de dados do barco para a equipe e é onde esse projeto se encaixa.

## Problema
O barco solar da equipe Zênite do IFSC participa da competição Desafio Solar Brasil, para o desenvolvimento dos sistemas do barco e o acompanhamento durante a competição, um sistema de telemetria é importante para a estratégia nas estapas da competição e para identificação de problemas no barco. A necessidade então é como obter esses dados em tempo real enquanto o barco está navegando por alguém que não esteja abordo.

## Objetivo
Este projeto visa implementar um sistema de comunicação sem fio entre uma embarcação solar e um computador.

## Cronograma

| Atividade | Semanas   |
| ----------------------------------------------------------------- | ------------ |
| Definição do projeto | 1, 2 e 3 |
| Descrição do trabalho(Problemática e objetivo) | 3 e 4 |
| Estudo de referências bibliográficas | 5 e 6 |
| Definição dos requesitos de projeto | 5 e 6 |
| Definição do tipo de sistema de transmissão de dados sem fio | 6 e 7 |
| Definição do hardware a ser implementado | 7, 8 e 9 |
| Testes de validação do hardware definido | 10, 11, 12 e 13 |
| Montagem do protótipo | 14, 15 e 16 |
| Testes de validação do protótipo | 17, 18, 19 e 20 |
| Documentação do projeto | 4 até 20 |

## Diagrama de blocos

![Diagrama de blocos PI3 -2](https://github.com/andretanaka29/PI-3_ANDRE_TANAKA_2023-2/assets/45289349/374546f6-34ad-4162-8971-d12ea5927eff)

## Requesitos de projeto
-Alimentação via bateria de 12 V.
-Baixo consumo.
-Para o alcance deve ser considerada a prova de maior distância do DSB, que é de 5 milhas(8 km).
-Usar barramento CAN para aquisição de dados dos sensores.
