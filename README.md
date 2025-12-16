# Tarefa_stackx_-Metodologias-dentro-do-CSS
Para esta tarefa, utlizei a metodologia B.E.M para criar um site de vendas de itens Star Wars
Metodologia CSS – BEM (Block Element Modifier)

Pesquisa e Descrição da Metodologia B.E.M (Block, Element, Modifier) 

Este documento apresenta a pesquisa e a descrição da metodologia de organização de CSS B.E.M (Block, Element, Modifier), conforme solicitado no enunciado da atividade. 

1. Introdução 

Em projetos de desenvolvimento front-end, o CSS pode se tornar difícil de manter à medida que a aplicação cresce. Para solucionar problemas como conflitos de estilos, baixa reutilização e dificuldade de manutenção, surgiram metodologias de organização de CSS. 

Entre as metodologias mais conhecidas estão o B.E.M (Block, Element, Modifier) e o S.M.A.CSS (Scalable and Modular Architecture for CSS). Estas metodologias auxiliam na criação de códigos mais organizados, legíveis e escaláveis. 

2. Metodologia B.E.M 

A metodologia B.E.M (Block, Element, Modifier) é um padrão de nomenclatura de classes CSS que tem como objetivo dividir a interface em componentes independentes, facilitando a manutenção e evolução do código. 

3. Conceitos do B.E.M 

Block (Bloco) 

O Block representa um componente independente da interface, que pode existir sozinho e ser reutilizado em diferentes contextos. 

Element (Elemento) 

O Element é uma parte interna do bloco e depende dele para existir. Sua nomenclatura segue o padrão bloco__elemento. 

Modifier (Modificador) 

O Modifier representa uma variação visual ou de estado de um bloco ou elemento. Sua nomenclatura segue o padrão bloco--modificador ou bloco__elemento--modificador. 

4. Benefícios da Metodologia B.E.M 

- Organização clara do CSS 
- Facilidade de manutenção 
- Redução de conflitos entre estilos 
- Melhor escalabilidade do projeto 

5. Conclusão 

A metodologia B.E.M (Block, Element, Modifier) foi pesquisada e descrita conforme solicitado na atividade. Seu uso contribui significativamente para a organização do código CSS, tornando o projeto mais consistente e de fácil manutenção. 

APLICAÇÃO DENTRO DO PROJETO
1. Onde a metodologia B.E.M foi utilizada 

A metodologia B.E.M foi aplicada na estrutura do HTML do projeto, por meio da padronização e organização das classes CSS. Sua utilização está presente nos componentes principais do layout, como o container do quiz, o formulário, os grupos de perguntas, os campos de entrada, as mensagens de erro e os botões. 

2. Definição do Block no projeto 

O Block principal definido no projeto foi o componente 'quiz', que representa todo o formulário de perguntas e respostas de forma independente. 

Exemplo de aplicação do Block no HTML: 

<main class="card quiz"> 
  ... 
</main> 

3. Utilização dos Elements 

Os Elements representam partes internas do bloco 'quiz' e seguem o padrão bloco__elemento. Eles foram utilizados para identificar e organizar os elementos internos do formulário. 

Exemplos de Elements aplicados no projeto: 

- quiz__title 
- quiz__hint 
- quiz__group 
- quiz__label 
- quiz__input 
- quiz__error 
- quiz__controls 
- quiz__button 
- quiz__result 

Exemplo prático no HTML: 

<section class="group quiz__group"> 
  <label class="quiz__label">Nome completo</label> 
  <input class="quiz__input" type="text"> 
  <div class="error quiz__error"></div> 
</section> 

4. Uso de Modifiers no projeto 

Embora o projeto não utilize modificadores visuais complexos, a metodologia B.E.M foi estruturada de forma a permitir o uso de Modifiers, seguindo o padrão bloco--modificador ou bloco__elemento--modificador, caso sejam necessários em futuras evoluções do projeto. 

5. Como o B.E.M foi aplicado sem alterar o código 

Para garantir que o funcionamento original do projeto fosse preservado, a aplicação do B.E.M foi feita mantendo as classes existentes e adicionando as classes B.E.M em paralelo. Dessa forma, nenhuma lógica JavaScript ou regra de estilo original foi modificada. 
