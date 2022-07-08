# SOLID

## Single responsability principle

Está relacionado com a possibilidade de mudanças em um classe. É sempre requerido que as classes tenham uma responsabilidade única, sendo assim, ela não terá muitos motivos para mudar

## Open closed principle

Uma classe de estar aberta para extensão e fechada para modificações.
É notório a falta desse princípio quando vemos uma quantidade de ifs mudando o código com base em uma variável de estado. Se um novo estado surgir, será necessário mudar o código para adicionar um novo if, ou seja, uma modificação no código, e não uma extensão.

## Liskov substitution principle

Se S é uma subclasse de T, é possível substituir objetos da classe T por objetos da classe S sem quebrar o comportamento esperado do programa.

## Interface segragation

É fundamental para garantir os outros principios. Uma interface não deve forçar uma classe a implementar coisas que ela não irá utilizar. Interfaces com muitos comportamentos trazem complexidade excesiva para o código. Então é preferível segragar esses comportamentos em interfaces ou classes abstratas.

## Dependency inversion

Abstrações não devem depender de detalhes, não devem depender de implementações concretas. Abstrações devem depender de outras abstrações.
