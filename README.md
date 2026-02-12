# Usando-o-array-no-JS

Sobre o projeto

Esta aplicação foi criada para ajudar uma quitanda a controlar a entrada e saída de frutas de maneira simples, funcionando diretamente no navegador. Não existe banco de dados nem armazenamento permanente. Se a página for fechada ou atualizada, as informações são perdidas.

O foco é entender como utilizar arrays em JavaScript para guardar e manipular vários itens dentro de uma única variável, além de aprender a refletir essas mudanças na tela por meio do DOM.

Como funciona

O estoque é representado por um array. Cada fruta adicionada entra como um novo item nessa lista. Sempre que algo muda, o sistema atualiza o conteúdo exibido na página para mostrar a situação atual do estoque.

Conceitos aplicados
Array

Estrutura que permite armazenar diversos valores em sequência dentro de uma variável. Em vez de criar uma variável para cada fruta, todas ficam organizadas em uma única lista.

push()

Adiciona um novo item ao final do estoque. É usado quando chega uma fruta nova.

pop()

Remove o último item da lista. Serve para representar a saída de um produto.

length

Mostra quantos itens existem no estoque naquele momento.

join()

Transforma os itens do array em um texto único, facilitando a exibição das frutas na página.

Manipulação do DOM

Sempre que o array é alterado, o sistema modifica os elementos do HTML para que o usuário veja a lista atualizada sem precisar recarregar a página.

Limitações

O sistema é temporário. Atualizou ou fechou o navegador, perdeu tudo. A proposta aqui é aprendizado de lógica e manipulação de dados, não persistência.

Resultado esperado

Ao final, é possível entender claramente:

como guardar vários valores em uma lista,

como inserir e remover itens,

como contar elementos,

e como transformar dados em algo visível para o usuário.
