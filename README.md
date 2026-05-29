## O que eu entendi da atividade

Nessa atividade eu pratiquei conceitos de Programação Orientada a Objetos em Java, como:

* criação de enum
* herança
* encapsulamento
* sobrescrita de métodos
* sobrecarga de métodos

O enum `FurColor` foi criado para representar as cores dos gatos.

A classe `Cat` foi criada herdando da classe `Animal`, aproveitando características que já existiam nela.

## Decisões tomadas

Usei os arquivos `TrainingLevel.java` e `Dog.java` como exemplo para seguir o mesmo padrão do projeto.

Na classe `Cat`:

* defini 7 vidas no início
* usei o `isIndoor` para definir o habitat do gato
* fiz o método `loseLife()` diminuir as vidas sem ficar negativo
* criei dois métodos `move()` com funções diferentes

## Como testei

Criei alguns objetos `Cat` e testei os métodos:

* `makeSound()`
* `sleep()`
* `move()`
* `purr()`
* `loseLife()`
* `displayInfo()`

Também testei o método `fromCode()` do enum para verificar se os códigos funcionavam corretamente.
