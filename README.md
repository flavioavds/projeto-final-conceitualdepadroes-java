# 👨‍🎓 Apresentação

## Projeto Final Explorando Padrões de Projetos na Pratica com Java - Spring Boot

---
<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;São dois projetos, criados e implementado com padrões Java. Projeto #padroes-de-projetos-na-pratica, Onde foi desenvolvido um robo, e #projetomc.
</p>
<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;A implementação do projetomc, é uma implementação de Produto, Cliente, Endereço, Pagamento, Categoria.
  Onde foi imlementado padrões de:
</p>
- Leitura e entendimento do diagrama de classes <br>
- Leitura e entendimento do diagrama de objetos <br>
 Associações: <br>
&nbsp;&nbsp;&nbsp;&nbsp;o Um para muitos / muitos para um <br>
&nbsp;&nbsp;&nbsp;&nbsp;o Um para um <br>
&nbsp;&nbsp;&nbsp;&nbsp;o Muitos para muitos comum <br>
&nbsp;&nbsp;&nbsp;&nbsp;o Muitos para muitos com classe de associação <br>
&nbsp;&nbsp;&nbsp;&nbsp;o Bidirecionais / direcionadas <br>
- Conceito independente / dependente <br>
- Classe de associação <br>
- Herança <br>
- Enumerações <br>
- Atributos Embedded (ItemPedidoPK) <br>
- Coleções ElementCollection (telefones de um cliente) <br>

--- 
## Estrutura Principal
<h1 align="center">
            <img src="https://github.com/flavioavds/projeto-final-conceitualdepadroes-java/blob/master/projetomc/imagens/estruturaPrincipal.jpg" alt="estruturaPrincipal" width="900"/>
</h1>

## Estrutura de Enumeração
<h1 align="center">
            <img src="https://github.com/flavioavds/projeto-final-conceitualdepadroes-java/blob/master/projetomc/imagens/enumeracaoPrincipal.jpg" alt="enumeracaoPrincipal" width="900"/>
</h1>

## Estrutura de Instanciação
<h1 align="center">
            <img src="https://github.com/flavioavds/projeto-final-conceitualdepadroes-java/blob/master/projetomc/imagens/instanciaModeloPrincipal.jpg" alt="instanciaModeloPrincipal" width="900"/>
</h1>

Além de Gerar uma base de dados relacional automaticamente a partir do modelo conceitual, bem como povoar a base com a instância dada.
--- 
Recuperar os dados e disponibilizá-los por meio de uma API Rest BÁSICA. Os seguintes end points devem ser disponibilizados.
--- 
<p align="justify"> End point Dados <br>
/categorias/{id} Categoria e seus produtos <br>
/clientes/{id} Cliente, seus telefones e seus endereços <br>
/pedidos/{id} Pedido, seu cliente, seu pagamento, seus itens de <br>
pedido, seu endereço de entrega.
</p>
