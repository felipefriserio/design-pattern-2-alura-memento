Estudo de Designs patterns ALURA - Memento

- Usamos o padrão memento para guardarmos estados anteriores de um objeto, como um tipo de rollback ou CTRL + Z


Solução : Quando um contrato sofre alguma alteração, seu estado anterior é guardado em uma lista

- Classe Estado só encapsula o objeto contrato, caso precise ter alguma informação adicional, como um campo data, por exemplo, poderá ser colocado nessa classe;
- Caso não precise dessas informações adicionais, é possível guardar o objeto contrato diretamente no Historico
