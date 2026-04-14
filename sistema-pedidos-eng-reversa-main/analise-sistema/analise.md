## Parte 1 – Análise do Sistema Real

O sistema analisado é um site de pedidos online de uma pizzaria. O principal objetivo do sistema é permitir que clientes visualizem o cardápio e realizem pedidos de forma prática pela internet.

Entre as funcionalidades disponíveis, é possível visualizar os produtos, navegar por categorias (como pizzas, bebidas e lanches), adicionar itens ao carrinho e finalizar um pedido. O sistema também apresenta informações como preço e descrição dos produtos.

A interação do usuário com o sistema ocorre de forma simples, através de cliques na interface. O usuário acessa o site, escolhe os produtos desejados, adiciona ao carrinho e segue para a finalização do pedido.

Os produtos estão organizados em categorias, o que facilita a navegação e a busca. Essa organização ajuda o usuário a encontrar rapidamente o que deseja, tornando o uso do sistema mais intuitivo.


## Parte 2 – Análise de Arquitetura

Com base na análise do funcionamento do sistema, é possível perceber que ele segue uma arquitetura em camadas, mesmo sem acesso ao código-fonte.

Existe uma separação entre a interface do usuário (front-end), que é responsável pela exibição dos produtos e interação com o cliente, e o processamento dos dados (back-end), que provavelmente gerencia pedidos, produtos e outras informações.

Essa divisão indica uma separação de responsabilidades, onde cada parte do sistema possui uma função específica. Isso facilita a manutenção e a evolução do sistema.


## Parte 3 – Análise de Design

Em relação ao design do sistema, é possível observar uma coesão razoável, pois as funcionalidades estão organizadas de forma lógica e relacionadas ao objetivo principal do sistema.

O acoplamento aparenta ser moderado, já que as partes do sistema parecem depender umas das outras, principalmente na interação entre o carrinho e os produtos.

A separação de responsabilidades existe, mas pode não ser totalmente clara internamente, já que não temos acesso ao código. Mesmo assim, pela interface, o sistema demonstra uma organização aceitável.