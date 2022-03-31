# Anotações sobre FLEX

é interessante saber que, quando você aplica FLEX em uma determinado elemento os <strong> FILHOS </strong> dele ganham essa propriedade flex, mas não seus netos.


# Display block

Sempre que você coloca essa propriedade em um elemento, faz ele se tornar como se fosse uma caixa, porque alguns elementos possuem padrões de linha etc.

# fLex Wrap

Propriede que permite que os elementos quebrem de linha, caso o limite tenha estourado, daquele bloco, por exemplo: 

supondo que tenhamos 4 divs, e cada uma com tamanho de 50% -> então logo só cabera duas por linha, porém o flex não vai quebrar
e manter todas na mesma linha, ATÉ, passamos a propriedade flex-wrap: wrap -> que faz ele quebrar e agora os itens ficaram alinhadoos
apenas 2 por linha

# Entendendo as propriedades do flex

- flex : 1 1 300px -> 

- flex-grow ->  define o tamanho de uma propriedade dentro do container
- flex-shrink -> Se o tamanho de todos os itens flexíveis for maior que o contêiner flexível, os itens encolherão para caber de acordo com o flex-shrink
- flex-basis ->  Ele define o tamanho da caixa de conteúdo, a menos que seja definido de outra forma com dimensionamento de caixa.

# Curosidades sobre div

Uma div sempre se comporta como elemmento de bloco, então automaticammente ela vai sempre uma pra baixo da outra e nunca do lado

# Flex direction

Por padrão o flex quando aplicado vem no padrão ROW -> isso significa que todos os itens dentro daquele determinado container
vão ficar um do lado do outro, porém você pode modificar isso usando a propriedade :

flex-direction: column -> assim um vai ficar em cima do outro semelhante ao comportamento de baixa
outro ponto interessante é que existe a propriedade reverse o que faz os itens ficarem na ordem reversa do que foi colocado.