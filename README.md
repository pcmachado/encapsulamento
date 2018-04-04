## [Módulo 1: Programação Java](https://aula-java.github.io/aulas/modulo-1.html)

### [Exercício: Conceitos Avançados: Encapsulamento](https://aula-java.github.io/aulas/avancado/#/2)

1. Clone o projeto
2. Adicione modificadores de visibilidade (todos atributos privados e somente os métodos que necessitam ser públicos definidos como public). Siga as convenções para cada atributo e método. Aplique para as classes CarteiraDeContas, Conta e Cliente. Corrija todas as classes que geraram erros de compilação.
3. Crie Getters e Setters sempre que necessário para os atributos das classes e atualize as classes de teste para que funcionem.
4. Adicione um atributo na classe Cliente de tipo int que se chama identificador. Esse identificador deve ter um valor único para cada instância do tipo Cliente. O primeiro Cliente instanciado tem identificador 1, o segundo 2, e assim por diante. Você deve utilizar os recursos aprendidos para resolver esse problema (crie getter para esse atributo, obviamente que setter não é necessário).
5. Crie uma classe de teste chamada ClienteTest que verifica se o identificador está sendo corretamente atribuído a cada criação de novos clientes (antes de instanciar nenhum cliente, o identificador deve ser Zero e a cada nova instância o identificador deve ser incrementado - faça um método e no mínimo 3 asserções).
6. Faça a classe Cliente sempre receber o CPF para ser instanciada e a classe Conta sempre receber o Cliente (titular) para ser instanciada. Utilize construtores para obter esse resultado. Faça um método privado chamado validaCPF(String cpf): boolean para garantir que a string do CPF tenha apenas 11 caracteres. Verifique que esse método está funcionando na classe ClienteTest através de um novo método para validar o CPF usando o construtor (teste valores válidos e inválidos - e não se esqueça que o método da classe cliente deve permanecer privado). Corrija as demais classes para que o código e teste continuem funcionando corretamente.
