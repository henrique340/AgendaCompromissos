# AgendaCompromissos

## :memo: Descrição
O projeto Agenda de Compromissos foi feito na linguagem c para manipular um arquivo que contém compromissos de um usuário. Nele é possível adicionar, remover ou ordenar compromissos.
Os compromissos possuem as seguintes informações (Ano, mês, dia, hora, minuto, duração (em horas), prioridade (1 menor e 5 maior), nome do compromisso, descrição e local)

## Funções 
* **Adicionar Compromisso:** Recebe como parâmetros todas as informações do compromissos e pede para o usuário digitar uma a uma a informação que ele deseja adicionar. O compromisso é adicionado ao arquivo entrada.csv, que é o arquivo em que eu estou armazenando todas as informações
*  **Remover Compromisso:** Ele lista todos os compromissos e o usuário escolhe qual compromisso ele deseja excluir
*  **Ordenação por Data:** Essa função compara os anos, meses e dias pelo algoritimo de ordenação Bubble Sort em ordem crescente. A lista de compromissos ordenados é mostrada ao usuário porém o arquivo entrada.csv não é alterado
*  **Ordenação por Data e Horário:** Essa função funciona da mesma forma que a função Ordenação por Data mas é adicinado as horas e os minutos.
*  **Ordenação por Data e Prioridade:** Essa função também funciona como a função Ordenação por Data mas é adicionado a prioridade, em que a prioridade 1 é a menor e 5 é a maior
*  **Ordenação por Local, Prioridade e Duração:** Nessa função, eu ordenei primeiro o local por ordem alfabética e, depois ordenei a prioridade e a duração usando o Bubble Sort de forma decrescente  

## :wrench: Tecnologias utilizadas
* C

## :dart: Status do projeto
* ➕:  In progress

## Próximas implementações
Eu vou adicionar uma GUI para facilitar a vizualização dos compromissos
