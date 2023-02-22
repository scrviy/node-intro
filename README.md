# Introdução ao NodeJS

### O que é NodeJS?
_O nodeJS é como um ambiente de execução JavaScript assíncrono orientado a eventos, o NodeJS é projetado para desenvolvimento de aplicações escaláveis de rede._ **Trecho retirado do site: https://nodejs.org/pt-bt/about/**

---

### Como funciona o NodeJS?
A principal característica do NodeJS é sua execução ser single-thread, ou seja, os recursos computacionais são alocados apenas uma vez pelo tempo que a aplicação estiver sendo executada. Aplicações multi-thread a cada nova requisição, e ela não é executada enquanto a anterior não for finalizada.

Essa thread única é chamada de "Event Loop". Ela trata as requisições como eventos, de maneira assíncrona e não-bloqueável, eliminando a necessidade de filas de processamento e tornando as aplicações mais eficientes e responsivas.

---

### Quais as vantagens de se utilizar NodeJS?

O NodeJS é muito utilizado em aplicações que requerem uma alta escalabilidade, que possam crescer sem perder qualidade, e é por essa questão que devido ao baixo consumo de recursos e à capacidade processar requisições o NodeJS acaba sendo muito valorizado.

Outra vantagem interessante do NodeJS é a capacidade de conseguir manter o ecossistema de aplicações e toda     a base de código em uma só linguagem de programação, nesse caso, o JavaScript. 

### Desvantagens de se trabalhar com NodeJS

- O NodeJS possui o Javascript como linguagem de programação não tipada, mas possível com TypeScript e acaba tendo suas vantagens e desvantagens nesse formato.
- É preciso pensar na escalabilidade do projeto desde o início para desenvolver sistemas distribuídos escalonáveis sem monitoração constante do estado da aplicação.
- Não há nenhum benefício para tarefas ligadas á CPU.