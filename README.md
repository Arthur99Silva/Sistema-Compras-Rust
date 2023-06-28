# Sistema-Compras-Rust
![image](https://github.com/Arthur99Silva/Sistema-Compras-Rust/assets/51514914/9950960e-687f-4bd4-8e25-cca1164569b5)
Desenvolver um sistema utilizando a linguagem escolhida pela equipe. O sistema deve apresentar um menu em linha de comando que permite a inclusão, alteração, remoção e visualização dos dados das entidades abaixo. As classes das entidades devem conter apenas atributos e métodos que manipulam os dados. A interface em linha de comando deve ser implementada em uma ou mais classes separadas:

Pessoa (abstrata): nome (String), endereço (String);
Cliente (subclasse de Pessoa): rg (String), data de nascimento (Date);
Produto: código (int), nome (String), valor (float);
Totalizavel (abstrata ou interface): define um método abstrato chamado total que retorna o valor total (float);
Venda (subclasse de Totalizavel): número (int), data (Date), cliente (Cliente), itens (lista ou array de ItemVenda). O método total deve calcular a soma dos totais de cada item.
• ItemVenda (subclasse de Totalizavel): produto (Produto), valor (float), quantidade (int). O valor é copiado do valor do produto no momento da venda, assim, mesmo que o valor do produto mude posteriormente, as vendas mantêm o valor do momento em que foram realizadas). O método total deve calcular o valor vezes a quantidade.

![image](https://github.com/Arthur99Silva/Sistema-Compras-Rust/assets/51514914/9a34b4a0-b143-4a97-bded-29ca92158b7f)

