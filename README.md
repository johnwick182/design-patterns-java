<h1>S.O.L.I.D - Java</h1>

<li>Single Responsability: cada classe deve ter uma unica funcao e objetivo</li>
<li>Open/Close: Aberto para extensao, fechado para alteracao</li>
<li>Liskov Subtitution Principle: se a classe A for um subtipo da classe B , poderemos substituir B por A sem interromper o comportamento do nosso programa.</li>
<li>Interface Segregation: Nenhum cliente deve ser forçado a depender de metodos que nao utiliza (interfaces infladas)</li>
<li>Dependency Inversion: Desacoplar logica de negocio das camadas de baixo nivel com o uso de abstracoes</li>

<hr>

<h1>Design Patterns Java (gof)</h1>

<h3>Factory Method</h3>
[see example](src/com/company/designPatterns/factoryMethod)

<p>Definir uma interface para criar um objeto, mas deixar as subclasses decidirem que
classe instanciar. O Factory Method permite adiar a instanciação para subclasses.</p>

<hr>
<h3>Abstract Factory</h3>

[see example](src/com/company/designPatterns/abstractFactory)

<p>Fornecer uma interface para criação de famílias de objetos relacionados ou dependentes sem especificar suas classes concretas.</p>

<hr>
<h3>Adapter</h3>

[see example](src/com/company/designPatterns/adapter)

<p>Converter a interface de uma classe em outra interface, esperada pelos clientes. O
Adapter permite que classes com interfaces incompatíveis trabalhem em conjunto –
o que, de outra forma, seria impossível.</p>

<hr>

<h3>Decorator</h3>

<p>Dinamicamente, agregar responsabilidades adicionais a um objeto. Os Decorators
fornecem uma alternativa flexível ao uso de subclasses para extensão de funcionalidades.</p>

[see example](src/com/company/designPatterns/decorator)

_<p>Fonte: Padrões de Projeto ‑ Soluções Reutilizaveis de Software - 1994
Erich Gamma, John Vlissides, Richard Helm, Ralph Johnson<p>_