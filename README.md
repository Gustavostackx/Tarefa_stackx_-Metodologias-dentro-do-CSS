# Tarefa_stackx_-Metodologias-dentro-do-CSS
Para esta tarefa, utlizei a metodologia B.E.M para criar um site de vendas de itens Star Wars
Metodologia CSS – BEM (Block Element Modifier)

Neste projeto foi utilizada a metodologia BEM (Block Element Modifier) para organização e padronização do código CSS.

O BEM é uma metodologia que tem como objetivo tornar o CSS mais legível, reutilizável e fácil de manter, especialmente em projetos que crescem com o tempo.

* Conceitos do BEM

- Block (Bloco)
- Representa um componente independente da interface.
- Exemplo neste projeto: .from
- Element (Elemento)
São partes internas de um bloco, que dependem dele para existir.
São nomeados usando dois underlines __.
Exemplos: .form__title
.form__group
.form__label
.form__input
.form__submit
Modifier (Modificador)
Serve para criar variações de um bloco ou elemento (estado, aparência ou comportamento).
Neste projeto não foi necessário o uso de modificadores, mas um exemplo seria: .form__submit--disabled

* Aplicação do BEM no Projeto

No formulário Star Wars Store, o bloco principal é o .form, que representa o formulário como um todo.
Todos os elementos internos seguem o padrão BEM, garantindo que os estilos fiquem bem organizados e sem conflitos.

Essa abordagem facilita:

- A manutenção do código

- A leitura por outros desenvolvedores

- A escalabilidade do projeto

- A reutilização de componentes

Conclusão:

A metodologia BEM foi escolhida por sua simplicidade e eficiência na organização de estilos CSS.
Seu uso neste projeto garante um código mais estruturado, consistente e preparado paraa futuras avaliações.
