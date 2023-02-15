#Automatização - Escala de Pausas

É comum empresas de médio e grande porte terem de organizar as saídas para descanso e/ou almoço de seus funcionários. Aqui, apresento uma situação específica: uma instituição de atendimento ao cliente, por meio de diferentes canais, com diferentes setores resolvendo os problemas que estão sob seus escopos.
O objetivo aqui é apresentar uma proposta de automatização de escalas para essas pausas, de forma democrática e com critérios bem claros, tanto para gestores quanto para colaboradores.
Para contextualizar melhor, os colaboradores que atendem os clientes são o alvo dessas escalas. Eles têm um expediente de trabalho de 06:20 de duração, e devem desfrutar de três pausas ao longo do mesmo: a primeira de 10 minutos; uma segunda de 20 minutos; e uma última, também de 10 minutos. A primeira pausa só pode acontecer após uma hora de trabalho, e a última pausa deve ocorrer no máximo até 01:10 antes do fim do expediente.
Uma possível solução, e a que foi utilizada aqui, tem seu algoritmo descrito a seguir:

* Separar os colaboradores em categorias que incluem as combinações de horário de entrada, setor e canal de atendimento. Cada combinação desses três fatores é uma categoria.
* Dividir os colaboradores de uma categoria em quatro grupos
* Cada grupo desfrutará de suas pausas sempre 10 min após o grupo imediatamente anterior
* A partir da primeira hora de trabalho completa, as primeiras pausas têm início
* A segunda pausa terá início exatamente 01:30 após a primeira pausa
* A última pausa acontecerá após exatamente 02:00 após a segunda pausa

Seguindo esses passos, é possível ter uma operação em atividade sempre com força de trabalho adequada à execução das atividades, sem risco de sobrecarregar algum colaborador ou de ter demandas acumuladas por falta de pessoal.

##Tecnologias
*Python Versão 3.11.1

## Serviços utilizados
* Google Colab

## Como usar
* O código da automatização está disponível nos arquivos do projeto. Com alguns ajustes para adaptar ao cenário específico de cada instituição, é possível reproduzi-lo com certa tranquilidade. Após a escala pronta, sugere-se aqui liberá-la (já que desligamentos e admissões fazem parte da rotina de qualquer empresa) diariamente por meio de sistema próprio ou dashboard, para que os colaboradores possam consultá-la a qualquer momento.

## Features
*Automatização de processos
*List Comprehension
*DataFrames
*Dicionários
*Funções lambda
*Função map()
*Manipulação de data e hora

## Versão
* 1.0.0.0

## Autores
* Matheus Henrique de Souza: @Matheus2510 (https://github.com/Matheus2510)
